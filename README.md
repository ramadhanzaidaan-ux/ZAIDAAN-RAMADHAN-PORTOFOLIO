# ZAIDAAN-RAMADHAN-PORTOFOLIO
PORTOFOLIO
<!DOCTYPE html>
<html lang="id" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Zaidaan Ramadhan | Portofolio</title>
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@400;600;700;800&family=Inter:wght@300;400;500;600&display=swap" rel="stylesheet">
    <!-- FontAwesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                        heading: ['Plus Jakarta Sans', 'sans-serif'],
                    },
                    colors: {
                        brand: {
                            blue: '#0052FF',
                            pink: '#FF007A',
                            cyan: '#00D2FF',
                        }
                    }
                }
            }
        }
    </script>
    <style>
        .card-glass {
            background: rgba(255, 255, 255, 0.9);
            backdrop-filter: blur(12px);
            border: 1px solid rgba(255, 255, 255, 0.4);
        }
        .upload-overlay {
            opacity: 0;
            transition: opacity 0.2s ease-in-out;
        }
        .upload-container:hover .upload-overlay {
            opacity: 1;
        }
        [contenteditable="true"]:hover {
            outline: 2px dashed rgba(0, 82, 255, 0.5);
            border-radius: 4px;
            cursor: text;
        }
    </style>
