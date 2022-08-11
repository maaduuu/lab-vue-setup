<template>

    <div>
        <div id="check-box">
          <input type="checkbox" id="todo-item" />
        <label for="todo-item">My Todo Item</label>  
        </div>
        
    </div>
    

</template>

<script>
export default {
  name: 'app',
  props: {

  }
};
</script>

<style>

*{
    padding: 0;
    margin: 0;
    background-color: aquamarine;
}

body {
    display: flex;
    justify-content: center;
}
li{
    list-style: none;
    
}
</style>