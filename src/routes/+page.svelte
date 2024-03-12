<script>
	import FollowButton from "$lib/components/FollowButton.svelte";

</script>


<div class="w-[75%] mx-auto mt-[20px] pb-20">
    <!-- profile section -->
    <section class="flex items-center gap-[25px] ">
        <!-- left profile section -->
        <div class="flex flex-col text-center ">
            <img class="w-[120px] h-[120px]" src="/assets/profileImage.png" alt="logo"/>
            <p class="font-
            Inter text-[24px] w-[700]  font-bold text-[#4B5C6D]">Krishna <br> Kiran</p>
        </div>
        <!-- right section -->
        <div class="flex flex-col  w-full gap-[20px]">
            <!-- top -->
            <div class="flex items-center justify-between">
                <p class="font-Inter text-[14px] text-[#141618] font-[400]">Co-Founder and CEO at Duggup - Social network for people in tech. Ex-Amazon Head <br> of Engineering. I write hot-takes on building a business, shipping delightful products and <br> accelerating product and career growth.</p>
                <!-- left -->
                <div class="flex flex-col items-end gap-[8px]">
                    <img src="/assets/roundIcon.png" alt="logo"/>
                    <div class="flex flex-col items-end gap-[4px]">
                        <p class="text-[16px] font-Inter text-[#000000] font-bold">Duggup</p>
                    <p class="text-[12px] font-Inter text-[#7A9299]">Co-Founder and CEO</p>
                    </div>
                </div>
            </div>
            <div class="flex items-center justify-between">
                <FollowButton/>
                <div class="flex items-center gap-[16px]">
                   <div class="flex items-center gap-[4px]">
                    <p class="text-[#4D4D4D] text-[14px]">My website</p>
                    <img class="cursor-pointer" src="/assets/link.png" alt="logo"/>
                   </div>
                    <img class="cursor-pointer" src="/assets/dots.png" alt="logo"/>
                </div>
            </div>
        </div>
    </section>

    <!-- section 1 history -->
    <section class="flex items-center mt-[20px] gap-[25px] pl-[30px]">
        <!-- left -->
        <div class="relative ">
            <p class="absolute top-[47%] bottom-[50%] right-10 text-[12px] text-end text-[#7A9299] w-[100px]">Dec 2023</p>
            <img src="/assets/pattern1.png" alt="pattern"/>
        </div>
        <!-- right -->
        <div class="flex gap-8">
            <!-- card 1 -->
            <div class="flex flex-col w-[334px] h-[226px]">
                <img src="/assets/billGates.png" alt="pattern"/>
                <div class="flex items-center justify-center  w-full h-full border-b border-l border-r border-gray rounded-b-xl">
                    <p class="  text-[14px] font-[400] font-Inter text-[#141618]"> No amount of technology can convert a bad <br> story into a good story.</p>
                </div>
            </div>
            <!-- card 2 -->
            <div class="flex flex-col w-[334px] h-[226px] ">
                <img class="rounded-t-xl" src="/assets/sam.png" alt="pattern"/>
                <div class="flex items-center justify-center  w-full h-full border-b border-l border-r border-gray rounded-b-xl">
                    <p class="p-4 text-[14px] font-[400] font-Inter text-[#141618]">
                        Most people don't have original ideas. Here <br>is how Sam Altman pushes himself to have unpopular ideas.
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- section 2 history -->
    <section class="flex items-center gap-[25px] pl-[30px]">
        <!-- left -->
        <div class="relative flex  items-center">
            <div class="absolute top-[15%]  right-10 flex flex-col items-end gap-[4px]">
                <img src="/assets/roundIcon.png" alt="logo"/>
                <div class="flex flex-col items-end gap-[2px]">
                    <p class="text-[16px] font-Inter text-[#141618] font-bold ">Duggup</p>
                <p class="text-[12px] font-Inter text-[#7A9299] text-end  w-[100px]">San Francisco Bay Area <br>Joined <br> Nov 2023</p>
                </div>
            </div>
            <img src="/assets/pattern2.png" alt="pattern"/>
        </div>
        <div  class="flex flex-col gap-[8px]">
            <p class="text-[20px] text-[141618] text-bold">Co-Founder and CEO</p>
            <p class="text-[12px] text-[#7A9299]">Full-time · Remote</p>
        </div>
    </section>

    <!-- section 3 history -->
    <section class="flex items-center  gap-[25px] pl-[30px]">
        <!-- left -->
        <div class="relative ">
            <p class="absolute top-[47%] bottom-[50%] right-10 text-[12px] text-end text-[#7A9299] w-[100px]">Dec 2023</p>
            <img src="/assets/pattern1.png" alt="pattern"/>
        </div>
        <!-- right -->
        <div class="flex gap-8">
            <!-- card 1 -->
            <div class="flex flex-col w-[334px] h-[226px]">
                <img src="/assets/pcImage.png" alt="pattern"/>
                <div class="flex items-center justify-center  w-full h-full border-b border-l border-r border-gray rounded-b-xl">
                    <p class="  text-[14px] font-[400] font-Inter text-[#141618]">Startup Lesson I am reflecting. Don't build <br> for the "average person".</p>
                </div>
            </div>
            <!-- card 2 -->
            <div class="flex flex-col w-[334px] h-[226px] ">
                <img class="rounded-t-xl" src="/assets/mapImage.png" alt="pattern"/>
                <div class="flex items-center justify-center  w-full h-full border-b border-l border-r border-gray rounded-b-xl">
                    <p class="p-4 text-[14px] font-[400] font-Inter text-[#141618]">
                        Your biggest regrets at 80 will be acts of<br> omission.
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- section 4 history -->
    <section class="flex items-center gap-[25px] pl-[30px]">
        <!-- left -->
        <div class="relative flex  items-center">
            <div class="absolute top-[15%]  right-10 flex flex-col items-end gap-[4px]">
                <img class="w-[36px] h-[36px]" src="/assets/butterIcon.png" alt="logo"/>
                <div class="flex flex-col items-end gap-[2px]">
                    <p class="text-[16px] font-Inter text-[#141618] font-bold ">Duggup</p>
                <p class="text-[12px] font-Inter text-[#7A9299] text-end  w-[100px]">San Francisco Bay Area <br>Joined <br> Nov 2023</p>
                </div>
            </div>
            <img src="/assets/pattern2.png" alt="pattern"/>
        </div>
        <div class="flex flex-col gap-[8px]">
            <p class="text-[20px] text-[141618] text-bold">VP Engineering</p>
            <p class="text-[12px] text-[#7A9299]">Full-time</p>
        </div>
    </section>
</div>
