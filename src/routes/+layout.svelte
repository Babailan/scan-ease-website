<script>
  import "./global.css";
  import Logo from "../icons/logo/Logo.svelte";
  import GithubLogo from "../icons/github-mark-white.png";
  import { onMount } from "svelte";
</script>

<main class="px-5 sm:p-10 md:px-20">
  <nav class="flex items-center justify-between">
    <div>
      <Logo />
    </div>
    <div class="flex gap-5 font-medium">
      <!-- right col -->
      <a href="/downloads" class="flex items-center gap-3 hover:underline"
        >Download</a
      >

      <a
        href="https://github.com/Babailan/scan-ease-website"
        target="_blank"
        class="flex items-center gap-3 hover:underline"
        ><span>Github Repository</span>
        <span><img src={GithubLogo} alt="" class="w-5" /></span>
      </a>
    </div>
  </nav>
  <slot />
</main>
