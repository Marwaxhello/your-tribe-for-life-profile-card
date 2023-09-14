<script>
	import { SliceZone } from '@prismicio/svelte';

	import { components } from '$lib/slices';

	/** @type {import('./$types').PageData} */
	export let data;
</script>

<SliceZone slices={data.page.data.slices} {components} />


<main>
  <div class="profile-page">
    <section class="profile-page-content" />
    
    <div class="highlights">About</div>
 
  </div>
</main>

<style>




      main {
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
}
    /* .highlights{
	
		

   } */

</style>