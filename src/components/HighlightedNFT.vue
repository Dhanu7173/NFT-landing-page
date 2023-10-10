<template>
  <div
    class="flex-1 h-[37.5rem] flex flex-col items-center justify-start text-left text-[1.38rem] text-neutral-0 font-caption-work-sans"
  >
    <div
      class="rounded-xl bg-darkslategray-100 w-[19.19rem] hidden flex-row items-center justify-start p-[1.25rem] box-border gap-[0.75rem]"
    >
      <div class="flex flex-row items-start justify-start">
        <div class="relative w-[3.75rem] h-[3.75rem]">
          <img
            class="absolute h-full w-full top-[0%] right-[0%] bottom-[0%] left-[0%] rounded-81xl max-w-full overflow-hidden max-h-full object-cover"
            alt=""
            src="/avatar-placeholder@2x.png"
          />
        </div>
      </div>
      <div class="flex-1 flex flex-col items-start justify-start gap-[0.31rem]">
        <div
          class="self-stretch relative leading-[140%] capitalize font-semibold"
        >
          Dish Studio
        </div>
        <div
          class="self-stretch flex flex-row items-start justify-start gap-[0.31rem] text-[1rem] text-caption-label-text"
        >
          <div class="flex-1 relative leading-[140%]">Total Sales:</div>
          <div
            class="flex-1 relative leading-[140%] font-h5-space-mono text-neutral-0"
          >
            34.53 ETH
          </div>
        </div>
      </div>
    </div>
    <img
      class="self-stretch flex-1 relative rounded-t-xl rounded-b-none max-w-full overflow-hidden max-h-full object-cover"
      alt=""
      src="/image-placeholder@2x.png"
    />
    <div
      class="rounded-xl bg-darkslategray-100 box-border w-[17.5rem] hidden flex-row items-center justify-between py-[1.25rem] px-[1.88rem] text-[0.75rem] text-caption-label-text font-h5-space-mono border-[1px] border-solid border-caption-label-text"
    >
      <div class="flex flex-col items-start justify-start gap-[0.31rem]">
        <div class="w-[5.56rem] flex flex-row items-start justify-start">
          <div
            class="relative leading-[110%] inline-block w-[3.25rem] shrink-0"
          >
            Price:
          </div>
        </div>
        <div
          class="w-[5.56rem] flex flex-row items-start justify-start text-[1rem] text-neutral-0"
        >
          <div
            class="relative leading-[140%] inline-block w-[5.56rem] shrink-0"
          >
            1.63 ETH
          </div>
        </div>
      </div>
      <div
        class="w-[7.06rem] flex flex-col items-end justify-center gap-[0.31rem] text-right"
      >
        <div class="w-[7.06rem] flex flex-row items-start justify-end">
          <div
            class="relative leading-[110%] inline-block w-[7.06rem] shrink-0"
          >
            Release Date:
          </div>
        </div>
        <div
          class="w-[7.06rem] flex flex-row items-end justify-end text-[1rem] text-neutral-0"
        >
          <div
            class="relative leading-[140%] inline-block w-[7.06rem] shrink-0"
          >
            2 Sep 2022
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
  import { defineComponent } from "vue";

  export default defineComponent({
    name: "HighlightedNFT",
  });
</script>
