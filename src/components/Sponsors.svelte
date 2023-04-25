
<script>
    import Sponsors from '../assets/MAHE Bengaluru icon white.png';
    import mahesvg from '../assets/MITB.png';
    import devfolio from '../assets/Devfolio_Logo-White@2x.png';
    import polygon from '../assets/Polygon_Logo-White.png';
    import solana from '../assets/Solana Dark.svg'
    import filecoin from '../assets/Filecoin Coloured White Text-1.svg';
    import replit from '../assets/Replit-Dark-Background.png'
    import schneider from '../assets/Schneider_Electric_2007.svg.png';
</script>
<div class="mt-20 text-white w-full flex flex-col items-center">
    <p class="mt-10 text-3xl font-bold tracking-widest mb-10">Sponsors</p>
    <div class="flex bg-purple-700 p-3 rounded-md mb-10 cursor-pointer">
        <a class="text-xl" href="https://docs.google.com/forms/d/e/1FAIpQLSfDaxDjGcEmSjnldSzVGJc-eLyCWq26-za-vUGFVOp1keru2Q/viewform?usp=sf_link">Sponsor us</a>
    </div>
    <div class="flex flex-col justify-center items-center mt-10">
        <h1 class="text-3xl font-light">Gold Sponsors</h1>
        <div class="flex flex-row flex-wrap justify-center items-center">
            <img src ={mahesvg} alt="schedule-svg" class=" w-[450px] max-w-[70%] m-10 brightness-0 invert rounded-sm "/>
            <img src ={schneider} alt="SCHNEIDER LOGO" class="w-[250px] max-w-[70%] m-10"/>
            <img src ={devfolio} alt="DEVFOLIO LOGO" class=" w-[250px] max-w-[70%] m-10"/>
            <img src ={polygon} alt="POLYGON LOGO" class="w-[250px] max-w-[70%] m-10"/>
        </div>
        
        <h1 class=" mt-20 text-3xl font-light">Silver Sponsors</h1>
        <div class="flex flex-row flex-wrap justify-center items-center">
            <img src ={solana} alt="SOLANA LOGO" class="w-[250px] max-w-[70%] m-10"/>
            <img src ={filecoin} alt="FILECOIN LOGO" class="w-[250px] max-w-[70%] m-10"/>
            <img src ={replit} alt="REPLIT LOGO" class="w-[250px] max-w-[70%] m-10"/>
        </div>
    </div>
</div>