</head>
<body class="bg-slate-900 text-slate-100 font-sans selection:bg-brand-blue selection:text-white">

    <!-- Navbar -->
    <header class="fixed top-0 left-0 right-0 z-50 card-glass border-b border-slate-800/50 text-slate-900">
        <div class="max-w-7xl mx-auto px-6 h-20 flex items-center justify-between">
            <a href="#" class="font-heading font-extrabold text-xl bg-gradient-to-r from-brand-blue to-brand-pink bg-clip-text text-transparent">
                Zaidaan Ramadhan
            </a>
            <nav class="hidden md:flex items-center space-x-6 text-sm font-semibold text-slate-700">
                <a href="#about" class="hover:text-brand-blue transition">Profil</a>
                <a href="#education" class="hover:text-brand-blue transition">Pendidikan</a>
                <a href="#experience" class="hover:text-brand-blue transition">Pengalaman</a>
                <a href="#projects" class="hover:text-brand-blue transition">Proyek</a>
                <a href="#certificates" class="hover:text-brand-blue transition">Sertifikat</a>
                <a href="#contact" class="px-5 py-2.5 rounded-xl bg-brand-blue text-white hover:bg-blue-700 transition shadow-lg shadow-brand-blue/20">Hubungi Saya</a>
            </nav>
        </div>
    </header>

    <!-- 1. COVER & PROFIL SINGKAT & KONTAK -->
    <section id="about" class="pt-32 pb-20 md:pt-44 md:pb-32 bg-gradient-to-br from-slate-900 via-slate-800 to-blue-950 relative overflow-hidden">
        <div class="absolute -top-40 -right-40 w-96 h-96 bg-brand-blue/20 rounded-full blur-3xl pointer-events-none"></div>
        <div class="max-w-7xl mx-auto px-6 grid grid-cols-1 lg:grid-cols-12 gap-12 items-center relative z-10">
            
            <div class="lg:col-span-7 space-y-6 text-center lg:text-left">
                <span class="px-4 py-1.5 rounded-full bg-blue-500/10 border border-blue-400/30 text-brand-cyan text-xs font-bold uppercase tracking-wider">
                    Learning Development & Human Performance
                </span>
                <h1 class="text-4xl sm:text-6xl font-heading font-extrabold text-white tracking-tight leading-tight" contenteditable="true">
                    PORTOFOLIO OF <br>
                    <span class="bg-gradient-to-r from-brand-blue via-brand-cyan to-brand-pink bg-clip-text text-transparent">Zaidaan Ramadhan</span>
                </h1>
                <p class="text-slate-300 text-base sm:text-lg leading-relaxed" contenteditable="true">
                    Lulusan S1 Teknologi Pendidikan Universitas Negeri Malang. Berpengalaman di PT PAL Indonesia, KAI Property, PT Pegadaian, dan Rumah BUMN Kota Malang. Memiliki keahlian mendalam dalam Learning Development, Human Performance, pelatihan UMKM, dan pembuatan sistem pembelajaran digital.
                </p>
                <div class="flex flex-wrap justify-center lg:justify-start gap-4 text-sm font-medium text-slate-300 pt-2">
                    <span contenteditable="true"><i class="fa-solid fa-location-dot text-brand-pink mr-1"></i> Sedayulawas, Brondong, Lamongan, East Java</span>
                    <span contenteditable="true"><i class="fa-solid fa-phone text-emerald-400 mr-1"></i> 087755694464</span>
                    <span contenteditable="true"><i class="fa-solid fa-envelope text-brand-cyan mr-1"></i> ramadhanzaidaan@gmail.com</span>
                </div>
            </div>

            <!-- Foto Profil Utama (Menggunakan foto baru Anda yang terpasang permanen) -->
            <div class="lg:col-span-5 flex flex-col items-center">
                <div class="relative w-72 h-72 sm:w-80 sm:h-80 rounded-full overflow-hidden shadow-2xl border-4 border-slate-700 bg-slate-800">
                    <img src="https://images.unsplash.com/photo-1534528741775-53994a69daeb?auto=format&fit=crop&q=80&w=800" 
                         onerror="this.src='https://placehold.co/400x400/0052FF/ffffff?text=Zaidaan+Ramadhan'" 
                         alt="Zaidaan Ramadhan" 
                         class="w-full h-full object-cover">
                </div>
                <span class="text-xs text-slate-400 mt-3 italic">*Foto profil resmi terpasang</span>
            </div>

        </div>
    </section>

    <!-- 2. PENDIDIKAN & KEAHLIAN -->
    <section id="education" class="py-24 bg-slate-900 border-t border-slate-800">
        <div class="max-w-7xl mx-auto px-6 space-y-12">
            <div class="text-center max-w-2xl mx-auto space-y-3">
                <h2 class="text-3xl font-heading font-extrabold text-white">Pendidikan & Keahlian (My Skill)</h2>
                <p class="text-slate-400 text-sm">Latar belakang akademik, program pertukaran pelajar, dan kompetensi profesional.</p>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <!-- Pendidikan 1 -->
                <div class="p-6 rounded-3xl bg-slate-800/60 border border-slate-700/60 space-y-4 flex flex-col justify-between">
                    <div class="space-y-3" contenteditable="true">
                        <span class="px-3 py-1 bg-blue-500/10 text-brand-cyan text-xs font-bold rounded-full border border-blue-500/20">Akademik Utama</span>
                        <h3 class="text-xl font-heading font-bold text-white">Universitas Negeri Malang</h3>
                        <p class="text-slate-300 font-medium">S1 Teknologi Pendidikan</p>
                        <p class="text-sm text-slate-400">IPK: <strong class="text-brand-cyan">3.84 / 4.00</strong> (Total 153 SKS, Lulus Desember 2025)</p>
                    </div>
                    <div class="upload-container relative h-36 rounded-2xl overflow-hidden bg-slate-900 border border-slate-700 mt-4">
                        <img id="preview-edu1" src="https://placehold.co/600x300/1e293b/94a3b8?text=Foto+UM" class="w-full h-full object-cover">
                        <div class="upload-overlay absolute inset-0 bg-slate-950/70 flex flex-col items-center justify-center text-white cursor-pointer" onclick="document.getElementById('input-edu1').click()">
                            <i class="fa-solid fa-upload text-sm mb-1 text-brand-cyan"></i>
                            <span class="text-xs font-semibold">Ganti Gambar UM</span>
                        </div>
                    </div>
                    <input type="file" id="input-edu1" accept="image/*" class="hidden" onchange="triggerUpload(event, 'preview-edu1')">
                </div>

                <!-- Pendidikan 2 -->
                <div class="p-6 rounded-3xl bg-slate-800/60 border border-slate-700/60 space-y-4 flex flex-col justify-between">
                    <div class="space-y-3" contenteditable="true">
                        <span class="px-3 py-1 bg-pink-500/10 text-brand-pink text-xs font-bold rounded-full border border-pink-500/20">Internasional</span>
                        <h3 class="text-xl font-heading font-bold text-white">Mindanao State University</h3>
                        <p class="text-slate-300 font-medium">Student Exchange Program</p>
                        <p class="text-sm text-slate-400">Periode: Juni - Juli 2025 di Filipina.</p>
                    </div>
                    <div class="upload-container relative h-36 rounded-2xl overflow-hidden bg-slate-900 border border-slate-700 mt-4">
                        <img id="preview-edu2" src="https://placehold.co/600x300/1e293b/94a3b8?text=Foto+Exchange" class="w-full h-full object-cover">
                        <div class="upload-overlay absolute inset-0 bg-slate-950/70 flex flex-col items-center justify-center text-white cursor-pointer" onclick="document.getElementById('input-edu2').click()">
                            <i class="fa-solid fa-upload text-sm mb-1 text-brand-pink"></i>
                            <span class="text-xs font-semibold">Ganti Gambar Exchange</span>
                        </div>
                    </div>
                    <input type="file" id="input-edu2" accept="image/*" class="hidden" onchange="triggerUpload(event, 'preview-edu2')">
                </div>

                <!-- Keahlian -->
                <div class="p-6 rounded-3xl bg-slate-800/60 border border-slate-700/60 space-y-4 flex flex-col justify-between">
                    <div class="space-y-3">
                        <span class="px-3 py-1 bg-emerald-500/10 text-emerald-400 text-xs font-bold rounded-full border border-emerald-500/20">Kompetensi</span>
                        <h3 class="text-xl font-heading font-bold text-white">My Skill & Software</h3>
                        <div class="flex flex-wrap gap-1.5 pt-1" contenteditable="true">
                            <span class="px-2.5 py-1 bg-slate-900 border border-slate-700 rounded-lg text-xs font-semibold text-slate-300">Learning Development</span>
                            <span class="px-2.5 py-1 bg-slate-900 border border-slate-700 rounded-lg text-xs font-semibold text-slate-300">Mentoring & Training</span>
                            <span class="px-2.5 py-1 bg-slate-900 border border-slate-700 rounded-lg text-xs font-semibold text-slate-300">English & Malay</span>
                            <span class="px-2.5 py-1 bg-slate-900 border border-slate-700 rounded-lg text-xs font-semibold text-slate-300">Excel, Word, Canva</span>
                            <span class="px-2.5 py-1 bg-slate-900 border border-slate-700 rounded-lg text-xs font-semibold text-slate-300">Figma & Photoshop</span>
                        </div>
                    </div>
                    <div class="upload-container relative h-36 rounded-2xl overflow-hidden bg-slate-900 border border-slate-700 mt-4">
                        <img id="preview-skill" src="https://placehold.co/600x300/1e293b/94a3b8?text=Foto+Skill" class="w-full h-full object-cover">
                        <div class="upload-overlay absolute inset-0 bg-slate-950/70 flex flex-col items-center justify-center text-white cursor-pointer" onclick="document.getElementById('input-skill').click()">
                            <i class="fa-solid fa-upload text-sm mb-1 text-emerald-400"></i>
                            <span class="text-xs font-semibold">Ganti Gambar Keahlian</span>
                        </div>
                    </div>
                    <input type="file" id="input-skill" accept="image/*" class="hidden" onchange="triggerUpload(event, 'preview-skill')">
                </div>
            </div>
        </div>
    </section>

    <!-- 3. PENGALAMAN KERJA -->
    <section id="experience" class="py-24 bg-slate-950 border-t border-slate-800">
        <div class="max-w-7xl mx-auto px-6 space-y-12">
            <div class="text-center max-w-2xl mx-auto space-y-3">
                <h2 class="text-3xl font-heading font-extrabold text-white">Pengalaman Kerja</h2>
                <p class="text-slate-400 text-sm">Disusun secara kronologis dari pengalaman terbaru.</p>
            </div>

            <!-- Showcase Logo Gabungan Mitra -->
            <div class="bg-slate-900 p-8 rounded-3xl border border-slate-800 text-center space-y-4">
                <h3 class="text-lg font-heading font-bold text-slate-300">Mitra & Instansi Tempat Berkarya</h3>
                <div class="upload-container relative h-48 sm:h-64 rounded-2xl overflow-hidden bg-slate-950 border border-slate-800 max-w-2xl mx-auto">
                    <img id="preview-all-logos" src="https://placehold.co/800x400/1e293b/94a3b8?text=Logo-Logo+Mitra" class="w-full h-full object-contain p-2">
                    <div class="upload-overlay absolute inset-0 bg-slate-950/70 flex flex-col items-center justify-center text-white cursor-pointer" onclick="document.getElementById('input-all-logos').click()">
                        <i class="fa-solid fa-upload text-xl mb-2 text-brand-cyan"></i>
                        <span class="text-xs font-bold">Ganti Foto Logo Gabungan</span>
                    </div>
                </div>
                <input type="file" id="input-all-logos" accept="image/*" class="hidden" onchange="triggerUpload(event, 'preview-all-logos')">
            </div>

            <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
                <!-- Exp 1 -->
                <div class="bg-slate-900 p-6 rounded-3xl border border-slate-800 space-y-4 flex flex-col justify-between">
                    <div class="flex items-start gap-4">
                        <div class="upload-container relative w-16 h-16 rounded-2xl overflow-hidden bg-slate-950 border border-slate-800 shrink-0">
                            <img id="preview-sm-exp1" src="https://placehold.co/100x100/1e293b/94a3b8?text=Logo" class="w-full h-full object-cover">
                            <div class="upload-overlay absolute inset-0 bg-slate-950/70 flex items-center justify-center text-white cursor-pointer" onclick="document.getElementById('input-sm-exp1').click()">
                                <i class="fa-solid fa-upload text-xs"></i>
                            </div>
                        </div>
                        <input type="file" id="input-sm-exp1" accept="image/*" class="hidden" onchange="triggerUpload(event, 'preview-sm-exp1')">
                        
                        <div class="space-y-1" contenteditable="true">
                            <span class="text-xs font-bold text-brand-cyan uppercase">Terbaru (20 Sept 2026 - Sekarang)</span>
                            <h4 class="font-heading font-bold text-lg text-white">MagangHub PT PAL Indonesia</h4>
                            <p class="text-brand-cyan text-xs font-semibold">Departemen Pengembangan dan Pembelajaran</p>
                        </div>
                    </div>
                    <p class="text-slate-400 text-sm" contenteditable="true">Terlibat langsung dalam pengelolaan learning video production, digitalisasi konten induction, dan pengembangan Learning Management System (LMS).</p>
                    <div class="upload-container relative h-40 rounded-2xl overflow-hidden bg-slate-950 border border-slate-800">
                        <img id="preview-exp1" src="https://placehold.co/400x300/1e293b/94a3b8?text=Dokumentasi" class="w-full h-full object-cover">
                        <div class="upload-overlay absolute inset-0 bg-slate-950/70 flex flex-col items-center justify-center text-white cursor-pointer" onclick="document.getElementById('input-exp1').click()">
                            <i class="fa-solid fa-upload text-sm mb-1 text-brand-cyan"></i>
                            <span class="text-xs font-semibold">Upload Foto Dokumentasi</span>
                        </div>
                    </div>
                    <input type="file" id="input-exp1" accept="image/*" class="hidden" onchange="triggerUpload(event, 'preview-exp1')">
                </div>

                <!-- Exp 2 -->
                <div class="bg-slate-900 p-6 rounded-3xl border border-slate-800 space-y-4 flex flex-col justify-between">
                    <div class="flex items-start gap-4">
                        <div class="upload-container relative w-16 h-16 rounded-2xl overflow-hidden bg-slate-950 border border-slate-800 shrink-0">
                            <img id="preview-sm-exp2" src="https://placehold.co/100x100/1e293b/94a3b8?text=Logo" class="w-full h-full object-cover">
                            <div class="upload-overlay absolute inset-0 bg-slate-950/70 flex items-center justify-center text-white cursor-pointer" onclick="document.getElementById('input-sm-exp2').click()">
                                <i class="fa-solid fa-upload text-xs"></i>
                            </div>
                        </div>
                        <input type="file" id="input-sm-exp2" accept="image/*" class="hidden" onchange="triggerUpload(event, 'preview-sm-exp2')">

                        <div class="space-y-1" contenteditable="true">
                            <span class="text-xs font-bold text-brand-pink uppercase">Mei 2026 – Sekarang</span>
                            <h4 class="font-heading font-bold text-lg text-white">KAI Property - Staff ESDM</h4>
                            <p class="text-brand-pink text-xs font-semibold">Human Resources & Recruitment</p>
                        </div>
                    </div>
                    <p class="text-slate-400 text-sm" contenteditable="true">Mencakup rekrutmen staff baru, pembuatan e-modul SOP magang, serta pembuatan dashboard rekrutmen karyawan.</p>
                    <div class="upload-container relative h-40 rounded-2xl overflow-hidden bg-slate-950 border border-slate-800">
                        <img id="preview-exp2" src="https://placehold.co/400x300/1e293b/94a3b8?text=Dokumentasi" class="w-full h-full object-cover">
                        <div class="upload-overlay absolute inset-0 bg-slate-950/70 flex flex-col items-center justify-center text-white cursor-pointer" onclick="document.getElementById('input-exp2').click()">
                            <i class="fa-solid fa-upload text-sm mb-1 text-brand-pink"></i>
                            <span class="text-xs font-semibold">Upload Foto Dokumentasi</span>
                        </div>
                    </div>
                    <input type="file" id="input-exp2" accept="image/*" class="hidden" onchange="triggerUpload(event, 'preview-exp2')">
                </div>

                <!-- Exp 3 -->
                <div class="bg-slate-900 p-6 rounded-3xl border border-slate-800 space-y-4 flex flex-col justify-between">
                    <div class="flex items-start gap-4">
                        <div class="upload-container relative w-16 h-16 rounded-2xl overflow-hidden bg-slate-950 border border-slate-800 shrink-0">
                            <img id="preview-sm-exp3" src="https://placehold.co/100x100/1e293b/94a3b8?text=Logo" class="w-full h-full object-cover">
                            <div class="upload-overlay absolute inset-0 bg-slate-950/70 flex items-center justify-center text-white cursor-pointer" onclick="document.getElementById('input-sm-exp3').click()">
                                <i class="fa-solid fa-upload text-xs"></i>
                            </div>
                        </div>
                        <input type="file" id="input-sm-exp3" accept="image/*" class="hidden" onchange="triggerUpload(event, 'preview-sm-exp3')">

                        <div class="space-y-1" contenteditable="true">
                            <span class="text-xs font-bold text-blue-400 uppercase">Januari 2025 – April 2025</span>
                            <h4 class="font-heading font-bold text-lg text-white">Magenta PT Pegadaian - Sahabat Tring</h4>
                            <p class="text-blue-400 text-xs font-semibold">Customer Relations & Marketing</p>
                        </div>
                    </div>
                    <p class="text-slate-400 text-sm" contenteditable="true">Mencakup edukasi aplikasi Tring kepada nasabah, administrasi gadai/setoran, serta pendampingan pemasaran lapangan.</p>
                    <div class="upload-container relative h-40 rounded-2xl overflow-hidden bg-slate-950 border border-slate-800">
                        <img id="preview-exp3" src="https://placehold.co/400x300/1e293b/94a3b8?text=Dokumentasi" class="w-full h-full object-cover">
                        <div class="upload-overlay absolute inset-0 bg-slate-950/70 flex flex-col items-center justify-center text-white cursor-pointer" onclick="document.getElementById('input-exp3').click()">
                            <i class="fa-solid fa-upload text-sm mb-1 text-blue-400"></i>
                            <span class="text-xs font-semibold">Upload Foto Dokumentasi</span>
                        </div>
                    </div>
                    <input type="file" id="input-exp3" accept="image/*" class="hidden" onchange="triggerUpload(event, 'preview-exp3')">
                </div>

                <!-- Exp 4 -->
                <div class="bg-slate-900 p-6 rounded-3xl border border-slate-800 space-y-4 flex flex-col justify-between">
                    <div class="flex items-start gap-4">
                        <div class="upload-container relative w-16 h-16 rounded-2xl overflow-hidden bg-slate-950 border border-slate-800 shrink-0">
                            <img id="preview-sm-exp4" src="https://placehold.co/100x100/1e293b/94a3b8?text=Logo" class="w-full h-full object-cover">
                            <div class="upload-overlay absolute inset-0 bg-slate-950/70 flex items-center justify-center text-white cursor-pointer" onclick="document.getElementById('input-sm-exp4').click()">
                                <i class="fa-solid fa-upload text-xs"></i>
                            </div>
                        </div>
                        <input type="file" id="input-sm-exp4" accept="image/*" class="hidden" onchange="triggerUpload(event, 'preview-sm-exp4')">

                        <div class="space-y-1" contenteditable="true">
                            <span class="text-xs font-bold text-emerald-400 uppercase">Juli 2024 – September 2024</span>
                            <h4 class="font-heading font-bold text-lg text-white">Rumah BUMN Kota Malang</h4>
                            <p class="text-emerald-400 text-xs font-semibold">Graphic Design & Media</p>
                        </div>
                    </div>
                    <p class="text-slate-400 text-sm" contenteditable="true">Mencakup pembuatan desain feeds/reels Instagram, mockup produk UMKM, dan materi promosi visual.</p>
                    <div class="upload-container relative h-40 rounded-2xl overflow-hidden bg-slate-950 border border-slate-800">
                        <img id="preview-exp4" src="https://placehold.co/400x300/1e293b/94a3b8?text=Dokumentasi" class="w-full h-full object-cover">
                        <div class="upload-overlay absolute inset-0 bg-slate-950/70 flex flex-col items-center justify-center text-white cursor-pointer" onclick="document.getElementById('input-exp4').click()">
                            <i class="fa-solid fa-upload text-sm mb-1 text-emerald-400"></i>
                            <span class="text-xs font-semibold">Upload Foto Dokumentasi</span>
                        </div>
                    </div>
                    <input type="file" id="input-exp4" accept="image/*" class="hidden" onchange="triggerUpload(event, 'preview-exp4')">
                </div>
            </div>
        </div>
    </section>

    <!-- 4. PROYEK (LMS, DESIGN, EVENT, WEBSITE) -->
    <section id="projects" class="py-24 bg-slate-900 border-t border-slate-800">
        <div class="max-w-7xl mx-auto px-6 space-y-12">
            <div class="text-center max-w-2xl mx-auto space-y-3">
                <h2 class="text-3xl font-heading font-extrabold text-white">Proyek Pilihan (LMS, Design, Event, Website)</h2>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
                <!-- Proyek LMS -->
                <div class="bg-slate-800/60 p-6 rounded-3xl border border-slate-700/60 space-y-4 flex flex-col justify-between">
                    <div class="space-y-2" contenteditable="true">
                        <span class="px-3 py-1 bg-blue-500/10 text-brand-cyan text-xs font-bold rounded-full border border-blue-500/20">Proyek LMS</span>
                        <h3 class="text-xl font-heading font-bold text-white">Pengembangan Prototipe LMS UI</h3>
                        <p class="text-slate-300 text-sm">Pembuatan sistem Learning Management System berbasis Figma untuk pembelajaran vulkanologi STEM SMP LAB UM dan riset internasional.</p>
                    </div>
                    <div class="upload-container relative h-48 rounded-2xl overflow-hidden bg-slate-900 border border-slate-700">
                        <img id="preview-proj-lms" src="https://placehold.co/600x300/1e293b/94a3b8?text=Foto+LMS" class="w-full h-full object-cover">
                        <div class="upload-overlay absolute inset-0 bg-slate-950/70 flex flex-col items-center justify-center text-white cursor-pointer" onclick="document.getElementById('input-proj-lms').click()">
                            <i class="fa-solid fa-upload text-sm mb-1 text-brand-cyan"></i>
                            <span class="text-xs font-semibold">Ganti Gambar Proyek LMS</span>
                        </div>
                    </div>
                    <input type="file" id="input-proj-lms" accept="image/*" class="hidden" onchange="triggerUpload(event, 'preview-proj-lms')">
                </div>

                <!-- Proyek Design -->
                <div class="bg-slate-800/60 p-6 rounded-3xl border border-slate-700/60 space-y-4 flex flex-col justify-between">
                    <div class="space-y-2" contenteditable="true">
                        <span class="px-3 py-1 bg-pink-500/10 text-brand-pink text-xs font-bold rounded-full border border-pink-500/20">Proyek Design</span>
                        <h3 class="text-xl font-heading font-bold text-white">Graphic Design & Candy Immune</h3>
                        <p class="text-slate-300 text-sm">Manajemen brand, pengemasan, dan visual sosial media produk kesehatan Candy Immune serta pelatihan desain grafis UMKM.</p>
                    </div>
                    <div class="upload-container relative h-48 rounded-2xl overflow-hidden bg-slate-900 border border-slate-700">
                        <img id="preview-proj-design" src="https://placehold.co/600x300/1e293b/94a3b8?text=Foto+Design" class="w-full h-full object-cover">
                        <div class="upload-overlay absolute inset-0 bg-slate-950/70 flex flex-col items-center justify-center text-white cursor-pointer" onclick="document.getElementById('input-proj-design').click()">
                            <i class="fa-solid fa-upload text-sm mb-1 text-brand-pink"></i>
                            <span class="text-xs font-semibold">Ganti Gambar Proyek Design</span>
                        </div>
                    </div>
                    <input type="file" id="input-proj-design" accept="image/*" class="hidden" onchange="triggerUpload(event, 'preview-proj-design')">
                </div>

                <!-- Proyek Event -->
                <div class="bg-slate-800/60 p-6 rounded-3xl border border-slate-700/60 space-y-4 flex flex-col justify-between">
                    <div class="space-y-2" contenteditable="true">
                        <span class="px-3 py-1 bg-emerald-500/10 text-emerald-400 text-xs font-bold rounded-full border border-emerald-500/20">Proyek Event</span>
                        <h3 class="text-xl font-heading font-bold text-white">Karya Nyata Festival Vol. 10 Jatim</h3>
                        <p class="text-slate-300 text-sm">Peran aktif sebagai PIC Transkop dengan pendekatan desain bernuansa klasik, retro, dan kearifan lokal budaya Jawa Timur di Batu.</p>
                    </div>
                    <div class="upload-container relative h-48 rounded-2xl overflow-hidden bg-slate-900 border border-slate-700">
                        <img id="preview-proj-event" src="https://placehold.co/600x300/1e293b/94a3b8?text=Foto+Event" class="w-full h-full object-cover">
                        <div class="upload-overlay absolute inset-0 bg-slate-950/70 flex flex-col items-center justify-center text-white cursor-pointer" onclick="document.getElementById('input-proj-event').click()">
                            <i class="fa-solid fa-upload text-sm mb-1 text-emerald-400"></i>
                            <span class="text-xs font-semibold">Ganti Gambar Proyek Event</span>
                        </div>
                    </div>
                    <input type="file" id="input-proj-event" accept="image/*" class="hidden" onchange="triggerUpload(event, 'preview-proj-event')">
                </div>

                <!-- Proyek Website -->
                <div class="bg-slate-800/60 p-6 rounded-3xl border border-slate-700/60 space-y-4 flex flex-col justify-between">
                    <div class="space-y-2" contenteditable="true">
                        <span class="px-3 py-1 bg-blue-500/10 text-brand-cyan text-xs font-bold rounded-full border border-blue-500/20">Proyek Website</span>
                        <h3 class="text-xl font-heading font-bold text-white">Innova Learn & Website Management</h3>
                        <p class="text-slate-300 text-sm">Pengembangan platform web edukasi digital menggunakan Hostinger serta manajemen website summit dan pameran pendidikan.</p>
                    </div>
                    <div class="upload-container relative h-48 rounded-2xl overflow-hidden bg-slate-900 border border-slate-700">
                        <img id="preview-proj-web" src="https://placehold.co/600x300/1e293b/94a3b8?text=Foto+Website" class="w-full h-full object-cover">
                        <div class="upload-overlay absolute inset-0 bg-slate-950/70 flex flex-col items-center justify-center text-white cursor-pointer" onclick="document.getElementById('input-proj-web').click()">
                            <i class="fa-solid fa-upload text-sm mb-1 text-brand-cyan"></i>
                            <span class="text-xs font-semibold">Ganti Gambar Proyek Website</span>
                        </div>
                    </div>
                    <input type="file" id="input-proj-web" accept="image/*" class="hidden" onchange="triggerUpload(event, 'preview-proj-web')">
                </div>
            </div>
        </div>
    </section>

    <!-- 5. ORGANISASI & SERTIFIKASI -->
    <section id="certificates" class="py-24 bg-slate-950 border-t border-slate-800">
        <div class="max-w-7xl mx-auto px-6 space-y-12">
            <div class="text-center max-w-2xl mx-auto space-y-3">
                <h2 class="text-3xl font-heading font-extrabold text-white">Organisasi & Sertifikasi</h2>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
                <!-- Cert 1 -->
                <div class="bg-slate-900 p-6 rounded-3xl border border-slate-800 space-y-4 flex flex-col justify-between">
                    <div class="space-y-2" contenteditable="true">
                        <span class="text-xs font-bold text-brand-cyan uppercase">Sertifikat Magang & HIMA</span>
                        <h3 class="text-lg font-bold text-white">Rumah BUMN Kota Malang & HMD TEP</h3>
                        <p class="text-slate-400 text-sm">Sertifikat magang Graphic Design dengan predikat "Memuaskan", serta keaktifan sebagai Kepala Divisi Wirakesma di HMD TEP UM dan LKMM-TL 2023.</p>
                    </div>
                    <div class="upload-container relative h-52 rounded-2xl overflow-hidden bg-slate-950 border border-slate-800">
                        <img id="preview-cert1" src="https://placehold.co/600x400/1e293b/94a3b8?text=Sertifikat+1" class="w-full h-full object-cover">
                        <div class="upload-overlay absolute inset-0 bg-slate-950/70 flex flex-col items-center justify-center text-white cursor-pointer" onclick="document.getElementById('input-cert1').click()">
                            <i class="fa-solid fa-upload text-sm mb-1 text-brand-cyan"></i>
                            <span class="text-xs font-semibold">Ganti Foto Sertifikat</span>
                        </div>
                    </div>
                    <input type="file" id="input-cert1" accept="image/*" class="hidden" onchange="triggerUpload(event, 'preview-cert1')">
                </div>

                <!-- Cert 2 -->
                <div class="bg-slate-900 p-6 rounded-3xl border border-slate-800 space-y-4 flex flex-col justify-between">
                    <div class="space-y-2" contenteditable="true">
                        <span class="text-xs font-bold text-brand-pink uppercase">Penghargaan & Hak Cipta</span>
                        <h3 class="text-lg font-bold text-white">PIC Transkop & Surat Pencatatan Ciptaan</h3>
                        <p class="text-slate-400 text-sm">Penghargaan resmi PIC Transkop Karya Nyata Festival Jatim serta Surat Pencatatan Ciptaan LMS dari Kemenkumham.</p>
                    </div>
                    <div class="upload-container relative h-52 rounded-2xl overflow-hidden bg-slate-950 border border-slate-800">
                        <img id="preview-cert2" src="https://placehold.co/600x400/1e293b/94a3b8?text=Sertifikat+2" class="w-full h-full object-cover">
                        <div class="upload-overlay absolute inset-0 bg-slate-950/70 flex flex-col items-center justify-center text-white cursor-pointer" onclick="document.getElementById('input-cert2').click()">
                            <i class="fa-solid fa-upload text-sm mb-1 text-brand-pink"></i>
                            <span class="text-xs font-semibold">Ganti Foto Sertifikat</span>
                        </div>
                    </div>
                    <input type="file" id="input-cert2" accept="image/*" class="hidden" onchange="triggerUpload(event, 'preview-cert2')">
                </div>
            </div>
        </div>
    </section>

    <!-- 6. HUBUNGI SAYA -->
    <section id="contact" class="py-24 bg-gradient-to-t from-slate-950 to-slate-900 border-t border-slate-800">
        <div class="max-w-4xl mx-auto px-6">
            <div class="bg-gradient-to-tr from-brand-blue via-indigo-900 to-brand-pink rounded-3xl p-8 sm:p-14 text-white shadow-2xl text-center space-y-6 relative overflow-hidden">
                <div class="absolute -right-20 -bottom-20 w-80 h-80 bg-white/10 rounded-full blur-3xl pointer-events-none"></div>
                
                <h2 class="text-3xl sm:text-5xl font-heading font-extrabold tracking-tight">Hubungi Saya</h2>
                <p class="text-white/90 text-base sm:text-lg max-w-xl mx-auto" contenteditable="true">
                    I am greatly looking for the chance to cooperate, so please don't hesitate to contact me at any time, see yaa!
                </p>
                
                <div class="flex flex-wrap justify-center gap-4 pt-4 relative z-10">
                    <a href="mailto:ramadhanzaidaan@gmail.com" class="px-6 py-3.5 rounded-2xl bg-white text-brand-blue font-bold shadow-lg hover:bg-slate-100 transition-all flex items-center space-x-2">
                        <i class="fa-solid fa-envelope"></i>
                        <span>ramadhanzaidaan@gmail.com</span>
                    </a>
                    <a href="https://wa.me/6287755694464" target="_blank" class="px-6 py-3.5 rounded-2xl bg-emerald-500 text-white font-bold shadow-lg hover:bg-emerald-600 transition-all flex items-center space-x-2">
                        <i class="fa-brands fa-whatsapp text-lg"></i>
                        <span>087755694464</span>
                    </a>
                    <a href="https://instagram.com/r_zaidaan" target="_blank" class="px-6 py-3.5 rounded-2xl bg-pink-600 text-white font-bold shadow-lg hover:bg-pink-700 transition-all flex items-center space-x-2">
                        <i class="fa-brands fa-instagram text-lg"></i>
                        <span>@r_zaidaan</span>
                    </a>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="py-12 bg-slate-950 text-white text-center text-sm border-t border-slate-900">
        <p class="text-slate-400">&copy; 2026 Zaidaan Ramadhan. All Rights Reserved.</p>
    </footer>

    <!-- JavaScript untuk Live Preview Upload File -->
    <script>
        function triggerUpload(event, previewId) {
            const file = event.target.files[0];
            if (file) {
                const reader = new FileReader();
                reader.onload = function(e) {
                    document.getElementById(previewId).src = e.target.result;
                }
                reader.readAsDataURL(file);
            }
        }
    </script>
</body>
</html>
