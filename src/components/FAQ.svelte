<script>
	import DropdownFaq from './DropdownFAQ.svelte';
	const faqs = [
		{
      question: "What is a hackathon?",
      answer: "A hackathon is an event where people come together to collaborate and create innovative solutions to solve problems."
    },	{
      question: "How many hours is the hackathon for?",
      answer: "The hackathon will be 24 hours long."
    },
    {
      question: "Where is the hackathon?",
      answer: "The hackathon will be held both virtually and in-person at Manipal Institute of Technology, Bengaluru."
    },

    {
      question: "Who can participate in a hackathon?",
      answer: "Anyone can participate in a hackathon! You don't need to have any specific background or experience - just bring your creativity and enthusiasm."
    },
    {
      question: "What should I bring to a hackathon?",
      answer: "Bring your laptop, charger, any necessary software and tools, and any other materials you might need to work on your project."
    },
    {
      question: "Do I need to have a team before the hackathon?",
      answer: "Yes, we suggest you to form a team before the hackathon. You can work with friends, classmates, or other participants. If you don't have a team, you can also form one at the event."
    },
    {
      question: "What if I've never been to a hackathon before?",
      answer: "Don't worry! Hackathons are a welcoming and inclusive environment for people of all backgrounds and experiences. There will be plenty of opportunities to learn and collaborate with others."
    },
    {
      question: "What kind of projects can I work on at a hackathon?",
      answer: "You can work on any kind of project that interests you! Hackathons usually have specific themes or tracks, but you're free to explore your own ideas as well."
    },
    {
      question: "What happens after the hackathon?",
      answer: "After the hackathon, you'll have the opportunity to present your project to judges and other participants. There may also be opportunities to continue working on your project, get feedback, or even bring it to market."
    },
    {
      question: "How can I prepare for a hackathon?",
      answer: "To prepare for a hackathon, you can brainstorm ideas, brush up on your skills, and connect with other participants. It's also a good idea to get plenty of rest and stay hydrated during the event."
    }
	];
</script>

<div class="w-full flex justify-center items-center flex-col text-white mt-10 mb-20">
	<p class="mt-10 text-3xl font-bold tracking-widest">FAQs</p>
	{#each faqs as faq}
        <DropdownFaq question={faq.question} answer={faq.answer} />
    {/each}

</div>
