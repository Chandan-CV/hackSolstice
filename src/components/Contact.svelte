<script>
	import { goto } from '$app/navigation';
	import insta from '../assets/insta.svg';
	import logo from '../assets/logo.svg';
</script>

<div class="text-white flex flex-col items-center mt-10">
	<p class="mt-5 text-3xl font-bold tracking-widest">Contact us!</p>
	<div class="flex flex-row w-full justify-center flex-wrap">
		<img
			src={insta}
			alt="instasvg"
			class="h-[70px] w-[70px] m-5 cursor-pointer on:click={() => {
				goto('https://www.instagram.com/solstice.mitb/');
			}}"
		/>
		<img
			src={logo}
			alt="logosvg"
			class="h-[80px] w-[80px] m-5 cursor-pointer"
			on:click={() => {
				goto('https://linktr.ee/techsolstice');
			}}
		/>
	</div>
	<div class=" flex flex-col items-center text-center">
		<p class="text-2xl font-light tracking-wide">For any queries, contact us at</p>
		<p class="sm:text-xl font-light tracking-wide text-md">
			<a href="mailto:chandan.mitblr2022@learner.manipal.edu">
				chandan.mitblr2022@learner.manipal.edu
			</a>
		</p>
		<p>or</p>
		<p class="sm:text-xl font-light tracking-wide text-md">
			<a href="mailto:anshuman@learner.manipal.edu"> anshuman@learner.manipal.edu </a>
		</p>	
	</div>
</div>
