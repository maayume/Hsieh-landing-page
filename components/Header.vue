<template>
  <header class="flex items-center justify-between h-20 mx-auto p-7 lg:px-10">
    <img src="/logo.png" class="w-30 h-10" />

    <div class="justify-self-end flex">
    <ul class="md:flex items-center space-x-3 hidden">
      <template v-for="(n) in nav" :key="n">
        <li>
          <NuxtLink
            class="
              inline-block
              p-2
              rounded-full
              text-blue-700
              font-bold
              text-sm
              hover:text-blue-300
              transition-all
              duration-300"
              :to="n.link"
            >
            {{ n.name }}
          </NuxtLink>
        </li>
      </template>
    </ul>
      <NuxtLink
        to="/#contact"
        class="
          ml-4
          px-5
          py-2
          text-sm
          bg-blue-700
          text-white
          rounded-full
          hover:bg-blue-300
          transition-all
          duration-500"
        >
        CONTATO
      </NuxtLink>
    </div>
  </header>
</template>

<script setup>
  const nav = [
    {
      name: "INÍCIO",
      link: "/",
    },
    {
      name: "SOBRE MIM",
      link: "/#about",
    },
    {
      name: "EXPERIÊNCIA",
      link: "/#specialities",
    },
  ]
</script>