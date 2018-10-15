<template>
  <header>
    <!-- Navigation Area -->
    <nav>
      <ul>
        <li>
          <nuxt-link to="/">Home</nuxt-link>
        </li>
        <li>
          <nuxt-link to="/about">About</nuxt-link>
        </li>
        <li>Contact</li>
      </ul>
    </nav>
  </header>
</template>


<style lang="scss">
nav {
  ul {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 30px;
    background-color: #41b883;
    color: #ffff;
    list-style: none;
    padding: 0;
    margin: 0;

    li {
      margin: 0 20px;
      a {
        color: #fff;
        &:hover {
          color: #ccc;
          text-decoration: none;
        }
      }
    }
  }
}
</style>
