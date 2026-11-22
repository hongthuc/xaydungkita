<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>CÔNG TY TNHH THƯƠNG MẠI XÂY DỰNG KITA | Thiết Kế & Thi Công Xây Dựng Đà Nẵng</title>
    <meta name="description" content="Công ty TNHH Thương Mại Xây Dựng KITA (xaydungkita.com) - Chuyên thiết kế kiến trúc, thi công phần thô, hoàn thiện, xây nhà trọn gói tại Đà Nẵng. Hotline: 0328.785.252.">
    <meta name="keywords" content="xây dựng kita, xaydungkita.com, xây nhà trọn gói đà nẵng, thi công phần thô đà nẵng, thiết kế kiến trúc đà nẵng, công ty xây dựng ngũ hành sơn">
    <link rel="canonical" href="https://xaydungkita.com/">

    <!-- Favicon & Ảnh Thumbnail Logo Khi Chia Sẻ Link (Open Graph / Zalo / Facebook) -->
    <link rel="icon" type="image/svg+xml" href="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 64 64'%3E%3Crect width='64' height='64' rx='10' fill='%230E2F56'/%3E%3Cpath d='M16 48V18h7v13l13-13h9L31 32l15 16h-9L25 35v13h-9z' fill='%23FFFFFF'/%3E%3Cpath d='M12 16l20-9 20 9v4L32 11 12 20v-4z' fill='%23D98A1A'/%3E%3C/svg%3E">
    <meta property="og:type" content="website">
    <meta property="og:site_name" content="CÔNG TY TNHH THƯƠNG MẠI XÂY DỰNG KITA">
    <meta property="og:url" content="https://xaydungkita.com/">
    <meta property="og:title" content="CÔNG TY TNHH THƯƠNG MẠI XÂY DỰNG KITA - Thiết Kế & Thi Công Đà Nẵng">
    <meta property="og:description" content="Chuyên Thiết kế Kiến trúc - Thi công phần thô - Hoàn thiện - Xây nhà trọn gói tại Đà Nẵng. Địa chỉ: 17 Nguyễn Trọng Hợp, Ngũ Hành Sơn, TP Đà Nẵng. Hotline: 0328.785.252.">
    <meta property="og:image" content="https://xaydungkita.com/wp-content/uploads/logo-kita-share.png">
    <meta property="og:image:width" content="1200">
    <meta property="og:image:height" content="630">
    <meta property="og:image:alt" content="Logo Công Ty TNHH Thương Mại Xây Dựng KITA">
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:title" content="CÔNG TY TNHH THƯƠNG MẠI XÂY DỰNG KITA">
    <meta name="twitter:description" content="Thiết kế & Thi công xây dựng uy tín tại Đà Nẵng - Hotline: 0328.785.252">
    <meta name="twitter:image" content="https://xaydungkita.com/wp-content/uploads/logo-kita-share.png">

    <!-- Font Inter & FontAwesome -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">

    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                    },
                    colors: {
                        kita: {
                            navy: '#0E2F56',
                            dark: '#081D36',
                            gold: '#D98A1A',
                            goldLight: '#F3B44C',
                            bg: '#F4F6F9',
                            border: '#E2E8F0',
                            text: '#1E293B',
                            muted: '#55657A'
                        }
                    }
                }
            }
        }
    </script>

    <style>
        /* Thiết lập chống tràn viền tuyệt đối và căn giữa chuẩn Flatsome */
        *, *::before, *::after {
            box-sizing: border-box;
        }
        html, body {
            width: 100%;
            max-width: 100%;
            margin: 0;
            padding: 0;
            overflow-x: hidden;
            font-family: 'Inter', sans-serif;
            color: #1E293B;
            background-color: #FFFFFF;
            scroll-behavior: smooth;
            -webkit-font-smoothing: antialiased;
        }

        /* Chiều ngang giao diện trên máy tính bằng 95% kích thước màn hình */
        .kita-container {
            width: 100%;
            max-width: 100%;
            margin-left: auto;
            margin-right: auto;
            padding-left: 12px;
            padding-right: 12px;
        }
        @media (min-width: 1024px) {
            .kita-container {
                width: 95%;
                max-width: 95%;
                padding-left: 0;
                padding-right: 0;
            }
        }

        /* Chuẩn thanh tiêu đề Flatsome */
        .flatsome-heading {
            position: relative;
            display: inline-block;
            padding-bottom: 10px;
        }
        .flatsome-heading::after {
            content: '';
            position: absolute;
            bottom: 0;
            left: 50%;
            transform: translateX(-50%);
            width: 56px;
            height: 3px;
            background-color: #D98A1A;
            border-radius: 2px;
        }
        .flatsome-heading-left::after {
            left: 0;
            transform: none;
        }

        /* 2 Banner tự trượt kích thước bằng nhau tuyệt đối bằng CSS Grid Stack */
        .hero-slider-grid {
            display: grid;
            grid-template-columns: 1fr;
            position: relative;
            width: 100%;
            overflow: hidden;
            border-radius: 10px;
            background-color: #0E2F56;
        }
        .hero-slide-item {
            grid-column: 1 / 2;
            grid-row: 1 / 2;
            position: relative;
            width: 100%;
            display: flex;
            align-items: center;
            opacity: 0;
            visibility: hidden;
            transition: opacity 0.7s ease-in-out, visibility 0.7s ease-in-out;
            z-index: 1;
        }
        .hero-slide-item.active {
            opacity: 1;
            visibility: visible;
            z-index: 2;
        }

        /* Đảm bảo tên danh mục trên máy tính & tab luôn gọn trên 1 hàng, không xuống dòng vỡ chữ */
        .nav-single-line {
            white-space: nowrap;
        }

        /* Hiệu ứng thẻ Flatsome nhẹ nhàng */
        .flatsome-card {
            transition: transform 0.25s ease, box-shadow 0.25s ease, border-color 0.25s ease;
        }
        .flatsome-card:hover {
            transform: translateY(-3px);
            box-shadow: 0 10px 24px -6px rgba(14, 47, 86, 0.14);
            border-color: #D98A1A;
        }
        .flatsome-card img {
            transition: transform 0.45s ease;
        }
        .flatsome-card:hover img {
            transform: scale(1.04);
        }

        /* Đảm bảo tên sản phẩm/dự án hiển thị đủ chữ, không bị cắt hay tràn viền */
        .card-title-full {
            overflow-wrap: break-word;
            word-wrap: break-word;
            word-break: break-word;
            hyphens: auto;
        }

        /* Hiệu ứng rung nhẹ cho nút Hotline nổi */
        @keyframes kitaPulse {
            0% { box-shadow: 0 0 0 0 rgba(217, 138, 26, 0.55); }
            70% { box-shadow: 0 0 0 12px rgba(217, 138, 26, 0); }
            100% { box-shadow: 0 0 0 0 rgba(217, 138, 26, 0); }
        }
        .hotline-pulse {
            animation: kitaPulse 2s infinite;
        }

        /* Tùy chỉnh thanh cuộn cho dải danh mục mobile nếu cần nhưng không tràn trang */
        .no-scrollbar::-webkit-scrollbar {
            display: none;
        }
        .no-scrollbar {
            -ms-overflow-style: none;
            scrollbar-width: none;
        }
    </style>
