<script>
  // No imports needed as we use inline SVGs for specific styling control
</script>

<section class="relative flex flex-col items-center justify-start pt-20 pb-32 overflow-hidden">
  <!-- Content -->
  <div class="z-10 mx-auto max-w-4xl px-4 text-center mb-16">
    <h1 class="mb-6 text-5xl md:text-6xl lg:text-7xl font-serif text-gray-900 leading-tight">
      Financial Reporting That Works as Hard as You Do
    </h1>
    <p class="mx-auto mb-10 max-w-2xl text-lg text-gray-600 leading-relaxed">
      Unify accounting, forecasting, and reporting for all your clients. Automated QuickBooks integration and real-time dashboards reduce manual work by 70%.
    </p>
    
    <div class="flex justify-center">
        <div class="relative group">
            <button class="relative rounded-full bg-black px-8 py-3 text-base font-medium text-white hover:bg-gray-800 transition-all">
                Get Started Free
            </button>
            <!-- Decorative corners -->
            <div class="absolute -top-2 -left-2 h-4 w-4 border-t-2 border-l-2 border-black"></div>
            <div class="absolute -bottom-2 -right-2 h-4 w-4 border-b-2 border-r-2 border-black"></div>
        </div>
    </div>
  </div>

  <!-- Hero Image - Dashboard Preview -->
  <div class="relative w-full max-w-7xl mx-auto px-4">
    <div class="relative aspect-[21/9] w-full overflow-hidden rounded-lg shadow-2xl bg-gradient-to-br from-gray-50 to-gray-100">
      <img 
        src="/generated/image-modern-financial-dashboard-on-computer-s-1765561250591-0.webp" 
        alt="Financial Dashboard" 
        class="h-full w-full object-cover"
      />
      
      <!-- Overlay Dashboard Stats -->
      <div class="absolute inset-0 flex items-center justify-center bg-black/5">
        <div class="w-full max-w-4xl grid grid-cols-3 gap-4 px-8 animate-fade-in-up">
            <div class="rounded-xl bg-white p-6 shadow-xl">
                <div class="text-xs font-medium text-gray-500 mb-2">MONTHLY REPORTS</div>
                <div class="text-3xl font-bold text-gray-900">12</div>
                <div class="text-xs text-primary-600 mt-2">↑ Automated</div>
            </div>
            <div class="rounded-xl bg-white p-6 shadow-xl">
                <div class="text-xs font-medium text-gray-500 mb-2">TIME SAVED</div>
                <div class="text-3xl font-bold text-gray-900">70%</div>
                <div class="text-xs text-primary-600 mt-2">↓ Manual work</div>
            </div>
            <div class="rounded-xl bg-white p-6 shadow-xl">
                <div class="text-xs font-medium text-gray-500 mb-2">ACTIVE CLIENTS</div>
                <div class="text-3xl font-bold text-gray-900">24</div>
                <div class="text-xs text-primary-600 mt-2">↑ Synced</div>
            </div>
        </div>
      </div>
    </div>
  </div>
</section>

<style>
    .animate-fade-in-up {
        animation: fadeInUp 0.8s ease-out forwards;
    }
    @keyframes fadeInUp {
        from { opacity: 0; transform: translateY(20px); }
        to { opacity: 1; transform: translateY(0); }
    }
</style>
