<template>
    <footer class="footer">  
        <span class="todo-count">  
            <strong></strong>left                     
        </span>  
        <ul class="filters">  
            <router-link to="/All" tag="li">All</router-link>
            <router-link to="/Active" tag="li">Active</router-link>
            <router-link to="/Completed" tag="li">Completed</router-link>
        </ul>  
    </footer> 

</template>
<script>
    export default {
        name: "Footer"
    }
</script>
