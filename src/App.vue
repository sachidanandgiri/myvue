<template>
  <div id="app">
    <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link> |
      <router-link to="/contact">Contact</router-link>
      </div>
    <router-view />
    <footer>
      &copy; Awesome Company
    </footer>
    <!-- <keep-alive>
      <router-view />
    </keep-alive> -->
  </div>
</template>
