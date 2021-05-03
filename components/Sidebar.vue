<template>

<div class="sidebar">

  <nuxt-link to="/"> <img alt="Hi" src="/favicon.ico" style="width:100px;height:100px;">

  </nuxt-link>

   <nuxt-link to="/ask">Ask</nuxt-link>
  <nuxt-link to="/questions/1">Explore</nuxt-link>



  </div>
  <!--

   -->

</template>

<style scoped>

/*




 */
@import url('https://fonts.googleapis.com/css2?family=Montserrat&display=swap');
    .sidebar {
      margin-right: 10%;
      padding: 20px;
      width: 20%;
      background-color: #444952;
      /* background-color:burlywood; */
      position: fixed;
      height: 100%;
      font-size: 1em;
      overflow: auto;
      font-size: 25px;
   justify-content: center;
  align-items: center;
  text-align: center;
}


    .sidebar a {
      /* margin-right: 20px; */
      display: block;
      /* color: #818181; */
      color: burlywood;
      padding: 16px;
      text-decoration: none;
    }

    .sidebar a.active {
      background-color: burlywood;
      border: 2px solid red;

    }

    .sidebar a:hover:not(.active) {
      border-radius: 15px;
       background-color: burlywood;

      border-left: 5px solid rgba(112, 21, 21, 0.87);


      color: rgba(112, 21, 21, 0.87);
      font: bold;
    }
     div.content {
      margin-left: 200px;
      padding: 1px 16px;
      height: 1000px;
    }

    h1,
    h2,
    h3,
    h4,
    h5,
    h6,
    p,
    a {
font-family: 'Montserrat', sans-serif;    }





    .main {
      margin-left: 20%;
      margin-right: 10%;
      font-size: 28px;
      padding: 10px 10px;
    }

    /**/

    @media screen and (max-width: 700px) {
      .sidebar {
        width: 100%;
        height: auto;
        position: relative;
      }

      .sidebar a {
        float: left;
      }

      div.content {
        margin-left: 0;
      }
    }

    @media screen and (max-width: 400px) {
      .sidebar a {
        text-align: center;
        float: none;
      }
    }



</style>
