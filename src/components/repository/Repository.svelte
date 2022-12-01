<script lang="ts">
	export let name: string;
	export let description: string;
	export let lang: string;
	export let author: string;
</script>

<li class="Repository">
	<div class="Content">
		<div class="Main">
			<p class="Name">{name}</p>
			<p class="Description">{description}</p>
		</div>
		<div class="Info">
			<div class="Lang">
				<div />
				<p class="Text">{lang}</p>
				<p class="Text Author">{author}</p>
			</div>
		</div>
	</div>
</li>
<hr class="RepositorySeperator" />

<style lang="scss">
	@import './Repository.sass';
</style>
