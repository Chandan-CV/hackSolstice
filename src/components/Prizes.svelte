<script>
	import { goto } from '$app/navigation';
	import svgPrizes from '../assets/undraw_winners_re_wr1l.svg';
</script>

<div class="mt-20 text-white w-full flex flex-col items-center justify-center">
	<p class="text-3xl mb-20 tracking-widest font-bold">Prizes</p>
	<div class=" flex w-full justify-evenly flex-wrap flex-row items-center">
		<img
			src={svgPrizes}
			alt="prizes-svg"
			class=" max-h-[30%] max-w-[30%] min-h-[250px] min-w-[250px] self-center"
		/>
		<div class="flex flex-col items-center text-center justify-center">
			<!-- <h1 class="text-3xl">In-Person</h1>
			<p class="mt-10 text-2xl tracking-wider">1st Prize: <strong> 20,000 INR </strong></p>
			<p class="mt-10 text-2xl tracking-wider">2nd Prize: <strong> 15,000 INR </strong></p>
			<p class="mt-10 text-2xl tracking-wider">3rd Prize: <strong> 10,000 INR </strong></p>
		</div>
		<div class="flex flex-col items-center text-center">
			<h1 class="text-3xl">Online</h1>
			<p class="mt-10 text-2xl tracking-wider">1st Prize: <strong> 10,000 INR </strong></p>
			<p class="mt-10 text-2xl tracking-wider">2nd Prize: <strong> 7,500 INR </strong></p>
			<p class="mt-10 text-2xl tracking-wider">3rd Prize: <strong> 3,500 INR </strong></p> -->
			<p class="mt-10 text-2xl tracking-wider">
				<strong> Prizes worth about 160K INR </strong>
			</p>
			<button class="p-6 rounded-md bg-purple-900 font-bold text-xl m-10" on:click={()=>goto("https://hack-solstice.devfolio.co/prizes" )}> Check out the prizes</button>
		</div>
	</div>
	<p class="mt-20 text-white text-3xl font-bold font-mono tracking-wider">
		Schwags for top participants!
	</p>
</div>
