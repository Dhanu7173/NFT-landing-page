<template>
  <img
    class="w-[276px] h-[276px] overflow-hidden"
    alt=""
    :src="startEarningIconStartEarn"
    :style="startEarningIconStyle"
  />
</template>
<script>
  import { defineComponent } from "vue";

  export default defineComponent({
    name: "StartEarningIcon",
    props: {
      startEarningIconStartEarn: { type: String },
      startEarningIconWidth: { type: [Object, Array, String, Number, Boolean] },
      startEarningIconHeight: {
        type: [Object, Array, String, Number, Boolean],
      },
      startEarningIconPosition: { type: String },
      startEarningIconFlexShrink: { type: String },
    },
    computed: {
      startEarningIconStyle() {
        return {
          width: this.startEarningIconWidth,
          height: this.startEarningIconHeight,
          position: this.startEarningIconPosition,
          flexShrink: this.startEarningIconFlexShrink,
        };
      },
    },
  });
</script>
