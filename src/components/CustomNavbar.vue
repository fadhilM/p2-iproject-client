<template>
  <div class="navbar bg-base-100 shadow-2xl">
    <div class="navbar-start">
      <div class="dropdown">
        <label tabindex="0" class="btn btn-primary btn-square rounded-2xl">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            class="h-5 w-5"
            fill="none"
            viewBox="0 0 24 24"
            stroke="currentColor"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              d="M4 6h16M4 12h16M4 18h7"
            />
          </svg>
        </label>
        <ul
          tabindex="0"
          class="menu menu-compact dropdown-content mt-3 p-2 shadow bg-base-100 rounded-box w-52"
        >
          <li><router-link to="/travel">Travel</router-link></li>
          <li>
            <router-link to="/" class="text-left"
              >Estimate Carbon Production</router-link
            >
          </li>
        </ul>
      </div>
    </div>
    <div class="navbar-center">
      <a class="btn btn-ghost normal-case text-xl">CARBON </a>
    </div>
    <div class="navbar-end"></div>
  </div>
</template>

<script>
export default {
  name: "CustomNavbar",
};
</script>

<style></style>
