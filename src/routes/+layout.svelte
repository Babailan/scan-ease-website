<script>
  import "./global.css";
  import Logo from "../icons/logo/Logo.svelte";
</script>

<main class="p-5 sm:p-10 md:p-20">
  <nav class="flex items-center justify-between">
    <div>
      <Logo />
    </div>
    <div class="flex gap-5">
      <!-- right col -->
      <a href="">Download</a>

      <a href="">Github</a>
    </div>
  </nav>
  <slot />
</main>
