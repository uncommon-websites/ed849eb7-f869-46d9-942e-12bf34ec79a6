<script lang="ts">
  const cards = [
    {
      title: "We're Not Just Publicists...",
      subtitle: "We're Seasoned Journalists.",
      image: "/generated/image-professional-journalist-or-editor-workin-1765569153949-3.webp"
    },
    {
      title: "We Don't Promise Coverage...",
      subtitle: "We Guarantee It Weekly.",
      image: "/generated/image-confident-pr-professional-on-phone-call--1765569148859-1.webp"
    },
    {
      title: "We Don't Just Send Pitches...",
      subtitle: "We Leverage Direct Relationships.",
      image: "/generated/image-pr-team-celebrating-success-high-fiving--1765569151497-2.webp"
    }
  ];
</script>

<section class="py-24 px-6 md:px-12 bg-white">
  <div class="max-w-2xl mb-16">
    <p class="text-xl md:text-2xl leading-relaxed text-gray-800">
      Our team comprises seasoned journalists who bring narrative mastery and direct media relationships. This journalistic insight enables us to identify what's newsworthy and position your story within larger media narratives that editors care about.
    </p>
  </div>

  <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
    {#each cards as card}
      <div class="group">
        <div class="aspect-[4/3] overflow-hidden rounded-lg mb-4 bg-gray-100">
          <img src={card.image} alt={card.title} class="w-full h-full object-cover grayscale group-hover:grayscale-0 transition-all duration-500" />
        </div>
        <h3 class="text-sm text-gray-500 mb-1">{card.title}</h3>
        <p class="text-sm font-bold">{card.subtitle}</p>
        
        <div class="flex justify-between mt-4 text-xs text-gray-400">
           <span>01</span>
           <span>-></span>
        </div>
      </div>
    {/each}
  </div>
</section>
