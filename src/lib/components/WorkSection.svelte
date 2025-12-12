<script lang="ts">
  const projects = [
    {
      client: "Vetter Ecosystem",
      desc: "Presale sold out in 3 minutes. Grew Telegram from 0 to 18,000 members in 2 weeks. 8-figure presale launch.",
      bg: "bg-black",
      img: "/generated/image-blockchain-startup-founder-presenting-at-1765569156533-4.webp",
      dark: true
    },
    {
      client: "Christian Santiago",
      desc: "93% website traffic increase in first 2 weeks through strategic media placements.",
      bg: "bg-gray-100",
      img: "/generated/image-ai-technology-company-office-space-moder-1765569159086-5.webp",
      dark: false
    },
    {
      client: "Lanette Pinkard",
      desc: "Waiting list grew from 15-20 to 90 people. Secured multi-billion dollar company as first sponsor.",
      bg: "bg-gray-900",
      img: "",
      dark: true
    },
    {
      client: "Galen M. Hair",
      desc: "Substantial business growth with clients citing media appearances as reason for contact.",
      bg: "bg-gray-100",
      img: "",
      dark: false
    }
  ];
</script>

<section class="px-6 md:px-12 py-24 bg-white">
  <div class="max-w-3xl mb-16">
    <h2 class="text-2xl md:text-3xl font-medium leading-tight">
      <span class="font-bold">We secure guaranteed weekly press coverage</span> for AI and blockchain companies, delivering 3-4 media opportunities per month including articles, TV appearances, podcasts, and interviews.
    </h2>
  </div>

  <div class="grid grid-cols-1 md:grid-cols-2 gap-x-6 gap-y-12">
    {#each projects as project}
      <div class="group cursor-pointer">
        <div class={`aspect-[4/3] w-full rounded-lg overflow-hidden relative ${project.bg} mb-4`}>
          {#if project.img}
             <img src={project.img} alt={project.client} class="w-full h-full object-cover transition-transform duration-500 group-hover:scale-105" />
          {:else}
             <!-- Placeholder for case studies on solid bg -->
             <div class="w-full h-full flex items-center justify-center p-8">
                <span class={`text-xl font-bold text-center ${project.dark ? 'text-white' : 'text-black'}`}>{project.client}</span>
             </div>
          {/if}
        </div>
        <h3 class="text-sm font-bold mb-1">{project.client}</h3>
        <p class="text-sm text-gray-600">{project.desc}</p>
      </div>
    {/each}
  </div>
</section>
