<template>
    <div>
        <div class="todoListContianer">
            <div class="heading">
                <h2 id="title">Todo List</h2>
            </div>
        </div>
    </div>
</template>

<script>

import addItem from './addItem.vue'
import listView from "./listView.vue"

export default {
    components:{
        addItem,
        listView
    }
}

</script>


<style scoped>
    .todoListContianer {
        width: 350px;
        margin: auto;
    }
    .heading{
        background: #e6e6e6;
        padding: 10px;
    }
    #title {
        text-align: center;

    }

</style>
