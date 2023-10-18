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
    <div class="flex gap-3 mt-5">
      <button
        class="bg-primary hover:bg-secondary text-white py-3 px-5 rounded-md flex gap-1"
        on:click={test}
      >
        <span> Download for windows </span>
        <span>
          <svg
            xmlns="http://www.w3.org/2000/svg"
            height="24"
            viewBox="0 -960 960 960"
            width="24"
            class="fill-white"
            ><path
              d="M480-320 280-520l56-58 104 104v-326h80v326l104-104 56 58-200 200ZM240-160q-33 0-56.5-23.5T160-240v-120h80v120h480v-120h80v120q0 33-23.5 56.5T720-160H240Z"
            /></svg
          >
        </span>
      </button>
      <button class="bg-primary hover:bg-secondary rounded-md p-3">
        <span>
          <svg
            xmlns="http://www.w3.org/2000/svg"
            height="24"
            viewBox="0 -960 960 960"
            width="24"
            class="fill-white"
            ><path
              d="M160-120q-33 0-56.5-23.5T80-200v-280h80v280h360v80H160Zm160-160q-33 0-56.5-23.5T240-360v-280h80v280h360v80H320Zm160-160q-33 0-56.5-23.5T400-520v-240q0-33 23.5-56.5T480-840h320q33 0 56.5 23.5T880-760v240q0 33-23.5 56.5T800-440H480Zm0-80h320v-160H480v160Z"
            /></svg
          >
        </span>
      </button>
    </div>
  </div>
  <div class="max-w-lg lg:block hidden">
    <img class="w-full h-full object-cover" src={HomePageImage} alt="" />
  </div>
</div>

<!-- Feature -->
<div class="mt-20">
  <h1 class="text-3xl font-black">Features</h1>
</div>
