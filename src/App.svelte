<script>
  import { Feature } from '@components';
  import { iconCalculator, iconKarma, iconSupervisor, iconTeamBuilder } from '@assets';
</script>

<main class="max-w-xs mx-auto my-22 | grid gap-20 | md:max-w-2xl lg:max-w-4xl xl:max-w-6xl">
  <section class="max-w-lg mx-auto | grid gap-4 | text-center">
    <h1 class="grid | text-2xl leading-normal | md:text-3xl">
      <span class="font-extralight"> Reliable, efficient delivery </span>
      <span class="text-neutral-700 font-bold"> Powered by Technology </span>
    </h1>
    <p>
      Our Artificial Intelligence powered tools use millions of project data points to ensure that
      your project is successful
    </p>
  </section>
  <section class="grid gap-8 | md:grid-cols-2 lg:(grid-cols-3 items-center)">
    <h2 class="sr-only">Features</h2>
    <Feature border="border-top-cyan" title="Supervisor" icon={iconSupervisor}>
      Monitors activity to identify project roadblocks
    </Feature>
    <div class="contents lg:(grid gap-8)">
      <Feature border="border-top-red" title="Team Builder" icon={iconTeamBuilder}>
        Scans our talent network to create the optimal team for your project
      </Feature>
      <Feature border="border-top-orange" title="Karma" icon={iconKarma}>
        Regularly evaluates our talent to ensure quality
      </Feature>
    </div>
    <Feature border="border-top-blue" title="Calculator" icon={iconCalculator}>
      Uses data from past projects to provide better delivery estimates
    </Feature>
  </section>
</main>
