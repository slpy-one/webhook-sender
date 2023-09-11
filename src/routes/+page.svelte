<script>
  import 'animate.css'

	import TW from "$lib/constants/tailwind";
</script>

<svelte:head>
  <title>SLPY Webhook sender</title>
</svelte:head>

<section class="w-full h-screen !bg-cover !bg-center !bg-no-repeat" style="background: url('https://frame.caffe.quest/cdn')">
  <div class="w-full h-full flex flex-col items-center text-center justify-center bg-[rgba(0,0,0,0.8)] backdrop-blur-md">
    <h1 class={`${TW.heading.xxxl} font-bold animate__animated animate__fadeInDown`}>
      Webhook Sender
    </h1>
    <p class={`${TW.heading.l} animate__animated animate__fadeInDown`} style="animation-delay: .5s;">
      Test your webhook styling and send it to your discord webhook :)
    </p>
    <div class="animate__animated animate__fadeInDown" style="animation-delay: 1s;">
      <a href="/hook" class="block my-4 p-4 bg-ctp-sapphire text-ctp-base rounded hover:opacity-60 hover:scale-95">
        Get started →
      </a>
    </div>
  </div>
</section>

<style>

</style>