<script lang="ts">
  const stats = [
    {
      label: "100+ Media Outlets",
      desc: "We maintain direct relationships with editors and journalists at major publications including Bloomberg, Forbes, Entrepreneur, TechCrunch, Wired, Inc, Fast Company, Yahoo Finance, Business Insider, MarketWatch, Cointelegraph, and many more. Our network is your advantage.",
      img: "/generated/image-professional-pr-team-strategizing-in-mod-1765569145726-0.webp"
    },
    {
      label: "Industry Recognition",
      desc: "Best PR Firm in Las Vegas by Expertise. Top PR Firm by Mirror Agency. Member of Rolling Stone Culture Council and Forbes Agency Council. Our work and reputation speak for themselves.",
      img: "/generated/image-pr-team-celebrating-success-high-fiving--1765569151497-2.webp"
    },
    {
      label: "3-4 Opportunities/Month",
      desc: "Average 3-4 media opportunities per month including articles, placements, press releases, TV appearances, podcasts, and interviews. Press releases achieve average of 100 placements across networks including Yahoo Finance, NBC, CBS, FOX, and 100 additional syndications.",
      img: "/generated/image-media-interview-setup-with-cameras-and-l-1765569166610-8.webp"
    },
    {
      label: "$10K-$12K/Month",
      desc: "Transparent pricing with no hidden fees. Month-to-month at $12,000/month or 6-month commitment at $10,000/month (saves $12,000 total). Compared to competitors, we deliver 3x more coverage volume with guaranteed weekly press coverage vs sporadic quarterly coverage.",
      img: "/generated/image-business-professional-reviewing-analytic-1765569169231-9.webp"
    }
  ];
</script>

<section class="py-24 px-6 md:px-12 bg-white border-t border-gray-100">
  <div class="mb-16">
    <p class="text-gray-500 max-w-xl">
      The numbers that matter. Here's what sets Victorious PR apart in the competitive landscape of AI and blockchain public relations.
    </p>
  </div>

  <div class="space-y-16">
    {#each stats as stat}
      <div class="flex flex-col md:flex-row md:items-start justify-between gap-8 border-b border-gray-100 pb-16 last:border-0">
        <h3 class="text-2xl md:text-4xl font-medium w-full md:w-1/3">{stat.label}</h3>
        <div class="w-full md:w-1/3">
           <p class="text-xs leading-relaxed text-gray-500">{stat.desc}</p>
        </div>
        <div class="w-full md:w-1/6 flex justify-end">
           <img src={stat.img} alt={stat.label} class="w-20 h-20 object-cover rounded bg-gray-100" />
        </div>
      </div>
    {/each}
  </div>
</section>
