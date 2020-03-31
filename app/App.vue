<template>
	<div class="App">
		<ThePostWrite />
		<ThePosts />
	</div>
</template>

<script>
	import ThePosts from "./components/ThePosts.vue";
	import ThePostWrite from "./components/ThePostWrite.vue";

	export default {
		components: {
			ThePostWrite,
			ThePosts
		}
	};
</script>
