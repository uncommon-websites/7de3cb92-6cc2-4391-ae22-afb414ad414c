<section class="py-12 bg-ravenna-dark">
  <div class="container-custom">
    <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
      
      <!-- Card 1 -->
      <div class="bg-ravenna-dark-secondary rounded-2xl p-8 border border-gray-800 hover:border-gray-700 transition-colors group">
        <div class="h-40 mb-8 flex items-center justify-center relative">
            <!-- Icons Grid -->
            <div class="grid grid-cols-4 gap-3 opacity-60 group-hover:opacity-100 transition-opacity">
                {#each Array(8) as _}
                <div class="w-8 h-8 rounded bg-gray-800 border border-gray-700"></div>
                {/each}
            </div>
        </div>
        <h3 class="text-xl font-bold text-white mb-3">Unify IT tools</h3>
        <p class="text-gray-400 text-sm leading-relaxed">
          Connect ServiceNow, Jira, Slack, Microsoft Teams, email, and your entire IT stack into one intelligent orchestration platform.
        </p>
      </div>

      <!-- Card 2 -->
      <div class="bg-ravenna-dark-secondary rounded-2xl p-8 border border-gray-800 hover:border-gray-700 transition-colors group">
        <div class="h-40 mb-8 flex items-end justify-center gap-1 pb-4">
            <!-- Bar Chart -->
            <div class="w-3 bg-primary-900/40 h-12 rounded-t"></div>
            <div class="w-3 bg-primary-800/60 h-16 rounded-t"></div>
            <div class="w-3 bg-primary-700/80 h-10 rounded-t"></div>
            <div class="w-3 bg-primary-600 h-24 rounded-t"></div>
            <div class="w-3 bg-primary-500 h-20 rounded-t"></div>
            <div class="w-3 bg-primary-400 h-28 rounded-t shadow-[0_0_15px_rgba(74,222,128,0.5)]"></div>
            <div class="w-3 bg-primary-500 h-14 rounded-t"></div>
            <div class="w-3 bg-primary-600 h-18 rounded-t"></div>
            
            <!-- Tooltip-like badge -->
            <div class="absolute top-10 bg-white text-black text-[10px] font-bold px-2 py-1 rounded shadow-lg transform translate-x-4">
                Resolution time ↓
            </div>
        </div>
        <h3 class="text-xl font-bold text-white mb-3">Gain IT insights</h3>
        <p class="text-gray-400 text-sm leading-relaxed">
          Track service metrics, identify bottlenecks, and optimize IT operations with automated analytics and real-time dashboards.
        </p>
      </div>

      <!-- Card 3 -->
      <div class="bg-ravenna-dark-secondary rounded-2xl p-8 border border-gray-800 hover:border-gray-700 transition-colors group">
        <div class="h-40 mb-8 flex flex-col items-center justify-center gap-3">
             <div class="flex gap-2">
                 <div class="px-3 py-1 bg-primary text-white text-xs rounded font-medium">Auto-route ticket</div>
                 <div class="px-3 py-1 bg-primary/20 text-primary-300 border border-primary/30 text-xs rounded font-medium">Find solution</div>
             </div>
             <div class="flex gap-2">
                 <div class="px-3 py-1 bg-primary/20 text-primary-300 border border-primary/30 text-xs rounded font-medium">Escalate priority</div>
                 <div class="px-3 py-1 bg-primary/20 text-primary-300 border border-primary/30 text-xs rounded font-medium">Update status</div>
             </div>
        </div>
        <h3 class="text-xl font-bold text-white mb-3">Empower IT teams</h3>
        <p class="text-gray-400 text-sm leading-relaxed">
          AI-powered automation handles routing, prioritization, and resolution suggestions so your IT team can focus on complex issues.
        </p>
      </div>

    </div>
  </div>
</section>
