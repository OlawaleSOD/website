<template>
  <div>
  <b-navbar toggleable="sm" type="light" variant="light">
    <b-navbar-toggle target="nav-text-collapse"></b-navbar-toggle>

    <b-navbar-brand class="mx-5">
      <a href="#">
      <img src="/raxzle.png"
      </a>
      <span href="#" class="font-semibold text-xl tracking-tight"><a href="#">Braxzle</a></span>
    </b-navbar-brand>

    <b-collapse id="nav-text-collapse" is-nav>
      <b-navbar-nav>

      <b-nav>
    <b-nav-item class="mx-3">Work</b-nav-item>
    <b-nav-item class="mx-3">About</b-nav-item>
    <b-nav-item-dropdown right>
      <template slot="button-content">Download</template>
          <b-dropdown-item href="#">Resume</b-dropdown-item>
          <b-dropdown-item href="#">Cover Letter</b-dropdown-item>
        </b-nav-item-dropdown>
      </b-nav>
    
      </b-navbar-nav>
    </b-collapse>
  </b-navbar>
</div>
</template>

