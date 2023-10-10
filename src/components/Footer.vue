<template>
  <div
    class="absolute top-[328.69rem] left-[-2.37rem] bg-darkslategray-400 w-[120rem] h-[26.81rem] flex flex-col items-center justify-start py-[2.88rem] px-[8.81rem] box-border gap-[2.63rem] text-left text-[1.38rem] text-neutral-0 font-h5-space-mono"
    :style="footerStyle"
  >
    <div class="w-[98.81rem] flex flex-col items-start justify-start">
      <div
        class="self-stretch relative box-border h-[0.13rem] border-t-[2px] border-solid border-caption-label-text"
      />
    </div>
    <div
      class="w-[96.75rem] flex flex-row items-start justify-between py-[0.81rem] px-[0rem] box-border"
    >
      <div
        class="w-[20.46rem] flex flex-col items-start justify-start py-[0rem] pr-[5.25rem] pl-[0rem] box-border gap-[1.88rem] text-center text-[1.25rem] font-poppins"
      >
        <div class="relative w-[9.88rem] h-[2rem]">
          <img
            class="absolute top-[0rem] left-[0rem] w-[2rem] h-[2rem]"
            alt=""
            :src="imageDimensions"
          />
          <div
            class="absolute top-[0rem] left-[2.75rem] font-semibold inline-block w-[7.13rem] h-[1.75rem]"
          >
            MOJARTO
          </div>
        </div>
        <div
          class="flex flex-col items-start justify-start gap-[1.25rem] text-left text-[1rem] text-lightgray font-caption-work-sans"
        >
          <div class="relative leading-[140%] inline-block w-[14.88rem]">
            Tranding Ui
          </div>
          <div class="flex flex-col items-start justify-start gap-[0.94rem]">
            <div
              class="relative leading-[140%] inline-block w-[14.88rem] h-[1.13rem] shrink-0"
            >
              Join our community
            </div>
            <div class="flex flex-row items-start justify-start gap-[0.63rem]">
              <img
                class="relative w-[2rem] h-[2rem] cursor-pointer"
                alt=""
                :src="imageCode"
                @click="onDiscordLogoIconClick"
              />
              <img
                class="relative w-[2rem] h-[2rem] cursor-pointer"
                alt=""
                :src="imageCodeDimensions"
                @click="onYoutubeLogoIconClick"
              />
              <img
                class="relative w-[2rem] h-[2rem] cursor-pointer"
                alt=""
                :src="imageCodeDimensions2"
                @click="onTwitterLogoIconClick"
              />
              <img
                class="relative w-[2rem] h-[2rem] cursor-pointer"
                alt=""
                :src="imageCodeDimensionsText"
                @click="onInstagramLogoIconClick"
              />
            </div>
          </div>
        </div>
      </div>
      <div
        class="w-[15rem] flex flex-col items-start justify-start gap-[1.56rem]"
      >
        <b class="relative leading-[160%] capitalize">Explore</b>
        <div
          class="flex flex-col items-start justify-start gap-[1.25rem] text-[1rem] text-lightgray font-caption-work-sans"
        >
          <div class="relative leading-[140%]">Marketplace</div>
          <div class="relative leading-[140%]">Rankings</div>
          <div class="relative leading-[140%]">Connect a wallet</div>
        </div>
      </div>
      <div class="flex flex-col items-start justify-start gap-[1.56rem]">
        <b class="relative leading-[160%] capitalize">Join our weekly digest</b>
        <div
          class="flex flex-col items-start justify-start gap-[1.25rem] text-[1rem] text-lightgray font-caption-work-sans"
        >
          <div class="relative leading-[140%] inline-block w-[20.63rem]">
            Get exclusive promotions & updates straight to your inbox.
          </div>
          <div
            class="rounded-xl bg-neutral-0 w-[26.25rem] h-[3.13rem] flex flex-row items-center justify-start py-[1rem] pr-[0rem] pl-[1.25rem] box-border gap-[0.75rem] text-background"
          >
            <div class="flex-1 relative leading-[140%]">
              Enter your email here
            </div>
            <div
              class="rounded-xl [background:linear-gradient(270deg,_#4287f6,_#d3e5fe)] h-[3.13rem] flex flex-row items-center justify-center py-[0rem] px-[3.13rem] box-border gap-[0.75rem] text-center text-neutral-0"
            >
              <img
                class="relative w-[1.25rem] h-[1.25rem] hidden"
                alt=""
                :src="imageCodeDimensionsText2"
              />
              <div class="relative leading-[140%] font-semibold">Subscribe</div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div
      class="w-[98.81rem] flex flex-col items-start justify-start gap-[1.25rem] text-[0.75rem] text-lightgray font-caption-work-sans"
    >
      <div
        class="self-stretch relative box-border h-[0.06rem] border-t-[1px] border-solid border-caption-label-text"
      />
      <div class="self-stretch relative leading-[110%]">
        Ⓒ 2023 Use this template freely.
      </div>
    </div>
  </div>
</template>
<script>
  import { defineComponent } from "vue";

  export default defineComponent({
    name: "Footer",
    props: {
      imageDimensions: { type: String },
      imageCode: { type: String },
      imageCodeDimensions: { type: String },
      imageCodeDimensions2: { type: String },
      imageCodeDimensionsText: { type: String },
      imageCodeDimensionsText2: { type: String },
      propTop: { type: [Object, Array, String, Number, Boolean] },
      propLeft: { type: [Object, Array, String, Number, Boolean] },
      onDiscordLogoIconClick: { type: Function },
      onYoutubeLogoIconClick: { type: Function },
      onTwitterLogoIconClick: { type: Function },
      onInstagramLogoIconClick: { type: Function },
    },
    computed: {
      footerStyle() {
        return {
          top: this.propTop,
          left: this.propLeft,
        };
      },
    },
  });
</script>
