<script lang="ts">
	import Header from '../../../components/header/Header.svelte';
	import Repository from '../../../components/repository/Repository.svelte';
	import Repositories from '../../../components/repository/Repositories.svelte';
</script>

<div class="PageRepository Page">
	<Header />

	<Repositories>
		<Repository
			lang="C++"
			name="Genesis Engine"
			description="Short Repository description about the repository"
			author="GMasterHD"
		/>
	</Repositories>
</div>

<style lang="scss">
	@import './Page.sass';
</style>
