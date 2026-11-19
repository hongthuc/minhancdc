<html lang="vi">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=5.0">
  <title>CÔNG TY TNHH MTV TƯ VẤN THIẾT KẾ XÂY DỰNG VÀ THƯƠNG MẠI MINH ÂN CDC | minhancdc.com</title>
  <meta name="description" content="Minh Ân CDC chuyên Tư vấn Thiết kế Kiến trúc - Nội thất, Thi công Xây dựng trọn gói nhà phố, biệt thự, khách sạn, căn hộ, văn phòng tại Đà Nẵng & Huế. Hotline: 0941 394 848.">

  <!-- Meta Open Graph & Thumbnail chia sẻ link trang web là Logo Minh Ân CDC -->
  <meta property="og:type" content="website">
  <meta property="og:site_name" content="MINH ÂN CDC - minhancdc.com">
  <meta property="og:title" content="CÔNG TY TNHH MTV TƯ VẤN THIẾT KẾ XÂY DỰNG VÀ THƯƠNG MẠI MINH ÂN CDC">
  <meta property="og:description" content="Tư vấn Thiết kế - Thi công Xây dựng & Thương mại uy tín tại Đà Nẵng và Huế. Hotline: 0941 394 848.">
  <meta property="og:url" content="https://minhancdc.com">
  <meta property="og:image" content="https://lh3.googleusercontent.com/d/1mB37EKXpyrvpswPrIUaMt2Wrn1lH-Gvu=w1200">
  <meta property="og:image:secure_url" content="https://lh3.googleusercontent.com/d/1mB37EKXpyrvpswPrIUaMt2Wrn1lH-Gvu=w1200">
  <meta property="og:image:alt" content="Logo Công ty TNHH MTV Tư vấn Thiết kế Xây dựng và Thương mại Minh Ân CDC">
  <meta name="twitter:card" content="summary_large_image">
  <meta name="twitter:title" content="MINH ÂN CDC | Tư vấn Thiết kế & Thi công Xây dựng Đà Nẵng - Huế">
  <meta name="twitter:description" content="Thiết kế Kiến trúc, Thi công phần thô, Hoàn thiện trọn gói tại Đà Nẵng & Huế. Hotline: 0941 394 848.">
  <meta name="twitter:image" content="https://lh3.googleusercontent.com/d/1mB37EKXpyrvpswPrIUaMt2Wrn1lH-Gvu=w1200">
  <link rel="icon" type="image/png" href="https://lh3.googleusercontent.com/d/1mB37EKXpyrvpswPrIUaMt2Wrn1lH-Gvu=w256">

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
            sans: ['Inter', 'system-ui', '-apple-system', 'sans-serif'],
          },
          colors: {
            brand: {
              primary: 'var(--brand-primary)',
              dark: 'var(--brand-dark)',
              light: 'var(--brand-light)',
              accent: 'var(--brand-accent)',
              accentHover: 'var(--brand-accent-hover)',
            }
          }
        }
      }
    }
  </script>

  <style>
    /* ============================================================
       BIẾN MÀU THƯƠNG HIỆU THEO LOGO MINH ÂN CDC & PHONG CÁCH FLATSOME
       Dễ dàng chỉnh sửa đồng bộ khi dựng lại trên Flatsome UX Builder
       ============================================================ */
    :root {
      --brand-primary: #0B3D6B;       /* Xanh dương kiến trúc chủ đạo */
      --brand-dark: #072848;          /* Xanh đậm footer & nhấn mạnh */
      --brand-light: #EFF5FB;         /* Nền xanh nhạt phân khu */
      --brand-accent: #D48A18;        /* Vàng đồng xây dựng nổi bật */
      --brand-accent-hover: #B87410;  /* Vàng đồng hover */
      --text-main: #1E293B;
      --text-muted: #475569;
      --border-soft: #E2E8F0;
    }

    *, *::before, *::after {
      box-sizing: border-box;
    }

    html {
      scroll-behavior: smooth;
      overflow-x: hidden;
      width: 100%;
      max-width: 100%;
    }

    body {
      margin: 0;
      padding: 0;
      width: 100%;
      max-width: 100%;
      overflow-x: hidden;
      font-family: 'Inter', sans-serif;
      color: var(--text-main);
      background-color: #FFFFFF;
      -webkit-font-smoothing: antialiased;
    }

    /* Khung chuẩn Flatsome: 95% chiều ngang màn hình trên máy tính, full gọn gàng trên mobile */
    .flatsome-container {
      width: 100%;
      margin-left: auto;
      margin-right: auto;
      padding-left: 12px;
      padding-right: 12px;
    }

    @media (min-width: 640px) {
      .flatsome-container {
        padding-left: 16px;
        padding-right: 16px;
      }
    }

    @media (min-width: 1024px) {
      .flatsome-container {
        width: 95%;
        max-width: 95%;
        padding-left: 0;
        padding-right: 0;
      }
    }

    /* Dropdown Menu chuẩn Flatsome */
    .nav-dropdown-parent {
      position: relative;
    }
    .nav-dropdown-menu {
      opacity: 0;
      visibility: hidden;
      transform: translateY(8px);
      transition: all 0.2s ease;
      position: absolute;
      top: 100%;
      left: 0;
      min-width: 230px;
      background: #FFFFFF;
      border: 1px solid #E2E8F0;
      border-top: 3px solid var(--brand-accent);
      border-radius: 0 0 10px 10px;
      box-shadow: 0 12px 28px rgba(11, 61, 107, 0.12);
      z-index: 60;
      padding: 6px 0;
    }
    .nav-dropdown-parent:hover .nav-dropdown-menu,
    .nav-dropdown-parent:focus-within .nav-dropdown-menu {
      opacity: 1;
      visibility: visible;
      transform: translateY(0);
    }

    /* Đường gạch chân tiêu đề mục chuẩn Flatsome */
    .flatsome-section-title {
      position: relative;
      display: inline-block;
      padding-bottom: 10px;
    }
    .flatsome-section-title::after {
      content: '';
      position: absolute;
      bottom: 0;
      left: 50%;
      transform: translateX(-50%);
      width: 64px;
      height: 3px;
      background: linear-gradient(90deg, var(--brand-primary), var(--brand-accent));
      border-radius: 99px;
    }
    .flatsome-section-title.align-left::after {
      left: 0;
      transform: none;
    }

    /* Banner 2 slide tự trượt có kích thước bằng nhau tuyệt đối */
    .hero-slider-viewport {
      width: 100%;
      overflow: hidden;
      position: relative;
      border-radius: 14px;
    }
    .hero-slider-track {
      display: flex;
      width: 100%;
      transition: transform 0.65s cubic-bezier(0.22, 1, 0.36, 1);
      align-items: stretch;
    }
    .hero-slide {
      flex: 0 0 100%;
      width: 100%;
      min-width: 100%;
      display: flex;
      align-items: center;
      position: relative;
      overflow: hidden;
    }

    /* Hiệu ứng card sản phẩm / dự án Flatsome */
    .ux-card {
      transition: transform 0.25s ease, box-shadow 0.25s ease, border-color 0.25s ease;
    }
    .ux-card:hover {
      transform: translateY(-3px);
      box-shadow: 0 12px 24px rgba(11, 61, 107, 0.10);
      border-color: rgba(11, 61, 107, 0.28);
    }
    .ux-card img {
      transition: transform 0.45s ease;
    }
    .ux-card:hover img {
      transform: scale(1.04);
    }

    /* Tab danh mục gọn đẹp, không xuống dòng trong tên danh mục */
    .cat-tab-btn {
      white-space: nowrap;
      transition: all 0.2s ease;
    }
    .cat-tab-btn.active {
      background-color: var(--brand-primary);
      color: #FFFFFF;
      border-color: var(--brand-primary);
      box-shadow: 0 4px 12px rgba(11, 61, 107, 0.22);
    }

    /* Hiệu ứng rung nhẹ cho nút Hotline nổi */
    @keyframes pulseRing {
      0% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(212, 138, 24, 0.55); }
      70% { transform: scale(1); box-shadow: 0 0 0 10px rgba(212, 138, 24, 0); }
      100% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(212, 138, 24, 0); }
    }
    .hotline-pulse {
      animation: pulseRing 2.2s infinite;
    }

    /* Đảm bảo ảnh và iframe không bao giờ tràn viền */
    img, iframe, svg {
      max-width: 100%;
    }
  </style>
