<template>
  <div id="navbar">
   <nav class="navbar navbar-expand-md top">
    <a href="http://semicolon.africa/" class="navbar-brand">
        <img src="./semilogo.svg" alt="Semicolon" class="lo">
    </a>
    <button type="button" class="navbar-toggler" data-toggle="collapse" data-target="#navbarCollapse">
        <span class="navbar-toggler-icon"></span>
    </button>

    <div class="collapse navbar-collapse" id="navbarCollapse">
      <div class="navbar-nav ml-auto">
           <ul class="navbar-nav drop">
      <!--<li class="nav-item"><h2 class="nav-link">Applicant Record</h2></li> -->
      <li class="nav-item dropdown drop">
      
        <a class="nav-link dropdown-toggle" href="#" id="navbarDropdownMenuLink" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false" style="color: #960C0C; padding-left: 1100px;">
          Hello, Sam
        </a>
        <div class="dropdown-menu" aria-labelledby="navbarDropdownMenuLink">
          <a class="dropdown-item" href="#">Action</a>
          <a class="dropdown-item" href="#">Another action</a>
          <a class="dropdown-item" href="#">Something else here</a>
        </div>
      </li>
    </ul>
        </div>
    </div>
</nav>
   
  </div>
</template>

<script>

export default {
  name: 'navbar',

}
</script>

<style>
.lo{
  /* height: 34px; */
  padding-top: 12px;
  /* margin-left: 15px; */
  position: absolute;
  left: 9.38%;
  right: 75.8%;
  top: 15%;
  bottom: 92.22%;
}

.drop{
  color: red;
  position: relative;
  left: -58px;
  right: 30.8%;
  top: 3.33%;
  bottom: 92.22%;
 
}

.top{
  /* background-color: #FFFFFF; */
}

</style>


