<template>
    <div class="container">
      <ul class="menu">
        <li><router-link to="/"> Home </router-link></li>
        <li><router-link to="/about"> About </router-link></li>
        <li><router-link to="/contact"> Contact </router-link></li>
      </ul>
      <section class="content">
        <p>
            Ini adalah website pertama saya yang menggunakan framework nuxt.js 
            Saya akan terus belajar agar project ini berhasil.
        </p>
      </section>
    </div>
  </template>

<style scoped>
.container {
    width: 75%;
    margin: 100px auto;
    text-align: center;
    
}

a:hover {
  color: yellow;
}

 .menu  {
    border-radius: 25px;
    height: fit-content;
    display: inline-flex;
    background-color: rgba(29, 28, 28, 0.925);
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
