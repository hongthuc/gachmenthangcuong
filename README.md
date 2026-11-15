<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=5.0">
    <title>Gạch Men Thắng Cường - Tổng Kho Gạch Ốp Lát & Thiết Bị Vệ Sinh Đà Nẵng</title>
    <meta name="description" content="Gạch men Thắng Cường (gachmenthangcuong.com) - Tổng kho phân phối gạch lát nền, gạch ốp tường, gạch khổ lớn, gạch trang trí và thiết bị vệ sinh chính hãng tại Xã Núi Thành, Tp. Đà Nẵng. Hotline: 0896666236.">

    <!-- Open Graph / Thumbnail là ảnh Logo khi gửi link trang web qua Zalo, Facebook -->
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://gachmenthangcuong.com/">
    <meta property="og:site_name" content="gachmenthangcuong.com">
    <meta property="og:title" content="Gạch Men Thắng Cường - Tổng Kho Gạch Ốp Lát Cao Cấp">
    <meta property="og:description" content="Chuyên phân phối gạch lát nền 60x60, 80x80, 100x100, gạch khổ lớn 60x120, 80x160, 1200x2400, gạch trang trí & thiết bị vệ sinh tại Xã Núi Thành, Tp. Đà Nẵng. ĐT: 0896666236.">
    <meta property="og:image" content="https://drive.google.com/thumbnail?id=1AOQpSlLMl8y-XyUpqqHvErHWgy-mI7Uu&sz=w800">
    <meta property="og:image:alt" content="Logo Gạch Men Thắng Cường">
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:image" content="https://drive.google.com/thumbnail?id=1AOQpSlLMl8y-XyUpqqHvErHWgy-mI7Uu&sz=w800">
    <link rel="icon" type="image/png" href="https://drive.google.com/thumbnail?id=1AOQpSlLMl8y-XyUpqqHvErHWgy-mI7Uu&sz=w200">

    <!-- Google Fonts: Inter -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">

    <!-- Font Awesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">

    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                    },
                    colors: {
                        brand: {
                            DEFAULT: '#0f3b68',
                            dark: '#092542',
                            light: '#1d5691',
                            accent: '#c81e1e',
                            gold: '#d97706',
                            bg: '#f6f8fa'
                        }
                    }
                }
            }
        }
    </script>

    <style>
        /* Reset & Chống tràn viền, chống lệch phải tuyệt đối */
        *, *::before, *::after {
            box-sizing: border-box;
        }
        html, body {
            width: 100%;
            max-width: 100vw;
            overflow-x: hidden;
            margin: 0;
            padding: 0;
            font-family: 'Inter', sans-serif;
            background-color: #f5f7fa;
            color: #1e293b;
            scroll-behavior: smooth;
        }

        /* Chiều ngang giao diện trên máy tính bằng 95% kích thước màn hình máy tính */
        .flatsome-container {
            width: 100%;
            padding-left: 12px;
            padding-right: 12px;
            margin-left: auto;
            margin-right: auto;
        }
        @media (min-width: 1024px) {
            .flatsome-container {
                width: 95%;
                max-width: 95%;
                padding-left: 0;
                padding-right: 0;
            }
        }

        /* Menu danh mục trên máy tính: chữ nhỏ gọn, viết liền trên 1 hàng, không xuống dòng từng tên danh mục */
        .desktop-cat-nav {
            display: flex;
            flex-wrap: wrap;
            align-items: center;
            justify-content: center;
            gap: 2px 6px;
        }
        .desktop-cat-link {
            white-space: nowrap !important;
            display: inline-flex;
            align-items: center;
            gap: 4px;
            padding: 7px 9px;
            font-size: 12px;
            font-weight: 700;
            letter-spacing: 0.01em;
            text-transform: uppercase;
            color: #ffffff;
            border-radius: 4px;
            transition: background-color 0.2s ease, color 0.2s ease;
        }
        @media (min-width: 1280px) {
            .desktop-cat-link {
                font-size: 12.5px;
                padding: 8px 11px;
            }
        }
        .desktop-cat-link:hover, .desktop-cat-link.active {
            background-color: rgba(255, 255, 255, 0.16);
            color: #fde047;
        }

        /* Dropdown Submenu kiểu Flatsome */
        .nav-item-has-children {
            position: relative;
        }
        .nav-dropdown {
            display: none;
            position: absolute;
            top: 100%;
            left: 0;
            min-width: 200px;
            background: #ffffff;
            box-shadow: 0 10px 25px rgba(0,0,0,0.14);
            border-top: 3px solid #c81e1e;
            border-radius: 0 0 6px 6px;
            z-index: 60;
            padding: 6px 0;
        }
        .nav-item-has-children:hover .nav-dropdown {
            display: block;
        }
        .nav-dropdown a {
            display: block;
            padding: 8px 14px;
            font-size: 12.5px;
            font-weight: 600;
            color: #334155;
            white-space: nowrap;
            border-bottom: 1px solid #f1f5f9;
            transition: all 0.15s ease;
        }
        .nav-dropdown a:last-child {
            border-bottom: none;
        }
        .nav-dropdown a:hover {
            background: #f8fafc;
            color: #0f3b68;
            padding-left: 18px;
        }

        /* Tiêu đề Section chuẩn Flatsome UX Builder */
        .section-title-container {
            margin-bottom: 16px;
        }
        .section-title-normal {
            display: flex;
            align-items: center;
            justify-content: space-between;
            border-bottom: 2px solid #e2e8f0;
            padding-bottom: 8px;
            gap: 10px;
            flex-wrap: wrap;
        }
        .section-title-main {
            font-size: 15px;
            font-weight: 800;
            text-transform: uppercase;
            color: #0f3b68;
            border-bottom: 3px solid #c81e1e;
            padding-bottom: 8px;
            margin-bottom: -10px;
            display: inline-flex;
            align-items: center;
            gap: 8px;
        }
        @media (min-width: 768px) {
            .section-title-main {
                font-size: 18px;
            }
        }

        /* 2 Banner tự trượt kích thước bằng nhau tuyệt đối, chữ cách xa viền */
        .hero-banner-wrapper {
            position: relative;
            width: 100%;
            height: 250px;
            border-radius: 10px;
            overflow: hidden;
            background: #092542;
        }
        @media (min-width: 640px) {
            .hero-banner-wrapper {
                height: 310px;
            }
        }
        @media (min-width: 1024px) {
            .hero-banner-wrapper {
                height: 370px;
            }
        }
        .hero-slide {
            position: absolute;
            inset: 0;
            width: 100%;
            height: 100%;
            opacity: 0;
            visibility: hidden;
            transition: opacity 0.65s ease-in-out, visibility 0.65s ease-in-out;
        }
        .hero-slide.active {
            opacity: 1;
            visibility: visible;
            z-index: 10;
        }

        /* Nhãn % Giảm Giá góc trên bên trái chuẩn Flatsome */
        .flatsome-discount-badge {
            position: absolute;
            top: 8px;
            left: 8px;
            z-index: 15;
            background-color: #c81e1e;
            color: #ffffff;
            font-size: 11px;
            font-weight: 800;
            width: 38px;
            height: 38px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            box-shadow: 0 2px 6px rgba(200, 30, 30, 0.35);
            line-height: 1;
        }
        @media (min-width: 640px) {
            .flatsome-discount-badge {
                width: 42px;
                height: 42px;
                font-size: 12px;
            }
        }

        /* Tên sản phẩm không bị tràn hoặc thiếu chữ */
        .product-title-full {
            font-size: 13px;
            line-height: 1.38;
            font-weight: 600;
            color: #1e293b;
            white-space: normal;
            word-break: break-word;
            overflow-wrap: break-word;
            display: block;
            margin-bottom: 6px;
        }
        @media (min-width: 640px) {
            .product-title-full {
                font-size: 14px;
            }
        }

        /* Danh mục nhỏ gọn, không xuống dòng tên danh mục */
        .cat-chip-title {
            white-space: nowrap;
            font-size: 11.5px;
            font-weight: 700;
            line-height: 1.25;
            color: #0f3b68;
        }
        @media (min-width: 768px) {
            .cat-chip-title {
                font-size: 12.5px;
            }
        }

        /* Nút liên hệ nổi bật cố định góc phải */
        @keyframes pulseRing {
            0% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(200, 30, 30, 0.6); }
            70% { transform: scale(1); box-shadow: 0 0 0 10px rgba(200, 30, 30, 0); }
            100% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(200, 30, 30, 0); }
        }
        .floating-pulse {
            animation: pulseRing 2s infinite;
        }
    </style>
