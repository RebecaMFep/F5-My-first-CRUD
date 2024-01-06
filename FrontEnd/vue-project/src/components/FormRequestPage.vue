<script setup>


</script>

<template>

<header>

</header>



    <body class=" d-flex justify-content-center align items-center vh-100">
     
     <form @submit.prevent="login" class="bg-danger opacity-75  p-5 rounded-5" style="width: 300px; height: 350px">
         
       <div class="text-center fw-bold mt-4"><h1>Welcome</h1></div>
 
       <div class="input-group mt-1">
         
       <input class="form-control border border-black" type="text"  id="email" aria-describedby="emailHelp" placeholder="Username" v-model="username">
           
       </div>
 
       <div class="input-group mt-3 ">
     
         <input class="form-control border border-black" type="password"  id="password" placeholder="Password" v-model="password">
 
       </div>
 
         <button type="submit" class=" form-control btn btn border border-black mt-3">Log in</button> 
 
       <!-- <div v-if="showAlert" class="alert alert-danger mt-3" role="alert">
          Invalid username or password. Please try again.
       </div> -->
     </form> 
    
</body>

<footer>

</footer>
   
</template>




<style lang="scss" scoped>

</style>