<script>
  const logos = [
    { name: "Datadog", font: "font-sans font-bold" },
    { name: "PAGERDUTY", font: "font-mono font-bold tracking-widest" },
    { name: "Atlassian", font: "font-sans font-bold" },
    { name: "Zendesk", font: "font-sans font-bold text-xl" },
    { name: "Okta", font: "font-sans font-bold" },
    { name: "Splunk", font: "font-sans font-bold" },
    { name: "SLACK", font: "font-sans font-light uppercase tracking-widest" },
    { name: "Microsoft", font: "font-sans font-bold tracking-tight" },
    { name: "Salesforce", font: "font-sans font-bold" },
    { name: "Zoom", font: "font-sans font-black tracking-tighter" },
    { name: "Cisco", font: "font-sans font-bold" },
    { name: "VMware", font: "font-sans font-bold" },
  ];
</script>

<section class="py-16 border-b border-gray-100">
  <div class="container-custom text-center">
    <p class="text-[10px] font-bold tracking-[0.2em] text-gray-400 uppercase mb-10">
      Trusted by IT teams at mid-market enterprises
    </p>
    
    <div class="grid grid-cols-2 md:grid-cols-4 lg:grid-cols-6 gap-x-8 gap-y-12 items-center justify-items-center opacity-60 grayscale hover:grayscale-0 transition-all duration-500">
      {#each logos as logo}
        <div class="text-xl md:text-2xl text-gray-800 flex items-center justify-center w-full">
           <!-- Placeholder for actual SVG logos -->
           <span class="{logo.font}">{logo.name}</span>
        </div>
      {/each}
    </div>
  </div>
</section>
