<template>
  <div
    class="relative w-full flex flex-row items-start justify-start gap-[8.06rem] text-left text-[2.5rem] text-neutral-0 font-poppins overflow-x-hidden"
  >
    <div
      class="relative [background:linear-gradient(31.67deg,_rgba(3,_14,_21,_0.96),_#05121b)] w-[120rem] h-[355.5rem]"
    >
      <img
        class="absolute top-[0.25rem] left-[0rem] w-[120rem] h-[65.44rem] object-cover"
        alt=""
        src="/image-3@2x.png"
      />
      <div
        class="absolute top-[338.34rem] left-[-8.2rem] bg-gray-1300 w-[138.54rem] h-[55.78rem] [transform:_rotate(-14.72deg)] [transform-origin:0_0]"
      />
      <div
        class="absolute top-[416.17rem] left-[123.93rem] bg-gray-1200 w-[170.44rem] h-[50.38rem] [transform:_rotate(-159.24deg)] [transform-origin:0_0]"
      />
      <div
        class="absolute top-[60.31rem] left-[0rem] [background:linear-gradient(0deg,_#05121b,_rgba(4,_13,_20,_0.59)_33.45%,_rgba(2,_8,_12,_0.45)_62.45%,_rgba(0,_0,_0,_0))] w-[120rem] h-[8.75rem]"
      />
      <div
        class="absolute top-[0.25rem] left-[77.81rem] rounded-504xl-5 [background:radial-gradient(50%_50%_at_50%_50%,_rgba(202,_157,_255,_0.4),_rgba(119,_149,_255,_0))] [backdrop-filter:blur(4px)] w-[66.25rem] h-[65.44rem] opacity-[0.3]"
      />
      <HowItWorks /><Tranding1 /><Tranding />
      <div
        class="absolute top-[17rem] left-[10.19rem] w-[99.63rem] h-[38.19rem] flex flex-row items-start justify-start gap-[1.88rem]"
      >
        <HeroTextButtons /><HighlightedNFT />
      </div>
      <Navigation1 :onNavLogoClick="onNavLogoClick" /><TopRatedArtists />
      <footer
        imageDimensions="/storefront.svg"
        imageCode="/discordlogo.svg"
        imageCodeDimensions="/youtubelogo.svg"
        imageCodeDimensions2="/twitterlogo.svg"
        imageCodeDimensionsText="/instagramlogo.svg"
        imageCodeDimensionsText2="/envelopesimple.svg"
        :onDiscordLogoIconClick="onDiscordLogoIconClick"
        :onYoutubeLogoIconClick="onYoutubeLogoIconClick"
        :onTwitterLogoIconClick="onTwitterLogoIconClick"
        :onInstagramLogoIconClick="onInstagramLogoIconClick"
      />
    </div>
    <div
      class="relative [background:linear-gradient(180deg,_#05121b,_#05121b,_rgba(5,_18,_27,_0.89))] w-[120rem] h-[316.56rem] overflow-hidden shrink-0 hidden"
    >
      <img
        class="absolute top-[0rem] left-[0rem] w-[120rem] h-[47.31rem] object-cover mix-blend-normal"
        alt=""
        src="/rectangle-2@2x.png"
      />
      <div
        class="absolute top-[297.82rem] left-[-5.45rem] bg-gray-1300 w-[138.54rem] h-[55.78rem] [transform:_rotate(-14.72deg)] [transform-origin:0_0]"
      />
      <div
        class="absolute top-[375.65rem] left-[126.68rem] bg-gray-1200 w-[170.44rem] h-[50.38rem] [transform:_rotate(-159.24deg)] [transform-origin:0_0]"
      />
      <div
        class="absolute top-[0.25rem] left-[77.81rem] rounded-504xl-5 [background:radial-gradient(50%_50%_at_50%_50%,_rgba(202,_157,_255,_0.4),_rgba(119,_149,_255,_0))] [backdrop-filter:blur(4px)] w-[66.25rem] h-[65.44rem] opacity-[0.3]"
      />
      <footer
        imageDimensions="/storefront1.svg"
        imageCode="/discordlogo1.svg"
        imageCodeDimensions="/youtubelogo1.svg"
        imageCodeDimensions2="/twitterlogo1.svg"
        imageCodeDimensionsText="/instagramlogo1.svg"
        imageCodeDimensionsText2="/envelopesimple1.svg"
        propTop="288.17rem"
        propLeft="0.38rem"
        :onDiscordLogoIconClick="onDiscordLogoIcon1Click"
        :onYoutubeLogoIconClick="onYoutubeLogoIcon1Click"
        :onTwitterLogoIconClick="onTwitterLogoIcon1Click"
        :onInstagramLogoIconClick="onInstagramLogoIcon1Click"
      />
      <div
        class="absolute top-[54.75rem] left-[8.75rem] w-[101.64rem] h-[203.06rem]"
      >
        <div
          class="absolute top-[0rem] left-[25.44rem] tracking-[0.06em] font-extrabold inline-block w-[41.81rem] h-[3.61rem]"
        >
          EVERYTHING YOU NEED TO SEE
        </div>
        <div
          class="absolute top-[6.5rem] left-[92.69rem] rounded-xl [background:linear-gradient(270deg,_#4287f6,_#d3e5fe)] w-[8.81rem] h-[2.94rem] flex flex-row items-center justify-center py-[0rem] px-[3.13rem] box-border text-center text-[1rem] font-caption-work-sans"
        >
          <div class="relative leading-[140%] font-semibold">Sort by</div>
        </div>
        <div
          class="absolute top-[calc(50%_-_1525.5px)] left-[25.44rem] w-[62.44rem] h-[3rem] flex flex-row items-start justify-start pt-[0rem] pb-[0.63rem] pr-[0.63rem] pl-[0rem] box-border gap-[0.63rem] text-center text-[0.88rem] text-silver-100 font-inter"
        >
          <div
            class="rounded-lg [background:linear-gradient(180deg,_#7646ff,_rgba(37,_48,_142,_0.88))] w-[6.81rem] h-[3rem] flex flex-row items-center justify-center pt-[0.56rem] pb-[0.63rem] pr-[1.1rem] pl-[1.13rem] box-border text-neutral-0"
          >
            <div class="relative capitalize font-semibold">advisory</div>
          </div>
          <div
            class="rounded-lg box-border w-[10.88rem] h-[3rem] flex flex-row items-center justify-center pt-[0.56rem] pb-[0.63rem] pr-[1.19rem] pl-[1.25rem] border-[0.3px] border-solid border-cornflowerblue-100"
          >
            <div class="relative capitalize font-semibold">printmaking</div>
          </div>
          <div
            class="rounded-lg box-border w-[6.13rem] h-[3rem] flex flex-row items-center justify-center pt-[0.56rem] pb-[0.63rem] pr-[1.12rem] pl-[1.13rem] border-[0.3px] border-solid border-cornflowerblue-100"
          >
            <div class="relative capitalize font-semibold">printing</div>
          </div>
          <div
            class="rounded-lg box-border w-[8.31rem] h-[3rem] flex flex-row items-center justify-center pt-[0.56rem] pb-[0.63rem] pr-[1.12rem] pl-[1.19rem] border-[0.3px] border-solid border-cornflowerblue-100"
          >
            <div class="relative capitalize font-semibold">Digital Art</div>
          </div>
          <div
            class="rounded-lg box-border w-[5.94rem] h-[3rem] flex flex-row items-center justify-center pt-[0.56rem] pb-[0.63rem] pr-[1.14rem] pl-[1.13rem] border-[0.3px] border-solid border-cornflowerblue-100"
          >
            <div class="relative capitalize font-semibold">Drawing</div>
          </div>
          <div
            class="rounded-lg box-border w-[7.06rem] h-[3rem] flex flex-row items-center justify-center pt-[0.56rem] pb-[0.63rem] pr-[1.08rem] pl-[1.06rem] border-[0.3px] border-solid border-cornflowerblue-100"
          >
            <div class="relative capitalize font-semibold">Prints</div>
          </div>
          <div
            class="rounded-lg box-border w-[8.06rem] h-[3rem] flex flex-row items-center justify-center pt-[0.56rem] pb-[0.63rem] pr-[1.16rem] pl-[1.13rem] border-[0.3px] border-solid border-cornflowerblue-100"
          >
            <div class="relative capitalize font-semibold">Sculpture</div>
          </div>
          <div
            class="rounded-lg box-border w-[4.88rem] h-[3rem] flex flex-row items-center justify-center pt-[0.56rem] pb-[0.63rem] pr-[1.11rem] pl-[1.06rem] border-[0.3px] border-solid border-cornflowerblue-100"
          >
            <div class="relative capitalize font-semibold">All</div>
          </div>
        </div>
        <div
          class="absolute top-[0rem] left-[0rem] box-border w-[19rem] flex flex-col items-start justify-start py-[0rem] pr-[2rem] pl-[0rem] gap-[1.25rem] text-[0.81rem] text-gainsboro-100 font-bold-text-sm border-r-[1px] border-solid border-neutral-50"
        >
          <div
            class="self-stretch flex flex-row items-start justify-start pt-[1.06rem] px-[0rem] pb-[1.5rem] text-[1.25rem] text-neutral-0 border-b-[1px] border-solid border-neutral-50"
          >
            <b class="relative leading-[150%]">Filters </b>
          </div>
          <div
            class="self-stretch flex flex-col items-start justify-start pt-[0rem] px-[0rem] pb-[1.25rem] gap-[1.25rem] text-[0.88rem] text-gray-100 border-b-[1px] border-solid border-neutral-50"
          >
            <b class="relative tracking-[1px] leading-[150%]">Size</b>
            <div
              class="flex flex-col items-start justify-start gap-[0.75rem] text-lightskyblue-200"
            >
              <div
                class="flex flex-row items-center justify-start gap-[0.75rem]"
              >
                <div
                  class="rounded-81xl bg-neutral-0 box-border w-[1.25rem] h-[1.25rem] flex flex-col items-center justify-center border-[1px] border-solid border-neutral-50"
                >
                  <div
                    class="relative rounded-[50%] bg-neutral-0 box-border w-[0.88rem] h-[0.88rem] border-[3px] border-solid border-neutral-0"
                  />
                </div>
                <div
                  class="relative leading-[150%] [text-shadow:9px_4px_3px_rgba(206,_199,_199,_0.25)]"
                >
                  Small
                </div>
                <div
                  class="relative box-border w-[0.06rem] h-[0.75rem] border-r-[1px] border-solid border-neutral-50"
                />
                <div
                  class="relative leading-[150%] font-light text-neutral-200"
                >
                  12
                </div>
              </div>
              <div
                class="flex flex-row items-center justify-start gap-[0.75rem]"
              >
                <div
                  class="rounded-81xl bg-royalblue w-[1.25rem] h-[1.25rem] flex flex-col items-center justify-center"
                >
                  <div
                    class="relative rounded-[50%] bg-neutral-0 w-[0.5rem] h-[0.5rem]"
                  />
                </div>
                <div
                  class="relative leading-[150%] [text-shadow:9px_4px_3px_rgba(206,_199,_199,_0.25)]"
                >
                  Medium
                </div>
                <div
                  class="relative box-border w-[0.06rem] h-[0.75rem] border-r-[1px] border-solid border-neutral-50"
                />
                <div
                  class="relative leading-[150%] font-light text-neutral-200"
                >
                  430
                </div>
              </div>
              <div
                class="flex flex-row items-center justify-start gap-[0.75rem]"
              >
                <div
                  class="rounded-81xl bg-neutral-0 box-border w-[1.25rem] h-[1.25rem] flex flex-col items-center justify-center border-[1px] border-solid border-neutral-50"
                >
                  <div
                    class="relative rounded-[50%] bg-neutral-0 box-border w-[0.88rem] h-[0.88rem] border-[3px] border-solid border-neutral-0"
                  />
                </div>
                <div
                  class="relative leading-[150%] [text-shadow:9px_4px_3px_rgba(206,_199,_199,_0.25)]"
                >
                  large
                </div>
                <div
                  class="relative box-border w-[0.06rem] h-[0.75rem] border-r-[1px] border-solid border-neutral-50"
                />
                <div
                  class="relative leading-[150%] font-light text-neutral-200"
                >
                  40
                </div>
              </div>
            </div>
          </div>
          <div
            class="self-stretch flex flex-col items-start justify-start pt-[0rem] px-[0rem] pb-[1.5rem] gap-[1.25rem] text-[0.75rem] text-gray-300 border-b-[1px] border-solid border-neutral-50"
          >
            <b class="relative tracking-[1px] leading-[150%]"
              >FILTER BY PRICE</b
            >
            <div
              class="self-stretch flex flex-col items-start justify-start gap-[1.5rem] text-neutral-900"
            >
              <div class="relative w-[17rem] h-[3rem]">
                <div
                  class="absolute top-[2.69rem] left-[0rem] rounded-81xl bg-snow w-[17rem] h-[0.13rem] flex flex-col items-start justify-start"
                >
                  <div
                    class="self-stretch relative rounded-81xl bg-dodgerblue-100 h-[0.19rem]"
                  />
                </div>
                <div
                  class="absolute top-[0rem] left-[0rem] w-[17rem] flex flex-row items-start justify-between"
                >
                  <div
                    class="flex flex-col items-start justify-start gap-[0.75rem]"
                  >
                    <div
                      class="rounded-81xl bg-neutral-50 h-[1.75rem] flex flex-row items-center justify-center pt-[0.25rem] px-[0.63rem] pb-[0.31rem] box-border"
                    >
                      <div class="relative leading-[150%]">$0</div>
                    </div>
                    <div
                      class="rounded-81xl bg-neutral-0 shadow-[0px_4px_8px_rgba(0,_0,_0,_0.1)] box-border w-[0.63rem] h-[0.63rem] border-[2px] border-solid border-black"
                    />
                  </div>
                  <div
                    class="flex flex-col items-end justify-start gap-[0.75rem] text-neutral-0"
                  >
                    <div
                      class="rounded-81xl bg-mediumslateblue h-[1.75rem] flex flex-row items-center justify-center pt-[0.25rem] px-[0.63rem] pb-[0.31rem] box-border"
                    >
                      <div class="relative leading-[150%]">$50,000.00</div>
                    </div>
                    <div
                      class="rounded-81xl bg-neutral-0 shadow-[0px_4px_8px_rgba(0,_0,_0,_0.1)] box-border w-[0.63rem] h-[0.63rem] border-[2px] border-solid border-black"
                    />
                  </div>
                </div>
              </div>
              <div
                class="rounded-lg [background:linear-gradient(180deg,_#7646ff,_rgba(37,_48,_142,_0.88))] w-[8rem] h-[2.5rem] flex flex-row items-center justify-center pt-[0.56rem] pb-[0.63rem] pr-[1.1rem] pl-[1.13rem] box-border text-[0.88rem] text-neutral-0"
              >
                <b class="relative leading-[150%]">FILTER</b>
              </div>
            </div>
          </div>
          <div
            class="self-stretch flex flex-col items-start justify-start pt-[0rem] px-[0rem] pb-[1.25rem] gap-[1.25rem] text-[0.75rem] text-whitesmoke border-b-[1px] border-solid border-neutral-50"
          >
            <b class="relative tracking-[1px] leading-[150%]">ORDER BY</b>
            <div
              class="flex flex-col items-start justify-start gap-[0.75rem] text-[0.88rem] text-lightskyblue-200"
            >
              <div
                class="flex flex-row items-center justify-start gap-[0.75rem]"
              >
                <div
                  class="rounded-81xl bg-neutral-0 box-border w-[1.25rem] h-[1.25rem] flex flex-col items-center justify-center border-[1px] border-solid border-neutral-50"
                >
                  <div
                    class="relative rounded-[50%] bg-neutral-0 box-border w-[0.88rem] h-[0.88rem] border-[3px] border-solid border-neutral-0"
                  />
                </div>
                <div
                  class="relative leading-[150%] [text-shadow:9px_4px_3px_rgba(206,_199,_199,_0.25)]"
                >
                  Default
                </div>
              </div>
              <div
                class="flex flex-row items-center justify-start gap-[0.75rem]"
              >
                <div
                  class="rounded-81xl bg-cornflowerblue-200 w-[1.25rem] h-[1.25rem] flex flex-col items-center justify-center"
                >
                  <div
                    class="relative rounded-[50%] bg-neutral-0 w-[0.5rem] h-[0.5rem]"
                  />
                </div>
                <div
                  class="relative leading-[150%] [text-shadow:9px_4px_3px_rgba(206,_199,_199,_0.25)]"
                >
                  Review Count
                </div>
              </div>
              <div
                class="flex flex-row items-center justify-start gap-[0.75rem]"
              >
                <div
                  class="rounded-81xl bg-neutral-0 box-border w-[1.25rem] h-[1.25rem] flex flex-col items-center justify-center border-[1px] border-solid border-neutral-50"
                >
                  <div
                    class="relative rounded-[50%] bg-neutral-0 box-border w-[0.88rem] h-[0.88rem] border-[3px] border-solid border-neutral-0"
                  />
                </div>
                <div
                  class="relative leading-[150%] [text-shadow:9px_4px_3px_rgba(206,_199,_199,_0.25)]"
                >
                  Popularity
                </div>
              </div>
              <div
                class="flex flex-row items-center justify-start gap-[0.75rem]"
              >
                <div
                  class="rounded-81xl bg-neutral-0 box-border w-[1.25rem] h-[1.25rem] flex flex-col items-center justify-center border-[1px] border-solid border-neutral-50"
                >
                  <div
                    class="relative rounded-[50%] bg-neutral-0 box-border w-[0.88rem] h-[0.88rem] border-[3px] border-solid border-neutral-0"
                  />
                </div>
                <div
                  class="relative leading-[150%] [text-shadow:9px_4px_3px_rgba(206,_199,_199,_0.25)]"
                >
                  Average Rating
                </div>
              </div>
              <div
                class="flex flex-row items-center justify-start gap-[0.75rem]"
              >
                <div
                  class="rounded-81xl bg-neutral-0 box-border w-[1.25rem] h-[1.25rem] flex flex-col items-center justify-center border-[1px] border-solid border-neutral-50"
                >
                  <div
                    class="relative rounded-[50%] bg-neutral-0 box-border w-[0.88rem] h-[0.88rem] border-[3px] border-solid border-neutral-0"
                  />
                </div>
                <div
                  class="relative leading-[150%] [text-shadow:9px_4px_3px_rgba(206,_199,_199,_0.25)]"
                >
                  Newness
                </div>
              </div>
              <div
                class="flex flex-row items-center justify-start gap-[0.75rem]"
              >
                <div
                  class="rounded-81xl bg-neutral-0 box-border w-[1.25rem] h-[1.25rem] flex flex-col items-center justify-center border-[1px] border-solid border-neutral-50"
                >
                  <div
                    class="relative rounded-[50%] bg-neutral-0 box-border w-[0.88rem] h-[0.88rem] border-[3px] border-solid border-neutral-0"
                  />
                </div>
                <div
                  class="relative leading-[150%] [text-shadow:9px_4px_3px_rgba(206,_199,_199,_0.25)]"
                >
                  Price: Low to High
                </div>
              </div>
              <div
                class="flex flex-row items-center justify-start gap-[0.75rem]"
              >
                <div
                  class="rounded-81xl bg-neutral-0 box-border w-[1.25rem] h-[1.25rem] flex flex-col items-center justify-center border-[1px] border-solid border-neutral-50"
                >
                  <div
                    class="relative rounded-[50%] bg-neutral-0 box-border w-[0.88rem] h-[0.88rem] border-[3px] border-solid border-neutral-0"
                  />
                </div>
                <div
                  class="relative leading-[150%] [text-shadow:9px_4px_3px_rgba(206,_199,_199,_0.25)]"
                >
                  Price: High to Low
                </div>
              </div>
              <div
                class="flex flex-row items-center justify-start gap-[0.75rem]"
              >
                <div
                  class="rounded-81xl bg-neutral-0 box-border w-[1.25rem] h-[1.25rem] flex flex-col items-center justify-center border-[1px] border-solid border-neutral-50"
                >
                  <div
                    class="relative rounded-[50%] bg-neutral-0 box-border w-[0.88rem] h-[0.88rem] border-[3px] border-solid border-neutral-0"
                  />
                </div>
                <div
                  class="relative leading-[150%] [text-shadow:9px_4px_3px_rgba(206,_199,_199,_0.25)]"
                >
                  Random Products
                </div>
              </div>
              <div
                class="flex flex-row items-center justify-start gap-[0.75rem]"
              >
                <div
                  class="rounded-81xl bg-neutral-0 box-border w-[1.25rem] h-[1.25rem] flex flex-col items-center justify-center border-[1px] border-solid border-neutral-50"
                >
                  <div
                    class="relative rounded-[50%] bg-neutral-0 box-border w-[0.88rem] h-[0.88rem] border-[3px] border-solid border-neutral-0"
                  />
                </div>
                <div
                  class="relative leading-[150%] [text-shadow:9px_4px_3px_rgba(206,_199,_199,_0.25)]"
                >
                  Product Name
                </div>
              </div>
            </div>
          </div>
          <div
            class="rounded-[1000px] bg-primary-50 h-[2.5rem] flex flex-row items-center justify-start py-[0rem] px-[2rem] box-border text-[0.88rem] text-crimson-200"
          >
            <div class="relative leading-[150%]">Clear Filters</div>
          </div>
          <div
            class="self-stretch flex flex-col items-start justify-start pt-[0rem] px-[0rem] pb-[1.5rem] border-b-[1px] border-solid border-neutral-50"
          >
            <b class="relative tracking-[1px] leading-[150%]">Color</b>
          </div>
          <div
            class="self-stretch flex flex-col items-start justify-start pt-[0rem] px-[0rem] pb-[1.5rem] border-b-[1px] border-solid border-neutral-50"
          >
            <b class="relative tracking-[1px] leading-[150%]">Style</b>
          </div>
          <div
            class="self-stretch flex flex-col items-start justify-start pt-[0rem] px-[0rem] pb-[1.5rem] border-b-[1px] border-solid border-neutral-50"
          >
            <b class="relative tracking-[1px] leading-[150%]">Subject</b>
          </div>
          <div
            class="self-stretch flex flex-col items-start justify-start pt-[0rem] px-[0rem] pb-[1.5rem] border-b-[1px] border-solid border-neutral-50"
          >
            <b class="relative tracking-[1px] leading-[150%]">Medium</b>
          </div>
          <div
            class="self-stretch flex flex-col items-start justify-start pt-[0rem] px-[0rem] pb-[1.5rem] border-b-[1px] border-solid border-neutral-50"
          >
            <b class="relative tracking-[1px] leading-[150%]">Mojarto Picks</b>
          </div>
          <div
            class="self-stretch flex flex-col items-start justify-start pt-[0rem] px-[0rem] pb-[1.5rem] border-b-[1px] border-solid border-neutral-50"
          >
            <b class="relative tracking-[1px] leading-[150%]">Artist</b>
          </div>
        </div>
        <div
          class="absolute top-[13.38rem] left-[24.38rem] flex flex-col items-start justify-start gap-[3.13rem] text-[0.75rem] text-steelblue-200"
        >
          <div class="relative w-[77.27rem] h-[35.44rem]">
            <div
              class="absolute top-[0rem] left-[0rem] w-[24.05rem] h-[35.44rem]"
            >
              <div
                class="absolute top-[0rem] left-[0rem] rounded-lg bg-gray-1100 box-border w-[24.05rem] h-[35.44rem] border-[2px] border-solid border-steelblue-400"
              />
              <img
                class="absolute top-[1.63rem] left-[1.56rem] rounded-lgi w-[21.25rem] h-[19.19rem] object-cover"
                alt=""
                src="/image-22@2x.png"
              />
              <div
                class="absolute top-[22.44rem] left-[1.25rem] flex flex-col items-center justify-start gap-[0.56rem]"
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
                <div
                  class="flex flex-col items-start justify-start gap-[0.56rem]"
                >
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
                  <div
                    class="absolute top-[0rem] left-[0rem] rounded-4xs [background:linear-gradient(269.73deg,_rgba(193,_221,_253,_0.84)_12.27%,_#5495f7)] w-[14.38rem] h-[2.5rem]"
                  />
                  <div
                    class="absolute top-[0.58rem] left-[2.17rem] font-semibold inline-block w-[9.94rem] h-[1.31rem]"
                  >
                    Buy Now
                  </div>
                </div>
              </div>
            </div>
            <div
              class="absolute top-[0rem] left-[26.61rem] w-[24.05rem] h-[35.44rem]"
            >
              <div
                class="absolute top-[0rem] left-[0rem] rounded-lg bg-gray-1100 box-border w-[24.05rem] h-[35.44rem] border-[2px] border-solid border-steelblue-400"
              />
              <div
                class="absolute top-[22.44rem] left-[1.08rem] flex flex-col items-center justify-start gap-[0.56rem]"
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
                <div
                  class="flex flex-col items-start justify-start gap-[0.56rem]"
                >
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
                  <div
                    class="absolute top-[0rem] left-[0rem] w-[14.38rem] h-[2.5rem]"
                  >
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
              <img
                class="absolute top-[1.63rem] left-[1.64rem] rounded-lgi w-[21.25rem] h-[19.5rem] object-cover"
                alt=""
                src="/nft3@2x.png"
              />
            </div>
            <div
              class="absolute top-[0rem] left-[53.22rem] w-[24.05rem] h-[35.44rem]"
            >
              <div
                class="absolute top-[0rem] left-[0rem] rounded-lg bg-gray-1100 box-border w-[24.05rem] h-[35.44rem] border-[2px] border-solid border-steelblue-400"
              />
              <img
                class="absolute top-[1.63rem] left-[1.6rem] rounded-lgi w-[21.25rem] h-[19.5rem] object-cover"
                alt=""
                src="/image-23@2x.png"
              />
              <div
                class="absolute top-[22.44rem] left-[0.97rem] flex flex-col items-center justify-start gap-[0.56rem]"
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
                <div
                  class="flex flex-col items-start justify-start gap-[0.56rem]"
                >
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
                  <div
                    class="absolute top-[0rem] left-[0rem] w-[14.38rem] h-[2.5rem]"
                  >
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
          </div>
          <div class="relative w-[77.27rem] h-[35.44rem]">
            <div
              class="absolute top-[0rem] left-[0rem] w-[24.05rem] h-[35.44rem]"
            >
              <div
                class="absolute top-[0rem] left-[0rem] rounded-lg bg-gray-1100 box-border w-[24.05rem] h-[35.44rem] border-[2px] border-solid border-steelblue-400"
              />
              <img
                class="absolute top-[1.63rem] left-[1.56rem] rounded-lgi w-[21.25rem] h-[19.19rem] object-cover"
                alt=""
                src="/image-22@2x.png"
              />
              <div
                class="absolute top-[22.44rem] left-[1.25rem] flex flex-col items-center justify-start gap-[0.56rem]"
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
                <div
                  class="flex flex-col items-start justify-start gap-[0.56rem]"
                >
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
                  <div
                    class="absolute top-[0rem] left-[0rem] w-[14.38rem] h-[2.5rem]"
                  >
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
            <div
              class="absolute top-[0rem] left-[26.61rem] w-[24.05rem] h-[35.44rem]"
            >
              <div
                class="absolute top-[0rem] left-[0rem] rounded-lg bg-gray-1100 box-border w-[24.05rem] h-[35.44rem] border-[2px] border-solid border-steelblue-400"
              />
              <div
                class="absolute top-[22.44rem] left-[1.08rem] flex flex-col items-center justify-start gap-[0.56rem]"
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
                <div
                  class="flex flex-col items-start justify-start gap-[0.56rem]"
                >
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
                  <div
                    class="absolute top-[0rem] left-[0rem] w-[14.38rem] h-[2.5rem]"
                  >
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
              <img
                class="absolute top-[1.63rem] left-[1.64rem] rounded-lgi w-[21.25rem] h-[19.5rem] object-cover"
                alt=""
                src="/nft4@2x.png"
              />
            </div>
            <div
              class="absolute top-[0rem] left-[53.22rem] w-[24.05rem] h-[35.44rem]"
            >
              <div
                class="absolute top-[0rem] left-[0rem] rounded-lg bg-gray-1100 box-border w-[24.05rem] h-[35.44rem] border-[2px] border-solid border-steelblue-400"
              />
              <img
                class="absolute top-[1.63rem] left-[1.6rem] rounded-lgi w-[21.25rem] h-[19.5rem] object-cover"
                alt=""
                src="/image-23@2x.png"
              />
              <div
                class="absolute top-[22.44rem] left-[0.97rem] flex flex-col items-center justify-start gap-[0.56rem]"
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
                <div
                  class="flex flex-col items-start justify-start gap-[0.56rem]"
                >
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
                  <div
                    class="absolute top-[0rem] left-[0rem] w-[14.38rem] h-[2.5rem]"
                  >
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
          </div>
          <div class="relative w-[77.27rem] h-[35.44rem]">
            <NFTCard
              image2="/image-22@2x.png"
              propLeft="0rem"
              propLeft1="1.56rem"
              propHeight="19.19rem"
              propLeft2="1.25rem"
            />
            <div
              class="absolute top-[0rem] left-[26.61rem] w-[24.05rem] h-[35.44rem]"
            >
              <div
                class="absolute top-[0rem] left-[0rem] rounded-lg bg-gray-1100 box-border w-[24.05rem] h-[35.44rem] border-[2px] border-solid border-steelblue-400"
              />
              <div
                class="absolute top-[22.44rem] left-[1.08rem] flex flex-col items-center justify-start gap-[0.56rem]"
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
                <div
                  class="flex flex-col items-start justify-start gap-[0.56rem]"
                >
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
                  <div
                    class="absolute top-[0rem] left-[0rem] w-[14.38rem] h-[2.5rem]"
                  >
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
              <img
                class="absolute top-[1.63rem] left-[1.64rem] rounded-lgi w-[21.25rem] h-[19.5rem] object-cover"
                alt=""
                src="/nft4@2x.png"
              />
              <img
                class="absolute top-[1.63rem] left-[1.64rem] rounded-lgi w-[21.25rem] h-[19.5rem] object-cover"
                alt=""
                src="/nft3@2x.png"
              />
            </div>
            <NFTCard
              image2="/image-23@2x.png"
              propLeft="53.22rem"
              propLeft1="1.6rem"
              propHeight="19.5rem"
              propLeft2="0.97rem"
            />
          </div>
          <div class="relative w-[77.27rem] h-[35.44rem]">
            <div
              class="absolute top-[0rem] left-[0rem] w-[24.05rem] h-[35.44rem]"
            >
              <div
                class="absolute top-[0rem] left-[0rem] rounded-lg bg-gray-1100 box-border w-[24.05rem] h-[35.44rem] border-[2px] border-solid border-steelblue-400"
              />
              <img
                class="absolute top-[1.63rem] left-[1.56rem] rounded-lgi w-[21.25rem] h-[19.19rem] object-cover"
                alt=""
                src="/image-22@2x.png"
              />
              <div
                class="absolute top-[22.44rem] left-[1.25rem] flex flex-col items-center justify-start gap-[0.56rem]"
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
                <div
                  class="flex flex-col items-start justify-start gap-[0.56rem]"
                >
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
                  <div
                    class="absolute top-[0rem] left-[0rem] w-[14.38rem] h-[2.5rem]"
                  >
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
            <div
              class="absolute top-[0rem] left-[26.61rem] w-[24.05rem] h-[35.44rem]"
            >
              <div
                class="absolute top-[0rem] left-[0rem] rounded-lg bg-gray-1100 box-border w-[24.05rem] h-[35.44rem] border-[2px] border-solid border-steelblue-400"
              />
              <div
                class="absolute top-[22.44rem] left-[1.08rem] flex flex-col items-center justify-start gap-[0.56rem]"
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
                <div
                  class="flex flex-col items-start justify-start gap-[0.56rem]"
                >
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
                  <div
                    class="absolute top-[0rem] left-[0rem] w-[14.38rem] h-[2.5rem]"
                  >
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
              <img
                class="absolute top-[1.63rem] left-[1.64rem] rounded-lgi w-[21.25rem] h-[19.5rem] object-cover"
                alt=""
                src="/nft4@2x.png"
              />
            </div>
            <div
              class="absolute top-[0rem] left-[53.22rem] w-[24.05rem] h-[35.44rem]"
            >
              <div
                class="absolute top-[0rem] left-[0rem] rounded-lg bg-gray-1100 box-border w-[24.05rem] h-[35.44rem] border-[2px] border-solid border-steelblue-400"
              />
              <img
                class="absolute top-[1.63rem] left-[1.6rem] rounded-lgi w-[21.25rem] h-[19.5rem] object-cover"
                alt=""
                src="/image-23@2x.png"
              />
              <div
                class="absolute top-[22.44rem] left-[0.97rem] flex flex-col items-center justify-start gap-[0.56rem]"
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
                <div
                  class="flex flex-col items-start justify-start gap-[0.56rem]"
                >
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
                  <div
                    class="absolute top-[0rem] left-[0rem] w-[14.38rem] h-[2.5rem]"
                  >
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
          </div>
          <div class="relative w-[77.27rem] h-[35.44rem]">
            <div
              class="absolute top-[0rem] left-[0rem] w-[24.05rem] h-[35.44rem]"
            >
              <div
                class="absolute top-[0rem] left-[0rem] rounded-lg bg-gray-1100 box-border w-[24.05rem] h-[35.44rem] border-[2px] border-solid border-steelblue-400"
              />
              <img
                class="absolute top-[1.63rem] left-[1.56rem] rounded-lgi w-[21.25rem] h-[19.19rem] object-cover"
                alt=""
                src="/image-22@2x.png"
              />
              <div
                class="absolute top-[22.44rem] left-[1.25rem] flex flex-col items-center justify-start gap-[0.56rem]"
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
                <div
                  class="flex flex-col items-start justify-start gap-[0.56rem]"
                >
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
                  <div
                    class="absolute top-[0rem] left-[0rem] w-[14.38rem] h-[2.5rem]"
                  >
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
            <div
              class="absolute top-[0rem] left-[26.61rem] w-[24.05rem] h-[35.44rem]"
            >
              <div
                class="absolute top-[0rem] left-[0rem] rounded-lg bg-gray-1100 box-border w-[24.05rem] h-[35.44rem] border-[2px] border-solid border-steelblue-400"
              />
              <div
                class="absolute top-[22.44rem] left-[1.08rem] flex flex-col items-center justify-start gap-[0.56rem]"
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
                <div
                  class="flex flex-col items-start justify-start gap-[0.56rem]"
                >
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
                  <div
                    class="absolute top-[0rem] left-[0rem] w-[14.38rem] h-[2.5rem]"
                  >
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
              <img
                class="absolute top-[1.63rem] left-[1.64rem] rounded-lgi w-[21.25rem] h-[19.5rem] object-cover"
                alt=""
                src="/nft4@2x.png"
              />
            </div>
            <div
              class="absolute top-[0rem] left-[53.22rem] w-[24.05rem] h-[35.44rem]"
            >
              <div
                class="absolute top-[0rem] left-[0rem] rounded-lg bg-gray-1100 box-border w-[24.05rem] h-[35.44rem] border-[2px] border-solid border-steelblue-400"
              />
              <img
                class="absolute top-[1.63rem] left-[1.6rem] rounded-lgi w-[21.25rem] h-[19.5rem] object-cover"
                alt=""
                src="/image-23@2x.png"
              />
              <div
                class="absolute top-[22.44rem] left-[0.97rem] flex flex-col items-center justify-start gap-[0.56rem]"
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
                <div
                  class="flex flex-col items-start justify-start gap-[0.56rem]"
                >
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
                  <div
                    class="absolute top-[0rem] left-[0rem] w-[14.38rem] h-[2.5rem]"
                  >
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
          </div>
        </div>
      </div>
      <div
        class="absolute top-[15.06rem] left-[10.19rem] w-[99.63rem] h-[24.75rem] flex flex-row items-center justify-center text-center text-[5rem]"
      >
        <div
          class="flex-1 flex flex-col items-center justify-center gap-[1.88rem]"
        >
          <div class="self-stretch flex flex-col items-center justify-center">
            <div
              class="relative leading-[110%] capitalize font-semibold flex items-center justify-center w-[86rem] h-[16.5rem] shrink-0"
            >
              Explore the NFT world, collect and sell your artwork
            </div>
          </div>
          <div
            class="rounded-xl [background:linear-gradient(270deg,_#4287f6,_#d3e5fe)] h-[3.75rem] flex flex-row items-center justify-center py-[0rem] px-[3.13rem] box-border gap-[0.75rem] text-[1rem] font-caption-work-sans"
          >
            <img
              class="relative w-[1.25rem] h-[1.25rem]"
              alt=""
              src="/rocketlaunch.svg"
            />
            <div class="relative leading-[140%] font-semibold">Get Started</div>
          </div>
        </div>
      </div>
      <Navigation1
        propHeight="7.56rem"
        propBackgroundColor="rgba(0, 0, 0, 0)"
        :onNavLogoClick="onNavLogo1Click"
      />
      <div
        class="absolute top-[263.44rem] left-[34.19rem] box-border w-[77.25rem] flex flex-row items-center justify-between pt-[1.5rem] px-[0rem] pb-[0rem] text-[1rem] text-gray-200 font-bold-text-sm border-t-[1px] border-solid border-neutral-50"
      >
        <b class="relative leading-[150%]">Showing 1-30 of 393 results</b>
        <div
          class="flex flex-row items-center justify-start gap-[0.75rem] text-[0.88rem] text-neutral-0"
        >
          <div
            class="rounded-81xl bg-steelblue-300 box-border w-[2.25rem] h-[2.25rem] flex flex-row items-center justify-center border-[1px] border-solid border-neutral-50"
          >
            <img
              class="relative w-[1.13rem] h-[1.13rem]"
              alt=""
              src="/vuesaxlineararrowleft.svg"
            />
          </div>
          <div class="flex flex-row items-center justify-start gap-[0.75rem]">
            <div
              class="rounded-81xl bg-secondary-50 w-[2.25rem] h-[2.25rem] flex flex-row items-center justify-center text-secondary-500"
            >
              <div class="relative leading-[150%]">1</div>
            </div>
            <div
              class="rounded-81xl bg-steelblue-300 w-[2.25rem] h-[2.25rem] flex flex-row items-center justify-center"
            >
              <div class="relative leading-[150%]">2</div>
            </div>
            <div
              class="rounded-81xl bg-steelblue-300 w-[2.25rem] h-[2.25rem] flex flex-row items-center justify-center"
            >
              <div class="relative leading-[150%]">3</div>
            </div>
            <div
              class="rounded-81xl bg-steelblue-300 w-[2.25rem] h-[2.25rem] flex flex-row items-center justify-center"
            >
              <div class="relative leading-[150%]">4</div>
            </div>
            <div
              class="rounded-md bg-steelblue-300 w-[1.25rem] h-[2.25rem] flex flex-row items-center justify-center"
            >
              <div class="relative leading-[150%]">...</div>
            </div>
            <div
              class="rounded-81xl bg-steelblue-300 w-[2.25rem] h-[2.25rem] flex flex-row items-center justify-center"
            >
              <div class="relative leading-[150%]">55</div>
            </div>
          </div>
          <div
            class="rounded-81xl bg-steelblue-300 box-border w-[2.25rem] h-[2.25rem] flex flex-row items-center justify-center border-[1px] border-solid border-neutral-50"
          >
            <img
              class="relative w-[1.13rem] h-[1.13rem]"
              alt=""
              src="/vuesaxlineararrowright.svg"
            />
          </div>
        </div>
        <div
          class="relative [text-decoration:underline] leading-[150%] text-neutral-30 hidden"
        >
          Clear
        </div>
        <div class="relative leading-[150%] text-neutral-60 hidden">
          Shop All Weed
        </div>
      </div>
    </div>
    <div
      class="relative bg-gray-1100 w-[120rem] h-[282.63rem] overflow-hidden shrink-0 hidden text-center text-[5rem]"
    >
      <img
        class="absolute top-[7.19rem] left-[0rem] w-[120rem] h-[40.44rem] object-cover"
        alt=""
        src="/image-4@2x.png"
      />
      <div
        class="absolute top-[10.19rem] left-[0rem] [background:linear-gradient(180deg,_rgba(0,_0,_0,_0),_rgba(54,_32,_69,_0.67)_48.96%,_rgba(112,_100,_120,_0))] w-[120rem] h-[38.88rem]"
      />
      <div
        class="absolute top-[0rem] left-[0rem] w-[120rem] h-[47.63rem] mix-blend-normal"
      />
      <div
        class="absolute top-[263.89rem] left-[-5.57rem] bg-gray-1300 w-[138.54rem] h-[55.78rem] [transform:_rotate(-14.72deg)] [transform-origin:0_0]"
      />
      <div
        class="absolute top-[341.71rem] left-[126.56rem] bg-gray-1200 w-[170.44rem] h-[50.38rem] [transform:_rotate(-159.24deg)] [transform-origin:0_0]"
      />
      <div
        class="absolute top-[0.25rem] left-[77.81rem] rounded-504xl-5 [background:radial-gradient(50%_50%_at_50%_50%,_rgba(202,_157,_255,_0.4),_rgba(119,_149,_255,_0))] [backdrop-filter:blur(4px)] w-[66.25rem] h-[65.44rem] opacity-[0.3]"
      />
      <footer
        imageDimensions="/storefront1.svg"
        imageCode="/discordlogo1.svg"
        imageCodeDimensions="/youtubelogo1.svg"
        imageCodeDimensions2="/twitterlogo1.svg"
        imageCodeDimensionsText="/instagramlogo1.svg"
        imageCodeDimensionsText2="/envelopesimple1.svg"
        propTop="254.23rem"
        propLeft="0.25rem"
        :onDiscordLogoIconClick="onDiscordLogoIcon2Click"
        :onYoutubeLogoIconClick="onYoutubeLogoIcon2Click"
        :onTwitterLogoIconClick="onTwitterLogoIcon2Click"
        :onInstagramLogoIconClick="onInstagramLogoIcon2Click"
      />
      <div
        class="absolute top-[15.06rem] left-[10.19rem] w-[99.63rem] h-[24.75rem] flex flex-row items-center justify-center"
      >
        <div
          class="flex-1 flex flex-col items-center justify-center gap-[1.88rem]"
        >
          <div class="self-stretch flex flex-col items-center justify-center">
            <div
              class="relative leading-[110%] capitalize font-semibold flex items-center justify-center w-[68.25rem] h-[12.63rem] shrink-0"
            >
              Welcome to the NFT world’s Blogs
            </div>
          </div>
          <div
            class="relative text-[1rem] leading-[110%] capitalize font-semibold flex items-center justify-center w-[41.31rem]"
          >
            informatic articals from our expert Guests, some important
            announc-ements fromour team and many more...
          </div>
        </div>
      </div>
      <Navigation1
        propHeight="7.56rem"
        propBackgroundColor="#05121b"
        :onNavLogoClick="onNavLogo2Click"
      />
      <div
        class="absolute top-[51.31rem] left-[5.25rem] flex flex-col items-center justify-start gap-[4.44rem] text-left text-[3rem]"
      >
        <div class="relative w-[109.5rem] h-[44.06rem]">
          <div
            class="absolute top-[0rem] left-[3.06rem] w-[103.88rem] h-[4.63rem]"
          >
            <div
              class="absolute top-[0rem] left-[0rem] tracking-[0.06em] font-extrabold"
            >
              Guides
            </div>
            <div
              class="absolute top-[0.88rem] left-[91.81rem] rounded-xl [background:linear-gradient(270deg,_#4287f6,_#d3e5fe)] w-[12.06rem] h-[3.75rem] flex flex-row items-center justify-center py-[0rem] px-[3.13rem] box-border text-center text-[1rem] text-gray-1100 font-caption-work-sans"
            >
              <div class="relative leading-[140%] font-semibold">
                Explore More
              </div>
            </div>
          </div>
          <div
            class="absolute top-[9.06rem] left-[0rem] w-[109.5rem] h-[35rem] text-[1.38rem]"
          >
            <div
              class="absolute top-[0rem] left-[75.13rem] w-[34.38rem] h-[35rem]"
            >
              <div
                class="absolute top-[0rem] left-[0rem] rounded-mini bg-gray-800 shadow-[0px_4px_8px_rgba(0,_0,_0,_0.58)] w-[34.38rem] h-[35rem]"
              />
              <img
                class="absolute top-[0rem] left-[0rem] rounded-t-xl rounded-b-none w-[34.38rem] h-[24.88rem] object-cover"
                alt=""
                src="/image-placeholder1@2x.png"
              />
              <div
                class="absolute top-[26.44rem] left-[2.31rem] w-[30.19rem] h-[7rem]"
              >
                <div class="absolute top-[0rem] left-[0rem] font-medium">
                  The guide to creating & selling digital artsd
                </div>
                <div
                  class="absolute top-[2.5rem] left-[0.5rem] text-[1rem] font-medium whitespace-pre-wrap text-center inline-block w-[29.69rem] text-darkgray-200"
                >
                  <p class="m-0">
                    It is a long established fact that a reader will be
                    distracted by the readable content of page when looking at
                    ...
                  </p>
                  <p class="m-0 text-cadetblue">
                    <span>Read more </span>
                    <span class="text-darkgray-200"> </span>
                  </p>
                </div>
              </div>
            </div>
            <div class="absolute top-[0rem] left-[0rem] w-[34.38rem] h-[35rem]">
              <div
                class="absolute top-[0rem] left-[0rem] rounded-mini bg-gray-800 shadow-[0px_4px_8px_rgba(0,_0,_0,_0.58)] w-[34.38rem] h-[35rem]"
              />
              <img
                class="absolute top-[0rem] left-[0rem] rounded-t-xl rounded-b-none w-[34.38rem] h-[24.88rem] object-cover"
                alt=""
                src="/image-placeholder1@2x.png"
              />
              <div
                class="absolute top-[26.44rem] left-[2.31rem] w-[30.19rem] h-[7rem]"
              >
                <div class="absolute top-[0rem] left-[0rem] font-medium">
                  The guide to creating & selling digital artsd
                </div>
                <div
                  class="absolute top-[2.5rem] left-[0.5rem] text-[1rem] font-medium whitespace-pre-wrap text-center inline-block w-[29.69rem] text-darkgray-200"
                >
                  <p class="m-0">
                    It is a long established fact that a reader will be
                    distracted by the readable content of page when looking at
                    ...
                  </p>
                  <p class="m-0 text-cadetblue">
                    <span>Read more </span>
                    <span class="text-darkgray-200"> </span>
                  </p>
                </div>
              </div>
            </div>
            <div
              class="absolute top-[0rem] left-[37.56rem] w-[34.38rem] h-[35rem]"
            >
              <div
                class="absolute top-[0rem] left-[0rem] rounded-mini bg-gray-800 shadow-[0px_4px_8px_rgba(0,_0,_0,_0.58)] w-[34.38rem] h-[35rem]"
              />
              <img
                class="absolute top-[0rem] left-[0rem] rounded-lgi w-[34.38rem] h-[24.88rem] object-cover"
                alt=""
                src="/nft5@2x.png"
              />
              <div
                class="absolute top-[26.44rem] left-[2.31rem] w-[30.19rem] h-[7rem]"
              >
                <div class="absolute top-[0rem] left-[0rem] font-medium">
                  The guide to creating & selling digital artsd
                </div>
                <div
                  class="absolute top-[2.5rem] left-[0.5rem] text-[1rem] font-medium whitespace-pre-wrap text-center inline-block w-[29.69rem] text-darkgray-200"
                >
                  <p class="m-0">
                    It is a long established fact that a reader will be
                    distracted by the readable content of page when looking at
                    ...
                  </p>
                  <p class="m-0 text-cadetblue">
                    <span>Read more </span>
                    <span class="text-darkgray-200"> </span>
                  </p>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="relative w-[109.5rem] h-[44.06rem]">
          <div
            class="absolute top-[0rem] left-[3.06rem] w-[103.88rem] h-[4.63rem]"
          >
            <div
              class="absolute top-[0rem] left-[0rem] tracking-[0.06em] font-extrabold"
            >
              Guest Posts
            </div>
            <div
              class="absolute top-[0.88rem] left-[91.81rem] rounded-xl [background:linear-gradient(270deg,_#4287f6,_#d3e5fe)] w-[12.06rem] h-[3.75rem] flex flex-row items-center justify-center py-[0rem] px-[3.13rem] box-border text-center text-[1rem] text-gray-1100 font-caption-work-sans"
            >
              <div class="relative leading-[140%] font-semibold">
                Explore More
              </div>
            </div>
          </div>
          <div
            class="absolute top-[9.06rem] left-[0rem] w-[109.5rem] h-[35rem] text-[1.38rem]"
          >
            <div class="absolute top-[0rem] left-[0rem] w-[34.38rem] h-[35rem]">
              <div
                class="absolute top-[0rem] left-[0rem] rounded-mini bg-gray-800 shadow-[0px_4px_8px_rgba(0,_0,_0,_0.58)] w-[34.38rem] h-[35rem]"
              />
              <img
                class="absolute top-[0rem] left-[0rem] rounded-t-xl rounded-b-none w-[34.38rem] h-[24.88rem] object-cover"
                alt=""
                src="/image-placeholder1@2x.png"
              />
              <div
                class="absolute top-[26.44rem] left-[2.31rem] w-[30.19rem] h-[7rem]"
              >
                <div class="absolute top-[0rem] left-[0rem] font-medium">
                  The guide to creating & selling digital artsd
                </div>
                <div
                  class="absolute top-[2.5rem] left-[0.5rem] text-[1rem] font-medium whitespace-pre-wrap text-center inline-block w-[29.69rem] text-darkgray-200"
                >
                  <p class="m-0">
                    It is a long established fact that a reader will be
                    distracted by the readable content of page when looking at
                    ...
                  </p>
                  <p class="m-0 text-cadetblue">
                    <span>Read more </span>
                    <span class="text-darkgray-200"> </span>
                  </p>
                </div>
              </div>
            </div>
            <div
              class="absolute top-[0rem] left-[37.56rem] w-[34.38rem] h-[35rem]"
            >
              <div
                class="absolute top-[0rem] left-[0rem] rounded-mini bg-gray-800 shadow-[0px_4px_8px_rgba(0,_0,_0,_0.58)] w-[34.38rem] h-[35rem]"
              />
              <img
                class="absolute top-[0rem] left-[0rem] rounded-lgi w-[34.38rem] h-[24.88rem] object-cover"
                alt=""
                src="/nft5@2x.png"
              />
              <div
                class="absolute top-[26.44rem] left-[2.31rem] w-[30.19rem] h-[7rem]"
              >
                <div class="absolute top-[0rem] left-[0rem] font-medium">
                  The guide to creating & selling digital artsd
                </div>
                <div
                  class="absolute top-[2.5rem] left-[0.5rem] text-[1rem] font-medium whitespace-pre-wrap text-center inline-block w-[29.69rem] text-darkgray-200"
                >
                  <p class="m-0">
                    It is a long established fact that a reader will be
                    distracted by the readable content of page when looking at
                    ...
                  </p>
                  <p class="m-0 text-cadetblue">
                    <span>Read more </span>
                    <span class="text-darkgray-200"> </span>
                  </p>
                </div>
              </div>
            </div>
            <div
              class="absolute top-[0rem] left-[75.13rem] w-[34.38rem] h-[35rem]"
            >
              <div
                class="absolute top-[0rem] left-[0rem] rounded-mini bg-gray-800 shadow-[0px_4px_8px_rgba(0,_0,_0,_0.58)] w-[34.38rem] h-[35rem]"
              />
              <img
                class="absolute top-[0rem] left-[0rem] rounded-t-xl rounded-b-none w-[34.38rem] h-[24.88rem] object-cover"
                alt=""
                src="/image-placeholder1@2x.png"
              />
              <div
                class="absolute top-[26.44rem] left-[2.31rem] w-[30.19rem] h-[7rem]"
              >
                <div class="absolute top-[0rem] left-[0rem] font-medium">
                  The guide to creating & selling digital artsd
                </div>
                <div
                  class="absolute top-[2.5rem] left-[0.5rem] text-[1rem] font-medium whitespace-pre-wrap text-center inline-block w-[29.69rem] text-darkgray-200"
                >
                  <p class="m-0">
                    It is a long established fact that a reader will be
                    distracted by the readable content of page when looking at
                    ...
                  </p>
                  <p class="m-0 text-cadetblue">
                    <span>Read more </span>
                    <span class="text-darkgray-200"> </span>
                  </p>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="relative w-[109.5rem] h-[44.06rem]">
          <div
            class="absolute top-[0rem] left-[3.06rem] w-[103.88rem] h-[4.63rem]"
          >
            <div
              class="absolute top-[0rem] left-[0rem] tracking-[0.06em] font-extrabold"
            >
              Announcements
            </div>
            <div
              class="absolute top-[0.88rem] left-[91.81rem] rounded-xl [background:linear-gradient(270deg,_#4287f6,_#d3e5fe)] w-[12.06rem] h-[3.75rem] flex flex-row items-center justify-center py-[0rem] px-[3.13rem] box-border text-center text-[1rem] text-gray-1100 font-caption-work-sans"
            >
              <div class="relative leading-[140%] font-semibold">
                Explore More
              </div>
            </div>
          </div>
          <div
            class="absolute top-[9.06rem] left-[0rem] w-[109.5rem] h-[35rem] text-[1.38rem]"
          >
            <div class="absolute top-[0rem] left-[0rem] w-[34.38rem] h-[35rem]">
              <div
                class="absolute top-[0rem] left-[0rem] rounded-mini bg-gray-800 shadow-[0px_4px_8px_rgba(0,_0,_0,_0.58)] w-[34.38rem] h-[35rem]"
              />
              <img
                class="absolute top-[0rem] left-[0rem] rounded-t-xl rounded-b-none w-[34.38rem] h-[24.88rem] object-cover"
                alt=""
                src="/image-placeholder1@2x.png"
              />
              <div
                class="absolute top-[26.44rem] left-[2.31rem] w-[30.19rem] h-[7rem]"
              >
                <div class="absolute top-[0rem] left-[0rem] font-medium">
                  The guide to creating & selling digital artsd
                </div>
                <div
                  class="absolute top-[2.5rem] left-[0.5rem] text-[1rem] font-medium whitespace-pre-wrap text-center inline-block w-[29.69rem] text-darkgray-200"
                >
                  <p class="m-0">
                    It is a long established fact that a reader will be
                    distracted by the readable content of page when looking at
                    ...
                  </p>
                  <p class="m-0 text-cadetblue">
                    <span>Read more </span>
                    <span class="text-darkgray-200"> </span>
                  </p>
                </div>
              </div>
            </div>
            <div
              class="absolute top-[0rem] left-[37.56rem] w-[34.38rem] h-[35rem]"
            >
              <div
                class="absolute top-[0rem] left-[0rem] rounded-mini bg-gray-800 shadow-[0px_4px_8px_rgba(0,_0,_0,_0.58)] w-[34.38rem] h-[35rem]"
              />
              <img
                class="absolute top-[0rem] left-[0rem] rounded-t-xl rounded-b-none w-[34.38rem] h-[24.88rem] object-cover"
                alt=""
                src="/image-placeholder1@2x.png"
              />
              <div
                class="absolute top-[26.44rem] left-[2.31rem] w-[30.19rem] h-[7rem]"
              >
                <div class="absolute top-[0rem] left-[0rem] font-medium">
                  The guide to creating & selling digital artsd
                </div>
                <div
                  class="absolute top-[2.5rem] left-[0.5rem] text-[1rem] font-medium whitespace-pre-wrap text-center inline-block w-[29.69rem] text-darkgray-200"
                >
                  <p class="m-0">
                    It is a long established fact that a reader will be
                    distracted by the readable content of page when looking at
                    ...
                  </p>
                  <p class="m-0 text-cadetblue">
                    <span>Read more </span>
                    <span class="text-darkgray-200"> </span>
                  </p>
                </div>
              </div>
            </div>
            <div
              class="absolute top-[0rem] left-[75.13rem] w-[34.38rem] h-[35rem]"
            >
              <div
                class="absolute top-[0rem] left-[0rem] rounded-mini bg-gray-800 shadow-[0px_4px_8px_rgba(0,_0,_0,_0.58)] w-[34.38rem] h-[35rem]"
              />
              <img
                class="absolute top-[0rem] left-[0rem] rounded-lgi w-[34.38rem] h-[24.88rem] object-cover"
                alt=""
                src="/nft5@2x.png"
              />
              <div
                class="absolute top-[26.44rem] left-[2.31rem] w-[30.19rem] h-[7rem]"
              >
                <div class="absolute top-[0rem] left-[0rem] font-medium">
                  The guide to creating & selling digital artsd
                </div>
                <div
                  class="absolute top-[2.5rem] left-[0.5rem] text-[1rem] font-medium whitespace-pre-wrap text-center inline-block w-[29.69rem] text-darkgray-200"
                >
                  <p class="m-0">
                    It is a long established fact that a reader will be
                    distracted by the readable content of page when looking at
                    ...
                  </p>
                  <p class="m-0 text-cadetblue">
                    <span>Read more </span>
                    <span class="text-darkgray-200"> </span>
                  </p>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="relative w-[109.5rem] h-[44.06rem]">
          <div
            class="absolute top-[0rem] left-[3.06rem] w-[103.88rem] h-[4.63rem]"
          >
            <div
              class="absolute top-[0rem] left-[0rem] tracking-[0.06em] font-extrabold"
            >
              Safety & Security
            </div>
            <div
              class="absolute top-[0.88rem] left-[91.81rem] rounded-xl [background:linear-gradient(270deg,_#4287f6,_#d3e5fe)] w-[12.06rem] h-[3.75rem] flex flex-row items-center justify-center py-[0rem] px-[3.13rem] box-border text-center text-[1rem] text-gray-1100 font-caption-work-sans"
            >
              <div class="relative leading-[140%] font-semibold">
                Explore More
              </div>
            </div>
          </div>
          <div
            class="absolute top-[9.06rem] left-[0rem] w-[109.5rem] h-[35rem] text-[1.38rem]"
          >
            <div class="absolute top-[0rem] left-[0rem] w-[34.38rem] h-[35rem]">
              <div
                class="absolute top-[0rem] left-[0rem] rounded-mini bg-gray-800 shadow-[0px_4px_8px_rgba(0,_0,_0,_0.58)] w-[34.38rem] h-[35rem]"
              />
              <img
                class="absolute top-[0rem] left-[0rem] rounded-lgi w-[34.38rem] h-[24.88rem] object-cover"
                alt=""
                src="/nft5@2x.png"
              />
              <div
                class="absolute top-[26.44rem] left-[2.31rem] w-[30.19rem] h-[7rem]"
              >
                <div class="absolute top-[0rem] left-[0rem] font-medium">
                  The guide to creating & selling digital artsd
                </div>
                <div
                  class="absolute top-[2.5rem] left-[0.5rem] text-[1rem] font-medium whitespace-pre-wrap text-center inline-block w-[29.69rem] text-darkgray-200"
                >
                  <p class="m-0">
                    It is a long established fact that a reader will be
                    distracted by the readable content of page when looking at
                    ...
                  </p>
                  <p class="m-0 text-cadetblue">
                    <span>Read more </span>
                    <span class="text-darkgray-200"> </span>
                  </p>
                </div>
              </div>
            </div>
            <div
              class="absolute top-[0rem] left-[37.56rem] w-[34.38rem] h-[35rem]"
            >
              <div
                class="absolute top-[0rem] left-[0rem] rounded-mini bg-gray-800 shadow-[0px_4px_8px_rgba(0,_0,_0,_0.58)] w-[34.38rem] h-[35rem]"
              />
              <img
                class="absolute top-[0rem] left-[0rem] rounded-t-xl rounded-b-none w-[34.38rem] h-[24.88rem] object-cover"
                alt=""
                src="/image-placeholder1@2x.png"
              />
              <div
                class="absolute top-[26.44rem] left-[2.31rem] w-[30.19rem] h-[7rem]"
              >
                <div class="absolute top-[0rem] left-[0rem] font-medium">
                  The guide to creating & selling digital artsd
                </div>
                <div
                  class="absolute top-[2.5rem] left-[0.5rem] text-[1rem] font-medium whitespace-pre-wrap text-center inline-block w-[29.69rem] text-darkgray-200"
                >
                  <p class="m-0">
                    It is a long established fact that a reader will be
                    distracted by the readable content of page when looking at
                    ...
                  </p>
                  <p class="m-0 text-cadetblue">
                    <span>Read more </span>
                    <span class="text-darkgray-200"> </span>
                  </p>
                </div>
              </div>
            </div>
            <div
              class="absolute top-[0rem] left-[75.13rem] w-[34.38rem] h-[35rem]"
            >
              <div
                class="absolute top-[0rem] left-[0rem] rounded-mini bg-gray-800 shadow-[0px_4px_8px_rgba(0,_0,_0,_0.58)] w-[34.38rem] h-[35rem]"
              />
              <img
                class="absolute top-[0rem] left-[0rem] rounded-t-xl rounded-b-none w-[34.38rem] h-[24.88rem] object-cover"
                alt=""
                src="/image-placeholder1@2x.png"
              />
              <div
                class="absolute top-[26.44rem] left-[2.31rem] w-[30.19rem] h-[7rem]"
              >
                <div class="absolute top-[0rem] left-[0rem] font-medium">
                  The guide to creating & selling digital artsd
                </div>
                <div
                  class="absolute top-[2.5rem] left-[0.5rem] text-[1rem] font-medium whitespace-pre-wrap text-center inline-block w-[29.69rem] text-darkgray-200"
                >
                  <p class="m-0">
                    It is a long established fact that a reader will be
                    distracted by the readable content of page when looking at
                    ...
                  </p>
                  <p class="m-0 text-cadetblue">
                    <span>Read more </span>
                    <span class="text-darkgray-200"> </span>
                  </p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div
      class="relative bg-gray-1100 w-[120rem] h-[182.88rem] overflow-hidden shrink-0 hidden text-[1rem]"
    >
      <img
        class="absolute top-[0.25rem] left-[0rem] w-[119.88rem] h-[129.69rem] object-cover"
        alt=""
        src="/image-9@2x.png"
      />
      <div
        class="absolute top-[161.57rem] left-[-5.95rem] bg-gray-1300 w-[138.54rem] h-[55.78rem] [transform:_rotate(-14.72deg)] [transform-origin:0_0]"
      />
      <div
        class="absolute top-[239.4rem] left-[126.18rem] bg-gray-1200 w-[170.44rem] h-[50.38rem] [transform:_rotate(-159.24deg)] [transform-origin:0_0]"
      />
      <div class="absolute top-[0rem] left-[0rem] w-[120rem] h-[182.88rem]" />
      <div
        class="absolute top-[0.25rem] left-[77.81rem] rounded-504xl-5 [background:radial-gradient(50%_50%_at_50%_50%,_rgba(202,_157,_255,_0.4),_rgba(119,_149,_255,_0))] [backdrop-filter:blur(4px)] w-[66.25rem] h-[65.44rem] opacity-[0.3]"
      />
      <footer
        imageDimensions="/storefront2.svg"
        imageCode="/discordlogo2.svg"
        imageCodeDimensions="/youtubelogo2.svg"
        imageCodeDimensions2="/twitterlogo1.svg"
        imageCodeDimensionsText="/instagramlogo1.svg"
        imageCodeDimensionsText2="/envelopesimple1.svg"
        propTop="151.92rem"
        propLeft="-0.12rem"
        :onDiscordLogoIconClick="onDiscordLogoIcon3Click"
        :onYoutubeLogoIconClick="onYoutubeLogoIcon3Click"
        :onTwitterLogoIconClick="onTwitterLogoIcon3Click"
        :onInstagramLogoIconClick="onInstagramLogoIcon3Click"
      />
      <Navigation1
        propHeight="11.44rem"
        propBackgroundColor="rgba(46, 46, 46, 0.19)"
        :onNavLogoClick="onNavLogo3Click"
      />
      <div
        class="absolute top-[140rem] left-[34.88rem] box-border w-[77.25rem] flex flex-row items-center justify-between pt-[1.5rem] px-[0rem] pb-[0rem] text-gray-200 font-bold-text-sm border-t-[1px] border-solid border-neutral-50"
      >
        <b class="relative leading-[150%]">Showing 1-30 of 393 results</b>
        <div
          class="flex flex-row items-center justify-start gap-[0.75rem] text-[0.88rem] text-neutral-0"
        >
          <div
            class="rounded-81xl bg-steelblue-300 box-border w-[2.25rem] h-[2.25rem] flex flex-row items-center justify-center border-[1px] border-solid border-neutral-50"
          >
            <img
              class="relative w-[1.13rem] h-[1.13rem]"
              alt=""
              src="/vuesaxlineararrowleft1.svg"
            />
          </div>
          <div class="flex flex-row items-center justify-start gap-[0.75rem]">
            <div
              class="rounded-81xl bg-secondary-50 w-[2.25rem] h-[2.25rem] flex flex-row items-center justify-center text-secondary-500"
            >
              <div class="relative leading-[150%]">1</div>
            </div>
            <div
              class="rounded-81xl bg-steelblue-300 w-[2.25rem] h-[2.25rem] flex flex-row items-center justify-center"
            >
              <div class="relative leading-[150%]">2</div>
            </div>
            <div
              class="rounded-81xl bg-steelblue-300 w-[2.25rem] h-[2.25rem] flex flex-row items-center justify-center"
            >
              <div class="relative leading-[150%]">3</div>
            </div>
            <div
              class="rounded-81xl bg-steelblue-300 w-[2.25rem] h-[2.25rem] flex flex-row items-center justify-center"
            >
              <div class="relative leading-[150%]">4</div>
            </div>
            <div
              class="rounded-md bg-steelblue-300 w-[1.25rem] h-[2.25rem] flex flex-row items-center justify-center"
            >
              <div class="relative leading-[150%]">...</div>
            </div>
            <div
              class="rounded-81xl bg-steelblue-300 w-[2.25rem] h-[2.25rem] flex flex-row items-center justify-center"
            >
              <div class="relative leading-[150%]">55</div>
            </div>
          </div>
          <div
            class="rounded-81xl bg-steelblue-300 box-border w-[2.25rem] h-[2.25rem] flex flex-row items-center justify-center border-[1px] border-solid border-neutral-50"
          >
            <img
              class="relative w-[1.13rem] h-[1.13rem]"
              alt=""
              src="/vuesaxlineararrowright1.svg"
            />
          </div>
        </div>
        <div
          class="relative [text-decoration:underline] leading-[150%] text-neutral-30 hidden"
        >
          Clear
        </div>
        <div class="relative leading-[150%] text-neutral-60 hidden">
          Shop All Weed
        </div>
      </div>
      <div
        class="absolute top-[28.06rem] left-[4.69rem] flex flex-col items-start justify-start gap-[1.25rem] text-[1.25rem] text-neutral-50"
      >
        <div class="relative w-[26.25rem] h-[5rem]">
          <div
            class="absolute top-[0rem] left-[0rem] rounded-mini [background:linear-gradient(90.8deg,_rgba(29,_76,_105,_0.96),_rgba(28,_38,_17,_0))] w-[26.25rem] h-[5rem]"
          />
          <div class="absolute top-[1.25rem] left-[7.56rem] font-semibold">
            Artist of the Week
          </div>
        </div>
        <div class="relative w-[26.25rem] h-[5rem]">
          <div
            class="absolute top-[0rem] left-[0rem] rounded-mini [background:linear-gradient(90.8deg,_rgba(29,_76,_105,_0.96),_rgba(28,_38,_17,_0))] w-[26.25rem] h-[5rem]"
          />
          <div class="absolute top-[1.13rem] left-[8.81rem] font-semibold">
            Popular Artist
          </div>
        </div>
        <div class="relative w-[26.25rem] h-[5rem]">
          <div
            class="absolute top-[0rem] left-[0rem] rounded-mini [background:linear-gradient(90.8deg,_rgba(29,_76,_105,_0.96),_rgba(28,_38,_17,_0))] w-[26.25rem] h-[5rem]"
          />
          <div class="absolute top-[1.13rem] left-[8.44rem] font-semibold">
            Trending Artist
          </div>
        </div>
        <div class="relative w-[26.25rem] h-[5rem]">
          <div
            class="absolute top-[0rem] left-[0rem] rounded-mini [background:linear-gradient(90.8deg,_rgba(29,_76,_105,_0.96),_rgba(28,_38,_17,_0))] w-[26.25rem] h-[5rem]"
          />
          <div class="absolute top-[1.13rem] left-[8.44rem] font-semibold">
            Trending Artist
          </div>
        </div>
        <div class="relative w-[26.25rem] h-[5rem]">
          <div
            class="absolute top-[0rem] left-[0rem] rounded-mini [background:linear-gradient(90.8deg,_rgba(29,_76,_105,_0.96),_rgba(28,_38,_17,_0))] w-[26.25rem] h-[5rem]"
          />
          <div class="absolute top-[1.56rem] left-[10.5rem] font-semibold">
            All Artist
          </div>
        </div>
      </div>
      <div
        class="absolute top-[29.31rem] left-[34.88rem] flex flex-col items-start justify-start gap-[4.56rem] text-center text-[0.69rem]"
      >
        <div class="relative w-[78.44rem] h-[17.56rem]">
          <div
            class="absolute top-[0rem] left-[0rem] rounded-xl [background:linear-gradient(180deg,_rgba(11,_27,_38,_0.56),_rgba(11,_27,_38,_0))] [backdrop-filter:blur(20px)] box-border w-[78.44rem] h-[17.56rem] border-[1px] border-solid border-gray-600"
          />
          <div
            class="absolute top-[13.38rem] left-[3.06rem] rounded-xl [background:linear-gradient(180deg,_rgba(105,_125,_156,_0.51),_rgba(105,_125,_156,_0))] w-[6.38rem] h-[1.75rem] flex flex-row items-center justify-center py-[0rem] px-[3.13rem] box-border text-[1rem] font-caption-work-sans"
          >
            <div class="relative leading-[140%] font-semibold">Follow</div>
          </div>
          <img
            class="absolute top-[2.73rem] left-[1.56rem] rounded-[50%] w-[9.38rem] h-[9.38rem] object-cover"
            alt=""
            src="/ellipse-38@2x.png"
          />
          <div
            class="absolute top-[9.81rem] left-[19.19rem] font-semibold text-gainsboro-200 inline-block w-[3.81rem] h-[0.81rem]"
          >
            11 Artworks
          </div>
          <div
            class="absolute top-[9.81rem] left-[23.81rem] font-semibold text-gainsboro-200 inline-block w-[3.81rem] h-[0.99rem]"
          >
            5 followers
          </div>
          <div
            class="absolute top-[3.25rem] left-[18.44rem] w-[15.19rem] h-[4.75rem] text-left text-[2rem]"
          >
            <div
              class="absolute top-[0rem] left-[0rem] leading-[150%] font-medium inline-block w-[15.19rem] h-[2.44rem]"
            >
              Ashis Mondal
            </div>
            <div
              class="absolute top-[3.67rem] left-[0.75rem] text-[1rem] leading-[150%] font-medium inline-block w-[6.5rem] h-[1.09rem]"
            >
              700156, India
            </div>
          </div>
          <img
            class="absolute top-[1.63rem] left-[57.81rem] rounded-3xs w-[16.13rem] h-[11.56rem] object-cover"
            alt=""
            src="/image-6@2x.png"
          />
          <img
            class="absolute top-[13.75rem] left-[57.81rem] rounded-3xs w-[4.56rem] h-[2.69rem] object-cover"
            alt=""
            src="/image-7@2x.png"
          />
          <img
            class="absolute top-[13.75rem] left-[63.63rem] rounded-3xs w-[4.56rem] h-[2.69rem] object-cover"
            alt=""
            src="/image-8@2x.png"
          />
          <div
            class="absolute top-[13.75rem] left-[69.44rem] rounded-3xs bg-gainsboro-300 w-[4.56rem] h-[2.69rem]"
          />
        </div>
        <div class="relative w-[78.44rem] h-[17.56rem]">
          <div
            class="absolute top-[0rem] left-[0rem] rounded-xl [background:linear-gradient(180deg,_rgba(11,_27,_38,_0.56),_rgba(11,_27,_38,_0))] [backdrop-filter:blur(20px)] box-border w-[78.44rem] h-[17.56rem] border-[1px] border-solid border-gray-600"
          />
          <div
            class="absolute top-[13.38rem] left-[3.06rem] rounded-xl [background:linear-gradient(180deg,_rgba(105,_125,_156,_0.51),_rgba(105,_125,_156,_0))] w-[6.38rem] h-[1.75rem] flex flex-row items-center justify-center py-[0rem] px-[3.13rem] box-border text-[1rem] font-caption-work-sans"
          >
            <div class="relative leading-[140%] font-semibold">Follow</div>
          </div>
          <img
            class="absolute top-[2.73rem] left-[1.56rem] rounded-[50%] w-[9.38rem] h-[9.38rem] object-cover"
            alt=""
            src="/ellipse-38@2x.png"
          />
          <div
            class="absolute top-[9.81rem] left-[19.19rem] font-semibold text-gainsboro-200 inline-block w-[3.81rem] h-[0.81rem]"
          >
            11 Artworks
          </div>
          <div
            class="absolute top-[9.81rem] left-[23.81rem] font-semibold text-gainsboro-200 inline-block w-[3.81rem] h-[0.99rem]"
          >
            5 followers
          </div>
          <div
            class="absolute top-[3.25rem] left-[18.44rem] w-[15.19rem] h-[4.75rem] text-left text-[2rem]"
          >
            <div
              class="absolute top-[0rem] left-[0rem] leading-[150%] font-medium inline-block w-[15.19rem] h-[2.44rem]"
            >
              Ashis Mondal
            </div>
            <div
              class="absolute top-[3.67rem] left-[0.75rem] text-[1rem] leading-[150%] font-medium inline-block w-[6.5rem] h-[1.09rem]"
            >
              700156, India
            </div>
          </div>
          <img
            class="absolute top-[1.63rem] left-[57.81rem] rounded-3xs w-[16.13rem] h-[11.56rem] object-cover"
            alt=""
            src="/image-61@2x.png"
          />
          <img
            class="absolute top-[13.75rem] left-[57.81rem] rounded-3xs w-[4.56rem] h-[2.69rem] object-cover"
            alt=""
            src="/image-7@2x.png"
          />
          <img
            class="absolute top-[13.75rem] left-[63.63rem] rounded-3xs w-[4.56rem] h-[2.69rem] object-cover"
            alt=""
            src="/image-8@2x.png"
          />
          <div
            class="absolute top-[13.75rem] left-[69.44rem] rounded-3xs bg-gainsboro-300 w-[4.56rem] h-[2.69rem]"
          />
        </div>
        <div class="relative w-[78.44rem] h-[17.56rem]">
          <div
            class="absolute top-[0rem] left-[0rem] rounded-xl [background:linear-gradient(180deg,_rgba(11,_27,_38,_0.56),_rgba(11,_27,_38,_0))] [backdrop-filter:blur(20px)] box-border w-[78.44rem] h-[17.56rem] border-[1px] border-solid border-gray-600"
          />
          <div
            class="absolute top-[13.38rem] left-[3.06rem] rounded-xl [background:linear-gradient(180deg,_rgba(105,_125,_156,_0.51),_rgba(105,_125,_156,_0))] w-[6.38rem] h-[1.75rem] flex flex-row items-center justify-center py-[0rem] px-[3.13rem] box-border text-[1rem] font-caption-work-sans"
          >
            <div class="relative leading-[140%] font-semibold">Follow</div>
          </div>
          <img
            class="absolute top-[2.73rem] left-[1.56rem] rounded-[50%] w-[9.38rem] h-[9.38rem] object-cover"
            alt=""
            src="/ellipse-38@2x.png"
          />
          <div
            class="absolute top-[9.81rem] left-[19.19rem] font-semibold text-gainsboro-200 inline-block w-[3.81rem] h-[0.81rem]"
          >
            11 Artworks
          </div>
          <div
            class="absolute top-[9.81rem] left-[23.81rem] font-semibold text-gainsboro-200 inline-block w-[3.81rem] h-[0.99rem]"
          >
            5 followers
          </div>
          <div
            class="absolute top-[3.25rem] left-[18.44rem] w-[15.19rem] h-[4.75rem] text-left text-[2rem]"
          >
            <div
              class="absolute top-[0rem] left-[0rem] leading-[150%] font-medium inline-block w-[15.19rem] h-[2.44rem]"
            >
              Ashis Mondal
            </div>
            <div
              class="absolute top-[3.67rem] left-[0.75rem] text-[1rem] leading-[150%] font-medium inline-block w-[6.5rem] h-[1.09rem]"
            >
              700156, India
            </div>
          </div>
          <img
            class="absolute top-[1.63rem] left-[57.81rem] rounded-3xs w-[16.13rem] h-[11.56rem] object-cover"
            alt=""
            src="/image-6@2x.png"
          />
          <img
            class="absolute top-[13.75rem] left-[57.81rem] rounded-3xs w-[4.56rem] h-[2.69rem] object-cover"
            alt=""
            src="/image-7@2x.png"
          />
          <img
            class="absolute top-[13.75rem] left-[63.63rem] rounded-3xs w-[4.56rem] h-[2.69rem] object-cover"
            alt=""
            src="/image-8@2x.png"
          />
          <div
            class="absolute top-[13.75rem] left-[69.44rem] rounded-3xs bg-gainsboro-300 w-[4.56rem] h-[2.69rem]"
          />
        </div>
        <div class="relative w-[78.44rem] h-[17.56rem]">
          <div
            class="absolute top-[0rem] left-[0rem] rounded-xl [background:linear-gradient(180deg,_rgba(11,_27,_38,_0.56),_rgba(11,_27,_38,_0))] [backdrop-filter:blur(20px)] box-border w-[78.44rem] h-[17.56rem] border-[1px] border-solid border-gray-600"
          />
          <div
            class="absolute top-[13.38rem] left-[3.06rem] rounded-xl [background:linear-gradient(180deg,_rgba(105,_125,_156,_0.51),_rgba(105,_125,_156,_0))] w-[6.38rem] h-[1.75rem] flex flex-row items-center justify-center py-[0rem] px-[3.13rem] box-border text-[1rem] font-caption-work-sans"
          >
            <div class="relative leading-[140%] font-semibold">Follow</div>
          </div>
          <img
            class="absolute top-[2.73rem] left-[1.56rem] rounded-[50%] w-[9.38rem] h-[9.38rem] object-cover"
            alt=""
            src="/ellipse-38@2x.png"
          />
          <div
            class="absolute top-[9.81rem] left-[19.19rem] font-semibold text-gainsboro-200 inline-block w-[3.81rem] h-[0.81rem]"
          >
            11 Artworks
          </div>
          <div
            class="absolute top-[9.81rem] left-[23.81rem] font-semibold text-gainsboro-200 inline-block w-[3.81rem] h-[0.99rem]"
          >
            5 followers
          </div>
          <div
            class="absolute top-[3.25rem] left-[18.44rem] w-[15.19rem] h-[4.75rem] text-left text-[2rem]"
          >
            <div
              class="absolute top-[0rem] left-[0rem] leading-[150%] font-medium inline-block w-[15.19rem] h-[2.44rem]"
            >
              Ashis Mondal
            </div>
            <div
              class="absolute top-[3.67rem] left-[0.75rem] text-[1rem] leading-[150%] font-medium inline-block w-[6.5rem] h-[1.09rem]"
            >
              700156, India
            </div>
          </div>
          <img
            class="absolute top-[1.63rem] left-[57.81rem] rounded-3xs w-[16.13rem] h-[11.56rem] object-cover"
            alt=""
            src="/image-61@2x.png"
          />
          <img
            class="absolute top-[13.75rem] left-[57.81rem] rounded-3xs w-[4.56rem] h-[2.69rem] object-cover"
            alt=""
            src="/image-7@2x.png"
          />
          <img
            class="absolute top-[13.75rem] left-[63.63rem] rounded-3xs w-[4.56rem] h-[2.69rem] object-cover"
            alt=""
            src="/image-8@2x.png"
          />
          <div
            class="absolute top-[13.75rem] left-[69.44rem] rounded-3xs bg-gainsboro-300 w-[4.56rem] h-[2.69rem]"
          />
        </div>
        <div class="relative w-[78.44rem] h-[17.56rem]">
          <div
            class="absolute top-[0rem] left-[0rem] rounded-xl [background:linear-gradient(180deg,_rgba(11,_27,_38,_0.56),_rgba(11,_27,_38,_0))] [backdrop-filter:blur(20px)] box-border w-[78.44rem] h-[17.56rem] border-[1px] border-solid border-gray-600"
          />
          <div
            class="absolute top-[13.38rem] left-[3.06rem] rounded-xl [background:linear-gradient(180deg,_rgba(105,_125,_156,_0.51),_rgba(105,_125,_156,_0))] w-[6.38rem] h-[1.75rem] flex flex-row items-center justify-center py-[0rem] px-[3.13rem] box-border text-[1rem] font-caption-work-sans"
          >
            <div class="relative leading-[140%] font-semibold">Follow</div>
          </div>
          <img
            class="absolute top-[2.73rem] left-[1.56rem] rounded-[50%] w-[9.38rem] h-[9.38rem] object-cover"
            alt=""
            src="/ellipse-38@2x.png"
          />
          <div
            class="absolute top-[9.81rem] left-[19.19rem] font-semibold text-gainsboro-200 inline-block w-[3.81rem] h-[0.81rem]"
          >
            11 Artworks
          </div>
          <div
            class="absolute top-[9.81rem] left-[23.81rem] font-semibold text-gainsboro-200 inline-block w-[3.81rem] h-[0.99rem]"
          >
            5 followers
          </div>
          <div
            class="absolute top-[3.25rem] left-[18.44rem] w-[15.19rem] h-[4.75rem] text-left text-[2rem]"
          >
            <div
              class="absolute top-[0rem] left-[0rem] leading-[150%] font-medium inline-block w-[15.19rem] h-[2.44rem]"
            >
              Ashis Mondal
            </div>
            <div
              class="absolute top-[3.67rem] left-[0.75rem] text-[1rem] leading-[150%] font-medium inline-block w-[6.5rem] h-[1.09rem]"
            >
              700156, India
            </div>
          </div>
          <img
            class="absolute top-[1.63rem] left-[57.81rem] rounded-3xs w-[16.13rem] h-[11.56rem] object-cover"
            alt=""
            src="/image-6@2x.png"
          />
          <img
            class="absolute top-[13.75rem] left-[57.81rem] rounded-3xs w-[4.56rem] h-[2.69rem] object-cover"
            alt=""
            src="/image-7@2x.png"
          />
          <img
            class="absolute top-[13.75rem] left-[63.63rem] rounded-3xs w-[4.56rem] h-[2.69rem] object-cover"
            alt=""
            src="/image-8@2x.png"
          />
          <div
            class="absolute top-[13.75rem] left-[69.44rem] rounded-3xs bg-gainsboro-300 w-[4.56rem] h-[2.69rem]"
          />
        </div>
      </div>
      <div
        class="absolute top-[17.5rem] left-[9.38rem] text-[3rem] leading-[150%] font-semibold"
      >
        Artist page
      </div>
    </div>
    <div
      class="relative bg-gray-1100 w-[120rem] h-[140.38rem] overflow-hidden shrink-0 hidden text-[0.94rem]"
    >
      <div
        class="absolute top-[121.64rem] left-[-5.2rem] bg-gray-1300 w-[138.54rem] h-[55.78rem] [transform:_rotate(-14.72deg)] [transform-origin:0_0]"
      />
      <div
        class="absolute top-[199.46rem] left-[126.93rem] bg-gray-1200 w-[170.44rem] h-[50.38rem] [transform:_rotate(-159.24deg)] [transform-origin:0_0]"
      />
      <div
        class="absolute top-[0.25rem] left-[77.81rem] rounded-504xl-5 [background:radial-gradient(50%_50%_at_50%_50%,_rgba(202,_157,_255,_0.4),_rgba(119,_149,_255,_0))] [backdrop-filter:blur(4px)] w-[66.25rem] h-[65.44rem] opacity-[0.3]"
      />
      <footer
        imageDimensions="/storefront2.svg"
        imageCode="/discordlogo2.svg"
        imageCodeDimensions="/youtubelogo2.svg"
        imageCodeDimensions2="/twitterlogo1.svg"
        imageCodeDimensionsText="/instagramlogo1.svg"
        imageCodeDimensionsText2="/envelopesimple1.svg"
        propTop="111.98rem"
        propLeft="0.63rem"
        :onDiscordLogoIconClick="onDiscordLogoIcon4Click"
        :onYoutubeLogoIconClick="onYoutubeLogoIcon4Click"
        :onTwitterLogoIconClick="onTwitterLogoIcon4Click"
        :onInstagramLogoIconClick="onInstagramLogoIcon4Click"
      />
      <Navigation1
        propHeight="10.19rem"
        propBackgroundColor="rgba(0, 0, 0, 0)"
        :onNavLogoClick="onNavLogo4Click"
      />
      <div
        class="absolute top-[99.25rem] left-[16.38rem] box-border w-[87.56rem] flex flex-row items-center justify-between pt-[1.5rem] px-[0rem] pb-[0rem] text-[1rem] text-gray-200 font-bold-text-sm border-t-[1px] border-solid border-neutral-50"
      >
        <b class="relative leading-[150%]">Showing 1-30 of 393 results</b>
        <div
          class="flex flex-row items-center justify-start gap-[0.75rem] text-[0.88rem] text-neutral-0"
        >
          <div
            class="rounded-81xl bg-steelblue-300 box-border w-[2.25rem] h-[2.25rem] flex flex-row items-center justify-center border-[1px] border-solid border-neutral-50"
          >
            <img
              class="relative w-[1.13rem] h-[1.13rem]"
              alt=""
              src="/vuesaxlineararrowleft1.svg"
            />
          </div>
          <div class="flex flex-row items-center justify-start gap-[0.75rem]">
            <div
              class="rounded-81xl bg-secondary-50 w-[2.25rem] h-[2.25rem] flex flex-row items-center justify-center text-secondary-500"
            >
              <div class="relative leading-[150%]">1</div>
            </div>
            <div
              class="rounded-81xl bg-steelblue-300 w-[2.25rem] h-[2.25rem] flex flex-row items-center justify-center"
            >
              <div class="relative leading-[150%]">2</div>
            </div>
            <div
              class="rounded-81xl bg-steelblue-300 w-[2.25rem] h-[2.25rem] flex flex-row items-center justify-center"
            >
              <div class="relative leading-[150%]">3</div>
            </div>
            <div
              class="rounded-81xl bg-steelblue-300 w-[2.25rem] h-[2.25rem] flex flex-row items-center justify-center"
            >
              <div class="relative leading-[150%]">4</div>
            </div>
            <div
              class="rounded-md bg-steelblue-300 w-[1.25rem] h-[2.25rem] flex flex-row items-center justify-center"
            >
              <div class="relative leading-[150%]">...</div>
            </div>
            <div
              class="rounded-81xl bg-steelblue-300 w-[2.25rem] h-[2.25rem] flex flex-row items-center justify-center"
            >
              <div class="relative leading-[150%]">55</div>
            </div>
          </div>
          <div
            class="rounded-81xl bg-steelblue-300 box-border w-[2.25rem] h-[2.25rem] flex flex-row items-center justify-center border-[1px] border-solid border-neutral-50"
          >
            <img
              class="relative w-[1.13rem] h-[1.13rem]"
              alt=""
              src="/vuesaxlineararrowright1.svg"
            />
          </div>
        </div>
        <div
          class="relative [text-decoration:underline] leading-[150%] text-neutral-30 hidden"
        >
          Clear
        </div>
        <div class="relative leading-[150%] text-neutral-60 hidden">
          Shop All Weed
        </div>
      </div>
      <div
        class="absolute top-[15.56rem] left-[10rem] text-[3rem] leading-[150%] font-semibold"
      >
        Artist Profile
      </div>
      <div
        class="absolute top-[26.19rem] left-[15.69rem] w-[88.56rem] h-[26.94rem] text-center text-[1rem]"
      >
        <div
          class="absolute top-[0rem] left-[5.75rem] rounded-xl [background:linear-gradient(96.5deg,_rgba(95,_141,_172,_0.22),_rgba(65,_81,_72,_0)_45.9%)] shadow-[0px_4px_20px_rgba(137,_137,_137,_0.25)] box-border w-[82.81rem] h-[26.94rem] border-[3px] border-solid border-steelblue-100"
        />
        <div
          class="absolute top-[3.5rem] left-[73.75rem] rounded-xl bg-dodgerblue-200 h-[3.75rem] flex flex-row items-center justify-center py-[0rem] px-[3.13rem] box-border font-caption-work-sans"
        >
          <div class="relative leading-[140%] font-semibold">Follow</div>
        </div>
        <div
          class="absolute top-[8.56rem] left-[73.75rem] rounded-xl bg-dodgerblue-200 w-[9.56rem] h-[3.75rem] flex flex-row items-center justify-center py-[0rem] px-[3.13rem] box-border font-caption-work-sans"
        >
          <div class="relative leading-[140%] font-semibold">Message</div>
        </div>
        <img
          class="absolute top-[2.94rem] left-[0rem] rounded-[50%] w-[13.75rem] h-[13.75rem] object-cover"
          alt=""
          src="/ellipse-381@2x.png"
        />
        <div
          class="absolute top-[11.56rem] left-[16.88rem] rounded-[5px] bg-gray-1700 [backdrop-filter:blur(4px)] w-[15.19rem] h-[1.63rem]"
        />
        <div
          class="absolute top-[11.94rem] left-[18.44rem] text-[0.69rem] font-semibold text-black inline-block w-[3.81rem] h-[0.88rem]"
        >
          11 Artworks
        </div>
        <div
          class="absolute top-[11.94rem] left-[26.19rem] text-[0.69rem] font-semibold text-black"
        >
          5 followers
        </div>
        <div
          class="absolute top-[3.5rem] left-[16.88rem] w-[45.94rem] h-[20.19rem] text-left text-[2.25rem]"
        >
          <div
            class="absolute top-[0rem] left-[0rem] leading-[150%] font-medium"
          >
            Ashis Mondal
          </div>
          <div
            class="absolute top-[5.06rem] left-[0.75rem] text-[1rem] leading-[150%] font-medium"
          >
            700156, India
          </div>
          <div
            class="absolute top-[11.38rem] left-[0rem] leading-[140%] font-semibold font-caption-work-sans inline-block w-[45.94rem] text-[1.5rem]"
          >
            <p class="m-0">About Artist</p>
            <p class="m-0 text-[1rem]">
              Myself Ashis Mondal. I born in Kolkata in the year of 1978. I have
              passed B.F.A in the year of 2001 from Indian College of Art &
              Draftsmanship (Rabindra Bharati University). Upto 2016 I have
              organized various Group Exhibition in India & Abroad. Also there
              are two Solo Exhibition between Fifteen years. In the past years I
              have done various type of work. But mostly I prefer to do
              conceptual type of work.
            </p>
          </div>
        </div>
      </div>
      <div
        class="absolute top-[37.66rem] left-[40.09rem] box-border w-[0.06rem] h-[1.75rem] border-r-[1px] border-solid border-black"
      />
      <div
        class="absolute top-[65.69rem] left-[21.94rem] w-[77.27rem] h-[30.75rem] text-[0.75rem] text-steelblue-200"
      >
        <div class="absolute top-[0rem] left-[0rem] w-[24.05rem] h-[30.75rem]">
          <div
            class="absolute top-[0rem] left-[0rem] rounded-lg bg-gray-1100 box-border w-[24.05rem] h-[30.75rem] border-[2px] border-solid border-steelblue-400"
          />
          <img
            class="absolute top-[1.25rem] left-[2.31rem] rounded-lgi w-[20.06rem] h-[14.69rem] object-cover"
            alt=""
            src="/image-24@2x.png"
          />
          <div
            class="absolute top-[16.75rem] left-[1.19rem] flex flex-col items-center justify-start gap-[0.56rem]"
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
              <div
                class="absolute top-[0rem] left-[0rem] rounded-4xs [background:linear-gradient(269.73deg,_rgba(193,_221,_253,_0.84)_12.27%,_#5495f7)] w-[14.38rem] h-[2.5rem]"
              />
              <div
                class="absolute top-[0.58rem] left-[2.17rem] font-semibold inline-block w-[9.94rem] h-[1.31rem]"
              >
                Buy Now
              </div>
            </div>
          </div>
        </div>
        <div
          class="absolute top-[0rem] left-[26.61rem] w-[24.05rem] h-[30.75rem]"
        >
          <div
            class="absolute top-[0rem] left-[0rem] rounded-lg bg-gray-1100 box-border w-[24.05rem] h-[30.75rem] border-[2px] border-solid border-steelblue-400"
          />
          <div
            class="absolute top-[16.75rem] left-[1.14rem] flex flex-col items-center justify-start gap-[0.56rem]"
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
              <div
                class="absolute top-[0rem] left-[0rem] w-[14.38rem] h-[2.5rem]"
              >
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
          <img
            class="absolute top-[1.25rem] left-[2.39rem] rounded-lgi w-[19.56rem] h-[14.94rem] object-cover"
            alt=""
            src="/nft6@2x.png"
          />
        </div>
        <div
          class="absolute top-[0rem] left-[53.22rem] w-[24.05rem] h-[30.75rem]"
        >
          <div
            class="absolute top-[0rem] left-[0rem] rounded-lg bg-gray-1100 box-border w-[24.05rem] h-[30.75rem] border-[2px] border-solid border-steelblue-400"
          />
          <img
            class="absolute top-[1.25rem] left-[2.35rem] rounded-lgi w-[19.94rem] h-[14.94rem] object-cover"
            alt=""
            src="/image-25@2x.png"
          />
          <div
            class="absolute top-[16.75rem] left-[1.1rem] flex flex-col items-center justify-start gap-[0.56rem]"
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
              <div
                class="absolute top-[0rem] left-[0rem] w-[14.38rem] h-[2.5rem]"
              >
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
      </div>
      <div
        class="absolute top-[59.25rem] left-[20.88rem] w-[78.31rem] h-[3.63rem]"
      >
        <div
          class="absolute top-[0rem] left-[0rem] rounded-3xs bg-silver-300 shadow-[0px_4px_10px_rgba(0,_0,_0,_0.25)] w-[24.24rem] h-[3.63rem]"
        />
        <div
          class="absolute top-[0rem] left-[27.04rem] rounded-3xs bg-silver-300 shadow-[0px_4px_10px_rgba(0,_0,_0,_0.25)] w-[24.24rem] h-[3.63rem]"
        />
        <div
          class="absolute top-[0rem] left-[54.07rem] rounded-3xs bg-silver-300 shadow-[0px_4px_10px_rgba(0,_0,_0,_0.25)] w-[24.24rem] h-[3.63rem]"
        />
        <div
          class="absolute top-[1.06rem] left-[62.85rem] font-semibold inline-block w-[6.68rem]"
        >
          Sold Artworks
        </div>
      </div>
      <div class="absolute top-[60.31rem] left-[29.19rem] font-semibold">
        Original Artworks
      </div>
      <div class="absolute top-[60.31rem] left-[58.63rem] font-semibold">
        Prints
      </div>
    </div>
    <div
      class="hidden flex-col items-start justify-start gap-[8.06rem] text-[3.19rem] font-caption-work-sans"
    >
      <div
        class="relative bg-gray-1100 w-[120rem] h-[82.69rem] overflow-hidden shrink-0"
      >
        <div
          class="absolute top-[61.26rem] left-[-8.64rem] bg-gray-1300 w-[138.54rem] h-[55.78rem] [transform:_rotate(-14.72deg)] [transform-origin:0_0]"
        />
        <div
          class="absolute top-[139.09rem] left-[123.5rem] bg-gray-1200 w-[170.44rem] h-[50.38rem] [transform:_rotate(-159.24deg)] [transform-origin:0_0]"
        />
        <footer
          imageDimensions="/logo.svg"
          imageCode="/discordlogo3.svg"
          imageCodeDimensions="/youtubelogo3.svg"
          imageCodeDimensions2="/twitterlogo.svg"
          imageCodeDimensionsText="/instagramlogo.svg"
          imageCodeDimensionsText2="/envelopesimple.svg"
          propTop="55.56rem"
          propLeft="0rem"
          :onDiscordLogoIconClick="onDiscordLogoIcon5Click"
          :onYoutubeLogoIconClick="onYoutubeLogoIcon5Click"
          :onTwitterLogoIconClick="onTwitterLogoIcon5Click"
          :onInstagramLogoIconClick="onInstagramLogoIcon5Click"
        />
        <Navigation1
          propHeight="7.56rem"
          propBackgroundColor="rgba(0, 0, 0, 0)"
          :onNavLogoClick="onNavLogo5Click"
        />
        <div
          class="absolute top-[9.94rem] left-[13.25rem] bg-darkslategray-300 [backdrop-filter:blur(4px)] w-[93.5rem] h-[45.81rem] flex flex-row items-center justify-start gap-[7.69rem]"
        >
          <img
            class="relative rounded-xl w-[36.69rem] h-[35.38rem] object-cover"
            alt=""
            src="/image-placeholder2@2x.png"
          />
          <div
            class="w-[30.81rem] flex flex-col items-start justify-start py-[6.25rem] px-[0rem] box-border gap-[2.5rem]"
          >
            <div class="w-[28.75rem] flex flex-col items-start justify-start">
              <div
                class="self-stretch flex flex-col items-start justify-start gap-[1.25rem]"
              >
                <div
                  class="self-stretch flex flex-row items-start justify-start"
                >
                  <div
                    class="flex-1 relative leading-[110%] capitalize font-semibold"
                  >
                    Create account
                  </div>
                </div>
                <div
                  class="self-stretch flex flex-col items-start justify-start text-[1.38rem]"
                >
                  <div class="self-stretch relative leading-[160%] capitalize">
                    Welcome! enter your details and start creating, collecting
                    and selling NFTs.
                  </div>
                </div>
              </div>
            </div>
            <div
              class="w-[20.63rem] flex flex-col items-start justify-start gap-[1.88rem] text-[1rem] text-gray-500"
            >
              <div
                class="self-stretch flex flex-col items-start justify-start gap-[0.94rem]"
              >
                <div
                  class="self-stretch rounded-xl bg-gray-1400 box-border h-[2.88rem] flex flex-row items-center justify-start py-[1rem] px-[1.25rem] gap-[0.75rem] border-[1px] border-solid border-caption-label-text"
                >
                  <img
                    class="relative w-[1.25rem] h-[1.25rem]"
                    alt=""
                    src="/user1.svg"
                  />
                  <div class="flex-1 relative leading-[140%]">Username</div>
                  <img
                    class="relative w-[1.25rem] h-[1.25rem] hidden"
                    alt=""
                    src="/eyeslash.svg"
                  />
                </div>
                <div
                  class="self-stretch rounded-xl bg-gray-1400 box-border h-[2.88rem] flex flex-row items-center justify-start py-[1rem] px-[1.25rem] gap-[0.75rem] border-[1px] border-solid border-caption-label-text"
                >
                  <img
                    class="relative w-[1.25rem] h-[1.25rem]"
                    alt=""
                    src="/envelopesimple2.svg"
                  />
                  <div class="flex-1 relative leading-[140%]">
                    Email Address
                  </div>
                  <img
                    class="relative w-[1.25rem] h-[1.25rem] hidden"
                    alt=""
                    src="/eyeslash.svg"
                  />
                </div>
                <div
                  class="self-stretch rounded-xl bg-gray-1400 box-border h-[2.88rem] flex flex-row items-center justify-start py-[1rem] px-[1.25rem] gap-[0.75rem] border-[1px] border-solid border-caption-label-text"
                >
                  <img
                    class="relative w-[1.25rem] h-[1.25rem]"
                    alt=""
                    src="/lockkey.svg"
                  />
                  <div class="flex-1 relative leading-[140%]">Password</div>
                  <img
                    class="relative w-[1.25rem] h-[1.25rem] hidden"
                    alt=""
                    src="/eyeslash.svg"
                  />
                </div>
                <div
                  class="self-stretch rounded-xl bg-gray-1400 box-border h-[2.88rem] flex flex-row items-center justify-start py-[1rem] px-[1.25rem] gap-[0.75rem] border-[1px] border-solid border-caption-label-text"
                >
                  <img
                    class="relative w-[1.25rem] h-[1.25rem]"
                    alt=""
                    src="/lockkey.svg"
                  />
                  <div class="flex-1 relative leading-[140%]">
                    Confirm Password
                  </div>
                  <img
                    class="relative w-[1.25rem] h-[1.25rem] hidden"
                    alt=""
                    src="/eyeslash.svg"
                  />
                </div>
              </div>
              <div
                class="self-stretch rounded-xl [background:linear-gradient(270deg,_#4287f6,_#d3e5fe)] h-[2.88rem] flex flex-row items-center justify-center py-[0rem] px-[3.13rem] box-border gap-[0.75rem] text-center text-neutral-0"
              >
                <img
                  class="relative w-[1.25rem] h-[1.25rem] hidden"
                  alt=""
                  src="/rocketlaunch3.svg"
                />
                <div class="relative leading-[140%] font-semibold">
                  Create account
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div
        class="relative bg-gray-1100 w-[120rem] h-[82.69rem] overflow-hidden shrink-0"
      >
        <div
          class="absolute top-[61.26rem] left-[-8.64rem] bg-gray-1300 w-[138.54rem] h-[55.78rem] [transform:_rotate(-14.72deg)] [transform-origin:0_0]"
        />
        <div
          class="absolute top-[139.09rem] left-[123.5rem] bg-gray-1200 w-[170.44rem] h-[50.38rem] [transform:_rotate(-159.24deg)] [transform-origin:0_0]"
        />
        <footer
          imageDimensions="/logo.svg"
          imageCode="/discordlogo3.svg"
          imageCodeDimensions="/youtubelogo3.svg"
          imageCodeDimensions2="/twitterlogo.svg"
          imageCodeDimensionsText="/instagramlogo.svg"
          imageCodeDimensionsText2="/envelopesimple.svg"
          propTop="55.56rem"
          propLeft="0rem"
          :onDiscordLogoIconClick="onDiscordLogoIcon6Click"
          :onYoutubeLogoIconClick="onYoutubeLogoIcon6Click"
          :onTwitterLogoIconClick="onTwitterLogoIcon6Click"
          :onInstagramLogoIconClick="onInstagramLogoIcon6Click"
        />
        <Navigation1
          propHeight="7.56rem"
          propBackgroundColor="rgba(0, 0, 0, 0)"
          :onNavLogoClick="onNavLogo6Click"
        />
        <div
          class="absolute top-[9.94rem] left-[13.25rem] bg-darkslategray-300 [backdrop-filter:blur(4px)] w-[93.5rem] h-[45.81rem] flex flex-row items-center justify-start gap-[7.69rem]"
        >
          <img
            class="relative rounded-xl w-[34.94rem] h-[38.94rem] object-cover"
            alt=""
            src="/image-placeholder3@2x.png"
          />
          <div
            class="w-[30.81rem] flex flex-col items-start justify-start py-[6.25rem] px-[0rem] box-border gap-[2.5rem]"
          >
            <div class="w-[28.75rem] flex flex-col items-start justify-start">
              <div
                class="self-stretch flex flex-col items-start justify-start gap-[1.25rem]"
              >
                <div
                  class="self-stretch flex flex-row items-start justify-start"
                >
                  <div
                    class="relative leading-[110%] capitalize font-semibold flex items-center w-[30.63rem] shrink-0"
                  >
                    LogIn With Mojarto
                  </div>
                </div>
                <div
                  class="self-stretch flex flex-col items-start justify-start text-[1.38rem]"
                >
                  <div class="self-stretch relative leading-[160%] capitalize">
                    Welcome! enter your details and start creating, collecting
                    and selling NFTs.
                  </div>
                </div>
              </div>
            </div>
            <div
              class="w-[20.63rem] flex flex-col items-start justify-start gap-[1.88rem] text-[1rem] text-silver-200"
            >
              <div
                class="self-stretch flex flex-col items-start justify-start gap-[0.94rem]"
              >
                <div
                  class="self-stretch rounded-xl bg-gray-1400 box-border h-[2.88rem] flex flex-row items-center justify-start py-[1rem] px-[1.25rem] gap-[0.75rem] border-[1px] border-solid border-caption-label-text"
                >
                  <img
                    class="relative w-[1.25rem] h-[1.25rem]"
                    alt=""
                    src="/envelopesimple2.svg"
                  />
                  <div class="flex-1 relative leading-[140%]">
                    Email Address
                  </div>
                  <img
                    class="relative w-[1.25rem] h-[1.25rem] hidden"
                    alt=""
                    src="/eyeslash.svg"
                  />
                </div>
                <div
                  class="self-stretch rounded-xl bg-gray-1400 box-border h-[2.88rem] flex flex-row items-center justify-start py-[1rem] px-[1.25rem] gap-[0.75rem] border-[1px] border-solid border-caption-label-text"
                >
                  <img
                    class="relative w-[1.25rem] h-[1.25rem]"
                    alt=""
                    src="/lockkey.svg"
                  />
                  <div class="flex-1 relative leading-[140%]">Password</div>
                  <img
                    class="relative w-[1.25rem] h-[1.25rem] hidden"
                    alt=""
                    src="/eyeslash.svg"
                  />
                </div>
              </div>
              <div
                class="self-stretch rounded-xl [background:linear-gradient(270deg,_#4287f6,_#d3e5fe)] h-[2.88rem] flex flex-row items-center justify-center py-[0rem] px-[3.13rem] box-border gap-[0.75rem] text-center text-neutral-0"
              >
                <img
                  class="relative w-[1.25rem] h-[1.25rem] hidden"
                  alt=""
                  src="/rocketlaunch3.svg"
                />
                <div class="relative leading-[140%] font-semibold">
                  Create account
                </div>
              </div>
            </div>
          </div>
        </div>
        <img
          class="absolute h-[1.66%] w-[3.63%] top-[55.86%] right-[43.03%] bottom-[42.48%] left-[53.33%] max-w-full overflow-hidden max-h-full"
          alt=""
          src="/group-41.svg"
        />
      </div>
    </div>
    <div
      class="relative bg-gray-1100 w-[120rem] h-[82.69rem] overflow-hidden shrink-0 hidden text-[0.75rem] font-bold-text-sm"
    >
      <div
        class="absolute top-[61.26rem] left-[-8.64rem] bg-gray-1300 w-[138.54rem] h-[55.78rem] [transform:_rotate(-14.72deg)] [transform-origin:0_0]"
      />
      <div
        class="absolute top-[139.09rem] left-[123.5rem] bg-gray-1200 w-[170.44rem] h-[50.38rem] [transform:_rotate(-159.24deg)] [transform-origin:0_0]"
      />
      <footer
        imageDimensions="/logo.svg"
        imageCode="/discordlogo3.svg"
        imageCodeDimensions="/youtubelogo3.svg"
        imageCodeDimensions2="/twitterlogo.svg"
        imageCodeDimensionsText="/instagramlogo.svg"
        imageCodeDimensionsText2="/envelopesimple.svg"
        propTop="55.56rem"
        propLeft="0rem"
        :onDiscordLogoIconClick="onDiscordLogoIcon7Click"
        :onYoutubeLogoIconClick="onYoutubeLogoIcon7Click"
        :onTwitterLogoIconClick="onTwitterLogoIcon7Click"
        :onInstagramLogoIconClick="onInstagramLogoIcon7Click"
      />
      <Navigation1
        propHeight="7.56rem"
        propBackgroundColor="rgba(0, 0, 0, 0)"
        :onNavLogoClick="onNavLogo7Click"
      />
      <div
        class="absolute top-[10.69rem] left-[7rem] w-[105.38rem] flex flex-row items-start justify-start py-[2rem] px-[5rem] box-border gap-[4.06rem]"
      >
        <div
          class="flex-1 flex flex-col items-start justify-start gap-[3.38rem]"
        >
          <div
            class="relative text-[2rem] leading-[150%] font-semibold font-caption-work-sans"
          >
            Your Cart
          </div>
          <div
            class="self-stretch flex flex-col items-start justify-start gap-[2.31rem]"
          >
            <div
              class="self-stretch flex flex-row items-start justify-start gap-[1.25rem]"
            >
              <div
                class="flex-1 rounded-xl flex flex-col items-start justify-center gap-[0.5rem]"
              >
                <div class="relative tracking-[1px] leading-[150%] uppercase">
                  First Name *
                </div>
                <div
                  class="self-stretch rounded-lg shadow-[0px_4px_4px_rgba(0,_0,_0,_0.25)] box-border h-[3rem] flex flex-row items-center justify-start py-[0rem] px-[1rem] text-[0.88rem] text-darkgray-100 border-[1px] border-solid border-neutral-50"
                >
                  <div class="flex-1 relative leading-[150%]">Placeholder</div>
                </div>
              </div>
              <div
                class="flex-1 rounded-xl flex flex-col items-start justify-center gap-[0.5rem]"
              >
                <div class="relative tracking-[1px] leading-[150%] uppercase">
                  Last Name *
                </div>
                <div
                  class="self-stretch rounded-lg box-border h-[3rem] flex flex-row items-center justify-start py-[0rem] px-[1rem] text-[0.88rem] text-darkgray-100 border-[1px] border-solid border-neutral-50"
                >
                  <div class="flex-1 relative leading-[150%]">Placeholder</div>
                </div>
              </div>
            </div>
            <div class="self-stretch flex flex-row items-start justify-start">
              <div
                class="flex-1 rounded-xl flex flex-col items-start justify-center gap-[0.5rem]"
              >
                <div class="relative tracking-[1px] leading-[150%] uppercase">
                  Email address *
                </div>
                <div
                  class="self-stretch rounded-lg box-border h-[3rem] flex flex-row items-center justify-start py-[0rem] px-[1rem] text-[0.88rem] text-darkgray-100 border-[1px] border-solid border-neutral-50"
                >
                  <div class="flex-1 relative leading-[150%]">
                    johndoe@example.com
                  </div>
                </div>
              </div>
            </div>
            <div
              class="self-stretch flex flex-row items-start justify-start gap-[1.25rem]"
            >
              <div
                class="flex-1 rounded-xl flex flex-col items-start justify-center gap-[0.5rem]"
              >
                <div class="relative tracking-[1px] leading-[150%] uppercase">
                  TELEGRAM CONTACT ( TELEGRAM CONTACT )
                </div>
                <div
                  class="self-stretch rounded-lg box-border h-[3rem] flex flex-row items-center justify-start py-[0rem] px-[1rem] text-[0.88rem] text-darkgray-100 border-[1px] border-solid border-neutral-50"
                >
                  <div class="flex-1 relative leading-[150%]">Placeholder</div>
                </div>
              </div>
              <div
                class="flex-1 rounded-xl flex flex-col items-start justify-center gap-[0.5rem]"
              >
                <div class="relative tracking-[1px] leading-[150%] uppercase">
                  ICQ CONTACT ( OPTIONAL)
                </div>
                <div
                  class="self-stretch rounded-lg box-border h-[3rem] flex flex-row items-center justify-start py-[0rem] px-[1rem] text-[0.88rem] text-darkgray-100 border-[1px] border-solid border-neutral-50"
                >
                  <div class="flex-1 relative leading-[150%]">Placeholder</div>
                </div>
              </div>
            </div>
          </div>
          <div
            class="self-stretch flex flex-col items-start justify-start pt-[2rem] px-[0rem] pb-[0rem] gap-[1.25rem] border-t-[1px] border-solid border-neutral-100"
          >
            <div
              class="rounded h-[2.25rem] flex flex-row items-center justify-center"
            >
              <div class="relative tracking-[1px] leading-[150%] uppercase">
                Where did you hear About Us?
              </div>
            </div>
            <div
              class="self-stretch rounded-lg box-border h-[6.13rem] flex flex-row items-start justify-start py-[0.75rem] px-[1rem] text-[0.88rem] text-darkgray-100 border-[1px] border-solid border-neutral-50"
            >
              <div class="flex-1 relative leading-[150%]">
                Notes about your order, e.g. special notes for delivery.
              </div>
            </div>
          </div>
        </div>
        <div
          class="rounded-2xl box-border w-[26.25rem] flex flex-col items-start justify-start p-[1.5rem] gap-[1.25rem] text-[0.88rem] text-neutral-200 border-[1px] border-solid border-neutral-50"
        >
          <div
            class="self-stretch hidden flex-col items-start justify-start gap-[1rem]"
          >
            <div
              class="self-stretch flex flex-row items-center justify-between"
            >
              <div class="relative leading-[150%]">
                Khalifa Kush (AAAA) | 1x
              </div>
              <div class="relative leading-[150%] text-neutral-900">
                $245.00
              </div>
            </div>
            <div
              class="self-stretch flex flex-row items-center justify-between"
            >
              <div class="relative leading-[150%]">
                Jungle Diamond (AA+) | 1x
              </div>
              <div class="relative leading-[150%] text-neutral-900">
                $200.00
              </div>
            </div>
            <div
              class="self-stretch flex flex-row items-center justify-between"
            >
              <div class="relative leading-[150%]">
                Shipwreck Edibles Gummy | 1x
              </div>
              <div class="relative leading-[150%] text-neutral-900">$52.00</div>
            </div>
          </div>
          <div
            class="self-stretch relative box-border h-[0.06rem] hidden border-t-[1px] border-solid border-neutral-50"
          />
          <div
            class="self-stretch flex flex-col items-start justify-start gap-[1rem]"
          >
            <div
              class="self-stretch flex flex-row items-center justify-between"
            >
              <div class="relative leading-[150%]">Subtotal</div>
              <div class="relative leading-[150%] text-neutral-900">
                <span>$497.00</span>
              </div>
            </div>
            <div
              class="self-stretch flex flex-row items-center justify-between"
            >
              <div class="relative leading-[150%]">Total item cost</div>
              <div class="relative leading-[150%] text-neutral-900">
                New York, US
              </div>
            </div>
            <div
              class="self-stretch flex flex-row items-center justify-between"
            >
              <div class="relative leading-[150%]">Coupon Discount</div>
              <div class="relative leading-[150%] text-neutral-900">$0.0</div>
            </div>
            <div
              class="self-stretch flex flex-row items-center justify-between"
            >
              <div class="relative leading-[150%]">Sub Total(0)</div>
              <div class="relative leading-[150%] text-neutral-900">$50.00</div>
            </div>
          </div>
          <div
            class="self-stretch relative box-border h-[0.06rem] border-t-[1px] border-solid border-neutral-50"
          />
          <div class="self-stretch flex flex-row items-center justify-between">
            <div class="relative leading-[150%]">Email Money Transfer</div>
            <img
              class="relative w-[1.25rem] h-[1.25rem]"
              alt=""
              src="/clip-path-group.svg"
            />
          </div>
          <div
            class="self-stretch flex flex-row items-start justify-start gap-[0.75rem] text-[1rem] text-neutral-100"
          >
            <div
              class="flex-1 rounded-lg box-border h-[3rem] flex flex-row items-center justify-start py-[0.25rem] px-[1.5rem] border-[1px] border-solid border-neutral-50"
            >
              <div class="flex-1 relative leading-[150%]">Coupon code</div>
            </div>
            <div
              class="rounded-81xl bg-steelblue-500 h-[3rem] flex flex-row items-center justify-center py-[0.5rem] px-[1.25rem] box-border text-[0.88rem] text-gray-400"
            >
              <div class="relative leading-[150%] font-medium">
                Apply Coupon
              </div>
            </div>
          </div>
          <div
            class="self-stretch relative box-border h-[0.06rem] border-t-[1px] border-solid border-neutral-50"
          />
          <div
            class="self-stretch rounded flex flex-row items-start justify-start gap-[0.63rem] text-neutral-300"
          >
            <div
              class="rounded-md bg-neutral-0 box-border w-[1.38rem] h-[1.38rem] flex flex-col items-center justify-center border-[1px] border-solid border-neutral-50"
            >
              <img
                class="relative w-[0.59rem] h-[0.39rem]"
                alt=""
                src="/tick.svg"
              />
            </div>
            <div class="flex-1 relative leading-[150%]">
              I confirm that my address is 100% correct and WILL NOT hold Top
              Shelf BC liable if this shipment is sent to an incorrect address.
              *
            </div>
          </div>
          <div
            class="self-stretch rounded flex flex-row items-start justify-start gap-[0.63rem] text-neutral-300"
          >
            <div
              class="rounded-md bg-neutral-0 box-border w-[1.38rem] h-[1.38rem] flex flex-col items-center justify-center border-[1px] border-solid border-neutral-50"
            >
              <img
                class="relative w-[0.59rem] h-[0.39rem]"
                alt=""
                src="/tick.svg"
              />
            </div>
            <div class="flex-1 relative leading-[150%]">
              Sign me up to receive email updates and news (optional)
            </div>
          </div>
          <div
            class="self-stretch relative box-border h-[0.06rem] border-t-[1px] border-solid border-neutral-50"
          />
          <div class="self-stretch flex flex-row items-center justify-between">
            <div class="flex flex-row items-center justify-start gap-[0.5rem]">
              <div
                class="rounded-81xl bg-other-orange w-[1.25rem] h-[1.25rem] flex flex-row items-center justify-center"
              >
                <img
                  class="relative w-[0.88rem] h-[0.88rem]"
                  alt=""
                  src="/vuesaxbolddollarcircle.svg"
                />
              </div>
              <div class="relative leading-[150%]">Your point</div>
              <div class="relative leading-[150%] text-neutral-900">10.850</div>
            </div>
            <div
              class="rounded-81xl bg-slategray w-[3.06rem] flex flex-row items-center justify-start p-[0.13rem] box-border"
            >
              <div
                class="relative rounded-[50%] bg-gray-900 w-[1.25rem] h-[1.25rem]"
              />
            </div>
          </div>
          <div
            class="self-stretch rounded-xl [background:linear-gradient(270deg,_#4287f6,_#d3e5fe)] h-[3.5rem] flex flex-row items-center justify-center py-[0rem] px-[3.13rem] box-border gap-[0.75rem] text-[1rem] text-neutral-0"
          >
            <div class="relative leading-[150%] font-medium">Place Order</div>
            <div
              class="relative box-border w-[0.06rem] h-[0.81rem] border-r-[1px] border-solid border-neutral-0"
            />
            <div class="relative leading-[150%] font-medium">$547.00</div>
          </div>
          <div
            class="flex flex-col items-start justify-start gap-[1rem] text-[0.75rem] text-neutral-300"
          >
            <div
              class="relative tracking-[1px] leading-[150%] uppercase font-light"
            >
              SECURE PAYMENTS PROVIDED BY
            </div>
            <div class="flex flex-row items-start justify-start gap-[0.75rem]">
              <div
                class="rounded-md bg-neutral-0 box-border w-[3.5rem] h-[2rem] flex flex-col items-center justify-center border-[1px] border-solid border-neutral-50"
              >
                <img
                  class="relative w-[1.88rem] h-[1.13rem]"
                  alt=""
                  src="/group-16.svg"
                />
              </div>
              <div
                class="rounded-md bg-neutral-0 box-border w-[3.5rem] h-[2rem] flex flex-col items-center justify-center border-[1px] border-solid border-neutral-50"
              >
                <img
                  class="relative w-[2.31rem] h-[0.88rem] overflow-hidden shrink-0"
                  alt=""
                  src="/visa.svg"
                />
              </div>
              <div
                class="rounded-md bg-neutral-0 box-border w-[3.5rem] h-[2rem] flex flex-col items-center justify-center border-[1px] border-solid border-neutral-50"
              >
                <img
                  class="relative w-[1.25rem] h-[1.25rem]"
                  alt=""
                  src="/group.svg"
                />
              </div>
              <div
                class="rounded-md bg-neutral-0 box-border w-[3.5rem] h-[2rem] flex flex-col items-center justify-center border-[1px] border-solid border-neutral-50"
              >
                <img
                  class="relative w-[1.25rem] h-[1.25rem]"
                  alt=""
                  src="/clip-path-group1.svg"
                />
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
  import { defineComponent } from "vue";
  import HowItWorks from "../components/HowItWorks.vue";
  import Tranding1 from "../components/Tranding1.vue";
  import Tranding from "../components/Tranding.vue";
  import HeroTextButtons from "../components/HeroTextButtons.vue";
  import HighlightedNFT from "../components/HighlightedNFT.vue";
  import Navigation1 from "../components/Navigation1.vue";
  import TopRatedArtists from "../components/TopRatedArtists.vue";
  import Footer from "../components/Footer.vue";
  import NFTCard from "../components/NFTCard.vue";

  export default defineComponent({
    name: "Frame",
    components: {
      HowItWorks,
      Tranding1,
      Tranding,
      HeroTextButtons,
      HighlightedNFT,
      Navigation1,
      TopRatedArtists,
      Footer,
      NFTCard,
    },
    methods: {
      onNavLogoClick() {
        window.open(
          "https://www.animaapp.com/?utm_source=figma-samples&utm_campaign=figma-nftmarket&utm_medium=figma-samples"
        );
      },
      onDiscordLogoIconClick() {
        window.open("https://discord.com/invite/eQxkYTNxSp");
      },
      onYoutubeLogoIconClick() {
        window.open("https://www.youtube.com/channel/UCXqr0Ca-b73rU9zcpSBJ5cw");
      },
      onTwitterLogoIconClick() {
        window.open("https://twitter.com/animaapp?lang=en");
      },
      onInstagramLogoIconClick() {
        window.open("https://www.instagram.com/animaapp/?hl=en");
      },
      onDiscordLogoIcon1Click() {
        window.open("https://discord.com/invite/eQxkYTNxSp");
      },
      onYoutubeLogoIcon1Click() {
        window.open("https://www.youtube.com/channel/UCXqr0Ca-b73rU9zcpSBJ5cw");
      },
      onTwitterLogoIcon1Click() {
        window.open("https://twitter.com/animaapp?lang=en");
      },
      onInstagramLogoIcon1Click() {
        window.open("https://www.instagram.com/animaapp/?hl=en");
      },
      onNavLogo1Click() {
        window.open(
          "https://www.animaapp.com/?utm_source=figma-samples&utm_campaign=figma-nftmarket&utm_medium=figma-samples"
        );
      },
      onDiscordLogoIcon2Click() {
        window.open("https://discord.com/invite/eQxkYTNxSp");
      },
      onYoutubeLogoIcon2Click() {
        window.open("https://www.youtube.com/channel/UCXqr0Ca-b73rU9zcpSBJ5cw");
      },
      onTwitterLogoIcon2Click() {
        window.open("https://twitter.com/animaapp?lang=en");
      },
      onInstagramLogoIcon2Click() {
        window.open("https://www.instagram.com/animaapp/?hl=en");
      },
      onNavLogo2Click() {
        window.open(
          "https://www.animaapp.com/?utm_source=figma-samples&utm_campaign=figma-nftmarket&utm_medium=figma-samples"
        );
      },
      onDiscordLogoIcon3Click() {
        window.open("https://discord.com/invite/eQxkYTNxSp");
      },
      onYoutubeLogoIcon3Click() {
        window.open("https://www.youtube.com/channel/UCXqr0Ca-b73rU9zcpSBJ5cw");
      },
      onTwitterLogoIcon3Click() {
        window.open("https://twitter.com/animaapp?lang=en");
      },
      onInstagramLogoIcon3Click() {
        window.open("https://www.instagram.com/animaapp/?hl=en");
      },
      onNavLogo3Click() {
        window.open(
          "https://www.animaapp.com/?utm_source=figma-samples&utm_campaign=figma-nftmarket&utm_medium=figma-samples"
        );
      },
      onDiscordLogoIcon4Click() {
        window.open("https://discord.com/invite/eQxkYTNxSp");
      },
      onYoutubeLogoIcon4Click() {
        window.open("https://www.youtube.com/channel/UCXqr0Ca-b73rU9zcpSBJ5cw");
      },
      onTwitterLogoIcon4Click() {
        window.open("https://twitter.com/animaapp?lang=en");
      },
      onInstagramLogoIcon4Click() {
        window.open("https://www.instagram.com/animaapp/?hl=en");
      },
      onNavLogo4Click() {
        window.open(
          "https://www.animaapp.com/?utm_source=figma-samples&utm_campaign=figma-nftmarket&utm_medium=figma-samples"
        );
      },
      onDiscordLogoIcon5Click() {
        window.open("https://discord.com/invite/eQxkYTNxSp");
      },
      onYoutubeLogoIcon5Click() {
        window.open("https://www.youtube.com/channel/UCXqr0Ca-b73rU9zcpSBJ5cw");
      },
      onTwitterLogoIcon5Click() {
        window.open("https://twitter.com/animaapp?lang=en");
      },
      onInstagramLogoIcon5Click() {
        window.open("https://www.instagram.com/animaapp/?hl=en");
      },
      onNavLogo5Click() {
        window.open(
          "https://www.animaapp.com/?utm_source=figma-samples&utm_campaign=figma-nftmarket&utm_medium=figma-samples"
        );
      },
      onDiscordLogoIcon6Click() {
        window.open("https://discord.com/invite/eQxkYTNxSp");
      },
      onYoutubeLogoIcon6Click() {
        window.open("https://www.youtube.com/channel/UCXqr0Ca-b73rU9zcpSBJ5cw");
      },
      onTwitterLogoIcon6Click() {
        window.open("https://twitter.com/animaapp?lang=en");
      },
      onInstagramLogoIcon6Click() {
        window.open("https://www.instagram.com/animaapp/?hl=en");
      },
      onNavLogo6Click() {
        window.open(
          "https://www.animaapp.com/?utm_source=figma-samples&utm_campaign=figma-nftmarket&utm_medium=figma-samples"
        );
      },
      onDiscordLogoIcon7Click() {
        window.open("https://discord.com/invite/eQxkYTNxSp");
      },
      onYoutubeLogoIcon7Click() {
        window.open("https://www.youtube.com/channel/UCXqr0Ca-b73rU9zcpSBJ5cw");
      },
      onTwitterLogoIcon7Click() {
        window.open("https://twitter.com/animaapp?lang=en");
      },
      onInstagramLogoIcon7Click() {
        window.open("https://www.instagram.com/animaapp/?hl=en");
      },
      onNavLogo7Click() {
        window.open(
          "https://www.animaapp.com/?utm_source=figma-samples&utm_campaign=figma-nftmarket&utm_medium=figma-samples"
        );
      },
    },
  });
</script>
