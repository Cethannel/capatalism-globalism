<script lang="ts">
  import Header from "./Header.svelte";
</script>

<div class="text">
  <slot name="heading"/>
  <ul>
    <slot />
  </ul>
</div>

<style lang="scss">
main {
  margin-left: 0;
  margin-right: 0;
}

.text {
  box-shadow: 0px 0px 2px gray;
  text-align: left;
  margin-left: 20em;
  margin-right: 20em;
  margin-top: 2em;
  width: 80%;
}
</style>
