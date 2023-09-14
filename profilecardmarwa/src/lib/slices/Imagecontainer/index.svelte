<script>
	/** @type {import("@prismicio/client").Content.ImagecontainerSlice} */
	export let slice;

	console.log(slice);
</script>

<section data-slice-type={slice.slice_type} data-slice-variation={slice.variation}>

<main>
	<section class="profile-page">
    

	<img class="profile-foto" src={slice.primary.images.url} />
	<h1 class="profile-name">{slice.primary.name}</h1>
    <h1>Marwa</h1>
	<p>{slice.primary.bio}</p>

    <div class="follow-container">
    <button class="follow-text"><h3>Follow</h3></button>
	 <button class="follow-text"><h3>Message</h3></button>
    </div>


	<div class="highlights-container">
	<img class="highlights" src={slice.primary.highlights.url} />
    <img class="highlights" src={slice.primary.highlights.url} />
	<img class="highlights" src={slice.primary.highlights.url} />
    <img class="highlights" src={slice.primary.highlights.url} />
    </div>

	</section>
	
    <!-- <div class="center-container">
			<button><a href={slice.primary.github.url}>{slice.primary.linkname} </a></button>
		</div> -->

</main>
</section>




<style>


* {
	box-sizing: border-box;
	margin: 0;
	padding: 0;
	scroll-behavior: smooth;
}


	main {
      display: flex;
      margin-top: 6em;
      justify-content: center;
    }

	h1{
	margin-bottom: 1em;
	margin-left: 0.7em;
    }

	.profile-name {
	/* margin-bottom: 1em;
	margin-left: 0.7em; */
	display: block;
	text-align: right;
    }

	p{
	font-size: 0.7em;
	margin-left: 1em;
	}

	.follow-text{
	width: 14em;
	height: 2.4em;
    color: #ffffff;
	background-color: #3997F1;
	/* border: #0b0c0e; */
	border-radius: 0.5em;
    margin: 1em;
	justify-content: center;
    /* text-transform: uppercase;
    font-weight: 600; */
    letter-spacing: 0.05em;
	}

  .follow-container {
  display: flex;
  justify-content: center;
  }

	 .profile-page {
      width: 30em;
      height: 45em;
      background-color: #ffffff;
      border-radius: 1em;
	  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
    }
 
	.profile-foto{
	width: 10em;
    height: 10.4em;
    border-radius: 50%;
    padding: 1.5em;
	border: 1.5px;
	}


	.highlights {
    width: 6em;
    height: 6.1em;
    border-radius: 50%;
    padding: 1em;
    }

	.highlights-container{
	margin-left: 2.3em;
	}


</style>