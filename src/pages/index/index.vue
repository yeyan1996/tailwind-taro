<template>
  <view class="mb-20 white-children">
    <view class="w-1_4 bg-blue-400 h-40">25% width</view>
    <view class="w-1_2 bg-blue-400 h-40">50% width</view>
    <view class="w-3_4 bg-blue-400 h-40">75% width</view>
    <view class="w-full bg-blue-400 h-40">100% width</view>
  </view>

  <view class="bg-purple-300 mb-20">
    <text class="font-mono">
      font-mono: The quick brown fox jumps over the lazy dog.
    </text>
  </view>

  <view class="flex items-start bg-pink-300 mb-20">
    <view class="mr-20">align-start</view>
    <view class="h-120 w-80 bg-purple-600 rounded text-white">1</view>
    <view class="h-240 w-80 ml-10 bg-purple-600 rounded text-white">2</view>
    <view class="h-160 w-80 ml-10 bg-purple-600 rounded text-white">3</view>
  </view>

  <view class="border-solid border-4 border-blue-500 rounded mb-20 flex justify-center">
      border
  </view>

  <view class="rounded bg-yellow-500 w-100 mb-20 ml-1_3 flex justify-center text-white">rounded</view>

  <view class="bg-gradient-to-r from-yellow-400 via-red-500 to-pink-500 h-30 flex justify-center items-center">
    <text class="text-white">bg-gradient-to-r</text>
  </view>

  <button class="text-sm w-200 py-3 rounded-md font-semi bold text-white bg-blue-500 shadow-2xl mt-20">shadow</button>
</template>


<style>
.white-children view{
  @apply text-white
}
</style>
