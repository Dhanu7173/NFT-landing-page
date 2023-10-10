<template>
  <div
    class="absolute top-[211.56rem] left-[-1.31rem] bg-gray-1600 w-[120.13rem] flex flex-col items-center justify-start py-[5rem] px-[12.19rem] box-border gap-[3.75rem] text-left text-[3rem] text-neutral-0 font-caption-work-sans"
  >
    <div
      class="w-[102.56rem] flex flex-row items-end justify-center gap-[42.63rem]"
    >
      <div
        class="w-[43.94rem] flex flex-col items-start justify-start gap-[0.63rem]"
      >
        <div class="self-stretch flex flex-row items-start justify-start">
          <div class="flex-1 relative leading-[120%] capitalize font-extrabold">
            Top creators
          </div>
        </div>
        <div
          class="self-stretch flex flex-row items-start justify-start text-[1.38rem]"
        >
          <div class="flex-1 relative leading-[160%] capitalize">
            Checkout Top Rated Creators on the NFT Marketplace
          </div>
        </div>
      </div>
      <div
        class="rounded-xl box-border h-[3.75rem] flex flex-row items-center justify-center py-[0rem] px-[3.13rem] gap-[0.75rem] text-center text-[1rem] border-[2px] border-solid border-steelblue-400"
      >
        <img
          class="relative w-[1.25rem] h-[1.25rem]"
          alt=""
          src="/rocketlaunch2.svg"
        />
        <div class="relative leading-[140%] font-semibold">View Rankings</div>
      </div>
    </div>
    <div
      class="w-[103.88rem] flex flex-col items-start justify-start py-[0rem] pr-[1.38rem] pl-[0rem] box-border gap-[1.88rem] text-center text-[1.38rem]"
    >
      <ArtistCardsRow
        imageId="/avatar-placeholder1@2x.png"
        componentName="Keepitreal"
        thumbnailId="1"
        imageDimensions="/avatar-placeholder2@2x.png"
        componentImageUrl="DigiLab"
        imageDimensionsId="2"
        imageDimensionsUrl="/avatar-placeholder3@2x.png"
        componentImageId="GravityOne"
        imageDimensionsCode="3"
        imageCode="/avatar-placeholder4@2x.png"
        entityImageUrl="Juanie"
        imageDimensionsCode2="4"
      /><ArtistCardsRow
        imageId="/avatar-placeholder5@2x.png"
        componentName="BlueWhale"
        thumbnailId="5"
        imageDimensions="/avatar-placeholder6@2x.png"
        componentImageUrl="mr fox"
        imageDimensionsId="6"
        imageDimensionsUrl="/avatar-placeholder7@2x.png"
        componentImageId="Shroomie"
        imageDimensionsCode="7"
        imageCode="/avatar-placeholder8@2x.png"
        entityImageUrl="robotica"
        imageDimensionsCode2="8"
        propHeight="16.31rem"
        propBorderRadius="100px"
        propHeight1="16.31rem"
        propBorderRadius1="100px"
        propLeft="calc(50% - 5px)"
        propHeight2="16.31rem"
        propBorderRadius2="120px"
        propLeft1="calc(50% - 5px)"
        propHeight3="16.31rem"
        propBorderRadius3="120px"
        propLeft2="calc(50% - 5px)"
      /><ArtistCardsRow
        imageId="/avatar-placeholder9@2x.png"
        componentName="RustyRobot"
        thumbnailId="9"
        imageDimensions="/avatar-placeholder10@2x.png"
        componentImageUrl="animakid"
        imageDimensionsId="10"
        imageDimensionsUrl="/avatar-placeholder11@2x.png"
        componentImageId="Dotgu"
        imageDimensionsCode="11"
        imageCode="/avatar-placeholder12@2x.png"
        entityImageUrl="Ghiblier"
        imageDimensionsCode2="12"
        propHeight="16.25rem"
        propBorderRadius="120px"
        propHeight1="16.25rem"
        propBorderRadius1="120px"
        propLeft="calc(50% - 10px)"
        propHeight2="16.25rem"
        propBorderRadius2="120px"
        propLeft1="calc(50% - 10px)"
        propHeight3="16.25rem"
        propBorderRadius3="120px"
        propLeft2="calc(50% - 10px)"
      />
    </div>
  </div>
</template>
<script>
  import { defineComponent } from "vue";
  import ArtistCardsRow from "./ArtistCardsRow.vue";

  export default defineComponent({
    name: "TopRatedArtists",
    components: { ArtistCardsRow },
  });
</script>
