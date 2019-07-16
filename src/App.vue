<template>
  <div id="app">
    <div class="border-b mb-12">
      <div class="container mx-auto py-3">
        <span class="text-2xl font-bold">
          Cards
        </span>
      </div>
    </div>

    <div class="container mx-auto">
      <div class="flex">
        <ProductCard
          image="https://images.pexels.com/photos/1752806/pexels-photo-1752806.jpeg?cs=srgb&dl=blurred-background-close-up-clouds-1752806.jpg&fm=jpg"
          title="Coffee"
          description="The best coffee you'll ever have"
          price="200"
          currency-symbol="$"
          class="w-72 mr-6"
        />
        <ProductCard
          image="https://images.pexels.com/photos/1752806/pexels-photo-1752806.jpeg?cs=srgb&dl=blurred-background-close-up-clouds-1752806.jpg&fm=jpg"
          title="Another product"
          description="Lorem ipsum dolor sit amet, consectetur adipisicing elit. Adipisci, alias dolor, enim est facere fuga ipsum itaque minus perspiciatis quae quidem soluta voluptatem? Eaque minima nesciunt obcaecati quas quia voluptas?"
          price="200"
          currency-symbol="$"
          class="w-72"
        />
      </div>
    </div>
  </div>
</template>

<script>
import ProductCard from "./components/ProductCard";

export default {
  name: "app",
  components: {
    ProductCard
  }
};
</script>

<style lang="postcss">
@import "assets/css/main.css";
</style>
