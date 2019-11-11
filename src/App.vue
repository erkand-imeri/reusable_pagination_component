<template>
<div id="container">
    <h1 class="text-center">Pagination Component</h1>

    <Pagination />
    
</div>    
</template>

<script>
import Pagination from './Pagination';

export default {
    components: {
        Pagination
    }
    
}
</script>
<style scoped>
#container {
    width: 60%;
    margin-left: auto;
    margin-right: auto;
    background-color: #f7faf8;
    border-radius: 3px;
    box-shadow: 0px 2px 5px 1px #c9c9c9;
    min-height: 75vh;
}
.text-center {
    text-align: center;
}
</style>
