<script>
    const partners = [
        { name: "QuickBooks Online", icon: "Q", color: "bg-green-600" },
        { name: "QuickBooks Desktop", icon: "Q", color: "bg-green-700" },
        { name: "Excel & CSV", icon: "📊" },
        { name: "Google Sheets", icon: "G", color: "bg-green-500" },
        { name: "Xero", icon: "X", color: "bg-blue-500" },
        { name: "Stripe", icon: "S", color: "bg-purple-600" },
        { name: "PayPal", icon: "P", color: "bg-blue-600" },
        { name: "Bank Feeds", icon: "🏦" },
        { name: "Custom API", icon: "⚡" }
    ];
</script>

<section class="py-24 bg-white">
    <div class="mx-auto max-w-7xl px-4 sm:px-6 lg:px-8">
        <div class="mb-16 max-w-2xl">
            <h2 class="text-3xl md:text-4xl font-serif text-gray-900 mb-6">Seamless Integrations</h2>
            <p class="text-sm text-gray-500 leading-relaxed">
                Connect with the tools you already use. Kordis integrates directly with QuickBooks and other popular accounting platforms, automatically syncing your client data in real-time for effortless financial management.
            </p>
        </div>

        <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-4">
            {#each partners as partner}
                <div class="flex items-center gap-4 p-4 bg-gray-50 rounded-lg hover:bg-gray-100 transition-colors cursor-default">
                    <div class={`h-8 w-8 rounded flex items-center justify-center text-white text-xs font-bold ${partner.color ? partner.color : 'bg-gray-200 text-gray-600'}`}>
                        {partner.icon}
                    </div>
                    <span class="text-sm font-medium text-gray-900">{partner.name}</span>
                </div>
            {/each}
        </div>
    </div>
</section>
