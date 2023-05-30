<script lang="ts">
  import 'boxicons';
  export let url: string;
</script>

<a href={url}>
  <slot></slot>
</a>

<style lang="scss">
  a {
    height: 32px;
    width: 32px;
    display: flex;
    justify-content: center;
    align-items: center;
    border: solid 1px #CACCD9;
    border-radius: 50%;
    background-color: transparent;
    transition: box-shadow 0.5s ease-out;
    &:hover {
      background-color: white;
      border: none;
      box-shadow: 0px 0px 10px -3px rgba(202, 204, 217, 1);
    }
  }
</style>