<script>
export default {
  data() {
    return {
      menuData: [
        {
          name: "CHARACTER",
          src: "#",
        },
        {
          name: "COMICS",
          src: "#",
        },
        {
          name: "MOVIES",
          src: "#",
        },
        {
          name: "TV",
          src: "#",
        },
        {
          name: "GAMES",
          src: "#",
        },
        {
          name: "COLLECTIBLES",
          src: "#",
        },
        {
          name: "VIDEOS",
          src: "#",
        },
        {
          name: "FANS",
          src: "#",
        },
        {
          name: "NEWS",
          src: "#",
        },
        {
          name: "SHOP",
          src: "#",
        },
      ],
    };
  },
};
</script>

<template>
  <nav>
    <ul>
      <li v-for="menuItem in menuData" :key="menuItem.name">
        <a :href="menuItem.src">{{ menuItem.name }}</a>
      </li>
    </ul>
  </nav>
</template>

<style lang="scss" scoped>
nav {
  margin: auto;
}
ul {
  display: flex;
  justify-content: center;
  align-items: center;
  gap: 0.5rem;
  list-style: none;
}
a {
  text-decoration: none;
  color: black;
  padding-right: 0.5rem;
}
</style>
