<template>
  <body >
  <section class="content-main">
    <header>
      <img src="@/assets/astronaut.svg">
      <span>Perguntas frequentes</span>
      <h1>Escolha a categoria desejada</h1>
    </header>
   
    <main>
      <div class="wrapper">
        <img src="@/assets/rocket.svg">
        <router-link class="p" :to="{path:'/about'}">Bootcamp</router-link>
        
      </div>
      

      <div class="wrapper">
        <img src="@/assets/astronaut-helmet.svg">
        <p>Bootcamp</p>
      </div>
      <div class="wrapper">
        <img src="@/assets/student-hat.svg">
        <p>Cataline</p>
      </div>
      <div class="wrapper">
        <img src="@/assets/partnership.svg">
        <p>Parcerias</p>
      </div>
    </main>
  </section>
</body>
</template>


<script>
  /* eslint-disable */

export default {
    name: "App",
}
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Lato:wght@300;400;700&family=Nunito+Sans:wght@400;700&family=Poppins:ital,wght@0,700;1,400&display=swap');


  :root {

/* Colors: */
--unnamed-color-26282c: #26282C;
--unnamed-color-3f4452: #3F4452;
--unnamed-color-5d6681: #5D6681;
--unnamed-color-f5f6f8: #F5F6F8;
--unnamed-color-22e0db: #22E0DB;
--unnamed-color-935e92: #935E92;
}

body {
  
  background: #404451;
}

header {
  display: flex;
  flex-direction: column;
  align-items: center;
}
img {
  margin-top: 20px;
  width: 20rem;
}
span {
  font-family: 'Lato', sans-serif;
  font-size: 20px;
  font-weight: bold;
  color: #F5F6F8;
  position: relative;
  top: 30px;
}
h1 {
  font-family: 'Lato', sans-serif;
  font-weight: regular;
  font-size: 13px;
  color: #F5F6F8;
  margin-top: 40px;
  margin-right: 25px;
}
.wrapper {
  margin-top: 20px;
  display: flex;
  justify-content: center;
  align-items: center;
  gap: 3rem;
  border-radius: 8px;
  cursor: pointer;
}
.wrapper img {
  width: 50px;
  margin-right: 1rem;
 
}
 .p {
  text-decoration: none;
  font-family: 'Lato';
  font-size: 17px;
  color: #F5F6F8;
  margin-top: 30px;
}
.wrapper:hover {
  background: #484d5bb3;
}
</style>
