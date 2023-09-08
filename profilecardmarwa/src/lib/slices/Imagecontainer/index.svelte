<script>
	/** @type {import("@prismicio/client").Content.ImagecontainerSlice} */
	export let slice;

	console.log(slice);
</script>

<section data-slice-type={slice.slice_type} data-slice-variation={slice.variation}>
	<img src={slice.primary.images.url} />
</section>

<style>
	img {
		width: 100%;
	}
</style>
