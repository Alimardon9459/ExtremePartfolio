<template>
  <q-layout view="hHh lpR fFf">

    <q-header bordered class="bg-transparent text-white row items-center">
      <q-toolbar >
        <q-toolbar-title  class="q-ml-lg" >
          <router-link to="/">          <img src="https://xtrm.foxthemes.me/wp-content/uploads/2018/09/white.png" alt="Xtrm"  ></router-link>
        </q-toolbar-title>
        <q-item class="row items-center" >
          <div class="text text-weight-bold q-ml-xl" style="font-size:14px; font-family: sans-serif;"> HOME</div>
          <div class="text text-weight-bold q-ml-xl" style="font-size:14px; font-family: sans-serif;"> PAGES</div>
          <div class="text text-weight-bold q-ml-xl" style="font-size:14px; font-family: sans-serif;">  SHOWCASES</div>
          <div class="text text-weight-bold q-ml-xl" style="font-size:14px; font-family: sans-serif;"> BLOG</div>
          <div class="text text-weight-bold q-ml-xl" style="font-size:14px; font-family: sans-serif;"><router-link to="/shop" >SHOP</router-link></div>
          <div class="text text-weight-bold q-ml-xl" style="font-size:14px; font-family: sans-serif;"> PRICING</div>
          <div class="text text-weight-bold q-ml-xl" style="font-size:14px; font-family: sans-serif;"> CONTACT US</div>
        </q-item>
        <q-item class="q-ml-xl q-mr-md">
          <q-icon size="24px" class="q-mr-lg" name="search"/>
          <q-icon size="24px" name="work_outline"/>
        </q-item>

      </q-toolbar>

    </q-header>

    <q-page-container>
      <router-view />
    </q-page-container>

  </q-layout>
</template>
<style scoped>
  .bg-transparent{
    height: 80px;
    border-color: rgb(201, 196, 196);
  }
  .text{
    transition: 0.5s;
  }
  .text:hover{
    color: yellow;
  }
  a{
    text-decoration: none;
    color: white;
  }
  a:hover{
    color: yellow;
  }
</style>
