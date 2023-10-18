<script>
  import { onMount } from "svelte";
  import HomePageImage from "../images/homepage.jpg";
  function test() {
    alert("gago");
  }
  onMount(() => {
    document.title = "HomePage | ScanEase";
  });
</script>

<div class="flex gap-10">
  <div class="max-w-3xl py-20">
    <p class="text-primary font-bold mb-5">By the student of YASC.</p>
    <h1 class="text-5xl sm:text-6xl font-extrabold">
      Make your business more astonishing.
    </h1>
    <p class="text-gray-200 mt-2">
      <span class="font-black">Open-Source</span> that is beautifully designed,
      a crafted software application, built by the student of
      <span class="font-bold text-primary">
        Young Achiever School of Caloocan.
      </span> The perfect starting point for your next business.
    </p>
    <div class="mt-5 flex gap-2">
      <button
        class="bg-primary hover:bg-secondary text-white py-3 px-7 rounded-md flex gap-1 font-bold"
        on:click={test}
      >
        <span> Windows (x64) </span>
      </button>
      <button
        class="bg-primary hover:bg-secondary text-white py-3 px-7 rounded-md flex gap-1 font-bold"
        on:click={test}
      >
        <span> Linux (x64) </span>
      </button>
    </div>
    <p class="mt-5 text-sm">
      By downloading and using Postman, I agree to the <a
        href="/"
        class="text-sky">Privacy Policy</a
      >
      and <a href="/" class="text-sky">Terms</a>.
    </p>
    <div class="flex gap-2 mt-2 text-sm">
      <a href="/" class="text-sky">Release Notes</a>
      <p>·</p>
    </div>
  </div>
  <div class="max-w-lg lg:block hidden">
    <img class="w-full h-full object-cover" src={HomePageImage} alt="" />
  </div>
</div>

<!-- Feature -->
<div class="mt-20">
  <h1 class="text-5xl font-black text-primary">Features</h1>
  <div class="mt-5 max-w-5xl">
    <h2 class="font-bold text-2xl">Data Visualization</h2>
    <p>
      Data visualization is a powerful feature that transforms raw data into
      visual representations, enhancing clarity, revealing insights, aiding
      communication, and enabling the rapid identification of outliers and
      anomalies.
    </p>
  </div>
</div>
