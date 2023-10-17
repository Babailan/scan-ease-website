<script>
  import { onMount } from "svelte";

  function test() {
    alert("gago");
  }
  onMount(() => {
    document.title = "HomePage | ScanEase";
  });
</script>

<div class="max-w-3xl py-20">
  <p class="text-sky-300 font-bold mb-5">By the makers of Tailwindcss</p>
  <h1 class="text-5xl sm:text-6xl font-extrabold">
    Make your business more astonishing.
  </h1>
  <p class="text-gray-200 mt-2">
    Beautifully designed, expertly crafted components, built by the student of
    <span class="font-bold text-sky-500">
      Young Achiever School of Caloocan.
    </span> The perfect starting point for your next business.
  </p>
  <div class="flex">
    <button
      class="bg-sky-600 text-white py-3 px-5 rounded-md mt-3 font-medium flex gap-1"
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
    <button class="bg-sky-600 rounded-md">
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
