<template>
  <div class="container px-0">
    <b-navbar
      class="b-navbar navbar-custom"
      toggleable="lg"
      type="dark"
      variant=""
    >
      <b-navbar-brand class="b-navbar-brand"
        ><NuxtLink class="b-navbar-brand" to="/"
          >Digital Reflection</NuxtLink
        ></b-navbar-brand
      >

      <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

      <b-collapse id="nav-collapse" is-nav>
        <!-- Right aligned nav items -->
        <b-navbar-nav class="ml-auto">
          <b-nav-item-dropdown text="First Year" right>
            <b-dropdown-item
              ><NuxtLink class="b-navbar b-navbar-link" to="/"
                >Introduction</NuxtLink
              ></b-dropdown-item
            >
            <b-dropdown-item
              ><NuxtLink
                class="b-navbar b-navbar-link"
                to="/cstpGrowthDevelopment"
                >Growth & Development</NuxtLink
              ></b-dropdown-item
            >
            <b-dropdown-item href="/impactOnStudentSuccess"
              >Impact on Student Success</b-dropdown-item
            >
          </b-nav-item-dropdown>
          <b-nav-item-dropdown text="Second Year" right>
            <b-dropdown-item href="#">Example1</b-dropdown-item>
            <b-dropdown-item href="#">Example2</b-dropdown-item>
          </b-nav-item-dropdown>
        </b-navbar-nav>
      </b-collapse>
    </b-navbar>
  </div>
</template>