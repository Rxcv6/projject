<script lang="ts">
  import { page } from "$app/stores";
  import Button from "$lib/components/ui/button/button.svelte";
  import Arrow from "$lib/components/Arrow.svelte";
  let x = "<";
</script>

<div class="flex flex-col justify-center items-center min-h-screen">
  <div class="con">
    <div class="text text-white text-xl md:text-5xl">Welcome To My Site</div>
  </div>
</div>
<div class="view">
  <div class="blockk text-white flex justify-center text-2xl md:text-4xl mx-0">
    Hi, do u want to know who I am?
  </div>
  <div
    class="blockk text-white flex justify-center text-2xl md:text-4xl mx-0 pt-64"
  >
    My name is Badr Alyasi
  </div>
  <div
    class="blockk text-white flex justify-center ml-4 text-2xl md:text-4xl mx-0 pt-96"
  >
    I'm Computer science student and I'll show some of my projects but don't be
    rude im new to this field {x}3
  </div>
  <div class="blockk text-white flex justify-center text-4xl pt-96">
    <!-- svelte-ignore a11y-img-redundant-alt -->
    <img src="calu.png" alt="photo  " class=" object-cover h-[40rem]" />
  </div>
  <div class="blockk text-white flex justify-center text-4xl pt-96"></div>
  <div
    class="blockk text-white flex justify-center ml-5 text-2xl md:text-4xl mx-0 pt-96"
  >
    I know it's calculator and maybe it's easy for you but hey it's my first
    project
  </div>
  <div class="h-[30rem] flex justify-center items-center mx-auto">
    <Button
      class="bg-transparent flex justify-center items-center text-4xl"
      href=" https://redstonecalculator.netlify.app/"
      target="true"
      >Try it!
    </Button>
  </div>
  <div
    class="blockk text-white flex justify-center ml-6 text-2xl md:text-4xl mx-0 pt-64"
  >
    It was a good project and I had fun making it
  </div>
  <div
    class="blockk text-white flex justify-center text-2xl md:text-4xl mx-0 pt-64"
  >
    Now to the second project
  </div>
  <div class="blockk text-white flex justify-center text-4xl pt-96">
    <!-- svelte-ignore a11y-img-redundant-alt -->
    <img
      src="todo.png"
      alt="photo  "
      class=" object-cover h-[20rem] md:h-[40rem] md:w-fit"
    />
  </div>
  <div class="blockk text-white flex justify-center text-4xl pt-96"></div>
  <div class="blockk text-white flex justify-center text-4xl pt-96">
    A wonderful To-Do list I love it
  </div>

  <div class="h-[30rem] flex justify-center items-center mx-auto">
    <Button
      class="bg-transparent flex justify-center items-center text-4xl"
      href=" https://redstonetodolist.netlify.app/"
      target="true"
      >Try it!
    </Button>
  </div>

  <div class="blockk text-white flex justify-center text-4xl pt-96">
    And now to the last project but not for while
  </div>
  <div class="blockk text-white flex justify-center text-4xl pt-96">
    <a href=" https://red-badr.netlify.app/">
      <!-- svelte-ignore a11y-img-redundant-alt -->
      <img
        src="das.png"
        alt="photo  "
        class=" object-cover h-[20rem] md:h-[40rem]"
      /></a
    >
    <!-- svelte-ignore a11y-img-redundant-alt -->
  </div>
  <div class="blockk text-white flex justify-center text-4xl pt-96">
    My first personal website
  </div>
  <div class="blockk text-white flex justify-center text-4xl mb-36 pt-96">
    I don't want to be a narcissist, but this is the best personal website
  </div>

  <div class="blockk text-white flex justify-center py-96 text-4xl">
    In the end, I hope you liked my site and thanks.
  </div>
</div>
