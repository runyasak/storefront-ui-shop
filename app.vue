<template>
  <div class="container mx-auto p-8">
    <div class="flex flex-col md:flex-row flex-wrap gap-6 max-w-[1540px]">
      <div
        class="relative flex md:max-w-[1536px] md:[&:not(:first-of-type)]:flex-1 md:first-of-type:w-full bg-negative-200"
      >
        <div class="flex justify-between overflow-hidden grow">
          <div
            class="flex flex-col justify-center items-start p-6 lg:p-10 max-w-1/2"
          >
            <p
              class="uppercase typography-text-xs block font-bold tracking-widest md:typography-headline-6"
            >
              Be inspired
            </p>
            <h2
              class="mb-4 mt-2 font-bold typography-headline-3 md:typography-headline-2"
            >
              {{ title }}
            </h2>
            <p class="typography-text-base block mb-4">
              Step out in style with our sunglasses collection
            </p>
            <SfButton class="!bg-black">Discover now</SfButton>
          </div>
          <img
            src="https://docs.storefrontui.io/v2-vue/_nuxt/display.2aeba4ea.png"
            :alt="title"
            class="w-1/2 self-end object-contain"
          />
        </div>
      </div>
    </div>
  </div>
</template>

<script lang="ts" setup>
import { SfButton } from "@storefront-ui/vue";

const title = ref("Fashion Store");
</script>
