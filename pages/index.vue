<template>
  <main>
    <section class="self-center flex flex-col flex-1 items-center justify-center">
      <h1 class="title text-center">Bienvenue sur mon blog</h1>
      <h2 class="subtitle text-center">ici on parle tech 😁 mais pas que !</h2>
    </section>

    <section class="mt-8">
      <h3 class="text-primary-600 dark:text-primary-400 max-w-5xl mx-auto">Les derniers articles</h3>
      <posts post-type="blog" :amount="1" />
    </section>
  </main>
</template>