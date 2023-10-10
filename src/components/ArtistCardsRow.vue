<template>
  <div
    class="w-[65.63rem] flex flex-row items-start justify-start gap-[1.88rem] text-center text-[1.38rem] text-neutral-0 font-caption-work-sans"
  >
    <div
      class="rounded-xl bg-gray-1000 shadow-[0px_0px_20px_rgba(0,_0,_0,_0.44)] w-[24.56rem] h-[16.25rem] flex flex-col items-center justify-start p-[1.25rem] box-border relative gap-[1.25rem]"
      :style="artistCardStyle"
    >
      <div class="flex flex-col items-end justify-start z-[0]">
        <div class="flex flex-row items-start justify-start z-[0]">
          <div class="relative w-[7.5rem] h-[7.5rem]">
            <img
              class="absolute h-full w-full top-[0%] right-[0%] bottom-[0%] left-[0%] rounded-81xl max-w-full overflow-hidden max-h-full object-cover"
              alt=""
              :src="imageId"
              :style="avatarPlaceholderIconStyle"
            />
          </div>
        </div>
      </div>
      <div
        class="self-stretch flex flex-col items-center justify-center gap-[0.31rem] z-[1]"
      >
        <div
          class="self-stretch relative leading-[140%] capitalize font-semibold"
        >
          {{componentName}}
        </div>
        <div
          class="self-stretch flex flex-row items-start justify-center gap-[0.63rem] text-right text-[1rem] text-caption-label-text"
        >
          <div class="flex-1 relative leading-[140%]">Total Sales:</div>
          <div
            class="flex-1 relative leading-[140%] font-h5-space-mono text-neutral-0 text-left"
          >
            34.53 ETH
          </div>
        </div>
      </div>
      <div
        class="my-0 mx-[!important] absolute top-[1.13rem] left-[1.25rem] rounded-xl bg-background w-[1.88rem] flex flex-row items-start justify-start z-[2] text-[1rem] text-caption-label-text font-h5-space-mono"
      >
        <div
          class="absolute my-0 mx-[!important] top-[calc(50%_-_11px)] left-[calc(50%_-_5px)] leading-[140%] z-[0]"
        >
          {{thumbnailId}}
        </div>
      </div>
    </div>
    <div
      class="rounded-xl bg-gray-1000 shadow-[0px_0px_20px_rgba(0,_0,_0,_0.44)] w-[24.56rem] h-[16.25rem] flex flex-col items-center justify-start p-[1.25rem] box-border relative gap-[1.25rem]"
      :style="artistCard1Style"
    >
      <div class="flex flex-col items-end justify-start z-[0]">
        <div class="flex flex-row items-start justify-start z-[0]">
          <div class="relative w-[7.5rem] h-[7.5rem]">
            <img
              class="absolute h-full w-full top-[0%] right-[0%] bottom-[0%] left-[0%] rounded-81xl max-w-full overflow-hidden max-h-full object-cover"
              alt=""
              :src="imageDimensions"
              :style="avatarPlaceholderIcon1Style"
            />
          </div>
        </div>
      </div>
      <div
        class="self-stretch flex flex-col items-center justify-center gap-[0.31rem] z-[1]"
      >
        <div
          class="self-stretch relative leading-[140%] capitalize font-semibold"
        >
          {{componentImageUrl}}
        </div>
        <div
          class="self-stretch flex flex-row items-start justify-center gap-[0.63rem] text-right text-[1rem] text-caption-label-text"
        >
          <div class="flex-1 relative leading-[140%]">Total Sales:</div>
          <div
            class="flex-1 relative leading-[140%] font-h5-space-mono text-neutral-0 text-left"
          >
            34.53 ETH
          </div>
        </div>
      </div>
      <div
        class="my-0 mx-[!important] absolute top-[1.13rem] left-[1.25rem] rounded-xl bg-background w-[1.88rem] flex flex-row items-start justify-start z-[2] text-[1rem] text-caption-label-text font-h5-space-mono"
      >
        <div
          class="absolute my-0 mx-[!important] top-[calc(50%_-_11px)] left-[calc(50%_-_5px)] leading-[140%] z-[0]"
          :style="divStyle"
        >
          {{imageDimensionsId}}
        </div>
      </div>
    </div>
    <div
      class="rounded-xl bg-gray-1000 shadow-[0px_0px_20px_rgba(0,_0,_0,_0.44)] w-[24.56rem] h-[16.25rem] flex flex-col items-center justify-start p-[1.25rem] box-border relative gap-[1.25rem]"
      :style="artistCard2Style"
    >
      <div class="flex flex-col items-end justify-start z-[0]">
        <div class="flex flex-row items-start justify-start z-[0]">
          <div class="relative w-[7.5rem] h-[7.5rem]">
            <img
              class="absolute h-full w-full top-[0%] right-[0%] bottom-[0%] left-[0%] rounded-81xl max-w-full overflow-hidden max-h-full object-cover"
              alt=""
              :src="imageDimensionsUrl"
              :style="avatarPlaceholderIcon2Style"
            />
          </div>
        </div>
      </div>
      <div
        class="self-stretch flex flex-col items-center justify-center gap-[0.31rem] z-[1]"
      >
        <div
          class="self-stretch relative leading-[140%] capitalize font-semibold"
        >
          {{componentImageId}}
        </div>
        <div
          class="self-stretch flex flex-row items-start justify-center gap-[0.63rem] text-right text-[1rem] text-caption-label-text"
        >
          <div class="flex-1 relative leading-[140%]">Total Sales:</div>
          <div
            class="flex-1 relative leading-[140%] font-h5-space-mono text-neutral-0 text-left"
          >
            34.53 ETH
          </div>
        </div>
      </div>
      <div
        class="my-0 mx-[!important] absolute top-[1.13rem] left-[1.25rem] rounded-xl bg-background w-[1.88rem] flex flex-row items-start justify-start z-[2] text-[1rem] text-caption-label-text font-h5-space-mono"
      >
        <div
          class="absolute my-0 mx-[!important] top-[calc(50%_-_11px)] left-[calc(50%_-_5px)] leading-[140%] z-[0]"
          :style="div1Style"
        >
          {{imageDimensionsCode}}
        </div>
      </div>
    </div>
    <div
      class="rounded-xl bg-gray-1000 shadow-[0px_0px_20px_rgba(0,_0,_0,_0.44)] w-[24.56rem] h-[16.25rem] flex flex-col items-center justify-start p-[1.25rem] box-border relative gap-[1.25rem]"
      :style="artistCard3Style"
    >
      <div class="flex flex-col items-end justify-start z-[0]">
        <div class="flex flex-row items-start justify-start z-[0]">
          <div class="relative w-[7.5rem] h-[7.5rem]">
            <img
              class="absolute h-full w-full top-[0%] right-[0%] bottom-[0%] left-[0%] rounded-81xl max-w-full overflow-hidden max-h-full object-cover"
              alt=""
              :src="imageCode"
              :style="avatarPlaceholderIcon3Style"
            />
          </div>
        </div>
      </div>
      <div
        class="self-stretch flex flex-col items-center justify-center gap-[0.31rem] z-[1]"
      >
        <div
          class="self-stretch relative leading-[140%] capitalize font-semibold"
        >
          {{entityImageUrl}}
        </div>
        <div
          class="self-stretch flex flex-row items-start justify-center gap-[0.63rem] text-right text-[1rem] text-caption-label-text"
        >
          <div class="flex-1 relative leading-[140%]">Total Sales:</div>
          <div
            class="flex-1 relative leading-[140%] font-h5-space-mono text-neutral-0 text-left"
          >
            34.53 ETH
          </div>
        </div>
      </div>
      <div
        class="my-0 mx-[!important] absolute top-[1.13rem] left-[1.25rem] rounded-xl bg-background w-[1.88rem] flex flex-row items-start justify-start z-[2] text-[1rem] text-caption-label-text font-h5-space-mono"
      >
        <div
          class="absolute my-0 mx-[!important] top-[calc(50%_-_11px)] left-[calc(50%_-_5px)] leading-[140%] z-[0]"
          :style="div2Style"
        >
          {{imageDimensionsCode2}}
        </div>
      </div>
    </div>
  </div>
