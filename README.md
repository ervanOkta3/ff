<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portofolio Saya - Ervan Okta Alipiandi</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
        }
        /* Custom scrollbar for better aesthetics (optional) */
        ::-webkit-scrollbar {
            width: 8px;
        }
        ::-webkit-scrollbar-track {
            background: #f1f1f1;
        }
        ::-webkit-scrollbar-thumb {
            background: #888;
            border-radius: 4px;
        }
        ::-webkit-scrollbar-thumb:hover {
            background: #555;
        }
        .profile-img-container {
            width: 180px; /* Ukuran kontainer foto profil */
            height: 180px;
            overflow: hidden;
            border-radius: 50%;
            margin: 0 auto 1.5rem; /* Tengah dan beri jarak bawah */
            box-shadow: 0 10px 15px -3px rgba(0, 0, 0, 0.1), 0 4px 6px -2px rgba(0, 0, 0, 0.05);
            border: 4px solid white;
        }
        .profile-img {
            width: 100%;
            height: 100%;
            object-fit: cover; /* Memastikan gambar mengisi kontainer tanpa distorsi */
        }
        .section-card {
            background-color: white;
            border-radius: 0.75rem; /* 12px */
            padding: 1.5rem; /* 24px */
            margin-bottom: 1.5rem; /* 24px */
            box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.1), 0 2px 4px -1px rgba(0, 0, 0, 0.06);
        }
        .nav-link {
            transition: color 0.3s ease;
        }
        .nav-link:hover {
            color: #3b82f6; /* Tailwind's blue-500 */
        }
        /* Smooth scrolling */
        html {
            scroll-behavior: smooth;
        }
    </style>
