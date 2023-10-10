<template>
  <div
    class="rounded-xl [background:linear-gradient(180deg,_#142935,_rgba(17,_30,_38,_0))] w-[22.25rem] h-[29.56rem] flex flex-col items-center justify-start pt-[0.63rem] px-[1.88rem] pb-[1.88rem] box-border gap-[1.25rem] text-center text-[1.38rem] text-neutral-0 font-caption-work-sans"
  >
    <SetupWalletIcon
      setupWalletIconSetupWalle="/icon.svg"
      setupWalletIconWidth="15.63rem"
      setupWalletIconHeight="15.63rem"
      setupWalletIconPosition="relative"
      setupWalletIconFlexShrink="0"
    />
    <div
      class="self-stretch flex flex-col items-center justify-start gap-[0.63rem]"
    >
      <div
        class="self-stretch relative leading-[140%] capitalize font-semibold"
      >
        {{actionDescription}}
      </div>
      <div class="self-stretch relative text-[1rem] leading-[140%]">
        {{walletSetupDescription}}
      </div>
    </div>
  </div>
</template>
<script>
  import { defineComponent } from "vue";
  import SetupWalletIcon from "./SetupWalletIcon.vue";

  export default defineComponent({
    name: "InfoCard",
    components: { SetupWalletIcon },
    props: {
      imageId: { type: String },
      actionDescription: { type: String },
      walletSetupDescription: { type: String },
    },
  });
</script>
