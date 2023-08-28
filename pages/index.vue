<template>
  <div class="container">
    <ul class="menu">
      <li><router-link to="/"> Home </router-link></li>
      <li><router-link to="/about"> About </router-link></li>
      <li><router-link to="/contact"> Contact </router-link></li>
    </ul>
    <h1>Selamat datang di website pertama saya</h1>
    <p style="color: blue; text-align: left;">Ini merupakan website pertama saya yang menggunakan framework.
      framework yang saya gunakan adalah nuxt.js, sebelumnya saya belum pernah membuat website dengan menggunakan framework
    </p>
  </div>
  
</template>

<script>
</script>
<style scoped>
.container {
    width: 75%;
    margin: 100px auto;
    text-align: center;
    color: red;
}

 .menu  {
    border-radius: 25px;
    height: fit-content;
    display: inline-flex;
    background-color: rgba(0, 0, 0, .4);
    -webkit-backdrop-filter: blur(10px);
    backdrop-filter: blur(10px);  
    align-items: center;
    padding: 0 20px;
    margin: 50px 0 0 0;
 }

 .menu li {
  list-style: none;
		color: white;
		font-family: sans-serif;
		font-weight: bold;
		padding: 12px 16px;
		margin: 0 8px;
		position: relative;
		cursor: pointer;
		white-space: nowrap;
 }

 .menu li a {
    padding: 20px;
    text-decoration: none;
 }
</style>
