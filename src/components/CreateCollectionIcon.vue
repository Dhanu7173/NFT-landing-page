<template>
  <img
    class="w-[276px] h-[276px] overflow-hidden"
    alt=""
    :src="createCollectionIconCreat"
    :style="createCollectionIconStyle"
  />
</template>
<script>
  import { defineComponent } from "vue";

  export default defineComponent({
    name: "CreateCollectionIcon",
    props: {
      createCollectionIconCreat: { type: String },
      createCollectionIconWidth: {
        type: [Object, Array, String, Number, Boolean],
      },
      createCollectionIconHeight: {
        type: [Object, Array, String, Number, Boolean],
      },
      createCollectionIconPosition: { type: String },
      createCollectionIconFlexShrink: { type: String },
    },
    computed: {
      createCollectionIconStyle() {
        return {
          width: this.createCollectionIconWidth,
          height: this.createCollectionIconHeight,
          position: this.createCollectionIconPosition,
          flexShrink: this.createCollectionIconFlexShrink,
        };
      },
    },
  });
</script>
