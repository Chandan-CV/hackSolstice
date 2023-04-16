<script>
    // @ts-ignore
    function scrollIntoView({ target }) {
		const el = document.querySelector(target.getAttribute('href'));
		if (!el) return;
		el.scrollIntoView({
			behavior: 'smooth'
		});
	}
</script>

<div class="flex p-4 flex-row justify-center fixed w-full z-30 backdrop-blur-lg max-[1460px]:invisible">
    <!-- <img src={logo} alt="logo" width="100" height="100" /> -->
    <div>
        <a class=" text-white font-light text-xl py-2 px-4 m-5 hover:text-yellow-600"
            href="#hacksolstice"
            on:click|preventDefault={scrollIntoView}
            >Hack Solstice</a
        >
        <a
            class=" text-white font-light text-xl py-2 px-4 m-5 hover:text-yellow-600"
            href="#Aboutus"
            on:click|preventDefault={scrollIntoView}>About us</a
        >
        <a class=" text-white font-light text-xl py-2 px-4 m-5 hover:text-yellow-600"
        href="#Prizes"
        on:click|preventDefault={scrollIntoView}
            >Prizes</a
        >
        <a class=" text-white font-light text-xl py-2 px-4 m-5 hover:text-yellow-600"
            href="#Schedule"
            on:click|preventDefault={scrollIntoView}
            >Schedule</a
        >
        <a class=" text-white font-light text-xl py-2 px-4 m-5 hover:text-yellow-600"
            href="#Tracks"
            on:click|preventDefault={scrollIntoView}

            >Tracks</a
        >
        <a class=" text-white font-light text-xl py-2 px-4 m-5 hover:text-yellow-600"
            href="#Speakers"
            on:click|preventDefault={scrollIntoView}

            >Speakers</a
        >
        <a class=" text-white font-light text-xl py-2 px-4 m-5 hover:text-yellow-600"
            href="#Sponsors"
            on:click|preventDefault={scrollIntoView}
            >Sponsors</a
        >
        <a class=" text-white font-light text-xl py-2 px-4 m-5 hover:text-yellow-600"
            href="#FAQ"
            on:click|preventDefault={scrollIntoView}
        >FAQ</a
        >
        <a class=" text-white font-light text-xl py-2 px-4 m-5 hover:text-yellow-600"
            href="#Contact"
            on:click|preventDefault={scrollIntoView}
            >Contact</a
        >
    </div>
</div>