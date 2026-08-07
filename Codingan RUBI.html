<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Batik Ciprat RUBI - Desa KedungDowo</title>
    <style>
        /* --- 1. CSS DASAR (TEMA BATIK/COKLAT BUMI) --- */
        :root {
            --primary-color: #5D4037; /* Coklat Gelap Elegan */
            --accent-color: #D84315; /* Oranye Bata/Sogan */
            --bg-color: #FDFBF7; /* Krem Terang/Off-white */
            --card-bg: #ffffff;
        }
        * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; }
        body { background-color: var(--bg-color); color: #333; overflow-x: hidden; }

        /* --- 2. HEADER --- */
        header {
            background-color: var(--primary-color); color: white; padding: 1rem 2rem;
            display: flex; justify-content: space-between; align-items: center;
            position: sticky; top: 0; z-index: 100;
            box-shadow: 0 2px 10px rgba(0,0,0,0.2);
        }
        .header-left { display: flex; align-items: center; gap: 15px; }
        
        /* LOGO ICON */
        .logo-icon { 
            width: 50px; 
            height: 50px; 
            object-fit: contain; 
            background: transparent; 
            border: none; 
            border-radius: 0; 
            transform: scale(1.8); 
            margin-left: 15px; 
        }

        header h1 { font-size: 1.5rem; font-weight: bold; letter-spacing: 1px; }
        
        /* Hamburger Menu */
        .hamburger {
            font-size: 1.4rem; cursor: pointer; color: white; 
            padding: 5px 10px; transition: 0.3s; border: 1px solid rgba(255,255,255,0.5); border-radius: 5px;
        }
        .hamburger:hover { background: rgba(255,255,255,0.1); border-color: white; }

        /* --- 3. SIDEBAR MENU --- */
        .sidebar {
            position: fixed; top: 0; right: -250px; width: 250px; height: 100vh;
            background: white; box-shadow: -5px 0 15px rgba(0,0,0,0.2);
            padding: 20px; z-index: 200; transition: 0.4s ease;
            display: flex; flex-direction: column; gap: 15px;
        }
        .sidebar.active { right: 0; }
        .close-btn { align-self: flex-end; font-size: 1.5rem; cursor: pointer; color: var(--primary-color); }
        .menu-link {
            text-decoration: none; color: #333; font-size: 1rem; font-weight: bold;
            border-bottom: 1px solid #eee; padding-bottom: 10px; display: block; transition: 0.3s;
        }
        .menu-link:hover { color: var(--accent-color); }

        .overlay {
            position: fixed; top: 0; left: 0; width: 100%; height: 100%;
            background: rgba(0,0,0,0.5); z-index: 150; display: none;
        }
        .overlay.active { display: block; }

        /* --- 4. HERO BANNER --- */
        .hero {
            background-image: linear-gradient(rgba(93, 64, 55, 0.7), rgba(93, 64, 55, 0.7)), url('banner-batik.jpg');
            background-size: cover; background-position: center; height: 400px;
            display: flex; flex-direction: column; justify-content: center; align-items: center; color: white; text-align: center; padding: 0 20px;
        }
        .hero h2 { font-size: 2.8rem; margin-bottom: 15px; text-shadow: 2px 2px 4px rgba(0,0,0,0.5); }
        .hero p { font-size: 1.2rem; max-width: 600px; line-height: 1.5; }

        /* --- 5. KATALOG --- */
        .container { max-width: 1200px; margin: 50px auto; padding: 0 20px; }
        .section-title { text-align: center; font-size: 2.5rem; color: var(--primary-color); margin-bottom: 10px; }
        .section-subtitle { text-align: center; font-size: 1.1rem; color: #666; margin-bottom: 40px; }
        
        .category-title { font-size: 1.5rem; color: var(--primary-color); margin-top: 20px; margin-bottom: 20px; border-bottom: 2px solid var(--accent-color); padding-bottom: 10px; display: inline-block; }
        .product-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(280px, 1fr)); gap: 30px; }

        /* --- 6. KARTU PRODUK --- */
        .product-card {
            background: var(--card-bg); border-radius: 12px; overflow: hidden;
            box-shadow: 0 5px 20px rgba(0,0,0,0.08); position: relative;
            display: flex; flex-direction: column; transition: transform 0.3s;
            border: 1px solid #f0f0f0;
        }
        .product-card:hover { transform: translateY(-8px); box-shadow: 0 8px 25px rgba(0,0,0,0.15); }
        
        .product-image { 
            width: 100%; height: 350px; 
            object-fit: cover; object-position: center; 
        }

        /* --- QTY MELAYANG --- */
        .qty-container {
            position: absolute; top: 300px; 
            left: 50%; transform: translate(-50%, 20px);
            background: white; padding: 5px 15px; border-radius: 50px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.2); opacity: 0; visibility: hidden;
            transition: all 0.3s; display: flex; align-items: center; gap: 10px; z-index: 30;
        }
        .product-card:hover .qty-container { opacity: 1; visibility: visible; transform: translate(-50%, -15px); }
        .btn-qty-control { width: 28px; height: 28px; background: var(--primary-color); color: white; border: none; border-radius: 50%; cursor: pointer; display: flex; align-items: center; justify-content: center; font-weight: bold; }
        .input-qty-display { width: 30px; text-align: center; border: none; font-weight: bold; color: var(--primary-color); }
        
        .product-info { padding: 20px; background: white; z-index: 20; flex-grow: 1; display: flex; flex-direction: column; justify-content: space-between; }
        .product-title { font-size: 1.2rem; font-weight: bold; margin-bottom: 5px; color: #333; }
        .product-desc { font-size: 0.9rem; color: #777; margin-bottom: 15px; line-height: 1.4; }

        /* HARGA & TOMBOL */
        .price-box { margin-top: auto; padding-top: 15px; border-top: 1px dashed #eee; margin-bottom: 15px; }
        .price-original { color: var(--accent-color); font-size: 1.35rem; font-weight: bold; }

        .btn-buy {
            display: block; width: 100%; padding: 12px;
            background-color: var(--primary-color); color: white;
            border: none; border-radius: 8px; cursor: pointer; font-weight: bold; font-size: 1rem;
            transition: 0.3s; text-align: center; text-decoration: none;
        }
        .btn-buy:hover { background: var(--accent-color); }

        /* Footer */
        footer { background: var(--primary-color); color: white; text-align: center; padding: 30px 20px; margin-top: 60px; }
        .footer-desc { font-size: 0.9rem; max-width: 500px; margin: 0 auto 15px auto; opacity: 0.8; line-height: 1.5; }
        .social-icon { width: 30px; height: 30px; fill: white; transition: 0.3s; }
        .social-icon:hover { transform: scale(1.2); fill: var(--accent-color); }
        
        /* Responsif */
        @media (max-width: 600px) {
            .product-grid { grid-template-columns: 1fr; gap: 20px; }
            .product-image { height: 300px; }
            .qty-container { top: 250px; }
            .hero h2 { font-size: 2rem; }
        }
    </style>
</head>
<body>

    <!-- HEADER -->
    <header>
        <div class="header-left">
            <img src="Logo Batik.png" alt="Logo RUBI" class="logo-icon">
            <h1>Batik Ciprat RUBI</h1>
        </div>
        <div class="hamburger" onclick="toggleMenu()">&#9776; Menu</div>
    </header>

    <div class="overlay" id="overlay" onclick="toggleMenu()"></div>

    <!-- SIDEBAR MENU -->
    <div class="sidebar" id="sidebar">
        <div class="close-btn" onclick="toggleMenu()">&times;</div>
        <a href="#" class="menu-link">Beranda</a>
        <a href="#katalog" class="menu-link">Katalog Produk</a>
        <a href="#tentang" class="menu-link">Tentang Kami</a>
    </div>

    <section class="hero">
        <h2>Karya Autentik KedungDowo</h2>
        <p>Memberdayakan masyarakat melalui seni Batik Ciprat yang unik, bernilai tinggi, dan penuh makna. Setiap cipratan bercerita tentang harapan.</p>
    </section>

    <!-- KATALOG PRODUK -->
    <div class="container" id="katalog">
        <h2 class="section-title">Katalog Produk</h2>
        <p class="section-subtitle">Pilih mahakarya terbaik dari pengrajin lokal kami</p>

        <h3 class="category-title">Lembaran Kain Batik</h3>
        <div class="product-grid">
            
            <!-- PRODUK 1 -->
            <div class="product-card">
                <img src="kain1.jpg" alt="Kain Ciprat Klasik Sogan" class="product-image">
                <!-- QTY MELAYANG -->
                <div class="qty-container">
                    <button class="btn-qty-control" onclick="kurangQty('qty1')">-</button>
                    <input type="text" id="qty1" class="input-qty-display" value="1" readonly>
                    <button class="btn-qty-control" onclick="tambahQty('qty1')">+</button>
                </div>
                <div class="product-info">
                    <div>
                        <h3 class="product-title">Kain Ciprat Klasik Sogan</h3>
                        <p class="product-desc">Ukuran 2m x 1.15m. Bahan Katun Primisima, adem dan menyerap keringat.</p>
                    </div>
                    <div>
                        <div class="price-box">
                            <span class="price-original">Rp 250.000</span>
                        </div>
                        <button class="btn-buy" onclick="pesanWA('Kain Ciprat Klasik Sogan', 250000, 'qty1')">Pesan Sekarang</button>
                    </div>
                </div>
            </div>

            <!-- PRODUK 2 -->
            <div class="product-card">
                <img src="kain2.jpg" alt="Kain Ciprat Gradasi Senja" class="product-image">
                <div class="qty-container">
                    <button class="btn-qty-control" onclick="kurangQty('qty2')">-</button>
                    <input type="text" id="qty2" class="input-qty-display" value="1" readonly>
                    <button class="btn-qty-control" onclick="tambahQty('qty2')">+</button>
                </div>
                <div class="product-info">
                    <div>
                        <h3 class="product-title">Kain Ciprat Gradasi Senja</h3>
                        <p class="product-desc">Ukuran 2m x 1.15m. Warna lebih cerah dan modern, perpaduan jingga dan merah.</p>
                    </div>
                    <div>
                        <div class="price-box">
                            <span class="price-original">Rp 250.000</span>
                        </div>
                        <button class="btn-buy" onclick="pesanWA('Kain Ciprat Gradasi Senja', 250000, 'qty2')">Pesan Sekarang</button>
                    </div>
                </div>
            </div>

            <!-- PRODUK 3 -->
            <div class="product-card">
                <img src="kain3.jpg" alt="Kain Ciprat Alam Hijau" class="product-image">
                <div class="qty-container">
                    <button class="btn-qty-control" onclick="kurangQty('qty3')">-</button>
                    <input type="text" id="qty3" class="input-qty-display" value="1" readonly>
                    <button class="btn-qty-control" onclick="tambahQty('qty3')">+</button>
                </div>
                <div class="product-info">
                    <div>
                        <h3 class="product-title">Kain Ciprat Alam Hijau</h3>
                        <p class="product-desc">Ukuran 2m x 1.15m. Nuansa hijau alami yang memberikan kesan segar dan tenang.</p>
                    </div>
                    <div>
                        <div class="price-box">
                            <span class="price-original">Rp 250.000</span>
                        </div>
                        <button class="btn-buy" onclick="pesanWA('Kain Ciprat Alam Hijau', 250000, 'qty3')">Pesan Sekarang</button>
                    </div>
                </div>
            </div>

            <!-- PRODUK 4 -->
            <div class="product-card">
                <img src="kain4.jpg" alt="Kain Ciprat Langit Biru" class="product-image">
                <div class="qty-container">
                    <button class="btn-qty-control" onclick="kurangQty('qty4')">-</button>
                    <input type="text" id="qty4" class="input-qty-display" value="1" readonly>
                    <button class="btn-qty-control" onclick="tambahQty('qty4')">+</button>
                </div>
                <div class="product-info">
                    <div>
                        <h3 class="product-title">Kain Ciprat Langit Biru</h3>
                        <p class="product-desc">Ukuran 2m x 1.15m. Warna biru cerah yang elegan, cocok untuk seragam kantor.</p>
                    </div>
                    <div>
                        <div class="price-box">
                            <span class="price-original">Rp 250.000</span>
                        </div>
                        <button class="btn-buy" onclick="pesanWA('Kain Ciprat Langit Biru', 250000, 'qty4')">Pesan Sekarang</button>
                    </div>
                </div>
            </div>

            <!-- PRODUK 5 -->
            <div class="product-card">
                <img src="kain5.jpg" alt="Kain Ciprat Malam Kelam" class="product-image">
                <div class="qty-container">
                    <button class="btn-qty-control" onclick="kurangQty('qty5')">-</button>
                    <input type="text" id="qty5" class="input-qty-display" value="1" readonly>
                    <button class="btn-qty-control" onclick="tambahQty('qty5')">+</button>
                </div>
                <div class="product-info">
                    <div>
                        <h3 class="product-title">Kain Ciprat Malam Kelam</h3>
                        <p class="product-desc">Ukuran 2m x 1.15m. Dasar warna gelap dengan cipratan kontras yang mewah.</p>
                    </div>
                    <div>
                        <div class="price-box">
                            <span class="price-original">Rp 250.000</span>
                        </div>
                        <button class="btn-buy" onclick="pesanWA('Kain Ciprat Malam Kelam', 250000, 'qty5')">Pesan Sekarang</button>
                    </div>
                </div>
            </div>

            <!-- PRODUK 6 -->
            <div class="product-card">
                <img src="kain6.jpg" alt="Kain Ciprat Merah Delima" class="product-image">
                <div class="qty-container">
                    <button class="btn-qty-control" onclick="kurangQty('qty6')">-</button>
                    <input type="text" id="qty6" class="input-qty-display" value="1" readonly>
                    <button class="btn-qty-control" onclick="tambahQty('qty6')">+</button>
                </div>
                <div class="product-info">
                    <div>
                        <h3 class="product-title">Kain Ciprat Merah Delima</h3>
                        <p class="product-desc">Ukuran 2m x 1.15m. Corak merah berani yang memancarkan energi positif.</p>
                    </div>
                    <div>
                        <div class="price-box">
                            <span class="price-original">Rp 250.000</span>
                        </div>
                        <button class="btn-buy" onclick="pesanWA('Kain Ciprat Merah Delima', 250000, 'qty6')">Pesan Sekarang</button>
                    </div>
                </div>
            </div>

            <!-- PRODUK 7 -->
            <div class="product-card">
                <img src="kain7.jpg" alt="Kain Ciprat Kopi Susu" class="product-image">
                <div class="qty-container">
                    <button class="btn-qty-control" onclick="kurangQty('qty7')">-</button>
                    <input type="text" id="qty7" class="input-qty-display" value="1" readonly>
                    <button class="btn-qty-control" onclick="tambahQty('qty7')">+</button>
                </div>
                <div class="product-info">
                    <div>
                        <h3 class="product-title">Kain Ciprat Kopi Susu</h3>
                        <p class="product-desc">Ukuran 2m x 1.15m. Perpaduan warna krem dan coklat muda yang kalem.</p>
                    </div>
                    <div>
                        <div class="price-box">
                            <span class="price-original">Rp 250.000</span>
                        </div>
                        <button class="btn-buy" onclick="pesanWA('Kain Ciprat Kopi Susu', 250000, 'qty7')">Pesan Sekarang</button>
                    </div>
                </div>
            </div>

            <!-- PRODUK 8 -->
            <div class="product-card">
                <img src="kain8.jpg" alt="Kain Ciprat Tanah Liat" class="product-image">
                <div class="qty-container">
                    <button class="btn-qty-control" onclick="kurangQty('qty8')">-</button>
                    <input type="text" id="qty8" class="input-qty-display" value="1" readonly>
                    <button class="btn-qty-control" onclick="tambahQty('qty8')">+</button>
                </div>
                <div class="product-info">
                    <div>
                        <h3 class="product-title">Kain Ciprat Tanah Liat</h3>
                        <p class="product-desc">Ukuran 2m x 1.15m. Motif abstrak dengan warna dasar khas tanah liat Nusantara.</p>
                    </div>
                    <div>
                        <div class="price-box">
                            <span class="price-original">Rp 250.000</span>
                        </div>
                        <button class="btn-buy" onclick="pesanWA('Kain Ciprat Tanah Liat', 250000, 'qty8')">Pesan Sekarang</button>
                    </div>
                </div>
            </div>

            <!-- PRODUK 9 -->
            <div class="product-card">
                <img src="kain9.jpg" alt="Kain Ciprat Embun Pagi" class="product-image">
                <div class="qty-container">
                    <button class="btn-qty-control" onclick="kurangQty('qty9')">-</button>
                    <input type="text" id="qty9" class="input-qty-display" value="1" readonly>
                    <button class="btn-qty-control" onclick="tambahQty('qty9')">+</button>
                </div>
                <div class="product-info">
                    <div>
                        <h3 class="product-title">Kain Ciprat Embun Pagi</h3>
                        <p class="product-desc">Ukuran 2m x 1.15m. Dominasi warna putih bersih dengan cipratan tipis yang memukau.</p>
                    </div>
                    <div>
                        <div class="price-box">
                            <span class="price-original">Rp 250.000</span>
                        </div>
                        <button class="btn-buy" onclick="pesanWA('Kain Ciprat Embun Pagi', 250000, 'qty9')">Pesan Sekarang</button>
                    </div>
                </div>
            </div>

            <!-- PRODUK 10 -->
            <div class="product-card">
                <img src="kain10.jpg" alt="Kain Ciprat Senja Jingga" class="product-image">
                <div class="qty-container">
                    <button class="btn-qty-control" onclick="kurangQty('qty10')">-</button>
                    <input type="text" id="qty10" class="input-qty-display" value="1" readonly>
                    <button class="btn-qty-control" onclick="tambahQty('qty10')">+</button>
                </div>
                <div class="product-info">
                    <div>
                        <h3 class="product-title">Kain Ciprat Senja Jingga</h3>
                        <p class="product-desc">Ukuran 2m x 1.15m. Warna oranye pekat berpadu dengan cipratan hitam dramatis.</p>
                    </div>
                    <div>
                        <div class="price-box">
                            <span class="price-original">Rp 250.000</span>
                        </div>
                        <button class="btn-buy" onclick="pesanWA('Kain Ciprat Senja Jingga', 250000, 'qty10')">Pesan Sekarang</button>
                    </div>
                </div>
            </div>

        </div>
    </div>

    <!-- FOOTER -->
    <footer id="tentang">
        <h3 style="margin-bottom: 10px;">Batik Ciprat RUBI</h3>
        <p class="footer-desc">Produk kebanggaan warga Desa KedungDowo. Dikelola langsung oleh pengrajin lokal dan didukung oleh Mahasiswa KKN. Setiap pembelian Anda sangat berarti bagi pengembangan ekonomi masyarakat kami.</p>
        
        <div style="display:flex; justify-content:center; align-items:center; gap:15px; margin-bottom:15px;">
            <span>Dukung kami di:</span>
            <!-- Ganti link dengan Instagram desa atau KKN -->
            <a href="https://www.instagram.com/akun_desa_atau_kkn/" target="_blank">
                 <svg class="social-icon" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24">
                    <path d="M12 2.163c3.204 0 3.584.012 4.85.07 3.252.148 4.771 1.691 4.919 4.919.058 1.265.069 1.645.069 4.85s-.012 3.584-.07 4.85c-.148 3.252-1.691 4.771-4.919 4.919-1.265.058-1.645.069-4.85.069s-3.584-.012-4.85-.07c-3.252-.148-4.771-1.691-4.919-4.919-.058-1.265-.069-1.645-.069-4.85s.012-3.584.07-4.85c.148-3.252 1.691-4.771 4.919-4.919 1.265-.058 1.645-.069 4.85-.069zm0-2.163c-3.259 0-3.667.014-4.947.072-4.358.2-6.78 2.618-6.98 6.98-.059 1.281-.073 1.689-.073 4.948 0 3.259.014 3.668.072 4.948.2 4.358 2.618 6.78 6.98 6.98 1.281.058 1.689.072 4.948.072 3.259 0 3.668-.014 4.948-.072 4.354-.2 6.782-2.618 6.979-6.98.059-1.28.073-1.689.073-4.948 0-3.259-.014-3.667-.072-4.947-.196-4.354-2.617-6.78-6.979-6.98-1.281-.059-1.69-.073-4.949-.073zm0 5.838c-3.403 0-6.162 2.759-6.162 6.162s2.759 6.163 6.162 6.163 6.162-2.759 6.162-6.163c0-3.403-2.759-6.162-6.162-6.162zm0 10.162c-2.209 0-4-1.79-4-4 0-2.209 1.79-4 4-4s4 1.791 4 4c0 2.21-1.791 4-4 4zm6.406-11.845c-.796 0-1.441.645-1.441 1.44s.645 1.44 1.441 1.44c.795 0 1.439-.645 1.439-1.44s-.644-1.44-1.439-1.44z"/>
                 </svg>
            </a>
        </div>
        <p>&copy; 2026 Batik Ciprat RUBI - Desa KedungDowo.</p>
    </footer>

    <script>
        /* FUNGSI MENU */
        function toggleMenu() {
            document.getElementById('sidebar').classList.toggle('active');
            document.getElementById('overlay').classList.toggle('active');
        }

        /* FUNGSI QTY */
        function tambahQty(id) {
            let input = document.getElementById(id);
            input.value = parseInt(input.value) + 1;
        }
        function kurangQty(id) {
            let input = document.getElementById(id);
            if (parseInt(input.value) > 1) {
                input.value = parseInt(input.value) - 1;
            }
        }

        /* FUNGSI PESAN WHATSAPP (DENGAN KALKULASI QTY) */
        function pesanWA(namaProduk, hargaSatuan, idQty) {
            // Ambil jumlah pesanan dari kotak input
            let qty = parseInt(document.getElementById(idQty).value);
            
            // Hitung total harga
            let totalAkhir = hargaSatuan * qty;

            const nomorWA = "6287888227567"; 
            
            let pesan = `Halo Admin Batik RUBI, P MESEN WOK:\n\n`;
            pesan += `*${qty}x ${namaProduk}*\n`;
            pesan += `Harga Satuan: Rp ${hargaSatuan.toLocaleString('id-ID')}\n`;
            pesan += `*TOTAL BAYAR: Rp ${totalAkhir.toLocaleString('id-ID')}*\n\n`;
            pesan += `Apakah stoknya masih tersedia?`;

            window.open(`https://wa.me/${nomorWA}?text=${encodeURIComponent(pesan)}`, '_blank');
        }
    </script>

</body>
</html>