</head>
<body class="bg-gray-100 text-gray-800">

    <!-- Container Utama -->
    <div class="container mx-auto max-w-6xl p-4 md:p-8">
        <div class="md:flex md:space-x-8">

            <!-- Kolom Profil (Samping Kiri di Desktop) -->
            <aside class="md:w-1/3 lg:w-1/4 mb-8 md:mb-0 md:sticky md:top-8 self-start">
                <div class="bg-white p-6 rounded-xl shadow-lg text-center">
                    <div class="profile-img-container">
                        <!-- Pastikan nama file foto sesuai -->
                        <img src="IMG_20250425_170303.jpg" alt="Foto Profil Ervan Okta Alipiandi" class="profile-img">
                    </div>
                    <h1 class="text-3xl font-bold text-gray-900 mb-2">Ervan Okta Alipiandi</h1>
                    <p class="text-gray-600 text-lg mb-4">Pelajar / Web Developer / Lainnya</p>

                    <!-- Navigasi Internal -->
                    <nav class="mb-6">
                        <ul class="space-y-2">
                            <li><a href="#tentang" class="block py-2 px-3 text-gray-700 hover:bg-blue-500 hover:text-white rounded-md nav-link text-left">Tentang Saya</a></li>
                            <li><a href="#keahlian" class="block py-2 px-3 text-gray-700 hover:bg-blue-500 hover:text-white rounded-md nav-link text-left">Keahlian</a></li>
                            <li><a href="#proyek" class="block py-2 px-3 text-gray-700 hover:bg-blue-500 hover:text-white rounded-md nav-link text-left">Proyek</a></li>
                            <li><a href="#kontak" class="block py-2 px-3 text-gray-700 hover:bg-blue-500 hover:text-white rounded-md nav-link text-left">Kontak</a></li>
                        </ul>
                    </nav>

                    <!-- Ikon Sosial Media (Contoh) -->
                    <div class="flex justify-center space-x-4">
                        <a href="#" class="text-gray-500 hover:text-blue-600 transition-colors">
                            <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 24 24" aria-hidden="true"><path fill-rule="evenodd" d="M22 12c0-5.523-4.477-10-10-10S2 6.477 2 12c0 4.991 3.657 9.128 8.438 9.878v-6.987h-2.54V12h2.54V9.797c0-2.506 1.492-3.89 3.777-3.89 1.094 0 2.238.195 2.238.195v2.46h-1.26c-1.243 0-1.63.771-1.63 1.562V12h2.773l-.443 2.89h-2.33v6.988C18.343 21.128 22 16.991 22 12z" clip-rule="evenodd" /></svg>
                            <span class="sr-only">Facebook</span>
                        </a>
                        <a href="#" class="text-gray-500 hover:text-sky-500 transition-colors">
                            <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 24 24" aria-hidden="true"><path d="M8.29 20.251c7.547 0 11.675-6.253 11.675-11.675 0-.178 0-.355-.012-.53A8.348 8.348 0 0022 5.92a8.19 8.19 0 01-2.357.646 4.118 4.118 0 001.804-2.27 8.224 8.224 0 01-2.605.996 4.107 4.107 0 00-6.993 3.743 11.65 11.65 0 01-8.457-4.287 4.106 4.106 0 001.27 5.477A4.072 4.072 0 012.8 9.713v.052a4.105 4.105 0 003.292 4.022 4.095 4.095 0 01-1.853.07 4.108 4.108 0 003.834 2.85A8.233 8.233 0 012 18.407a11.616 11.616 0 006.29 1.84" /></svg>
                            <span class="sr-only">Twitter</span>
                        </a>
                        <a href="#" class="text-gray-500 hover:text-pink-600 transition-colors">
                            <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 24 24" aria-hidden="true"><path fill-rule="evenodd" d="M12.315 2c2.43 0 2.784.013 3.808.06 1.064.049 1.791.218 2.427.465a4.902 4.902 0 011.772 1.153 4.902 4.902 0 011.153 1.772c.247.636.416 1.363.465 2.427.048 1.024.06 1.378.06 3.808s-.012 2.784-.06 3.808c-.049 1.064-.218 1.791-.465 2.427a4.902 4.902 0 01-1.153 1.772 4.902 4.902 0 01-1.772 1.153c-.636.247-1.363.416-2.427.465-1.024.048-1.378.06-3.808.06s-2.784-.013-3.808-.06c-1.064-.049-1.791-.218-2.427-.465a4.902 4.902 0 01-1.772-1.153 4.902 4.902 0 01-1.153-1.772c-.247-.636-.416-1.363-.465-2.427-.048-1.024-.06-1.378-.06-3.808s.012-2.784.06-3.808c.049-1.064.218-1.791.465-2.427a4.902 4.902 0 011.153-1.772A4.902 4.902 0 016.028 4.53c.636-.247 1.363-.416 2.427-.465C9.53 2.013 9.884 2 12.315 2zm0 1.623c-2.372 0-2.686.009-3.637.053-.877.04-.148.185-1.996.437-.746.23-1.226.526-1.623.922-.398.398-.693.877-.922 1.623-.25.518-.397 1.12-.437 1.996-.044.95-.053 1.265-.053 3.637s.009 2.686.053 3.637c.04.877.185 1.48.437 1.996.23.746.526 1.226.922 1.623.398.398.877.693 1.623.922.518.25 1.12.397 1.996.437.95.044 1.265.053 3.637.053s2.686-.009 3.637-.053c.877-.04 1.48-.185 1.996-.437.746-.23 1.226-.526 1.623-.922.398-.398-.693-.877-.922-1.623.25-.518.397-1.12.437-1.996.044-.95.053-1.265.053-3.637s-.009-2.686-.053-3.637c-.04-.877-.185-1.48-.437-1.996-.23-.746-.526-1.226-.922-1.623-.398-.398-.877-.693-1.623-.922-.518-.25-1.12-.397-1.996-.437-.95-.044-1.265-.053-3.637-.053zM12 16a4 4 0 110-8 4 4 0 010 8zm0-1.623a2.377 2.377 0 100-4.754 2.377 2.377 0 000 4.754zM16.338 7.623a1.2 1.2 0 110-2.4 1.2 1.2 0 010 2.4z" clip-rule="evenodd" /></svg>
                            <span class="sr-only">Instagram</span>
                        </a>
                         <a href="#" class="text-gray-500 hover:text-gray-900 transition-colors">
                            <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 24 24" aria-hidden="true"><path fill-rule="evenodd" d="M12 2C6.477 2 2 6.484 2 12.017c0 4.425 2.865 8.18 6.839 9.504.5.092.682-.217.682-.483 0-.237-.008-.868-.013-1.703-2.782.605-3.369-1.343-3.369-1.343-.454-1.158-1.11-1.466-1.11-1.466-.908-.62.069-.608.069-.608 1.003.07 1.531 1.032 1.531 1.032.892 1.53 2.341 1.088 2.91.832.092-.647.35-1.088.636-1.338-2.22-.253-4.555-1.113-4.555-4.951 0-1.093.39-1.988 1.029-2.688-.103-.253-.446-1.272.098-2.65 0 0 .84-.27 2.75 1.026A9.564 9.564 0 0112 6.82c.85.004 1.705.115 2.504.337 1.909-1.296 2.747-1.027 2.747-1.027.546 1.378.201 2.398.1 2.651.64.7 1.028 1.595 1.028 2.688 0 3.848-2.339 4.695-4.566 4.943.359.308.678.92.678 1.855 0 1.338-.012 2.419-.012 2.747 0 .268.18.58.688.482A10.001 10.001 0 0022 12.017C22 6.484 17.522 2 12 2z" clip-rule="evenodd" /></svg>
                            <span class="sr-only">GitHub</span>
                        </a>
                    </div>
                </div>
            </aside>

            <!-- Kolom Konten Utama (Samping Kanan di Desktop) -->
            <main class="md:w-2/3 lg:w-3/4">
                <!-- Bagian Tentang Saya -->
                <section id="tentang" class="section-card">
                    <h2 class="text-2xl font-semibold text-blue-600 mb-4">Tentang Saya</h2>
                    <p class="text-gray-700 leading-relaxed mb-3">
                        Halo! Saya Ervan Okta Alipiandi, seorang [Status/Profesi Anda, misal: pelajar yang antusias, calon pengembang web] dengan minat besar pada [Sebutkan Minat Utama Anda, misal: teknologi, desain, seni, literasi]. Saat ini saya sedang fokus untuk mempelajari dan mengembangkan kemampuan saya di bidang [Sebutkan Bidang Fokus, misal: pengembangan front-end, penulisan kreatif, analisis data].
                    </p>
                    <p class="text-gray-700 leading-relaxed">
                        Saya percaya bahwa belajar adalah proses seumur hidup dan saya selalu mencari kesempatan baru untuk tumbuh dan berkontribusi. Di luar kegiatan akademis/profesional, saya juga menikmati [Sebutkan Hobi atau Kegiatan Lain, misal: membaca buku fiksi ilmiah, bermain musik, hiking].
                    </p>
                </section>

                <!-- Bagian Keahlian -->
                <section id="keahlian" class="section-card">
                    <h2 class="text-2xl font-semibold text-blue-600 mb-6">Keahlian Saya</h2>
                    <div class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-4 gap-4">
                        <!-- Contoh Keahlian Item -->
                        <div class="bg-blue-50 p-4 rounded-lg text-center hover:shadow-md transition-shadow">
                            <h3 class="font-semibold text-blue-700">HTML5</h3>
                        </div>
                        <div class="bg-green-50 p-4 rounded-lg text-center hover:shadow-md transition-shadow">
                            <h3 class="font-semibold text-green-700">CSS3</h3>
                        </div>
                        <div class="bg-yellow-50 p-4 rounded-lg text-center hover:shadow-md transition-shadow">
                            <h3 class="font-semibold text-yellow-700">JavaScript</h3>
                        </div>
                        <div class="bg-purple-50 p-4 rounded-lg text-center hover:shadow-md transition-shadow">
                            <h3 class="font-semibold text-purple-700">Tailwind CSS</h3>
                        </div>
                        <div class="bg-red-50 p-4 rounded-lg text-center hover:shadow-md transition-shadow">
                            <h3 class="font-semibold text-red-700">Desain Grafis</h3>
                        </div>
                        <div class="bg-indigo-50 p-4 rounded-lg text-center hover:shadow-md transition-shadow">
                            <h3 class="font-semibold text-indigo-700">Menulis Kreatif</h3>
                        </div>
                        <!-- Tambahkan keahlian lainnya sesuai kebutuhan -->
                    </div>
                </section>

                <!-- Bagian Proyek -->
                <section id="proyek" class="section-card">
                    <h2 class="text-2xl font-semibold text-blue-600 mb-6">Proyek Unggulan</h2>
                    <div class="space-y-6">
                        <!-- Proyek Item 1 -->
                        <div class="bg-gray-50 p-6 rounded-lg hover:shadow-lg transition-shadow">
                            <h3 class="text-xl font-semibold text-gray-800 mb-2">Development Game</h3>
                            <p class="text-gray-600 mb-3">
                                Deskripsi singkat tentang proyek development game ini. Jelaskan tujuan, teknologi yang digunakan (misalnya Unity, Unreal Engine, Godot, Phaser.js), dan peran Anda dalam proyek tersebut. Apakah ini game 2D atau 3D? Genre apa?
                            </p>
                            <a href="#" class="text-blue-500 hover:text-blue-700 font-medium">Lihat Detail Proyek &rarr;</a>
                        </div>
                        <!-- Proyek Item 2 -->
                        <div class="bg-gray-50 p-6 rounded-lg hover:shadow-lg transition-shadow">
                            <h3 class="text-xl font-semibold text-gray-800 mb-2">Buat App</h3>
                            <p class="text-gray-600 mb-3">
                                Ini adalah proyek pembuatan aplikasi. Jelaskan jenis aplikasinya (misalnya mobile, web, desktop), teknologi yang digunakan (misalnya React Native, Flutter, Swift, Kotlin, Node.js, Python Django/Flask), dan fitur utama aplikasi tersebut.
                            </p>
                            <a href="#" class="text-blue-500 hover:text-blue-700 font-medium">Lihat Kode di GitHub &rarr;</a>
                        </div>
                        <!-- Tambahkan proyek lainnya -->
                    </div>
                </section>

                <!-- Bagian Kontak -->
                <section id="kontak" class="section-card">
                    <h2 class="text-2xl font-semibold text-blue-600 mb-6">Hubungi Saya</h2>
                    <p class="text-gray-700 mb-4">
                        Saya selalu terbuka untuk diskusi, kolaborasi, atau sekadar bertukar sapa. Jangan ragu untuk menghubungi saya melalui:
                    </p>
                    <ul class="space-y-3">
                        <li class="flex items-center">
                            <svg class="w-5 h-5 text-blue-500 mr-3" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"></path></svg>
                            <a href="mailto:emailanda@example.com" class="text-gray-700 hover:text-blue-600">emailanda@example.com</a>
                        </li>
                        <li class="flex items-center">
                             <svg class="w-5 h-5 text-blue-500 mr-3" fill="currentColor" viewBox="0 0 24 24" aria-hidden="true"><path fill-rule="evenodd" d="M12.315 2c2.43 0 2.784.013 3.808.06 1.064.049 1.791.218 2.427.465a4.902 4.902 0 011.772 1.153 4.902 4.902 0 011.153 1.772c.247.636.416 1.363.465 2.427.048 1.024.06 1.378.06 3.808s-.012 2.784-.06 3.808c-.049 1.064-.218 1.791-.465 2.427a4.902 4.902 0 01-1.153 1.772 4.902 4.902 0 01-1.772 1.153c-.636.247-1.363.416-2.427.465-1.024.048-1.378.06-3.808.06s-2.784-.013-3.808-.06c-1.064-.049-1.791-.218-2.427-.465a4.902 4.902 0 01-1.772-1.153 4.902 4.902 0 01-1.153-1.772c-.247-.636-.416-1.363-.465-2.427-.048-1.024-.06-1.378-.06-3.808s.012-2.784.06-3.808c.049-1.064.218-1.791.465-2.427a4.902 4.902 0 011.153-1.772A4.902 4.902 0 016.028 4.53c.636-.247 1.363-.416 2.427-.465C9.53 2.013 9.884 2 12.315 2zm0 1.623c-2.372 0-2.686.009-3.637.053-.877.04-.148.185-1.996.437-.746.23-1.226.526-1.623.922-.398.398-.693.877-.922 1.623-.25.518-.397 1.12-.437 1.996-.044.95-.053 1.265-.053 3.637s.009 2.686.053 3.637c.04.877.185 1.48.437 1.996.23.746.526 1.226.922 1.623.398.398.877.693 1.623.922.518.25 1.12.397 1.996.437.95.044 1.265.053 3.637.053s2.686-.009 3.637-.053c.877-.04 1.48-.185 1.996-.437.746-.23 1.226-.526 1.623-.922.398-.398-.693-.877-.922-1.623.25-.518.397-1.12.437-1.996.044-.95.053-1.265.053-3.637s-.009-2.686-.053-3.637c-.04-.877-.185-1.48-.437-1.996-.23-.746-.526-1.226-.922-1.623-.398-.398-.877-.693-1.623-.922-.518-.25-1.12-.397-1.996-.437-.95-.044-1.265-.053-3.637-.053zM12 16a4 4 0 110-8 4 4 0 010 8zm0-1.623a2.377 2.377 0 100-4.754 2.377 2.377 0 000 4.754zM16.338 7.623a1.2 1.2 0 110-2.4 1.2 1.2 0 010 2.4z" clip-rule="evenodd" /></svg>
                            <a href="https://instagram.com/usernameanda" target="_blank" rel="noopener noreferrer" class="text-gray-700 hover:text-pink-600">Instagram: @usernameanda</a>
                        </li>
                        <!-- Tambahkan link LinkedIn, GitHub, dll. -->
                    </ul>
                </section>
            </main>
        </div>

        <!-- Footer -->
        <footer class="text-center mt-12 py-6 border-t border-gray-300">
            <p class="text-gray-600">&copy; <span id="currentYear"></span> Ervan Okta Alipiandi. Dibuat dengan <span class="text-red-500">&hearts;</span> dan Tailwind CSS.</p>
        </footer>
    </div>

    <script>
        // Untuk menampilkan tahun saat ini di footer
        document.getElementById('currentYear').textContent = new Date().getFullYear();
    </script>
</body>
</html>
