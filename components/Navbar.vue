<template>
  <b-navbar sticky toggleable="sm" type="dark" variant="dark" v-b-scrollspy:scrollspy-nested>
    <b-navbar-brand href="#">Gunjan Patel</b-navbar-brand>

    <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

    <b-navbar-nav>
      <b-nav-item href="#home">Home</b-nav-item>
      <b-nav-item href="#about">About</b-nav-item>
    </b-navbar-nav>

    <b-collapse id="nav-collapse" is-nav>

      <!-- Right aligned nav items -->
      <b-navbar-nav class="ml-auto">

        <b-nav-item href="https://github.com/gunjanpatel" target="_blank"><b-icon icon="github"></b-icon></b-nav-item>
        <b-nav-item href="https://www.linkedin.com/in/jgunjanpatel/" target="_blank"><b-icon icon="linkedin"></b-icon></b-nav-item>

      </b-navbar-nav>
    </b-collapse>
  </b-navbar>
</template>
