<script defer async src="https://apply.devfolio.co/v2/sdk.js">
	import logo from '../assets/logo.svg';
	import '../app.css';
	import Banner from '../components/Banner.svelte';
	import Aboutus from '../components/Aboutus.svelte';
	import Navbar from '../components/Navbar.svelte';
	import Prizes from '../components/Prizes.svelte';
	import Schedule from '../components/Schedule.svelte';
	import Tracks from '../components/Tracks.svelte';
	import Speakers from '../components/Speakers.svelte';
	import Sponsors from '../components/Sponsors.svelte';
	import Faq from '../components/FAQ.svelte';
	import Contact from '../components/Contact.svelte';
	import Footer from '../components/footer.svelte';

	// @ts-ignore
</script>

<title> Hack Solstice 23 </title>



<div class="h-full w-screen bg-gradient-to-t to-[#2b1a25] via-[#130926] from-zinc-900">
	<!-- Navbar -->
	<Navbar />
	<div id="hacksolstice">
		<Banner />
	</div>
	<div class="flex w-full flex-col items-center text-white cursor-pointer">
		<div class="bg-gradient-to-tr from-[#3d1f32] via-[#7f3365] to-[#3d1f32] p-6 rounded-md mt-52">
			<a
				class="self-center text-2xl"
				href="https://docs.google.com/forms/d/e/1FAIpQLSemckZEYbDFoMMtN5Ou62L9G3i_yhKr3thSbXEcNcT8NXTiLw/viewform?usp=sf_link"
				>Mentor Application</a
			>
		</div>
	</div>
	<div id="Aboutus">
		<Aboutus />
	</div>
	<div id="Prizes">
		<Prizes />
	</div>
	<div id="Schedule">
		<Schedule />
	</div>
	<div id="Tracks">
		<Tracks />
	</div>
	<div id="Speakers">
		<Speakers />
	</div>
	<div id="Sponsors">
		<Sponsors />
	</div>
	<div id="FAQ">
		<Faq />
	</div>
	<div id="Contact">
		<Contact />
	</div>
	<Footer />
</div>
