<template>
  <img
    class="w-[276px] h-[276px] overflow-hidden"
    alt=""
    :src="setupWalletIconSetupWalle"
    :style="setupWalletIconStyle"
  />
</template>
<script>
  import { defineComponent } from "vue";

  export default defineComponent({
    name: "SetupWalletIcon",
    props: {
      setupWalletIconSetupWalle: { type: String },
      setupWalletIconWidth: { type: [Object, Array, String, Number, Boolean] },
      setupWalletIconHeight: { type: [Object, Array, String, Number, Boolean] },
      setupWalletIconPosition: { type: String },
      setupWalletIconFlexShrink: { type: String },
    },
    computed: {
      setupWalletIconStyle() {
        return {
          width: this.setupWalletIconWidth,
          height: this.setupWalletIconHeight,
          position: this.setupWalletIconPosition,
          flexShrink: this.setupWalletIconFlexShrink,
        };
      },
    },
  });
</script>
