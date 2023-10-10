<template>
  <div
    class="flex-1 flex flex-col items-start justify-start gap-[1.88rem] text-left text-[5.38rem] text-neutral-0 font-poppins"
  >
    <div
      class="self-stretch flex flex-col items-start justify-start gap-[1.25rem]"
    >
      <div
        class="flex-1 relative leading-[110%] capitalize font-semibold flex items-center w-[40.81rem]"
      >
        Discover digital art & Collect NFTs
      </div>
      <div
        class="self-stretch relative text-[1.38rem] leading-[160%] capitalize font-caption-work-sans"
      >
        NFT marketplace Collect, buy and sell art from more than 20k NFT
        artists.
      </div>
    </div>
    <div
      class="rounded-xl [background:linear-gradient(270deg,_#4287f6,_#d3e5fe)] h-[3.75rem] flex flex-row items-center justify-center py-[0rem] px-[3.13rem] box-border gap-[0.75rem] text-center text-[1rem] font-caption-work-sans"
    >
      <img
        class="relative w-[1.25rem] h-[1.25rem]"
        alt=""
        src="/rocketlaunch.svg"
      />
      <div class="relative leading-[140%] font-semibold">Get Started</div>
    </div>
    <div
      class="self-stretch rounded-xl flex flex-row items-start justify-start gap-[1.88rem] text-[1.75rem] font-h5-space-mono"
    >
      <div class="flex-1 rounded-xl flex flex-col items-start justify-start">
        <b class="self-stretch relative leading-[140%] capitalize">240k+ </b>
        <div
          class="self-stretch relative text-[1.5rem] leading-[160%] capitalize font-caption-work-sans"
        >
          Total Sale
        </div>
      </div>
      <div class="flex-1 rounded-xl flex flex-col items-start justify-start">
        <b class="self-stretch relative leading-[140%] capitalize">100k+</b>
        <div
          class="self-stretch relative text-[1.5rem] leading-[160%] capitalize font-caption-work-sans"
        >
          Auctions
        </div>
      </div>
      <div class="flex-1 rounded-xl flex flex-col items-start justify-start">
        <b class="self-stretch relative leading-[140%] capitalize">240k+</b>
        <div
          class="self-stretch relative text-[1.5rem] leading-[160%] capitalize font-caption-work-sans"
        >
          Artists
        </div>
      </div>
    </div>
  </div>
</template>
<script>
  import { defineComponent } from "vue";

  export default defineComponent({
    name: "HeroTextButtons",
  });
</script>
