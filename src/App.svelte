<script lang="ts">
  import NavBar from "./components/UI/navbar/NavBar.svelte";
  import SocialBlock from "./components/UI/social/SocialBlock.svelte";
  import Header from "./components/UI/header/Header.svelte";
</script>

<main class="container">
  <Header />
  <div class="content">
    <div class="side">
      <NavBar />
      <SocialBlock />
    </div>
    <div class="main">
  
    </div>
  </div>
</main>

<style>
  .container {
    display: flex;
    flex-direction: column;
  }
  .content {
    display: flex;
    height: 95%;
  }
.side {
  width: 30%;
  background-color: blueviolet;
}
.main {
  width: 70%;
  background-color: brown;
}
</style>
