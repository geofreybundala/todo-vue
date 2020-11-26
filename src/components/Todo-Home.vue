<template>
    <div class="mt-11 grid grid-cols-2 h-screen">
        <div class="bg-gray-100 shadow-md mx-3 h-full space-y-4">items list
            <List/>
        </div>
        <div class="bg-gray-100 shadow-md mx-3 h-full">add items here</div>
    </div>
</template>

<script>
import List from './List.vue';
export default {
    name:'Todo-Home',
    components:{
        List
    }

}
</script>