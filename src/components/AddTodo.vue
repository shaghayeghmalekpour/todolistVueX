<template>
 <div>
   <h3>Add TODO</h3>
   <div class="add">
     <form>
       <input type="text" v-model="title" placeholder="Add Todo...">
       <input type="submit" value="submit">
     </form>
   </div>
 </div>
</template>

<script>
export default {
  name: "AddTodo.vue"
}
</script>

<style scoped>
form{
  display: flex;
}

input[type='text']{
  flex: 10;
  padding: 10px;
  border: 1px solid #41b883;
  outline: 0;
}

input[type='submit']{
  flex: 2;
  background: #42b983;
  color: white;
  border: 1px solid #42b983;
  cursor: pointer;
}
</style>