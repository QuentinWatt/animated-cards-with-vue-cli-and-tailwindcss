<template>
  <div class="border flex flex-col">
    <img :src="image" />

    <div class="p-3 flex-1 flex flex-col">
      <div class="flex-1">
        <h3 class="font-bold text-2xl">
          {{ title }}
        </h3>

        <div class="my-3">
          {{ description }}
        </div>
      </div>

      <div>
        <p class="font-bold text-2xl">{{ currencySymbol }} {{ price }}</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "ProductCard",
  props: {
    title: {
      type: String,
      default: null
    },
    description: {
      type: String,
      default: null
    },
    currencySymbol: {
      type: String,
      default: "$"
    },
    price: {
      type: String,
      default: null
    },
    image: {
      type: String,
      default: ""
    }
  }
};
</script>
