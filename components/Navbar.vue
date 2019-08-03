<template>
  <div>
  <b-navbar fixed="top" toggleable="sm" type="light" variant="light">
    <b-navbar-toggle target="nav-text-collapse"></b-navbar-toggle>

    <b-navbar-brand class="mx-5">
      <a href="/">
      <img src="/raxzle.png">
      </a>
      <span href="/" class="text-white"><a href="/">Braxzle</a></span>
    </b-navbar-brand>

    <b-collapse id="nav-text-collapse" is-nav>
      <b-navbar-nav>
        <b-nav>
          <b-nav-item class="mx-3"><nuxt-link to="/work">Work</nuxt-link></b-nav-item>
          <b-nav-item class="mx-3"><nuxt-link to="/about">About</nuxt-link></b-nav-item>          
          <b-nav-item><nuxt-link to="/resume">Resume</nuxt-link></b-nav-item>
        </b-nav>
      </b-navbar-nav>
    </b-collapse>
  </b-navbar>
</div>
</template>

