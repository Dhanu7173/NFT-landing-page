<template>
  <div
    class="absolute top-[0rem] left-[0rem] bg-gray-1800 w-[120rem] h-[8.44rem] flex flex-row items-center justify-between py-[1.25rem] px-[6.5rem] box-border text-center text-[2rem] text-neutral-0 font-poppins"
    :style="navigationStyle"
  >
    <div class="relative w-[16.25rem] h-[3rem]">
      <div
        class="absolute top-[0.09rem] left-[0rem] w-[2.26rem] flex flex-row items-center justify-start cursor-pointer"
        @click="onNavLogoClick"
      >
        <img class="relative w-[2rem] h-[2rem]" alt="" src="/logo.svg" />
      </div>
      <div
        class="absolute top-[0rem] left-[2.88rem] font-semibold inline-block w-[13.38rem]"
      >
        MOJARTO
      </div>
    </div>
    <div
      class="flex flex-row items-center justify-end gap-[0.63rem] text-[1rem] font-caption-work-sans"
    >
      <div
        class="rounded-xl h-[2.88rem] flex flex-row items-center justify-center py-[0rem] px-[1.25rem] box-border gap-[0.75rem]"
      >
        <img
          class="relative w-[1.25rem] h-[1.25rem] hidden"
          alt=""
          src="/rocketlaunch1.svg"
        />
        <div class="relative leading-[140%] font-semibold">Marketplace</div>
      </div>
      <div
        class="rounded-xl h-[2.88rem] flex flex-row items-center justify-center py-[0rem] px-[1.25rem] box-border gap-[0.75rem]"
      >
        <img
          class="relative w-[1.25rem] h-[1.25rem] hidden"
          alt=""
          src="/rocketlaunch1.svg"
        />
        <div class="relative leading-[140%] font-semibold">Rankings</div>
      </div>
      <div
        class="rounded-xl h-[2.88rem] flex flex-row items-center justify-center py-[0rem] px-[1.25rem] box-border gap-[0.75rem]"
      >
        <img
          class="relative w-[1.25rem] h-[1.25rem] hidden"
          alt=""
          src="/rocketlaunch1.svg"
        />
        <div class="relative leading-[140%] font-semibold">
          Connect a wallet
        </div>
      </div>
      <div
        class="rounded-xl cursor-pointer [background:linear-gradient(270deg,_#4287f6,_#d3e5fe)] w-[10.81rem] h-[2.56rem] flex flex-row items-center justify-center  box-border gap-[0.75rem] text-gray-700"
      >
        Sign Up
      </div>
    </div>
  </div>
</template>
<script>
  import { defineComponent } from "vue";

  export default defineComponent({
    name: "Navigation1",
    props: {
      propHeight: { type: [Object, Array, String, Number, Boolean] },
      propBackgroundColor: { type: String },
      onNavLogoClick: { type: Function },
    },
    computed: {
      navigationStyle() {
        return {
          height: this.propHeight,
          backgroundColor: this.propBackgroundColor,
        };
      },
    },
  });
</script>
