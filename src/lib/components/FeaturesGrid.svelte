<script>
    // Icons replaced with CSS shapes for pixel-perfect custom visuals
</script>

<section class="py-24 bg-white">
    <div class="mx-auto max-w-7xl px-4 sm:px-6 lg:px-8">
        <div class="mb-16">
            <h2 class="text-4xl md:text-5xl font-serif text-gray-900 leading-tight">
                Built for Fractional CFOs<br />Managing Multiple Clients
            </h2>
        </div>

        <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
            <!-- Multi-Client Dashboard -->
            <div class="bg-gray-50 p-8 rounded-lg flex flex-col h-full">
                <h3 class="text-lg font-serif text-gray-900 mb-8">Multi-Client Dashboard</h3>
                <div class="flex-1 flex items-center justify-center mb-8">
                    <div class="grid grid-cols-3 gap-4">
                        {#each [1, 2, 3, 4, 5, 6] as i}
                            <div class="h-10 w-10 bg-white rounded-full shadow-sm flex items-center justify-center text-primary-600 font-bold text-xs">
                                {i}
                            </div>
                        {/each}
                    </div>
                </div>
                <p class="text-xs text-gray-500 leading-relaxed mt-auto">
                    Manage all your clients from a single dashboard. Switch between accounts instantly and get a bird's-eye view of every client's financial health.
                </p>
            </div>

            <!-- Report Templates -->
            <div class="bg-gray-50 p-8 rounded-lg flex flex-col h-full">
                <h3 class="text-lg font-serif text-gray-900 mb-8">Report Templates</h3>
                <div class="flex-1 flex items-center justify-center mb-8">
                    <div class="bg-white p-4 rounded shadow-sm w-full max-w-[200px] space-y-2">
                        <div class="h-2 bg-primary-200 rounded w-1/3 mb-4"></div>
                        {#each [1, 2, 3, 4, 5] as i}
                            <div class="flex items-center gap-2">
                                <div class="h-2 w-2 rounded-full bg-primary-300"></div>
                                <div class="h-1.5 bg-gray-100 rounded w-3/4"></div>
                            </div>
                        {/each}
                    </div>
                </div>
                <p class="text-xs text-gray-500 leading-relaxed mt-auto">
                    Pre-built financial report templates for P&L, cash flow, balance sheets, and forecasts. Customize to match your brand and client needs.
                </p>
            </div>

            <!-- Expert Support -->
            <div class="bg-gray-50 p-8 rounded-lg flex flex-col h-full">
                <h3 class="text-lg font-serif text-gray-900 mb-8">Expert Support</h3>
                <div class="flex-1 flex items-center justify-center mb-8">
                    <div class="flex -space-x-2">
                        <div class="h-10 w-10 rounded-full bg-primary-100 border-2 border-white flex items-center justify-center text-primary-600 text-xs">A</div>
                        <div class="h-10 w-10 rounded-full bg-primary-100 border-2 border-white flex items-center justify-center text-primary-600 text-xs">B</div>
                        <div class="h-10 w-10 rounded-full bg-primary-100 border-2 border-white flex items-center justify-center text-primary-600 text-xs">C</div>
                    </div>
                </div>
                <p class="text-xs text-gray-500 leading-relaxed mt-auto">
                    Dedicated onboarding and ongoing support from financial operations experts who understand fractional CFO workflows.
                </p>
            </div>

            <!-- Automated Insights -->
            <div class="bg-gray-50 p-8 rounded-lg flex flex-col h-full">
                <h3 class="text-lg font-serif text-gray-900 mb-8">Automated Insights</h3>
                <div class="flex-1 flex items-center justify-center mb-8">
                    <div class="relative">
                        <!-- Tree structure visualization -->
                        <div class="flex justify-center gap-4 mb-4">
                            <div class="h-6 w-6 border border-primary-300 bg-white rounded-sm"></div>
                            <div class="h-6 w-6 border border-primary-300 bg-white rounded-sm"></div>
                            <div class="h-6 w-6 border border-primary-300 bg-white rounded-sm"></div>
                        </div>
                        <div class="flex justify-center mb-4">
                            <div class="h-8 w-px bg-primary-300"></div>
                        </div>
                        <div class="flex justify-center">
                            <div class="h-8 w-8 bg-primary-600 rounded flex items-center justify-center text-white text-xs">AI</div>
                        </div>
                    </div>
                </div>
                <p class="text-xs text-gray-500 leading-relaxed mt-auto">
                    Smart alerts for cash flow issues, unusual transactions, and forecast variances. Stay ahead of problems before they impact your clients.
                </p>
            </div>

            <!-- Client Collaboration -->
            <div class="bg-gray-50 p-8 rounded-lg flex flex-col h-full">
                <h3 class="text-lg font-serif text-gray-900 mb-8">Client Collaboration</h3>
                <div class="flex-1 flex items-center justify-center mb-8">
                    <div class="bg-white p-4 rounded shadow-sm w-full max-w-[200px]">
                        <div class="flex justify-between mb-4">
                            <div class="text-[10px] font-bold text-primary-600">SHARED</div>
                            <div class="text-[10px] font-bold text-gray-400">VIEW</div>
                        </div>
                        <div class="space-y-2">
                            <div class="h-px bg-gray-100 w-full"></div>
                            <div class="h-1.5 bg-primary-100 rounded w-1/2"></div>
                            <div class="h-1.5 bg-primary-100 rounded w-3/4"></div>
                            <div class="h-1.5 bg-primary-100 rounded w-2/3"></div>
                        </div>
                    </div>
                </div>
                <p class="text-xs text-gray-500 leading-relaxed mt-auto">
                    Share reports and dashboards directly with clients. Control access levels and keep everyone on the same page with real-time financial data.
                </p>
            </div>

            <!-- Bank-Level Security -->
            <div class="bg-gray-50 p-8 rounded-lg flex flex-col h-full">
                <h3 class="text-lg font-serif text-gray-900 mb-8">Bank-Level Security</h3>
                <div class="flex-1 flex items-center justify-center mb-8">
                    <div class="grid grid-cols-3 gap-1">
                        {#each [1, 2, 3, 4, 5, 6, 7, 8, 9] as i}
                            <div class={`h-8 w-8 border border-gray-200 ${i === 5 ? 'bg-primary-600 flex items-center justify-center' : 'bg-white'}`}>
                                {#if i === 5}
                                    <div class="h-2 w-2 bg-white rounded-full"></div>
                                {/if}
                            </div>
                        {/each}
                    </div>
                </div>
                <p class="text-xs text-gray-500 leading-relaxed mt-auto">
                    256-bit encryption, SOC 2 compliance, and secure data storage. Your client data is protected with the same security standards as major financial institutions.
                </p>
            </div>
        </div>
    </div>
</section>
