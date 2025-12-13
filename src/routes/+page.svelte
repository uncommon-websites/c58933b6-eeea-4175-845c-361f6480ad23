<script>
    import Navbar from '$lib/components/Navbar.svelte';
    import Footer from '$lib/components/Footer.svelte';
    import FeatureRow from '$lib/components/FeatureRow.svelte';
</script>

<div class="bg-[var(--color-mudah-dark)] min-h-screen flex flex-col">
    <Navbar />

    <main class="flex-grow">
        <!-- Hero Section -->
        <section class="relative pt-32 pb-20 overflow-hidden">
            <div class="container mx-auto px-6 relative z-10">
                <div class="max-w-4xl mx-auto text-center">
                    <!-- Search/Notification Pill -->
                    <div class="inline-flex items-center gap-2 bg-white/10 backdrop-blur-sm border border-white/10 rounded-full px-4 py-1.5 mb-8">
                        <span class="w-2 h-2 rounded-full bg-[var(--color-mudah-primary)]"></span>
                        <span class="text-white text-sm font-medium">Mulai dari Rp 299.000</span>
                        <span class="text-gray-400 text-sm">per bulan</span>
                        <svg class="w-4 h-4 text-gray-400" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7"></path></svg>
                    </div>

                    <h1 class="text-5xl md:text-7xl font-bold text-white tracking-tight mb-6 text-balance">
                        ERP yang mudah untuk UKM Indonesia.
                    </h1>
                    
                    <p class="text-lg md:text-xl text-gray-400 mb-10 max-w-2xl mx-auto leading-relaxed text-balance">
                        Platform enterprise-ready yang paling mudah untuk mengelola inventori, pesanan omnichannel, produksi, dan gudang. Satu dashboard untuk semua saluran penjualan Anda—Shopee, TikTok Shop, Lazada, Tokopedia, dan lainnya.
                    </p>
                    
                    <div class="flex flex-col sm:flex-row items-center justify-center gap-4">
                        <button class="bg-white hover:bg-gray-100 text-black px-6 py-3 rounded-full font-medium transition-colors flex items-center gap-2">
                            Coba Gratis 14 Hari
                            <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                                <path d="M5 12h14M12 5l7 7-7 7"/>
                            </svg>
                        </button>
                        <button class="bg-transparent border border-white/20 hover:bg-white/10 text-white px-6 py-3 rounded-full font-medium transition-colors flex items-center gap-2">
                            Lihat Demo
                            <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                                <path d="M5 12h14M12 5l7 7-7 7"/>
                            </svg>
                        </button>
                    </div>
                </div>
            </div>

            <!-- Hero Images/Cards -->
            <div class="mt-20 relative">
                <div class="flex justify-center gap-6 overflow-hidden px-6">
                    <!-- Card 1 - Inventory -->
                    <div class="w-[350px] md:w-[450px] flex-shrink-0 rounded-xl overflow-hidden shadow-2xl border border-white/10 transform -rotate-2 mt-8">
                        <div class="bg-white p-4">
                            <div class="flex items-center justify-between mb-4">
                                <div class="text-xs font-semibold text-gray-600">Inventori Real-time</div>
                                <div class="h-8 px-3 bg-[var(--color-mudah-primary)]/20 rounded text-[var(--color-mudah-primary)] text-xs flex items-center justify-center font-bold">1,234 SKU</div>
                            </div>
                            <div class="space-y-3">
                                <div class="h-24 bg-gray-100 rounded-lg w-full flex items-center justify-center">
                                    <svg class="w-12 h-12 text-gray-400" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M20 7l-8-4-8 4m16 0l-8 4m8-4v10l-8 4m0-10L4 7m8 4v10M4 7v10l8 4"></path></svg>
                                </div>
                                <div class="h-4 w-full bg-gray-50 rounded"></div>
                                <div class="h-4 w-2/3 bg-gray-50 rounded"></div>
                            </div>
                        </div>
                    </div>

                    <!-- Card 2 (Center) - Orders -->
                    <div class="w-[350px] md:w-[450px] flex-shrink-0 rounded-xl overflow-hidden shadow-2xl border border-white/10 z-10">
                        <div class="bg-white h-full flex flex-col">
                            <div class="bg-[var(--color-mudah-primary)] p-6">
                                <div class="flex justify-between items-center">
                                    <div class="text-white font-semibold">Pesanan Hari Ini</div>
                                    <div class="h-8 w-8 bg-white/20 rounded-full flex items-center justify-center text-white font-bold">47</div>
                                </div>
                            </div>
                            <div class="p-6 flex-grow">
                                <div class="space-y-3">
                                    <div class="flex items-center gap-3 pb-3 border-b border-gray-100">
                                        <div class="w-8 h-8 bg-orange-100 rounded flex items-center justify-center text-xs">🛍️</div>
                                        <div class="flex-grow">
                                            <div class="text-xs font-medium">Shopee</div>
                                            <div class="text-xs text-gray-400">15 pesanan</div>
                                        </div>
                                    </div>
                                    <div class="flex items-center gap-3 pb-3 border-b border-gray-100">
                                        <div class="w-8 h-8 bg-blue-100 rounded flex items-center justify-center text-xs">🎵</div>
                                        <div class="flex-grow">
                                            <div class="text-xs font-medium">TikTok Shop</div>
                                            <div class="text-xs text-gray-400">23 pesanan</div>
                                        </div>
                                    </div>
                                    <div class="flex items-center gap-3">
                                        <div class="w-8 h-8 bg-purple-100 rounded flex items-center justify-center text-xs">🛒</div>
                                        <div class="flex-grow">
                                            <div class="text-xs font-medium">Lazada</div>
                                            <div class="text-xs text-gray-400">9 pesanan</div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- Card 3 - Production -->
                    <div class="w-[350px] md:w-[450px] flex-shrink-0 rounded-xl overflow-hidden shadow-2xl border border-white/10 transform rotate-2 mt-8">
                        <div class="bg-white p-4">
                            <div class="flex items-center justify-between mb-4">
                                <div class="text-xs font-semibold text-gray-600">Status Produksi</div>
                                <div class="h-8 px-3 bg-green-100 rounded text-green-700 text-xs flex items-center justify-center font-bold">On Track</div>
                            </div>
                            <div class="space-y-3">
                                <div class="h-24 bg-gray-100 rounded-lg w-full p-3">
                                    <div class="flex justify-between text-xs mb-2">
                                        <span class="text-gray-500">Progress</span>
                                        <span class="font-semibold">75%</span>
                                    </div>
                                    <div class="h-2 bg-gray-200 rounded-full overflow-hidden mb-3">
                                        <div class="h-full bg-[var(--color-mudah-primary)] w-3/4"></div>
                                    </div>
                                    <div class="text-xs text-gray-400">Est. selesai: 2 hari</div>
                                </div>
                                <div class="h-4 w-full bg-gray-50 rounded"></div>
                                <div class="h-4 w-2/3 bg-gray-50 rounded"></div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Logos Section -->
        <section class="py-12 border-y border-white/5 bg-black/20">
            <div class="container mx-auto px-6">
                <p class="text-center text-gray-500 text-sm mb-8">Terintegrasi dengan platform e-commerce favorit Anda</p>
                <div class="flex flex-wrap justify-center items-center gap-12 md:gap-20 opacity-60">
                    <!-- Shopee -->
                    <div class="text-white font-bold text-2xl tracking-tight">Shopee</div>
                    <!-- TikTok Shop -->
                    <div class="text-white font-bold text-2xl tracking-tight">TikTok Shop</div>
                    <!-- Lazada -->
                    <div class="text-white font-bold text-2xl tracking-tight">Lazada</div>
                    <!-- Tokopedia -->
                    <div class="text-white font-bold text-2xl tracking-tight">Tokopedia</div>
                    <!-- Shopify -->
                    <div class="text-white font-bold text-2xl tracking-tight">Shopify</div>
                </div>
            </div>
        </section>

        <!-- Mudah Core Section -->
        <section class="py-32 relative overflow-hidden">
            <div class="container mx-auto px-6 relative z-10">
                <div class="text-center mb-24">
                    <h2 class="text-[var(--color-mudah-primary)] font-mono text-xs tracking-[0.2em] uppercase mb-6">Mudah ERP</h2>
                    <h3 class="text-4xl md:text-6xl font-bold text-white mb-2 tracking-tight">Sistem ERP yang lengkap.</h3>
                    <h3 class="text-4xl md:text-6xl font-bold text-gray-600 tracking-tight">Mudah digunakan.</h3>
                </div>

                <div class="grid md:grid-cols-2 gap-16 items-center max-w-6xl mx-auto">
                    <!-- Teal Card -->
                    <div class="bg-gradient-to-br from-[var(--color-mudah-primary)] to-[#0d9488] rounded-3xl p-12 aspect-[4/3] relative overflow-hidden flex items-center justify-center shadow-2xl">
                        <!-- Abstract UI Elements -->
                        <div class="relative z-10 w-full max-w-[320px]">
                            <!-- Dashboard Card -->
                            <div class="bg-white/10 backdrop-blur-xl border border-white/20 rounded-2xl p-6 mb-8 shadow-xl relative overflow-hidden group hover:scale-105 transition-transform duration-500">
                                <div class="space-y-4 relative z-10">
                                    <div class="flex justify-between items-center">
                                        <div class="text-white/80 text-xs uppercase tracking-wider font-medium">Total Penjualan</div>
                                        <div class="text-white/60 text-xs">Hari ini</div>
                                    </div>
                                    <div class="text-white font-bold text-3xl">Rp 45.8 jt</div>
                                    <div class="flex gap-2">
                                        <div class="flex-1 h-16 bg-white/20 rounded flex flex-col justify-end p-2">
                                            <div class="bg-white/40 h-3/4 rounded-t"></div>
                                        </div>
                                        <div class="flex-1 h-16 bg-white/20 rounded flex flex-col justify-end p-2">
                                            <div class="bg-white/40 h-1/2 rounded-t"></div>
                                        </div>
                                        <div class="flex-1 h-16 bg-white/20 rounded flex flex-col justify-end p-2">
                                            <div class="bg-white/40 h-full rounded-t"></div>
                                        </div>
                                        <div class="flex-1 h-16 bg-white/20 rounded flex flex-col justify-end p-2">
                                            <div class="bg-white/40 h-2/3 rounded-t"></div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                            
                            <!-- Floating Pills -->
                            <div class="relative">
                                <div class="absolute -left-4 top-0 bg-white text-black px-5 py-2.5 rounded-full text-sm font-semibold shadow-lg flex items-center gap-2 transform -rotate-2">
                                    <div class="w-5 h-5 rounded-full bg-orange-100 flex items-center justify-center text-orange-600">
                                        <svg class="w-3 h-3" fill="currentColor" viewBox="0 0 20 20"><path d="M3 1a1 1 0 000 2h1.22l.305 1.222a.997.997 0 00.01.042l1.358 5.43-.893.892C3.74 11.846 4.632 14 6.414 14H15a1 1 0 000-2H6.414l1-1H14a1 1 0 00.894-.553l3-6A1 1 0 0017 3H6.28l-.31-1.243A1 1 0 005 1H3zM16 16.5a1.5 1.5 0 11-3 0 1.5 1.5 0 013 0zM6.5 18a1.5 1.5 0 100-3 1.5 1.5 0 000 3z"/></svg>
                                    </div>
                                    Omnichannel
                                </div>
                                <div class="absolute -right-4 top-12 bg-white/10 backdrop-blur-md text-white px-5 py-2.5 rounded-full text-sm font-semibold border border-white/20 flex items-center gap-2 transform rotate-2">
                                    <div class="w-5 h-5 rounded-full bg-teal-500/30 flex items-center justify-center text-teal-200">
                                        <svg class="w-3 h-3" fill="currentColor" viewBox="0 0 20 20"><path d="M3 12v3c0 1.657 3.134 3 7 3s7-1.343 7-3v-3c0 1.657-3.134 3-7 3s-7-1.343-7-3z"/><path d="M3 7v3c0 1.657 3.134 3 7 3s7-1.343 7-3V7c0 1.657-3.134 3-7 3S3 8.657 3 7z"/><path d="M17 5c0 1.657-3.134 3-7 3S3 6.657 3 5s3.134-3 7-3 7 1.343 7 3z"/></svg>
                                    </div>
                                    Real-time inventory
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- Text Content -->
                    <div class="space-y-8">
                        <h3 class="text-4xl md:text-5xl font-bold text-white tracking-tight">Berkembang dengan fleksibilitas.</h3>
                        <p class="text-gray-400 text-lg leading-relaxed max-w-lg">
                            Bisnis berubah. Kebutuhan pelanggan berkembang. Mudah menyediakan ERP modern yang dibangun untuk beradaptasi dan tumbuh bersama bisnis Anda.
                        </p>
                    </div>
                </div>
            </div>
        </section>

        <!-- White Section -->
        <div class="bg-[#F9FAFB] text-black rounded-t-[4rem] relative z-20 mt-[-2rem] pt-32 pb-32">
            <div class="container mx-auto px-6">
                <!-- Header -->
                <div class="max-w-4xl mb-24">
                    <div class="flex items-center gap-4 mb-6">
                        <div class="h-px w-12 bg-gray-300"></div>
                        <span class="text-gray-500 font-mono text-xs tracking-[0.2em] uppercase">Modul Lengkap</span>
                    </div>
                    <h2 class="text-4xl md:text-6xl font-bold text-gray-900 mb-2 tracking-tight">Satu platform untuk mengelola dan mengembangkan bisnis.</h2>
                    <h2 class="text-4xl md:text-6xl font-bold text-gray-400 tracking-tight mb-8">Sesederhana atau sekompleks yang Anda butuhkan.</h2>
                    
                    <a href="#" class="inline-flex items-center gap-2 text-sm font-semibold border-b border-black pb-0.5 hover:text-gray-600 transition-colors">
                        Jelajahi semua modul
                        <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                            <path d="M5 12h14M12 5l7 7-7 7"/>
                        </svg>
                    </a>
                </div>

                <!-- Features Grid -->
                <div class="flex flex-col lg:flex-row gap-12">
                    <!-- Sidebar Navigation (Sticky) -->
                    <div class="hidden lg:block w-64 flex-shrink-0">
                        <div class="sticky top-32 space-y-4">
                            <div class="flex items-center gap-2 text-sm font-semibold text-black border-l-2 border-black pl-4 py-1">
                                <span class="w-1.5 h-1.5 rounded-full bg-[var(--color-mudah-primary)]"></span>
                                Manajemen Inventori
                            </div>
                            <a href="#" class="block text-sm text-gray-500 pl-4 py-1 hover:text-black border-l-2 border-transparent hover:border-gray-200 transition-colors">Pesanan Omnichannel</a>
                            <a href="#" class="block text-sm text-gray-500 pl-4 py-1 hover:text-black border-l-2 border-transparent hover:border-gray-200 transition-colors">Manajemen Produksi</a>
                            <a href="#" class="block text-sm text-gray-500 pl-4 py-1 hover:text-black border-l-2 border-transparent hover:border-gray-200 transition-colors">Manajemen Pembelian</a>
                            <a href="#" class="block text-sm text-gray-500 pl-4 py-1 hover:text-black border-l-2 border-transparent hover:border-gray-200 transition-colors">Akuntansi Biaya</a>
                            <a href="#" class="block text-sm text-gray-500 pl-4 py-1 hover:text-black border-l-2 border-transparent hover:border-gray-200 transition-colors">Manajemen Gudang</a>
                        </div>
                    </div>

                    <!-- Feature Cards -->
                    <div class="flex-grow space-y-8">
                        <FeatureRow 
                            title="Manajemen Inventori" 
                            description="Minimalkan stockout dan maksimalkan turnover. Platform enterprise-ready paling mudah untuk melacak level stok dan menghitung biaya inventori secara real-time."
                            icon="lock"
                            image="collateral"
                        />
                         <FeatureRow 
                            title="Pesanan Omnichannel" 
                            description="Menangkan bisnis lebih cepat dengan sentralisasi setiap penjualan. Baik Shopee, TikTok Shop, Lazada, Shopify, Amazon, atau grosir B2B, pesanan dari setiap saluran mengalir ke satu dashboard terpadu."
                            icon="connect"
                            image="connect"
                        />
                         <FeatureRow 
                            title="Manajemen Produksi" 
                            description="Beradaptasi dengan alur kerja apa pun. Baik model 'Make-to-Stock' atau 'Make-to-Order', alat kami membantu Anda memangkas biaya, melacak bahan baku, dan meningkatkan throughput produksi."
                            icon="data"
                            image="data"
                        />
                         <FeatureRow 
                            title="Manajemen Pembelian" 
                            description="Tetap unggul dari permintaan tanpa kerja manual. Gunakan saran reorder pintar dan alur pembelian otomatis untuk mengisi ulang stok tepat saat Anda membutuhkannya."
                            icon="lab"
                            image="lab"
                        />
                         <FeatureRow 
                            title="Akuntansi Biaya" 
                            description="Ketahui margin sebenarnya Anda. Lihat biaya secara real-time dan sinkronkan invoice otomatis dengan alat keuangan yang sudah Anda percaya, termasuk QuickBooks, Xero, dan Sage."
                            icon="preview"
                            image="preview"
                        />
                         <FeatureRow 
                            title="Manajemen Gudang" 
                            description="Bawa disiplin ke fulfillment Anda. Sederhanakan transfer stok, picking, packing, dan shipping dengan aplikasi gudang mobile yang dilengkapi pemindaian barcode dan pencetakan label."
                            icon="guard"
                            image="guard"
                        />
                    </div>
                </div>

                <!-- Modular Section -->
                <div class="mt-32 text-center max-w-4xl mx-auto mb-24">
                    <div class="w-24 h-24 mx-auto bg-gradient-to-br from-teal-100 to-cyan-100 rounded-full flex items-center justify-center mb-8 relative">
                        <div class="absolute inset-0 bg-white/50 blur-xl rounded-full"></div>
                        <svg class="w-10 h-10 text-teal-600 relative z-10" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 5a1 1 0 011-1h4a1 1 0 011 1v7a1 1 0 01-1 1H5a1 1 0 01-1-1V5zM14 5a1 1 0 011-1h4a1 1 0 011 1v7a1 1 0 01-1 1h-4a1 1 0 01-1-1V5zM4 16a1 1 0 011-1h4a1 1 0 011 1v3a1 1 0 01-1 1H5a1 1 0 01-1-1v-3zM14 16a1 1 0 011-1h4a1 1 0 011 1v3a1 1 0 01-1 1h-4a1 1 0 01-1-1v-3z"></path></svg>
                    </div>
                    <h2 class="text-4xl md:text-5xl font-bold text-gray-900 mb-8 leading-tight">
                        Mulai dengan modul yang Anda butuhkan, berkembang seiring pertumbuhan bisnis Anda.
                    </h2>
                    <button class="bg-white border border-gray-200 hover:border-gray-400 text-black px-6 py-3 rounded-full font-medium transition-colors flex items-center gap-2 mx-auto">
                        Lihat semua industri
                        <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                            <path d="M5 12h14M12 5l7 7-7 7"/>
                        </svg>
                    </button>
                </div>

                <!-- Trusted By Section -->
                <div class="mb-32">
                    <p class="text-xl text-gray-500 mb-12">Dipercaya oleh UKM Indonesia. Pelajari lebih lanjut dari pelanggan kami.</p>
                    
                    <div class="grid md:grid-cols-3 gap-6">
                        <!-- Main Card (Large) -->
                        <div class="md:col-span-2 bg-[#0A0A0A] rounded-3xl p-10 relative overflow-hidden group min-h-[400px] flex flex-col justify-end">
                            <div class="absolute inset-0 bg-gradient-to-t from-black via-black/50 to-transparent"></div>
                            
                            <div class="relative z-10">
                                <div class="flex items-center gap-4 mb-6">
                                    <div class="text-white font-bold text-2xl tracking-tight">BatikKu</div>
                                    <div class="w-8 h-8 rounded-full bg-[var(--color-mudah-primary)] flex items-center justify-center text-white font-bold">+</div>
                                    <div class="flex items-center gap-2 text-white font-semibold text-xl tracking-tight">
                                        <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                                            <rect x="3" y="3" width="8" height="8" rx="1" stroke="white" stroke-width="2"/>
                                            <rect x="13" y="3" width="8" height="8" rx="1" stroke="white" stroke-width="2"/>
                                            <rect x="3" y="13" width="8" height="8" rx="1" stroke="white" stroke-width="2"/>
                                            <rect x="13" y="13" width="8" height="8" rx="1" stroke="white" stroke-width="2"/>
                                        </svg>
                                        Mudah
                                    </div>
                                </div>
                                <h3 class="text-3xl font-bold text-white mb-4 max-w-md">
                                    Bagaimana BatikKu meningkatkan penjualan 300% dengan Mudah ERP
                                </h3>
                                <div class="w-10 h-10 rounded-full bg-white/10 backdrop-blur-md border border-white/20 flex items-center justify-center text-white group-hover:bg-white group-hover:text-black transition-colors">
                                    <svg class="w-4 h-4" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><line x1="7" y1="17" x2="17" y2="7"></line><polyline points="7 7 17 7 17 17"></polyline></svg>
                                </div>
                            </div>
                        </div>

                        <!-- Smaller Cards -->
                        <div class="space-y-6">
                            <!-- Card 2 -->
                            <div class="bg-[#0A0A0A] rounded-3xl p-8 relative overflow-hidden group h-[240px] flex flex-col justify-between">
                                <div class="absolute inset-0 bg-gradient-to-br from-teal-900/40 to-black"></div>
                                <div class="relative z-10">
                                    <div class="text-white font-semibold text-lg mb-2">SnackBox</div>
                                    <p class="text-gray-400 text-sm">Mengelola 5 toko online dengan satu dashboard</p>
                                </div>
                                <div class="relative z-10 flex justify-end">
                                    <div class="w-12 h-12 rounded-full bg-teal-400/20 blur-xl absolute -left-2 -bottom-2"></div>
                                    <div class="w-10 h-10 rounded-full bg-white/10 backdrop-blur-md border border-white/20 flex items-center justify-center text-white group-hover:bg-white group-hover:text-black transition-colors">
                                        <svg class="w-4 h-4" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><line x1="7" y1="17" x2="17" y2="7"></line><polyline points="7 7 17 7 17 17"></polyline></svg>
                                    </div>
                                </div>
                            </div>
                            <!-- Card 3 -->
                            <div class="bg-[#0A0A0A] rounded-3xl p-8 relative overflow-hidden group h-[240px] flex flex-col justify-between">
                                <div class="absolute inset-0 bg-gradient-to-br from-cyan-900/40 to-black"></div>
                                <div class="relative z-10">
                                    <div class="text-white font-semibold text-lg mb-2">FurniCraft</div>
                                    <p class="text-gray-400 text-sm">Produksi custom furniture tanpa chaos</p>
                                </div>
                                <div class="relative z-10 flex justify-end">
                                    <div class="w-12 h-12 rounded-full bg-cyan-400/20 blur-xl absolute -left-2 -bottom-2"></div>
                                    <div class="w-10 h-10 rounded-full bg-white/10 backdrop-blur-md border border-white/20 flex items-center justify-center text-white group-hover:bg-white group-hover:text-black transition-colors">
                                        <svg class="w-4 h-4" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><line x1="7" y1="17" x2="17" y2="7"></line><polyline points="7 7 17 7 17 17"></polyline></svg>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Banner -->
                <div class="bg-[#0A0A0A] rounded-3xl p-12 md:p-20 relative overflow-hidden mb-32 text-center">
                    <div class="absolute inset-0 bg-[url('/grid-pattern.svg')] opacity-10"></div>
                    <div class="absolute left-0 top-0 w-64 h-64 bg-teal-500/10 blur-[100px] rounded-full"></div>
                    <div class="absolute right-0 bottom-0 w-64 h-64 bg-cyan-500/10 blur-[100px] rounded-full"></div>
                    
                    <div class="relative z-10 max-w-3xl mx-auto">
                        <h2 class="text-4xl md:text-6xl font-bold text-white mb-6 tracking-tight">
                            Kelola bisnis dengan mudah. <span class="text-[var(--color-mudah-primary)]">Mulai Rp 299.000.</span>
                        </h2>
                        <p class="text-gray-400 mb-10">
                            Pilih modul yang Anda butuhkan hari ini. Tambahkan lebih banyak seiring pertumbuhan bisnis Anda. Tanpa kontrak jangka panjang.
                        </p>
                        <div class="inline-flex items-center gap-2 bg-white/10 backdrop-blur-md border border-white/10 rounded-full px-4 py-2 text-white text-sm hover:bg-white/20 transition-colors cursor-pointer">
                            <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 6.253v13m0-13C10.832 5.477 9.246 5 7.5 5S4.168 5.477 3 6.253v13C4.168 18.477 5.754 18 7.5 18s3.332.477 4.5 1.253m0-13C13.168 5.477 14.754 5 16.5 5c1.747 0 3.332.477 4.5 1.253v13C19.832 18.477 18.247 18 16.5 18c-1.746 0-3.332.477-4.5 1.253"></path></svg>
                            Panduan Memulai
                            <kbd class="bg-black/30 px-1.5 py-0.5 rounded text-xs text-gray-400 font-mono">→</kbd>
                        </div>
                    </div>
                </div>

                <!-- Integrations -->
                <div class="text-center mb-32">
                    <h2 class="text-3xl md:text-4xl font-bold text-gray-900 mb-4">
                        E-commerce. Akuntansi.<br>
                        Pembayaran. <span class="text-gray-400">Platform apa pun yang<br>Anda gunakan, Mudah terhubung.</span>
                    </h2>
                    <button class="bg-gray-100 hover:bg-gray-200 text-black px-6 py-2 rounded-full text-sm font-medium transition-colors flex items-center gap-2 mx-auto mb-16 mt-8">
                        Jelajahi semua integrasi
                        <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                            <path d="M5 12h14M12 5l7 7-7 7"/>
                        </svg>
                    </button>

                    <div class="grid grid-cols-2 md:grid-cols-4 gap-px bg-gray-200 border border-gray-200 rounded-2xl overflow-hidden">
                        {#each ['Shopee', 'TikTok Shop', 'Lazada', 'Tokopedia', 'QuickBooks', 'Xero', 'Shopify', 'Amazon'] as logo}
                        <div class="bg-[#F9FAFB] p-12 flex items-center justify-center grayscale opacity-60 hover:grayscale-0 hover:opacity-100 transition-all duration-300">
                            <span class="font-bold text-xl tracking-wider">{logo}</span>
                        </div>
                        {/each}
                    </div>
                </div>

                <!-- Blog Section -->
                <div class="mb-12">
                    <h2 class="text-4xl font-bold text-gray-900 mb-12">Pelajari lebih lanjut tentang manajemen bisnis modern.</h2>
                    <div class="grid md:grid-cols-2 gap-8">
                        <!-- Post 1 -->
                        <div class="group cursor-pointer">
                            <div class="bg-gradient-to-br from-teal-100 to-cyan-200 rounded-3xl aspect-[16/9] mb-6 relative overflow-hidden">
                                <div class="absolute inset-0 flex items-center justify-center">
                                    <div class="grid grid-cols-6 gap-4 opacity-50">
                                        {#each Array(24) as _}
                                            <svg class="w-6 h-6 text-teal-600 transform -rotate-45" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 10l7-7m0 0l7 7m-7-7v18"></path></svg>
                                        {/each}
                                    </div>
                                </div>
                            </div>
                            <div class="text-xs font-bold text-gray-500 uppercase tracking-wider mb-2">Wawasan Industri</div>
                            <h3 class="text-2xl font-bold text-gray-900 group-hover:text-teal-600 transition-colors">Cara UKM Indonesia meningkatkan efisiensi dengan ERP</h3>
                        </div>
                        <!-- Post 2 -->
                        <div class="group cursor-pointer">
                            <div class="bg-gray-100 rounded-3xl aspect-[16/9] mb-6 relative overflow-hidden flex items-center justify-center">
                                <div class="flex gap-4">
                                    <div class="w-16 h-16 rounded-full bg-teal-400 blur-xl opacity-80"></div>
                                    <div class="w-20 h-20 rounded-full bg-cyan-400 blur-xl opacity-80"></div>
                                    <div class="w-12 h-12 rounded-full bg-blue-400 blur-xl opacity-80"></div>
                                </div>
                            </div>
                            <div class="text-xs font-bold text-gray-500 uppercase tracking-wider mb-2">Panduan</div>
                            <h3 class="text-2xl font-bold text-gray-900 group-hover:text-teal-600 transition-colors">Omnichannel selling: Dari satu toko ke lima marketplace</h3>
                        </div>
                    </div>
                </div>


    </main>

    <Footer />
</div>

