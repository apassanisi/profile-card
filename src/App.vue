<template>
  <div
    class="font-body w-screen h-screen flex flex-col items-center bg-gradient-to-b from-gray-50 to-[#d2d6db] py-[120px]"
  >
    <div class="max-w-[340px] shadow bg-white rounded-lg px-4 py-8">
      <div class="flex flex-col items-center justify-center gap-6 text-center">
        <img class="h-16 w-16 rounded-full" src="./assets/profile.png" />
        <div class="flex flex-col">
          <span class="font-medium text-xl text-center text-neutral-900">Sarah Dole</span>
          <span class="font-normal text-sm text-center text-neutral-600">Front End Engineer @ Microsoft</span>
        </div>
        <div>
          <span
          class="font-normal text-base text-center text-neutral-600"
            >I turn coffee into bugs which are fixed by someone else. Certified
            Stack Overflow and ChatGPT developer.</span
          >
        </div>
        <div class="w-full">
          <button class="flex text-white w-full justify-center items-center gap-1.5 self-stretch bg-indigo-700 px-4 py-2.5 rounded">Contact me</button>
        </div>
        <div class="flex flex-row gap-10 w-full justify-center items-center">
          <img class="h-5 w-5" src="./assets/github-fill.png" />
          <img class="h-5 w-5" src="./assets/linkedin-box-fill.png" />
          <img class="h-5 w-5" src="./assets/instagram-fill.png" />
          <img class="h-5 w-5" src="./assets/twitter-x-fill.png" />
        </div>
      </div>
    </div>
  </div>
</template>
