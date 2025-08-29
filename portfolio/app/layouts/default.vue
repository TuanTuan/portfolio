<template>
  <div class="container mx-auto max-w-2xl">
    <header class="flex justify-between items-center mt-5">
        <div class="hidden md:block">
          <NuxtLink to="/" class="text-xl font-semibold p-2 hover:bg-gray-200 dark:hover:bg-gray-800">TuanTuan
          </NuxtLink>
        </div>
        <Menu />
    </header>
    <main class="p-2 mt-4">
      <slot />
    </main>
  </div>
</template>
