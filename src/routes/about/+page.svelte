<script lang="ts">
  import TW from "$lib/constants/tailwind";
</script>

<svelte:head>
  <title>About | SLPY Webhook sender</title>
</svelte:head>

<section class="md:w-[80%] w-full min-h-screen flex flex-row items-center justify-center text-center mx-auto">
  <div class="h-[50vh] w-full overflow-y-auto">
    <h1 class={`${TW.heading.xxxl} underline !py-4`}>
      About
    </h1>   
    <p class="w-full md:w-[50%] mx-auto text-[18px]">
      This project is got inspiration from <a href="https://discohook.org/" target="_blank" class={TW.link}>discohook.org</a> which is used to send embed discord webhook and payload sample from <a href="https://gist.github.com/dmdboi/743111ae5945a1fe1ea558039cbe25f7" target="_blank" class={TW.link}>dmdboi's gist</a>. If you want to update anything its okay to send a pull request to the <a href="https://github.com/slpy-one/webhook-sender" target="_blank" class={TW.link}>repository</a> :)
    </p>
    <p class="py-4"></p>
    <p class="w-full md:w-[50%] mx-auto text-[18px]">
      This is one of various project that under organize name <a href="https://github.com/slpy-one" target="_blank" class={TW.link}>slpy one team.</a> in MIT LICENSE & Open source. If you love this project don't fotget to leave a star on this <a href="https://github.com/slpy-one/webhook-sender" target="_blank" class={TW.link}>repository</a> and follow us on <a href="https://github.com/slpy-one" target="_blank" class={TW.link}>github</a>.
    </p>
  </div>
</section>