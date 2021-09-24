<template>
  <div>
        <h1 class="pt-12 pb-8 text-center text-5xl font-extrabold">Hello, beautiful human!</h1>
        <p>Welcome to my little corner on the web.</p>
        <p>Here are some unedited pretty pictures to lift your mood and... fill this page up. &#128517;</p>
        <br />
        <div class="flex flex-col gap-1 items-center">
          <div class="m-auto p-3 border-2 border-grey w-2/5">
            <img src='~assets/lake.JPG' alt="Mirror Lake">
          </div>
          <br>
          <div class="m-auto p-3 border-2 border-grey w-2/5">
            <img src='~assets/lone-red-tree.JPG' alt="Lone Red Tree">
          </div>
          <br>
          <div class="m-auto p-3 border-2 border-grey w-2/5">
            <img src='~assets/rain-mountains.JPG' alt="Pouring on Mountains">
          </div>
          <br>
          <div class="m-auto p-3 border-2 border-grey w-2/5">
            <img src='~assets/jardin-luxem.JPG' alt="Grey in Sky Rainbow on Earth">
          </div>                              
        </div>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({})
</script>

<style>
p {
  padding: 12px 32px;
  text-align: left;
  font-size: 24px;
}
</style>