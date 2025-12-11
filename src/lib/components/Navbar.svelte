<script>
  import { onMount } from 'svelte';
  
  let isScrolled = false;

  onMount(() => {
    const handleScroll = () => {
      isScrolled = window.scrollY > 10;
    };
    window.addEventListener('scroll', handleScroll);
    return () => window.removeEventListener('scroll', handleScroll);
  });
</script>

<nav class="fixed top-0 left-0 right-0 z-50 transition-all duration-300 {isScrolled ? 'bg-white/90 backdrop-blur-md border-b border-gray-100 py-3' : 'bg-transparent py-5'}">
  <div class="container-custom flex items-center justify-between">
    <div class="flex items-center gap-8">
      <a href="/" class="flex items-center gap-2 text-xl font-bold tracking-tight text-gray-900">
        <!-- Ravenna Logo -->
        <svg width="24" height="24" viewBox="0 0 93 92" fill="none" xmlns="http://www.w3.org/2000/svg">
          <path fill-rule="evenodd" clip-rule="evenodd" d="M46.2451 17.9688C36.2169 17.9688 28.0872 9.92388 28.0872 0H15.982C15.982 16.5399 29.5311 29.9479 46.2451 29.9479C62.9591 29.9479 76.5083 16.5399 76.5083 0H64.403C64.403 9.92388 56.2734 17.9688 46.2451 17.9688ZM28.0872 91.0417C28.0872 81.1179 36.2169 73.0729 46.2451 73.0729C56.2734 73.0729 64.403 81.1179 64.403 91.0417H76.5083C76.5083 74.5018 62.9591 61.0937 46.2451 61.0937C29.5311 61.0937 15.982 74.5018 15.982 91.0417H28.0872ZM18.403 45.5208C18.403 35.597 10.2735 27.5521 0.245117 27.5521V15.5729C16.959 15.5729 30.5083 28.981 30.5083 45.5208C30.5083 62.0607 16.959 75.4688 0.245117 75.4688V63.4896C10.2735 63.4896 18.403 55.4446 18.403 45.5208ZM74.0872 45.5208C74.0872 35.597 82.2169 27.5521 92.2451 27.5521V15.5729C75.5311 15.5729 61.982 28.981 61.982 45.5208C61.982 62.0607 75.5311 75.4688 92.2451 75.4688V63.4896C82.2169 63.4896 74.0872 55.4446 74.0872 45.5208Z" fill="#0A0D12"/>
        </svg>
        Ravenna
      </a>
      
      <div class="hidden md:flex items-center gap-6 text-sm font-medium text-gray-600">
        <a href="#" class="hover:text-gray-900 transition-colors">Platform <span class="text-xs ml-0.5">▼</span></a>
        <a href="#" class="hover:text-gray-900 transition-colors">Solutions <span class="text-xs ml-0.5">▼</span></a>
        <a href="#" class="hover:text-gray-900 transition-colors">Resources <span class="text-xs ml-0.5">▼</span></a>
        <a href="#" class="hover:text-gray-900 transition-colors">Pricing</a>
        <a href="#" class="hover:text-gray-900 transition-colors">Customers</a>
      </div>
    </div>

    <div class="flex items-center gap-3">
      <a href="#" class="px-3 py-1.5 text-xs font-semibold border border-gray-200 rounded text-gray-700 hover:border-gray-400 transition-colors uppercase tracking-wide">
        Sign In
      </a>
      <a href="#" class="px-3 py-1.5 text-xs font-semibold bg-primary text-white rounded hover:bg-primary-dark transition-colors uppercase tracking-wide">
        Request Demo
      </a>
    </div>
  </div>
</nav>
