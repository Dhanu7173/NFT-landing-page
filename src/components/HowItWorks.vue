<template>
  <div
    class="absolute top-[281.25rem] left-[-0.37rem] bg-gray-1500 w-[120.13rem] flex flex-col items-center justify-start py-[5rem] px-[12.19rem] box-border gap-[3rem] text-center text-[3rem] text-neutral-0 font-caption-work-sans"
  >
    <div
      class="w-[92.88rem] flex flex-col items-center justify-center gap-[0.63rem]"
    >
      <div
        class="relative leading-[120%] capitalize font-semibold inline-block w-[65.63rem]"
      >
        How it works
      </div>
      <div
        class="relative text-[1.38rem] leading-[160%] capitalize inline-block w-[65.63rem]"
      >
        Find out how to get started
      </div>
    </div>
    <div
      class="w-[103.63rem] flex flex-row items-start justify-start gap-[4.88rem] text-[1.38rem]"
    >
      <InfoCard
        imageId="/icon.svg"
        actionDescription="Setup Your wallet"
        walletSetupDescription="Set up your wallet of choice. Connect it to the Animarket by clicking the wallet icon in the top right corner."
      /><InfoCard
        imageId="/icon1.svg"
        actionDescription="Create Collection"
        walletSetupDescription="Upload your work and setup your collection. Add a description, social links and floor price."
      /><InfoCard
        imageId="/icon2.svg"
        actionDescription="Start Earning"
        walletSetupDescription="Choose between auctions and fixed-price listings. Start earning by selling your NFTs or trading others."
      /><InfoCard
        imageId="/icon3.svg"
        actionDescription="Start Earning"
        walletSetupDescription="Choose between auctions and fixed-price listings. Start earning by selling your NFTs or trading others."
      />
    </div>
  </div>
</template>
<script>
  import { defineComponent } from "vue";
  import InfoCard from "./InfoCard.vue";

  export default defineComponent({
    name: "HowItWorks",
    components: { InfoCard },
  });
</script>
