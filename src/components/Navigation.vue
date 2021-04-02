<template>
  <!-- HEADER -->
  <header class="block">
    <ul class="header-menu horizontal-list">
      <li>
        <router-link to="/login">
          <a class="header-menu-tab" href="#3"
            ><span class="icon fontawesome-sign-in-alt scnd-font-color"></span
            >Login</a
          >
        </router-link>
      </li>
      <li>
        <router-link to="/planner">
          <a class="header-menu-tab" href="#3"
            ><span class="icon fontawesome-edit scnd-font-color"></span
            >Planner</a
          >
        </router-link>
      </li>
      <li>
        <router-link to="/events">
          <a class="header-menu-tab" href="#2"
            ><span class="icon fontawesome-calendar scnd-font-color"></span
            >Events</a
          >
        </router-link>
      </li>
      <li>
        <router-link to="/guest">
          <a class="header-menu-tab" href="#1"
            ><span class="icon fontawesome-user scnd-font-color"></span>Guest</a
          >
        </router-link>
      </li>
      <li>
        <router-link to="/reports">
          <a class="header-menu-tab" href="#5"
            ><span class="icon fontawesome-file-alt scnd-font-color"></span
            >Viewer</a
          >
        </router-link>
      </li>
    </ul>
    <router-link to="/login">
      <div class="profile-menu">
        <p>
          Me
          <a href="#26"
            ><span class="entypo-down-open scnd-font-color"></span
          ></a>
        </p>
        <div class="profile-picture small-profile-picture">
          <img
            width="40px"
            alt="Mark Zuck Pic"
            src="https://yourwikis.com/wp-content/uploads/2020/01/mark-zuck-img.jpg"
          />
        </div>
      </div>
    </router-link>
  </header>
</template>

<script>
export default {
  name: "Navigation",
  props: {},
};
</script>

<style lang="scss">
@import "../assets/sass/main";
</style>