</head>
<body class="bg-white text-slate-800">

  <!-- =================================================================
       SECTION 1: TOP BAR (THÔNG TIN LIÊN HỆ NHANH - PHONG CÁCH FLATSOME)
       Không hiển thị thanh công cụ chỉnh sửa UX Builder
       ================================================================= -->
  <div class="bg-[var(--brand-dark)] text-white/95 text-[11px] sm:text-xs py-2 border-b border-white/10">
    <div class="flatsome-container flex flex-wrap items-center justify-between gap-y-1 gap-x-4">
      <div class="flex flex-wrap items-center gap-x-4 gap-y-1">
        <span class="inline-flex items-center gap-1.5 font-medium">
          <i class="fa-solid fa-phone text-[var(--brand-accent)] text-[11px]"></i>
          <a href="tel:0941394848" class="hover:text-[var(--brand-accent)] transition">0941 394 848</a>
        </span>
        <span class="hidden sm:inline text-white/30">|</span>
        <span class="inline-flex items-center gap-1.5">
          <i class="fa-solid fa-globe text-[var(--brand-accent)] text-[11px]"></i>
          <span>minhancdc.com</span>
        </span>
        <span class="hidden md:inline text-white/30">|</span>
        <span class="hidden md:inline-flex items-center gap-1.5 text-white/85">
          <i class="fa-solid fa-location-dot text-[var(--brand-accent)] text-[11px]"></i>
          <span>Trụ sở: 35 Phan Thành Tài, P. Hải Châu, TP. Đà Nẵng</span>
        </span>
      </div>
      <div class="flex items-center gap-3">
        <a href="https://www.facebook.com/jacky.huynh.311" target="_blank" rel="noopener noreferrer"
           class="inline-flex items-center gap-1.5 hover:text-[var(--brand-accent)] transition" aria-label="Facebook Minh Ân CDC">
          <i class="fa-brands fa-facebook-f text-xs"></i>
          <span class="hidden sm:inline">Facebook</span>
        </a>
        <a href="https://zalo.me/0941394848" target="_blank" rel="noopener noreferrer"
           class="inline-flex items-center gap-1.5 hover:text-[var(--brand-accent)] transition" aria-label="Zalo Minh Ân CDC">
          <i class="fa-solid fa-comment-dots text-xs"></i>
          <span class="hidden sm:inline">Zalo</span>
        </a>
      </div>
    </div>
  </div>

  <!-- =================================================================
       SECTION 2: HEADER CHÍNH (LOGO NHỎ GỌN + MENU 1 HÀNG DUY NHẤT)
       Không đặt nút Gọi ngay trên Header để tránh tràn viền
       ================================================================= -->
  <header id="main-header" class="sticky top-0 z-50 bg-white/95 backdrop-blur-md border-b border-slate-200 shadow-sm">
    <div class="flatsome-container flex items-center justify-between h-16 lg:h-[72px] gap-2">
      <!-- Logo gọn nhỏ -->
      <a href="#trang-chu" class="flex items-center gap-2.5 shrink-0 group" title="CÔNG TY TNHH MTV TƯ VẤN THIẾT KẾ XÂY DỰNG VÀ THƯƠNG MẠI MINH ÂN CDC">
        <img
          id="brand-logo"
          data-drive-id="1mB37EKXpyrvpswPrIUaMt2Wrn1lH-Gvu"
          src="https://lh3.googleusercontent.com/d/1mB37EKXpyrvpswPrIUaMt2Wrn1lH-Gvu=w400"
          alt="Logo Minh Ân CDC"
          class="h-10 sm:h-11 lg:h-12 w-auto max-w-[140px] object-contain rounded"
          onerror="handleDriveImageError(this)"
        >
        <div class="flex flex-col leading-tight">
          <span class="text-[13px] sm:text-sm lg:text-[15px] font-extrabold tracking-tight text-[var(--brand-primary)] whitespace-nowrap">
            MINH ÂN CDC
          </span>
          <span class="text-[9.5px] sm:text-[10px] font-medium text-slate-500 uppercase tracking-wider whitespace-nowrap">
            Thiết kế • Xây dựng • Thương mại
          </span>
        </div>
      </a>

      <!-- Menu máy tính: 1 hàng duy nhất, chữ gọn sắc nét, không bao giờ xuống dòng -->
      <nav aria-label="Menu chính" class="hidden lg:flex items-center justify-end flex-1 min-w-0">
        <ul class="flex items-center justify-end gap-0.5 xl:gap-1.5 list-none m-0 p-0">
          <li>
            <a href="#trang-chu" class="block px-2 xl:px-2.5 py-2 text-[12px] xl:text-[13px] font-semibold text-[var(--brand-primary)] hover:text-[var(--brand-accent)] whitespace-nowrap transition rounded-md">
              Trang chủ
            </a>
          </li>
          <li>
            <a href="#gioi-thieu" class="block px-2 xl:px-2.5 py-2 text-[12px] xl:text-[13px] font-semibold text-slate-700 hover:text-[var(--brand-primary)] whitespace-nowrap transition rounded-md">
              Giới thiệu
            </a>
          </li>
          <!-- Dropdown Công trình thực tế (theo danh mục web mẫu) -->
          <li class="nav-dropdown-parent">
            <a href="#cong-trinh-thuc-te" class="inline-flex items-center gap-1 px-2 xl:px-2.5 py-2 text-[12px] xl:text-[13px] font-semibold text-slate-700 hover:text-[var(--brand-primary)] whitespace-nowrap transition rounded-md">
              <span>Công trình thực tế</span>
              <i class="fa-solid fa-chevron-down text-[9px] text-slate-400"></i>
            </a>
            <div class="nav-dropdown-menu">
              <a href="#cong-trinh-thuc-te" onclick="selectCategoryFromNav('khach-san-can-ho')" class="block px-4 py-2 text-[13px] text-slate-700 hover:bg-[var(--brand-light)] hover:text-[var(--brand-primary)] font-medium">Khách sạn – Căn hộ – Phòng trọ</a>
              <a href="#cong-trinh-thuc-te" onclick="selectCategoryFromNav('biet-thu')" class="block px-4 py-2 text-[13px] text-slate-700 hover:bg-[var(--brand-light)] hover:text-[var(--brand-primary)] font-medium">Biệt thự</a>
              <a href="#cong-trinh-thuc-te" onclick="selectCategoryFromNav('nha-pho')" class="block px-4 py-2 text-[13px] text-slate-700 hover:bg-[var(--brand-light)] hover:text-[var(--brand-primary)] font-medium">Nhà phố</a>
              <a href="#cong-trinh-thuc-te" onclick="selectCategoryFromNav('van-phong')" class="block px-4 py-2 text-[13px] text-slate-700 hover:bg-[var(--brand-light)] hover:text-[var(--brand-primary)] font-medium">Văn phòng</a>
              <a href="#cong-trinh-thuc-te" onclick="selectCategoryFromNav('phan-tho-hoan-thien')" class="block px-4 py-2 text-[13px] text-slate-700 hover:bg-[var(--brand-light)] hover:text-[var(--brand-primary)] font-medium">Thi công phần thô & Hoàn thiện</a>
            </div>
          </li>
          <!-- Dropdown Lĩnh vực hoạt động (theo web mẫu) -->
          <li class="nav-dropdown-parent">
            <a href="#linh-vuc-hoat-dong" class="inline-flex items-center gap-1 px-2 xl:px-2.5 py-2 text-[12px] xl:text-[13px] font-semibold text-slate-700 hover:text-[var(--brand-primary)] whitespace-nowrap transition rounded-md">
              <span>Lĩnh vực hoạt động</span>
              <i class="fa-solid fa-chevron-down text-[9px] text-slate-400"></i>
            </a>
            <div class="nav-dropdown-menu">
              <a href="#linh-vuc-hoat-dong" class="block px-4 py-2 text-[13px] text-slate-700 hover:bg-[var(--brand-light)] hover:text-[var(--brand-primary)] font-medium">Thiết kế Kiến trúc – Nội thất</a>
              <a href="#linh-vuc-hoat-dong" class="block px-4 py-2 text-[13px] text-slate-700 hover:bg-[var(--brand-light)] hover:text-[var(--brand-primary)] font-medium">Thi công phần thô</a>
              <a href="#linh-vuc-hoat-dong" class="block px-4 py-2 text-[13px] text-slate-700 hover:bg-[var(--brand-light)] hover:text-[var(--brand-primary)] font-medium">Thi công hoàn thiện</a>
              <a href="#linh-vuc-hoat-dong" class="block px-4 py-2 text-[13px] text-slate-700 hover:bg-[var(--brand-light)] hover:text-[var(--brand-primary)] font-medium">Thi công nội thất & Thương mại</a>
            </div>
          </li>
          <li>
            <a href="#du-an-da-nang" class="block px-2 xl:px-2.5 py-2 text-[12px] xl:text-[13px] font-semibold text-slate-700 hover:text-[var(--brand-primary)] whitespace-nowrap transition rounded-md">
              Dự án Đà Nẵng
            </a>
          </li>
          <!-- Dropdown Báo giá (theo web mẫu) -->
          <li class="nav-dropdown-parent">
            <a href="#bao-gia" class="inline-flex items-center gap-1 px-2 xl:px-2.5 py-2 text-[12px] xl:text-[13px] font-semibold text-slate-700 hover:text-[var(--brand-primary)] whitespace-nowrap transition rounded-md">
              <span>Báo giá</span>
              <i class="fa-solid fa-chevron-down text-[9px] text-slate-400"></i>
            </a>
            <div class="nav-dropdown-menu">
              <a href="#bao-gia" onclick="prefillQuoteType('Thiết kế Kiến trúc - Nội thất')" class="block px-4 py-2 text-[13px] text-slate-700 hover:bg-[var(--brand-light)] hover:text-[var(--brand-primary)] font-medium">Báo giá thiết kế kiến trúc</a>
              <a href="#bao-gia" onclick="prefillQuoteType('Thi công phần thô')" class="block px-4 py-2 text-[13px] text-slate-700 hover:bg-[var(--brand-light)] hover:text-[var(--brand-primary)] font-medium">Báo giá thi công phần thô</a>
              <a href="#bao-gia" onclick="prefillQuoteType('Thi công hoàn thiện')" class="block px-4 py-2 text-[13px] text-slate-700 hover:bg-[var(--brand-light)] hover:text-[var(--brand-primary)] font-medium">Báo giá thi công hoàn thiện</a>
              <a href="#bao-gia" onclick="prefillQuoteType('Thi công trọn gói')" class="block px-4 py-2 text-[13px] text-slate-700 hover:bg-[var(--brand-light)] hover:text-[var(--brand-primary)] font-medium">Báo giá thi công trọn gói</a>
            </div>
          </li>
          <li>
            <a href="#doi-tac" class="block px-2 xl:px-2.5 py-2 text-[12px] xl:text-[13px] font-semibold text-slate-700 hover:text-[var(--brand-primary)] whitespace-nowrap transition rounded-md">
              Đối tác
            </a>
          </li>
          <li>
            <a href="#tin-tuc" class="block px-2 xl:px-2.5 py-2 text-[12px] xl:text-[13px] font-semibold text-slate-700 hover:text-[var(--brand-primary)] whitespace-nowrap transition rounded-md">
              Tin tức
            </a>
          </li>
          <li>
            <a href="#lien-he" class="block px-2 xl:px-2.5 py-2 text-[12px] xl:text-[13px] font-semibold text-slate-700 hover:text-[var(--brand-primary)] whitespace-nowrap transition rounded-md">
              Liên hệ
            </a>
          </li>
        </ul>
      </nav>

      <!-- Nút mở Menu trên Điện thoại / Tablet -->
      <button id="mobile-menu-open" type="button"
              class="lg:hidden inline-flex items-center justify-center w-10 h-10 rounded-lg border border-slate-200 text-[var(--brand-primary)] hover:bg-[var(--brand-light)] transition shrink-0"
              aria-label="Mở menu điều hướng">
        <i class="fa-solid fa-bars text-lg"></i>
      </button>
    </div>
  </header>

  <!-- Menu trượt ngang cho Mobile (Flatsome Off-Canvas Drawer) -->
  <div id="mobile-drawer-overlay" class="fixed inset-0 z-[70] bg-slate-900/55 hidden opacity-0 transition-opacity duration-200"></div>
  <aside id="mobile-drawer" class="fixed top-0 left-0 bottom-0 z-[80] w-[82%] max-w-[320px] bg-white shadow-2xl transform -translate-x-full transition-transform duration-300 flex flex-col">
    <div class="flex items-center justify-between px-4 py-3.5 border-b border-slate-200 bg-[var(--brand-light)]">
      <div class="flex items-center gap-2">
        <img
          data-drive-id="1mB37EKXpyrvpswPrIUaMt2Wrn1lH-Gvu"
          src="https://lh3.googleusercontent.com/d/1mB37EKXpyrvpswPrIUaMt2Wrn1lH-Gvu=w300"
          alt="Logo Minh Ân CDC"
          class="h-8 w-auto object-contain rounded"
          onerror="handleDriveImageError(this)"
        >
        <span class="font-bold text-sm text-[var(--brand-primary)]">MINH ÂN CDC</span>
      </div>
      <button id="mobile-menu-close" type="button" class="w-9 h-9 rounded-lg flex items-center justify-center text-slate-600 hover:bg-white transition" aria-label="Đóng menu">
        <i class="fa-solid fa-xmark text-lg"></i>
      </button>
    </div>
    <div class="flex-1 overflow-y-auto py-3 px-4 space-y-1">
      <a href="#trang-chu" class="mobile-nav-link block py-2.5 px-3 rounded-lg text-sm font-semibold text-[var(--brand-primary)] bg-[var(--brand-light)]">Trang chủ</a>
      <a href="#gioi-thieu" class="mobile-nav-link block py-2.5 px-3 rounded-lg text-sm font-semibold text-slate-700 hover:bg-slate-50">Giới thiệu</a>
      <a href="#linh-vuc-hoat-dong" class="mobile-nav-link block py-2.5 px-3 rounded-lg text-sm font-semibold text-slate-700 hover:bg-slate-50">Lĩnh vực hoạt động</a>

      <div class="pt-1">
        <a href="#cong-trinh-thuc-te" class="mobile-nav-link block py-2.5 px-3 rounded-lg text-sm font-semibold text-slate-700 hover:bg-slate-50">Công trình thực tế</a>
        <div class="pl-4 border-l-2 border-slate-100 ml-3 space-y-1 mt-1">
          <a href="#cong-trinh-thuc-te" onclick="selectCategoryFromNav('khach-san-can-ho')" class="mobile-nav-link block py-1.5 px-2 text-xs font-medium text-slate-600 hover:text-[var(--brand-primary)]">Khách sạn – Căn hộ – Phòng trọ</a>
          <a href="#cong-trinh-thuc-te" onclick="selectCategoryFromNav('biet-thu')" class="mobile-nav-link block py-1.5 px-2 text-xs font-medium text-slate-600 hover:text-[var(--brand-primary)]">Biệt thự</a>
          <a href="#cong-trinh-thuc-te" onclick="selectCategoryFromNav('nha-pho')" class="mobile-nav-link block py-1.5 px-2 text-xs font-medium text-slate-600 hover:text-[var(--brand-primary)]">Nhà phố</a>
          <a href="#cong-trinh-thuc-te" onclick="selectCategoryFromNav('van-phong')" class="mobile-nav-link block py-1.5 px-2 text-xs font-medium text-slate-600 hover:text-[var(--brand-primary)]">Văn phòng</a>
        </div>
      </div>

      <a href="#du-an-da-nang" class="mobile-nav-link block py-2.5 px-3 rounded-lg text-sm font-semibold text-slate-700 hover:bg-slate-50">Dự án tại Đà Nẵng</a>
      <a href="#doi-tac" class="mobile-nav-link block py-2.5 px-3 rounded-lg text-sm font-semibold text-slate-700 hover:bg-slate-50">Đối tác tiêu biểu</a>
      <a href="#bao-gia" class="mobile-nav-link block py-2.5 px-3 rounded-lg text-sm font-semibold text-slate-700 hover:bg-slate-50">Yêu cầu Báo giá</a>
      <a href="#tin-tuc" class="mobile-nav-link block py-2.5 px-3 rounded-lg text-sm font-semibold text-slate-700 hover:bg-slate-50">Tin tức & Bài viết</a>
      <a href="#lien-he" class="mobile-nav-link block py-2.5 px-3 rounded-lg text-sm font-semibold text-slate-700 hover:bg-slate-50">Liên hệ & Bản đồ</a>
    </div>
    <div class="p-4 border-t border-slate-200 bg-slate-50 text-xs text-slate-600 space-y-1.5">
      <div class="font-semibold text-[var(--brand-primary)]">Hotline: <a href="tel:0941394848" class="underline">0941 394 848</a></div>
      <div>35 Phan Thành Tài, P. Hải Châu, Đà Nẵng</div>
    </div>
  </aside>

  <!-- =================================================================
       SECTION 3: 2 ẢNH BANNER TỰ TRƯỢT CHUYÊN NGHIỆP KÍCH THƯỚC BẰNG NHAU
       Hình ảnh và chữ nằm trọn trong banner, cách xa viền, không mất chữ trên Mobile & Desktop
       ================================================================= -->
  <section id="trang-chu" class="py-3 sm:py-4 lg:py-5 bg-slate-50">
    <div class="flatsome-container">
      <div class="hero-slider-viewport shadow-lg border border-slate-200 bg-[var(--brand-dark)]" id="hero-slider">
        <div class="hero-slider-track" id="hero-track">

          <!-- BANNER 1 -->
          <div class="hero-slide bg-gradient-to-br from-[#072848] via-[#0B3D6B] to-[#12528C] text-white">
            <!-- Khoảng đệm lớn (px-11 sm:px-16 md:px-20 lg:px-24) giúp chữ và ảnh luôn cách xa viền banner ở mọi màn hình -->
            <div class="w-full px-11 sm:px-16 md:px-20 lg:px-24 py-8 sm:py-11 md:py-14 lg:py-16">
              <div class="grid grid-cols-1 md:grid-cols-12 gap-5 md:gap-8 lg:gap-10 items-center">
                <div class="md:col-span-7 space-y-3 sm:space-y-4">
                  <div class="text-[11px] sm:text-xs font-bold uppercase tracking-[0.16em] text-[#F5C156]">
                    MINH ÂN CDC • ĐÀ NẴNG &amp; HUẾ
                  </div>
                  <h1 class="text-lg sm:text-2xl md:text-3xl lg:text-[34px] font-extrabold leading-snug text-white break-words">
                    TƯ VẤN THIẾT KẾ KIẾN TRÚC &amp; THI CÔNG XÂY DỰNG TRỌN GÓI
                  </h1>
                  <p class="text-xs sm:text-sm md:text-[15px] text-slate-200 leading-relaxed max-w-2xl">
                    Kiến tạo không gian sống đẳng cấp cho Nhà phố, Biệt thự, Khách sạn, Căn hộ và Văn phòng với tiêu chuẩn kỹ thuật vững chắc, minh bạch chi phí và đúng tiến độ cam kết.
                  </p>
                  <div class="flex flex-wrap items-center gap-2.5 sm:gap-3 pt-1">
                    <a href="#bao-gia" class="inline-flex items-center justify-center gap-2 px-4 sm:px-6 py-2.5 rounded-lg bg-[var(--brand-accent)] hover:bg-[var(--brand-accent-hover)] text-white text-xs sm:text-sm font-bold shadow-md transition">
                      <span>Nhận báo giá ngay</span>
                      <i class="fa-solid fa-arrow-right text-xs"></i>
                    </a>
                    <a href="#cong-trinh-thuc-te" class="inline-flex items-center justify-center gap-2 px-4 sm:px-6 py-2.5 rounded-lg bg-white/10 hover:bg-white/20 border border-white/30 text-white text-xs sm:text-sm font-semibold transition">
                      <span>Xem công trình</span>
                    </a>
                  </div>
                </div>
                <div class="md:col-span-5">
                  <div class="rounded-xl overflow-hidden border-2 border-white/25 shadow-2xl bg-slate-900/40 aspect-[16/10] w-full">
                    <img
                      data-drive-id="13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz"
                      src="https://lh3.googleusercontent.com/d/13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz=w1000"
                      alt="Công trình thi công xây dựng thực tế Minh Ân CDC"
                      class="w-full h-full object-cover"
                      onerror="handleDriveImageError(this)"
                    >
                  </div>
                </div>
              </div>
            </div>
          </div>

          <!-- BANNER 2 (Cấu trúc, tỷ lệ ảnh và độ dài chữ đồng nhất 100% với Banner 1 để 2 banner bằng nhau tuyệt đối) -->
          <div class="hero-slide bg-gradient-to-br from-[#0A2F54] via-[#10467A] to-[#1A365D] text-white">
            <div class="w-full px-11 sm:px-16 md:px-20 lg:px-24 py-8 sm:py-11 md:py-14 lg:py-16">
              <div class="grid grid-cols-1 md:grid-cols-12 gap-5 md:gap-8 lg:gap-10 items-center">
                <div class="md:col-span-7 space-y-3 sm:space-y-4">
                  <div class="text-[11px] sm:text-xs font-bold uppercase tracking-[0.16em] text-[#F5C156]">
                    CHẤT LƯỢNG TẠO NIỀM TIN • MINHANCDC.COM
                  </div>
                  <h2 class="text-lg sm:text-2xl md:text-3xl lg:text-[34px] font-extrabold leading-snug text-white break-words">
                    NHÀ THẦU CHUYÊN NGHIỆP CÁC DỰ ÁN TIÊU BIỂU TẠI ĐÀ NẴNG
                  </h2>
                  <p class="text-xs sm:text-sm md:text-[15px] text-slate-200 leading-relaxed max-w-2xl">
                    Đội ngũ kỹ sư, kiến trúc sư giàu kinh nghiệm trực tiếp giám sát thi công từ phần thô đến hoàn thiện nội thất, bảo hành công trình lâu dài và tư vấn tận tâm 24/7.
                  </p>
                  <div class="flex flex-wrap items-center gap-2.5 sm:gap-3 pt-1">
                    <a href="#du-an-da-nang" class="inline-flex items-center justify-center gap-2 px-4 sm:px-6 py-2.5 rounded-lg bg-[var(--brand-accent)] hover:bg-[var(--brand-accent-hover)] text-white text-xs sm:text-sm font-bold shadow-md transition">
                      <span>Dự án tại Đà Nẵng</span>
                      <i class="fa-solid fa-arrow-right text-xs"></i>
                    </a>
                    <a href="#lien-he" class="inline-flex items-center justify-center gap-2 px-4 sm:px-6 py-2.5 rounded-lg bg-white/10 hover:bg-white/20 border border-white/30 text-white text-xs sm:text-sm font-semibold transition">
                      <span>Liên hệ tư vấn</span>
                    </a>
                  </div>
                </div>
                <div class="md:col-span-5">
                  <div class="rounded-xl overflow-hidden border-2 border-white/25 shadow-2xl bg-slate-900/40 aspect-[16/10] w-full">
                    <img
                      data-drive-id="157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT"
                      src="https://lh3.googleusercontent.com/d/157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT=w1000"
                      alt="Dự án xây dựng tại Đà Nẵng - Minh Ân CDC"
                      class="w-full h-full object-cover"
                      onerror="handleDriveImageError(this)"
                    >
                  </div>
                </div>
              </div>
            </div>
          </div>

        </div>

        <!-- Nút chuyển slide trái / phải nằm sát mép ngoài vùng padding an toàn -->
        <button id="hero-prev" type="button"
                class="absolute left-2 sm:left-3.5 top-1/2 -translate-y-1/2 w-8 h-8 sm:w-10 sm:h-10 rounded-full bg-black/35 hover:bg-[var(--brand-accent)] text-white flex items-center justify-center transition z-20"
                aria-label="Banner trước">
          <i class="fa-solid fa-chevron-left text-xs sm:text-sm"></i>
        </button>
        <button id="hero-next" type="button"
                class="absolute right-2 sm:right-3.5 top-1/2 -translate-y-1/2 w-8 h-8 sm:w-10 sm:h-10 rounded-full bg-black/35 hover:bg-[var(--brand-accent)] text-white flex items-center justify-center transition z-20"
                aria-label="Banner tiếp theo">
          <i class="fa-solid fa-chevron-right text-xs sm:text-sm"></i>
        </button>

        <!-- Chấm chỉ báo 2 banner -->
        <div class="absolute bottom-2.5 sm:bottom-3.5 left-1/2 -translate-x-1/2 flex items-center gap-2 z-20">
          <button type="button" class="hero-dot w-7 h-2 rounded-full bg-[var(--brand-accent)] transition-all" data-slide="0" aria-label="Xem banner 1"></button>
          <button type="button" class="hero-dot w-2.5 h-2 rounded-full bg-white/50 hover:bg-white transition-all" data-slide="1" aria-label="Xem banner 2"></button>
        </div>
      </div>
    </div>
  </section>

  <!-- =================================================================
       SECTION 4: DỊCH VỤ TIÊU BIỂU (3 KHỐI FLATSOME NHƯ WEB MẪU)
       ================================================================= -->
  <section id="linh-vuc-hoat-dong" class="py-10 sm:py-12 lg:py-14 bg-white">
    <div class="flatsome-container">
      <div class="text-center mb-7 sm:mb-9">
        <h2 class="flatsome-section-title text-lg sm:text-2xl lg:text-[26px] font-extrabold uppercase text-[var(--brand-primary)]">
          Dịch vụ tiêu biểu
        </h2>
        <p class="mt-3 text-xs sm:text-sm text-slate-600 max-w-2xl mx-auto">
          Giải pháp toàn diện từ ý tưởng kiến trúc, hồ sơ kỹ thuật đến thi công xây dựng và hoàn thiện nội thất
        </p>
      </div>

      <div class="grid grid-cols-1 md:grid-cols-3 gap-4 sm:gap-6">
        <!-- Dịch vụ 1 -->
        <div class="ux-card bg-white rounded-xl border border-slate-200 overflow-hidden flex flex-col">
          <div class="aspect-[16/10] w-full overflow-hidden bg-slate-100">
            <img
              data-drive-id="1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR"
              src="https://lh3.googleusercontent.com/d/1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR=w800"
              alt="Thiết kế Kiến trúc - Nội thất"
              class="w-full h-full object-cover"
              onerror="handleDriveImageError(this)"
            >
          </div>
          <div class="p-4 sm:p-5 flex-1 flex flex-col">
            <div class="flex items-center gap-2.5 mb-2">
              <span class="w-9 h-9 rounded-lg bg-[var(--brand-light)] text-[var(--brand-primary)] flex items-center justify-center shrink-0">
                <i class="fa-solid fa-compass-drafting text-base"></i>
              </span>
              <h3 class="text-sm sm:text-base font-bold uppercase text-[var(--brand-primary)]">
                Thiết kế Kiến trúc – Nội thất
              </h3>
            </div>
            <p class="text-xs sm:text-sm text-slate-600 leading-relaxed flex-1">
              Tư vấn lập phương án kiến trúc, kết cấu, điện nước (M&amp;E) và phối cảnh 3D tối ưu công năng, thẩm mỹ và phong thủy cho mọi công trình.
            </p>
            <a href="#bao-gia" onclick="prefillQuoteType('Thiết kế Kiến trúc - Nội thất')" class="mt-3 inline-flex items-center gap-1.5 text-xs sm:text-sm font-semibold text-[var(--brand-accent)] hover:text-[var(--brand-primary)] transition">
              <span>Nhận tư vấn thiết kế</span>
              <i class="fa-solid fa-angle-right text-xs"></i>
            </a>
          </div>
        </div>

        <!-- Dịch vụ 2 -->
        <div class="ux-card bg-white rounded-xl border border-slate-200 overflow-hidden flex flex-col">
          <div class="aspect-[16/10] w-full overflow-hidden bg-slate-100">
            <img
              data-drive-id="1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv"
              src="https://lh3.googleusercontent.com/d/1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv=w800"
              alt="Thi công Xây dựng Phần thô & Trọn gói"
              class="w-full h-full object-cover"
              onerror="handleDriveImageError(this)"
            >
          </div>
          <div class="p-4 sm:p-5 flex-1 flex flex-col">
            <div class="flex items-center gap-2.5 mb-2">
              <span class="w-9 h-9 rounded-lg bg-[var(--brand-light)] text-[var(--brand-primary)] flex items-center justify-center shrink-0">
                <i class="fa-solid fa-helmet-safety text-base"></i>
              </span>
              <h3 class="text-sm sm:text-base font-bold uppercase text-[var(--brand-primary)]">
                Thi công Xây dựng Trọn gói
              </h3>
            </div>
            <p class="text-xs sm:text-sm text-slate-600 leading-relaxed flex-1">
              Thi công phần thô, nhân công hoàn thiện và chìa khóa trao tay cho nhà phố, biệt thự, khách sạn, căn hộ dịch vụ với quy trình kiểm soát chất lượng nghiêm ngặt.
            </p>
            <a href="#bao-gia" onclick="prefillQuoteType('Thi công trọn gói')" class="mt-3 inline-flex items-center gap-1.5 text-xs sm:text-sm font-semibold text-[var(--brand-accent)] hover:text-[var(--brand-primary)] transition">
              <span>Nhận báo giá thi công</span>
              <i class="fa-solid fa-angle-right text-xs"></i>
            </a>
          </div>
        </div>

        <!-- Dịch vụ 3 -->
        <div class="ux-card bg-white rounded-xl border border-slate-200 overflow-hidden flex flex-col">
          <div class="aspect-[16/10] w-full overflow-hidden bg-slate-100">
            <img
              data-drive-id="1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_"
              src="https://lh3.googleusercontent.com/d/1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_=w800"
              alt="Hoàn thiện Nội thất & Thương mại Vật tư"
              class="w-full h-full object-cover"
              onerror="handleDriveImageError(this)"
            >
          </div>
          <div class="p-4 sm:p-5 flex-1 flex flex-col">
            <div class="flex items-center gap-2.5 mb-2">
              <span class="w-9 h-9 rounded-lg bg-[var(--brand-light)] text-[var(--brand-primary)] flex items-center justify-center shrink-0">
                <i class="fa-solid fa-couch text-base"></i>
              </span>
              <h3 class="text-sm sm:text-base font-bold uppercase text-[var(--brand-primary)]">
                Nội thất &amp; Thương mại Vật tư
              </h3>
            </div>
            <p class="text-xs sm:text-sm text-slate-600 leading-relaxed flex-1">
              Thi công hoàn thiện nội thất văn phòng, nhà ở, cải tạo sửa chữa và cung cấp vật liệu, thiết bị điện nước chính hãng đạt chuẩn công trình.
            </p>
            <a href="#bao-gia" onclick="prefillQuoteType('Thi công hoàn thiện')" class="mt-3 inline-flex items-center gap-1.5 text-xs sm:text-sm font-semibold text-[var(--brand-accent)] hover:text-[var(--brand-primary)] transition">
              <span>Tìm hiểu giải pháp</span>
              <i class="fa-solid fa-angle-right text-xs"></i>
            </a>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- =================================================================
       SECTION 5: GIỚI THIỆU MINH ÂN CDC & THẾ MẠNH CỦA CHÚNG TÔI
       ================================================================= -->
  <section id="gioi-thieu" class="py-10 sm:py-12 lg:py-14 bg-[var(--brand-light)] border-y border-slate-200/80">
    <div class="flatsome-container">
      <!-- Giới thiệu công ty -->
      <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 lg:gap-10 items-center mb-10 sm:mb-12">
        <div class="lg:col-span-6 space-y-3.5">
          <div class="text-xs font-bold uppercase tracking-widest text-[var(--brand-accent)]">
            Về chúng tôi
          </div>
          <h2 class="flatsome-section-title align-left text-lg sm:text-2xl font-extrabold text-[var(--brand-primary)] leading-snug">
            CÔNG TY TNHH MTV TƯ VẤN THIẾT KẾ XÂY DỰNG VÀ THƯƠNG MẠI MINH ÂN CDC
          </h2>
          <p class="text-xs sm:text-sm md:text-[15px] text-slate-700 leading-relaxed">
            <strong>Minh Ân CDC</strong> là đơn vị chuyên sâu trong lĩnh vực Tư vấn Thiết kế Kiến trúc – Nội thất, Thi công Xây dựng và Thương mại vật tư tại khu vực <strong>Đà Nẵng – Huế – Miền Trung</strong>. Chúng tôi sở hữu đầy đủ Chứng chỉ năng lực hoạt động xây dựng (Mã số: <strong>00064700</strong>) cùng đội ngũ kiến trúc sư, kỹ sư và tổ đội thi công lành nghề.
          </p>
          <p class="text-xs sm:text-sm md:text-[15px] text-slate-700 leading-relaxed">
            Đặt chữ <strong>"TÂM"</strong> và uy tín nghề nghiệp lên hàng đầu, mỗi công trình Minh Ân CDC thực hiện đều tuân thủ nghiêm ngặt tiêu chí: <strong>AN TOÀN – CHẤT LƯỢNG – TIẾN ĐỘ – CHI PHÍ HỢP LÝ</strong>, mang lại sự an tâm trọn vẹn cho Quý Chủ đầu tư.
          </p>
          <div class="grid grid-cols-3 gap-2.5 sm:gap-4 pt-2">
            <div class="bg-white rounded-xl p-3 sm:p-4 border border-slate-200 text-center">
              <div class="text-lg sm:text-2xl font-extrabold text-[var(--brand-primary)]">100%</div>
              <div class="text-[11px] sm:text-xs text-slate-600 mt-0.5">Đúng tiến độ</div>
            </div>
            <div class="bg-white rounded-xl p-3 sm:p-4 border border-slate-200 text-center">
              <div class="text-lg sm:text-2xl font-extrabold text-[var(--brand-accent)]">24/7</div>
              <div class="text-[11px] sm:text-xs text-slate-600 mt-0.5">Tư vấn tận tâm</div>
            </div>
            <div class="bg-white rounded-xl p-3 sm:p-4 border border-slate-200 text-center">
              <div class="text-lg sm:text-2xl font-extrabold text-[var(--brand-primary)]">02</div>
              <div class="text-[11px] sm:text-xs text-slate-600 mt-0.5">VP Đà Nẵng &amp; Huế</div>
            </div>
          </div>
        </div>

        <div class="lg:col-span-6">
          <div class="grid grid-cols-2 gap-3 sm:gap-4">
            <div class="rounded-xl overflow-hidden border border-white shadow-md aspect-[4/3] bg-slate-200">
              <img
                data-drive-id="1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO"
                src="https://lh3.googleusercontent.com/d/1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO=w800"
                alt="Thi công công trình Minh Ân CDC"
                class="w-full h-full object-cover"
                onerror="handleDriveImageError(this)"
              >
            </div>
            <div class="rounded-xl overflow-hidden border border-white shadow-md aspect-[4/3] bg-slate-200">
              <img
                data-drive-id="1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t"
                src="https://lh3.googleusercontent.com/d/1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t=w800"
                alt="Giám sát thi công kỹ thuật Minh Ân CDC"
                class="w-full h-full object-cover"
                onerror="handleDriveImageError(this)"
              >
            </div>
          </div>
        </div>
      </div>

      <!-- 6 Thế mạnh của Minh Ân CDC (bố cục Flatsome giống web mẫu) -->
      <div class="text-center mb-6 sm:mb-8">
        <h3 class="flatsome-section-title text-base sm:text-xl font-extrabold uppercase text-[var(--brand-primary)]">
          Thế mạnh của Minh Ân CDC
        </h3>
      </div>

      <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-4 sm:gap-5">
        <div class="bg-white rounded-xl p-4 sm:p-5 border border-slate-200 shadow-sm flex items-start gap-3.5">
          <div class="w-10 h-10 rounded-lg bg-[var(--brand-primary)] text-white flex items-center justify-center shrink-0">
            <i class="fa-solid fa-users-gear"></i>
          </div>
          <div>
            <h4 class="text-sm font-bold text-[var(--brand-primary)] mb-1">Đội ngũ Kiến trúc sư, Kỹ sư chuyên nghiệp</h4>
            <p class="text-xs sm:text-[13px] text-slate-600 leading-relaxed">Đội ngũ kiến trúc sư sáng tạo kết hợp kỹ sư hiện trường giàu kinh nghiệm và thợ tay nghề cao.</p>
          </div>
        </div>

        <div class="bg-white rounded-xl p-4 sm:p-5 border border-slate-200 shadow-sm flex items-start gap-3.5">
          <div class="w-10 h-10 rounded-lg bg-[var(--brand-primary)] text-white flex items-center justify-center shrink-0">
            <i class="fa-solid fa-layer-group"></i>
          </div>
          <div>
            <h4 class="text-sm font-bold text-[var(--brand-primary)] mb-1">Cập nhật xu hướng thiết kế hiện đại</h4>
            <p class="text-xs sm:text-[13px] text-slate-600 leading-relaxed">Ứng dụng giải pháp kiến trúc tối ưu ánh sáng, thông gió tự nhiên, vật liệu bền vững và hiện đại.</p>
          </div>
        </div>

        <div class="bg-white rounded-xl p-4 sm:p-5 border border-slate-200 shadow-sm flex items-start gap-3.5">
          <div class="w-10 h-10 rounded-lg bg-[var(--brand-primary)] text-white flex items-center justify-center shrink-0">
            <i class="fa-solid fa-clipboard-check"></i>
          </div>
          <div>
            <h4 class="text-sm font-bold text-[var(--brand-primary)] mb-1">Giám sát tiến độ &amp; chất lượng chuẩn xác</h4>
            <p class="text-xs sm:text-[13px] text-slate-600 leading-relaxed">Cập nhật báo cáo tiến độ thực tế thường xuyên giúp chủ đầu tư theo dõi công trình minh bạch mọi lúc.</p>
          </div>
        </div>

        <div class="bg-white rounded-xl p-4 sm:p-5 border border-slate-200 shadow-sm flex items-start gap-3.5">
          <div class="w-10 h-10 rounded-lg bg-[var(--brand-primary)] text-white flex items-center justify-center shrink-0">
            <i class="fa-solid fa-shield-halved"></i>
          </div>
          <div>
            <h4 class="text-sm font-bold text-[var(--brand-primary)] mb-1">Bảo hành công trình lâu dài</h4>
            <p class="text-xs sm:text-[13px] text-slate-600 leading-relaxed">Cam kết chính sách bảo hành kết cấu và hoàn thiện rõ ràng, hỗ trợ nhanh chóng khi khách hàng cần.</p>
          </div>
        </div>

        <div class="bg-white rounded-xl p-4 sm:p-5 border border-slate-200 shadow-sm flex items-start gap-3.5">
          <div class="w-10 h-10 rounded-lg bg-[var(--brand-primary)] text-white flex items-center justify-center shrink-0">
            <i class="fa-solid fa-hand-holding-dollar"></i>
          </div>
          <div>
            <h4 class="text-sm font-bold text-[var(--brand-primary)] mb-1">Dự toán minh bạch, chi phí hợp lý</h4>
            <p class="text-xs sm:text-[13px] text-slate-600 leading-relaxed">Bóc tách khối lượng chi tiết, không phát sinh vô lý, cân đối tối ưu ngân sách theo chất lượng thực tế.</p>
          </div>
        </div>

        <div class="bg-white rounded-xl p-4 sm:p-5 border border-slate-200 shadow-sm flex items-start gap-3.5">
          <div class="w-10 h-10 rounded-lg bg-[var(--brand-primary)] text-white flex items-center justify-center shrink-0">
            <i class="fa-solid fa-headset"></i>
          </div>
          <div>
            <h4 class="text-sm font-bold text-[var(--brand-primary)] mb-1">Hỗ trợ tư vấn miễn phí 24/7</h4>
            <p class="text-xs sm:text-[13px] text-slate-600 leading-relaxed">Sẵn sàng khảo sát thực tế, tư vấn phương án và lập dự toán sơ bộ hoàn toàn miễn phí qua Hotline 0941 394 848.</p>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- =================================================================
       SECTION 6: CÔNG TRÌNH THỰC TẾ & DANH MỤC SẢN PHẨM (9 ẢNH THỰC TẾ)
       - Không đặt nhãn dán trên ảnh
       - Danh mục nhỏ gọn, 1 hàng trên máy tính, không xuống dòng tên danh mục
       - Chia đúng 2 cột trên điện thoại, tên sản phẩm đầy đủ không cắt chữ
       ================================================================= -->
  <section id="cong-trinh-thuc-te" class="py-10 sm:py-12 lg:py-14 bg-white">
    <div class="flatsome-container">
      <div class="text-center mb-6 sm:mb-7">
        <h2 class="flatsome-section-title text-lg sm:text-2xl lg:text-[26px] font-extrabold uppercase text-[var(--brand-primary)]">
          Công trình thi công thực tế
        </h2>
        <p class="mt-3 text-xs sm:text-sm text-slate-600 max-w-2xl mx-auto">
          Hình ảnh thực tế các hạng mục thi công xây dựng và hoàn thiện do Minh Ân CDC trực tiếp triển khai
        </p>
      </div>

      <!-- Thanh lọc danh mục theo web mẫu: nhỏ gọn, viết liền không ngắt chữ -->
      <div id="category-tabs" class="flex flex-wrap items-center justify-center gap-1.5 sm:gap-2 mb-6 sm:mb-8">
        <button type="button" data-cat="all" class="cat-tab-btn active px-3 sm:px-4 py-1.5 sm:py-2 rounded-full border border-slate-300 text-[11px] sm:text-xs lg:text-[13px] font-semibold">
          Tất cả
        </button>
        <button type="button" data-cat="khach-san-can-ho" class="cat-tab-btn px-3 sm:px-4 py-1.5 sm:py-2 rounded-full border border-slate-300 bg-white text-slate-700 hover:border-[var(--brand-primary)] hover:text-[var(--brand-primary)] text-[11px] sm:text-xs lg:text-[13px] font-semibold">
          Khách sạn - Căn hộ
        </button>
        <button type="button" data-cat="biet-thu" class="cat-tab-btn px-3 sm:px-4 py-1.5 sm:py-2 rounded-full border border-slate-300 bg-white text-slate-700 hover:border-[var(--brand-primary)] hover:text-[var(--brand-primary)] text-[11px] sm:text-xs lg:text-[13px] font-semibold">
          Biệt thự
        </button>
        <button type="button" data-cat="nha-pho" class="cat-tab-btn px-3 sm:px-4 py-1.5 sm:py-2 rounded-full border border-slate-300 bg-white text-slate-700 hover:border-[var(--brand-primary)] hover:text-[var(--brand-primary)] text-[11px] sm:text-xs lg:text-[13px] font-semibold">
          Nhà phố
        </button>
        <button type="button" data-cat="van-phong" class="cat-tab-btn px-3 sm:px-4 py-1.5 sm:py-2 rounded-full border border-slate-300 bg-white text-slate-700 hover:border-[var(--brand-primary)] hover:text-[var(--brand-primary)] text-[11px] sm:text-xs lg:text-[13px] font-semibold">
          Văn phòng
        </button>
        <button type="button" data-cat="phan-tho-hoan-thien" class="cat-tab-btn px-3 sm:px-4 py-1.5 sm:py-2 rounded-full border border-slate-300 bg-white text-slate-700 hover:border-[var(--brand-primary)] hover:text-[var(--brand-primary)] text-[11px] sm:text-xs lg:text-[13px] font-semibold">
          Phần thô &amp; Hoàn thiện
        </button>
      </div>

      <!-- Lưới sản phẩm / công trình thực tế: 2 cột trên điện thoại, 3 cột tablet, 4 cột desktop -->
      <div id="construction-grid" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-2.5 sm:gap-4 lg:gap-5">
        <!-- Dữ liệu 9 ảnh thực tế được render bằng JS để hỗ trợ lọc danh mục mượt mà và xem ảnh phóng to -->
      </div>
    </div>
  </section>

  <!-- =================================================================
       SECTION 7: CÁC DỰ ÁN TIÊU BIỂU TẠI ĐÀ NẴNG (10 ẢNH DỰ ÁN ĐÀ NẴNG)
       - Không đặt nhãn dán trên ảnh
       - Chia 2 cột trên điện thoại, tên đầy đủ không bị tràn hay thiếu chữ
       ================================================================= -->
  <section id="du-an-da-nang" class="py-10 sm:py-12 lg:py-14 bg-slate-50 border-y border-slate-200/80">
    <div class="flatsome-container">
      <div class="text-center mb-6 sm:mb-8">
        <h2 class="flatsome-section-title text-lg sm:text-2xl lg:text-[26px] font-extrabold uppercase text-[var(--brand-primary)]">
          Các dự án tại Đà Nẵng
        </h2>
        <p class="mt-3 text-xs sm:text-sm text-slate-600 max-w-2xl mx-auto">
          Bộ sưu tập các dự án tiêu biểu Minh Ân CDC thiết kế và thi công tại thành phố Đà Nẵng
        </p>
      </div>

      <!-- Lưới 10 dự án tại Đà Nẵng: 2 cột trên điện thoại, 3-5 cột trên màn hình lớn -->
      <div id="danang-projects-grid" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-5 gap-2.5 sm:gap-4 lg:gap-5">
        <!-- Render 10 dự án Đà Nẵng từ bộ ảnh Google Drive người dùng cung cấp -->
      </div>
    </div>
  </section>

  <!-- =================================================================
       SECTION 8: ĐỐI TÁC TIÊU BIỂU
       ================================================================= -->
  <section id="doi-tac" class="py-10 sm:py-12 bg-white">
    <div class="flatsome-container">
      <div class="text-center mb-6 sm:mb-8">
        <h2 class="flatsome-section-title text-lg sm:text-2xl font-extrabold uppercase text-[var(--brand-primary)]">
          Đối tác tiêu biểu
        </h2>
        <p class="mt-3 text-xs sm:text-sm text-slate-600 max-w-2xl mx-auto">
          Hợp tác cùng các thương hiệu vật liệu xây dựng và thiết bị nội thất uy tín hàng đầu
        </p>
      </div>

      <div class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-4 lg:grid-cols-6 gap-3 sm:gap-4">
        <div class="rounded-xl border border-slate-200 bg-slate-50/70 hover:bg-white hover:border-[var(--brand-primary)] hover:shadow-md transition p-4 flex flex-col items-center justify-center text-center min-h-[82px]">
          <span class="text-sm sm:text-base font-extrabold tracking-wide text-[#004A99]">HÒA PHÁT</span>
          <span class="text-[10px] text-slate-500 mt-0.5">Thép xây dựng</span>
        </div>
        <div class="rounded-xl border border-slate-200 bg-slate-50/70 hover:bg-white hover:border-[var(--brand-primary)] hover:shadow-md transition p-4 flex flex-col items-center justify-center text-center min-h-[82px]">
          <span class="text-sm sm:text-base font-extrabold tracking-wide text-[#B91C1C]">SÔNG GIANH</span>
          <span class="text-[10px] text-slate-500 mt-0.5">Xi măng công trình</span>
        </div>
        <div class="rounded-xl border border-slate-200 bg-slate-50/70 hover:bg-white hover:border-[var(--brand-primary)] hover:shadow-md transition p-4 flex flex-col items-center justify-center text-center min-h-[82px]">
          <span class="text-sm sm:text-base font-extrabold tracking-wide text-[#0F5132]">CADIVI</span>
          <span class="text-[10px] text-slate-500 mt-0.5">Dây &amp; Cáp điện</span>
        </div>
        <div class="rounded-xl border border-slate-200 bg-slate-50/70 hover:bg-white hover:border-[var(--brand-primary)] hover:shadow-md transition p-4 flex flex-col items-center justify-center text-center min-h-[82px]">
          <span class="text-sm sm:text-base font-extrabold tracking-wide text-[#1D4ED8]">DULUX</span>
          <span class="text-[10px] text-slate-500 mt-0.5">Sơn trang trí</span>
        </div>
        <div class="rounded-xl border border-slate-200 bg-slate-50/70 hover:bg-white hover:border-[var(--brand-primary)] hover:shadow-md transition p-4 flex flex-col items-center justify-center text-center min-h-[82px]">
          <span class="text-sm sm:text-base font-extrabold tracking-wide text-[#0369A1]">NHỰA BÌNH MINH</span>
          <span class="text-[10px] text-slate-500 mt-0.5">Cấp thoát nước</span>
        </div>
        <div class="rounded-xl border border-slate-200 bg-slate-50/70 hover:bg-white hover:border-[var(--brand-primary)] hover:shadow-md transition p-4 flex flex-col items-center justify-center text-center min-h-[82px]">
          <span class="text-sm sm:text-base font-extrabold tracking-wide text-[#1E3A8A]">JOTUN</span>
          <span class="text-[10px] text-slate-500 mt-0.5">Sơn nội ngoại thất</span>
        </div>
        <div class="rounded-xl border border-slate-200 bg-slate-50/70 hover:bg-white hover:border-[var(--brand-primary)] hover:shadow-md transition p-4 flex flex-col items-center justify-center text-center min-h-[82px]">
          <span class="text-sm sm:text-base font-extrabold tracking-wide text-[#334155]">XINGFA</span>
          <span class="text-[10px] text-slate-500 mt-0.5">Nhôm kính cao cấp</span>
        </div>
        <div class="rounded-xl border border-slate-200 bg-slate-50/70 hover:bg-white hover:border-[var(--brand-primary)] hover:shadow-md transition p-4 flex flex-col items-center justify-center text-center min-h-[82px]">
          <span class="text-sm sm:text-base font-extrabold tracking-wide text-[#0B3D6B]">VĨNH TƯỜNG</span>
          <span class="text-[10px] text-slate-500 mt-0.5">Trần &amp; Vách thạch cao</span>
        </div>
        <div class="rounded-xl border border-slate-200 bg-slate-50/70 hover:bg-white hover:border-[var(--brand-primary)] hover:shadow-md transition p-4 flex flex-col items-center justify-center text-center min-h-[82px]">
          <span class="text-sm sm:text-base font-extrabold tracking-wide text-[#0F172A]">TOTO</span>
          <span class="text-[10px] text-slate-500 mt-0.5">Thiết bị vệ sinh</span>
        </div>
        <div class="rounded-xl border border-slate-200 bg-slate-50/70 hover:bg-white hover:border-[var(--brand-primary)] hover:shadow-md transition p-4 flex flex-col items-center justify-center text-center min-h-[82px]">
          <span class="text-sm sm:text-base font-extrabold tracking-wide text-[#005BAC]">PANASONIC</span>
          <span class="text-[10px] text-slate-500 mt-0.5">Thiết bị điện dân dụng</span>
        </div>
        <div class="rounded-xl border border-slate-200 bg-slate-50/70 hover:bg-white hover:border-[var(--brand-primary)] hover:shadow-md transition p-4 flex flex-col items-center justify-center text-center min-h-[82px]">
          <span class="text-sm sm:text-base font-extrabold tracking-wide text-[#9A3412]">AN CƯỜNG</span>
          <span class="text-[10px] text-slate-500 mt-0.5">Vật liệu gỗ nội thất</span>
        </div>
        <div class="rounded-xl border border-slate-200 bg-slate-50/70 hover:bg-white hover:border-[var(--brand-primary)] hover:shadow-md transition p-4 flex flex-col items-center justify-center text-center min-h-[82px]">
          <span class="text-sm sm:text-base font-extrabold tracking-wide text-[#B45309]">VIETCERAMICS</span>
          <span class="text-[10px] text-slate-500 mt-0.5">Gạch ốp lát cao cấp</span>
        </div>
      </div>
    </div>
  </section>

  <!-- =================================================================
       SECTION 9: FORM YÊU CẦU TƯ VẤN & BÁO GIÁ TRANG CHỦ (THEO WEB MẪU)
       ================================================================= -->
  <section id="bao-gia" class="py-10 sm:py-12 lg:py-14 bg-gradient-to-br from-[#072848] via-[#0B3D6B] to-[#114B82] text-white">
    <div class="flatsome-container">
      <div class="grid grid-cols-1 lg:grid-cols-12 gap-7 lg:gap-10 items-center">
        <!-- Cột thông tin cam kết báo giá -->
        <div class="lg:col-span-5 space-y-4">
          <div class="text-xs font-bold uppercase tracking-widest text-[#F5C156]">
            Miễn phí tư vấn &amp; dự toán
          </div>
          <h2 class="text-xl sm:text-2xl lg:text-3xl font-extrabold leading-snug text-white">
            ĐĂNG KÝ YÊU CẦU TƯ VẤN &amp; BÁO GIÁ XÂY DỰNG
          </h2>
          <p class="text-xs sm:text-sm text-slate-200 leading-relaxed">
            Để lại thông tin công trình dự kiến của bạn, đội ngũ kiến trúc sư và kỹ sư Minh Ân CDC sẽ liên hệ khảo sát và gửi bảng báo giá chi tiết từng hạng mục trong thời gian sớm nhất.
          </p>
          <ul class="space-y-2.5 text-xs sm:text-sm text-slate-100 list-none p-0 m-0">
            <li class="flex items-start gap-2.5">
              <i class="fa-solid fa-circle-check text-[#F5C156] mt-0.5"></i>
              <span>Báo giá thiết kế kiến trúc – nội thất tối ưu công năng</span>
            </li>
            <li class="flex items-start gap-2.5">
              <i class="fa-solid fa-circle-check text-[#F5C156] mt-0.5"></i>
              <span>Báo giá thi công phần thô &amp; nhân công hoàn thiện minh bạch</span>
            </li>
            <li class="flex items-start gap-2.5">
              <i class="fa-solid fa-circle-check text-[#F5C156] mt-0.5"></i>
              <span>Báo giá xây nhà trọn gói chìa khóa trao tay tại Đà Nẵng &amp; Huế</span>
            </li>
          </ul>
          <div class="pt-2 flex flex-wrap gap-3">
            <a href="tel:0941394848" class="inline-flex items-center gap-2 px-4 py-2.5 rounded-lg bg-white/10 hover:bg-white/20 border border-white/25 text-xs sm:text-sm font-bold text-white transition">
              <i class="fa-solid fa-phone-volume text-[#F5C156]"></i>
              <span>Hotline: 0941 394 848</span>
            </a>
            <a href="https://zalo.me/0941394848" target="_blank" rel="noopener noreferrer" class="inline-flex items-center gap-2 px-4 py-2.5 rounded-lg bg-[#0068FF] hover:bg-[#0056D6] text-xs sm:text-sm font-bold text-white transition">
              <i class="fa-solid fa-comment-dots"></i>
              <span>Nhắn Zalo ngay</span>
            </a>
          </div>
        </div>

        <!-- Cột Form nhập liệu -->
        <div class="lg:col-span-7">
          <form id="quote-form" class="bg-white text-slate-800 rounded-2xl p-5 sm:p-7 shadow-2xl border border-white/20 space-y-4">
            <div class="border-b border-slate-100 pb-3">
              <h3 class="text-base sm:text-lg font-extrabold text-[var(--brand-primary)]">
                NHẬP THÔNG TIN NHẬN BÁO GIÁ
              </h3>
              <p class="text-xs text-slate-500 mt-0.5">Thông tin của Quý khách được bảo mật tuyệt đối</p>
            </div>

            <div class="grid grid-cols-1 sm:grid-cols-2 gap-3.5">
              <div>
                <label for="q-name" class="block text-xs font-semibold text-slate-700 mb-1">Họ và tên <span class="text-red-500">*</span></label>
                <input id="q-name" type="text" required placeholder="Nhập họ tên của bạn"
                       class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-sm focus:outline-none focus:border-[var(--brand-primary)] focus:ring-2 focus:ring-[var(--brand-primary)]/15">
              </div>
              <div>
                <label for="q-phone" class="block text-xs font-semibold text-slate-700 mb-1">Số điện thoại / Zalo <span class="text-red-500">*</span></label>
                <input id="q-phone" type="tel" required placeholder="Ví dụ: 0941 394 848"
                       class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-sm focus:outline-none focus:border-[var(--brand-primary)] focus:ring-2 focus:ring-[var(--brand-primary)]/15">
              </div>
              <div>
                <label for="q-email" class="block text-xs font-semibold text-slate-700 mb-1">Email</label>
                <input id="q-email" type="email" placeholder="email@domain.com (không bắt buộc)"
                       class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-sm focus:outline-none focus:border-[var(--brand-primary)] focus:ring-2 focus:ring-[var(--brand-primary)]/15">
              </div>
              <div>
                <label for="q-type" class="block text-xs font-semibold text-slate-700 mb-1">Loại công trình / Dịch vụ</label>
                <select id="q-type"
                        class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-sm bg-white focus:outline-none focus:border-[var(--brand-primary)] focus:ring-2 focus:ring-[var(--brand-primary)]/15">
                  <option value="Nhà phố">Nhà phố</option>
                  <option value="Biệt thự">Biệt thự</option>
                  <option value="Khách sạn - Căn hộ cho thuê - Phòng trọ">Khách sạn – Căn hộ cho thuê – Phòng trọ</option>
                  <option value="Văn phòng">Văn phòng</option>
                  <option value="Thiết kế Kiến trúc - Nội thất">Thiết kế Kiến trúc – Nội thất</option>
                  <option value="Thi công phần thô">Thi công phần thô</option>
                  <option value="Thi công hoàn thiện">Thi công hoàn thiện</option>
                  <option value="Thi công trọn gói">Thi công trọn gói</option>
                  <option value="Cải tạo sửa chữa">Cải tạo sửa chữa</option>
                </select>
              </div>
              <div>
                <label for="q-budget" class="block text-xs font-semibold text-slate-700 mb-1">Mức đầu tư dự kiến</label>
                <select id="q-budget"
                        class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-sm bg-white focus:outline-none focus:border-[var(--brand-primary)] focus:ring-2 focus:ring-[var(--brand-primary)]/15">
                  <option value="Chưa xác định">Chưa xác định</option>
                  <option value="Dưới 500 triệu">Dưới 500 triệu</option>
                  <option value="500 triệu - 1 tỷ">500 triệu – 1 tỷ</option>
                  <option value="1 tỷ - 2 tỷ">1 tỷ – 2 tỷ</option>
                  <option value="2 tỷ - 3 tỷ">2 tỷ – 3 tỷ</option>
                  <option value="Trên 3 tỷ">Trên 3 tỷ</option>
                </select>
              </div>
              <div>
                <label for="q-location" class="block text-xs font-semibold text-slate-700 mb-1">Khu vực xây dựng</label>
                <input id="q-location" type="text" placeholder="Ví dụ: Hải Châu - Đà Nẵng / Huế"
                       class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-sm focus:outline-none focus:border-[var(--brand-primary)] focus:ring-2 focus:ring-[var(--brand-primary)]/15">
              </div>
            </div>

            <div>
              <label for="q-note" class="block text-xs font-semibold text-slate-700 mb-1">Mô tả quy mô / yêu cầu chi tiết</label>
              <textarea id="q-note" rows="3" placeholder="Diện tích đất, số tầng dự kiến, thời gian khởi công..."
                        class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-sm focus:outline-none focus:border-[var(--brand-primary)] focus:ring-2 focus:ring-[var(--brand-primary)]/15"></textarea>
            </div>

            <button type="submit"
                    class="w-full py-3 px-6 rounded-lg bg-[var(--brand-accent)] hover:bg-[var(--brand-accent-hover)] text-white font-bold text-sm uppercase tracking-wide shadow-md transition flex items-center justify-center gap-2">
              <i class="fa-solid fa-paper-plane"></i>
              <span>Gửi yêu cầu tư vấn &amp; báo giá</span>
            </button>
          </form>
        </div>
      </div>
    </div>
  </section>

  <!-- =================================================================
       SECTION 10: DANH MỤC CÁC BÀI VIẾT / TIN TỨC TRANG CHỦ
       ================================================================= -->
  <section id="tin-tuc" class="py-10 sm:py-12 lg:py-14 bg-white">
    <div class="flatsome-container">
      <div class="text-center mb-6 sm:mb-8">
        <h2 class="flatsome-section-title text-lg sm:text-2xl lg:text-[26px] font-extrabold uppercase text-[var(--brand-primary)]">
          Tin tức &amp; Kiến thức xây dựng
        </h2>
        <p class="mt-3 text-xs sm:text-sm text-slate-600 max-w-2xl mx-auto">
          Chia sẻ kinh nghiệm thiết kế, kỹ thuật thi công và cẩm nang xây nhà hữu ích từ đội ngũ kỹ sư Minh Ân CDC
        </p>
      </div>

      <div id="articles-grid" class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-4 sm:gap-5">
        <!-- Render danh sách bài viết trang chủ bằng JS (nhấn vào đọc chi tiết) -->
      </div>
    </div>
  </section>

  <!-- =================================================================
       SECTION 11: KẾT NỐI FACEBOOK & BẢN ĐỒ GOOGLE MAPS TRANG CHỦ
       Hiển thị trực tiếp Facebook https://www.facebook.com/jacky.huynh.311
       và Google Maps trụ sở Đà Nẵng & Chi nhánh Huế
       ================================================================= -->
  <section id="lien-he" class="py-10 sm:py-12 lg:py-14 bg-slate-50 border-t border-slate-200">
    <div class="flatsome-container">
      <div class="text-center mb-6 sm:mb-8">
        <h2 class="flatsome-section-title text-lg sm:text-2xl lg:text-[26px] font-extrabold uppercase text-[var(--brand-primary)]">
          Kết nối Facebook &amp; Bản đồ chỉ đường
        </h2>
        <p class="mt-3 text-xs sm:text-sm text-slate-600 max-w-2xl mx-auto">
          Ghé thăm văn phòng Minh Ân CDC tại Đà Nẵng &amp; Huế hoặc kết nối trực tiếp qua Facebook và Zalo
        </p>
      </div>

      <div class="grid grid-cols-1 lg:grid-cols-12 gap-5 lg:gap-6 items-stretch">
        <!-- Khối Facebook trực tiếp ngoài trang chủ -->
        <div class="lg:col-span-4 bg-white rounded-2xl border border-slate-200 shadow-sm overflow-hidden flex flex-col">
          <div class="bg-[#1877F2] px-5 py-4 text-white flex items-center justify-between">
            <div class="flex items-center gap-2.5">
              <i class="fa-brands fa-facebook text-2xl"></i>
              <div>
                <div class="text-sm font-bold leading-tight">Kết nối Facebook</div>
                <div class="text-[11px] text-blue-100">Cập nhật công trình mới nhất</div>
              </div>
            </div>
            <i class="fa-solid fa-arrow-up-right-from-square text-xs opacity-80"></i>
          </div>

          <div class="p-5 flex-1 flex flex-col justify-between space-y-4">
            <div class="space-y-4">
              <div class="flex items-center gap-3.5 pb-4 border-b border-slate-100">
                <img
                  data-drive-id="1mB37EKXpyrvpswPrIUaMt2Wrn1lH-Gvu"
                  src="https://lh3.googleusercontent.com/d/1mB37EKXpyrvpswPrIUaMt2Wrn1lH-Gvu=w300"
                  alt="Minh Ân CDC Facebook"
                  class="w-14 h-14 rounded-full object-contain border-2 border-[#1877F2]/30 p-1 bg-white shrink-0"
                  onerror="handleDriveImageError(this)"
                >
                <div class="min-w-0">
                  <div class="text-sm font-extrabold text-slate-800 break-words">Minh Ân CDC – Thiết kế &amp; Xây dựng</div>
                  <div class="text-xs text-slate-500 mt-0.5 break-all">facebook.com/jacky.huynh.311</div>
                </div>
              </div>

              <div class="space-y-2.5 text-xs sm:text-[13px] text-slate-600">
                <p class="leading-relaxed">
                  Theo dõi Facebook chính thức của đại diện <strong>Minh Ân CDC</strong> để xem nhật ký thi công thực tế hàng ngày, các mẫu thiết kế nhà phố, biệt thự mới và nhận tư vấn trực tuyến nhanh nhất.
                </p>
                <div class="grid grid-cols-3 gap-2 pt-1">
                  <img data-drive-id="1UB12E_spzIvo7TNREjBJXUV9o_HVWOv_" src="https://lh3.googleusercontent.com/d/1UB12E_spzIvo7TNREjBJXUV9o_HVWOv_=w400" alt="Ảnh công trình Facebook 1" class="w-full aspect-square object-cover rounded-lg border border-slate-200" onerror="handleDriveImageError(this)">
                  <img data-drive-id="1wHGqk7znpnGmrOjz4_EdpHnHK8xKyxkT" src="https://lh3.googleusercontent.com/d/1wHGqk7znpnGmrOjz4_EdpHnHK8xKyxkT=w400" alt="Ảnh công trình Facebook 2" class="w-full aspect-square object-cover rounded-lg border border-slate-200" onerror="handleDriveImageError(this)">
                  <img data-drive-id="1-eBgG9wF3I6_gyPir2CmCnwJg4sP7Bnn" src="https://lh3.googleusercontent.com/d/1-eBgG9wF3I6_gyPir2CmCnwJg4sP7Bnn=w400" alt="Ảnh công trình Facebook 3" class="w-full aspect-square object-cover rounded-lg border border-slate-200" onerror="handleDriveImageError(this)">
                </div>
              </div>
            </div>

            <div class="space-y-2.5 pt-2">
              <a href="https://www.facebook.com/jacky.huynh.311" target="_blank" rel="noopener noreferrer"
                 class="w-full py-2.5 px-4 rounded-lg bg-[#1877F2] hover:bg-[#1465D1] text-white font-bold text-xs sm:text-sm transition flex items-center justify-center gap-2 shadow-sm">
                <i class="fa-brands fa-facebook-f"></i>
                <span>Truy cập Facebook Minh Ân CDC</span>
              </a>
              <div class="text-xs text-slate-600 bg-slate-50 rounded-lg p-3 border border-slate-200/80 space-y-1">
                <div><strong class="text-[var(--brand-primary)]">Trụ sở:</strong> 35 Phan Thành Tài, P. Hải Châu, TP. Đà Nẵng</div>
                <div><strong class="text-[var(--brand-primary)]">Chi nhánh:</strong> 16/154 Bà Triệu, P. Thuận Hoá, TP. Huế</div>
                <div><strong class="text-[var(--brand-primary)]">Hotline / Zalo:</strong> <a href="tel:0941394848" class="font-bold text-[var(--brand-accent)]">0941 394 848</a></div>
              </div>
            </div>
          </div>
        </div>

        <!-- Khối Bản đồ Google Maps trực tiếp ngoài trang chủ (Trụ sở Đà Nẵng & Chi nhánh Huế) -->
        <div class="lg:col-span-8 bg-white rounded-2xl border border-slate-200 shadow-sm overflow-hidden flex flex-col">
          <div class="px-4 sm:px-5 py-3.5 bg-[var(--brand-light)] border-b border-slate-200 flex flex-wrap items-center justify-between gap-2">
            <div class="flex items-center gap-2 text-sm font-bold text-[var(--brand-primary)]">
              <i class="fa-solid fa-map-location-dot text-[var(--brand-accent)]"></i>
              <span>Bản đồ Google Maps – Minh Ân CDC</span>
            </div>
            <div class="flex items-center gap-1.5">
              <button type="button" id="map-btn-dn" onclick="switchMap('dn')"
                      class="px-3 py-1.5 rounded-lg text-xs font-semibold bg-[var(--brand-primary)] text-white transition whitespace-nowrap">
                Trụ sở Đà Nẵng
              </button>
              <button type="button" id="map-btn-hue" onclick="switchMap('hue')"
                      class="px-3 py-1.5 rounded-lg text-xs font-semibold bg-white text-slate-700 border border-slate-300 hover:border-[var(--brand-primary)] transition whitespace-nowrap">
                Chi nhánh Huế
              </button>
            </div>
          </div>

          <div class="relative flex-1 min-h-[320px] sm:min-h-[380px] bg-slate-100">
            <iframe
              id="google-map-iframe"
              title="Bản đồ Trụ sở Minh Ân CDC - 35 Phan Thành Tài, Hải Châu, Đà Nẵng"
              src="https://maps.google.com/maps?q=35+Phan+Th%C3%A0nh+T%C3%A0i,+H%E1%BA%A3i+Ch%C3%A2u,+%C4%90%C3%A0+N%E1%BA%B5ng&t=&z=16&ie=UTF8&iwloc=&output=embed"
              class="w-full h-full min-h-[320px] sm:min-h-[380px] border-0 block"
              loading="lazy"
              referrerpolicy="no-referrer-when-downgrade"
              allowfullscreen>
            </iframe>
          </div>

          <div class="px-4 sm:px-5 py-3 bg-white border-t border-slate-200 flex flex-wrap items-center justify-between gap-2 text-xs text-slate-600">
            <span id="map-address-label" class="font-medium">
              <i class="fa-solid fa-location-dot text-[var(--brand-accent)] mr-1"></i>
              Trụ sở: 35 Phan Thành Tài, P. Hải Châu, TP. Đà Nẵng
            </span>
            <a id="map-external-link"
               href="https://www.google.com/maps/search/?api=1&query=35+Phan+Th%C3%A0nh+T%C3%A0i,+H%E1%BA%A3i+Ch%C3%A2u,+%C4%90%C3%A0+N%E1%BA%B5ng"
               target="_blank" rel="noopener noreferrer"
               class="font-semibold text-[var(--brand-primary)] hover:text-[var(--brand-accent)] inline-flex items-center gap-1 whitespace-nowrap">
              <span>Mở trên Google Maps</span>
              <i class="fa-solid fa-arrow-up-right-from-square text-[10px]"></i>
            </a>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- =================================================================
       SECTION 12: FOOTER CHUẨN FLATSOME
       ================================================================= -->
  <footer class="bg-[var(--brand-dark)] text-slate-200 pt-10 sm:pt-12 pb-6">
    <div class="flatsome-container">
      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-12 gap-7 pb-8 border-b border-white/15">
        <!-- Cột 1: Thông tin doanh nghiệp -->
        <div class="lg:col-span-5 space-y-3.5">
          <div class="flex items-center gap-3">
            <div class="bg-white rounded-lg p-1.5 shrink-0">
              <img
                data-drive-id="1mB37EKXpyrvpswPrIUaMt2Wrn1lH-Gvu"
                src="https://lh3.googleusercontent.com/d/1mB37EKXpyrvpswPrIUaMt2Wrn1lH-Gvu=w300"
                alt="Logo Minh Ân CDC"
                class="h-9 w-auto object-contain"
                onerror="handleDriveImageError(this)"
              >
            </div>
            <div>
              <div class="text-sm sm:text-base font-extrabold text-white leading-snug">
                CÔNG TY TNHH MTV TƯ VẤN THIẾT KẾ XÂY DỰNG VÀ THƯƠNG MẠI MINH ÂN CDC
              </div>
            </div>
          </div>
          <ul class="space-y-2 text-xs sm:text-[13px] text-slate-300 list-none p-0 m-0">
            <li class="flex items-start gap-2">
              <i class="fa-solid fa-location-dot text-[var(--brand-accent)] mt-1"></i>
              <span><strong>Trụ sở:</strong> 35 Phan Thành Tài, P. Hải Châu, TP. Đà Nẵng</span>
            </li>
            <li class="flex items-start gap-2">
              <i class="fa-solid fa-building text-[var(--brand-accent)] mt-1"></i>
              <span><strong>Chi nhánh:</strong> 16/154 Bà Triệu, P. Thuận Hoá, TP. Huế</span>
            </li>
            <li class="flex items-start gap-2">
              <i class="fa-solid fa-phone text-[var(--brand-accent)] mt-1"></i>
              <span><strong>Hotline / Zalo:</strong> <a href="tel:0941394848" class="text-white font-bold hover:text-[var(--brand-accent)]">0941 394 848</a></span>
            </li>
            <li class="flex items-start gap-2">
              <i class="fa-solid fa-globe text-[var(--brand-accent)] mt-1"></i>
              <span><strong>Website:</strong> minhancdc.com</span>
            </li>
            <li class="flex items-start gap-2">
              <i class="fa-solid fa-file-contract text-[var(--brand-accent)] mt-1"></i>
              <span><strong>Mã số thuế:</strong> 3301711595</span>
            </li>
          </ul>
        </div>

        <!-- Cột 2: Lĩnh vực hoạt động -->
        <div class="lg:col-span-3 space-y-3">
          <h3 class="text-sm font-bold uppercase tracking-wider text-white border-b border-[var(--brand-accent)]/60 pb-2 inline-block">
            Lĩnh vực hoạt động
          </h3>
          <ul class="space-y-2 text-xs sm:text-[13px] text-slate-300 list-none p-0 m-0">
            <li><a href="#linh-vuc-hoat-dong" class="hover:text-[var(--brand-accent)] transition">Thiết kế Kiến trúc – Nội thất</a></li>
            <li><a href="#linh-vuc-hoat-dong" class="hover:text-[var(--brand-accent)] transition">Thi công phần thô</a></li>
            <li><a href="#linh-vuc-hoat-dong" class="hover:text-[var(--brand-accent)] transition">Thi công hoàn thiện</a></li>
            <li><a href="#linh-vuc-hoat-dong" class="hover:text-[var(--brand-accent)] transition">Thi công nội thất trọn gói</a></li>
            <li><a href="#bao-gia" class="hover:text-[var(--brand-accent)] transition">Báo giá xây dựng Đà Nẵng – Huế</a></li>
          </ul>
        </div>

        <!-- Cột 3: Danh mục công trình -->
        <div class="lg:col-span-4 space-y-3">
          <h3 class="text-sm font-bold uppercase tracking-wider text-white border-b border-[var(--brand-accent)]/60 pb-2 inline-block">
            Danh mục công trình
          </h3>
          <div class="grid grid-cols-2 gap-2 text-xs sm:text-[13px] text-slate-300">
            <a href="#cong-trinh-thuc-te" onclick="selectCategoryFromNav('khach-san-can-ho')" class="hover:text-[var(--brand-accent)] transition">Khách sạn – Căn hộ</a>
            <a href="#cong-trinh-thuc-te" onclick="selectCategoryFromNav('biet-thu')" class="hover:text-[var(--brand-accent)] transition">Biệt thự hiện đại</a>
            <a href="#cong-trinh-thuc-te" onclick="selectCategoryFromNav('nha-pho')" class="hover:text-[var(--brand-accent)] transition">Nhà phố trọn gói</a>
            <a href="#cong-trinh-thuc-te" onclick="selectCategoryFromNav('van-phong')" class="hover:text-[var(--brand-accent)] transition">Văn phòng công ty</a>
            <a href="#du-an-da-nang" class="hover:text-[var(--brand-accent)] transition">Dự án tại Đà Nẵng</a>
            <a href="#tin-tuc" class="hover:text-[var(--brand-accent)] transition">Tin tức xây dựng</a>
          </div>

          <div class="pt-2 flex items-center gap-2.5">
            <a href="https://www.facebook.com/jacky.huynh.311" target="_blank" rel="noopener noreferrer"
               class="inline-flex items-center gap-1.5 px-3 py-1.5 rounded-lg bg-[#1877F2] hover:bg-[#1465D1] text-white text-xs font-semibold transition">
              <i class="fa-brands fa-facebook-f"></i>
              <span>Facebook</span>
            </a>
            <a href="https://zalo.me/0941394848" target="_blank" rel="noopener noreferrer"
               class="inline-flex items-center gap-1.5 px-3 py-1.5 rounded-lg bg-[#0068FF] hover:bg-[#0056D6] text-white text-xs font-semibold transition">
              <i class="fa-solid fa-comment-dots"></i>
              <span>Zalo</span>
            </a>
            <a href="tel:0941394848"
               class="inline-flex items-center gap-1.5 px-3 py-1.5 rounded-lg bg-[var(--brand-accent)] hover:bg-[var(--brand-accent-hover)] text-white text-xs font-semibold transition">
              <i class="fa-solid fa-phone"></i>
              <span>Gọi ngay</span>
            </a>
          </div>
        </div>
      </div>

      <div class="pt-5 flex flex-col sm:flex-row items-center justify-between gap-2 text-xs text-slate-400 text-center sm:text-left">
        <div>Copyright 2026 &copy; <strong>minhancdc.com</strong> – CÔNG TY TNHH MTV TƯ VẤN THIẾT KẾ XÂY DỰNG VÀ THƯƠNG MẠI MINH ÂN CDC.</div>
        <div>Thiết kế chuẩn giao diện Flatsome UX Builder</div>
      </div>
    </div>
  </footer>

  <!-- =================================================================
       CÁC NÚT LIÊN HỆ NỔI BẬT: ZALO, FACEBOOK, HOTLINE
       Tương thích hoàn hảo trên cả máy tính và điện thoại, không che nội dung
       ================================================================= -->
  <div class="fixed right-3 sm:right-4 bottom-4 sm:bottom-5 z-50 flex flex-col items-end gap-2.5">
    <!-- Zalo -->
    <a href="https://zalo.me/0941394848" target="_blank" rel="noopener noreferrer"
       class="group flex items-center gap-2 bg-[#0068FF] hover:bg-[#0055D4] text-white rounded-full shadow-lg p-2.5 sm:px-4 sm:py-2.5 transition"
       aria-label="Liên hệ Zalo 0941 394 848">
      <span class="w-6 h-6 rounded-full bg-white text-[#0068FF] font-extrabold text-[10px] flex items-center justify-center shrink-0">Zalo</span>
      <span class="hidden sm:inline text-xs font-bold whitespace-nowrap">Chat Zalo</span>
    </a>

    <!-- Facebook -->
    <a href="https://www.facebook.com/jacky.huynh.311" target="_blank" rel="noopener noreferrer"
       class="group flex items-center gap-2 bg-[#1877F2] hover:bg-[#1363CC] text-white rounded-full shadow-lg p-2.5 sm:px-4 sm:py-2.5 transition"
       aria-label="Liên hệ Facebook Minh Ân CDC">
      <span class="w-6 h-6 rounded-full bg-white text-[#1877F2] flex items-center justify-center shrink-0">
        <i class="fa-brands fa-facebook-f text-xs"></i>
      </span>
      <span class="hidden sm:inline text-xs font-bold whitespace-nowrap">Facebook</span>
    </a>

    <!-- Hotline -->
    <a href="tel:0941394848"
       class="hotline-pulse flex items-center gap-2 bg-[var(--brand-accent)] hover:bg-[var(--brand-accent-hover)] text-white rounded-full shadow-xl p-2.5 sm:px-4 sm:py-2.5 transition"
       aria-label="Gọi Hotline 0941 394 848">
      <span class="w-6 h-6 rounded-full bg-white text-[var(--brand-accent)] flex items-center justify-center shrink-0">
        <i class="fa-solid fa-phone-volume text-xs"></i>
      </span>
      <span class="hidden sm:inline text-xs font-extrabold whitespace-nowrap">0941 394 848</span>
    </a>

    <!-- Lên đầu trang -->
    <button id="scroll-top-btn" type="button" onclick="window.scrollTo({top: 0, behavior: 'smooth'})"
            class="hidden w-10 h-10 rounded-full bg-[var(--brand-primary)] hover:bg-[var(--brand-dark)] text-white shadow-lg items-center justify-center transition"
            aria-label="Lên đầu trang">
      <i class="fa-solid fa-arrow-up text-xs"></i>
    </button>
  </div>

  <!-- =================================================================
       MODAL XEM CHI TIẾT ẢNH CÔNG TRÌNH / DỰ ÁN & BÀI VIẾT
       ================================================================= -->
  <div id="detail-modal" class="fixed inset-0 z-[90] bg-slate-900/75 hidden items-center justify-center p-3 sm:p-5">
    <div class="bg-white rounded-2xl max-w-3xl w-full max-h-[90vh] overflow-y-auto shadow-2xl border border-slate-200">
      <div class="sticky top-0 bg-white px-4 sm:px-6 py-3.5 border-b border-slate-200 flex items-center justify-between gap-3 z-10">
        <h3 id="modal-title" class="text-sm sm:text-base font-extrabold text-[var(--brand-primary)] break-words"></h3>
        <button type="button" onclick="closeDetailModal()" class="w-8 h-8 rounded-full bg-slate-100 hover:bg-slate-200 text-slate-600 flex items-center justify-center shrink-0" aria-label="Đóng hộp thoại">
          <i class="fa-solid fa-xmark"></i>
        </button>
      </div>
      <div class="p-4 sm:p-6 space-y-4">
        <div id="modal-image-wrap" class="rounded-xl overflow-hidden bg-slate-100 border border-slate-200">
          <img id="modal-image" src="" alt="" class="w-full max-h-[460px] object-contain mx-auto bg-slate-900/5" onerror="handleDriveImageError(this)">
        </div>
        <div id="modal-meta" class="text-xs font-semibold text-[var(--brand-accent)]"></div>
        <div id="modal-desc" class="text-xs sm:text-sm text-slate-700 leading-relaxed space-y-2.5"></div>
        <div class="pt-2 flex flex-wrap items-center gap-2.5 border-t border-slate-100">
          <a href="#bao-gia" onclick="closeDetailModal()" class="px-4 py-2 rounded-lg bg-[var(--brand-primary)] hover:bg-[var(--brand-dark)] text-white text-xs sm:text-sm font-bold transition">
            Yêu cầu báo giá công trình tương tự
          </a>
          <a href="tel:0941394848" class="px-4 py-2 rounded-lg bg-[var(--brand-accent)] hover:bg-[var(--brand-accent-hover)] text-white text-xs sm:text-sm font-bold transition">
            Gọi tư vấn: 0941 394 848
          </a>
        </div>
      </div>
    </div>
  </div>

  <!-- Thông báo Toast (thay thế hoàn toàn alert()) -->
  <div id="toast-box" class="fixed top-20 left-1/2 -translate-x-1/2 z-[100] hidden max-w-[92vw] sm:max-w-md w-full">
    <div class="bg-white border-l-4 border-emerald-600 rounded-xl shadow-2xl p-4 flex items-start gap-3">
      <div class="w-8 h-8 rounded-full bg-emerald-100 text-emerald-700 flex items-center justify-center shrink-0">
        <i class="fa-solid fa-check"></i>
      </div>
      <div class="flex-1 min-w-0">
        <div id="toast-title" class="text-sm font-bold text-slate-800"></div>
        <div id="toast-msg" class="text-xs text-slate-600 mt-0.5 leading-relaxed"></div>
      </div>
      <button type="button" onclick="hideToast()" class="text-slate-400 hover:text-slate-600 p-1" aria-label="Đóng thông báo">
        <i class="fa-solid fa-xmark"></i>
      </button>
    </div>
  </div>

  <!-- =================================================================
       JAVASCRIPT ĐIỀU KHIỂN TOÀN BỘ WEBSITE
       ================================================================= -->
  <script>
    /* -----------------------------------------------------------------
       1. HỆ THỐNG TẢI ẢNH GOOGLE DRIVE ĐA TẦNG (TỰ ĐỘNG DỰ PHÒNG AN TOÀN)
       ----------------------------------------------------------------- */
    function handleDriveImageError(img) {
      try {
        const fileId = img.getAttribute('data-drive-id');
        const step = parseInt(img.getAttribute('data-fallback-step') || '0', 10);

        if (fileId && step === 0) {
          img.setAttribute('data-fallback-step', '1');
          img.src = 'https://drive.google.com/thumbnail?id=' + fileId + '&sz=w1000';
        } else if (fileId && step === 1) {
          img.setAttribute('data-fallback-step', '2');
          img.src = 'https://drive.google.com/uc?export=view&id=' + fileId;
        } else {
          img.onerror = null;
          img.src = 'https://placehold.co/800x600/0B3D6B/FFFFFF?text=MINH+AN+CDC';
        }
      } catch (e) {
        img.onerror = null;
      }
    }

    function driveUrl(id, size) {
      return 'https://lh3.googleusercontent.com/d/' + id + '=w' + (size || 800);
    }

    /* -----------------------------------------------------------------
       2. DỮ LIỆU 9 ẢNH THỰC TẾ THI CÔNG XÂY DỰNG (PHÂN LOẠI THEO WEB MẪU)
       ----------------------------------------------------------------- */
    const constructionItems = [
      {
        id: '13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz',
        title: 'Thi công phần thô kết cấu bê tông cốt thép nhà phố',
        category: 'phan-tho-hoan-thien',
        categoryLabel: 'Phần thô & Hoàn thiện',
        location: 'Đà Nẵng – Miền Trung',
        desc: 'Hạng mục thi công phần thô kết cấu móng, dầm, sàn bê tông cốt thép chuẩn kỹ thuật, kiểm tra nghiêm ngặt độ sụt bê tông và thép chịu lực theo bản vẽ thiết kế.'
      },
      {
        id: '1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR',
        title: 'Thi công trọn gói nhà phố hiện đại 3 tầng',
        category: 'nha-pho',
        categoryLabel: 'Nhà phố',
        location: 'Quận Hải Châu, TP. Đà Nẵng',
        desc: 'Công trình nhà phố hiện đại được Minh Ân CDC tư vấn thiết kế và thi công trọn gói từ phần móng đến hoàn thiện mặt tiền sang trọng, tối ưu thông thoáng.'
      },
      {
        id: '1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv',
        title: 'Thi công hoàn thiện biệt thự phố 2 mặt tiền',
        category: 'biet-thu',
        categoryLabel: 'Biệt thự',
        location: 'Khu đô thị Hòa Xuân, Đà Nẵng',
        desc: 'Thi công xây dựng và hoàn thiện ngoại thất biệt thự phố 2 mặt tiền với hệ cửa nhôm kính cao cấp, vật liệu ốp lát chọn lọc và tỷ lệ kiến trúc tinh tế.'
      },
      {
        id: '1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_',
        title: 'Thiết kế & thi công căn hộ dịch vụ cho thuê',
        category: 'khach-san-can-ho',
        categoryLabel: 'Khách sạn - Căn hộ',
        location: 'Quận Sơn Trà, TP. Đà Nẵng',
        desc: 'Công trình căn hộ dịch vụ cao tầng tối ưu số phòng khai thác, bố trí hệ thống phòng cháy chữa cháy, điện nước âm tường chuẩn quy định.'
      },
      {
        id: '1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO',
        title: 'Thi công lắp dựng cốp pha & cốt thép sàn tầng',
        category: 'phan-tho-hoan-thien',
        categoryLabel: 'Phần thô & Hoàn thiện',
        location: 'TP. Huế – Đà Nẵng',
        desc: 'Công tác gia công lắp dựng cốt thép dầm sàn, hệ giáo chống an toàn và nghiệm thu kỹ thuật trực tiếp trước khi đổ bê tông tươi.'
      },
      {
        id: '1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t',
        title: 'Thi công xây dựng khách sạn mini kết hợp căn hộ',
        category: 'khach-san-can-ho',
        categoryLabel: 'Khách sạn - Căn hộ',
        location: 'Ngũ Hành Sơn, TP. Đà Nẵng',
        desc: 'Tư vấn thiết kế và thi công khách sạn mini hiện đại gần biển, đảm bảo thẩm mỹ mặt đứng nổi bật và chất lượng chống thấm vượt trội.'
      },
      {
        id: '1UB12E_spzIvo7TNREjBJXUV9o_HVWOv_',
        title: 'Thi công hoàn thiện không gian văn phòng làm việc',
        category: 'van-phong',
        categoryLabel: 'Văn phòng',
        location: 'Trung tâm TP. Đà Nẵng',
        desc: 'Hạng mục cải tạo và thi công hoàn thiện văn phòng làm việc chuyên nghiệp, hệ trần thạch cao, chiếu sáng tiêu chuẩn và vách kính cách âm.'
      },
      {
        id: '1wHGqk7znpnGmrOjz4_EdpHnHK8xKyxkT',
        title: 'Thi công nhà phố kết hợp kinh doanh mặt tiền',
        category: 'nha-pho',
        categoryLabel: 'Nhà phố',
        location: 'P. Thuận Hoá, TP. Huế',
        desc: 'Giải pháp thiết kế và thi công nhà ở kết hợp kinh doanh tầng trệt thông thoáng, công năng sinh hoạt riêng tư cho gia đình ở các tầng trên.'
      },
      {
        id: '1-eBgG9wF3I6_gyPir2CmCnwJg4sP7Bnn',
        title: 'Thi công hoàn thiện nội ngoại thất biệt thự vườn',
        category: 'biet-thu',
        categoryLabel: 'Biệt thự',
        location: 'TP. Đà Nẵng',
        desc: 'Hoàn thiện ốp lát, sơn nước cao cấp, hệ thống M&E và cảnh quan sân vườn đồng bộ, bàn giao công trình sạch đẹp đúng cam kết.'
      }
    ];

    /* -----------------------------------------------------------------
       3. DỮ LIỆU 10 DỰ ÁN TIÊU BIỂU TẠI ĐÀ NẴNG (10 ẢNH DRIVE NGƯỜI DÙNG)
       ----------------------------------------------------------------- */
    const danangProjects = [
      {
        id: '157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT',
        title: 'Dự án Nhà phố hiện đại – Hải Châu, Đà Nẵng',
        location: 'Quận Hải Châu, TP. Đà Nẵng',
        desc: 'Thiết kế kiến trúc và thi công trọn gói nhà phố hiện đại tại trung tâm quận Hải Châu, TP. Đà Nẵng.'
      },
      {
        id: '1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff',
        title: 'Dự án Căn hộ dịch vụ – Sơn Trà, Đà Nẵng',
        location: 'Quận Sơn Trà, TP. Đà Nẵng',
        desc: 'Thi công xây dựng tòa nhà căn hộ dịch vụ cao cấp khu vực biển Sơn Trà với kết cấu kiên cố và mặt tiền sang trọng.'
      },
      {
        id: '1wkzckXZhRrWh3V2GIOfdqBmOwQTBVFhz',
        title: 'Dự án Biệt thự phố – Hòa Xuân, Đà Nẵng',
        location: 'Khu đô thị Hòa Xuân, Cẩm Lệ, Đà Nẵng',
        desc: 'Thiết kế & thi công biệt thự phố 3 tầng phong cách hiện đại, không gian mở kết nối thiên nhiên tại Hòa Xuân.'
      },
      {
        id: '1I7lc3ghS0tyqh6Pq3xsZTidKsr0oT-8k',
        title: 'Dự án Khách sạn nghỉ dưỡng – Ngũ Hành Sơn, Đà Nẵng',
        location: 'Quận Ngũ Hành Sơn, TP. Đà Nẵng',
        desc: 'Thi công phần thô và hoàn thiện công trình lưu trú khu vực Ngũ Hành Sơn đạt tiêu chuẩn thẩm mỹ và tiến độ.'
      },
      {
        id: '1Q8VoCbT7s09UNaoI8GNcYdvKpJ2wz78N',
        title: 'Dự án Nhà ở kết hợp văn phòng – Thanh Khê, Đà Nẵng',
        location: 'Quận Thanh Khê, TP. Đà Nẵng',
        desc: 'Công trình nhà phố kết hợp trụ sở văn phòng công ty tại quận Thanh Khê do Minh Ân CDC trực tiếp triển khai.'
      },
      {
        id: '1tkQlfZJTkaSunwOIMhfnzkEG2YHwxhML',
        title: 'Dự án Biệt thự 2 mặt tiền – Nam Việt Á, Đà Nẵng',
        location: 'Khu dân cư Nam Việt Á, Đà Nẵng',
        desc: 'Thiết kế và thi công hoàn thiện biệt thự 2 mặt tiền bề thế, tối ưu ánh sáng tự nhiên và vật liệu bền đẹp theo thời gian.'
      },
      {
        id: '1An7LyMVwj3rhKZlsVnYQ2UrLe48IeTBF',
        title: 'Dự án Nhà phố 3 tầng – Liên Chiểu, Đà Nẵng',
        location: 'Quận Liên Chiểu, TP. Đà Nẵng',
        desc: 'Thi công xây dựng trọn gói nhà phố gia đình tại quận Liên Chiểu, bàn giao chìa khóa trao tay đúng tiến độ.'
      },
      {
        id: '1R1Da04pAYI9-NJz1IsAfa7pVKkuK7J-A',
        title: 'Dự án Căn hộ cao cấp – An Thượng, Đà Nẵng',
        location: 'Khu phố Tây An Thượng, Đà Nẵng',
        desc: 'Công trình căn hộ cho thuê hiện đại phục vụ khách du lịch tại khu vực An Thượng, hoàn thiện tỉ mỉ từng chi tiết.'
      },
      {
        id: '1FdQEsiEBrIW5TiN22dvzV5g6amDPp-80',
        title: 'Dự án Nhà phố hiện đại – Phước Mỹ, Đà Nẵng',
        location: 'Phường Phước Mỹ, Sơn Trà, Đà Nẵng',
        desc: 'Tư vấn thiết kế và thi công nhà phố hiện đại gần biển Mỹ Khê, chú trọng chống thấm và giải pháp vật liệu chống ăn mòn muối biển.'
      },
      {
        id: '1So_3V4rw1y7lHegiIkYmh2Z9UIdozAL4',
        title: 'Dự án Văn phòng & Showroom – Cẩm Lệ, Đà Nẵng',
        location: 'Quận Cẩm Lệ, TP. Đà Nẵng',
        desc: 'Thi công xây dựng và hoàn thiện không gian văn phòng kết hợp khu trưng bày thương mại hiện đại tại Đà Nẵng.'
      }
    ];

    /* -----------------------------------------------------------------
       4. DỮ LIỆU BÀI VIẾT / TIN TỨC TRANG CHỦ
       ----------------------------------------------------------------- */
    const articlesData = [
      {
        driveId: '13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz',
        date: '15/11/2026',
        title: 'Hướng dẫn bảo dưỡng bê tông móng và sàn đúng kỹ thuật khi xây nhà',
        excerpt: 'Bảo dưỡng bê tông đúng quy trình trong 7 ngày đầu quyết định trực tiếp đến cường độ chịu lực và khả năng chống nứt của công trình.',
        content: [
          'Trong quá trình thi công phần thô, công tác đổ bê tông mới chỉ là bước khởi đầu. Giai đoạn bảo dưỡng ẩm liên tục giúp quá trình thủy hóa xi măng diễn ra hoàn toàn, tránh hiện tượng co ngót gây rạn nứt bề mặt.',
          'Tại các công trình do Minh Ân CDC thi công ở Đà Nẵng và Huế, đội ngũ kỹ sư luôn che phủ bạt ẩm, tưới nước dưỡng hộ định kỳ 3–4 lần/ngày trong tuần đầu tiên, đặc biệt vào những ngày nắng gió miền Trung.',
          'Việc tuân thủ nghiêm ngặt quy trình bảo dưỡng giúp móng, cột, dầm sàn đạt đúng mác thiết kế và tăng tuổi thọ công trình lên hàng chục năm.'
        ]
      },
      {
        driveId: '1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR',
        date: '10/11/2026',
        title: '03 Nỗi lo lớn nhất khi xây nhà trọn gói và giải pháp từ Minh Ân CDC',
        excerpt: 'Phát sinh chi phí, chậm tiến độ và chất lượng vật tư không đúng cam kết là 3 vấn đề khiến nhiều chủ đầu tư lo lắng nhất.',
        content: [
          'Khi chuẩn bị xây dựng tổ ấm, hầu hết gia chủ đều băn khoăn về việc đội chi phí so với dự toán ban đầu, tiến độ kéo dài hoặc vật tư bị thay đổi chủng loại.',
          'Giải pháp tại Minh Ân CDC là bóc tách dự toán chi tiết từng hạng mục trước khi ký hợp đồng, quy định rõ thương hiệu vật liệu (thép Hòa Phát, dây điện Cadivi, ống nhựa Bình Minh, xi măng Sông Gianh...).',
          'Bên cạnh đó, chủ đầu tư luôn được nghiệm thu vật tư đầu vào tại công trình và nhận báo cáo tiến độ hình ảnh hàng tuần.'
        ]
      },
      {
        driveId: '1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_',
        date: '04/11/2026',
        title: 'Kinh nghiệm thiết kế căn hộ cho thuê & khách sạn mini tối ưu lợi nhuận tại Đà Nẵng',
        excerpt: 'Cách bố trí mặt bằng công năng, thông gió tự nhiên và chọn vật liệu bền bỉ giúp tăng tỷ lệ lấp đầy và giảm chi phí bảo trì.',
        content: [
          'Đà Nẵng là thị trường phát triển mạnh về lưu trú và căn hộ dịch vụ. Một bản thiết kế hiệu quả cần cân bằng giữa số lượng phòng khai thác và trải nghiệm thoáng đãng cho khách lưu trú.',
          'Minh Ân CDC tư vấn giải pháp kết cấu vượt nhịp hợp lý, giếng trời lấy sáng tự nhiên, bố trí hộp kỹ thuật khoa học để dễ bảo trì đường ống điện nước về sau.',
          'Đồng thời, việc lựa chọn vật liệu mặt tiền và hệ cửa chống gió biển giúp công trình giữ được vẻ mới đẹp lâu dài.'
        ]
      },
      {
        driveId: '1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv',
        date: '28/10/2026',
        title: 'Chứng chỉ năng lực hoạt động xây dựng quan trọng như thế nào đối với chủ đầu tư?',
        excerpt: 'Lựa chọn nhà thầu có đầy đủ năng lực pháp lý giúp đảm bảo an toàn kết cấu, thủ tục xin phép và hoàn công thuận lợi.',
        content: [
          'Chứng chỉ năng lực hoạt động xây dựng là văn bản đánh giá điều kiện chuyên môn của tổ chức khi tham gia thiết kế, giám sát và thi công công trình.',
          'CÔNG TY TNHH MTV TƯ VẤN THIẾT KẾ XÂY DỰNG VÀ THƯƠNG MẠI MINH ÂN CDC đã được cấp Mã chứng chỉ năng lực HĐXD 00064700, đảm bảo đầy đủ tư cách pháp nhân và năng lực kỹ thuật.',
          'Điều này giúp Quý khách hàng hoàn toàn yên tâm trong suốt quá trình lập hồ sơ xin giấy phép xây dựng, thi công an toàn và hoàn công công trình.'
        ]
      }
    ];

    /* -----------------------------------------------------------------
       5. RENDER CÔNG TRÌNH THỰC TẾ (KHÔNG NHÃN DÁN, 2 CỘT MOBILE, FULL TÊN)
       ----------------------------------------------------------------- */
    function renderConstructionGrid(filterCat) {
      const container = document.getElementById('construction-grid');
      if (!container) return;

      const filtered = filterCat === 'all'
        ? constructionItems
        : constructionItems.filter(item => item.category === filterCat);

      container.innerHTML = filtered.map((item) => {
        const idx = constructionItems.indexOf(item);
        return `
          <article onclick="openConstructionModal(${idx})"
                   class="ux-card cursor-pointer bg-white rounded-xl border border-slate-200 overflow-hidden flex flex-col">
            <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
              <img
                data-drive-id="${item.id}"
                src="${driveUrl(item.id, 700)}"
                alt="${item.title}"
                loading="lazy"
                class="w-full h-full object-cover"
                onerror="handleDriveImageError(this)"
              >
            </div>
            <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
              <h3 class="text-[12px] sm:text-[13.5px] font-bold text-slate-800 leading-snug break-words">
                ${item.title}
              </h3>
              <div class="mt-2 pt-2 border-t border-slate-100 flex items-center justify-between gap-1 text-[11px] text-slate-500">
                <span class="break-words">${item.location}</span>
                <span class="text-[var(--brand-primary)] font-semibold shrink-0">Xem</span>
              </div>
            </div>
          </article>
        `;
      }).join('');
    }

    /* -----------------------------------------------------------------
       6. RENDER 10 DỰ ÁN TẠI ĐÀ NẴNG (KHÔNG NHÃN DÁN, 2 CỘT MOBILE, FULL TÊN)
       ----------------------------------------------------------------- */
    function renderDaNangProjects() {
      const container = document.getElementById('danang-projects-grid');
      if (!container) return;

      container.innerHTML = danangProjects.map((proj, idx) => `
        <article onclick="openDaNangModal(${idx})"
                 class="ux-card cursor-pointer bg-white rounded-xl border border-slate-200 overflow-hidden flex flex-col">
          <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
            <img
              data-drive-id="${proj.id}"
              src="${driveUrl(proj.id, 700)}"
              alt="${proj.title}"
              loading="lazy"
              class="w-full h-full object-cover"
              onerror="handleDriveImageError(this)"
            >
          </div>
          <div class="p-2.5 sm:p-3 flex-1 flex flex-col justify-between">
            <h3 class="text-[12px] sm:text-[13px] font-bold text-slate-800 leading-snug break-words">
              ${proj.title}
            </h3>
            <div class="mt-2 text-[11px] text-slate-500 break-words">
              <i class="fa-solid fa-location-dot text-[var(--brand-accent)] mr-1"></i>${proj.location}
            </div>
          </div>
        </article>
      `).join('');
    }

    /* -----------------------------------------------------------------
       7. RENDER DANH MỤC BÀI VIẾT TRANG CHỦ
       ----------------------------------------------------------------- */
    function renderArticles() {
      const container = document.getElementById('articles-grid');
      if (!container) return;

      container.innerHTML = articlesData.map((art, idx) => `
        <article onclick="openArticleModal(${idx})"
                 class="ux-card cursor-pointer bg-white rounded-xl border border-slate-200 overflow-hidden flex flex-col">
          <div class="aspect-[16/10] w-full overflow-hidden bg-slate-100">
            <img
              data-drive-id="${art.driveId}"
              src="${driveUrl(art.driveId, 700)}"
              alt="${art.title}"
              loading="lazy"
              class="w-full h-full object-cover"
              onerror="handleDriveImageError(this)"
            >
          </div>
          <div class="p-4 flex-1 flex flex-col justify-between">
            <div>
              <div class="text-[11px] font-medium text-slate-400 mb-1.5">
                <i class="fa-regular fa-calendar mr-1"></i>${art.date}
              </div>
              <h3 class="text-[13.5px] sm:text-sm font-bold text-[var(--brand-primary)] leading-snug break-words mb-2">
                ${art.title}
              </h3>
              <p class="text-xs text-slate-600 leading-relaxed break-words">
                ${art.excerpt}
              </p>
            </div>
            <div class="mt-3 pt-2.5 border-t border-slate-100 text-xs font-semibold text-[var(--brand-accent)] inline-flex items-center gap-1">
              <span>Đọc chi tiết</span>
              <i class="fa-solid fa-arrow-right text-[10px]"></i>
            </div>
          </div>
        </article>
      `).join('');
    }

    /* -----------------------------------------------------------------
       8. BỘ LỌC DANH MỤC & ĐIỀU HƯỚNG TỪ MENU
       ----------------------------------------------------------------- */
    function setActiveCategoryTab(cat) {
      document.querySelectorAll('.cat-tab-btn').forEach(btn => {
        if (btn.getAttribute('data-cat') === cat) {
          btn.classList.add('active');
          btn.classList.remove('bg-white', 'text-slate-700');
        } else {
          btn.classList.remove('active');
          btn.classList.add('bg-white', 'text-slate-700');
        }
      });
      renderConstructionGrid(cat);
    }

    function selectCategoryFromNav(cat) {
      setActiveCategoryTab(cat);
      closeMobileDrawer();
    }

    function prefillQuoteType(val) {
      const sel = document.getElementById('q-type');
      if (sel) {
        for (let i = 0; i < sel.options.length; i++) {
          if (sel.options[i].value === val) {
            sel.selectedIndex = i;
            break;
          }
        }
      }
      closeMobileDrawer();
    }

    /* -----------------------------------------------------------------
       9. CHUYỂN ĐỔI BẢN ĐỒ GOOGLE MAPS (TRỤ SỞ ĐÀ NẴNG / CHI NHÁNH HUẾ)
       ----------------------------------------------------------------- */
    function switchMap(branch) {
      const iframe = document.getElementById('google-map-iframe');
      const label = document.getElementById('map-address-label');
      const extLink = document.getElementById('map-external-link');
      const btnDn = document.getElementById('map-btn-dn');
      const btnHue = document.getElementById('map-btn-hue');

      if (branch === 'hue') {
        iframe.src = 'https://maps.google.com/maps?q=16/154+B%C3%A0+Tri%E1%BB%87u,+Thu%E1%BA%ADn+H%C3%B3a,+Hu%E1%BA%BF&t=&z=16&ie=UTF8&iwloc=&output=embed';
        label.innerHTML = '<i class="fa-solid fa-location-dot text-[var(--brand-accent)] mr-1"></i>Chi nhánh: 16/154 Bà Triệu, P. Thuận Hoá, TP. Huế';
        extLink.href = 'https://www.google.com/maps/search/?api=1&query=16/154+B%C3%A0+Tri%E1%BB%87u,+Thu%E1%BA%ADn+H%C3%B3a,+Hu%E1%BA%BF';

        btnHue.className = 'px-3 py-1.5 rounded-lg text-xs font-semibold bg-[var(--brand-primary)] text-white transition whitespace-nowrap';
        btnDn.className = 'px-3 py-1.5 rounded-lg text-xs font-semibold bg-white text-slate-700 border border-slate-300 hover:border-[var(--brand-primary)] transition whitespace-nowrap';
      } else {
        iframe.src = 'https://maps.google.com/maps?q=35+Phan+Th%C3%A0nh+T%C3%A0i,+H%E1%BA%A3i+Ch%C3%A2u,+%C4%90%C3%A0+N%E1%BA%B5ng&t=&z=16&ie=UTF8&iwloc=&output=embed';
        label.innerHTML = '<i class="fa-solid fa-location-dot text-[var(--brand-accent)] mr-1"></i>Trụ sở: 35 Phan Thành Tài, P. Hải Châu, TP. Đà Nẵng';
        extLink.href = 'https://www.google.com/maps/search/?api=1&query=35+Phan+Th%C3%A0nh+T%C3%A0i,+H%E1%BA%A3i+Ch%C3%A2u,+%C4%90%C3%A0+N%E1%BA%B5ng';

        btnDn.className = 'px-3 py-1.5 rounded-lg text-xs font-semibold bg-[var(--brand-primary)] text-white transition whitespace-nowrap';
        btnHue.className = 'px-3 py-1.5 rounded-lg text-xs font-semibold bg-white text-slate-700 border border-slate-300 hover:border-[var(--brand-primary)] transition whitespace-nowrap';
      }
    }

    /* -----------------------------------------------------------------
       10. SLIDER 2 BANNER TỰ TRƯỢT (HỖ TRỢ VUỐT CẢM ỨNG & AUTO-SLIDE)
       ----------------------------------------------------------------- */
    let currentSlide = 0;
    const totalSlides = 2;
    let slideTimer = null;

    function goToSlide(index) {
      currentSlide = (index + totalSlides) % totalSlides;
      const track = document.getElementById('hero-track');
      if (track) {
        track.style.transform = 'translateX(-' + (currentSlide * 100) + '%)';
      }
      document.querySelectorAll('.hero-dot').forEach((dot, i) => {
        if (i === currentSlide) {
          dot.classList.remove('w-2.5', 'bg-white/50');
          dot.classList.add('w-7', 'bg-[var(--brand-accent)]');
        } else {
          dot.classList.remove('w-7', 'bg-[var(--brand-accent)]');
          dot.classList.add('w-2.5', 'bg-white/50');
        }
      });
    }

    function startAutoSlide() {
      stopAutoSlide();
      slideTimer = setInterval(() => {
        goToSlide(currentSlide + 1);
      }, 5000);
    }

    function stopAutoSlide() {
      if (slideTimer) {
        clearInterval(slideTimer);
        slideTimer = null;
      }
    }

    /* -----------------------------------------------------------------
       11. MODAL XEM CHI TIẾT CÔNG TRÌNH / DỰ ÁN / BÀI VIẾT
       ----------------------------------------------------------------- */
    function openModal(title, driveId, metaText, paragraphs) {
      const modal = document.getElementById('detail-modal');
      const img = document.getElementById('modal-image');
      document.getElementById('modal-title').textContent = title;
      document.getElementById('modal-meta').textContent = metaText;

      img.removeAttribute('data-fallback-step');
      img.setAttribute('data-drive-id', driveId);
      img.src = driveUrl(driveId, 1200);
      img.alt = title;

      document.getElementById('modal-desc').innerHTML = paragraphs
        .map(p => '<p>' + p + '</p>')
        .join('');

      modal.classList.remove('hidden');
      modal.classList.add('flex');
      document.body.style.overflow = 'hidden';
    }

    function openConstructionModal(index) {
      const item = constructionItems[index];
      if (!item) return;
      openModal(
        item.title,
        item.id,
        'Danh mục: ' + item.categoryLabel + '  •  Địa điểm: ' + item.location,
        [item.desc, 'Đơn vị thực hiện: CÔNG TY TNHH MTV TƯ VẤN THIẾT KẾ XÂY DỰNG VÀ THƯƠNG MẠI MINH ÂN CDC (minhancdc.com).']
      );
    }

    function openDaNangModal(index) {
      const proj = danangProjects[index];
      if (!proj) return;
      openModal(
        proj.title,
        proj.id,
        'Dự án tiêu biểu tại Đà Nẵng  •  ' + proj.location,
        [proj.desc, 'Liên hệ Hotline / Zalo 0941 394 848 để được tư vấn phương án thiết kế và báo giá chi tiết cho công trình của bạn.']
      );
    }

    function openArticleModal(index) {
      const art = articlesData[index];
      if (!art) return;
      openModal(
        art.title,
        art.driveId,
        'Chuyên mục Tin tức & Kiến thức Xây dựng  •  Ngày đăng: ' + art.date,
        art.content
      );
    }

    function closeDetailModal() {
      const modal = document.getElementById('detail-modal');
      modal.classList.add('hidden');
      modal.classList.remove('flex');
      document.body.style.overflow = '';
    }

    /* -----------------------------------------------------------------
       12. MENU MOBILE DRAWER & THÔNG BÁO TOAST
       ----------------------------------------------------------------- */
    function openMobileDrawer() {
      const overlay = document.getElementById('mobile-drawer-overlay');
      const drawer = document.getElementById('mobile-drawer');
      overlay.classList.remove('hidden');
      setTimeout(() => {
        overlay.classList.remove('opacity-0');
        drawer.classList.remove('-translate-x-full');
      }, 10);
      document.body.style.overflow = 'hidden';
    }

    function closeMobileDrawer() {
      const overlay = document.getElementById('mobile-drawer-overlay');
      const drawer = document.getElementById('mobile-drawer');
      overlay.classList.add('opacity-0');
      drawer.classList.add('-translate-x-full');
      setTimeout(() => {
        overlay.classList.add('hidden');
      }, 250);
      document.body.style.overflow = '';
    }

    let toastTimeout = null;
    function showToast(title, msg) {
      const box = document.getElementById('toast-box');
      document.getElementById('toast-title').textContent = title;
      document.getElementById('toast-msg').textContent = msg;
      box.classList.remove('hidden');
      if (toastTimeout) clearTimeout(toastTimeout);
      toastTimeout = setTimeout(hideToast, 6000);
    }

    function hideToast() {
      document.getElementById('toast-box').classList.add('hidden');
    }

    /* -----------------------------------------------------------------
       13. KHỞI TẠO SỰ KIỆN KHI TẢI TRANG
       ----------------------------------------------------------------- */
    document.addEventListener('DOMContentLoaded', function () {
      // Render các phần nội dung chính
      renderConstructionGrid('all');
      renderDaNangProjects();
      renderArticles();

      // Khởi chạy slider 2 banner tự trượt
      startAutoSlide();

      const sliderEl = document.getElementById('hero-slider');
      document.getElementById('hero-prev').addEventListener('click', () => {
        goToSlide(currentSlide - 1);
        startAutoSlide();
      });
      document.getElementById('hero-next').addEventListener('click', () => {
        goToSlide(currentSlide + 1);
        startAutoSlide();
      });
      document.querySelectorAll('.hero-dot').forEach(dot => {
        dot.addEventListener('click', () => {
          goToSlide(parseInt(dot.getAttribute('data-slide'), 10));
          startAutoSlide();
        });
      });

      // Tạm dừng khi di chuột vào banner trên máy tính
      sliderEl.addEventListener('mouseenter', stopAutoSlide);
      sliderEl.addEventListener('mouseleave', startAutoSlide);

      // Hỗ trợ vuốt cảm ứng trái/phải cho 2 banner trên điện thoại
      let touchStartX = 0;
      sliderEl.addEventListener('touchstart', (e) => {
        touchStartX = e.changedTouches[0].screenX;
        stopAutoSlide();
      }, { passive: true });
      sliderEl.addEventListener('touchend', (e) => {
        const diff = touchStartX - e.changedTouches[0].screenX;
        if (Math.abs(diff) > 40) {
          goToSlide(diff > 0 ? currentSlide + 1 : currentSlide - 1);
        }
        startAutoSlide();
      }, { passive: true });

      // Bộ lọc danh mục công trình thực tế
      document.querySelectorAll('.cat-tab-btn').forEach(btn => {
        btn.addEventListener('click', () => {
          setActiveCategoryTab(btn.getAttribute('data-cat'));
        });
      });

      // Sự kiện Mobile Drawer
      document.getElementById('mobile-menu-open').addEventListener('click', openMobileDrawer);
      document.getElementById('mobile-menu-close').addEventListener('click', closeMobileDrawer);
      document.getElementById('mobile-drawer-overlay').addEventListener('click', closeMobileDrawer);
      document.querySelectorAll('.mobile-nav-link').forEach(link => {
        link.addEventListener('click', closeMobileDrawer);
      });

      // Đóng modal khi click ra ngoài nền tối
      document.getElementById('detail-modal').addEventListener('click', (e) => {
        if (e.target.id === 'detail-modal') closeDetailModal();
      });

      // Xử lý Form yêu cầu tư vấn & báo giá
      document.getElementById('quote-form').addEventListener('submit', function (e) {
        e.preventDefault();
        const name = document.getElementById('q-name').value.trim();
        const phone = document.getElementById('q-phone').value.trim();
        const type = document.getElementById('q-type').value;

        if (!name || !phone) {
          showToast('Vui lòng kiểm tra lại', 'Bạn vui lòng nhập đầy đủ Họ tên và Số điện thoại để Minh Ân CDC liên hệ báo giá.');
          return;
        }

        showToast(
          'Gửi yêu cầu báo giá thành công!',
          'Cảm ơn ' + name + '. Minh Ân CDC đã tiếp nhận yêu cầu "' + type + '" và sẽ liên hệ qua số ' + phone + ' trong thời gian sớm nhất.'
        );
        this.reset();
      });

      // Nút cuộn lên đầu trang
      const scrollTopBtn = document.getElementById('scroll-top-btn');
      window.addEventListener('scroll', () => {
        if (window.scrollY > 360) {
          scrollTopBtn.classList.remove('hidden');
          scrollTopBtn.classList.add('flex');
        } else {
          scrollTopBtn.classList.add('hidden');
          scrollTopBtn.classList.remove('flex');
        }
      }, { passive: true });
    });
  </script>
</body>
</html>
