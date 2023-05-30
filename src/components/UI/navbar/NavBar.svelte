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
  width: 30%;
    height: 100%;
  ul {
    width: 60%;
    display: flex;
    flex-direction: column;
    justify-content: space-around;
  }
}
</style>