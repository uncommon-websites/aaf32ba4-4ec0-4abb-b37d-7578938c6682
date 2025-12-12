<script>
    import { Check, ArrowRight } from 'lucide-svelte';
</script>

<section class="py-24 bg-white">
    <div class="mx-auto max-w-7xl px-4 sm:px-6 lg:px-8">
        <div class="mb-16">
            <h2 class="text-4xl md:text-5xl font-serif text-gray-900 leading-tight">
                Automate Your Client<br />Financial Operations
            </h2>
        </div>

        <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
            <!-- Card 1: Automated Accounting Sync -->
            <div class="group">
                <div class="mb-6 bg-gray-900 rounded-lg p-6 aspect-[4/3] relative overflow-hidden flex flex-col">
                    <!-- Mock Interface -->
                    <div class="bg-white rounded-lg p-4 shadow-lg w-full max-w-[90%] mx-auto mt-auto mb-4 transform translate-y-2 transition-transform group-hover:translate-y-0">
                        <div class="flex items-center gap-2 mb-3 border-b pb-2">
                            <div class="h-2 w-2 rounded-full bg-green-500"></div>
                            <span class="text-[10px] font-mono text-gray-500">QuickBooks Auto-Sync Active</span>
                        </div>
                        <div class="space-y-2">
                            <div class="flex items-center gap-2 text-xs text-green-700">
                                <Check size={12} /> <span class="text-gray-600">Running workflow...</span>
                            </div>
                            <div class="flex items-center gap-2 text-xs pl-4">
                                <span class="h-1 w-1 rounded-full bg-gray-300"></span> <span class="text-gray-400">Syncing transactions</span>
                            </div>
                            <div class="flex items-center gap-2 text-xs pl-4">
                                <span class="h-1 w-1 rounded-full bg-gray-300"></span> <span class="text-gray-400">Updating balances</span>
                            </div>
                            <div class="flex items-center gap-2 text-xs pl-4">
                                <span class="h-1 w-1 rounded-full bg-gray-300"></span> <span class="text-gray-400">Generating reports</span>
                            </div>
                        </div>
                    </div>
                </div>
                <h3 class="text-xl font-serif text-gray-900 mb-3">Automated Accounting Sync</h3>
                <p class="text-sm text-gray-500 leading-relaxed">
                    Connect all your client QuickBooks accounts in minutes. Kordis automatically syncs transactions, balances, and reports in real-time, eliminating manual data entry and reducing errors.
                </p>
            </div>

            <!-- Card 2: Real-Time Forecasting -->
            <div class="group">
                <div class="mb-6 bg-gray-900 rounded-lg p-6 aspect-[4/3] relative overflow-hidden flex flex-col">
                     <!-- Mock Interface -->
                     <div class="bg-white rounded-lg p-4 shadow-lg w-full max-w-[90%] mx-auto mt-auto mb-4 transform translate-y-2 transition-transform group-hover:translate-y-0">
                        <div class="text-[10px] text-gray-500 mb-2">Q4 2024 Revenue Forecast</div>
                        <div class="flex items-center gap-2 mb-3">
                            <div class="h-4 w-4 bg-primary-600 rounded flex items-center justify-center text-white text-[8px]">$</div>
                            <span class="text-[10px] text-gray-400">Updated 2 hours ago</span>
                        </div>
                        <div class="space-y-2 border-t pt-2">
                            <div class="grid grid-cols-3 gap-2 text-[8px] text-gray-400 font-medium">
                                <div>Client</div>
                                <div class="col-span-2 text-right">Projected Revenue</div>
                            </div>
                            <div class="grid grid-cols-3 gap-2 text-[9px] items-center">
                                <div class="flex items-center gap-1"><div class="h-2 w-2 bg-primary-200 rounded-sm"></div> Acme Corp</div>
                                <div class="col-span-2 h-1.5 bg-primary-100 rounded"></div>
                            </div>
                            <div class="grid grid-cols-3 gap-2 text-[9px] items-center">
                                <div class="flex items-center gap-1"><div class="h-2 w-2 bg-primary-200 rounded-sm"></div> Tech Solutions</div>
                                <div class="col-span-2 h-1.5 bg-primary-100 rounded w-2/3 ml-auto"></div>
                            </div>
                            <div class="grid grid-cols-3 gap-2 text-[9px] items-center">
                                <div class="flex items-center gap-1"><div class="h-2 w-2 bg-primary-200 rounded-sm"></div> Retail Plus</div>
                                <div class="col-span-2 h-1.5 bg-primary-100 rounded w-1/2 ml-auto"></div>
                            </div>
                        </div>
                    </div>
                </div>
                <h3 class="text-xl font-serif text-gray-900 mb-3">Real-Time Forecasting</h3>
                <p class="text-sm text-gray-500 leading-relaxed">
                    Build accurate financial forecasts for all your clients with intelligent scenario modeling. Update projections instantly as actuals come in, keeping your clients informed and prepared.
                </p>
            </div>

            <!-- Card 3: One-Click Reporting -->
            <div class="group">
                <div class="mb-6 bg-gray-900 rounded-lg p-6 aspect-[4/3] relative overflow-hidden flex flex-col">
                     <!-- Mock Interface -->
                     <div class="bg-white rounded-lg p-4 shadow-lg w-full max-w-[90%] mx-auto mt-auto mb-4 transform translate-y-2 transition-transform group-hover:translate-y-0">
                        <div class="flex items-center gap-2 mb-3">
                            <div class="h-4 w-4 bg-primary-600 rounded flex items-center justify-center text-white text-[8px]">R</div>
                            <span class="text-[10px] text-gray-500">Generating Reports...</span>
                        </div>
                        <div class="text-[9px] text-gray-600 mb-3 leading-relaxed">
                            Your monthly financial reports are ready. All client data has been automatically populated from QuickBooks.
                        </div>
                        <div class="space-y-2">
                            <div class="flex items-center justify-between p-1.5 bg-gray-50 rounded border border-gray-100">
                                <div class="flex items-center gap-2">
                                    <div class="h-4 w-4 bg-red-500 rounded-sm"></div>
                                    <span class="text-[9px] font-medium">Monthly P&L Report.pdf</span>
                                </div>
                                <ArrowRight size={10} class="text-gray-400" />
                            </div>
                            <div class="flex items-center justify-between p-1.5 bg-gray-50 rounded border border-gray-100">
                                <div class="flex items-center gap-2">
                                    <div class="h-4 w-4 bg-green-600 rounded-sm"></div>
                                    <span class="text-[9px] font-medium">Cash Flow Analysis.xlsx</span>
                                </div>
                                <ArrowRight size={10} class="text-gray-400" />
                            </div>
                        </div>
                    </div>
                </div>
                <h3 class="text-xl font-serif text-gray-900 mb-3">One-Click Reporting</h3>
                <p class="text-sm text-gray-500 leading-relaxed">
                    Generate professional financial reports for all your clients instantly. Customizable templates, automated data population, and export to PDF or Excel with a single click.
                </p>
            </div>
        </div>
    </div>
</section>
