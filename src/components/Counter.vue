<template>
  <form>
    <div>
      <h1>Buy Token- TEST</h1>
     
      <div>
        <button type="button" class="signupbtn" v-on:click="test">Sign Up</button>
        <h1>{{message}}</h1>
      </div>
    </div>
  </form>
</template>


<script>
  export default {
    data() {
      return {
        message: 1
      }
    },
    methods: {
      test(){
        this.message = this.message + 1;
        console.log("Mohit");
      }
    },
  }
</script>

<style  scoped>

</style>