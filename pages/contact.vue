<template>
    <div class="container">
      <ul class="menu">
        <li><router-link to="/"> Home </router-link></li>
        <li><router-link to="/about"> About </router-link></li>
        <li><router-link to="/contact"> Contact </router-link></li>
      </ul>
      <section class="content">
        <p>
            Bila ingin membantu saya untuk menjadi programmer dapat menghubungi saya melalui
        </p>
        <ul class="contact">
            <li>Facebook</li>
            <li>Telegram</li>
            <li>Whatsapp</li>
        </ul>
      </section>
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
   
   .contact {
    border-radius: 25px;
      height: fit-content;
      display: inline-flex;
      background-color: rgba(160, 253, 9, 0.911);
      -webkit-backdrop-filter: blur(10px);
      backdrop-filter: blur(10px);  
      align-items: center;
      padding: 0 20px;
      margin: 50px 0 0 0;
   }

   .contact li {
    list-style: none;
    color: rgb(24, 22, 22);
    font-family: sans-serif;
    font-weight: bold;
    padding: 12px 16px;
    margin: 0 8px;
    position: relative;
    cursor: pointer;
    white-space: nowrap;
   }

   .contact li a {
      padding: 20px;
      text-decoration: none;
   }
   
</style>
  