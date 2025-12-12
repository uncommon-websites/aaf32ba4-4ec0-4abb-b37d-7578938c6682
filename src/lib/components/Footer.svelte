<script>
    const currentYear = new Date().getFullYear();
</script>

<footer class="bg-white pt-24 pb-12">
    <div class="mx-auto max-w-7xl px-4 sm:px-6 lg:px-8">
        <!-- Top Section -->
        <div class="flex flex-col md:flex-row justify-between items-start mb-24 gap-12">
            <div class="max-w-xl">
                <div class="mb-8">
                    <!-- Logo mark -->
                     <svg width="32" height="32" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <path d="M4 4H10V10H4V4Z" stroke="black" stroke-width="2"/>
                        <path d="M14 14H20V20H14V14Z" stroke="black" stroke-width="2"/>
                    </svg>
                </div>
                <h2 class="text-4xl md:text-5xl font-serif text-gray-900 leading-tight">
                    Start Automating Your<br />Client Reporting Today
                </h2>
            </div>
            <div>
                <a href="#demo" class="rounded-full bg-black px-6 py-3 text-sm font-medium text-white hover:bg-gray-800 transition-colors inline-block">
                    Get Started Free
                </a>
            </div>
        </div>

        <!-- Links Grid -->
        <div class="grid grid-cols-2 md:grid-cols-4 gap-8 mb-24 border-t border-gray-100 pt-16">
            <div>
                <h4 class="text-[10px] font-mono uppercase tracking-widest text-gray-500 mb-6">Overview</h4>
                <ul class="space-y-4">
                    <li><a href="#product" class="text-xs text-gray-600 hover:text-gray-900">Product</a></li>
                    <li><a href="#features" class="text-xs text-gray-600 hover:text-gray-900">Features</a></li>
                    <li><a href="#security" class="text-xs text-gray-600 hover:text-gray-900">Security</a></li>
                </ul>
            </div>
            <div>
                <h4 class="text-[10px] font-mono uppercase tracking-widest text-gray-500 mb-6">Company</h4>
                <ul class="space-y-4">
                    <li><a href="#about" class="text-xs text-gray-600 hover:text-gray-900">About</a></li>
                    <li><a href="#careers" class="text-xs text-gray-600 hover:text-gray-900">Careers</a></li>
                </ul>
            </div>
            <div>
                <h4 class="text-[10px] font-mono uppercase tracking-widest text-gray-500 mb-6">Legal</h4>
                <ul class="space-y-4">
                    <li><a href="#terms" class="text-xs text-gray-600 hover:text-gray-900">Terms of Use</a></li>
                    <li><a href="#privacy" class="text-xs text-gray-600 hover:text-gray-900">Privacy Policy</a></li>
                </ul>
            </div>
            <div>
                <h4 class="text-[10px] font-mono uppercase tracking-widest text-gray-500 mb-6">Contact</h4>
                <ul class="space-y-4">
                    <li><a href="#demo" class="text-xs text-gray-600 hover:text-gray-900">Get Started</a></li>
                    <li><a href="#support" class="text-xs text-gray-600 hover:text-gray-900">Support</a></li>
                    <li><a href="#linkedin" class="text-xs text-gray-600 hover:text-gray-900">LinkedIn</a></li>
                    <li><a href="mailto:hello@kordis.com" class="text-xs text-gray-600 hover:text-gray-900">Email Us</a></li>
                </ul>
            </div>
        </div>

        <!-- Copyright -->
        <div class="text-center border-t border-gray-100 pt-8">
            <p class="text-[10px] font-mono uppercase tracking-widest text-gray-400">
                © {currentYear} Kordis
            </p>
        </div>
    </div>
</footer>
