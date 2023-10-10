<template>
  <div
    class="absolute top-[0rem] left-[0rem] w-[24.05rem] h-[35.44rem] text-left text-[0.75rem] text-steelblue-200 font-poppins"
    :style="nFTCardStyle"
  >
    <div
      class="absolute top-[0rem] left-[0rem] rounded-lg bg-gray-1100 box-border w-[24.05rem] h-[35.44rem] border-[2px] border-solid border-steelblue-400"
    />
    <img
      class="absolute top-[1.63rem] left-[1.56rem] rounded-lgi w-[21.25rem] h-[19.19rem] object-cover"
      alt=""
      :src="image2"
      :style="image2IconStyle"
    />
    <div
      class="absolute top-[22.44rem] left-[1.25rem] flex flex-col items-center justify-start gap-[0.56rem]"
      :style="frameDivStyle"
    >
      <div class="relative w-[21.88rem] h-[2rem]">
        <div
          class="absolute top-[0.5rem] left-[15.56rem] inline-block w-[6.31rem] h-[1.5rem]"
        >
          Ranjeeta kumar
        </div>
        <div
          class="absolute top-[0rem] left-[0rem] text-[1.13rem] font-semibold text-neutral-0 inline-block w-[6.14rem] h-[1.64rem]"
        >
          Jagriti2
        </div>
      </div>
      <div class="flex flex-col items-start justify-start gap-[0.56rem]">
        <div class="relative w-[20.49rem] h-[1.47rem]">
          <div
            class="absolute top-[0rem] left-[0rem] inline-block w-[5.54rem] h-[1.47rem]"
          >
            painting
          </div>
          <div
            class="absolute top-[0.32rem] left-[18.12rem] text-[0.5rem] text-crimson-100 inline-block w-[2.38rem] h-[0.92rem]"
          >
            25% OFF
          </div>
        </div>
        <div class="relative w-[20.47rem] h-[1.47rem]">
          <div
            class="absolute top-[0rem] left-[0rem] inline-block w-[9.55rem] h-[1.47rem]"
          >
            Acrylic on Canvas
          </div>
          <div
            class="absolute top-[0rem] left-[16.12rem] text-right inline-block w-[4.35rem] h-[1.47rem]"
          >
            116480
          </div>
        </div>
        <div class="relative w-[20.47rem] h-[1.56rem] text-right">
          <div
            class="absolute top-[0rem] left-[16.12rem] inline-block w-[4.35rem] h-[1.47rem]"
          >
            87630
          </div>
          <div
            class="absolute top-[0.08rem] left-[0rem] text-left inline-block w-[6.06rem] h-[1.47rem]"
          >
            36 x 36 In
          </div>
        </div>
      </div>
      <div
        class="relative w-[14.38rem] h-[2.5rem] text-center text-[0.88rem] text-neutral-0"
      >
        <div class="absolute top-[0rem] left-[0rem] w-[14.38rem] h-[2.5rem]">
          <div
            class="absolute top-[0rem] left-[0rem] rounded-4xs bg-gray-1100 box-border w-[14.38rem] h-[2.5rem] border-[1px] border-solid border-lightskyblue-100"
          />
          <div
            class="absolute top-[0.58rem] left-[2.17rem] font-semibold inline-block w-[9.94rem] h-[1.31rem]"
          >
            Buy Now
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
  import { defineComponent } from "vue";

  export default defineComponent({
    name: "NFTCard",
    props: {
      image2: { type: String },
      propLeft: { type: [Object, Array, String, Number, Boolean] },
      propLeft1: { type: [Object, Array, String, Number, Boolean] },
      propHeight: { type: [Object, Array, String, Number, Boolean] },
      propLeft2: { type: [Object, Array, String, Number, Boolean] },
    },
    computed: {
      nFTCardStyle() {
        return {
          left: this.propLeft,
        };
      },
      image2IconStyle() {
        return {
          left: this.propLeft1,
          height: this.propHeight,
        };
      },
      frameDivStyle() {
        return {
          left: this.propLeft2,
        };
      },
    },
  });
</script>
