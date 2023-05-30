<script lang="ts">
  import { type NavLink } from "../../../types";

  export let navLink: NavLink;
</script>

<li>
  <a href={navLink.url}>{navLink.label}</a>
</li>

<style lang="scss">
  li {
    list-style: none;
    a {
      text-decoration: none;
    }
  }
</style>