<template>
  <div class="relative">
    <Header />
        <h1 class="pt-32 pb-8 text-center text-5xl font-extrabold">Hello, beautiful human!</h1>
        <p>Welcome to my little corner on the web.</p>
        <p>Here are some pretty pictures to lift your mood and... fill this page up. &#128517;</p>
        <div class="flex flex-col items-center pb-10">
          <div class="m-auto p-8">
            <img src='~assets/lake.JPG' alt="Mirror Lake">
          </div>
          <br>
          <div class="m-auto p-8">
            <img src='~assets/lone-red-tree.JPG' alt="Lone Red Tree">
          </div>
          <br>
          <div class="m-auto p-8">
            <img src='~assets/rain-mountains.JPG' alt="Pouring on Mountains">
          </div>
          <br>
          <div class="m-auto p-8">
            <img src='~assets/jardin-luxem.JPG' alt="Grey in Sky Rainbow on Earth">
          </div>                              
        </div>
    <Footer />
  </div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({})
</script>

<style>
img {
  border: 1px solid #ddd;
  border-radius: 4px;
  padding: 5px;
  height: 400px;
  width: 100%;
}

p {
  padding: 12px 32px;
  text-align: left;
  font-size: 24px;
}
</style>