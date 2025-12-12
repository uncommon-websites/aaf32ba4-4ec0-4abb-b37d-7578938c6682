<script>
    import { FileText, Database, Settings, Search } from 'lucide-svelte';
</script>

<section class="py-24 bg-white">
    <div class="mx-auto max-w-7xl px-4 sm:px-6 lg:px-8">
        <div class="mb-20">
            <h2 class="text-4xl md:text-5xl font-serif text-gray-900 leading-tight max-w-4xl">
                From spreadsheet chaos to automated clarity. <span class="font-semibold">Kordis transforms how fractional CFOs manage their clients.</span>
            </h2>
        </div>

        <div class="grid grid-cols-1 lg:grid-cols-2 gap-16 items-center">
            <!-- Left: Image/Interface -->
            <div class="relative">
                <div class="relative rounded-lg overflow-hidden shadow-2xl bg-primary-950 aspect-[4/3]">
                    <img 
                        src="/generated/image-confident-financial-professional-at-thei-1765561360647-0.webp" 
                        alt="Financial professional working" 
                        class="absolute inset-0 w-full h-full object-cover opacity-30 mix-blend-overlay"
                    />
                    
                    <!-- Floating Interface Element -->
                    <div class="absolute inset-0 flex items-center justify-center p-8">
                        <div class="bg-white rounded-lg shadow-xl w-full max-w-md p-6">
                            <div class="flex items-center gap-3 mb-4">
                                <div class="h-8 w-8 bg-primary-600 rounded flex items-center justify-center text-white">
                                    <Database size={16} />
                                </div>
                                <span class="font-medium text-gray-900">QuickBooks Sync</span>
                            </div>
                            <div class="space-y-2">
                                <div class="h-2 bg-primary-100 rounded w-3/4"></div>
                                <div class="h-2 bg-primary-100 rounded w-1/2"></div>
                            </div>
                            
                            <!-- Arrow indicator -->
                            <div class="absolute left-4 top-1/2 -translate-y-1/2 bg-white rounded-full p-2 shadow-lg">
                                <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="m9 18 6-6-6-6"/></svg>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

            <!-- Right: Features List -->
            <div class="space-y-12">
                <h3 class="text-2xl font-serif text-gray-900">
                    One Platform for All Your<br/>Client Financial Operations
                </h3>

                <div class="space-y-8">
                    {#each [
                        { id: '01', title: 'Unified client dashboard', icon: Database },
                        { id: '02', title: 'Automated QuickBooks sync', icon: Search },
                        { id: '03', title: 'Real-time forecasting', icon: Settings },
                        { id: '04', title: 'One-click reporting', icon: FileText }
                    ] as feature}
                        <div class="flex items-start gap-4 group cursor-pointer">
                            <div class="flex-shrink-0 relative">
                                <div class="h-10 w-10 rounded-full border border-gray-200 flex items-center justify-center text-xs font-mono text-gray-500 group-hover:border-primary-600 group-hover:text-primary-600 transition-colors bg-white z-10 relative">
                                    {feature.id}
                                </div>
                                {#if feature.id !== '04'}
                                    <div class="absolute top-10 left-1/2 -translate-x-1/2 w-px h-8 bg-gray-100 -z-0"></div>
                                {/if}
                            </div>
                            <div class="pt-2">
                                <h4 class="text-lg text-gray-600 group-hover:text-gray-900 transition-colors font-light">
                                    {feature.title}
                                </h4>
                            </div>
                        </div>
                    {/each}
                </div>
            </div>
        </div>
    </div>
</section>
