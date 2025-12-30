<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Aganz Official - Gadget, Aksesoris & Solusi Dana Tunai Nasional</title>
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Font Awesome -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">
    
    <script>
        window.tailwind = window.tailwind || {};
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        primary: '#0f172a',
                        accent: '#2563eb',
                        secondary: '#f59e0b',
                    },
                    fontFamily: {
                        sans: ['Poppins', 'sans-serif'],
                    }
                }
            }
        };
    </script>
    <style type="text/tailwindcss">
        @layer utilities {
          .hero-bg {
            background: linear-gradient(rgba(15, 23, 42, 0.85), rgba(15, 23, 42, 0.85)), url('https://images.unsplash.com/photo-1511707171634-5f897ff02aa9?ixlib=rb-4.0.3&auto=format&fit=crop&w=1415&q=80');
            background-size: cover;
            background-position: center;
          }
          .glass-card {
            background: rgba(255, 255, 255, 0.05);
            backdrop-filter: blur(10px);
            border: 1px solid rgba(255, 255, 255, 0.1);
          }
          .chat-bubble-shadow {
            box-shadow: 0 10px 25px -5px rgba(0, 0, 0, 0.1), 0 8px 10px -6px rgba(0, 0, 0, 0.1);
          }
        }
        .smooth-scroll {
            scroll-behavior: smooth;
        }
        @keyframes bounce-slow {
            0%, 100% { transform: translateY(-5%); }
            50% { transform: translateY(0); }
        }
        .animate-bounce-slow {
            animation: bounce-slow 3s infinite;
        }
    </style>
