<script>
	import Conversation from './../components/Conversation.svelte';
	import FAQs from './../components/FAQs.svelte';
	import Reviews from './../components/Reviews.svelte';
	import Product from './../components/Product.svelte';
	import Fottor from './../components/Fottor.svelte';
  import Hero from "../components/Hero.svelte";
</script>
<main class = "flex flex-col">
    <Hero/> 
    <Product/>
    <Reviews/>
    <FAQs/>
    <Conversation/>
</main>