</head>
<body>

    <!-- ================= HEADER (CHUẨN FLATSOME - KHÔNG CÓ NÚT GỌI NGAY ĐỂ TRÁNH TRÀN VIỀN) ================= -->
    <header id="header" class="bg-white shadow-sm sticky top-0 z-50 w-full">
        <!-- Dòng thông tin mỏng phía trên -->
        <div class="bg-slate-100 border-b border-slate-200 text-slate-600 text-[11px] sm:text-xs py-1.5">
            <div class="flatsome-container flex flex-wrap items-center justify-between gap-2">
                <div class="flex items-center gap-2 truncate">
                    <i class="fa-solid fa-location-dot text-brand-accent"></i>
                    <span class="font-medium truncate">Đ/c: Xã Núi Thành, Tp. Đà Nẵng</span>
                    <span class="hidden md:inline text-slate-300">|</span>
                    <span class="hidden md:inline font-medium text-brand">Website: gachmenthangcuong.com</span>
                </div>
                <div class="flex items-center gap-3 shrink-0">
                    <a href="#bang-bao-gia" class="hover:text-brand font-medium">Yêu cầu báo giá</a>
                    <span class="text-slate-300">|</span>
                    <a href="#tin-tuc" class="hover:text-brand font-medium">Tin tức</a>
                    <span class="text-slate-300">|</span>
                    <a href="#ban-do" class="hover:text-brand font-medium">Chỉ đường</a>
                </div>
            </div>
        </div>

        <!-- Header Main: Logo nhỏ gọn + Thanh tìm kiếm (Không để nút gọi ngay) -->
        <div class="py-2.5 bg-white">
            <div class="flatsome-container flex items-center justify-between gap-3">
                <!-- Nút mở menu trên điện thoại -->
                <button id="mobileMenuBtn" type="button" aria-label="Mở danh mục" class="lg:hidden p-2 rounded-md border border-slate-200 text-brand hover:bg-slate-50 shrink-0">
                    <i class="fa-solid fa-bars text-lg"></i>
                </button>

                <!-- Logo chỉnh gọn nhỏ lại -->
                <a href="#" class="flex items-center gap-2.5 shrink-0 group">
                    <div class="w-10 h-10 sm:w-11 sm:h-11 rounded-md border border-slate-200 bg-white p-0.5 flex items-center justify-center overflow-hidden shrink-0">
                        <img id="siteLogoImg"
                             src="https://drive.google.com/thumbnail?id=1AOQpSlLMl8y-XyUpqqHvErHWgy-mI7Uu&sz=w400"
                             data-drive-id="1AOQpSlLMl8y-XyUpqqHvErHWgy-mI7Uu"
                             onerror="handleDriveImageError(this, 'TC')"
                             alt="Logo Gạch Men Thắng Cường"
                             class="w-full h-full object-contain">
                    </div>
                    <div class="leading-tight">
                        <span class="block text-sm sm:text-base md:text-lg font-extrabold text-brand tracking-tight uppercase">GẠCH MEN THẮNG CƯỜNG</span>
                        <span class="block text-[10px] sm:text-[11px] text-slate-500 font-medium">gachmenthangcuong.com • Núi Thành, Đà Nẵng</span>
                    </div>
                </a>

                <!-- Ô tìm kiếm sản phẩm kiểu Flatsome -->
                <div class="hidden sm:flex flex-1 max-w-md mx-2">
                    <div class="relative w-full flex items-center">
                        <input id="searchInputDesktop" type="text" placeholder="Tìm gạch 60x60, 80x80, 60x120, giả gỗ, mosaic..."
                               class="w-full pl-3.5 pr-10 py-2 text-xs sm:text-sm bg-slate-50 border border-slate-300 rounded-md focus:outline-none focus:border-brand focus:bg-white transition">
                        <button type="button" onclick="handleSearch('searchInputDesktop')" aria-label="Tìm kiếm" class="absolute right-1 top-1 bottom-1 px-3 bg-brand text-white rounded hover:bg-brand-dark transition">
                            <i class="fa-solid fa-magnifying-glass text-xs"></i>
                        </button>
                    </div>
                </div>

                <!-- Thông tin kho hàng nhỏ gọn trên máy tính (Không phải nút gọi ngay) -->
                <div class="hidden xl:flex items-center gap-4 text-xs text-slate-600 shrink-0">
                    <div class="flex items-center gap-2">
                        <i class="fa-solid fa-warehouse text-brand text-base"></i>
                        <div>
                            <div class="font-bold text-slate-800">Tổng Kho Chính Hãng</div>
                            <div class="text-[11px] text-slate-500">Giao hàng tận công trình</div>
                        </div>
                    </div>
                </div>
            </div>

            <!-- Thanh tìm kiếm trên điện thoại -->
            <div class="flatsome-container sm:hidden mt-2">
                <div class="relative w-full flex items-center">
                    <input id="searchInputMobile" type="text" placeholder="Tìm kích thước, mã gạch Thắng Cường..."
                           class="w-full pl-3 pr-9 py-1.5 text-xs bg-slate-50 border border-slate-300 rounded-md focus:outline-none focus:border-brand">
                    <button type="button" onclick="handleSearch('searchInputMobile')" aria-label="Tìm kiếm" class="absolute right-1 top-1 bottom-1 px-2.5 bg-brand text-white rounded">
                        <i class="fa-solid fa-magnifying-glass text-[11px]"></i>
                    </button>
                </div>
            </div>
        </div>

        <!-- Thanh Menu Danh Mục Máy Tính (Viết liền trên 1 hàng chữ nhỏ gọn, không bao giờ xuống dòng trong 1 tên danh mục) -->
        <nav class="hidden lg:block bg-brand border-t border-brand-dark w-full">
            <div class="flatsome-container py-1">
                <ul class="desktop-cat-nav">
                    <li>
                        <a href="#" onclick="filterByCategory('ALL'); return false;" class="desktop-cat-link active">
                            <i class="fa-solid fa-house text-[11px]"></i> TRANG CHỦ
                        </a>
                    </li>
                    <li class="nav-item-has-children">
                        <a href="#san-pham-lat-nen" onclick="filterByCategory('GẠCH LÁT NỀN'); return false;" class="desktop-cat-link">
                            GẠCH LÁT NỀN <i class="fa-solid fa-angle-down text-[10px] opacity-80"></i>
                        </a>
                        <div class="nav-dropdown">
                            <a href="#tat-ca-san-pham" onclick="filterBySubCat('Gạch 60x60')">GẠCH 60X60</a>
                            <a href="#tat-ca-san-pham" onclick="filterBySubCat('Gạch 80x80')">GẠCH 80X80</a>
                            <a href="#tat-ca-san-pham" onclick="filterBySubCat('Gạch 100x100')">GẠCH 100X100</a>
                            <a href="#tat-ca-san-pham" onclick="filterBySubCat('Gạch 120x120')">GẠCH 120X120</a>
                        </div>
                    </li>
                    <li class="nav-item-has-children">
                        <a href="#san-pham-op-tuong" onclick="filterByCategory('GẠCH ỐP TƯỜNG'); return false;" class="desktop-cat-link">
                            GẠCH ỐP TƯỜNG <i class="fa-solid fa-angle-down text-[10px] opacity-80"></i>
                        </a>
                        <div class="nav-dropdown">
                            <a href="#tat-ca-san-pham" onclick="filterBySubCat('Gạch 30x60')">GẠCH 30X60</a>
                            <a href="#tat-ca-san-pham" onclick="filterBySubCat('Gạch 60x120')">GẠCH 60X120</a>
                            <a href="#tat-ca-san-pham" onclick="filterBySubCat('Gạch 80x160')">GẠCH 80X160</a>
                            <a href="#tat-ca-san-pham" onclick="filterBySubCat('Gạch 75x150')">GẠCH 75X150</a>
                            <a href="#tat-ca-san-pham" onclick="filterBySubCat('Gạch 90x180')">GẠCH 90X180</a>
                        </div>
                    </li>
                    <li class="nav-item-has-children">
                        <a href="#san-pham-kho-lon" onclick="filterByCategory('GẠCH KHỔ LỚN'); return false;" class="desktop-cat-link">
                            GẠCH KHỔ LỚN <i class="fa-solid fa-angle-down text-[10px] opacity-80"></i>
                        </a>
                        <div class="nav-dropdown">
                            <a href="#tat-ca-san-pham" onclick="filterBySubCat('Gạch 1600x3200')">GẠCH 1600X3200</a>
                            <a href="#tat-ca-san-pham" onclick="filterBySubCat('Gạch 1200x2400')">GẠCH 1200X2400</a>
                            <a href="#tat-ca-san-pham" onclick="filterBySubCat('Gạch 1200x2800')">GẠCH 1200X2800</a>
                            <a href="#tat-ca-san-pham" onclick="filterBySubCat('Gạch 1200x1800')">GẠCH 1200X1800</a>
                            <a href="#tat-ca-san-pham" onclick="filterBySubCat('Gạch 60x120')">GẠCH 60X120</a>
                            <a href="#tat-ca-san-pham" onclick="filterBySubCat('Gạch 80x160')">GẠCH 80X160</a>
                        </div>
                    </li>
                    <li class="nav-item-has-children">
                        <a href="#san-pham-trang-tri" onclick="filterByCategory('GẠCH TRANG TRÍ'); return false;" class="desktop-cat-link">
                            GẠCH TRANG TRÍ <i class="fa-solid fa-angle-down text-[10px] opacity-80"></i>
                        </a>
                        <div class="nav-dropdown">
                            <a href="#tat-ca-san-pham" onclick="filterBySubCat('Gạch Terrazzo')">GẠCH TERRAZZO</a>
                            <a href="#tat-ca-san-pham" onclick="filterBySubCat('Gạch Giả Gỗ')">GẠCH GIẢ GỖ</a>
                            <a href="#tat-ca-san-pham" onclick="filterBySubCat('Gạch Mosaic')">GẠCH MOSAIC</a>
                            <a href="#tat-ca-san-pham" onclick="filterBySubCat('Gạch Bông')">GẠCH BÔNG</a>
                        </div>
                    </li>
                    <li class="nav-item-has-children">
                        <a href="#danh-muc-trang-chu" onclick="filterByCategory('THIẾT BỊ VỆ SINH'); return false;" class="desktop-cat-link">
                            THIẾT BỊ VỆ SINH <i class="fa-solid fa-angle-down text-[10px] opacity-80"></i>
                        </a>
                        <div class="nav-dropdown">
                            <a href="#bang-bao-gia">TỦ LAVABO</a>
                            <a href="#bang-bao-gia">BỒN CẦU</a>
                            <a href="#bang-bao-gia">LAVABO</a>
                            <a href="#bang-bao-gia">VÒI SEN TẮM</a>
                            <a href="#bang-bao-gia">BỒN TẮM</a>
                            <a href="#bang-bao-gia">PHỤ KIỆN NHÀ TẮM</a>
                        </div>
                    </li>
                    <li><a href="#doi-tac" class="desktop-cat-link">ĐỐI TÁC</a></li>
                    <li><a href="#tin-tuc" class="desktop-cat-link">BÀI VIẾT</a></li>
                    <li><a href="#bang-bao-gia" class="desktop-cat-link">BÁO GIÁ</a></li>
                    <li><a href="#ban-do" class="desktop-cat-link">LIÊN HỆ</a></li>
                </ul>
            </div>
        </nav>

        <!-- Thanh danh mục rút gọn ngang cho Điện thoại (Xem đẹp, lướt mượt, chữ không gãy dòng) -->
        <div class="lg:hidden bg-brand text-white border-t border-brand-dark overflow-x-auto no-scrollbar">
            <div class="flex items-center px-2 py-1.5 gap-1.5 min-w-max">
                <button onclick="filterByCategory('ALL')" class="px-2.5 py-1 text-[11px] font-bold uppercase rounded bg-white/15 text-yellow-300 whitespace-nowrap">Tất cả</button>
                <button onclick="filterByCategory('GẠCH LÁT NỀN')" class="px-2.5 py-1 text-[11px] font-bold uppercase rounded hover:bg-white/10 whitespace-nowrap">Gạch Lát Nền</button>
                <button onclick="filterByCategory('GẠCH ỐP TƯỜNG')" class="px-2.5 py-1 text-[11px] font-bold uppercase rounded hover:bg-white/10 whitespace-nowrap">Gạch Ốp Tường</button>
                <button onclick="filterByCategory('GẠCH KHỔ LỚN')" class="px-2.5 py-1 text-[11px] font-bold uppercase rounded hover:bg-white/10 whitespace-nowrap">Gạch Khổ Lớn</button>
                <button onclick="filterByCategory('GẠCH TRANG TRÍ')" class="px-2.5 py-1 text-[11px] font-bold uppercase rounded hover:bg-white/10 whitespace-nowrap">Gạch Trang Trí</button>
                <a href="#bang-bao-gia" class="px-2.5 py-1 text-[11px] font-bold uppercase rounded hover:bg-white/10 whitespace-nowrap">Thiết Bị Vệ Sinh</a>
                <a href="#doi-tac" class="px-2.5 py-1 text-[11px] font-bold uppercase rounded hover:bg-white/10 whitespace-nowrap">Đối Tác</a>
                <a href="#bang-bao-gia" class="px-2.5 py-1 text-[11px] font-bold uppercase rounded hover:bg-white/10 whitespace-nowrap">Báo Giá</a>
            </div>
        </div>
    </header>

    <!-- Menu Drawer trên Điện thoại -->
    <div id="mobileMenuDrawer" class="fixed inset-0 z-50 hidden">
        <div class="absolute inset-0 bg-black/50" onclick="toggleMobileMenu(false)"></div>
        <div class="relative w-72 max-w-[82vw] h-full bg-white shadow-2xl flex flex-col overflow-y-auto">
            <div class="p-3.5 bg-brand text-white flex items-center justify-between">
                <span class="font-bold text-sm uppercase tracking-wide">DANH MỤC SẢN PHẨM</span>
                <button type="button" onclick="toggleMobileMenu(false)" class="w-7 h-7 rounded bg-white/10 flex items-center justify-center">
                    <i class="fa-solid fa-xmark"></i>
                </button>
            </div>
            <div class="p-3 divide-y divide-slate-100 text-xs font-semibold text-slate-700">
                <div class="py-2">
                    <div class="text-brand font-bold uppercase mb-1.5">GẠCH LÁT NỀN</div>
                    <div class="grid grid-cols-2 gap-1.5 pl-1">
                        <a href="#tat-ca-san-pham" onclick="filterBySubCat('Gạch 60x60'); toggleMobileMenu(false);" class="py-1 px-2 bg-slate-50 rounded">Gạch 60x60</a>
                        <a href="#tat-ca-san-pham" onclick="filterBySubCat('Gạch 80x80'); toggleMobileMenu(false);" class="py-1 px-2 bg-slate-50 rounded">Gạch 80x80</a>
                        <a href="#tat-ca-san-pham" onclick="filterBySubCat('Gạch 100x100'); toggleMobileMenu(false);" class="py-1 px-2 bg-slate-50 rounded">Gạch 100x100</a>
                        <a href="#tat-ca-san-pham" onclick="filterBySubCat('Gạch 120x120'); toggleMobileMenu(false);" class="py-1 px-2 bg-slate-50 rounded">Gạch 120x120</a>
                    </div>
                </div>
                <div class="py-2">
                    <div class="text-brand font-bold uppercase mb-1.5">GẠCH ỐP TƯỜNG</div>
                    <div class="grid grid-cols-2 gap-1.5 pl-1">
                        <a href="#tat-ca-san-pham" onclick="filterBySubCat('Gạch 30x60'); toggleMobileMenu(false);" class="py-1 px-2 bg-slate-50 rounded">Gạch 30x60</a>
                        <a href="#tat-ca-san-pham" onclick="filterBySubCat('Gạch 60x120'); toggleMobileMenu(false);" class="py-1 px-2 bg-slate-50 rounded">Gạch 60x120</a>
                        <a href="#tat-ca-san-pham" onclick="filterBySubCat('Gạch 80x160'); toggleMobileMenu(false);" class="py-1 px-2 bg-slate-50 rounded">Gạch 80x160</a>
                        <a href="#tat-ca-san-pham" onclick="filterBySubCat('Gạch 75x150'); toggleMobileMenu(false);" class="py-1 px-2 bg-slate-50 rounded">Gạch 75x150</a>
                    </div>
                </div>
                <div class="py-2">
                    <div class="text-brand font-bold uppercase mb-1.5">GẠCH KHỔ LỚN</div>
                    <div class="grid grid-cols-2 gap-1.5 pl-1">
                        <a href="#tat-ca-san-pham" onclick="filterBySubCat('Gạch 1200x1800'); toggleMobileMenu(false);" class="py-1 px-2 bg-slate-50 rounded">1200x1800</a>
                        <a href="#tat-ca-san-pham" onclick="filterBySubCat('Gạch 1200x2400'); toggleMobileMenu(false);" class="py-1 px-2 bg-slate-50 rounded">1200x2400</a>
                        <a href="#tat-ca-san-pham" onclick="filterBySubCat('Gạch 1200x2800'); toggleMobileMenu(false);" class="py-1 px-2 bg-slate-50 rounded">1200x2800</a>
                        <a href="#tat-ca-san-pham" onclick="filterBySubCat('Gạch 1600x3200'); toggleMobileMenu(false);" class="py-1 px-2 bg-slate-50 rounded">1600x3200</a>
                    </div>
                </div>
                <div class="py-2">
                    <div class="text-brand font-bold uppercase mb-1.5">GẠCH TRANG TRÍ</div>
                    <div class="grid grid-cols-2 gap-1.5 pl-1">
                        <a href="#tat-ca-san-pham" onclick="filterBySubCat('Gạch Terrazzo'); toggleMobileMenu(false);" class="py-1 px-2 bg-slate-50 rounded">Gạch Terrazzo</a>
                        <a href="#tat-ca-san-pham" onclick="filterBySubCat('Gạch Giả Gỗ'); toggleMobileMenu(false);" class="py-1 px-2 bg-slate-50 rounded">Gạch Giả Gỗ</a>
                        <a href="#tat-ca-san-pham" onclick="filterBySubCat('Gạch Mosaic'); toggleMobileMenu(false);" class="py-1 px-2 bg-slate-50 rounded">Gạch Mosaic</a>
                        <a href="#tat-ca-san-pham" onclick="filterBySubCat('Gạch Bông'); toggleMobileMenu(false);" class="py-1 px-2 bg-slate-50 rounded">Gạch Bông</a>
                    </div>
                </div>
                <div class="py-2">
                    <div class="text-brand font-bold uppercase mb-1.5">THIẾT BỊ VỆ SINH</div>
                    <div class="grid grid-cols-2 gap-1.5 pl-1">
                        <a href="#bang-bao-gia" onclick="toggleMobileMenu(false);" class="py-1 px-2 bg-slate-50 rounded">Bồn Cầu</a>
                        <a href="#bang-bao-gia" onclick="toggleMobileMenu(false);" class="py-1 px-2 bg-slate-50 rounded">Tủ Lavabo</a>
                        <a href="#bang-bao-gia" onclick="toggleMobileMenu(false);" class="py-1 px-2 bg-slate-50 rounded">Vòi Sen Tắm</a>
                        <a href="#bang-bao-gia" onclick="toggleMobileMenu(false);" class="py-1 px-2 bg-slate-50 rounded">Bồn Tắm</a>
                    </div>
                </div>
                <div class="py-3 space-y-2 text-slate-600">
                    <div><i class="fa-solid fa-location-dot text-brand-accent mr-1.5"></i> Xã Núi Thành, Tp. Đà Nẵng</div>
                    <div><i class="fa-solid fa-phone text-brand mr-1.5"></i> Hotline/Zalo: <strong>0896666236</strong></div>
                </div>
            </div>
        </div>
    </div>

    <!-- ================= MAIN CONTENT (UX BUILDER FLATSOME STRUCTURE) ================= -->
    <main class="py-4 space-y-7">

        <!-- 1. SECTION: 2 ẢNH BANNER TỰ TRƯỢT CHUYÊN NGHIỆP KÍCH THƯỚC BẰNG NHAU -->
        <!-- Thiết kế hình ảnh và chữ nằm gọn bên trong banner, cách xa viền, không bị thiếu chữ trên cả ĐT và Máy tính -->
        <section class="flatsome-container">
            <div class="hero-banner-wrapper shadow-md">
                <!-- SLIDE 1 -->
                <div class="hero-slide active" data-slide="0">
                    <div class="w-full h-full bg-gradient-to-r from-[#082038] via-[#0f3b68] to-[#164e87] flex items-center justify-between px-7 py-5 sm:px-12 md:px-16 lg:px-20">
                        <div class="w-full md:w-3/5 text-white space-y-2 sm:space-y-3 pr-2">
                            <p class="text-[11px] sm:text-xs md:text-sm font-bold uppercase tracking-widest text-amber-300">
                                TỔNG KHO GẠCH MEN THẮNG CƯỜNG - ĐÀ NẴNG
                            </p>
                            <h1 class="text-base sm:text-2xl md:text-3xl lg:text-4xl font-extrabold leading-snug">
                                GẠCH ỐP LÁT & GẠCH KHỔ LỚN CAO CẤP CHÍNH HÃNG
                            </h1>
                            <p class="text-[11px] sm:text-xs md:text-sm text-slate-200 leading-relaxed max-w-xl">
                                Đa dạng mẫu gạch 60x60, 80x80, 100x100, 60x120, 80x160, 1200x2400 vân đá Marble, Granite chống thấm, bền màu vượt thời gian.
                            </p>
                            <div class="pt-1 flex flex-wrap items-center gap-2 sm:gap-3 text-[11px] sm:text-xs font-semibold">
                                <a href="#tat-ca-san-pham" class="px-3.5 py-2 bg-brand-accent hover:bg-red-700 text-white rounded-md transition shadow">
                                    Xem Mẫu Thực Tế
                                </a>
                                <span class="px-3 py-1.5 bg-white/10 rounded-md border border-white/20 text-white">
                                    Đ/c: Xã Núi Thành, Tp. Đà Nẵng • ĐT: 0896666236
                                </span>
                            </div>
                        </div>
                        <!-- Khung ảnh nằm gọn bên trong banner (cách xa viền) -->
                        <div class="hidden md:grid grid-cols-2 gap-2.5 w-2/5 max-w-[340px] pl-4 shrink-0">
                            <div class="aspect-square rounded-lg overflow-hidden border-2 border-white/30 bg-white/10">
                                <img src="https://drive.google.com/thumbnail?id=1P2fePSvPXm6YIcNDixVa0YwFWshcHFDY&sz=w500"
                                     data-drive-id="1P2fePSvPXm6YIcNDixVa0YwFWshcHFDY"
                                     onerror="handleDriveImageError(this, '80x80')"
                                     alt="Gạch lát nền Thắng Cường" class="w-full h-full object-cover">
                            </div>
                            <div class="aspect-square rounded-lg overflow-hidden border-2 border-white/30 bg-white/10">
                                <img src="https://drive.google.com/thumbnail?id=11z7ir7cmqEcdrYuAThZvpOhgUVFsLUnP&sz=w500"
                                     data-drive-id="11z7ir7cmqEcdrYuAThZvpOhgUVFsLUnP"
                                     onerror="handleDriveImageError(this, '60x120')"
                                     alt="Gạch khổ lớn Thắng Cường" class="w-full h-full object-cover">
                            </div>
                        </div>
                    </div>
                </div>

                <!-- SLIDE 2 (Kích thước bằng nhau 100%) -->
                <div class="hero-slide" data-slide="1">
                    <div class="w-full h-full bg-gradient-to-r from-[#112a46] via-[#1b436d] to-[#0f3b68] flex items-center justify-between px-7 py-5 sm:px-12 md:px-16 lg:px-20">
                        <div class="w-full md:w-3/5 text-white space-y-2 sm:space-y-3 pr-2">
                            <p class="text-[11px] sm:text-xs md:text-sm font-bold uppercase tracking-widest text-amber-300">
                                GIẢI PHÁP KIẾN TRÚC HIỆN ĐẠI • GIÁ KHO TẬN GỐC
                            </p>
                            <h2 class="text-base sm:text-2xl md:text-3xl lg:text-4xl font-extrabold leading-snug">
                                GẠCH TRANG TRÍ, GIẢ GỖ & THIẾT BỊ VỆ SINH ĐỒNG BỘ
                            </h2>
                            <p class="text-[11px] sm:text-xs md:text-sm text-slate-200 leading-relaxed max-w-xl">
                                Chiết khấu ưu đãi cho nhà thầu, công trình dân dụng và biệt thự. Hỗ trợ tư vấn phối cảnh và vận chuyển nhanh chóng tận nơi.
                            </p>
                            <div class="pt-1 flex flex-wrap items-center gap-2 sm:gap-3 text-[11px] sm:text-xs font-semibold">
                                <a href="#bang-bao-gia" class="px-3.5 py-2 bg-amber-500 hover:bg-amber-600 text-slate-950 font-bold rounded-md transition shadow">
                                    Nhận Báo Giá Sỉ & Lẻ
                                </a>
                                <span class="px-3 py-1.5 bg-white/10 rounded-md border border-white/20 text-white">
                                    Website: gachmenthangcuong.com • 0896666236
                                </span>
                            </div>
                        </div>
                        <!-- Khung ảnh nằm gọn bên trong banner (cách xa viền) -->
                        <div class="hidden md:grid grid-cols-2 gap-2.5 w-2/5 max-w-[340px] pl-4 shrink-0">
                            <div class="aspect-square rounded-lg overflow-hidden border-2 border-white/30 bg-white/10">
                                <img src="https://drive.google.com/thumbnail?id=1ciwHcFfmGbsIyjTsi9KlyIsx6EXBNJTN&sz=w500"
                                     data-drive-id="1ciwHcFfmGbsIyjTsi9KlyIsx6EXBNJTN"
                                     onerror="handleDriveImageError(this, '1200x2400')"
                                     alt="Gạch khổ lớn Thắng Cường" class="w-full h-full object-cover">
                            </div>
                            <div class="aspect-square rounded-lg overflow-hidden border-2 border-white/30 bg-white/10">
                                <img src="https://drive.google.com/thumbnail?id=17YrxXteZmzhvVRYgfaklNGC2hKjN09N8&sz=w500"
                                     data-drive-id="17YrxXteZmzhvVRYgfaklNGC2hKjN09N8"
                                     onerror="handleDriveImageError(this, 'Giả Gỗ')"
                                     alt="Gạch giả gỗ Thắng Cường" class="w-full h-full object-cover">
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Nút điều hướng trái/phải cách mép an toàn -->
                <button type="button" onclick="changeBannerSlide(-1)" aria-label="Slide trước"
                        class="absolute left-2 top-1/2 -translate-y-1/2 z-20 w-7 h-7 sm:w-8 sm:h-8 rounded-full bg-black/35 hover:bg-black/60 text-white flex items-center justify-center transition">
                    <i class="fa-solid fa-chevron-left text-xs"></i>
                </button>
                <button type="button" onclick="changeBannerSlide(1)" aria-label="Slide tiếp"
                        class="absolute right-2 top-1/2 -translate-y-1/2 z-20 w-7 h-7 sm:w-8 sm:h-8 rounded-full bg-black/35 hover:bg-black/60 text-white flex items-center justify-center transition">
                    <i class="fa-solid fa-chevron-right text-xs"></i>
                </button>

                <!-- Chấm chỉ báo slide -->
                <div class="absolute bottom-2.5 left-1/2 -translate-x-1/2 z-20 flex items-center gap-2">
                    <button type="button" onclick="goToBannerSlide(0)" id="bannerDot0" class="w-6 h-2 rounded-full bg-amber-400 transition-all"></button>
                    <button type="button" onclick="goToBannerSlide(1)" id="bannerDot1" class="w-2 h-2 rounded-full bg-white/50 transition-all"></button>
                </div>
            </div>
        </section>

        <!-- 2. SECTION: DANH MỤC SẢN PHẨM TRANG CHỦ (THEO WEB MẪU GACHMENDANANG.VN, CHỮ NHỎ GỌN, ĐẸP TRÊN ĐT & MÁY TÍNH) -->
        <section id="danh-muc-trang-chu" class="flatsome-container">
            <div class="section-title-container">
                <div class="section-title-normal">
                    <h2 class="section-title-main">
                        <i class="fa-solid fa-layer-group text-brand-accent"></i> DANH MỤC SẢN PHẨM
                    </h2>
                    <span class="text-xs text-slate-500">Chọn danh mục để lọc nhanh theo kích thước</span>
                </div>
            </div>

            <!-- 4 Khối Danh Mục Chính Giống Web Mẫu gachmendanang.vn -->
            <div class="grid grid-cols-1 md:grid-cols-2 xl:grid-cols-4 gap-3.5">

                <!-- Nhóm 1: GẠCH LÁT NỀN -->
                <div class="bg-white rounded-lg border border-slate-200 p-3 shadow-sm">
                    <div class="flex items-center justify-between pb-2 mb-2.5 border-b border-slate-100">
                        <h3 class="text-xs sm:text-sm font-extrabold text-brand uppercase whitespace-nowrap">GẠCH LÁT NỀN</h3>
                        <button onclick="filterByCategory('GẠCH LÁT NỀN')" class="text-[11px] text-brand-accent font-semibold hover:underline whitespace-nowrap">Xem tất cả</button>
                    </div>
                    <div class="grid grid-cols-2 gap-2">
                        <a href="#tat-ca-san-pham" onclick="filterBySubCat('Gạch 60x60')" class="group flex items-center gap-2 p-1.5 rounded border border-slate-100 hover:border-brand bg-slate-50/70 transition">
                            <img src="https://drive.google.com/thumbnail?id=1KTDzdSGqiXWuLZDkPoDD7oZZVL-5F3Rr&sz=w200" data-drive-id="1KTDzdSGqiXWuLZDkPoDD7oZZVL-5F3Rr" onerror="handleDriveImageError(this, '60x60')" alt="Gạch 60x60" class="w-10 h-10 rounded object-cover shrink-0">
                            <div class="min-w-0">
                                <div class="cat-chip-title group-hover:text-brand-accent">GẠCH 60X60</div>
                                <div class="text-[10px] text-slate-500">60 Sản phẩm</div>
                            </div>
                        </a>
                        <a href="#tat-ca-san-pham" onclick="filterBySubCat('Gạch 80x80')" class="group flex items-center gap-2 p-1.5 rounded border border-slate-100 hover:border-brand bg-slate-50/70 transition">
                            <img src="https://drive.google.com/thumbnail?id=1P2fePSvPXm6YIcNDixVa0YwFWshcHFDY&sz=w200" data-drive-id="1P2fePSvPXm6YIcNDixVa0YwFWshcHFDY" onerror="handleDriveImageError(this, '80x80')" alt="Gạch 80x80" class="w-10 h-10 rounded object-cover shrink-0">
                            <div class="min-w-0">
                                <div class="cat-chip-title group-hover:text-brand-accent">GẠCH 80X80</div>
                                <div class="text-[10px] text-slate-500">82 Sản phẩm</div>
                            </div>
                        </a>
                        <a href="#tat-ca-san-pham" onclick="filterBySubCat('Gạch 100x100')" class="group flex items-center gap-2 p-1.5 rounded border border-slate-100 hover:border-brand bg-slate-50/70 transition">
                            <img src="https://drive.google.com/thumbnail?id=171kMlCqYFeFpvYcgH1wQbaIMszY0Ns3O&sz=w200" data-drive-id="171kMlCqYFeFpvYcgH1wQbaIMszY0Ns3O" onerror="handleDriveImageError(this, '100x100')" alt="Gạch 100x100" class="w-10 h-10 rounded object-cover shrink-0">
                            <div class="min-w-0">
                                <div class="cat-chip-title group-hover:text-brand-accent">GẠCH 100X100</div>
                                <div class="text-[10px] text-slate-500">55 Sản phẩm</div>
                            </div>
                        </a>
                        <a href="#tat-ca-san-pham" onclick="filterBySubCat('Gạch 120x120')" class="group flex items-center gap-2 p-1.5 rounded border border-slate-100 hover:border-brand bg-slate-50/70 transition">
                            <img src="https://drive.google.com/thumbnail?id=1CGBZ4cuB7DMWadnoktlMoji6MB3dioC-&sz=w200" data-drive-id="1CGBZ4cuB7DMWadnoktlMoji6MB3dioC-" onerror="handleDriveImageError(this, '120x120')" alt="Gạch 120x120" class="w-10 h-10 rounded object-cover shrink-0">
                            <div class="min-w-0">
                                <div class="cat-chip-title group-hover:text-brand-accent">GẠCH 120X120</div>
                                <div class="text-[10px] text-slate-500">28 Sản phẩm</div>
                            </div>
                        </a>
                    </div>
                </div>

                <!-- Nhóm 2: GẠCH ỐP TƯỜNG -->
                <div class="bg-white rounded-lg border border-slate-200 p-3 shadow-sm">
                    <div class="flex items-center justify-between pb-2 mb-2.5 border-b border-slate-100">
                        <h3 class="text-xs sm:text-sm font-extrabold text-brand uppercase whitespace-nowrap">GẠCH ỐP TƯỜNG</h3>
                        <button onclick="filterByCategory('GẠCH ỐP TƯỜNG')" class="text-[11px] text-brand-accent font-semibold hover:underline whitespace-nowrap">Xem tất cả</button>
                    </div>
                    <div class="grid grid-cols-2 gap-2">
                        <a href="#tat-ca-san-pham" onclick="filterBySubCat('Gạch 60x120')" class="group flex items-center gap-2 p-1.5 rounded border border-slate-100 hover:border-brand bg-slate-50/70 transition">
                            <img src="https://drive.google.com/thumbnail?id=11z7ir7cmqEcdrYuAThZvpOhgUVFsLUnP&sz=w200" data-drive-id="11z7ir7cmqEcdrYuAThZvpOhgUVFsLUnP" onerror="handleDriveImageError(this, '60x120')" alt="Gạch 60x120" class="w-10 h-10 rounded object-cover shrink-0">
                            <div class="min-w-0">
                                <div class="cat-chip-title group-hover:text-brand-accent">GẠCH 60X120</div>
                                <div class="text-[10px] text-slate-500">171 Sản phẩm</div>
                            </div>
                        </a>
                        <a href="#tat-ca-san-pham" onclick="filterBySubCat('Gạch 80x160')" class="group flex items-center gap-2 p-1.5 rounded border border-slate-100 hover:border-brand bg-slate-50/70 transition">
                            <img src="https://drive.google.com/thumbnail?id=19jauCH_X7lcc0KNlu2OJ75CRiw3ArT7r&sz=w200" data-drive-id="19jauCH_X7lcc0KNlu2OJ75CRiw3ArT7r" onerror="handleDriveImageError(this, '80x160')" alt="Gạch 80x160" class="w-10 h-10 rounded object-cover shrink-0">
                            <div class="min-w-0">
                                <div class="cat-chip-title group-hover:text-brand-accent">GẠCH 80X160</div>
                                <div class="text-[10px] text-slate-500">66 Sản phẩm</div>
                            </div>
                        </a>
                        <a href="#tat-ca-san-pham" onclick="filterBySubCat('Gạch 30x60')" class="group flex items-center gap-2 p-1.5 rounded border border-slate-100 hover:border-brand bg-slate-50/70 transition">
                            <img src="https://drive.google.com/thumbnail?id=1uqL6ACCB5ne0G1BYkXCurdnrsf1m2lr4&sz=w200" data-drive-id="1uqL6ACCB5ne0G1BYkXCurdnrsf1m2lr4" onerror="handleDriveImageError(this, '30x60')" alt="Gạch 30x60" class="w-10 h-10 rounded object-cover shrink-0">
                            <div class="min-w-0">
                                <div class="cat-chip-title group-hover:text-brand-accent">GẠCH 30X60</div>
                                <div class="text-[10px] text-slate-500">45 Sản phẩm</div>
                            </div>
                        </a>
                        <a href="#tat-ca-san-pham" onclick="filterBySubCat('Gạch 75x150')" class="group flex items-center gap-2 p-1.5 rounded border border-slate-100 hover:border-brand bg-slate-50/70 transition">
                            <img src="https://drive.google.com/thumbnail?id=1NwR4v0eypEtIwPi6NJVJCKoNCFFQ8G54&sz=w200" data-drive-id="1NwR4v0eypEtIwPi6NJVJCKoNCFFQ8G54" onerror="handleDriveImageError(this, '75x150')" alt="Gạch 75x150" class="w-10 h-10 rounded object-cover shrink-0">
                            <div class="min-w-0">
                                <div class="cat-chip-title group-hover:text-brand-accent">GẠCH 75X150</div>
                                <div class="text-[10px] text-slate-500">24 Sản phẩm</div>
                            </div>
                        </a>
                    </div>
                </div>

                <!-- Nhóm 3: GẠCH KHỔ LỚN -->
                <div class="bg-white rounded-lg border border-slate-200 p-3 shadow-sm">
                    <div class="flex items-center justify-between pb-2 mb-2.5 border-b border-slate-100">
                        <h3 class="text-xs sm:text-sm font-extrabold text-brand uppercase whitespace-nowrap">GẠCH KHỔ LỚN</h3>
                        <button onclick="filterByCategory('GẠCH KHỔ LỚN')" class="text-[11px] text-brand-accent font-semibold hover:underline whitespace-nowrap">Xem tất cả</button>
                    </div>
                    <div class="grid grid-cols-2 gap-2">
                        <a href="#tat-ca-san-pham" onclick="filterBySubCat('Gạch 1200x1800')" class="group flex items-center gap-2 p-1.5 rounded border border-slate-100 hover:border-brand bg-slate-50/70 transition">
                            <img src="https://drive.google.com/thumbnail?id=1_HXfxWiPLtWiayxMPjgFCsl1WS1wGb7h&sz=w200" data-drive-id="1_HXfxWiPLtWiayxMPjgFCsl1WS1wGb7h" onerror="handleDriveImageError(this, '1200x1800')" alt="Gạch 1200x1800" class="w-10 h-10 rounded object-cover shrink-0">
                            <div class="min-w-0">
                                <div class="cat-chip-title group-hover:text-brand-accent">1200X1800</div>
                                <div class="text-[10px] text-slate-500">14 Sản phẩm</div>
                            </div>
                        </a>
                        <a href="#tat-ca-san-pham" onclick="filterBySubCat('Gạch 1200x2400')" class="group flex items-center gap-2 p-1.5 rounded border border-slate-100 hover:border-brand bg-slate-50/70 transition">
                            <img src="https://drive.google.com/thumbnail?id=1ciwHcFfmGbsIyjTsi9KlyIsx6EXBNJTN&sz=w200" data-drive-id="1ciwHcFfmGbsIyjTsi9KlyIsx6EXBNJTN" onerror="handleDriveImageError(this, '1200x2400')" alt="Gạch 1200x2400" class="w-10 h-10 rounded object-cover shrink-0">
                            <div class="min-w-0">
                                <div class="cat-chip-title group-hover:text-brand-accent">1200X2400</div>
                                <div class="text-[10px] text-slate-500">20 Sản phẩm</div>
                            </div>
                        </a>
                        <a href="#tat-ca-san-pham" onclick="filterBySubCat('Gạch 1200x2800')" class="group flex items-center gap-2 p-1.5 rounded border border-slate-100 hover:border-brand bg-slate-50/70 transition">
                            <img src="https://drive.google.com/thumbnail?id=1X-ECML9CKN4ycBfVFu4pC0wnqzTS12CP&sz=w200" data-drive-id="1X-ECML9CKN4ycBfVFu4pC0wnqzTS12CP" onerror="handleDriveImageError(this, '1200x2800')" alt="Gạch 1200x2800" class="w-10 h-10 rounded object-cover shrink-0">
                            <div class="min-w-0">
                                <div class="cat-chip-title group-hover:text-brand-accent">1200X2800</div>
                                <div class="text-[10px] text-slate-500">14 Sản phẩm</div>
                            </div>
                        </a>
                        <a href="#tat-ca-san-pham" onclick="filterBySubCat('Gạch 1600x3200')" class="group flex items-center gap-2 p-1.5 rounded border border-slate-100 hover:border-brand bg-slate-50/70 transition">
                            <img src="https://drive.google.com/thumbnail?id=1vHG-pgeryaSItJoQ5ciiCGSWA7SJSU8c&sz=w200" data-drive-id="1vHG-pgeryaSItJoQ5ciiCGSWA7SJSU8c" onerror="handleDriveImageError(this, '1600x3200')" alt="Gạch 1600x3200" class="w-10 h-10 rounded object-cover shrink-0">
                            <div class="min-w-0">
                                <div class="cat-chip-title group-hover:text-brand-accent">1600X3200</div>
                                <div class="text-[10px] text-slate-500">43 Sản phẩm</div>
                            </div>
                        </a>
                    </div>
                </div>

                <!-- Nhóm 4: GẠCH TRANG TRÍ -->
                <div class="bg-white rounded-lg border border-slate-200 p-3 shadow-sm">
                    <div class="flex items-center justify-between pb-2 mb-2.5 border-b border-slate-100">
                        <h3 class="text-xs sm:text-sm font-extrabold text-brand uppercase whitespace-nowrap">GẠCH TRANG TRÍ</h3>
                        <button onclick="filterByCategory('GẠCH TRANG TRÍ')" class="text-[11px] text-brand-accent font-semibold hover:underline whitespace-nowrap">Xem tất cả</button>
                    </div>
                    <div class="grid grid-cols-2 gap-2">
                        <a href="#tat-ca-san-pham" onclick="filterBySubCat('Gạch Terrazzo')" class="group flex items-center gap-2 p-1.5 rounded border border-slate-100 hover:border-brand bg-slate-50/70 transition">
                            <img src="https://drive.google.com/thumbnail?id=1oah4j6YAPIsJacMYQFJ0JGVemrMwqCgf&sz=w200" data-drive-id="1oah4j6YAPIsJacMYQFJ0JGVemrMwqCgf" onerror="handleDriveImageError(this, 'Terrazzo')" alt="Gạch Terrazzo" class="w-10 h-10 rounded object-cover shrink-0">
                            <div class="min-w-0">
                                <div class="cat-chip-title group-hover:text-brand-accent">TERRAZZO</div>
                                <div class="text-[10px] text-slate-500">44 Sản phẩm</div>
                            </div>
                        </a>
                        <a href="#tat-ca-san-pham" onclick="filterBySubCat('Gạch Giả Gỗ')" class="group flex items-center gap-2 p-1.5 rounded border border-slate-100 hover:border-brand bg-slate-50/70 transition">
                            <img src="https://drive.google.com/thumbnail?id=17YrxXteZmzhvVRYgfaklNGC2hKjN09N8&sz=w200" data-drive-id="17YrxXteZmzhvVRYgfaklNGC2hKjN09N8" onerror="handleDriveImageError(this, 'Giả Gỗ')" alt="Gạch Giả Gỗ" class="w-10 h-10 rounded object-cover shrink-0">
                            <div class="min-w-0">
                                <div class="cat-chip-title group-hover:text-brand-accent">GẠCH GIẢ GỖ</div>
                                <div class="text-[10px] text-slate-500">48 Sản phẩm</div>
                            </div>
                        </a>
                        <a href="#tat-ca-san-pham" onclick="filterBySubCat('Gạch Mosaic')" class="group flex items-center gap-2 p-1.5 rounded border border-slate-100 hover:border-brand bg-slate-50/70 transition">
                            <img src="https://drive.google.com/thumbnail?id=15IWAPhzVLsyUO5TDRoWXxvncrHoFcH1_&sz=w200" data-drive-id="15IWAPhzVLsyUO5TDRoWXxvncrHoFcH1_" onerror="handleDriveImageError(this, 'Mosaic')" alt="Gạch Mosaic" class="w-10 h-10 rounded object-cover shrink-0">
                            <div class="min-w-0">
                                <div class="cat-chip-title group-hover:text-brand-accent">GẠCH MOSAIC</div>
                                <div class="text-[10px] text-slate-500">126 Sản phẩm</div>
                            </div>
                        </a>
                        <a href="#tat-ca-san-pham" onclick="filterBySubCat('Gạch Bông')" class="group flex items-center gap-2 p-1.5 rounded border border-slate-100 hover:border-brand bg-slate-50/70 transition">
                            <img src="https://drive.google.com/thumbnail?id=1WLKyUBxRc63xFN9GBUhFcqE0xPo0sQKh&sz=w200" data-drive-id="1WLKyUBxRc63xFN9GBUhFcqE0xPo0sQKh" onerror="handleDriveImageError(this, 'Gạch Bông')" alt="Gạch Bông" class="w-10 h-10 rounded object-cover shrink-0">
                            <div class="min-w-0">
                                <div class="cat-chip-title group-hover:text-brand-accent">GẠCH BÔNG</div>
                                <div class="text-[10px] text-slate-500">27 Sản phẩm</div>
                            </div>
                        </a>
                    </div>
                </div>

            </div>
        </section>

        <!-- 3. SECTION: BỘ LỌC TẤT CẢ 19 SẢN PHẨM THỰC TẾ TRÊN TRANG CHỦ (CHIA 2 CỘT TRÊN ĐIỆN THOẠI, % GIẢM GIÁ GÓC TRÊN BÊN TRÁI) -->
        <section id="tat-ca-san-pham" class="flatsome-container">
            <div class="section-title-container">
                <div class="section-title-normal">
                    <h2 id="activeCategoryHeading" class="section-title-main">
                        <i class="fa-solid fa-table-cells-large text-brand-accent"></i> MẪU GẠCH THẮNG CƯỜNG THỰC TẾ MỚI NHẤT
                    </h2>
                    <!-- Các nút lọc nhanh viết liền không gãy chữ -->
                    <div class="flex flex-wrap items-center gap-1.5">
                        <button onclick="filterByCategory('ALL')" data-cat-btn="ALL" class="cat-filter-btn px-2.5 py-1 text-xs font-bold rounded bg-brand text-white whitespace-nowrap">Tất cả (19)</button>
                        <button onclick="filterByCategory('GẠCH LÁT NỀN')" data-cat-btn="GẠCH LÁT NỀN" class="cat-filter-btn px-2.5 py-1 text-xs font-semibold rounded bg-white border border-slate-200 text-slate-700 hover:border-brand whitespace-nowrap">Gạch Lát Nền</button>
                        <button onclick="filterByCategory('GẠCH ỐP TƯỜNG')" data-cat-btn="GẠCH ỐP TƯỜNG" class="cat-filter-btn px-2.5 py-1 text-xs font-semibold rounded bg-white border border-slate-200 text-slate-700 hover:border-brand whitespace-nowrap">Gạch Ốp Tường</button>
                        <button onclick="filterByCategory('GẠCH KHỔ LỚN')" data-cat-btn="GẠCH KHỔ LỚN" class="cat-filter-btn px-2.5 py-1 text-xs font-semibold rounded bg-white border border-slate-200 text-slate-700 hover:border-brand whitespace-nowrap">Gạch Khổ Lớn</button>
                        <button onclick="filterByCategory('GẠCH TRANG TRÍ')" data-cat-btn="GẠCH TRANG TRÍ" class="cat-filter-btn px-2.5 py-1 text-xs font-semibold rounded bg-white border border-slate-200 text-slate-700 hover:border-brand whitespace-nowrap">Gạch Trang Trí</button>
                    </div>
                </div>
            </div>

            <!-- Grid sản phẩm: Chia 2 cột trên điện thoại (grid-cols-2), 3 cột tablet, 4-5 cột máy tính -->
            <div id="mainProductGrid" class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-4 xl:grid-cols-5 gap-3 sm:gap-4">
                <!-- Được render tự động từ 19 ảnh thực tế trong JS -->
            </div>
        </section>

        <!-- 4. SECTION CHUYÊN BIỆT 1: GẠCH LÁT NỀN & GẠCH 60X120 (GIỐNG WEB MẪU GACHMENDANANG.VN) -->
        <section id="san-pham-lat-nen" class="flatsome-container">
            <div class="section-title-container">
                <div class="section-title-normal">
                    <h2 class="section-title-main">
                        GẠCH LÁT NỀN 60X60 • 80X80 • 100X100 • 120X120
                    </h2>
                    <a href="#tat-ca-san-pham" onclick="filterByCategory('GẠCH LÁT NỀN')" class="text-xs font-bold text-brand hover:text-brand-accent whitespace-nowrap">
                        Xem thêm gạch lát nền <i class="fa-solid fa-angle-right"></i>
                    </a>
                </div>
            </div>
            <div id="latNenGrid" class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-4 xl:grid-cols-5 gap-3 sm:gap-4"></div>
        </section>

        <!-- 5. SECTION CHUYÊN BIỆT 2: GẠCH ỐP TƯỜNG & GẠCH KHỔ LỚN 60X120, 80X160, 1200X2400 -->
        <section id="san-pham-kho-lon" class="flatsome-container">
            <div class="section-title-container">
                <div class="section-title-normal">
                    <h2 class="section-title-main">
                        GẠCH ỐP TƯỜNG & KHỔ LỚN 60X120 • 80X160 • 1200X2400
                    </h2>
                    <a href="#tat-ca-san-pham" onclick="filterByCategory('GẠCH KHỔ LỚN')" class="text-xs font-bold text-brand hover:text-brand-accent whitespace-nowrap">
                        Xem thêm gạch khổ lớn <i class="fa-solid fa-angle-right"></i>
                    </a>
                </div>
            </div>
            <div id="khoLonGrid" class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-4 xl:grid-cols-5 gap-3 sm:gap-4"></div>
        </section>

        <!-- 6. SECTION CHUYÊN BIỆT 3: GẠCH TRANG TRÍ, GIẢ GỖ, TERRAZZO, MOSAIC -->
        <section id="san-pham-trang-tri" class="flatsome-container">
            <div class="section-title-container">
                <div class="section-title-normal">
                    <h2 class="section-title-main">
                        GẠCH GIẢ GỖ • TERRAZZO • MOSAIC • GẠCH BÔNG
                    </h2>
                    <a href="#tat-ca-san-pham" onclick="filterByCategory('GẠCH TRANG TRÍ')" class="text-xs font-bold text-brand hover:text-brand-accent whitespace-nowrap">
                        Xem thêm gạch trang trí <i class="fa-solid fa-angle-right"></i>
                    </a>
                </div>
            </div>
            <div id="trangTriGrid" class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-4 xl:grid-cols-5 gap-3 sm:gap-4"></div>
        </section>

        <!-- 7. SECTION: FORM YÊU CẦU TƯ VẤN & BÁO GIÁ TRANG CHỦ -->
        <section id="bang-bao-gia" class="flatsome-container">
            <div class="bg-white rounded-xl border border-slate-200 shadow-sm overflow-hidden">
                <div class="grid grid-cols-1 lg:grid-cols-12">
                    <!-- Cột thông tin cam kết giống gachmendanang.vn -->
                    <div class="lg:col-span-5 bg-brand text-white p-5 sm:p-7 flex flex-col justify-between">
                        <div class="space-y-4">
                            <h2 class="text-lg sm:text-xl font-extrabold uppercase tracking-wide text-amber-300">
                                GẠCH MEN THẮNG CƯỜNG – ĐÀ NẴNG
                            </h2>
                            <p class="text-xs sm:text-sm text-slate-200 leading-relaxed">
                                Tổng kho chuyên phân phối gạch lát nền, gạch ốp tường, gạch khổ lớn cao cấp (Vesta, Granca, OneMax, Fizini...) và thiết bị vệ sinh chính hãng cho nhà phố, biệt thự, khách sạn tại Đà Nẵng và miền Trung.
                            </p>
                            <ul class="space-y-2.5 text-xs sm:text-sm">
                                <li class="flex items-start gap-2.5">
                                    <i class="fa-solid fa-circle-check text-amber-400 mt-1"></i>
                                    <span><strong>Chất lượng loại 1:</strong> Xương đá Porcelain & Granite cứng chắc, chống thấm, chống trầy xước.</span>
                                </li>
                                <li class="flex items-start gap-2.5">
                                    <i class="fa-solid fa-circle-check text-amber-400 mt-1"></i>
                                    <span><strong>Giá gốc tại kho:</strong> Chiết khấu hấp dẫn cho công trình, nhà thầu và đại lý.</span>
                                </li>
                                <li class="flex items-start gap-2.5">
                                    <i class="fa-solid fa-circle-check text-amber-400 mt-1"></i>
                                    <span><strong>Giao hàng tận nơi:</strong> Hỗ trợ vận chuyển nhanh tại Xã Núi Thành và toàn TP. Đà Nẵng.</span>
                                </li>
                            </ul>
                        </div>
                        <div class="mt-6 pt-4 border-t border-white/15 text-xs sm:text-sm space-y-1">
                            <div><strong>Địa chỉ:</strong> Xã Núi Thành, Tp. Đà Nẵng</div>
                            <div><strong>Hotline / Zalo báo giá:</strong> <a href="tel:0896666236" class="text-amber-300 font-extrabold">0896666236</a></div>
                            <div><strong>Website:</strong> gachmenthangcuong.com</div>
                        </div>
                    </div>

                    <!-- Cột Form Yêu Cầu & Báo Giá -->
                    <div class="lg:col-span-7 p-5 sm:p-7">
                        <h3 class="text-base sm:text-lg font-extrabold text-brand uppercase mb-1">
                            ĐĂNG KÝ NHẬN BÁO GIÁ & TƯ VẤN MẪU GẠCH
                        </h3>
                        <p class="text-xs text-slate-500 mb-4">
                            Quý khách để lại thông tin hoặc mã sản phẩm quan tâm, Gạch Men Thắng Cường sẽ gửi bảng báo giá chi tiết qua Zalo/SĐT ngay lập tức.
                        </p>
                        <form id="quoteForm" onsubmit="submitQuoteForm(event)" class="space-y-3.5">
                            <div class="grid grid-cols-1 sm:grid-cols-2 gap-3.5">
                                <div>
                                    <label class="block text-xs font-bold text-slate-700 mb-1">Họ và tên quý khách *</label>
                                    <input id="qName" type="text" required placeholder="Nhập họ và tên..."
                                           class="w-full px-3 py-2 text-xs sm:text-sm border border-slate-300 rounded-md focus:outline-none focus:border-brand">
                                </div>
                                <div>
                                    <label class="block text-xs font-bold text-slate-700 mb-1">Số điện thoại / Zalo *</label>
                                    <input id="qPhone" type="tel" required placeholder="Ví dụ: 0896666236"
                                           class="w-full px-3 py-2 text-xs sm:text-sm border border-slate-300 rounded-md focus:outline-none focus:border-brand">
                                </div>
                            </div>
                            <div class="grid grid-cols-1 sm:grid-cols-2 gap-3.5">
                                <div>
                                    <label class="block text-xs font-bold text-slate-700 mb-1">Danh mục quan tâm</label>
                                    <select id="qCategory" class="w-full px-3 py-2 text-xs sm:text-sm border border-slate-300 rounded-md focus:outline-none focus:border-brand bg-white">
                                        <option value="Gạch Lát Nền (60x60, 80x80, 100x100, 120x120)">Gạch Lát Nền (60x60, 80x80, 100x100...)</option>
                                        <option value="Gạch Ốp Tường (30x60, 60x120, 80x160)">Gạch Ốp Tường (30x60, 60x120, 80x160)</option>
                                        <option value="Gạch Khổ Lớn (1200x2400, 1200x2800, 1600x3200)">Gạch Khổ Lớn (1200x2400, 1600x3200...)</option>
                                        <option value="Gạch Trang Trí (Giả Gỗ, Terrazzo, Mosaic, Gạch Bông)">Gạch Trang Trí (Giả Gỗ, Terrazzo, Mosaic)</option>
                                        <option value="Thiết Bị Vệ Sinh Trọn Bộ">Thiết Bị Vệ Sinh Phòng Tắm</option>
                                        <option value="Báo Giá Sỉ Công Trình / Đại Lý">Báo Giá Sỉ Công Trình / Đại Lý</option>
                                    </select>
                                </div>
                                <div>
                                    <label class="block text-xs font-bold text-slate-700 mb-1">Diện tích / Số lượng dự kiến (m²)</label>
                                    <input id="qArea" type="text" placeholder="Ví dụ: 150m² hoặc nhà 2 tầng..."
                                           class="w-full px-3 py-2 text-xs sm:text-sm border border-slate-300 rounded-md focus:outline-none focus:border-brand">
                                </div>
                            </div>
                            <div>
                                <label class="block text-xs font-bold text-slate-700 mb-1">Mã sản phẩm hoặc yêu cầu chi tiết</label>
                                <textarea id="qNote" rows="2" placeholder="Nhập mã gạch bạn thích hoặc địa chỉ giao hàng tại Đà Nẵng..."
                                          class="w-full px-3 py-2 text-xs sm:text-sm border border-slate-300 rounded-md focus:outline-none focus:border-brand"></textarea>
                            </div>
                            <div class="flex flex-wrap items-center gap-3 pt-1">
                                <button type="submit" class="px-5 py-2.5 bg-brand-accent hover:bg-red-700 text-white font-bold text-xs sm:text-sm rounded-md transition shadow">
                                    <i class="fa-solid fa-paper-plane mr-1.5"></i> GỬI YÊU CẦU BÁO GIÁ
                                </button>
                                <a href="https://zalo.me/0896666236" target="_blank" rel="noopener" class="px-4 py-2.5 bg-blue-600 hover:bg-blue-700 text-white font-bold text-xs sm:text-sm rounded-md transition">
                                    Chat Zalo: 0896666236
                                </a>
                            </div>
                            <div id="quoteSuccessMsg" class="hidden p-3 rounded-md bg-emerald-50 border border-emerald-200 text-emerald-800 text-xs font-medium"></div>
                        </form>
                    </div>
                </div>
            </div>
        </section>

        <!-- 8. SECTION: DANH MỤC CÁC ĐỐI TÁC THƯƠNG HIỆU -->
        <section id="doi-tac" class="flatsome-container">
            <div class="section-title-container">
                <div class="section-title-normal">
                    <h2 class="section-title-main">
                        <i class="fa-solid fa-handshake text-brand-accent"></i> ĐỐI TÁC & THƯƠNG HIỆU PHÂN PHỐI
                    </h2>
                    <span class="text-xs text-slate-500">Hợp tác cùng các nhà máy sản xuất gạch men hàng đầu</span>
                </div>
            </div>
            <div class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-4 lg:grid-cols-6 gap-3">
                <div class="bg-white border border-slate-200 rounded-lg p-3 text-center hover:border-brand transition shadow-sm">
                    <div class="text-sm font-black text-brand tracking-wider">THẮNG CƯỜNG</div>
                    <div class="text-[11px] text-slate-500 mt-0.5">Thương hiệu Chủ lực</div>
                </div>
                <div class="bg-white border border-slate-200 rounded-lg p-3 text-center hover:border-brand transition shadow-sm">
                    <div class="text-sm font-black text-brand tracking-wider">VESTA TILES</div>
                    <div class="text-[11px] text-slate-500 mt-0.5">Gạch Granite Cao Cấp</div>
                </div>
                <div class="bg-white border border-slate-200 rounded-lg p-3 text-center hover:border-brand transition shadow-sm">
                    <div class="text-sm font-black text-brand tracking-wider">GRANCA</div>
                    <div class="text-[11px] text-slate-500 mt-0.5">Gạch Ốp Lát Châu Âu</div>
                </div>
                <div class="bg-white border border-slate-200 rounded-lg p-3 text-center hover:border-brand transition shadow-sm">
                    <div class="text-sm font-black text-brand tracking-wider">ONEMAX</div>
                    <div class="text-[11px] text-slate-500 mt-0.5">Gạch Bóng Kiếng</div>
                </div>
                <div class="bg-white border border-slate-200 rounded-lg p-3 text-center hover:border-brand transition shadow-sm">
                    <div class="text-sm font-black text-brand tracking-wider">VIGLACERA</div>
                    <div class="text-[11px] text-slate-500 mt-0.5">Gạch & Sứ Vệ Sinh</div>
                </div>
                <div class="bg-white border border-slate-200 rounded-lg p-3 text-center hover:border-brand transition shadow-sm">
                    <div class="text-sm font-black text-brand tracking-wider">PRIME / ĐỒNG TÂM</div>
                    <div class="text-[11px] text-slate-500 mt-0.5">Đối Tác Phân Phối</div>
                </div>
            </div>
        </section>

        <!-- 9. SECTION: DANH MỤC CÁC BÀI VIẾT TRANG CHỦ -->
        <section id="tin-tuc" class="flatsome-container">
            <div class="section-title-container">
                <div class="section-title-normal">
                    <h2 class="section-title-main">
                        <i class="fa-solid fa-newspaper text-brand-accent"></i> BÀI VIẾT & KINH NGHIỆM CHỌN GẠCH
                    </h2>
                    <span class="text-xs text-slate-500">Cập nhật xu hướng gạch ốp lát 2026</span>
                </div>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-3 gap-4">
                <!-- Bài viết 1 -->
                <article class="bg-white rounded-lg border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                    <div class="h-44 overflow-hidden bg-slate-100">
                        <img src="https://drive.google.com/thumbnail?id=11z7ir7cmqEcdrYuAThZvpOhgUVFsLUnP&sz=w600"
                             data-drive-id="11z7ir7cmqEcdrYuAThZvpOhgUVFsLUnP"
                             onerror="handleDriveImageError(this, 'Tin tức 1')"
                             alt="Kinh nghiệm chọn gạch khổ lớn" class="w-full h-full object-cover">
                    </div>
                    <div class="p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <div class="text-[11px] text-slate-400 font-medium mb-1">Tư vấn chọn gạch • gachmenthangcuong.com</div>
                            <h3 class="text-sm font-bold text-slate-800 hover:text-brand mb-2 leading-snug">
                                Xu hướng chọn gạch khổ lớn 60x120 và 80x160 cho phòng khách sang trọng
                            </h3>
                            <p class="text-xs text-slate-600 leading-relaxed">
                                Gạch khổ lớn Thắng Cường giúp giảm thiểu đường ron, tạo hiệu ứng không gian liền mạch, thoáng rộng và nâng tầm thẩm mỹ cho nhà phố, biệt thự hiện đại.
                            </p>
                        </div>
                        <button type="button" onclick="openArticleModal(0)" class="mt-3 text-xs font-bold text-brand hover:text-brand-accent inline-flex items-center gap-1">
                            Đọc chi tiết <i class="fa-solid fa-arrow-right text-[10px]"></i>
                        </button>
                    </div>
                </article>

                <!-- Bài viết 2 -->
                <article class="bg-white rounded-lg border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                    <div class="h-44 overflow-hidden bg-slate-100">
                        <img src="https://drive.google.com/thumbnail?id=1P2fePSvPXm6YIcNDixVa0YwFWshcHFDY&sz=w600"
                             data-drive-id="1P2fePSvPXm6YIcNDixVa0YwFWshcHFDY"
                             onerror="handleDriveImageError(this, 'Tin tức 2')"
                             alt="Phân biệt gạch Granite và Ceramic" class="w-full h-full object-cover">
                    </div>
                    <div class="p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <div class="text-[11px] text-slate-400 font-medium mb-1">Kiến thức vật liệu • Gạch Men Thắng Cường</div>
                            <h3 class="text-sm font-bold text-slate-800 hover:text-brand mb-2 leading-snug">
                                Cách nhận biết gạch xương đá Granite loại 1 chống thấm, chịu lực cao
                            </h3>
                            <p class="text-xs text-slate-600 leading-relaxed">
                                Hướng dẫn kiểm tra độ phẳng mặt men, xương gạch Porcelain/Granite và cách tính số lượng thùng gạch 60x60, 80x80 chính xác cho từng diện tích phòng.
                            </p>
                        </div>
                        <button type="button" onclick="openArticleModal(1)" class="mt-3 text-xs font-bold text-brand hover:text-brand-accent inline-flex items-center gap-1">
                            Đọc chi tiết <i class="fa-solid fa-arrow-right text-[10px]"></i>
                        </button>
                    </div>
                </article>

                <!-- Bài viết 3 -->
                <article class="bg-white rounded-lg border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                    <div class="h-44 overflow-hidden bg-slate-100">
                        <img src="https://drive.google.com/thumbnail?id=17YrxXteZmzhvVRYgfaklNGC2hKjN09N8&sz=w600"
                             data-drive-id="17YrxXteZmzhvVRYgfaklNGC2hKjN09N8"
                             onerror="handleDriveImageError(this, 'Tin tức 3')"
                             alt="Phối màu gạch giả gỗ và terrazzo" class="w-full h-full object-cover">
                    </div>
                    <div class="p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <div class="text-[11px] text-slate-400 font-medium mb-1">Thiết kế nội thất • Núi Thành, Đà Nẵng</div>
                            <h3 class="text-sm font-bold text-slate-800 hover:text-brand mb-2 leading-snug">
                                Bí quyết phối gạch giả gỗ ấm cúng cho phòng ngủ và gạch chống trơn nhà tắm
                            </h3>
                            <p class="text-xs text-slate-600 leading-relaxed">
                                Gạch vân gỗ 15x90, 20x120 kết hợp hoàn hảo vẻ đẹp tự nhiên của gỗ với khả năng chống ẩm mốc, mối mọt tuyệt đối trong khí hậu miền Trung.
                            </p>
                        </div>
                        <button type="button" onclick="openArticleModal(2)" class="mt-3 text-xs font-bold text-brand hover:text-brand-accent inline-flex items-center gap-1">
                            Đọc chi tiết <i class="fa-solid fa-arrow-right text-[10px]"></i>
                        </button>
                    </div>
                </article>
            </div>
        </section>

        <!-- 10. SECTION: ĐƯA GOOGLE MAP & FANPAGE FACEBOOK RA NGOÀI TRANG CHỦ -->
        <section id="ban-do" class="flatsome-container">
            <div class="section-title-container">
                <div class="section-title-normal">
                    <h2 class="section-title-main">
                        <i class="fa-solid fa-map-location-dot text-brand-accent"></i> BẢN ĐỒ GOOGLE MAPS & FANPAGE CHÍNH THỨC
                    </h2>
                    <span class="text-xs text-slate-500">Xã Núi Thành, Tp. Đà Nẵng • ĐT: 0896666236</span>
                </div>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-12 gap-4">
                <!-- Cột Bản đồ Google Maps ngoài trang chủ (7 phần) -->
                <div class="lg:col-span-7 bg-white rounded-lg border border-slate-200 p-3 shadow-sm flex flex-col justify-between">
                    <div class="flex flex-wrap items-center justify-between gap-2 mb-2.5">
                        <div>
                            <h3 class="text-xs sm:text-sm font-extrabold text-brand uppercase">VỊ TRÍ KHO & SHOWROOM GẠCH MEN THẮNG CƯỜNG</h3>
                            <p class="text-xs text-slate-600"><i class="fa-solid fa-location-dot text-brand-accent mr-1"></i> Địa chỉ: <strong>Xã Núi Thành, Tp. Đà Nẵng</strong></p>
                        </div>
                        <a href="https://www.google.com/maps/search/?api=1&query=Núi+Thành,+Đà+Nẵng" target="_blank" rel="noopener"
                           class="px-3 py-1.5 bg-brand text-white text-xs font-bold rounded hover:bg-brand-dark transition">
                            <i class="fa-solid fa-diamond-turn-right mr-1"></i> Mở Google Maps lớn
                        </a>
                    </div>
                    <div class="w-full h-64 sm:h-72 rounded-md overflow-hidden border border-slate-200 bg-slate-100">
                        <iframe
                            title="Bản đồ Gạch Men Thắng Cường - Xã Núi Thành, Tp. Đà Nẵng"
                            src="https://maps.google.com/maps?q=N%C3%BAi%20Th%C3%A0nh%2C%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=13&ie=UTF8&iwloc=&output=embed"
                            class="w-full h-full border-0"
                            loading="lazy"
                            referrerpolicy="no-referrer-when-downgrade">
                        </iframe>
                    </div>
                </div>

                <!-- Cột Fanpage Facebook ngoài trang chủ (5 phần) -->
                <div class="lg:col-span-5 bg-white rounded-lg border border-slate-200 p-3 shadow-sm flex flex-col justify-between">
                    <div class="mb-2.5 flex items-center justify-between gap-2">
                        <div>
                            <h3 class="text-xs sm:text-sm font-extrabold text-brand uppercase">FANPAGE GẠCH MEN THẮNG CƯỜNG</h3>
                            <p class="text-xs text-slate-600">Kết nối & xem video/hình ảnh xuất kho hàng ngày</p>
                        </div>
                        <a href="https://www.facebook.com/profile.php?id=61581399601584" target="_blank" rel="noopener"
                           class="px-3 py-1.5 bg-[#1877F2] text-white text-xs font-bold rounded hover:bg-blue-700 transition shrink-0">
                            <i class="fa-brands fa-facebook mr-1"></i> Mở Fanpage
                        </a>
                    </div>

                    <!-- Khung Fanpage trực quan + Nhúng Plugin Facebook -->
                    <div class="border border-slate-200 rounded-lg overflow-hidden bg-slate-50 flex-1 flex flex-col justify-between">
                        <div class="p-3.5 bg-gradient-to-r from-[#0f3b68] to-[#1e5799] text-white flex items-center gap-3">
                            <img src="https://drive.google.com/thumbnail?id=1AOQpSlLMl8y-XyUpqqHvErHWgy-mI7Uu&sz=w200"
                                 data-drive-id="1AOQpSlLMl8y-XyUpqqHvErHWgy-mI7Uu"
                                 onerror="handleDriveImageError(this, 'TC')"
                                 alt="Logo Fanpage" class="w-12 h-12 rounded-full border-2 border-white bg-white object-contain p-0.5 shrink-0">
                            <div class="min-w-0">
                                <a href="https://www.facebook.com/profile.php?id=61581399601584" target="_blank" rel="noopener" class="font-extrabold text-sm hover:underline block truncate">
                                    Gạch Men Thắng Cường
                                </a>
                                <div class="text-[11px] text-slate-200">Vật liệu xây dựng • Xã Núi Thành, Tp. Đà Nẵng</div>
                                <div class="text-[11px] text-amber-300 font-semibold mt-0.5"><i class="fa-solid fa-phone mr-1"></i> 0896666236</div>
                            </div>
                        </div>

                        <div class="p-3 space-y-2.5 text-xs text-slate-700">
                            <p class="leading-relaxed">
                                Chuyên cung cấp sỉ & lẻ gạch men lát nền, gạch ốp tường, gạch khổ lớn, gạch trang trí và thiết bị vệ sinh chính hãng tại Xã Núi Thành, Tp. Đà Nẵng.
                            </p>
                            <div class="grid grid-cols-4 gap-1.5">
                                <img src="https://drive.google.com/thumbnail?id=1P2fePSvPXm6YIcNDixVa0YwFWshcHFDY&sz=w200" data-drive-id="1P2fePSvPXm6YIcNDixVa0YwFWshcHFDY" onerror="handleDriveImageError(this, 'SP1')" alt="Ảnh fanpage 1" class="w-full h-14 object-cover rounded">
                                <img src="https://drive.google.com/thumbnail?id=11z7ir7cmqEcdrYuAThZvpOhgUVFsLUnP&sz=w200" data-drive-id="11z7ir7cmqEcdrYuAThZvpOhgUVFsLUnP" onerror="handleDriveImageError(this, 'SP2')" alt="Ảnh fanpage 2" class="w-full h-14 object-cover rounded">
                                <img src="https://drive.google.com/thumbnail?id=1ciwHcFfmGbsIyjTsi9KlyIsx6EXBNJTN&sz=w200" data-drive-id="1ciwHcFfmGbsIyjTsi9KlyIsx6EXBNJTN" onerror="handleDriveImageError(this, 'SP3')" alt="Ảnh fanpage 3" class="w-full h-14 object-cover rounded">
                                <img src="https://drive.google.com/thumbnail?id=17YrxXteZmzhvVRYgfaklNGC2hKjN09N8&sz=w200" data-drive-id="17YrxXteZmzhvVRYgfaklNGC2hKjN09N8" onerror="handleDriveImageError(this, 'SP4')" alt="Ảnh fanpage 4" class="w-full h-14 object-cover rounded">
                            </div>
                        </div>

                        <div class="p-3 bg-white border-t border-slate-200 flex flex-wrap items-center justify-between gap-2">
                            <a href="https://www.facebook.com/profile.php?id=61581399601584" target="_blank" rel="noopener"
                               class="flex-1 text-center py-2 px-3 bg-[#1877F2] hover:bg-blue-700 text-white font-bold text-xs rounded transition">
                                <i class="fa-brands fa-facebook-f mr-1"></i> Theo Dõi Trang Fanpage
                            </a>
                            <a href="https://www.facebook.com/profile.php?id=61581399601584" target="_blank" rel="noopener"
                               class="py-2 px-3 bg-slate-100 hover:bg-slate-200 text-slate-800 font-semibold text-xs rounded transition">
                                <i class="fa-brands fa-facebook-messenger text-[#1877F2] mr-1"></i> Nhắn Tin
                            </a>
                        </div>
                    </div>
                </div>
            </div>
        </section>

    </main>

    <!-- ================= FOOTER (CHUẨN FLATSOME GACHMENDANANG.VN) ================= -->
    <footer class="bg-brand-dark text-slate-200 pt-8 pb-20 md:pb-8 border-t-4 border-brand-accent mt-8">
        <div class="flatsome-container">
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-6 pb-6 border-b border-white/10 text-xs sm:text-sm">
                <!-- Cột 1: Thông tin công ty -->
                <div class="space-y-2.5">
                    <div class="flex items-center gap-2.5">
                        <div class="w-9 h-9 rounded bg-white p-0.5 flex items-center justify-center shrink-0">
                            <img src="https://drive.google.com/thumbnail?id=1AOQpSlLMl8y-XyUpqqHvErHWgy-mI7Uu&sz=w200"
                                 data-drive-id="1AOQpSlLMl8y-XyUpqqHvErHWgy-mI7Uu"
                                 onerror="handleDriveImageError(this, 'TC')"
                                 alt="Logo Gạch Men Thắng Cường" class="w-full h-full object-contain">
                        </div>
                        <span class="font-extrabold text-white text-sm sm:text-base uppercase">GẠCH MEN THẮNG CƯỜNG</span>
                    </div>
                    <p class="text-xs text-slate-300 leading-relaxed">
                        Tổng kho phân phối gạch ốp lát, gạch khổ lớn, gạch trang trí và thiết bị vệ sinh chính hãng uy tín, chất lượng cao.
                    </p>
                    <ul class="space-y-1.5 text-xs">
                        <li><i class="fa-solid fa-location-dot text-amber-400 mr-1.5"></i> <strong>Địa chỉ:</strong> Xã Núi Thành, Tp. Đà Nẵng</li>
                        <li><i class="fa-solid fa-phone text-amber-400 mr-1.5"></i> <strong>Hotline / Zalo:</strong> <a href="tel:0896666236" class="text-amber-300 font-bold">0896666236</a></li>
                        <li><i class="fa-solid fa-globe text-amber-400 mr-1.5"></i> <strong>Website:</strong> gachmenthangcuong.com</li>
                        <li><i class="fa-brands fa-facebook text-amber-400 mr-1.5"></i> <strong>Fanpage:</strong> <a href="https://www.facebook.com/profile.php?id=61581399601584" target="_blank" rel="noopener" class="underline hover:text-white">Gạch Men Thắng Cường</a></li>
                    </ul>
                </div>

                <!-- Cột 2: Danh mục sản phẩm -->
                <div>
                    <h4 class="font-extrabold text-white uppercase text-xs sm:text-sm mb-3 border-b border-white/15 pb-1.5">DANH MỤC GẠCH ỐP LÁT</h4>
                    <ul class="space-y-1.5 text-xs">
                        <li><a href="#tat-ca-san-pham" onclick="filterByCategory('GẠCH LÁT NỀN')" class="hover:text-amber-300">Gạch Lát Nền 60x60, 80x80, 100x100, 120x120</a></li>
                        <li><a href="#tat-ca-san-pham" onclick="filterByCategory('GẠCH ỐP TƯỜNG')" class="hover:text-amber-300">Gạch Ốp Tường 30x60, 60x120, 80x160</a></li>
                        <li><a href="#tat-ca-san-pham" onclick="filterByCategory('GẠCH KHỔ LỚN')" class="hover:text-amber-300">Gạch Khổ Lớn 1200x2400, 1200x2800, 1600x3200</a></li>
                        <li><a href="#tat-ca-san-pham" onclick="filterBySubCat('Gạch Giả Gỗ')" class="hover:text-amber-300">Gạch Giả Gỗ 15x90, 20x100, 20x120</a></li>
                        <li><a href="#tat-ca-san-pham" onclick="filterBySubCat('Gạch Terrazzo')" class="hover:text-amber-300">Gạch Terrazzo, Gạch Mosaic, Gạch Bông</a></li>
                    </ul>
                </div>

                <!-- Cột 3: Thiết bị vệ sinh & Hỗ trợ -->
                <div>
                    <h4 class="font-extrabold text-white uppercase text-xs sm:text-sm mb-3 border-b border-white/15 pb-1.5">THIẾT BỊ VỆ SINH & DỊCH VỤ</h4>
                    <ul class="space-y-1.5 text-xs">
                        <li><a href="#bang-bao-gia" class="hover:text-amber-300">Bồn Cầu 1 Khối & Tủ Lavabo Cao Cấp</a></li>
                        <li><a href="#bang-bao-gia" class="hover:text-amber-300">Sen Cây Tắm Nóng Lạnh & Phụ Kiện Phòng Tắm</a></li>
                        <li><a href="#bang-bao-gia" class="hover:text-amber-300">Chính Sách Chiết Khấu Công Trình & Nhà Thầu</a></li>
                        <li><a href="#bang-bao-gia" class="hover:text-amber-300">Hỗ Trợ Giao Hàng Tận Chân Công Trình</a></li>
                        <li><a href="#ban-do" class="hover:text-amber-300">Bản Đồ Chỉ Đường Đến Showroom</a></li>
                    </ul>
                </div>

                <!-- Cột 4: Kết nối nhanh -->
                <div>
                    <h4 class="font-extrabold text-white uppercase text-xs sm:text-sm mb-3 border-b border-white/15 pb-1.5">LIÊN HỆ BÁO GIÁ NHANH</h4>
                    <p class="text-xs text-slate-300 mb-3">
                        Quý khách cần xem mẫu gạch thực tế hoặc nhận bảng báo giá ưu đãi nhất hôm nay, vui lòng liên hệ trực tiếp:
                    </p>
                    <div class="space-y-2">
                        <a href="tel:0896666236" class="flex items-center justify-center gap-2 w-full py-2 px-3 bg-brand-accent hover:bg-red-700 text-white font-bold text-xs rounded transition">
                            <i class="fa-solid fa-phone-volume"></i> HOTLINE: 0896666236
                        </a>
                        <a href="https://zalo.me/0896666236" target="_blank" rel="noopener" class="flex items-center justify-center gap-2 w-full py-2 px-3 bg-blue-600 hover:bg-blue-700 text-white font-bold text-xs rounded transition">
                            <i class="fa-solid fa-comment-dots"></i> NHẮN ZALO: 0896666236
                        </a>
                    </div>
                </div>
            </div>

            <div class="pt-4 flex flex-col sm:flex-row items-center justify-between text-[11px] text-slate-400 gap-2">
                <div>Copyright © 2026 <strong>Gạch Men Thắng Cường (gachmenthangcuong.com)</strong>. Địa chỉ: Xã Núi Thành, Tp. Đà Nẵng.</div>
                <div>Thiết kế chuẩn bố cục Flatsome • Hotline: 0896666236</div>
            </div>
        </div>
    </footer>

    <!-- ================= CÁC NÚT LIÊN HỆ NỔI BẬT (ZALO, FACEBOOK, HOTLINE) TƯƠNG THÍCH MÁY TÍNH & ĐIỆN THOẠI ================= -->
    <div class="fixed right-3 bottom-4 z-40 flex flex-col items-end gap-2.5">
        <!-- Nút Facebook Fanpage -->
        <a href="https://www.facebook.com/profile.php?id=61581399601584" target="_blank" rel="noopener"
           aria-label="Facebook Gạch Men Thắng Cường"
           class="flex items-center gap-2 bg-[#1877F2] hover:bg-blue-700 text-white rounded-full p-2.5 sm:px-3.5 sm:py-2 shadow-lg transition">
            <i class="fa-brands fa-facebook-f text-base sm:text-sm w-5 text-center"></i>
            <span class="hidden sm:inline text-xs font-bold">Fanpage</span>
        </a>

        <!-- Nút Chat Zalo -->
        <a href="https://zalo.me/0896666236" target="_blank" rel="noopener"
           aria-label="Zalo 0896666236"
           class="flex items-center gap-2 bg-[#0068FF] hover:bg-blue-600 text-white rounded-full p-2.5 sm:px-3.5 sm:py-2 shadow-lg transition">
            <span class="font-extrabold text-[11px] bg-white text-[#0068FF] rounded-full w-5 h-5 flex items-center justify-center shrink-0">Z</span>
            <span class="hidden sm:inline text-xs font-bold">Zalo: 0896666236</span>
        </a>

        <!-- Nút Gọi Hotline -->
        <a href="tel:0896666236"
           aria-label="Gọi Hotline 0896666236"
           class="floating-pulse flex items-center gap-2 bg-brand-accent hover:bg-red-700 text-white rounded-full p-2.5 sm:px-3.5 sm:py-2.5 shadow-xl transition">
            <i class="fa-solid fa-phone-volume text-base sm:text-sm w-5 text-center"></i>
            <span class="text-xs font-extrabold pr-1">0896.666.236</span>
        </a>
    </div>

    <!-- ================= MODAL XEM CHI TIẾT SẢN PHẨM & BÀI VIẾT ================= -->
    <div id="detailModal" class="fixed inset-0 z-50 hidden items-center justify-center p-3 bg-black/60">
        <div class="bg-white rounded-xl max-w-lg w-full max-h-[90vh] overflow-y-auto shadow-2xl border border-slate-200 p-4 sm:p-5 relative">
            <button type="button" onclick="closeDetailModal()" aria-label="Đóng" class="absolute right-3 top-3 w-8 h-8 rounded-full bg-slate-100 hover:bg-slate-200 text-slate-700 flex items-center justify-center">
                <i class="fa-solid fa-xmark"></i>
            </button>
            <div id="detailModalContent"></div>
        </div>
    </div>

    <!-- ================= JAVASCRIPT XỬ LÝ DỮ LIỆU 19 ẢNH SẢN PHẨM THỰC TẾ & TƯƠNG TÁC ================= -->
    <script>
        // Hàm fallback thông minh cho ảnh Google Drive để luôn hiển thị nét trên mọi trình duyệt
        function handleDriveImageError(imgEl, labelText) {
            const fileId = imgEl.getAttribute('data-drive-id');
            const step = parseInt(imgEl.getAttribute('data-fallback-step') || '0', 10);
            if (fileId && step === 0) {
                imgEl.setAttribute('data-fallback-step', '1');
                imgEl.src = 'https://lh3.googleusercontent.com/d/' + fileId + '=w800';
            } else if (fileId && step === 1) {
                imgEl.setAttribute('data-fallback-step', '2');
                imgEl.src = 'https://drive.google.com/uc?export=view&id=' + fileId;
            } else {
                imgEl.onerror = null;
                imgEl.src = 'https://placehold.co/600x600/0f3b68/ffffff?text=' + encodeURIComponent(labelText || 'Gach+Thang+Cuong');
            }
        }

        // Danh sách đầy đủ 19 ảnh sản phẩm thực tế từ Google Drive của khách hàng, phân loại đúng danh mục & tên sản phẩm
        const productsData = [
            {
                id: 1,
                driveId: '1P2fePSvPXm6YIcNDixVa0YwFWshcHFDY',
                name: 'Gạch Lát Nền 80×80 Thắng Cường Vesta TC8801 Vân Đá Marble',
                category: 'GẠCH LÁT NỀN',
                subCategory: 'Gạch 80x80',
                oldPrice: 340000,
                newPrice: 265000,
                discount: 22,
                surface: 'Men bóng kiếng toàn phần, xương đá Granite'
            },
            {
                id: 2,
                driveId: '11z7ir7cmqEcdrYuAThZvpOhgUVFsLUnP',
                name: 'Gạch 60×120 Thắng Cường HG61201 Vân Đá Cẩm Thạch',
                category: 'GẠCH ỐP TƯỜNG',
                subCategory: 'Gạch 60x120',
                oldPrice: 480000,
                newPrice: 370000,
                discount: 23,
                surface: 'Men bóng cao cấp, ốp tường & lát nền'
            },
            {
                id: 3,
                driveId: '1KTDzdSGqiXWuLZDkPoDD7oZZVL-5F3Rr',
                name: 'Gạch Lát Nền 60×60 Thắng Cường Granca GA6701 Trắng Vân Khói',
                category: 'GẠCH LÁT NỀN',
                subCategory: 'Gạch 60x60',
                oldPrice: 230000,
                newPrice: 180000,
                discount: 22,
                surface: 'Xương Porcelain chống thấm, bền màu'
            },
            {
                id: 4,
                driveId: '1X31hmhpLVVORV-tmMSZYzBO-qtpyusry',
                name: 'Gạch Lát Nền 80×80 Thắng Cường OneMax OM8804 Xám Vân Đá',
                category: 'GẠCH LÁT NỀN',
                subCategory: 'Gạch 80x80',
                oldPrice: 350000,
                newPrice: 275000,
                discount: 21,
                surface: 'Đá Granite dày 10.4mm chịu lực cao'
            },
            {
                id: 5,
                driveId: '171kMlCqYFeFpvYcgH1wQbaIMszY0Ns3O',
                name: 'Gạch Lát Nền 100×100 Thắng Cường Fizini GVN101054 Vân Đá',
                category: 'GẠCH LÁT NỀN',
                subCategory: 'Gạch 100x100',
                oldPrice: 520000,
                newPrice: 410000,
                discount: 21,
                surface: 'Khổ lớn phòng khách biệt thự sang trọng'
            },
            {
                id: 6,
                driveId: '1t8U7WQsmDbGWzmSelkxzjVv8M0BvIxAg',
                name: 'Gạch 60×120 Thắng Cường HGE61214 Vân Đá Tự Nhiên',
                category: 'GẠCH ỐP TƯỜNG',
                subCategory: 'Gạch 60x120',
                oldPrice: 530000,
                newPrice: 415000,
                discount: 22,
                surface: 'Men vi tinh kim cương chống trầy xước'
            },
            {
                id: 7,
                driveId: '1uqL6ACCB5ne0G1BYkXCurdnrsf1m2lr4',
                name: 'Gạch Ốp Tường 30×60 Thắng Cường TC3605 Kem Vân Đá Sáng',
                category: 'GẠCH ỐP TƯỜNG',
                subCategory: 'Gạch 30x60',
                oldPrice: 215000,
                newPrice: 168000,
                discount: 22,
                surface: 'Men bóng dễ lau chùi phòng tắm & bếp'
            },
            {
                id: 8,
                driveId: '1NwR4v0eypEtIwPi6NJVJCKoNCFFQ8G54',
                name: 'Gạch Ốp Tường 75×150 Thắng Cường Granca GA4601 Cao Cấp',
                category: 'GẠCH ỐP TƯỜNG',
                subCategory: 'Gạch 75x150',
                oldPrice: 540000,
                newPrice: 420000,
                discount: 22,
                surface: 'Bề mặt mịn sáng bóng, chống bám bẩn'
            },
            {
                id: 9,
                driveId: '19jauCH_X7lcc0KNlu2OJ75CRiw3ArT7r',
                name: 'Gạch Khổ Lớn 80×160 Thắng Cường HG81602 Vân Đá Bóng Kiếng',
                category: 'GẠCH KHỔ LỚN',
                subCategory: 'Gạch 80x160',
                oldPrice: 582000,
                newPrice: 455000,
                discount: 22,
                surface: 'Gạch khổ lớn cao cấp cho sảnh & phòng khách'
            },
            {
                id: 10,
                driveId: '1_HXfxWiPLtWiayxMPjgFCsl1WS1wGb7h',
                name: 'Gạch Khổ Lớn 1200×1800 Thắng Cường HG81605 Xám Vân Mây',
                category: 'GẠCH KHỔ LỚN',
                subCategory: 'Gạch 1200x1800',
                oldPrice: 750000,
                newPrice: 570000,
                discount: 24,
                surface: 'Vân đá liên hoàn hiện đại, sắc nét HD'
            },
            {
                id: 11,
                driveId: '1ciwHcFfmGbsIyjTsi9KlyIsx6EXBNJTN',
                name: 'Gạch Khổ Lớn 1200×2400 Thắng Cường HG122401 Vân Đá Luxury',
                category: 'GẠCH KHỔ LỚN',
                subCategory: 'Gạch 1200x2400',
                oldPrice: 830000,
                newPrice: 610000,
                discount: 27,
                surface: 'Đá nung kết khổ lớn ốp vách tivi & sảnh'
            },
            {
                id: 12,
                driveId: '1vHG-pgeryaSItJoQ5ciiCGSWA7SJSU8c',
                name: 'Gạch Khổ Lớn 1600×3200 Thắng Cường HG122406 Trắng Vân Mây',
                category: 'GẠCH KHỔ LỚN',
                subCategory: 'Gạch 1600x3200',
                oldPrice: 1650000,
                newPrice: 1250000,
                discount: 24,
                surface: 'Siêu khổ lớn Big Slab chuẩn kiến trúc Ý'
            },
            {
                id: 13,
                driveId: '1X-ECML9CKN4ycBfVFu4pC0wnqzTS12CP',
                name: 'Gạch Khổ Lớn 1200×2800 Thắng Cường HGE122403 Đá Nung Kết',
                category: 'GẠCH KHỔ LỚN',
                subCategory: 'Gạch 1200x2800',
                oldPrice: 2200000,
                newPrice: 1500000,
                discount: 32,
                surface: 'Chống thấm, chịu nhiệt và độ bóng gương cao'
            },
            {
                id: 14,
                driveId: '1CGBZ4cuB7DMWadnoktlMoji6MB3dioC-',
                name: 'Gạch Lát Nền 120×120 Thắng Cường TC121208 Đá Granite Cao Cấp',
                category: 'GẠCH LÁT NỀN',
                subCategory: 'Gạch 120x120',
                oldPrice: 680000,
                newPrice: 530000,
                discount: 22,
                surface: 'Gạch 120x120 ít đường ron, sang trọng'
            },
            {
                id: 15,
                driveId: '17YrxXteZmzhvVRYgfaklNGC2hKjN09N8',
                name: 'Gạch Giả Gỗ 15×90 Thắng Cường HGK159001 Vân Gỗ Sồi Tự Nhiên',
                category: 'GẠCH TRANG TRÍ',
                subCategory: 'Gạch Giả Gỗ',
                oldPrice: 350000,
                newPrice: 280000,
                discount: 20,
                surface: 'Men Matt chống trơn, ấm cúng cho phòng ngủ'
            },
            {
                id: 16,
                driveId: '19k5uWHn_xeas2_BMP_JgBDwwu-IysSRP',
                name: 'Gạch Giả Gỗ 20×120 Thắng Cường HG201202 Vân Gỗ Óc Chó',
                category: 'GẠCH TRANG TRÍ',
                subCategory: 'Gạch Giả Gỗ',
                oldPrice: 360000,
                newPrice: 295000,
                discount: 18,
                surface: 'Xương Porcelain chống ẩm mốc, không cong vênh'
            },
            {
                id: 17,
                driveId: '1oah4j6YAPIsJacMYQFJ0JGVemrMwqCgf',
                name: 'Gạch Terrazzo 60×60 Thắng Cường TCR6008 Hạt Đá Nghệ Thuật',
                category: 'GẠCH TRANG TRÍ',
                subCategory: 'Gạch Terrazzo',
                oldPrice: 290000,
                newPrice: 225000,
                discount: 22,
                surface: 'Bề mặt Matt Sugar chống trơn trượt hiệu quả'
            },
            {
                id: 18,
                driveId: '15IWAPhzVLsyUO5TDRoWXxvncrHoFcH1_',
                name: 'Gạch Mosaic Trang Trí Thắng Cường HG25072 Men Gốm Cao Cấp',
                category: 'GẠCH TRANG TRÍ',
                subCategory: 'Gạch Mosaic',
                oldPrice: 380000,
                newPrice: 295000,
                discount: 22,
                surface: 'Chuyên ốp điểm nhấn phòng tắm, quầy bar, hồ bơi'
            },
            {
                id: 19,
                driveId: '1WLKyUBxRc63xFN9GBUhFcqE0xPo0sQKh',
                name: 'Gạch Bông & Sân Vườn Thắng Cường TCB6009 Chống Trơn Cao Cấp',
                category: 'GẠCH TRANG TRÍ',
                subCategory: 'Gạch Bông',
                oldPrice: 260000,
                newPrice: 199000,
                discount: 23,
                surface: 'Hoa văn sắc nét, độ cứng cao, chống rêu mốc'
            }
        ];

        function formatVND(amount) {
            return amount.toString().replace(/\B(?=(\d{3})+(?!\d))/g, '.') + ' ₫';
        }

        // Tạo HTML cho từng thẻ sản phẩm chuẩn Flatsome (Chỉ để duy nhất badge % giảm giá ở góc trên bên trái, tên sản phẩm hiển thị đầy đủ không tràn/cắt chữ)
        function createProductCardHTML(item) {
            const imgUrl = 'https://drive.google.com/thumbnail?id=' + item.driveId + '&sz=w700';
            return `
                <div class="bg-white rounded-lg border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col justify-between group">
                    <div>
                        <div class="relative aspect-square w-full bg-slate-100 overflow-hidden cursor-pointer" onclick="openProductModal(${item.id})">
                            <div class="flatsome-discount-badge">-${item.discount}%</div>
                            <img src="${imgUrl}"
                                 data-drive-id="${item.driveId}"
                                 onerror="handleDriveImageError(this, '${item.subCategory}')"
                                 alt="${item.name}"
                                 loading="lazy"
                                 class="w-full h-full object-cover group-hover:scale-105 transition duration-300">
                        </div>
                        <div class="p-2.5 sm:p-3">
                            <div class="text-[10px] sm:text-[11px] font-semibold text-slate-400 uppercase mb-1">${item.subCategory}</div>
                            <h3 class="product-title-full cursor-pointer hover:text-brand" onclick="openProductModal(${item.id})">
                                ${item.name}
                            </h3>
                        </div>
                    </div>
                    <div class="px-2.5 pb-2.5 sm:px-3 sm:pb-3 pt-1 border-t border-slate-100">
                        <div class="flex flex-wrap items-baseline gap-1.5 mb-2">
                            <del class="text-[11px] sm:text-xs text-slate-400">${formatVND(item.oldPrice)}</del>
                            <ins class="text-xs sm:text-sm font-extrabold text-brand-accent no-underline">${formatVND(item.newPrice)}</ins>
                        </div>
                        <button type="button" onclick="selectProductForQuote('${item.name.replace(/'/g, "\\'")}')"
                                class="w-full py-1.5 px-2 bg-slate-100 hover:bg-brand hover:text-white text-brand font-bold text-[11px] sm:text-xs rounded transition">
                            Nhận báo giá
                        </button>
                    </div>
                </div>
            `;
        }

        function renderAllSections() {
            // Render tất cả 19 sản phẩm ở lưới tổng
            const mainGrid = document.getElementById('mainProductGrid');
            mainGrid.innerHTML = productsData.map(createProductCardHTML).join('');

            // Render nhóm Gạch Lát Nền (5 mẫu tiêu biểu)
            const latNenItems = productsData.filter(p => p.category === 'GẠCH LÁT NỀN');
            document.getElementById('latNenGrid').innerHTML = latNenItems.map(createProductCardHTML).join('');

            // Render nhóm Gạch Ốp Tường & Khổ Lớn
            const khoLonItems = productsData.filter(p => p.category === 'GẠCH ỐP TƯỜNG' || p.category === 'GẠCH KHỔ LỚN');
            document.getElementById('khoLonGrid').innerHTML = khoLonItems.map(createProductCardHTML).join('');

            // Render nhóm Gạch Trang Trí & Giả Gỗ
            const trangTriItems = productsData.filter(p => p.category === 'GẠCH TRANG TRÍ');
            document.getElementById('trangTriGrid').innerHTML = trangTriItems.map(createProductCardHTML).join('');
        }

        function filterByCategory(categoryName) {
            const heading = document.getElementById('activeCategoryHeading');
            const mainGrid = document.getElementById('mainProductGrid');

            let filtered = productsData;
            if (categoryName !== 'ALL' && categoryName !== 'THIẾT BỊ VỆ SINH') {
                filtered = productsData.filter(p => p.category === categoryName);
                heading.innerHTML = `<i class="fa-solid fa-table-cells-large text-brand-accent"></i> ${categoryName} (${filtered.length} MẪU)`;
            } else {
                heading.innerHTML = `<i class="fa-solid fa-table-cells-large text-brand-accent"></i> MẪU GẠCH THẮNG CƯỜNG THỰC TẾ MỚI NHẤT (${productsData.length})`;
            }

            mainGrid.innerHTML = filtered.map(createProductCardHTML).join('');

            // Cập nhật trạng thái nút lọc
            document.querySelectorAll('.cat-filter-btn').forEach(btn => {
                if (btn.getAttribute('data-cat-btn') === categoryName) {
                    btn.className = 'cat-filter-btn px-2.5 py-1 text-xs font-bold rounded bg-brand text-white whitespace-nowrap';
                } else {
                    btn.className = 'cat-filter-btn px-2.5 py-1 text-xs font-semibold rounded bg-white border border-slate-200 text-slate-700 hover:border-brand whitespace-nowrap';
                }
            });

            document.getElementById('tat-ca-san-pham').scrollIntoView({ behavior: 'smooth', block: 'start' });
        }

        function filterBySubCat(subCatName) {
            const heading = document.getElementById('activeCategoryHeading');
            const mainGrid = document.getElementById('mainProductGrid');
            const filtered = productsData.filter(p => p.subCategory.toLowerCase() === subCatName.toLowerCase());
            const listToShow = filtered.length > 0 ? filtered : productsData;

            heading.innerHTML = `<i class="fa-solid fa-table-cells-large text-brand-accent"></i> DANH MỤC: ${subCatName.toUpperCase()}`;
            mainGrid.innerHTML = listToShow.map(createProductCardHTML).join('');
        }

        function handleSearch(inputId) {
            const query = (document.getElementById(inputId).value || '').trim().toLowerCase();
            const mainGrid = document.getElementById('activeCategoryHeading');
            if (!query) {
                filterByCategory('ALL');
                return;
            }
            const matched = productsData.filter(p =>
                p.name.toLowerCase().includes(query) ||
                p.subCategory.toLowerCase().includes(query) ||
                p.category.toLowerCase().includes(query)
            );
            mainGrid.innerHTML = `<i class="fa-solid fa-magnifying-glass text-brand-accent"></i> KẾT QUẢ TÌM KIẾM: "${query.toUpperCase()}" (${matched.length})`;
            document.getElementById('mainProductGrid').innerHTML = (matched.length ? matched : productsData).map(createProductCardHTML).join('');
            document.getElementById('tat-ca-san-pham').scrollIntoView({ behavior: 'smooth' });
        }

        // Mở Modal xem chi tiết sản phẩm
        function openProductModal(productId) {
            const item = productsData.find(p => p.id === productId);
            if (!item) return;
            const imgUrl = 'https://drive.google.com/thumbnail?id=' + item.driveId + '&sz=w900';
            const modalContent = document.getElementById('detailModalContent');
            modalContent.innerHTML = `
                <div class="space-y-3">
                    <div class="relative aspect-square w-full max-h-72 bg-slate-100 rounded-lg overflow-hidden">
                        <div class="flatsome-discount-badge">-${item.discount}%</div>
                        <img src="${imgUrl}" data-drive-id="${item.driveId}" onerror="handleDriveImageError(this, '${item.subCategory}')" alt="${item.name}" class="w-full h-full object-contain">
                    </div>
                    <div class="text-xs font-bold text-brand uppercase">${item.category} • ${item.subCategory}</div>
                    <h3 class="text-base font-extrabold text-slate-900">${item.name}</h3>
                    <div class="flex items-baseline gap-2">
                        <del class="text-xs text-slate-400">Giá gốc: ${formatVND(item.oldPrice)}</del>
                        <span class="text-base font-extrabold text-brand-accent">Giá ưu đãi: ${formatVND(item.newPrice)} / m²</span>
                    </div>
                    <p class="text-xs text-slate-600 bg-slate-50 p-2.5 rounded border border-slate-200">
                        <strong>Đặc điểm:</strong> ${item.surface}. Sản phẩm chính hãng phân phối tại Tổng kho Gạch Men Thắng Cường (Xã Núi Thành, Tp. Đà Nẵng).
                    </p>
                    <div class="flex flex-wrap gap-2 pt-2">
                        <a href="tel:0896666236" class="flex-1 text-center py-2.5 px-3 bg-brand-accent text-white font-bold text-xs rounded">
                            <i class="fa-solid fa-phone mr-1"></i> Gọi: 0896666236
                        </a>
                        <a href="https://zalo.me/0896666236" target="_blank" rel="noopener" class="flex-1 text-center py-2.5 px-3 bg-blue-600 text-white font-bold text-xs rounded">
                            Chat Zalo Báo Giá
                        </a>
                    </div>
                </div>
            `;
            const modal = document.getElementById('detailModal');
            modal.classList.remove('hidden');
            modal.classList.add('flex');
        }

        // Mở Modal đọc bài viết
        const articlesFull = [
            {
                title: 'Xu hướng chọn gạch khổ lớn 60x120 và 80x160 cho phòng khách sang trọng',
                content: 'Gạch khổ lớn 60x120, 80x160 và 1200x2400 của Gạch Men Thắng Cường đang được các gia chủ tại Đà Nẵng ưu tiên lựa chọn nhờ đường vân đá Marble tự nhiên, độ bóng sâu và khả năng mở rộng không gian tối đa. Khi lát nền hoặc ốp tường phòng khách, số lượng đường mạch gạch giảm xuống giúp sàn nhà liền mạch và cực kỳ dễ vệ sinh.'
            },
            {
                title: 'Cách nhận biết gạch xương đá Granite loại 1 chống thấm, chịu lực cao',
                content: 'Gạch xương đá Granite/Porcelain loại 1 của Thắng Cường có phần xương gạch đồng chất, gõ nhẹ phát ra âm thanh thanh gọn, độ hút nước gần như bằng 0 (<0.5%). Bề mặt viên gạch phẳng tuyệt đối, bốn cạnh mài chuẩn kích thước giúp thợ thi công nhanh và đều đẹp.'
            },
            {
                title: 'Bí quyết phối gạch giả gỗ ấm cúng cho phòng ngủ và gạch chống trơn nhà tắm',
                content: 'Với khí hậu miền Trung, gạch giả gỗ 15x90 và 20x120 là giải pháp thay thế sàn gỗ tự nhiên hoàn hảo vì không lo mối mọt hay ẩm mốc. Kết hợp cùng gạch Terrazzo hoặc gạch men Matt chống trơn cho khu vực phòng tắm sẽ mang lại sự an toàn và thẩm mỹ bền vững cho ngôi nhà.'
            }
        ];

        function openArticleModal(idx) {
            const art = articlesFull[idx];
            if (!art) return;
            document.getElementById('detailModalContent').innerHTML = `
                <div class="space-y-3 pr-4">
                    <div class="text-xs font-bold text-brand-accent uppercase">Cẩm Nang Gạch Men Thắng Cường</div>
                    <h3 class="text-base sm:text-lg font-extrabold text-brand">${art.title}</h3>
                    <p class="text-xs sm:text-sm text-slate-700 leading-relaxed">${art.content}</p>
                    <div class="p-3 bg-slate-50 rounded border border-slate-200 text-xs text-slate-600">
                        Liên hệ tư vấn trực tiếp tại <strong>Xã Núi Thành, Tp. Đà Nẵng</strong> • Hotline/Zalo: <strong>0896666236</strong>
                    </div>
                </div>
            `;
            const modal = document.getElementById('detailModal');
            modal.classList.remove('hidden');
            modal.classList.add('flex');
        }

        function closeDetailModal() {
            const modal = document.getElementById('detailModal');
            modal.classList.add('hidden');
            modal.classList.remove('flex');
        }

        function selectProductForQuote(productName) {
            const noteEl = document.getElementById('qNote');
            noteEl.value = 'Tôi cần báo giá mẫu: ' + productName;
            document.getElementById('bang-bao-gia').scrollIntoView({ behavior: 'smooth' });
            document.getElementById('qName').focus();
        }

        function submitQuoteForm(e) {
            e.preventDefault();
            const name = document.getElementById('qName').value.trim();
            const phone = document.getElementById('qPhone').value.trim();
            const category = document.getElementById('qCategory').value;
            const area = document.getElementById('qArea').value.trim();
            const note = document.getElementById('qNote').value.trim();

            const msgBox = document.getElementById('quoteSuccessMsg');
            msgBox.classList.remove('hidden');
            msgBox.innerHTML = `Cảm ơn <strong>${name}</strong> (${phone})! Yêu cầu báo giá mục <strong>${category}</strong> ${area ? '(' + area + ')' : ''} đã được ghi nhận. Bộ phận kinh doanh Gạch Men Thắng Cường (<strong>0896666236</strong>) sẽ liên hệ báo giá ngay!`;
            document.getElementById('quoteForm').reset();
        }

        // Điều khiển 2 Banner tự trượt chuyên nghiệp
        let currentBannerIdx = 0;
        const totalBannerSlides = 2;
        let bannerInterval = null;

        function updateBannerUI() {
            const slides = document.querySelectorAll('.hero-slide');
            slides.forEach((slide, idx) => {
                if (idx === currentBannerIdx) {
                    slide.classList.add('active');
                } else {
                    slide.classList.remove('active');
                }
            });
            const dot0 = document.getElementById('bannerDot0');
            const dot1 = document.getElementById('bannerDot1');
            if (currentBannerIdx === 0) {
                dot0.className = 'w-6 h-2 rounded-full bg-amber-400 transition-all';
                dot1.className = 'w-2 h-2 rounded-full bg-white/50 transition-all';
            } else {
                dot0.className = 'w-2 h-2 rounded-full bg-white/50 transition-all';
                dot1.className = 'w-6 h-2 rounded-full bg-amber-400 transition-all';
            }
        }

        function changeBannerSlide(step) {
            currentBannerIdx = (currentBannerIdx + step + totalBannerSlides) % totalBannerSlides;
            updateBannerUI();
            resetBannerTimer();
        }

        function goToBannerSlide(index) {
            currentBannerIdx = index;
            updateBannerUI();
            resetBannerTimer();
        }

        function resetBannerTimer() {
            if (bannerInterval) clearInterval(bannerInterval);
            bannerInterval = setInterval(() => {
                currentBannerIdx = (currentBannerIdx + 1) % totalBannerSlides;
                updateBannerUI();
            }, 4800);
        }

        function toggleMobileMenu(show) {
            const drawer = document.getElementById('mobileMenuDrawer');
            if (show) {
                drawer.classList.remove('hidden');
            } else {
                drawer.classList.add('hidden');
            }
        }

        document.getElementById('mobileMenuBtn').addEventListener('click', () => toggleMobileMenu(true));

        window.addEventListener('DOMContentLoaded', () => {
            renderAllSections();
            resetBannerTimer();
        });
    </script>
</body>
</html>
