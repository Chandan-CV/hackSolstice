<script>
    import openInnovation from "../assets/undraw_electricity_k2ft.svg";
    import Healthcare from '../assets/undraw_medicine_b-1-ol.svg';
    import Agriculture from '../assets/undraw_environment_iaus.svg';
    import Education from '../assets/undraw_education_f8ru.svg';
    import FinTech from '../assets/undraw_savings_re_eq4w.svg';
</script>

<div class="mt-20 text-white w-full flex flex-col items-center">
    <p class="mt-10 text-3xl font-bold tracking-widest">Tracks</p>
    <div class="p-20 text-2xl font-light tracking-wider leading-relaxed max-sm:p-5 text-center">
        <p>We welcome every idea in our hackathon, but if you are still confused, here are some tracks to help your decide the best suited track for you. Open Innovation, Healthcare, Web3, AI/ML, Hardware and IoT, Agriculture, and Education. Whether you're interested in building intuitive websites and applications, exploring cutting-edge technologies, or finding innovative solutions to real-world problems, we have a track that's right for you. Join us for an unforgettable experience that challenges and inspires you to create something amazing!</p>
    </div>
    <div class=" flex flex-row flex-wrap justify-center ">
        <div class="flex flex-col p-10 border border-purple-500 justify-center items-center rounded-md m-10">
            <img src={openInnovation} alt="openInnovationsvg" class="h-[200px] w-[200px] mb-10"/>
            <p class="text-2xl tracking-wider ">Open Innovation</p>
        </div>

        <div class="flex flex-col p-10 border border-purple-500 justify-center items-center rounded-md m-10">
            <img src={Healthcare} alt="healthCare" class="h-[200px] w-[200px] mb-10"/>
            <p class="text-2xl tracking-wider ">Health Care</p>
        </div>

        <div class="flex flex-col p-10 border border-purple-500 justify-center items-center rounded-md m-10">
            <img src={Agriculture} alt="agriculture" class="h-[200px] w-[200px] mb-10"/>
            <p class="text-2xl tracking-wider ">Agriculture</p>
        </div>

        <div class="flex flex-col p-10 border border-purple-500 justify-center items-center rounded-md m-10">
            <img src={Education} alt="Education" class="h-[200px] w-[200px] mb-10"/>
            <p class="text-2xl tracking-wider ">Education</p>
        </div>

        <div class="flex flex-col p-10 border border-purple-500 justify-center items-center rounded-md m-10">
            <img src={FinTech} alt="fintech" class="h-[200px] w-[200px] mb-10"/>
            <p class="text-2xl tracking-wider ">Fintech</p>
        </div>
    </div>
</div>