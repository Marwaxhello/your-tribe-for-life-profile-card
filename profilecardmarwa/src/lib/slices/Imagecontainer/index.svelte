<script>
	/** @type {import("@prismicio/client").Content.ImagecontainerSlice} */
	export let slice;

	console.log(slice);
</script>

<section data-slice-type={slice.slice_type} data-slice-variation={slice.variation}>
	<article>
<h1>{slice.primary.name}</h1>
	<img src={slice.primary.images.url} />
	
	</article>

</section>

<style>



* {
	box-sizing: border-box;
	margin: 0;
	padding: 0;
	scroll-behavior: smooth;
}


      /* main {
      display: flex;
      margin-top: 4em;
      justify-content: center;
    }


    .profile-page {
      width: 25em;
      height: 40em;
      background-color: #ffffff;
      border-radius: 1em;
	  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
    }


	.highlights {
      width: 5em;
    height: 5em;
    border-radius: 50%;
    padding: 1em;
} */
    /* .highlights{
	
		

   } */

</style>