<template>
  <div class="hello">
    <div class="bg-gray-50">
      <div class="max-w-screen-xl mx-auto py-2 px-4 sm:px-6 lg:py-2 lg:px-8 lg:flex lg:items-center lg:justify-between">
        <h2 class="text-3xl leading-9 font-extrabold tracking-tight text-gray-900 sm:text-4xl sm:leading-10">
          <span class="text-indigo-600">{{ msg }}</span>
        </h2>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: 'HelloWorld',
  props: {
   msg: String
  }
}
</script>
