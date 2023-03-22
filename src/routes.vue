const routes=[
{
  name:"signup"
  component:"SignUp"
  path:"/signup"
}]
<template>
    <div class="routes">
    <button v-on:click="signUp">Login</button>
   <p>
     router-link to="/sign-up">Sign Up</router-link>
   </p>
</div>
</template>
<script>

export default{
    name:"Login",
}
</script>

