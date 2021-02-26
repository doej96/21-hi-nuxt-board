<template lang="pug">
	div.container-wrapper
		header.header-wrapper
			h1 Header
		Nuxt
		footer.footer-wrapper
			p copyright eunjeong
</template>
<script>
export default {
	
}
</script>
<style lang="scss">
	.container-wrapper {
		height: 100vh;
		@include flex($FS, $ST);
		flex-direction: column;
		.header-wrapper {
			background-color: $colorBlack;
			color: $colorWhite;
		}
		.next-wrapper {
			flex-grow: 1;
		}
		.footer-wrapper {
			background-color: $colorBlack;
			color: $colorWhite;
		}
	}
</style>