<script lang="ts">
  // Major media outlets where we secure placements
  const mediaLogos = [
    "Bloomberg",
    "Forbes",
    "TechCrunch",
    "Wired",
    "Entrepreneur"
  ];
</script>

<section class="relative min-h-screen flex flex-col justify-end pb-20 px-6 md:px-12 bg-gradient-to-b from-black via-gray-900 to-white text-white">
  <!-- Gradient overlay/background handling -->
  <div class="absolute inset-0 z-[-1] bg-[linear-gradient(180deg,#000_0%,#1a1a1a_30%,#4a4a4a_60%,#fff_100%)]"></div>

  <div class="max-w-4xl mb-32 pt-40">
    <h1 class="text-3xl md:text-5xl font-medium leading-[1.15] tracking-tight">
      Secure Top-Tier Media Placements for Your AI or Blockchain Company. <span class="text-gray-400">Strategic storytelling that builds credibility, attracts investors, and drives adoption through guaranteed weekly press coverage.</span>
    </h1>
  </div>

  <div class="border-t border-gray-600 pt-8 flex flex-wrap gap-8 md:gap-16 items-center opacity-60">
    <div class="text-xs text-gray-400 uppercase tracking-wider">Featured In:</div>
    {#each mediaLogos as logo}
      <div class="h-8 flex items-center justify-center font-bold text-lg text-gray-300">{logo}</div>
    {/each}
    <div class="h-8 flex items-center justify-center font-bold text-lg text-gray-300">Inc</div>
    <div class="h-8 flex items-center justify-center font-bold text-lg text-gray-300">Fast Company</div>
    <div class="h-8 flex items-center justify-center font-bold text-lg text-gray-300">Yahoo Finance</div>
  </div>
</section>
