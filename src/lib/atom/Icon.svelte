<script lang="ts">
  export let icon;
</script>

<div>
  <slot />
  <svelte:component this={icon} /> 
  <!-- 컴포넌트가 변수회 되면 svelte:component 를 사용 할 것 -->
</div>


