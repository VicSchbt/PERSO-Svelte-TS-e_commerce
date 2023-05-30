<script lang="ts">
  import 'boxicons';
  import SocialButton from './SocialButton.svelte';

  const socialLinks = [
    {
      id: 1,
      url: "#",
      name: 'instagram'
    },
    {
      id: 2,
      url: "#",
      name: 'facebook'
    },
    {
      id: 3,
      url: "#",
      name: 'twitter'
    },
    {
      id: 4,
      url: "#",
      name: 'google'
    }
  ]
</script>

<div class="social-block">
  {#each socialLinks as link}
  <SocialButton url={link.url}>
    <box-icon name={link.name} type='logo' color='#caccd9' ></box-icon>
  </SocialButton>
  {/each}
 
</div>

<style>
  .social-block {
    display: grid;
    grid-template-columns: max-content max-content;
    gap: 10px;
  }
</style>

