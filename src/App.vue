<script setup></script>

<template>
  <h1 class="text-7xl font-bold underline">Hello Tailwind</h1>
  <br />
  <div>
    <h3 class="text-2xl font-blod text-center text-green-500">
      什麼是兔兔教？?🐰
    </h3>
    <p>
      一種兔兔的信仰教派，本派信奉真神兔兔，且每時每刻都將兔兔放在心中，期待兔兔降臨為我們出生時所帶的原紅蘿蔔通通吃乾淨，以讓我們可以進兔兔天國。
    </p>
    <div>
      <ul class="list-decimal list-inside">
        <li>每天都吃紅蘿蔔</li>
        <li>不吃紅蘿蔔就吃菜</li>
      </ul>
    </div>
    <div>
      <button class="underline text-blue-500">
        <b><i>信兔兔，無 Bug</i></b>
      </button>
    </div>
    <div
      class="bg-blue-500 text-white text-white w-40 h-40 text-center border-8 border-blue-300 rounded-3xl bg-gradient-to-tl from-yellow-300 via-red-500 to-indigo-500"
    >
      兔兔方塊
    </div>
    <div
      id="衛生所"
      class="max-w-19rem bg-floor bg-red-200 m-20 px-5 py-8 grid gap-6 grid grid-cols-4"
    >
      <span class="兔 沒口罩 flex-shrink-0 col-start-2 col-span-2"></span>
      <span class="兔 有口罩 flex-shrink-0"></span>
      <span class="兔 有口罩 flex-shrink-0"></span>
      <span class="兔 有口罩 flex-shrink-0"></span>
      <span class="兔 有口罩 flex-shrink-0"></span>
      <span class="兔 有口罩 flex-shrink-0"></span>
      <span class="兔 有口罩 flex-shrink-0"></span>
      <span class="兔 有口罩 flex-shrink-0"></span>
      <span class="兔 有口罩 flex-shrink-0"></span>
    </div>
  </div>
</template>

<style scoped>
.兔 {
  @apply w-10 h-5 inline-block relative;
}
.兔::after {
  content: '';
  @apply w-full h-36 block bg-contain bg-bottom bg-no-repeat absolute bottom-0;
}

.有口罩::after {
  background-image: url(https://i.imgur.com/qOW9ojH.png);
}

.沒口罩::after {
  background-image: url(https://i.imgur.com/48r5sL3.png);
}
</style>
