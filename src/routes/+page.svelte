<script >
    let title = "";

    const updateTitle =()=>{
        title ="Welcome To My Portfolio";
    }

</script>



<section class="pt-16">
    <h3>{title}</h3>
	<h2 id="text"><span>It's time for a new </span><br />Advanture</h2>

	<a href="#" id="btn" on:click={updateTitle}>Explore</a>
</section>