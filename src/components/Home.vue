<template>
    <div class=''>
    <Header/>
    <Todo/>
    </div>
</template>

<script>

import Todo from './Todo-Home.vue'
import Header from './common/Header.vue'


export default {
    name:'Home',
    components:{
        Todo,
        Header
    }
}
</script>
