<script lang="ts">
  const photos = [
    {
      title: "Expert Content Creation",
      desc: "Our team of seasoned journalists crafts compelling press releases, pitch emails, and articles that translate complex AI and blockchain innovations into stories editors want to publish.",
      img: "/generated/image-pr-professional-writing-press-release-on-1765569164113-7.webp"
    },
    {
      title: "Guaranteed Media Placements",
      desc: "We don't just promise coverage—we deliver guaranteed weekly press coverage with 3-4 media opportunities per month including TV appearances, podcasts, and top-tier publications.",
      img: "/generated/image-media-interview-setup-with-cameras-and-l-1765569166610-8.webp"
    },
    {
      title: "Data-Driven Results",
      desc: "Monthly PR strategy calls with dedicated publicists ensure real-time campaign adjustments. We track performance and optimize based on your business developments and market dynamics.",
      img: "/generated/image-business-professional-reviewing-analytic-1765569169231-9.webp"
    }
  ];
</script>

<section class="py-24 px-6 md:px-12 bg-white">
  <div class="max-w-xl mb-16">
    <h3 class="text-lg font-bold mb-2">Specialized expertise in AI and blockchain PR.</h3>
    <p class="text-gray-500 text-sm leading-relaxed">
      We exclusively focus on AI and blockchain companies, bringing deep understanding of complex, rapidly-evolving technologies. Our journalistic background enables us to position your innovations within larger media narratives that resonate with both technical and mainstream audiences.
    </p>
  </div>

  <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
    {#each photos as photo}
      <div>
        <div class="aspect-[3/4] rounded-lg overflow-hidden mb-4 bg-gray-100">
          <img src={photo.img} alt={photo.title} class="w-full h-full object-cover" />
        </div>
        <h4 class="text-xs font-bold mb-1">{photo.title}</h4>
        <p class="text-[10px] text-gray-500 leading-relaxed">{photo.desc}</p>
      </div>
    {/each}
  </div>
</section>