</template>
<script>
  import { defineComponent } from "vue";

  export default defineComponent({
    name: "ArtistCardsRow",
    props: {
      imageId: { type: String },
      componentName: { type: String },
      thumbnailId: { type: String },
      imageDimensions: { type: String },
      componentImageUrl: { type: String },
      imageDimensionsId: { type: String },
      imageDimensionsUrl: { type: String },
      componentImageId: { type: String },
      imageDimensionsCode: { type: String },
      imageCode: { type: String },
      entityImageUrl: { type: String },
      imageDimensionsCode2: { type: String },
      propHeight: { type: [Object, Array, String, Number, Boolean] },
      propBorderRadius: { type: String },
      propHeight1: { type: [Object, Array, String, Number, Boolean] },
      propBorderRadius1: { type: String },
      propLeft: { type: [Object, Array, String, Number, Boolean] },
      propHeight2: { type: [Object, Array, String, Number, Boolean] },
      propBorderRadius2: { type: String },
      propLeft1: { type: [Object, Array, String, Number, Boolean] },
      propHeight3: { type: [Object, Array, String, Number, Boolean] },
      propBorderRadius3: { type: String },
      propLeft2: { type: [Object, Array, String, Number, Boolean] },
    },
    computed: {
      artistCardStyle() {
        return {
          height: this.propHeight,
        };
      },
      avatarPlaceholderIconStyle() {
        return {
          borderRadius: this.propBorderRadius,
        };
      },
      artistCard1Style() {
        return {
          height: this.propHeight1,
        };
      },
      avatarPlaceholderIcon1Style() {
        return {
          borderRadius: this.propBorderRadius1,
        };
      },
      divStyle() {
        return {
          left: this.propLeft,
        };
      },
      artistCard2Style() {
        return {
          height: this.propHeight2,
        };
      },
      avatarPlaceholderIcon2Style() {
        return {
          borderRadius: this.propBorderRadius2,
        };
      },
      div1Style() {
        return {
          left: this.propLeft1,
        };
      },
      artistCard3Style() {
        return {
          height: this.propHeight3,
        };
      },
      avatarPlaceholderIcon3Style() {
        return {
          borderRadius: this.propBorderRadius3,
        };
      },
      div2Style() {
        return {
          left: this.propLeft2,
        };
      },
    },
  });
</script>