</head>
<body class="font-sans antialiased text-gray-800 bg-gray-50 smooth-scroll">

    <!-- Top Info Bar -->
    <div class="bg-accent text-white py-2 text-center text-xs font-semibold tracking-wide">
        <i class="fa-solid fa-earth-asia mr-2"></i> LAYANAN DANA TUNAI BPKB & GADGET TERSEDIA UNTUK SELURUH WILAYAH INDONESIA
    </div>

    <!-- Navigation -->
    <nav class="bg-primary/95 backdrop-blur-md text-white sticky top-0 z-50 shadow-xl">
        <div class="container mx-auto px-4 flex justify-between items-center py-4">
            <a href="#" class="text-2xl font-bold flex items-center gap-2">
                <i class="fa-solid fa-mobile-screen-button text-secondary text-xl"></i>
                Aganz<span class="text-accent">Official</span>
            </a>

            <div class="hidden md:flex space-x-8 font-medium text-sm">
                <a href="#home" class="hover:text-accent transition">Beranda</a>
                <a href="#produk-gadget" class="hover:text-accent transition">Gadget</a>
                <a href="#produk-aksesoris" class="hover:text-accent transition">Aksesoris</a>
                <a href="#gadai-bpkb" class="text-secondary hover:text-yellow-300 transition font-bold flex items-center gap-1">
                    <i class="fa-solid fa-file-invoice-dollar"></i> Dana Tunai BPKB
                </a>
                <a href="#contact" class="hover:text-accent transition">Kontak</a>
            </div>

            <button class="md:hidden text-2xl focus:outline-none">
                <i class="fa-solid fa-bars-staggered"></i>
            </button>
        </div>
    </nav>

    <!-- Hero Section -->
    <header id="home" class="hero-bg text-white min-h-[85vh] flex items-center">
        <div class="container mx-auto px-4 text-center md:text-left">
            <div class="max-w-3xl">
                <div class="inline-flex items-center gap-2 bg-white/10 border border-white/20 px-3 py-1 rounded-full text-xs font-bold mb-6">
                    <span class="flex h-2 w-2 rounded-full bg-green-400 animate-pulse"></span>
                    SOLUSI GADGET & DANA TUNAI TERPERCAYA
                </div>
                <h1 class="text-4xl md:text-6xl font-bold mb-6 leading-tight">
                    Pusat Gadget & <br> 
                    <span class="text-secondary underline decoration-accent text-3xl md:text-5xl uppercase">Pinjaman Dana BPKB</span>
                </h1>
                <p class="text-xl text-gray-300 mb-10 leading-relaxed">
                    Dapatkan smartphone impian dengan garansi resmi atau cairkan dana tunai cepat hanya dengan jaminan BPKB Motor/Mobil.
                </p>
                <div class="flex flex-wrap justify-center md:justify-start gap-4">
                    <a href="#produk-gadget" class="bg-accent hover:bg-blue-700 text-white px-8 py-3 rounded-xl font-bold transition-all shadow-lg flex items-center gap-2">
                        <i class="fa-solid fa-store"></i> Katalog Gadget
                    </a>
                    <a href="#gadai-bpkb" class="bg-secondary hover:bg-yellow-500 text-primary px-8 py-3 rounded-xl font-bold transition-all shadow-lg flex items-center gap-2">
                        <i class="fa-solid fa-car"></i> Ajukan Dana BPKB
                    </a>
                </div>
            </div>
        </div>
    </header>

    <!-- KATEGORI GADGET -->
    <section id="produk-gadget" class="py-20 bg-white">
        <div class="container mx-auto px-4">
            <div class="flex flex-col md:flex-row justify-between items-end mb-12 gap-4">
                <div>
                    <span class="text-accent font-bold text-xs uppercase tracking-widest">Premium Collection</span>
                    <h2 class="text-3xl font-bold text-primary mt-1 uppercase">Katalog Gadget</h2>
                    <p class="text-gray-500 text-sm mt-2">Smartphone Android & iOS dengan garansi resmi iBox / SEIN.</p>
                </div>
                <a href="https://wa.me/6282217446919" class="text-accent font-bold flex items-center gap-2 hover:underline">Lihat Semua <i class="fa-solid fa-arrow-right"></i></a>
            </div>
            
            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-8">
                <!-- Produk Gadget 1 -->
                <div class="group bg-gray-50 rounded-3xl p-4 border border-transparent hover:border-accent transition-all shadow-sm">
                    <div class="bg-white rounded-2xl h-60 flex items-center justify-center mb-6 overflow-hidden">
                        <img src="https://placehold.co/400x500/e2e8f0/1e293b?text=iPhone+16+Pro" alt="iPhone 16 Pro" class="h-48 object-contain group-hover:scale-110 transition duration-500">
                    </div>
                    <h3 class="font-bold text-lg text-primary mb-1">iPhone 16 Pro</h3>
                    <p class="text-gray-400 text-xs mb-4">Garansi Resmi iBox</p>
                    <div class="flex items-center justify-between">
                        <span class="text-accent font-bold">Cek Harga</span>
                        <button onclick="orderViaWA('iPhone 16 Pro')" class="bg-accent text-white w-10 h-10 rounded-full flex items-center justify-center hover:bg-primary transition shadow-md">
                            <i class="fa-solid fa-cart-shopping text-sm"></i>
                        </button>
                    </div>
                </div>

                <!-- Produk Gadget 2 -->
                <div class="group bg-gray-50 rounded-3xl p-4 border border-transparent hover:border-accent transition-all shadow-sm">
                    <div class="bg-white rounded-2xl h-60 flex items-center justify-center mb-6 overflow-hidden">
                        <img src="https://placehold.co/400x500/e2e8f0/1e293b?text=Samsung+S24" alt="Samsung S24" class="h-48 object-contain group-hover:scale-110 transition duration-500">
                    </div>
                    <h3 class="font-bold text-lg text-primary mb-1">Samsung S24 Ultra</h3>
                    <p class="text-gray-400 text-xs mb-4">Garansi Resmi SEIN</p>
                    <div class="flex items-center justify-between">
                        <span class="text-accent font-bold">Cek Harga</span>
                        <button onclick="orderViaWA('Samsung S24 Ultra')" class="bg-accent text-white w-10 h-10 rounded-full flex items-center justify-center hover:bg-primary transition shadow-md">
                            <i class="fa-solid fa-cart-shopping text-sm"></i>
                        </button>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- DANA TUNAI BPKB -->
    <section id="gadai-bpkb" class="py-24 bg-primary text-white relative overflow-hidden">
        <div class="container mx-auto px-4 relative z-10">
            <div class="grid grid-cols-1 lg:grid-cols-2 gap-16 items-center">
                <div>
                    <h2 class="text-4xl font-bold mb-6 text-secondary uppercase">Dana Tunai <br> BPKB Mobil & Motor</h2>
                    <p class="text-gray-400 mb-10 leading-relaxed text-lg">
                        Butuh dana cepat untuk modal usaha atau kebutuhan mendadak? Jaminkan BPKB kendaraan Anda. Proses aman dan diawasi OJK.
                    </p>
                    <div class="grid grid-cols-1 md:grid-cols-2 gap-4">
                        <div class="bg-white/5 p-4 rounded-xl border border-white/10">
                            <i class="fa-solid fa-bolt text-accent mb-3 text-xl"></i>
                            <h4 class="font-bold text-sm">Proses Cepat</h4>
                            <p class="text-[10px] text-gray-400 mt-1">Cair dalam hitungan jam setelah survei.</p>
                        </div>
                        <div class="bg-white/5 p-4 rounded-xl border border-white/10">
                            <i class="fa-solid fa-shield-halved text-secondary mb-3 text-xl"></i>
                            <h4 class="font-bold text-sm">Bunga Rendah</h4>
                            <p class="text-[10px] text-gray-400 mt-1">Suku bunga kompetitif mulai 0.7%.</p>
                        </div>
                    </div>
                </div>
                
                <div class="bg-white text-gray-800 p-8 rounded-[2rem] shadow-2xl">
                    <h3 class="text-2xl font-bold mb-6 text-center text-primary">Formulir Pengajuan</h3>
                    <form onsubmit="submitGadai(event)" class="space-y-4">
                        <div class="grid grid-cols-1 md:grid-cols-2 gap-4">
                            <input type="text" id="nama" class="w-full bg-gray-50 px-4 py-3 rounded-xl border border-gray-200 text-sm focus:border-accent outline-none" placeholder="Nama Sesuai KTP" required>
                            <input type="text" id="alamat" class="w-full bg-gray-50 px-4 py-3 rounded-xl border border-gray-200 text-sm focus:border-accent outline-none" placeholder="Kota Domisili" required>
                        </div>
                        <div class="grid grid-cols-1 md:grid-cols-2 gap-4">
                            <select id="jenis_jaminan" class="w-full bg-gray-50 px-4 py-3 rounded-xl border border-gray-200 text-sm focus:border-accent outline-none" required>
                                <option value="">Pilih Jaminan</option>
                                <option value="BPKB Motor">BPKB Motor</option>
                                <option value="BPKB Mobil">BPKB Mobil</option>
                            </select>
                            <input type="number" id="tahun" class="w-full bg-gray-50 px-4 py-3 rounded-xl border border-gray-200 text-sm focus:border-accent outline-none" placeholder="Tahun (Contoh: 2021)" required>
                        </div>
                        <input type="text" id="merk_tipe" class="w-full bg-gray-50 px-4 py-3 rounded-xl border border-gray-200 text-sm focus:border-accent outline-none" placeholder="Merk & Tipe" required>
                        <input type="text" id="nominal" class="w-full bg-gray-50 px-4 py-3 rounded-xl border border-gray-200 text-sm focus:border-accent outline-none" placeholder="Kebutuhan Dana" required>
                        <button type="submit" class="w-full bg-accent text-white font-bold py-4 rounded-xl hover:bg-blue-700 transition flex items-center justify-center gap-2 shadow-lg">
                            <i class="fa-brands fa-whatsapp text-xl"></i> Kirim Pengajuan WA
                        </button>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer id="contact" class="bg-primary text-gray-400 py-16 border-t border-white/5">
        <div class="container mx-auto px-4 text-center">
            <h2 class="text-2xl font-bold text-white mb-4">Aganz Official</h2>
            <!-- ALAMAT DIPERBARUI -->
            <p class="text-sm mb-8">Sukajati, Kecamatan Haurgeulis, Kabupaten Indramayu, Jawa Barat.</p>
            <div class="flex justify-center gap-6 mb-10">
                <a href="https://www.instagram.com/aganzofficialolshop?igsh=anRkaXc1aWV2bHN4&utm_source=qr" target="_blank" class="w-12 h-12 bg-white/5 rounded-full flex items-center justify-center hover:bg-accent hover:text-white transition"><i class="fa-brands fa-instagram text-xl"></i></a>
                <a href="https://wa.me/6282217446919" class="w-12 h-12 bg-white/5 rounded-full flex items-center justify-center hover:bg-green-500 hover:text-white transition"><i class="fa-brands fa-whatsapp text-xl"></i></a>
            </div>
            <p class="text-[9px] tracking-widest uppercase">© 2025 Aganz Official - Solusi Gadget & Dana Tunai.</p>
        </div>
    </footer>

    <!-- FLOAT BUTTON WHATSAPP -->
    <a href="https://wa.me/6282217446919" target="_blank" class="fixed bottom-6 right-6 w-14 h-14 bg-green-500 text-white rounded-full flex items-center justify-center shadow-2xl z-[999] animate-bounce-slow">
        <i class="fa-brands fa-whatsapp text-2xl"></i>
    </a>

    <script>
        function orderViaWA(productName) {
            const url = `https://wa.me/6282217446919?text=Halo%20Admin%20Aganz%20Official,%20saya%20tertarik%20order%20*${productName}*.`;
            window.open(url, '_blank');
        }

        function submitGadai(event) {
            event.preventDefault();
            const nama = document.getElementById('nama').value;
            const alamat = document.getElementById('alamat').value;
            const jaminan = document.getElementById('jenis_jaminan').value;
            const merk = document.getElementById('merk_tipe').value;
            const tahun = document.getElementById('tahun').value;
            const dana = document.getElementById('nominal').value;

            const message = `Halo Admin Aganz Official,\n\nSaya ingin mengajukan Dana Tunai BPKB.\n\n*Nama:* ${nama}\n*Domisili:* ${alamat}\n*Jenis Jaminan:* ${jaminan}\n*Merk/Tipe:* ${merk}\n*Tahun:* ${tahun}\n*Kebutuhan Dana:* ${dana}`;
            window.open(`https://wa.me/6282217446919?text=${encodeURIComponent(message)}`, '_blank');
        }
    </script>
</body>
</html>
