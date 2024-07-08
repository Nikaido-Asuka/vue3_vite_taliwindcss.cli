
<template>
  <div class=" flex justify-center flex-col items-center border bg-blue-900 h-screen">
    <div class="title flex text-center flex-col">
      <div>
        <span class=" text-white font-bold text-8xl">Asuka</span>
        <span class="text-white text-7xl">&nbsp;の 脚手架</span>
      </div>
      <p class=" mt-6 flex justify-center items-center text-2xl text-white font-extralight">基于<span class=" font-semibold text-green-500">&nbsp;Vue3</span> + <span class=" font-semibold text-orange-400">&nbsp;Vite</span> + <span class=" font-semibold text-blue-500">&nbsp;tailwindcss</span>&nbsp;搭建的快速项目脚手架 🤣 👉 🤡</p>
    </div>

    <a href="https://github.com/Nikaido-Asuka" target="_blank">
      <div class="btn mt-10 px-16 py-5 rounded-lg text-center text-white">
        <div class=" text-lg ">点击开始查看</div>
        <div class="flex font-light gap-3 justify-center items-center">
          <img class=" w-5" src="./assets/github.png"/>
          <span>@Asuka</span>
        </div>
      </div>
    </a>
   

    <div class="power mt-6 h-20 flex items-center">
      <div class="left  w-1/4 text-lg text-white font-medium">Powered by:</div>
      <div class="right w-3/4 flex justify-around items-center">

        <a href="https://vitejs.dev" target="_blank">
          <div class=" flex justify-around items-center gap-2">
            <img src="./assets/vue.svg" class="w-6" alt="Vue logo" />
            <span class="text-white">vue.js</span>
          </div>
        </a>

        <a href="https://vitejs.dev" target="_blank">
          <div class=" flex justify-around items-center gap-2">
            <img src="/vite.svg" class="w-6" alt="Vite logo" />
            <span class="text-white">vitejs</span>
          </div>
        </a>

        <a href="https://vitejs.dev" target="_blank">
          <div class=" flex justify-around items-center gap-2">
            <img src="./assets/tailwindCSS.png" class="w-6" alt="Vite logo" />
            <span class="text-white">tailwindcss</span>
          </div>
        </a>

      </div>
    </div>


  </div>
 
</template>

<script setup lang="ts">
</script>


<style scoped>
.power{
  width: 30%;
}
.btn{
  background-color: #0b66c0;
  cursor: pointer;
}
</style>