</head>
<body class="bg-white text-kita-text antialiased">

    <!-- ======================================================================= -->
    <!-- UXBUILDER: TOP BAR (CHỈ HIỂN THỊ THÔNG TIN LIÊN HỆ, KHÔNG CÓ THANH EDIT) -->
    <!-- ======================================================================= -->
    <div class="bg-kita-navy text-white text-xs border-b border-white/10">
        <div class="kita-container py-2 flex flex-wrap items-center justify-between gap-2">
            <div class="flex flex-wrap items-center gap-x-4 gap-y-1">
                <a href="tel:0328785252" class="inline-flex items-center gap-1.5 hover:text-kita-goldLight transition-colors whitespace-nowrap">
                    <i class="fa-solid fa-phone text-kita-gold text-[11px]"></i>
                    <span class="font-semibold">0328.785.252</span>
                </a>
                <span class="hidden sm:inline text-white/30">|</span>
                <a href="mailto:lienhe@xaydungkita.com" class="hidden sm:inline-flex items-center gap-1.5 hover:text-kita-goldLight transition-colors whitespace-nowrap">
                    <i class="fa-solid fa-envelope text-kita-gold text-[11px]"></i>
                    <span>lienhe@xaydungkita.com</span>
                </a>
            </div>
            <div class="hidden md:flex items-center gap-1.5 text-slate-200 truncate">
                <i class="fa-solid fa-location-dot text-kita-gold text-[11px]"></i>
                <span>17 Nguyễn Trọng Hợp, Phường Ngũ Hành Sơn, TP Đà Nẵng</span>
            </div>
        </div>
    </div>

    <!-- ======================================================================= -->
    <!-- UXBUILDER: HEADER FLATSOME (LOGO GỌN NHỎ + MENU 1 HÀNG, KHÔNG NÚT GỌI) -->
    <!-- ======================================================================= -->
    <header id="site-header" class="sticky top-0 z-40 bg-white/95 backdrop-blur-md border-b border-kita-border shadow-sm w-full">
        <div class="kita-container py-2.5 flex items-center justify-between gap-3">
            
            <!-- Logo Công Ty TNHH Thương Mại Xây Dựng KITA (Chỉnh gọn nhỏ chuyên nghiệp) -->
            <a href="#trang-chu" class="flex items-center gap-2 shrink-0 group focus:outline-none" aria-label="Trang chủ Xây Dựng KITA">
                <svg class="w-9 h-9 sm:w-10 sm:h-10 shrink-0" viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Logo Xây Dựng KITA">
                    <!-- Nền khối kiến trúc Xanh Navy -->
                    <rect x="2" y="2" width="60" height="60" rx="10" fill="#0E2F56"/>
                    <!-- Khung viền tinh tế -->
                    <rect x="4" y="4" width="56" height="56" rx="8" stroke="#D98A1A" stroke-opacity="0.35" stroke-width="1.5"/>
                    <!-- Mái kiến trúc Vàng Đồng -->
                    <path d="M12 23L32 11L52 23V27.5L32 15.5L12 27.5V23Z" fill="#D98A1A"/>
                    <!-- Chữ K hình cột kết cấu vững chắc -->
                    <path d="M19 29H25.5V40.5L36.5 29H44.5L33 40.5L45.5 53H37.2L28.3 43.4L25.5 46.2V53H19V29Z" fill="#FFFFFF"/>
                    <!-- Thanh nền móng -->
                    <rect x="19" y="55" width="26.5" height="2.2" rx="1.1" fill="#D98A1A"/>
                </svg>
                <div class="flex flex-col leading-none">
                    <span class="text-sm sm:text-base font-extrabold tracking-tight text-kita-navy group-hover:text-kita-gold transition-colors whitespace-nowrap">
                        XÂY DỰNG KITA
                    </span>
                    <span class="text-[9px] sm:text-[10px] font-semibold tracking-wider text-kita-gold uppercase mt-0.5 whitespace-nowrap">
                        xaydungkita.com
                    </span>
                </div>
            </a>

            <!-- Menu Máy Tính: Viết liền trên 1 hàng, chữ nhỏ gọn, tuyệt đối không xuống dòng -->
            <nav class="hidden lg:flex items-center justify-end flex-nowrap gap-4 xl:gap-6" aria-label="Điều hướng chính">
                <a href="#trang-chu" class="nav-single-line text-[13px] font-semibold text-kita-navy hover:text-kita-gold transition-colors py-1">Trang chủ</a>
                <a href="#gioi-thieu" class="nav-single-line text-[13px] font-semibold text-kita-navy hover:text-kita-gold transition-colors py-1">Giới thiệu</a>
                <a href="#linh-vuc" class="nav-single-line text-[13px] font-semibold text-kita-navy hover:text-kita-gold transition-colors py-1">Lĩnh vực hoạt động</a>
                <a href="#san-pham-thi-cong" class="nav-single-line text-[13px] font-semibold text-kita-navy hover:text-kita-gold transition-colors py-1">Hạng mục thi công</a>
                <a href="#du-an-da-nang" class="nav-single-line text-[13px] font-semibold text-kita-navy hover:text-kita-gold transition-colors py-1">Dự án Đà Nẵng</a>
                <a href="#bao-gia" class="nav-single-line text-[13px] font-semibold text-kita-navy hover:text-kita-gold transition-colors py-1">Báo giá</a>
                <a href="#tin-tuc" class="nav-single-line text-[13px] font-semibold text-kita-navy hover:text-kita-gold transition-colors py-1">Tin tức</a>
                <a href="#lien-he" class="nav-single-line text-[13px] font-semibold text-kita-navy hover:text-kita-gold transition-colors py-1">Liên hệ</a>
            </nav>

            <!-- Nút Mở Menu Mobile (Không để nút Gọi ngay trên Header) -->
            <button id="mobile-menu-btn" type="button" class="lg:hidden inline-flex items-center justify-center w-10 h-10 rounded-lg border border-kita-border text-kita-navy hover:bg-kita-bg focus:outline-none" aria-label="Mở menu điều hướng" aria-expanded="false">
                <i class="fa-solid fa-bars text-lg"></i>
            </button>
        </div>

        <!-- Menu Mobile Dạng Ngăn Kéo Gọn Gàng -->
        <div id="mobile-menu-panel" class="hidden lg:hidden bg-white border-t border-kita-border shadow-lg">
            <div class="kita-container py-3 flex flex-col divide-y divide-slate-100">
                <a href="#trang-chu" class="mobile-nav-link py-2.5 text-sm font-semibold text-kita-navy hover:text-kita-gold">Trang chủ</a>
                <a href="#gioi-thieu" class="mobile-nav-link py-2.5 text-sm font-semibold text-kita-navy hover:text-kita-gold">Giới thiệu</a>
                <a href="#linh-vuc" class="mobile-nav-link py-2.5 text-sm font-semibold text-kita-navy hover:text-kita-gold">Lĩnh vực hoạt động</a>
                <a href="#san-pham-thi-cong" class="mobile-nav-link py-2.5 text-sm font-semibold text-kita-navy hover:text-kita-gold">Hạng mục thi công</a>
                <a href="#du-an-da-nang" class="mobile-nav-link py-2.5 text-sm font-semibold text-kita-navy hover:text-kita-gold">Dự án Đà Nẵng</a>
                <a href="#bao-gia" class="mobile-nav-link py-2.5 text-sm font-semibold text-kita-navy hover:text-kita-gold">Báo giá</a>
                <a href="#tin-tuc" class="mobile-nav-link py-2.5 text-sm font-semibold text-kita-navy hover:text-kita-gold">Tin tức</a>
                <a href="#lien-he" class="mobile-nav-link py-2.5 text-sm font-semibold text-kita-navy hover:text-kita-gold">Liên hệ</a>
            </div>
        </div>
    </header>

    <main id="trang-chu" class="w-full overflow-x-hidden">

        <!-- ======================================================================= -->
        <!-- UXBUILDER: SECTION 1 - 2 BANNER TỰ TRƯỢT KÍCH THƯỚC BẰNG NHAU           -->
        <!-- Chữ và hình ảnh nằm trọn trong banner, cách xa viền, không mất chữ      -->
        <!-- ======================================================================= -->
        <section class="py-3 sm:py-5 bg-kita-bg">
            <div class="kita-container">
                <div id="hero-slider" class="hero-slider-grid shadow-md" role="region" aria-label="Banner nổi bật Xây Dựng KITA">
                    
                    <!-- BANNER 1 -->
                    <div class="hero-slide-item active">
                        <!-- Ảnh nền thực tế công trình (lớp phủ xanh navy theo logo) -->
                        <img src="https://drive.google.com/thumbnail?id=13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz&sz=w1600"
                             data-drive-id="13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz"
                             alt="Thi công xây dựng trọn gói Công Ty TNHH Thương Mại Xây Dựng KITA"
                             class="drive-img absolute inset-0 w-full h-full object-cover object-center"
                             loading="eager">
                        <div class="absolute inset-0 bg-gradient-to-r from-kita-dark/92 via-kita-navy/82 to-kita-navy/55"></div>

                        <!-- Nội dung nằm trọn bên trong, padding rộng cách xa viền ảnh trên cả Mobile & PC -->
                        <div class="relative z-10 w-full px-10 sm:px-16 md:px-20 lg:px-24 py-10 sm:py-16 md:py-20 lg:py-24">
                            <div class="max-w-2xl text-white">
                                <p class="text-[11px] sm:text-xs md:text-sm font-bold uppercase tracking-[0.16em] text-kita-goldLight mb-2 sm:mb-3">
                                    CÔNG TY TNHH THƯƠNG MẠI XÂY DỰNG KITA
                                </p>
                                <h1 class="text-xl sm:text-3xl md:text-4xl lg:text-[42px] font-extrabold leading-snug sm:leading-tight mb-3 sm:mb-4">
                                    Thiết Kế Kiến Trúc &amp; Thi Công Xây Dựng Trọn Gói Tại Đà Nẵng
                                </h1>
                                <p class="text-xs sm:text-sm md:text-base text-slate-200 leading-relaxed mb-5 sm:mb-7 max-w-xl">
                                    Chuyên xây dựng Nhà phố, Biệt thự, Khách sạn, Căn hộ dịch vụ và Văn phòng. Cam kết đúng tiến độ, chuẩn kỹ thuật kết cấu và minh bạch chi phí từng hạng mục.
                                </p>
                                <div class="flex flex-wrap items-center gap-3">
                                    <a href="#bao-gia" class="inline-flex items-center gap-2 bg-kita-gold hover:bg-amber-600 text-white font-semibold text-xs sm:text-sm px-4 sm:px-6 py-2.5 sm:py-3 rounded-lg transition-colors shadow">
                                        <span>Nhận báo giá miễn phí</span>
                                        <i class="fa-solid fa-arrow-right text-xs"></i>
                                    </a>
                                    <a href="#du-an-da-nang" class="inline-flex items-center gap-2 bg-white/15 hover:bg-white/25 text-white border border-white/40 font-semibold text-xs sm:text-sm px-4 sm:px-6 py-2.5 sm:py-3 rounded-lg transition-colors">
                                        <span>Xem dự án Đà Nẵng</span>
                                    </a>
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- BANNER 2 -->
                    <div class="hero-slide-item">
                        <img src="https://drive.google.com/thumbnail?id=157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT&sz=w1600"
                             data-drive-id="157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT"
                             alt="Công trình hoàn thiện tiêu biểu tại Đà Nẵng của Xây Dựng KITA"
                             class="drive-img absolute inset-0 w-full h-full object-cover object-center"
                             loading="lazy">
                        <div class="absolute inset-0 bg-gradient-to-r from-kita-dark/92 via-kita-navy/82 to-kita-navy/55"></div>

                        <!-- Nội dung nằm trọn bên trong, padding rộng cách xa viền ảnh trên cả Mobile & PC -->
                        <div class="relative z-10 w-full px-10 sm:px-16 md:px-20 lg:px-24 py-10 sm:py-16 md:py-20 lg:py-24">
                            <div class="max-w-2xl text-white">
                                <p class="text-[11px] sm:text-xs md:text-sm font-bold uppercase tracking-[0.16em] text-kita-goldLight mb-2 sm:mb-3">
                                    AN TOÀN – CHẤT LƯỢNG – TIẾN ĐỘ – BẢO HÀNH DÀI LÂU
                                </p>
                                <h2 class="text-xl sm:text-3xl md:text-4xl lg:text-[42px] font-extrabold leading-snug sm:leading-tight mb-3 sm:mb-4">
                                    Giải Pháp Thi Công Phần Thô &amp; Hoàn Thiện Nội Thất Chuẩn Mực
                                </h2>
                                <p class="text-xs sm:text-sm md:text-base text-slate-200 leading-relaxed mb-5 sm:mb-7 max-w-xl">
                                    Đội ngũ kỹ sư và kiến trúc sư giàu kinh nghiệm trực tiếp giám sát tại công trường. Vật tư chính hãng, không phát sinh chi phí ngoài hợp đồng.
                                </p>
                                <div class="flex flex-wrap items-center gap-3">
                                    <a href="#san-pham-thi-cong" class="inline-flex items-center gap-2 bg-kita-gold hover:bg-amber-600 text-white font-semibold text-xs sm:text-sm px-4 sm:px-6 py-2.5 sm:py-3 rounded-lg transition-colors shadow">
                                        <span>Xem hạng mục thi công</span>
                                        <i class="fa-solid fa-arrow-right text-xs"></i>
                                    </a>
                                    <a href="tel:0328785252" class="inline-flex items-center gap-2 bg-white/15 hover:bg-white/25 text-white border border-white/40 font-semibold text-xs sm:text-sm px-4 sm:px-6 py-2.5 sm:py-3 rounded-lg transition-colors">
                                        <i class="fa-solid fa-phone text-xs"></i>
                                        <span>Tư vấn: 0328.785.252</span>
                                    </a>
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- Nút điều hướng Banner gọn sát lề, không đè lên chữ -->
                    <button id="banner-prev" type="button" class="absolute left-2 sm:left-4 top-1/2 -translate-y-1/2 z-20 w-7 h-7 sm:w-10 sm:h-10 rounded-full bg-black/35 hover:bg-kita-gold text-white flex items-center justify-center transition-colors focus:outline-none" aria-label="Banner trước">
                        <i class="fa-solid fa-chevron-left text-xs sm:text-sm"></i>
                    </button>
                    <button id="banner-next" type="button" class="absolute right-2 sm:right-4 top-1/2 -translate-y-1/2 z-20 w-7 h-7 sm:w-10 sm:h-10 rounded-full bg-black/35 hover:bg-kita-gold text-white flex items-center justify-center transition-colors focus:outline-none" aria-label="Banner tiếp theo">
                        <i class="fa-solid fa-chevron-right text-xs sm:text-sm"></i>
                    </button>

                    <!-- Chấm chỉ báo Slide -->
                    <div class="absolute bottom-3 sm:bottom-4 left-1/2 -translate-x-1/2 z-20 flex items-center gap-2">
                        <button type="button" class="banner-dot w-6 h-2 rounded-full bg-kita-gold transition-all" data-index="0" aria-label="Chuyển tới banner 1"></button>
                        <button type="button" class="banner-dot w-2.5 h-2 rounded-full bg-white/50 hover:bg-white transition-all" data-index="1" aria-label="Chuyển tới banner 2"></button>
                    </div>
                </div>
            </div>
        </section>

        <!-- ======================================================================= -->
        <!-- UXBUILDER: SECTION 2 - DỊCH VỤ TIÊU BIỂU (GIỐNG MẪU TINTRUONGTHINH.COM) -->
        <!-- ======================================================================= -->
        <section id="linh-vuc" class="py-10 sm:py-14 bg-white">
            <div class="kita-container">
                <div class="text-center mb-8 sm:mb-10">
                    <h2 class="flatsome-heading text-xl sm:text-2xl md:text-3xl font-extrabold text-kita-navy uppercase tracking-tight">
                        Dịch Vụ Tiêu Biểu
                    </h2>
                    <p class="text-xs sm:text-sm text-kita-muted mt-3 max-w-2xl mx-auto">
                        Giải pháp toàn diện từ khâu tư vấn thiết kế đến thi công hoàn thiện và bàn giao chìa khóa trao tay tại Đà Nẵng và khu vực Miền Trung.
                    </p>
                </div>

                <!-- 3 Khối Dịch Vụ Chính Chuẩn Flatsome Row 3 Columns -->
                <div class="grid grid-cols-1 md:grid-cols-3 gap-4 sm:gap-6">
                    <!-- Dịch vụ 1 -->
                    <div class="flatsome-card bg-white border border-kita-border rounded-xl overflow-hidden flex flex-col">
                        <div class="aspect-[16/10] w-full overflow-hidden bg-slate-100">
                            <img src="https://drive.google.com/thumbnail?id=1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR&sz=w1000"
                                 data-drive-id="1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR"
                                 alt="Thiết kế kiến trúc và nội thất Xây Dựng KITA"
                                 class="drive-img w-full h-full object-cover" loading="lazy">
                        </div>
                        <div class="p-4 sm:p-5 flex-1 flex flex-col">
                            <div class="flex items-center gap-2.5 mb-2">
                                <span class="w-8 h-8 rounded-lg bg-kita-navy/10 text-kita-navy flex items-center justify-center shrink-0">
                                    <i class="fa-solid fa-compass-drafting text-sm"></i>
                                </span>
                                <h3 class="text-base sm:text-lg font-bold text-kita-navy uppercase">Thiết Kế Kiến Trúc</h3>
                            </div>
                            <p class="text-xs sm:text-sm text-kita-muted leading-relaxed flex-1">
                                Thiết kế mặt tiền, bố trí công năng tối ưu ánh sáng và thông gió tự nhiên cho nhà phố, biệt thự, khách sạn, căn hộ dịch vụ và văn phòng.
                            </p>
                            <a href="#bao-gia" class="inline-flex items-center gap-1.5 text-xs sm:text-sm font-semibold text-kita-gold hover:text-kita-navy mt-3 transition-colors">
                                <span>Nhận tư vấn thiết kế</span>
                                <i class="fa-solid fa-angle-right"></i>
                            </a>
                        </div>
                    </div>

                    <!-- Dịch vụ 2 -->
                    <div class="flatsome-card bg-white border border-kita-border rounded-xl overflow-hidden flex flex-col">
                        <div class="aspect-[16/10] w-full overflow-hidden bg-slate-100">
                            <img src="https://drive.google.com/thumbnail?id=1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv&sz=w1000"
                                 data-drive-id="1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv"
                                 alt="Thi công phần thô và xây nhà trọn gói KITA"
                                 class="drive-img w-full h-full object-cover" loading="lazy">
                        </div>
                        <div class="p-4 sm:p-5 flex-1 flex flex-col">
                            <div class="flex items-center gap-2.5 mb-2">
                                <span class="w-8 h-8 rounded-lg bg-kita-navy/10 text-kita-navy flex items-center justify-center shrink-0">
                                    <i class="fa-solid fa-helmet-safety text-sm"></i>
                                </span>
                                <h3 class="text-base sm:text-lg font-bold text-kita-navy uppercase">Thi Công Xây Dựng</h3>
                            </div>
                            <p class="text-xs sm:text-sm text-kita-muted leading-relaxed flex-1">
                                Thi công phần thô, nhân công hoàn thiện và xây nhà trọn gói. Tuân thủ nghiêm ngặt quy trình đổ bê tông, chống thấm và nghiệm thu từng giai đoạn.
                            </p>
                            <a href="#bao-gia" class="inline-flex items-center gap-1.5 text-xs sm:text-sm font-semibold text-kita-gold hover:text-kita-navy mt-3 transition-colors">
                                <span>Xem báo giá thi công</span>
                                <i class="fa-solid fa-angle-right"></i>
                            </a>
                        </div>
                    </div>

                    <!-- Dịch vụ 3 -->
                    <div class="flatsome-card bg-white border border-kita-border rounded-xl overflow-hidden flex flex-col">
                        <div class="aspect-[16/10] w-full overflow-hidden bg-slate-100">
                            <img src="https://drive.google.com/thumbnail?id=1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_&sz=w1000"
                                 data-drive-id="1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_"
                                 alt="Thi công hoàn thiện nội thất Xây Dựng KITA"
                                 class="drive-img w-full h-full object-cover" loading="lazy">
                        </div>
                        <div class="p-4 sm:p-5 flex-1 flex flex-col">
                            <div class="flex items-center gap-2.5 mb-2">
                                <span class="w-8 h-8 rounded-lg bg-kita-navy/10 text-kita-navy flex items-center justify-center shrink-0">
                                    <i class="fa-solid fa-couch text-sm"></i>
                                </span>
                                <h3 class="text-base sm:text-lg font-bold text-kita-navy uppercase">Hoàn Thiện Nội Thất</h3>
                            </div>
                            <p class="text-xs sm:text-sm text-kita-muted leading-relaxed flex-1">
                                Sản xuất và lắp đặt nội thất đồng bộ từ phòng khách, bếp, phòng ngủ đến sảnh lễ tân. Đảm bảo độ tinh xảo, bền đẹp theo đúng bản vẽ 3D.
                            </p>
                            <a href="#bao-gia" class="inline-flex items-center gap-1.5 text-xs sm:text-sm font-semibold text-kita-gold hover:text-kita-navy mt-3 transition-colors">
                                <span>Tư vấn nội thất trọn gói</span>
                                <i class="fa-solid fa-angle-right"></i>
                            </a>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- ======================================================================= -->
        <!-- UXBUILDER: SECTION 3 - GIỚI THIỆU CÔNG TY & THẾ MẠNH CỦA CHÚNG TÔI      -->
        <!-- ======================================================================= -->
        <section id="gioi-thieu" class="py-10 sm:py-14 bg-kita-bg border-y border-kita-border">
            <div class="kita-container">
                <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 sm:gap-8 items-center mb-10">
                    <!-- Cột giới thiệu -->
                    <div class="lg:col-span-6">
                        <p class="text-xs font-bold uppercase tracking-wider text-kita-gold mb-1.5">Về chúng tôi</p>
                        <h2 class="flatsome-heading flatsome-heading-left text-xl sm:text-2xl md:text-3xl font-extrabold text-kita-navy uppercase leading-snug mb-4">
                            CÔNG TY TNHH THƯƠNG MẠI XÂY DỰNG KITA
                        </h2>
                        <p class="text-xs sm:text-sm md:text-base text-kita-muted leading-relaxed mb-3">
                            <strong>Xây Dựng KITA</strong> chuyên Thiết kế – Xây dựng – Hoàn thiện Nội thất các công trình Nhà phố, Biệt thự, Khách sạn, Căn hộ cho thuê và Văn phòng tại Thành phố Đà Nẵng và khu vực lân cận.
                        </p>
                        <p class="text-xs sm:text-sm md:text-base text-kita-muted leading-relaxed mb-5">
                            Đặt chữ <strong>“TÂM”</strong> và <strong>“TÍN”</strong> lên hàng đầu, mỗi công trình do KITA thực hiện đều đảm bảo tiêu chuẩn <strong>An toàn – Chất lượng – Đúng tiến độ – Tối ưu chi phí</strong>. Chúng tôi đồng hành cùng chủ đầu tư từ bước lập hồ sơ xin phép xây dựng cho đến khi bàn giao và bảo hành kết cấu dài hạn.
                        </p>
                        <div class="grid grid-cols-3 gap-3 pt-2 border-t border-slate-200">
                            <div>
                                <div class="text-lg sm:text-2xl font-extrabold text-kita-navy">100%</div>
                                <div class="text-[11px] sm:text-xs text-kita-muted">Vật tư đúng cam kết</div>
                            </div>
                            <div>
                                <div class="text-lg sm:text-2xl font-extrabold text-kita-gold">5 Năm</div>
                                <div class="text-[11px] sm:text-xs text-kita-muted">Bảo hành kết cấu</div>
                            </div>
                            <div>
                                <div class="text-lg sm:text-2xl font-extrabold text-kita-navy">24/7</div>
                                <div class="text-[11px] sm:text-xs text-kita-muted">Hỗ trợ kỹ thuật</div>
                            </div>
                        </div>
                    </div>

                    <!-- Cột ảnh thực tế công trình -->
                    <div class="lg:col-span-6">
                        <div class="grid grid-cols-2 gap-3">
                            <div class="aspect-[4/3] rounded-xl overflow-hidden shadow-sm border border-white">
                                <img src="https://drive.google.com/thumbnail?id=1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO&sz=w1000"
                                     data-drive-id="1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO"
                                     alt="Thi công công trường thực tế Xây Dựng KITA"
                                     class="drive-img w-full h-full object-cover" loading="lazy">
                            </div>
                            <div class="aspect-[4/3] rounded-xl overflow-hidden shadow-sm border border-white">
                                <img src="https://drive.google.com/thumbnail?id=1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t&sz=w1000"
                                     data-drive-id="1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t"
                                     alt="Giám sát kỹ thuật công trình KITA Đà Nẵng"
                                     class="drive-img w-full h-full object-cover" loading="lazy">
                            </div>
                        </div>
                    </div>
                </div>

                <!-- 6 Thế Mạnh Nổi Bật (Đồng bộ bố cục tintruongthinh.com) -->
                <div class="text-center mb-6 sm:mb-8">
                    <h3 class="flatsome-heading text-lg sm:text-xl md:text-2xl font-extrabold text-kita-navy uppercase">
                        Thế Mạnh Của Chúng Tôi
                    </h3>
                </div>
                <div class="grid grid-cols-2 lg:grid-cols-3 gap-3 sm:gap-5">
                    <div class="bg-white p-4 sm:p-5 rounded-xl border border-kita-border">
                        <div class="w-9 h-9 rounded-lg bg-kita-navy text-kita-goldLight flex items-center justify-center mb-3">
                            <i class="fa-solid fa-users-gear text-sm"></i>
                        </div>
                        <h4 class="text-xs sm:text-sm md:text-base font-bold text-kita-navy mb-1.5">Đội ngũ kỹ sư chuyên nghiệp</h4>
                        <p class="text-[11px] sm:text-xs md:text-sm text-kita-muted leading-relaxed">Kiến trúc sư sáng tạo cùng đội ngũ kỹ sư giám sát và thợ thi công tay nghề cao, giàu kinh nghiệm thực chiến.</p>
                    </div>
                    <div class="bg-white p-4 sm:p-5 rounded-xl border border-kita-border">
                        <div class="w-9 h-9 rounded-lg bg-kita-navy text-kita-goldLight flex items-center justify-center mb-3">
                            <i class="fa-solid fa-layer-group text-sm"></i>
                        </div>
                        <h4 class="text-xs sm:text-sm md:text-base font-bold text-kita-navy mb-1.5">Cập nhật xu hướng hiện đại</h4>
                        <p class="text-[11px] sm:text-xs md:text-sm text-kita-muted leading-relaxed">Áp dụng vật liệu mới, giải pháp chống nóng và chống thấm phù hợp khí hậu ven biển Đà Nẵng.</p>
                    </div>
                    <div class="bg-white p-4 sm:p-5 rounded-xl border border-kita-border">
                        <div class="w-9 h-9 rounded-lg bg-kita-navy text-kita-goldLight flex items-center justify-center mb-3">
                            <i class="fa-solid fa-calendar-check text-sm"></i>
                        </div>
                        <h4 class="text-xs sm:text-sm md:text-base font-bold text-kita-navy mb-1.5">Giám sát tiến độ chuẩn xác</h4>
                        <p class="text-[11px] sm:text-xs md:text-sm text-kita-muted leading-relaxed">Báo cáo nhật ký thi công bằng hình ảnh thực tế hàng ngày giúp chủ đầu tư an tâm theo dõi từ xa.</p>
                    </div>
                    <div class="bg-white p-4 sm:p-5 rounded-xl border border-kita-border">
                        <div class="w-9 h-9 rounded-lg bg-kita-navy text-kita-goldLight flex items-center justify-center mb-3">
                            <i class="fa-solid fa-shield-halved text-sm"></i>
                        </div>
                        <h4 class="text-xs sm:text-sm md:text-base font-bold text-kita-navy mb-1.5">Bảo hành công trình lâu dài</h4>
                        <p class="text-[11px] sm:text-xs md:text-sm text-kita-muted leading-relaxed">Chế độ bảo hành kết cấu và hoàn thiện rõ ràng trên hợp đồng, hỗ trợ xử lý kỹ thuật nhanh chóng.</p>
                    </div>
                    <div class="bg-white p-4 sm:p-5 rounded-xl border border-kita-border">
                        <div class="w-9 h-9 rounded-lg bg-kita-navy text-kita-goldLight flex items-center justify-center mb-3">
                            <i class="fa-solid fa-file-invoice-dollar text-sm"></i>
                        </div>
                        <h4 class="text-xs sm:text-sm md:text-base font-bold text-kita-navy mb-1.5">Chi phí hợp lý, minh bạch</h4>
                        <p class="text-[11px] sm:text-xs md:text-sm text-kita-muted leading-relaxed">Dự toán chi tiết từng chủng loại vật tư, cam kết tối ưu ngân sách và không phát sinh bất hợp lý.</p>
                    </div>
                    <div class="bg-white p-4 sm:p-5 rounded-xl border border-kita-border">
                        <div class="w-9 h-9 rounded-lg bg-kita-navy text-kita-goldLight flex items-center justify-center mb-3">
                            <i class="fa-solid fa-headset text-sm"></i>
                        </div>
                        <h4 class="text-xs sm:text-sm md:text-base font-bold text-kita-navy mb-1.5">Tư vấn &amp; khảo sát miễn phí</h4>
                        <p class="text-[11px] sm:text-xs md:text-sm text-kita-muted leading-relaxed">Khảo sát thực tế khu đất tại Đà Nẵng, tư vấn phương án mặt bằng và dự toán sơ bộ hoàn toàn miễn phí.</p>
                    </div>
                </div>
            </div>
        </section>

        <!-- ======================================================================= -->
        <!-- UXBUILDER: SECTION 4 - DANH MỤC SẢN PHẨM & HẠNG MỤC THI CÔNG THỰC TẾ    -->
        <!-- Lấy 9 ảnh thực tế thi công từ Google Drive, 2 cột Mobile, chữ đủ không cắt -->
        <!-- ======================================================================= -->
        <section id="san-pham-thi-cong" class="py-10 sm:py-14 bg-white">
            <div class="kita-container">
                <div class="text-center mb-6">
                    <h2 class="flatsome-heading text-xl sm:text-2xl md:text-3xl font-extrabold text-kita-navy uppercase">
                        Danh Mục Sản Phẩm &amp; Thi Công Thực Tế
                    </h2>
                    <p class="text-xs sm:text-sm text-kita-muted mt-3 max-w-2xl mx-auto">
                        Hình ảnh thi công thực tế tại công trường của Xây Dựng KITA theo các hạng mục trọng tâm.
                    </p>
                </div>

                <!-- Danh mục sản phẩm (Chữ nhỏ gọn, viết liền trên 1 hàng không gãy tên danh mục) -->
                <div id="product-tabs" class="flex flex-wrap items-center justify-center gap-1.5 sm:gap-2 mb-7">
                    <button type="button" data-cat="all" class="product-tab active whitespace-nowrap px-3 sm:px-4 py-1.5 sm:py-2 rounded-lg text-[11px] sm:text-xs md:text-[13px] font-semibold border transition-colors bg-kita-navy text-white border-kita-navy">
                        Tất cả
                    </button>
                    <button type="button" data-cat="thiet-ke" class="product-tab whitespace-nowrap px-3 sm:px-4 py-1.5 sm:py-2 rounded-lg text-[11px] sm:text-xs md:text-[13px] font-semibold border transition-colors bg-white text-kita-navy border-kita-border hover:border-kita-gold">
                        Thiết kế Kiến trúc – Nội thất
                    </button>
                    <button type="button" data-cat="phan-tho" class="product-tab whitespace-nowrap px-3 sm:px-4 py-1.5 sm:py-2 rounded-lg text-[11px] sm:text-xs md:text-[13px] font-semibold border transition-colors bg-white text-kita-navy border-kita-border hover:border-kita-gold">
                        Thi công phần thô
                    </button>
                    <button type="button" data-cat="hoan-thien" class="product-tab whitespace-nowrap px-3 sm:px-4 py-1.5 sm:py-2 rounded-lg text-[11px] sm:text-xs md:text-[13px] font-semibold border transition-colors bg-white text-kita-navy border-kita-border hover:border-kita-gold">
                        Thi công hoàn thiện
                    </button>
                    <button type="button" data-cat="noi-that" class="product-tab whitespace-nowrap px-3 sm:px-4 py-1.5 sm:py-2 rounded-lg text-[11px] sm:text-xs md:text-[13px] font-semibold border transition-colors bg-white text-kita-navy border-kita-border hover:border-kita-gold">
                        Thi công nội thất
                    </button>
                    <button type="button" data-cat="tron-goi" class="product-tab whitespace-nowrap px-3 sm:px-4 py-1.5 sm:py-2 rounded-lg text-[11px] sm:text-xs md:text-[13px] font-semibold border transition-colors bg-white text-kita-navy border-kita-border hover:border-kita-gold">
                        Xây nhà trọn gói
                    </button>
                </div>

                <!-- Lưới sản phẩm: 2 cột trên Điện thoại, 3 cột trên Máy tính, KHÔNG nhãn dán, tên hiển thị đầy đủ -->
                <div id="product-grid" class="grid grid-cols-2 md:grid-cols-3 gap-3 sm:gap-5">
                    <!-- Nội dung được render tự động từ dữ liệu 9 ảnh thực tế Google Drive -->
                </div>
            </div>
        </section>

        <!-- ======================================================================= -->
        <!-- UXBUILDER: SECTION 5 - CÁC DỰ ÁN THỰC TẾ TẠI ĐÀ NẴNG (10 ẢNH DRIVE)     -->
        <!-- ======================================================================= -->
        <section id="du-an-da-nang" class="py-10 sm:py-14 bg-kita-bg border-y border-kita-border">
            <div class="kita-container">
                <div class="text-center mb-6">
                    <h2 class="flatsome-heading text-xl sm:text-2xl md:text-3xl font-extrabold text-kita-navy uppercase">
                        Các Dự Án Tiêu Biểu Tại Đà Nẵng
                    </h2>
                    <p class="text-xs sm:text-sm text-kita-muted mt-3 max-w-2xl mx-auto">
                        Những công trình thực tế do Công ty TNHH Thương Mại Xây Dựng KITA thiết kế và trực tiếp thi công trên địa bàn TP Đà Nẵng.
                    </p>
                </div>

                <!-- Danh mục dự án (Nhỏ gọn, viết liền không xuống dòng vỡ chữ) -->
                <div id="project-tabs" class="flex flex-wrap items-center justify-center gap-1.5 sm:gap-2 mb-7">
                    <button type="button" data-proj="all" class="project-tab active whitespace-nowrap px-3 sm:px-4 py-1.5 sm:py-2 rounded-lg text-[11px] sm:text-xs md:text-[13px] font-semibold border transition-colors bg-kita-navy text-white border-kita-navy">
                        Tất cả dự án
                    </button>
                    <button type="button" data-proj="nha-pho" class="project-tab whitespace-nowrap px-3 sm:px-4 py-1.5 sm:py-2 rounded-lg text-[11px] sm:text-xs md:text-[13px] font-semibold border transition-colors bg-white text-kita-navy border-kita-border hover:border-kita-gold">
                        Nhà phố
                    </button>
                    <button type="button" data-proj="biet-thu" class="project-tab whitespace-nowrap px-3 sm:px-4 py-1.5 sm:py-2 rounded-lg text-[11px] sm:text-xs md:text-[13px] font-semibold border transition-colors bg-white text-kita-navy border-kita-border hover:border-kita-gold">
                        Biệt thự
                    </button>
                    <button type="button" data-proj="khach-san-can-ho" class="project-tab whitespace-nowrap px-3 sm:px-4 py-1.5 sm:py-2 rounded-lg text-[11px] sm:text-xs md:text-[13px] font-semibold border transition-colors bg-white text-kita-navy border-kita-border hover:border-kita-gold">
                        Khách sạn – Căn hộ
                    </button>
                    <button type="button" data-proj="van-phong" class="project-tab whitespace-nowrap px-3 sm:px-4 py-1.5 sm:py-2 rounded-lg text-[11px] sm:text-xs md:text-[13px] font-semibold border transition-colors bg-white text-kita-navy border-kita-border hover:border-kita-gold">
                        Văn phòng
                    </button>
                </div>

                <!-- Lưới 10 dự án Đà Nẵng: 2 cột Mobile, 5 cột trên màn hình rộng (2 hàng cân đối) -->
                <div id="project-grid" class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-5 gap-3 sm:gap-4">
                    <!-- Render tự động 10 công trình thực tế tại Đà Nẵng -->
                </div>
            </div>
        </section>

        <!-- ======================================================================= -->
        <!-- UXBUILDER: SECTION 6 - CÁC ĐỐI TÁC VẬT TƯ & CHIẾN LƯỢC                  -->
        <!-- ======================================================================= -->
        <section id="doi-tac" class="py-10 sm:py-12 bg-white">
            <div class="kita-container">
                <div class="text-center mb-7">
                    <h2 class="flatsome-heading text-xl sm:text-2xl font-extrabold text-kita-navy uppercase">
                        Đối Tác Cung Ứng Vật Tư
                    </h2>
                    <p class="text-xs sm:text-sm text-kita-muted mt-3">
                        Hợp tác cùng các thương hiệu vật liệu xây dựng hàng đầu để bảo chứng chất lượng bền vững cho mọi công trình.
                    </p>
                </div>

                <!-- Lưới đối tác: 2 cột Mobile, 5 cột Máy tính -->
                <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-5 gap-3 sm:gap-4">
                    <div class="border border-kita-border rounded-xl p-4 flex flex-col items-center justify-center bg-kita-bg/50 hover:border-kita-gold transition-colors text-center">
                        <span class="text-sm sm:text-base font-extrabold tracking-wide text-kita-navy">HÒA PHÁT</span>
                        <span class="text-[11px] text-kita-muted mt-0.5">Thép xây dựng tiêu chuẩn</span>
                    </div>
                    <div class="border border-kita-border rounded-xl p-4 flex flex-col items-center justify-center bg-kita-bg/50 hover:border-kita-gold transition-colors text-center">
                        <span class="text-sm sm:text-base font-extrabold tracking-wide text-kita-navy">XI MĂNG SÔNG GIANH</span>
                        <span class="text-[11px] text-kita-muted mt-0.5">Xi măng PCB40 kết cấu</span>
                    </div>
                    <div class="border border-kita-border rounded-xl p-4 flex flex-col items-center justify-center bg-kita-bg/50 hover:border-kita-gold transition-colors text-center">
                        <span class="text-sm sm:text-base font-extrabold tracking-wide text-kita-navy">DULUX / JOTUN</span>
                        <span class="text-[11px] text-kita-muted mt-0.5">Sơn nước &amp; chống thấm</span>
                    </div>
                    <div class="border border-kita-border rounded-xl p-4 flex flex-col items-center justify-center bg-kita-bg/50 hover:border-kita-gold transition-colors text-center">
                        <span class="text-sm sm:text-base font-extrabold tracking-wide text-kita-navy">CADIVI &amp; PANASONIC</span>
                        <span class="text-[11px] text-kita-muted mt-0.5">Hệ thống dây &amp; thiết bị điện</span>
                    </div>
                    <div class="border border-kita-border rounded-xl p-4 flex flex-col items-center justify-center bg-kita-bg/50 hover:border-kita-gold transition-colors text-center">
                        <span class="text-sm sm:text-base font-extrabold tracking-wide text-kita-navy">NHỰA BÌNH MINH</span>
                        <span class="text-[11px] text-kita-muted mt-0.5">Hệ thống ống cấp thoát nước</span>
                    </div>
                    <div class="border border-kita-border rounded-xl p-4 flex flex-col items-center justify-center bg-kita-bg/50 hover:border-kita-gold transition-colors text-center">
                        <span class="text-sm sm:text-base font-extrabold tracking-wide text-kita-navy">GỖ AN CƯỜNG</span>
                        <span class="text-[11px] text-kita-muted mt-0.5">Vật liệu nội thất cao cấp</span>
                    </div>
                    <div class="border border-kita-border rounded-xl p-4 flex flex-col items-center justify-center bg-kita-bg/50 hover:border-kita-gold transition-colors text-center">
                        <span class="text-sm sm:text-base font-extrabold tracking-wide text-kita-navy">NHÔM XINGFA</span>
                        <span class="text-[11px] text-kita-muted mt-0.5">Cửa nhôm kính cường lực</span>
                    </div>
                    <div class="border border-kita-border rounded-xl p-4 flex flex-col items-center justify-center bg-kita-bg/50 hover:border-kita-gold transition-colors text-center">
                        <span class="text-sm sm:text-base font-extrabold tracking-wide text-kita-navy">SIKA VIỆT NAM</span>
                        <span class="text-[11px] text-kita-muted mt-0.5">Phụ gia &amp; chống thấm chuyên dụng</span>
                    </div>
                    <div class="border border-kita-border rounded-xl p-4 flex flex-col items-center justify-center bg-kita-bg/50 hover:border-kita-gold transition-colors text-center">
                        <span class="text-sm sm:text-base font-extrabold tracking-wide text-kita-navy">TOTO / INAX</span>
                        <span class="text-[11px] text-kita-muted mt-0.5">Thiết bị vệ sinh chính hãng</span>
                    </div>
                    <div class="border border-kita-border rounded-xl p-4 flex flex-col items-center justify-center bg-kita-bg/50 hover:border-kita-gold transition-colors text-center">
                        <span class="text-sm sm:text-base font-extrabold tracking-wide text-kita-navy">VIGLACERA</span>
                        <span class="text-[11px] text-kita-muted mt-0.5">Gạch ốp lát &amp; vật liệu hoàn thiện</span>
                    </div>
                </div>
            </div>
        </section>

        <!-- ======================================================================= -->
        <!-- UXBUILDER: SECTION 7 - DANH MỤC CÁC BÀI VIẾT / TIN TỨC XÂY DỰNG         -->
        <!-- ======================================================================= -->
        <section id="tin-tuc" class="py-10 sm:py-14 bg-kita-bg border-y border-kita-border">
            <div class="kita-container">
                <div class="text-center mb-8">
                    <h2 class="flatsome-heading text-xl sm:text-2xl md:text-3xl font-extrabold text-kita-navy uppercase">
                        Tin Tức &amp; Cẩm Nang Xây Dựng
                    </h2>
                    <p class="text-xs sm:text-sm text-kita-muted mt-3 max-w-2xl mx-auto">
                        Chia sẻ kinh nghiệm thiết kế, quy trình kỹ thuật thi công và dự toán chi phí xây dựng thực tế tại Đà Nẵng.
                    </p>
                </div>

                <!-- 2 cột Mobile, 4 cột Máy tính -->
                <div id="articles-grid" class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5">
                    <!-- Render tự động các bài viết kiến thức xây dựng -->
                </div>
            </div>
        </section>

        <!-- ======================================================================= -->
        <!-- UXBUILDER: SECTION 8 - FORM YÊU CẦU BÁO GIÁ + BẢN ĐỒ GOOGLE MAPS + FANPAGE -->
        <!-- ======================================================================= -->
        <section id="bao-gia" class="py-10 sm:py-14 bg-white">
            <div class="kita-container">
                <div class="text-center mb-8">
                    <h2 class="flatsome-heading text-xl sm:text-2xl md:text-3xl font-extrabold text-kita-navy uppercase">
                        Đăng Ký Tư Vấn &amp; Nhận Báo Giá Miễn Phí
                    </h2>
                    <p class="text-xs sm:text-sm text-kita-muted mt-3 max-w-2xl mx-auto">
                        Để lại thông tin công trình, kỹ sư Xây Dựng KITA sẽ liên hệ khảo sát và lập bảng dự toán chi tiết trong ngày.
                    </p>
                </div>

                <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-stretch">
                    <!-- CỘT TRÁI: FORM YÊU CẦU & BÁO GIÁ (GIỐNG TINTRUONGTHINH.COM) -->
                    <div class="lg:col-span-7 bg-kita-bg border border-kita-border rounded-xl p-5 sm:p-7 flex flex-col justify-between">
                        <div>
                            <h3 class="text-base sm:text-lg font-extrabold text-kita-navy uppercase mb-1">
                                Gửi Yêu Cầu Báo Giá Xây Dựng
                            </h3>
                            <p class="text-xs sm:text-sm text-kita-muted mb-5">
                                Áp dụng cho công trình Nhà phố, Biệt thự, Khách sạn, Căn hộ và Cải tạo sửa chữa tại Đà Nẵng.
                            </p>

                            <form id="quote-form" class="space-y-4" novalidate>
                                <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                                    <div>
                                        <label for="q-name" class="block text-xs font-semibold text-kita-navy mb-1.5">Họ và tên <span class="text-red-500">*</span></label>
                                        <input id="q-name" type="text" required placeholder="Nhập họ tên của bạn"
                                               class="w-full px-3.5 py-2.5 text-sm bg-white border border-slate-300 rounded-lg focus:outline-none focus:border-kita-gold focus:ring-2 focus:ring-kita-gold/20">
                                    </div>
                                    <div>
                                        <label for="q-phone" class="block text-xs font-semibold text-kita-navy mb-1.5">Số điện thoại <span class="text-red-500">*</span></label>
                                        <input id="q-phone" type="tel" required placeholder="Ví dụ: 0328.785.252"
                                               class="w-full px-3.5 py-2.5 text-sm bg-white border border-slate-300 rounded-lg focus:outline-none focus:border-kita-gold focus:ring-2 focus:ring-kita-gold/20">
                                    </div>
                                </div>

                                <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                                    <div>
                                        <label for="q-type" class="block text-xs font-semibold text-kita-navy mb-1.5">Loại công trình</label>
                                        <select id="q-type" class="w-full px-3.5 py-2.5 text-sm bg-white border border-slate-300 rounded-lg focus:outline-none focus:border-kita-gold focus:ring-2 focus:ring-kita-gold/20">
                                            <option value="Nhà phố">Nhà phố hiện đại</option>
                                            <option value="Biệt thự">Biệt thự / Villa</option>
                                            <option value="Khách sạn - Căn hộ - Phòng trọ">Khách sạn – Căn hộ cho thuê</option>
                                            <option value="Văn phòng">Văn phòng / Showroom</option>
                                            <option value="Thi công phần thô">Thi công phần thô</option>
                                            <option value="Thi công hoàn thiện & Nội thất">Hoàn thiện &amp; Nội thất</option>
                                            <option value="Cải tạo sửa chữa">Cải tạo sửa chữa công trình</option>
                                        </select>
                                    </div>
                                    <div>
                                        <label for="q-budget" class="block text-xs font-semibold text-kita-navy mb-1.5">Mức đầu tư dự kiến</label>
                                        <select id="q-budget" class="w-full px-3.5 py-2.5 text-sm bg-white border border-slate-300 rounded-lg focus:outline-none focus:border-kita-gold focus:ring-2 focus:ring-kita-gold/20">
                                            <option value="Chưa xác định">Chưa xác định</option>
                                            <option value="Dưới 500 triệu">Dưới 500 triệu</option>
                                            <option value="500 triệu - 1 tỷ">500 triệu – 1 tỷ</option>
                                            <option value="1 tỷ - 2 tỷ">1 tỷ – 2 tỷ</option>
                                            <option value="2 tỷ - 3 tỷ">2 tỷ – 3 tỷ</option>
                                            <option value="Trên 3 tỷ">Trên 3 tỷ</option>
                                        </select>
                                    </div>
                                </div>

                                <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                                    <div>
                                        <label for="q-email" class="block text-xs font-semibold text-kita-navy mb-1.5">Email (nếu có)</label>
                                        <input id="q-email" type="email" placeholder="example@gmail.com"
                                               class="w-full px-3.5 py-2.5 text-sm bg-white border border-slate-300 rounded-lg focus:outline-none focus:border-kita-gold focus:ring-2 focus:ring-kita-gold/20">
                                    </div>
                                    <div>
                                        <label for="q-area" class="block text-xs font-semibold text-kita-navy mb-1.5">Địa điểm &amp; diện tích xây dựng</label>
                                        <input id="q-area" type="text" placeholder="Ví dụ: Ngũ Hành Sơn, 5x20m, 3 tầng"
                                               class="w-full px-3.5 py-2.5 text-sm bg-white border border-slate-300 rounded-lg focus:outline-none focus:border-kita-gold focus:ring-2 focus:ring-kita-gold/20">
                                    </div>
                                </div>

                                <div>
                                    <label for="q-note" class="block text-xs font-semibold text-kita-navy mb-1.5">Nội dung yêu cầu chi tiết</label>
                                    <textarea id="q-note" rows="3" placeholder="Mô tả nhu cầu thiết kế, thi công phần thô hoặc trọn gói..."
                                              class="w-full px-3.5 py-2.5 text-sm bg-white border border-slate-300 rounded-lg focus:outline-none focus:border-kita-gold focus:ring-2 focus:ring-kita-gold/20"></textarea>
                                </div>

                                <!-- Thông báo trạng thái form -->
                                <div id="quote-feedback" class="hidden rounded-lg p-3 text-xs sm:text-sm font-medium"></div>

                                <button type="submit" class="w-full sm:w-auto inline-flex items-center justify-center gap-2 bg-kita-navy hover:bg-kita-gold text-white font-bold text-sm px-7 py-3 rounded-lg transition-colors shadow">
                                    <i class="fa-solid fa-paper-plane text-xs"></i>
                                    <span>Gửi yêu cầu nhận báo giá</span>
                                </button>
                            </form>
                        </div>
                    </div>

                    <!-- CỘT PHẢI: FANPAGE FACEBOOK ĐƯA RA NGOÀI TRANG CHỦ -->
                    <div class="lg:col-span-5 flex flex-col gap-5">
                        <!-- Khối Fanpage Facebook Xây Dựng KITA -->
                        <div class="bg-white border border-kita-border rounded-xl overflow-hidden shadow-sm flex flex-col flex-1">
                            <div class="bg-kita-navy px-4 py-3 flex items-center justify-between">
                                <div class="flex items-center gap-2 text-white">
                                    <i class="fa-brands fa-facebook text-lg text-blue-400"></i>
                                    <span class="text-xs sm:text-sm font-bold uppercase tracking-wide">Fanpage Chính Thức</span>
                                </div>
                                <a href="https://www.facebook.com/search/top?q=X%C3%A2y%20D%E1%BB%B1ng%20KITA%20%C4%90%C3%A0%20N%E1%BA%B5ng" target="_blank" rel="noopener noreferrer" class="text-[11px] font-semibold text-kita-goldLight hover:underline">
                                    Mở Facebook <i class="fa-solid fa-arrow-up-right-from-square text-[10px]"></i>
                                </a>
                            </div>

                            <!-- Giao diện thẻ Fanpage trực quan (hiển thị đẹp mọi thiết bị, không bao giờ trống) -->
                            <div class="relative h-36 sm:h-40 w-full overflow-hidden bg-kita-dark">
                                <img src="https://drive.google.com/thumbnail?id=1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff&sz=w1000"
                                     data-drive-id="1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff"
                                     alt="Ảnh bìa Fanpage Công Ty TNHH Thương Mại Xây Dựng KITA"
                                     class="drive-img w-full h-full object-cover opacity-80" loading="lazy">
                                <div class="absolute inset-0 bg-gradient-to-t from-black/80 via-black/30 to-transparent"></div>
                                <div class="absolute bottom-3 left-3 right-3 flex items-end gap-3">
                                    <div class="w-12 h-12 rounded-lg bg-kita-navy border-2 border-white flex items-center justify-center shrink-0 shadow">
                                        <span class="text-white font-extrabold text-sm">KITA</span>
                                    </div>
                                    <div class="min-w-0 text-white">
                                        <h4 class="text-sm font-bold leading-tight truncate">Xây Dựng KITA – Đà Nẵng</h4>
                                        <p class="text-[11px] text-slate-200 truncate">Công ty TNHH Thương Mại Xây Dựng KITA</p>
                                    </div>
                                </div>
                            </div>

                            <div class="p-4 flex-1 flex flex-col justify-between gap-3">
                                <p class="text-xs text-kita-muted leading-relaxed">
                                    Theo dõi Fanpage Xây Dựng KITA để cập nhật hình ảnh tiến độ công trường thực tế tại Đà Nẵng, mẫu thiết kế nhà đẹp và ưu đãi miễn phí thiết kế khi thi công trọn gói.
                                </p>
                                <div class="grid grid-cols-2 gap-2.5">
                                    <a href="https://www.facebook.com/search/top?q=C%C3%B4ng%20Ty%20TNHH%20Th%C6%B0%C6%A1ng%20M%E1%BA%A1i%20X%C3%A2y%20D%E1%BB%B1ng%20KITA" target="_blank" rel="noopener noreferrer"
                                       class="inline-flex items-center justify-center gap-1.5 bg-[#1877F2] hover:bg-blue-700 text-white text-xs font-semibold py-2.5 px-3 rounded-lg transition-colors">
                                        <i class="fa-brands fa-facebook-f"></i>
                                        <span>Theo dõi Fanpage</span>
                                    </a>
                                    <a href="https://zalo.me/0328785252" target="_blank" rel="noopener noreferrer"
                                       class="inline-flex items-center justify-center gap-1.5 bg-[#0068FF] hover:bg-blue-700 text-white text-xs font-semibold py-2.5 px-3 rounded-lg transition-colors">
                                        <i class="fa-solid fa-comment-dots"></i>
                                        <span>Nhắn tin Zalo</span>
                                    </a>
                                </div>
                                <div class="pt-3 border-t border-slate-100 text-xs text-kita-muted space-y-1.5">
                                    <div class="flex items-start gap-2">
                                        <i class="fa-solid fa-location-dot text-kita-gold mt-0.5"></i>
                                        <span>17 Nguyễn Trọng Hợp, Phường Ngũ Hành Sơn, TP Đà Nẵng</span>
                                    </div>
                                    <div class="flex items-center gap-2">
                                        <i class="fa-solid fa-phone text-kita-gold"></i>
                                        <a href="tel:0328785252" class="font-bold text-kita-navy hover:text-kita-gold">0328.785.252</a>
                                    </div>
                                    <div class="flex items-center gap-2">
                                        <i class="fa-solid fa-globe text-kita-gold"></i>
                                        <span>xaydungkita.com</span>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- BẢN ĐỒ GOOGLE MAPS ĐƯA TRỰC TIẾP RA NGOÀI TRANG CHỦ -->
                <div id="lien-he" class="mt-8 bg-white border border-kita-border rounded-xl overflow-hidden shadow-sm">
                    <div class="px-4 sm:px-5 py-3.5 bg-kita-bg border-b border-kita-border flex flex-wrap items-center justify-between gap-2">
                        <div class="flex items-center gap-2">
                            <i class="fa-solid fa-map-location-dot text-kita-gold text-base"></i>
                            <h3 class="text-xs sm:text-sm md:text-base font-bold text-kita-navy">
                                Bản Đồ Chỉ Đường Trụ Sở: 17 Nguyễn Trọng Hợp, Phường Ngũ Hành Sơn, TP Đà Nẵng
                            </h3>
                        </div>
                        <a href="https://www.google.com/maps/search/?api=1&query=17+Nguy%E1%BB%85n+Tr%E1%BB%8Dng+H%E1%BB%A3p,+Ng%C5%A9+H%C3%A0nh+S%C6%A1n,+%C4%90%C3%A0+N%E1%BA%B5ng" target="_blank" rel="noopener noreferrer"
                           class="inline-flex items-center gap-1.5 text-xs font-semibold text-kita-navy hover:text-kita-gold transition-colors">
                            <span>Xem trên Google Maps</span>
                            <i class="fa-solid fa-arrow-up-right-from-square text-[11px]"></i>
                        </a>
                    </div>
                    <div class="w-full h-72 sm:h-80 md:h-96 bg-slate-100">
                        <iframe
                            title="Bản đồ trụ sở Công Ty TNHH Thương Mại Xây Dựng KITA - 17 Nguyễn Trọng Hợp, Ngũ Hành Sơn, Đà Nẵng"
                            src="https://maps.google.com/maps?q=17%20Nguy%E1%BB%85n%20Tr%E1%BB%8Dng%20H%E1%BB%A3p,%20Ng%C5%A9%20H%C3%A0nh%20S%C6%A1n,%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=16&ie=UTF8&iwloc=&output=embed"
                            class="w-full h-full border-0"
                            allowfullscreen=""
                            loading="lazy"
                            referrerpolicy="no-referrer-when-downgrade">
                        </iframe>
                    </div>
                </div>
            </div>
        </section>
    </main>

    <!-- ======================================================================= -->
    <!-- UXBUILDER: FOOTER FLATSOME ĐỒNG BỘ MÀU LOGO XANH NAVY & VÀNG ĐỒNG       -->
    <!-- ======================================================================= -->
    <footer class="bg-kita-dark text-slate-300 pt-10 sm:pt-12 pb-6 border-t-4 border-kita-gold">
        <div class="kita-container">
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-12 gap-7 pb-8 border-b border-white/10">
                <!-- Cột 1: Thông tin doanh nghiệp -->
                <div class="lg:col-span-5">
                    <div class="flex items-center gap-2.5 mb-3">
                        <svg class="w-9 h-9 shrink-0" viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg">
                            <rect x="2" y="2" width="60" height="60" rx="10" fill="#0E2F56"/>
                            <rect x="4" y="4" width="56" height="56" rx="8" stroke="#D98A1A" stroke-opacity="0.5" stroke-width="1.5"/>
                            <path d="M12 23L32 11L52 23V27.5L32 15.5L12 27.5V23Z" fill="#D98A1A"/>
                            <path d="M19 29H25.5V40.5L36.5 29H44.5L33 40.5L45.5 53H37.2L28.3 43.4L25.5 46.2V53H19V29Z" fill="#FFFFFF"/>
                            <rect x="19" y="55" width="26.5" height="2.2" rx="1.1" fill="#D98A1A"/>
                        </svg>
                        <div>
                            <div class="text-sm sm:text-base font-extrabold text-white leading-tight">CÔNG TY TNHH THƯƠNG MẠI XÂY DỰNG KITA</div>
                            <div class="text-[11px] text-kita-goldLight font-semibold">xaydungkita.com</div>
                        </div>
                    </div>
                    <ul class="space-y-2 text-xs sm:text-sm text-slate-300 mt-4">
                        <li class="flex items-start gap-2.5">
                            <i class="fa-solid fa-location-dot text-kita-gold mt-1"></i>
                            <span>Trụ sở: 17 Nguyễn Trọng Hợp, Phường Ngũ Hành Sơn, TP Đà Nẵng</span>
                        </li>
                        <li class="flex items-center gap-2.5">
                            <i class="fa-solid fa-phone text-kita-gold"></i>
                            <a href="tel:0328785252" class="hover:text-white font-semibold">Hotline: 0328.785.252</a>
                        </li>
                        <li class="flex items-center gap-2.5">
                            <i class="fa-solid fa-envelope text-kita-gold"></i>
                            <a href="mailto:lienhe@xaydungkita.com" class="hover:text-white">Email: lienhe@xaydungkita.com</a>
                        </li>
                        <li class="flex items-center gap-2.5">
                            <i class="fa-solid fa-building-shield text-kita-gold"></i>
                            <span>Mã số thuế: 0402298379</span>
                        </li>
                    </ul>
                </div>

                <!-- Cột 2: Lĩnh vực hoạt động -->
                <div class="lg:col-span-3">
                    <h4 class="text-sm font-bold text-white uppercase tracking-wide mb-3.5 pb-2 border-b border-white/10">
                        Lĩnh Vực Hoạt Động
                    </h4>
                    <ul class="space-y-2 text-xs sm:text-sm">
                        <li><a href="#san-pham-thi-cong" class="hover:text-kita-goldLight transition-colors">Thiết kế Kiến trúc – Nội thất</a></li>
                        <li><a href="#san-pham-thi-cong" class="hover:text-kita-goldLight transition-colors">Thi công phần thô công trình</a></li>
                        <li><a href="#san-pham-thi-cong" class="hover:text-kita-goldLight transition-colors">Thi công hoàn thiện nhà phố</a></li>
                        <li><a href="#san-pham-thi-cong" class="hover:text-kita-goldLight transition-colors">Thi công nội thất trọn gói</a></li>
                        <li><a href="#san-pham-thi-cong" class="hover:text-kita-goldLight transition-colors">Xây dựng nhà trọn gói Đà Nẵng</a></li>
                    </ul>
                </div>

                <!-- Cột 3: Danh mục dự án & Liên kết nhanh -->
                <div class="lg:col-span-4">
                    <h4 class="text-sm font-bold text-white uppercase tracking-wide mb-3.5 pb-2 border-b border-white/10">
                        Công Trình &amp; Báo Giá
                    </h4>
                    <div class="grid grid-cols-2 gap-2 text-xs sm:text-sm">
                        <a href="#du-an-da-nang" class="hover:text-kita-goldLight transition-colors">Nhà phố Đà Nẵng</a>
                        <a href="#bao-gia" class="hover:text-kita-goldLight transition-colors">Báo giá thiết kế</a>
                        <a href="#du-an-da-nang" class="hover:text-kita-goldLight transition-colors">Biệt thự hiện đại</a>
                        <a href="#bao-gia" class="hover:text-kita-goldLight transition-colors">Báo giá phần thô</a>
                        <a href="#du-an-da-nang" class="hover:text-kita-goldLight transition-colors">Khách sạn – Căn hộ</a>
                        <a href="#bao-gia" class="hover:text-kita-goldLight transition-colors">Báo giá hoàn thiện</a>
                        <a href="#du-an-da-nang" class="hover:text-kita-goldLight transition-colors">Văn phòng công ty</a>
                        <a href="#bao-gia" class="hover:text-kita-goldLight transition-colors">Báo giá trọn gói</a>
                    </div>
                </div>
            </div>

            <!-- Dòng bản quyền -->
            <div class="pt-5 flex flex-col sm:flex-row items-center justify-between gap-2 text-xs text-slate-400 text-center sm:text-left">
                <p>Copyright 2026 © CÔNG TY TNHH THƯƠNG MẠI XÂY DỰNG KITA. All rights reserved.</p>
                <p>Website: <span class="text-kita-goldLight font-medium">xaydungkita.com</span></p>
            </div>
        </div>
    </footer>

    <!-- ======================================================================= -->
    <!-- CÁC NÚT LIÊN HỆ NỔI BẬT: ZALO, FACEBOOK, HOTLINE (TƯƠNG THÍCH PC & MOBILE) -->
    <!-- ======================================================================= -->
    <div class="fixed right-3 bottom-4 sm:right-5 sm:bottom-6 z-50 flex flex-col items-end gap-2.5" aria-label="Liên hệ nhanh">
        <!-- Nút Zalo -->
        <a href="https://zalo.me/0328785252" target="_blank" rel="noopener noreferrer"
           class="group flex items-center gap-2 bg-[#0068FF] hover:bg-blue-700 text-white rounded-full shadow-lg p-2.5 sm:px-3.5 sm:py-2.5 transition-all"
           aria-label="Liên hệ Zalo 0328.785.252">
            <span class="w-6 h-6 flex items-center justify-center font-extrabold text-[11px] bg-white text-[#0068FF] rounded-full shrink-0">Zalo</span>
            <span class="hidden md:inline text-xs font-bold pr-1 whitespace-nowrap">Chat Zalo</span>
        </a>

        <!-- Nút Facebook -->
        <a href="https://www.facebook.com/search/top?q=C%C3%B4ng%20Ty%20TNHH%20Th%C6%B0%C6%A1ng%20M%E1%BA%A1i%20X%C3%A2y%20D%E1%BB%B1ng%20KITA" target="_blank" rel="noopener noreferrer"
           class="group flex items-center gap-2 bg-[#1877F2] hover:bg-blue-800 text-white rounded-full shadow-lg p-2.5 sm:px-3.5 sm:py-2.5 transition-all"
           aria-label="Fanpage Facebook Xây Dựng KITA">
            <span class="w-6 h-6 flex items-center justify-center shrink-0">
                <i class="fa-brands fa-facebook-f text-sm"></i>
            </span>
            <span class="hidden md:inline text-xs font-bold pr-1 whitespace-nowrap">Facebook</span>
        </a>

        <!-- Nút Hotline Nổi Bật -->
        <a href="tel:0328785252"
           class="hotline-pulse flex items-center gap-2 bg-kita-gold hover:bg-amber-600 text-white rounded-full shadow-xl p-2.5 sm:px-4 sm:py-2.5 transition-all"
           aria-label="Gọi Hotline 0328.785.252">
            <span class="w-6 h-6 flex items-center justify-center shrink-0">
                <i class="fa-solid fa-phone-volume text-sm"></i>
            </span>
            <span class="hidden sm:inline text-xs font-extrabold pr-1 whitespace-nowrap">0328.785.252</span>
        </a>
    </div>

    <!-- ======================================================================= -->
    <!-- MODAL XEM CHI TIẾT HÌNH ẢNH CÔNG TRÌNH / SẢN PHẨM / BÀI VIẾT            -->
    <!-- ======================================================================= -->
    <div id="detail-modal" class="fixed inset-0 z-50 hidden items-center justify-center bg-black/75 p-3 sm:p-5" role="dialog" aria-modal="true" aria-labelledby="modal-title">
        <div class="bg-white rounded-xl max-w-2xl w-full max-h-[90vh] overflow-y-auto shadow-2xl border border-kita-border">
            <div class="sticky top-0 bg-kita-navy text-white px-4 py-3 flex items-center justify-between gap-3 z-10">
                <h3 id="modal-title" class="text-sm sm:text-base font-bold leading-snug">Chi tiết hạng mục</h3>
                <button id="modal-close" type="button" class="w-8 h-8 rounded-lg bg-white/10 hover:bg-kita-gold flex items-center justify-center text-white shrink-0" aria-label="Đóng cửa sổ">
                    <i class="fa-solid fa-xmark"></i>
                </button>
            </div>
            <div class="p-4 sm:p-5">
                <div class="aspect-[16/10] w-full rounded-lg overflow-hidden bg-slate-100 mb-4">
                    <img id="modal-image" src="" alt="" class="w-full h-full object-cover">
                </div>
                <div id="modal-meta" class="text-xs font-semibold text-kita-gold mb-2"></div>
                <p id="modal-desc" class="text-xs sm:text-sm text-kita-muted leading-relaxed mb-5"></p>
                <div class="flex flex-wrap items-center justify-between gap-3 pt-4 border-t border-slate-100">
                    <a href="tel:0328785252" class="inline-flex items-center gap-2 bg-kita-navy hover:bg-kita-gold text-white text-xs sm:text-sm font-semibold px-4 py-2.5 rounded-lg transition-colors">
                        <i class="fa-solid fa-phone"></i>
                        <span>Gọi tư vấn: 0328.785.252</span>
                    </a>
                    <a href="#bao-gia" id="modal-quote-btn" class="inline-flex items-center gap-2 border border-kita-navy text-kita-navy hover:bg-kita-navy hover:text-white text-xs sm:text-sm font-semibold px-4 py-2.5 rounded-lg transition-colors">
                        <span>Nhận báo giá hạng mục này</span>
                    </a>
                </div>
            </div>
        </div>
    </div>

    <!-- ======================================================================= -->
    <!-- JAVASCRIPT: DỮ LIỆU ẢNH GOOGLE DRIVE, SLIDER, BỘ LỌC, MODAL & FORM     -->
    <!-- ======================================================================= -->
    <script>
        (function () {
            "use strict";

            /* -------------------------------------------------------------------
             * 1. HÀM TẠO URL ẢNH GOOGLE DRIVE & FALLBACK AN TOÀN
             * Sử dụng endpoint thumbnail chính thức của Drive, dự phòng sang lh3
             * và ảnh placeholder nếu mạng bị chặn.
             * ------------------------------------------------------------------- */
            function getDriveImgUrl(fileId, width) {
                const size = width || 1000;
                return "https://drive.google.com/thumbnail?id=" + fileId + "&sz=w" + size;
            }

            function attachDriveFallback(imgEl) {
                if (!imgEl || imgEl.dataset.fallbackBound === "1") return;
                imgEl.dataset.fallbackBound = "1";
                imgEl.addEventListener("error", function () {
                    const step = parseInt(imgEl.dataset.errStep || "0", 10);
                    const fileId = imgEl.dataset.driveId;
                    if (step === 0 && fileId) {
                        imgEl.dataset.errStep = "1";
                        imgEl.src = "https://lh3.googleusercontent.com/d/" + fileId + "=w1000";
                    } else if (step <= 1) {
                        imgEl.dataset.errStep = "2";
                        const label = encodeURIComponent(imgEl.alt || "Xay Dung KITA");
                        imgEl.src = "https://placehold.co/800x600/0E2F56/FFFFFF?text=" + label;
                    }
                });
            }

            // Gắn fallback cho tất cả ảnh Drive tĩnh có sẵn trên trang
            document.querySelectorAll("img.drive-img").forEach(attachDriveFallback);

            /* -------------------------------------------------------------------
             * 2. DỮ LIỆU 9 ẢNH THỰC TẾ THI CÔNG XÂY DỰNG (SẢN PHẨM & DỊCH VỤ)
             * Đồng bộ danh mục theo trang mẫu tintruongthinh.com
             * ------------------------------------------------------------------- */
            const constructionProducts = [
                {
                    id: "13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz",
                    title: "Thi công phần thô kết cấu bê tông cốt thép chuẩn kỹ thuật",
                    category: "phan-tho",
                    categoryLabel: "Thi công phần thô",
                    desc: "Hạng mục thi công móng, dầm, sàn bê tông cốt thép và tường bao chuẩn mác thiết kế. Đội ngũ kỹ sư KITA trực tiếp nghiệm thu cốt thép, cốp pha và bảo dưỡng bê tông tiêu chuẩn."
                },
                {
                    id: "1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR",
                    title: "Thiết kế kiến trúc mặt tiền nhà phố hiện đại tại Đà Nẵng",
                    category: "thiet-ke",
                    categoryLabel: "Thiết kế Kiến trúc – Nội thất",
                    desc: "Giải pháp thiết kế kiến trúc tối ưu ánh sáng tự nhiên, thông gió đối lưu và đường nét mặt tiền sang trọng, phù hợp quỹ đất đô thị tại Đà Nẵng."
                },
                {
                    id: "1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv",
                    title: "Thi công xây dựng nhà phố trọn gói chìa khóa trao tay",
                    category: "tron-goi",
                    categoryLabel: "Xây nhà trọn gói",
                    desc: "Dịch vụ xây nhà trọn gói từ xin phép xây dựng, thiết kế hồ sơ kỹ thuật đến thi công phần thô, hoàn thiện và lắp đặt thiết bị đồng bộ, không phát sinh chi phí."
                },
                {
                    id: "1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_",
                    title: "Thi công hoàn thiện nội thất phòng khách và không gian bếp",
                    category: "noi-that",
                    categoryLabel: "Thi công nội thất",
                    desc: "Gia công và lắp đặt nội thất gỗ công nghiệp chống ẩm An Cường kết hợp đá ốp tự nhiên, hệ đèn chiếu sáng âm trần mang lại không gian sống tiện nghi."
                },
                {
                    id: "1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO",
                    title: "Thi công cốp pha sàn và lắp dựng cốt thép công trình nhiều tầng",
                    category: "phan-tho",
                    categoryLabel: "Thi công phần thô",
                    desc: "Kiểm soát chặt chẽ độ võng cốp pha, khoảng cách cốt thép và bảo hộ an toàn lao động tại công trường cho công trình nhà ở và căn hộ nhiều tầng."
                },
                {
                    id: "1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t",
                    title: "Thi công hoàn thiện tô trát, ốp lát và chống thấm chuyên sâu",
                    category: "hoan-thien",
                    categoryLabel: "Thi công hoàn thiện",
                    desc: "Xử lý chống thấm sàn mái, nhà vệ sinh, ban công bằng vật liệu Sika chính hãng; ốp lát gạch phẳng chuẩn laser và sơn nước ngoại thất bền màu."
                },
                {
                    id: "1UB12E_spzIvo7TNREjBJXUV9o_HVWOv_",
                    title: "Thi công hoàn thiện hệ thống điện nước M&E âm tường",
                    category: "hoan-thien",
                    categoryLabel: "Thi công hoàn thiện",
                    desc: "Lắp đặt hệ thống điện Cadivi, thiết bị đóng cắt Panasonic và đường ống cấp thoát nước Bình Minh thử áp lực chuẩn kỹ thuật trước khi tô trát hoàn thiện."
                },
                {
                    id: "1wHGqk7znpnGmrOjz4_EdpHnHK8xKyxkT",
                    title: "Thiết kế và thi công cải tạo văn phòng, căn hộ cho thuê",
                    category: "thiet-ke",
                    categoryLabel: "Thiết kế Kiến trúc – Nội thất",
                    desc: "Tối ưu hóa số lượng phòng khai thác, nâng cao thẩm mỹ mặt tiền và hệ thống kỹ thuật cho mô hình căn hộ dịch vụ, khách sạn mini và văn phòng tại Đà Nẵng."
                },
                {
                    id: "1-eBgG9wF3I6_gyPir2CmCnwJg4sP7Bnn",
                    title: "Thi công hoàn thiện trọn gói biệt thự và công trình dân dụng",
                    category: "tron-goi",
                    categoryLabel: "Xây nhà trọn gói",
                    desc: "Cam kết bàn giao đúng tiến độ hợp đồng, kiểm tra chất lượng toàn diện từ ngoại thất, cửa nhôm kính Xingfa đến hệ thống nội thất hoàn chỉnh."
                }
            ];

            /* -------------------------------------------------------------------
             * 3. DỮ LIỆU 10 ẢNH DỰ ÁN THỰC TẾ TẠI ĐÀ NẴNG (GOOGLE DRIVE)
             * ------------------------------------------------------------------- */
            const danangProjects = [
                {
                    id: "157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT",
                    title: "Nhà phố hiện đại 3 tầng – Khu đô thị Hòa Xuân, Đà Nẵng",
                    type: "nha-pho",
                    location: "Hòa Xuân, Cẩm Lệ, Đà Nẵng",
                    desc: "Công trình nhà phố 3 tầng phong cách tối giản, mặt tiền thông thoáng kết hợp lam chắn nắng và cây xanh ban công do Xây Dựng KITA thi công trọn gói."
                },
                {
                    id: "1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff",
                    title: "Biệt thự phố 2 mặt tiền – Phường Ngũ Hành Sơn, Đà Nẵng",
                    type: "biet-thu",
                    location: "Ngũ Hành Sơn, TP Đà Nẵng",
                    desc: "Thiết kế và thi công hoàn thiện biệt thự 2 mặt tiền sang trọng, không gian mở kết nối sân vườn và phòng khách rộng rãi."
                },
                {
                    id: "1wkzckXZhRrWh3V2GIOfdqBmOwQTBVFhz",
                    title: "Tòa căn hộ dịch vụ cho thuê – Khu An Thượng, Đà Nẵng",
                    type: "khach-san-can-ho",
                    location: "An Thượng, Ngũ Hành Sơn, Đà Nẵng",
                    desc: "Thi công trọn gói tòa căn hộ cao cấp phục vụ khách lưu trú ven biển Mỹ Khê, đầy đủ tiện nghi nội thất và hệ thống kỹ thuật hiện đại."
                },
                {
                    id: "1I7lc3ghS0tyqh6Pq3xsZTidKsr0oT-8k",
                    title: "Nhà phố kết hợp kinh doanh – Khu Nam Việt Á, Đà Nẵng",
                    type: "nha-pho",
                    location: "Nam Việt Á, Ngũ Hành Sơn, Đà Nẵng",
                    desc: "Công trình nhà ở kết hợp mặt bằng thương mại tầng 1, tối ưu công năng sử dụng và hệ kết cấu chịu lực vượt nhịp rộng."
                },
                {
                    id: "1Q8VoCbT7s09UNaoI8GNcYdvKpJ2wz78N",
                    title: "Khách sạn mini ven biển – Quận Sơn Trà, Đà Nẵng",
                    type: "khach-san-can-ho",
                    location: "Sơn Trà, TP Đà Nẵng",
                    desc: "Thi công phần thô và hoàn thiện kiến trúc khách sạn lưu trú gần biển với vật liệu chống ăn mòn muối biển và cách âm tiêu chuẩn."
                },
                {
                    id: "1tkQlfZJTkaSunwOIMhfnzkEG2YHwxhML",
                    title: "Trụ sở văn phòng doanh nghiệp – Quận Hải Châu, Đà Nẵng",
                    type: "van-phong",
                    location: "Hải Châu, TP Đà Nẵng",
                    desc: "Thiết kế và thi công tòa nhà văn phòng làm việc hiện đại, mặt dựng kính cường lực lấy sáng tối đa và không gian làm việc linh hoạt."
                },
                {
                    id: "1An7LyMVwj3rhKZlsVnYQ2UrLe48IeTBF",
                    title: "Biệt thự nghỉ dưỡng sân vườn – Khu FPT City Đà Nẵng",
                    type: "biet-thu",
                    location: "FPT City, Ngũ Hành Sơn, Đà Nẵng",
                    desc: "Biệt thự hiện đại sử dụng vật liệu đá tự nhiên, gỗ nhựa ngoài trời và hệ cửa nhôm kính lớn kết nối cảnh quan sân vườn."
                },
                {
                    id: "1R1Da04pAYI9-NJz1IsAfa7pVKkuK7J-A",
                    title: "Nhà phố 4 tầng tối ưu công năng – Quận Thanh Khê, Đà Nẵng",
                    type: "nha-pho",
                    location: "Thanh Khê, TP Đà Nẵng",
                    desc: "Giải pháp kiến trúc giếng trời thông tầng giúp nhà phố trung tâm luôn mát mẻ, tràn ngập ánh sáng tự nhiên và tiện nghi cho gia đình đa thế hệ."
                },
                {
                    id: "1FdQEsiEBrIW5TiN22dvzV5g6amDPp-80",
                    title: "Căn hộ lưu trú cao cấp view sông – Hòa Cường, Đà Nẵng",
                    type: "khach-san-can-ho",
                    location: "Hải Châu, TP Đà Nẵng",
                    desc: "Thiết kế và thi công trọn gói tổ hợp căn hộ dịch vụ cao cấp, bàn giao hoàn chỉnh nội thất sẵn sàng khai thác vận hành."
                },
                {
                    id: "1So_3V4rw1y7lHegiIkYmh2Z9UIdozAL4",
                    title: "Văn phòng đại diện & Showroom – Quận Liên Chiểu, Đà Nẵng",
                    type: "van-phong",
                    location: "Liên Chiểu, TP Đà Nẵng",
                    desc: "Thi công hoàn thiện không gian showroom trưng bày kết hợp khối văn phòng điều hành chuyên nghiệp, tiến độ vượt kế hoạch."
                }
            ];

            /* -------------------------------------------------------------------
             * 4. DỮ LIỆU CÁC BÀI VIẾT / TIN TỨC TRANG CHỦ
             * ------------------------------------------------------------------- */
            const articlesData = [
                {
                    id: "13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz",
                    title: "Hướng dẫn bảo dưỡng bê tông móng và sàn đúng tiêu chuẩn kỹ thuật",
                    date: "18/11/2026",
                    excerpt: "Quy trình giữ ẩm và bảo dưỡng bê tông sau khi đổ giúp tăng cường độ chịu lực, hạn chế nứt bề mặt và kéo dài tuổi thọ công trình.",
                    fullText: "Bảo dưỡng bê tông trong 7 ngày đầu sau khi đổ là bước quyết định đến chất lượng kết cấu công trình. Tại Xây Dựng KITA, mọi sàn và móng sau khi đổ đều được che phủ bao tải giữ ẩm, tưới nước định kỳ theo chu kỳ 3 giờ/lần trong điều kiện nắng nóng miền Trung để đảm bảo thủy hóa xi măng hoàn toàn."
                },
                {
                    id: "1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR",
                    title: "Kinh nghiệm chọn đơn vị xây nhà trọn gói uy tín tại Đà Nẵng",
                    date: "12/11/2026",
                    excerpt: "Những tiêu chí quan trọng về hồ sơ năng lực, bảng dự toán vật tư và điều khoản bảo hành chủ đầu tư cần kiểm tra trước khi ký hợp đồng.",
                    fullText: "Khi xây nhà trọn gói tại Đà Nẵng, chủ đầu tư nên kiểm tra rõ bảng chủng loại vật tư phần thô và hoàn thiện, xem trực tiếp công trình thực tế nhà thầu đang thi công, đồng thời thống nhất tiến độ thanh toán theo từng giai đoạn nghiệm thu để đảm bảo minh bạch tuyệt đối."
                },
                {
                    id: "1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_",
                    title: "Thiết kế nội thất tối ưu không gian sống cho nhà phố diện tích hẹp",
                    date: "05/11/2026",
                    excerpt: "Cách phối hợp màu sắc, ánh sáng và nội thất thông minh giúp nhà phố ngang 4m - 5m trở nên rộng rãi, thoáng đãng và sang trọng hơn.",
                    fullText: "Với nhà phố mặt tiền 4m đến 5m, việc liên thông phòng khách – bếp, sử dụng tông màu sáng kết hợp điểm nhấn gỗ ấm và bố trí giếng trời giữa nhà giúp tăng cảm giác rộng rãi lên đến 30% mà vẫn đảm bảo sự riêng tư cho từng thành viên."
                },
                {
                    id: "1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t",
                    title: "03 lưu ý chống thấm và chống nóng cho nhà ở ven biển Đà Nẵng",
                    date: "29/10/2026",
                    excerpt: "Khí hậu nắng gió và mưa bão miền Trung đòi hỏi giải pháp xử lý tường hướng Tây, cổ ống và sân thượng đúng quy chuẩn ngay từ phần thô.",
                    fullText: "Các vị trí dễ thấm như sàn mái, ban công, khe tiếp giáp nhà liền kề và hộp kỹ thuật cần được xử lý chống thấm 2 thành phần kết hợp lưới gia cường ngay trước khi cán nền. Bên cạnh đó, sử dụng tường hai lớp hoặc sơn chống nóng cho mặt hướng Tây sẽ giảm nhiệt độ trong nhà đáng kể."
                }
            ];

            /* -------------------------------------------------------------------
             * 5. RENDER SẢN PHẨM THI CÔNG & BỘ LỌC DANH MỤC (KHÔNG NHÃN DÁN)
             * ------------------------------------------------------------------- */
            const productGrid = document.getElementById("product-grid");
            function renderProducts(filterCat) {
                if (!productGrid) return;
                const list = filterCat === "all"
                    ? constructionProducts
                    : constructionProducts.filter(function (item) { return item.category === filterCat; });

                productGrid.innerHTML = "";
                list.forEach(function (item) {
                    const card = document.createElement("article");
                    card.className = "flatsome-card bg-white border border-kita-border rounded-xl overflow-hidden flex flex-col cursor-pointer";
                    card.innerHTML =
                        '<div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">' +
                            '<img src="' + getDriveImgUrl(item.id, 900) + '" data-drive-id="' + item.id + '" alt="' + item.title + '" class="drive-img w-full h-full object-cover" loading="lazy">' +
                        '</div>' +
                        '<div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">' +
                            '<div>' +
                                '<p class="text-[10px] sm:text-[11px] font-semibold text-kita-gold uppercase tracking-wide mb-1">' + item.categoryLabel + '</p>' +
                                '<h3 class="card-title-full text-xs sm:text-sm md:text-[15px] font-bold text-kita-navy leading-snug">' + item.title + '</h3>' +
                            '</div>' +
                            '<div class="mt-2.5 pt-2.5 border-t border-slate-100 flex items-center justify-between text-[11px] sm:text-xs font-semibold text-kita-navy">' +
                                '<span>Xem chi tiết</span>' +
                                '<i class="fa-solid fa-arrow-right text-kita-gold text-[10px]"></i>' +
                            '</div>' +
                        '</div>';

                    attachDriveFallback(card.querySelector("img"));
                    card.addEventListener("click", function () {
                        openModal(item.title, item.categoryLabel, item.desc, item.id);
                    });
                    productGrid.appendChild(card);
                });
            }

            /* -------------------------------------------------------------------
             * 6. RENDER 10 DỰ ÁN TẠI ĐÀ NẴNG & BỘ LỌC DANH MỤC
             * ------------------------------------------------------------------- */
            const projectGrid = document.getElementById("project-grid");
            function renderProjects(filterType) {
                if (!projectGrid) return;
                const list = filterType === "all"
                    ? danangProjects
                    : danangProjects.filter(function (p) { return p.type === filterType; });

                projectGrid.innerHTML = "";
                list.forEach(function (proj) {
                    const card = document.createElement("article");
                    card.className = "flatsome-card bg-white border border-kita-border rounded-xl overflow-hidden flex flex-col cursor-pointer";
                    card.innerHTML =
                        '<div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">' +
                            '<img src="' + getDriveImgUrl(proj.id, 900) + '" data-drive-id="' + proj.id + '" alt="' + proj.title + '" class="drive-img w-full h-full object-cover" loading="lazy">' +
                        '</div>' +
                        '<div class="p-3 sm:p-3.5 flex-1 flex flex-col justify-between">' +
                            '<h3 class="card-title-full text-xs sm:text-[13px] font-bold text-kita-navy leading-snug mb-2">' + proj.title + '</h3>' +
                            '<div class="flex items-start gap-1 text-[10px] sm:text-[11px] text-kita-muted">' +
                                '<i class="fa-solid fa-location-dot text-kita-gold mt-0.5 shrink-0"></i>' +
                                '<span class="card-title-full">' + proj.location + '</span>' +
                            '</div>' +
                        '</div>';

                    attachDriveFallback(card.querySelector("img"));
                    card.addEventListener("click", function () {
                        openModal(proj.title, "Địa điểm: " + proj.location, proj.desc, proj.id);
                    });
                    projectGrid.appendChild(card);
                });
            }

            /* -------------------------------------------------------------------
             * 7. RENDER BÀI VIẾT TIN TỨC TRANG CHỦ
             * ------------------------------------------------------------------- */
            const articlesGrid = document.getElementById("articles-grid");
            function renderArticles() {
                if (!articlesGrid) return;
                articlesGrid.innerHTML = "";
                articlesData.forEach(function (art) {
                    const card = document.createElement("article");
                    card.className = "flatsome-card bg-white border border-kita-border rounded-xl overflow-hidden flex flex-col cursor-pointer";
                    card.innerHTML =
                        '<div class="aspect-[16/10] w-full overflow-hidden bg-slate-100">' +
                            '<img src="' + getDriveImgUrl(art.id, 800) + '" data-drive-id="' + art.id + '" alt="' + art.title + '" class="drive-img w-full h-full object-cover" loading="lazy">' +
                        '</div>' +
                        '<div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">' +
                            '<div>' +
                                '<div class="text-[10px] sm:text-[11px] text-kita-muted mb-1"><i class="fa-regular fa-calendar text-kita-gold mr-1"></i>' + art.date + '</div>' +
                                '<h3 class="card-title-full text-xs sm:text-sm font-bold text-kita-navy leading-snug mb-2">' + art.title + '</h3>' +
                                '<p class="text-[11px] sm:text-xs text-kita-muted leading-relaxed">' + art.excerpt + '</p>' +
                            '</div>' +
                            '<div class="mt-3 text-[11px] sm:text-xs font-semibold text-kita-gold">Đọc tiếp <i class="fa-solid fa-angle-right ml-0.5"></i></div>' +
                        '</div>';

                    attachDriveFallback(card.querySelector("img"));
                    card.addEventListener("click", function () {
                        openModal(art.title, "Ngày đăng: " + art.date + " | Cẩm nang Xây Dựng KITA", art.fullText, art.id);
                    });
                    articlesGrid.appendChild(card);
                });
            }

            // Khởi tạo hiển thị dữ liệu
            renderProducts("all");
            renderProjects("all");
            renderArticles();

            /* -------------------------------------------------------------------
             * 8. XỬ LÝ CHUYỂN TAB DANH MỤC SẢN PHẨM & DỰ ÁN
             * ------------------------------------------------------------------- */
            function setupTabGroup(selector, attrName, onSelect) {
                const buttons = document.querySelectorAll(selector);
                buttons.forEach(function (btn) {
                    btn.addEventListener("click", function () {
                        buttons.forEach(function (b) {
                            b.classList.remove("bg-kita-navy", "text-white", "border-kita-navy", "active");
                            b.classList.add("bg-white", "text-kita-navy", "border-kita-border");
                        });
                        btn.classList.remove("bg-white", "text-kita-navy", "border-kita-border");
                        btn.classList.add("bg-kita-navy", "text-white", "border-kita-navy", "active");
                        onSelect(btn.getAttribute(attrName));
                    });
                });
            }

            setupTabGroup(".product-tab", "data-cat", renderProducts);
            setupTabGroup(".project-tab", "data-proj", renderProjects);

            /* -------------------------------------------------------------------
             * 9. SLIDER 2 BANNER TỰ TRƯỢT + HỖ TRỢ VUỐT TRÊN ĐIỆN THOẠI
             * ------------------------------------------------------------------- */
            const slides = document.querySelectorAll(".hero-slide-item");
            const dots = document.querySelectorAll(".banner-dot");
            const prevBtn = document.getElementById("banner-prev");
            const nextBtn = document.getElementById("banner-next");
            const sliderEl = document.getElementById("hero-slider");
            let currentSlide = 0;
            let slideTimer = null;

            function showSlide(index) {
                if (!slides.length) return;
                currentSlide = (index + slides.length) % slides.length;
                slides.forEach(function (s, idx) {
                    s.classList.toggle("active", idx === currentSlide);
                });
                dots.forEach(function (d, idx) {
                    if (idx === currentSlide) {
                        d.classList.add("w-6", "bg-kita-gold");
                        d.classList.remove("w-2.5", "bg-white/50");
                    } else {
                        d.classList.remove("w-6", "bg-kita-gold");
                        d.classList.add("w-2.5", "bg-white/50");
                    }
                });
            }

            function startAutoSlide() {
                stopAutoSlide();
                slideTimer = setInterval(function () {
                    showSlide(currentSlide + 1);
                }, 5500);
            }

            function stopAutoSlide() {
                if (slideTimer) {
                    clearInterval(slideTimer);
                    slideTimer = null;
                }
            }

            if (prevBtn) {
                prevBtn.addEventListener("click", function () {
                    showSlide(currentSlide - 1);
                    startAutoSlide();
                });
            }
            if (nextBtn) {
                nextBtn.addEventListener("click", function () {
                    showSlide(currentSlide + 1);
                    startAutoSlide();
                });
            }
            dots.forEach(function (dot) {
                dot.addEventListener("click", function () {
                    const idx = parseInt(dot.getAttribute("data-index"), 10);
                    showSlide(idx);
                    startAutoSlide();
                });
            });

            // Hỗ trợ thao tác vuốt cảm ứng trên điện thoại cho Banner
            if (sliderEl) {
                let touchStartX = 0;
                sliderEl.addEventListener("touchstart", function (e) {
                    touchStartX = e.changedTouches[0].screenX;
                    stopAutoSlide();
                }, { passive: true });
                sliderEl.addEventListener("touchend", function (e) {
                    const diff = e.changedTouches[0].screenX - touchStartX;
                    if (Math.abs(diff) > 40) {
                        showSlide(diff < 0 ? currentSlide + 1 : currentSlide - 1);
                    }
                    startAutoSlide();
                }, { passive: true });
            }
            startAutoSlide();

            /* -------------------------------------------------------------------
             * 10. MENU MOBILE & MODAL CHI TIẾT
             * ------------------------------------------------------------------- */
            const mobileMenuBtn = document.getElementById("mobile-menu-btn");
            const mobileMenuPanel = document.getElementById("mobile-menu-panel");
            if (mobileMenuBtn && mobileMenuPanel) {
                mobileMenuBtn.addEventListener("click", function () {
                    const isHidden = mobileMenuPanel.classList.contains("hidden");
                    mobileMenuPanel.classList.toggle("hidden");
                    mobileMenuBtn.setAttribute("aria-expanded", String(isHidden));
                });
                document.querySelectorAll(".mobile-nav-link").forEach(function (link) {
                    link.addEventListener("click", function () {
                        mobileMenuPanel.classList.add("hidden");
                        mobileMenuBtn.setAttribute("aria-expanded", "false");
                    });
                });
            }

            const modal = document.getElementById("detail-modal");
            const modalTitle = document.getElementById("modal-title");
            const modalMeta = document.getElementById("modal-meta");
            const modalDesc = document.getElementById("modal-desc");
            const modalImg = document.getElementById("modal-image");
            const modalClose = document.getElementById("modal-close");
            const modalQuoteBtn = document.getElementById("modal-quote-btn");

            function openModal(title, meta, desc, driveId) {
                if (!modal) return;
                modalTitle.textContent = title;
                modalMeta.textContent = meta;
                modalDesc.textContent = desc;
                modalImg.dataset.driveId = driveId;
                modalImg.dataset.errStep = "0";
                modalImg.alt = title;
                modalImg.src = getDriveImgUrl(driveId, 1200);
                attachDriveFallback(modalImg);

                modal.classList.remove("hidden");
                modal.classList.add("flex");
                document.body.style.overflow = "hidden";
            }

            function closeModal() {
                if (!modal) return;
                modal.classList.add("hidden");
                modal.classList.remove("flex");
                document.body.style.overflow = "";
            }

            if (modalClose) modalClose.addEventListener("click", closeModal);
            if (modalQuoteBtn) modalQuoteBtn.addEventListener("click", closeModal);
            if (modal) {
                modal.addEventListener("click", function (e) {
                    if (e.target === modal) closeModal();
                });
            }
            document.addEventListener("keydown", function (e) {
                if (e.key === "Escape") closeModal();
            });

            /* -------------------------------------------------------------------
             * 11. XỬ LÝ FORM YÊU CẦU TƯ VẤN & BÁO GIÁ (KHÔNG DÙNG ALERT)
             * ------------------------------------------------------------------- */
            const quoteForm = document.getElementById("quote-form");
            const quoteFeedback = document.getElementById("quote-feedback");

            if (quoteForm && quoteFeedback) {
                quoteForm.addEventListener("submit", function (e) {
                    e.preventDefault();
                    const nameVal = document.getElementById("q-name").value.trim();
                    const phoneVal = document.getElementById("q-phone").value.trim();
                    const typeVal = document.getElementById("q-type").value;

                    quoteFeedback.classList.remove("hidden", "bg-red-50", "text-red-700", "border", "border-red-200", "bg-emerald-50", "text-emerald-800", "border-emerald-200");

                    if (!nameVal || !phoneVal) {
                        quoteFeedback.classList.add("bg-red-50", "text-red-700", "border", "border-red-200");
                        quoteFeedback.innerHTML = '<i class="fa-solid fa-circle-exclamation mr-1.5"></i>Vui lòng nhập đầy đủ Họ và tên và Số điện thoại để kỹ sư KITA liên hệ tư vấn.';
                        return;
                    }

                    quoteFeedback.classList.add("bg-emerald-50", "text-emerald-800", "border", "border-emerald-200");
                    quoteFeedback.innerHTML =
                        '<i class="fa-solid fa-circle-check mr-1.5"></i>Cảm ơn <strong>' + nameVal + '</strong>! Yêu cầu báo giá hạng mục <strong>' + typeVal + '</strong> đã được gửi tới Xây Dựng KITA. Chúng tôi sẽ gọi lại số <strong>' + phoneVal + '</strong> trong thời gian sớm nhất (Hotline: 0328.785.252).';
                    quoteForm.reset();
                });
            }
        })();
    </script>
</body>
</html>
