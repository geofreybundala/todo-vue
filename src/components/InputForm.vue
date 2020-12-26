<template>
    <div class="mt-4 mx-3"> 
        <label class="block">
            <!-- <span class="text-gray-700">Title</span> -->
            <input type="text" class="mt-1 block w-full" placeholder="Please white your Todo Title">
        </label>
        <label class="block">
              <span class="text-gray-700">Description</span>
              <textarea class="mt-1 block w-full h-24" rows="3" placeholder="Enter some long form content."></textarea>
        </label>

            <label class="block">
            <span class="text-gray-700">Time</span>
            <input type="datetime-local" class="mt-1 block w-full" placeholder="john@example.com">
        </label>
    </div>
</template>

<script>
export default {
    name:'InputForm'
}
</script>