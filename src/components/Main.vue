<template>
  <section class="todoapp">  
     <header class="header">
        <h1>todos</h1>
        <input class="new-todo" autofocus="autofocus" autocomplete="off" placeholder="What needs to be done?">
    </header> 
      <section class="main" >  
          <ul class="todo-list">  
            <li class="todo">
                <div class="view">
                    <input type="checkbox" class="toggle"> 
                    <label>ghfgh</label> <button class="destroy"></button>
                </div> 
                <input type="text" class="edit"></li>
          </ul>  
      </section>   
      <Footer></Footer>
  </section>  
</template>

<script>
    import { mapState,mapMutations,mapActions } from "vuex"
    import Footer from "./Footer"
    export default {
        name: 'Main',
        data () {
            return {
                msg: 'Welcome to Your Vue.js App'
            }
        },
        components:{
            Footer
        }
    }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
