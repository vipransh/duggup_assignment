<script>
	import Logo from "./Logo.svelte";
	import PostButton from "./PostButton.svelte";

</script>

<header class="flex items-center justify-between  py-3 border-b-[1.5px] border-gray-400 border-dotted w-[90%] mx-auto">
    <Logo/>
    <div class="flex gap-[40px]">
        <div class="flex gap-[8px] items-center">
            <span>
                <img src="/assets/Container.png" alt="logo"/>
            </span>
            <p class="font-Inter text-[#4D4D4D] text-[14px]">Home</p>
        </div>
        <div class="flex gap-[8px]  items-center">
            <span>
                <img src="/assets/explore.png" alt="logo"/>
            </span>
            <p class="font-Inter text-[#4D4D4D] text-[14px]">Explore</p>
        </div>
        <div class="flex gap-[8px]  items-center">
            <span>
                <img src="/assets/learn.png" alt="logo"/>
            </span>
            <p class="font-Inter text-[#4D4D4D] text-[14px]">Learn</p>
        </div>
        <PostButton/>
        <section class="flex items-center gap-[12px]">
            <img class="w-[46px] h-[46px]" src="/assets/profileImage.png" alt="logo"/>
            <p class="text-[#4D4D4D] font-Inter text-[20px] font-medium">Krishna Kiran</p>
            <img  src="/assets/downArrow.png" alt="logo"/>
        </section>
    </div>
</header>