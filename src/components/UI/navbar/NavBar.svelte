<script>
  import NavLink from "./NavLink.svelte";

const navLinks = [
  {
    id: 1,
    label: "Home",
    url: "#"
  },
  {
    id: 2,
    label: "Catalog",
    url: "#"
  },
  {
    id: 1,
    label: "Contact",
    url: "#"
  },
]
</script>

<div>
<nav>
  <ul>
    {#each navLinks as link}
    <NavLink navLink={link} />      
    {/each}
  </ul>
</nav>
</div>

<style lang="scss">
nav {
  width: 100%;
  ul {
    display: flex;
    justify-content: space-between;
  }
}
</style>