<script lang="ts">
  import 'boxicons';
  let color = '#CACCD9';
</script>

<div class="nav-tools">
  <button>
    <box-icon name='search' color={color} ></box-icon>
  </button>
  |
  <button>
    <box-icon name='map' type='solid' color={color} ></box-icon>
  </button>
  <button>
    <box-icon name='cart' color={color} ></box-icon>
  </button>
</div>

<style>
  .nav-tools {
    display: flex;
    align-items: center;
    gap: 10px;
  }
  button {
    background: transparent;
    border: none;
    display: flex;
    justify-content: center;
    align-items: center;
  }
</style>
