<html lang="vi">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>CÔNG TY TNHH XÂY DỰNG RIN HOUSE | Thiết Kế &amp; Thi Công Trọn Gói Đà Nẵng - rinhouse.com</title>
  <meta name="description" content="CÔNG TY TNHH XÂY DỰNG RIN HOUSE (rinhouse.com) - Chuyên Thiết kế Kiến trúc, Thi công Phần thô, Hoàn thiện &amp; Nội thất trọn gói tại Đà Nẵng. Địa chỉ: 202 Bích Khê, Phường Hòa Xuân, TP Đà Nẵng. Hotline: 0394.234.956.">

  <!-- ===================================================================== -->
  <!-- ẢNH THUMBNAIL CHIA SẺ LINK (OPEN GRAPH & TWITTER CARD - LOGO RIN HOUSE) -->
  <!-- ===================================================================== -->
  <meta property="og:type" content="website">
  <meta property="og:site_name" content="RIN HOUSE - rinhouse.com">
  <meta property="og:url" content="https://rinhouse.com/">
  <meta property="og:title" content="CÔNG TY TNHH XÂY DỰNG RIN HOUSE | Thiết Kế &amp; Thi Công Trọn Gói Đà Nẵng">
  <meta property="og:description" content="Thiết kế kiến trúc, thi công xây dựng nhà phố, biệt thự, căn hộ, khách sạn uy tín tại Đà Nẵng. Địa chỉ: 202 Bích Khê, Phường Hòa Xuân, TP Đà Nẵng. Hotline: 0394.234.956.">
  <!-- Thumbnail logo định dạng SVG chuẩn để hiển thị logo công ty khi chia sẻ link; khi đưa lên WordPress/Hosting bạn có thể thay bằng đường dẫn file logo PNG 1200x630 -->
  <meta property="og:image" content="https://rinhouse.com/wp-content/uploads/logo-rin-house-thumbnail.png">
  <meta property="og:image:alt" content="Logo Công Ty TNHH Xây Dựng Rin House">
  <meta property="og:image:width" content="1200">
  <meta property="og:image:height" content="630">
  <meta name="twitter:card" content="summary_large_image">
  <meta name="twitter:title" content="CÔNG TY TNHH XÂY DỰNG RIN HOUSE - rinhouse.com">
  <meta name="twitter:description" content="Thiết kế kiến trúc &amp; thi công xây dựng trọn gói chuyên nghiệp tại Đà Nẵng. Hotline: 0394.234.956.">
  <meta name="twitter:image" content="https://rinhouse.com/wp-content/uploads/logo-rin-house-thumbnail.png">

  <!-- Favicon Logo Rin House -->
  <link rel="icon" type="image/svg+xml" href="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 64 64'%3E%3Crect width='64' height='64' rx='12' fill='%230F2C4C'/%3E%3Cpath d='M12 31L32 14L52 31' fill='none' stroke='%23C88A2B' stroke-width='5' stroke-linecap='round' stroke-linejoin='round'/%3E%3Cpath d='M20 30V50H44V30' fill='none' stroke='%23FFFFFF' stroke-width='4' stroke-linecap='round' stroke-linejoin='round'/%3E%3Crect x='28' y='37' width='8' height='13' fill='%23C88A2B'/%3E%3C/svg%3E">

  <!-- Google Fonts: Inter & Plus Jakarta Sans -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">

  <!-- Tailwind CSS CDN -->
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
              navy: '#0F2C4C',      /* Màu xanh đậm chủ đạo từ logo Rin House */
              navyDark: '#091E36',  /* Xanh đậm sâu cho footer / hover */
              navyLight: '#1B436E', /* Xanh trung tính cho điểm nhấn */
              gold: '#C88A2B',      /* Màu vàng đồng kiến trúc từ logo Rin House */
              goldHover: '#B0761E', /* Vàng đồng đậm khi hover */
              goldSoft: '#FBF5EA',  /* Nền vàng nhạt tinh tế */
              surface: '#F6F8FB',   /* Nền xám sáng thanh lịch Flatsome */
              ink: '#1E293B',       /* Màu chữ chính dễ đọc */
              muted: '#5B6779'      /* Màu chữ phụ */
            }
          }
        }
      }
    }
  </script>

  <style>
    /* Đảm bảo Box Sizing chuẩn, không bao giờ tràn viền hay lệch sang phải */
    *, *::before, *::after {
      box-sizing: border-box;
    }

    html, body {
      margin: 0;
      padding: 0;
      width: 100%;
      max-width: 100%;
      overflow-x: hidden;
      scroll-behavior: smooth;
      font-family: 'Inter', system-ui, -apple-system, sans-serif;
      color: #1E293B;
      background-color: #FFFFFF;
    }

    /* Container chuẩn Flatsome: 95% chiều ngang màn hình trên máy tính, gọn gàng trên điện thoại */
    .rh-container {
      width: 100%;
      max-width: 100%;
      margin-left: auto;
      margin-right: auto;
      padding-left: 12px;
      padding-right: 12px;
    }

    @media (min-width: 640px) {
      .rh-container {
        padding-left: 20px;
        padding-right: 20px;
      }
    }

    @media (min-width: 1024px) {
      .rh-container {
        width: 95%;
        max-width: 95%;
        padding-left: 0;
        padding-right: 0;
      }
    }

    /* Flatsome Dropdown Menu mượt mà trên Desktop */
    .rh-nav-item {
      position: relative;
    }
    .rh-dropdown {
      opacity: 0;
      visibility: hidden;
      transform: translateY(8px);
      transition: all 0.2s ease;
      pointer-events: none;
    }
    .rh-nav-item:hover .rh-dropdown,
    .rh-nav-item:focus-within .rh-dropdown {
      opacity: 1;
      visibility: visible;
      transform: translateY(0);
      pointer-events: auto;
    }

    /* 2 Banner tự trượt cùng 1 kích thước tuyệt đối nhờ CSS Grid overlap */
    .rh-hero-grid {
      display: grid;
      grid-template-columns: 1fr;
    }
    .rh-hero-slide {
      grid-column: 1 / -1;
      grid-row: 1 / -1;
      transition: opacity 0.7s ease-in-out, visibility 0.7s ease-in-out;
    }
    .rh-hero-slide.is-active {
      opacity: 1;
      visibility: visible;
      z-index: 2;
      pointer-events: auto;
    }
    .rh-hero-slide.is-inactive {
      opacity: 0;
      visibility: hidden;
      z-index: 1;
      pointer-events: none;
    }

    /* Hiệu ứng nhẹ nhàng cho ảnh Flatsome card */
    .rh-card-img {
      transition: transform 0.45s ease;
    }
    .rh-card:hover .rh-card-img {
      transform: scale(1.05);
    }

    /* Ẩn thanh cuộn nhưng vẫn cho vuốt mượt trên danh mục mobile nếu cần */
    .no-scrollbar::-webkit-scrollbar {
      display: none;
    }
    .no-scrollbar {
      -ms-overflow-style: none;
      scrollbar-width: none;
    }

    /* Hiệu ứng vòng tỏa nhẹ cho nút Hotline nổi bật */
    @keyframes rhPulse {
      0% { transform: scale(1); opacity: 0.75; }
      100% { transform: scale(1.55); opacity: 0; }
    }
    .rh-pulse-ring {
      animation: rhPulse 1.8s cubic-bezier(0.24, 0, 0.38, 1) infinite;
    }
  </style>
</head>
<body class="bg-white text-brand-ink antialiased">

  <!-- ===================================================================== -->
  <!-- TOP INFO BAR (PHONG CÁCH FLATSOME - GỌN GÀNG, KHÔNG CÓ THANH UXBUILDER) -->
  <!-- ===================================================================== -->
  <div class="bg-brand-navy text-white text-[11px] sm:text-xs border-b border-white/10">
    <div class="rh-container py-2 flex flex-wrap items-center justify-between gap-2">
      <div class="flex items-center gap-3 sm:gap-5 min-w-0">
        <span class="inline-flex items-center gap-1.5 text-white/90 truncate">
          <svg class="w-3.5 h-3.5 text-brand-gold shrink-0" fill="none" stroke="currentColor" viewBox="0 0 24 24">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z"/>
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 11a3 3 0 11-6 0 3 3 0 016 0z"/>
          </svg>
          <span class="truncate">202 Bích Khê, Phường Hòa Xuân, TP Đà Nẵng</span>
        </span>
      </div>
      <div class="hidden sm:flex items-center gap-4 shrink-0">
        <a href="tel:0394234956" class="inline-flex items-center gap-1.5 text-white/90 hover:text-brand-gold transition">
          <svg class="w-3.5 h-3.5 text-brand-gold" fill="none" stroke="currentColor" viewBox="0 0 24 24">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"/>
          </svg>
          <span>0394.234.956</span>
        </a>
        <span class="text-white/30">|</span>
        <span class="text-white/90">rinhouse.com</span>
      </div>
    </div>
  </div>

  <!-- ===================================================================== -->
  <!-- HEADER CHÍNH (LOGO GỌN NHỎ + MENU 1 HÀNG CHỮ NHỎ + KHÔNG CÓ NÚT GỌI NGAY) -->
  <!-- ===================================================================== -->
  <header class="sticky top-0 z-40 bg-white/95 backdrop-blur border-b border-slate-200 shadow-sm">
    <div class="rh-container h-14 sm:h-16 flex items-center justify-between gap-3">

      <!-- LOGO CÔNG TY TNHH XÂY DỰNG RIN HOUSE (GỌN NHỎ, CHUYÊN NGHIỆP) -->
      <a href="#trang-chu" class="flex items-center gap-2 shrink-0 group focus:outline-none" aria-label="CÔNG TY TNHH XÂY DỰNG RIN HOUSE">
        <!-- Biểu tượng kiến trúc vector nhỏ gọn -->
        <svg class="w-9 h-9 sm:w-10 sm:h-10 shrink-0" viewBox="0 0 48 48" fill="none" xmlns="http://www.w3.org/2000/svg">
          <rect width="48" height="48" rx="9" fill="#0F2C4C"/>
          <!-- Mái nhà hình học kiến trúc -->
          <path d="M9 24.5L24 11L39 24.5" stroke="#C88A2B" stroke-width="3.4" stroke-linecap="round" stroke-linejoin="round"/>
          <!-- Khung công trình vững chãi -->
          <path d="M15 23V37H33V23" stroke="#FFFFFF" stroke-width="2.6" stroke-linecap="round" stroke-linejoin="round"/>
          <!-- Cột kiến trúc chữ H cách điệu -->
          <path d="M21 37V27.5H27V37" fill="#C88A2B"/>
          <!-- Đường nền móng vững chắc -->
          <path d="M11 37H37" stroke="#C88A2B" stroke-width="2" stroke-linecap="round"/>
        </svg>
        <div class="leading-none">
          <div class="text-[15px] sm:text-[17px] font-extrabold tracking-tight text-brand-navy group-hover:text-brand-gold transition">
            RIN <span class="text-brand-gold">HOUSE</span>
          </div>
          <div class="text-[8.5px] sm:text-[9.5px] font-semibold tracking-[0.14em] text-brand-muted uppercase mt-0.5">
            XÂY DỰNG &amp; KIẾN TRÚC
          </div>
        </div>
      </a>

      <!-- MENU MÁY TÍNH: VIẾT LIỀN TRÊN 1 HÀNG, CHỮ NHỎ GỌN, KHÔNG XUỐNG DÒNG -->
      <nav class="hidden lg:flex items-center justify-end flex-nowrap gap-3.5 xl:gap-5" aria-label="Menu chính">
        <a href="#trang-chu" class="whitespace-nowrap text-[12px] xl:text-[13px] font-semibold uppercase tracking-tight text-brand-gold transition">
          Trang chủ
        </a>
        <a href="#gioi-thieu" class="whitespace-nowrap text-[12px] xl:text-[13px] font-semibold uppercase tracking-tight text-brand-navy hover:text-brand-gold transition">
          Giới thiệu
        </a>

        <!-- Dropdown: Công trình thực tế (theo mẫu tintruongthinh.com) -->
        <div class="rh-nav-item py-3">
          <a href="#cong-trinh-thuc-te" class="whitespace-nowrap inline-flex items-center gap-1 text-[12px] xl:text-[13px] font-semibold uppercase tracking-tight text-brand-navy hover:text-brand-gold transition">
            <span>Công trình thực tế</span>
            <svg class="w-3 h-3 opacity-70" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2.5" d="M19 9l-7 7-7-7"/></svg>
          </a>
          <div class="rh-dropdown absolute left-0 top-full w-60 bg-white border border-slate-200 rounded-lg shadow-lg py-1.5 z-50">
            <a href="#cong-trinh-thuc-te" onclick="filterWorks('khach-san-can-ho')" class="block px-4 py-2 text-[13px] text-brand-ink hover:bg-brand-goldSoft hover:text-brand-navy font-medium">Khách sạn – Căn hộ – Phòng trọ</a>
            <a href="#cong-trinh-thuc-te" onclick="filterWorks('biet-thu')" class="block px-4 py-2 text-[13px] text-brand-ink hover:bg-brand-goldSoft hover:text-brand-navy font-medium">Biệt thự</a>
            <a href="#cong-trinh-thuc-te" onclick="filterWorks('nha-pho')" class="block px-4 py-2 text-[13px] text-brand-ink hover:bg-brand-goldSoft hover:text-brand-navy font-medium">Nhà phố</a>
            <a href="#cong-trinh-thuc-te" onclick="filterWorks('van-phong')" class="block px-4 py-2 text-[13px] text-brand-ink hover:bg-brand-goldSoft hover:text-brand-navy font-medium">Văn phòng</a>
          </div>
        </div>

        <!-- Dropdown: Lĩnh vực hoạt động -->
        <div class="rh-nav-item py-3">
          <a href="#linh-vuc" class="whitespace-nowrap inline-flex items-center gap-1 text-[12px] xl:text-[13px] font-semibold uppercase tracking-tight text-brand-navy hover:text-brand-gold transition">
            <span>Lĩnh vực hoạt động</span>
            <svg class="w-3 h-3 opacity-70" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2.5" d="M19 9l-7 7-7-7"/></svg>
          </a>
          <div class="rh-dropdown absolute left-0 top-full w-60 bg-white border border-slate-200 rounded-lg shadow-lg py-1.5 z-50">
            <a href="#linh-vuc" class="block px-4 py-2 text-[13px] text-brand-ink hover:bg-brand-goldSoft hover:text-brand-navy font-medium">Thiết kế Kiến trúc – Nội thất</a>
            <a href="#cong-trinh-thuc-te" onclick="filterWorks('thi-cong-tho')" class="block px-4 py-2 text-[13px] text-brand-ink hover:bg-brand-goldSoft hover:text-brand-navy font-medium">Thi công phần thô</a>
            <a href="#cong-trinh-thuc-te" onclick="filterWorks('hoan-thien')" class="block px-4 py-2 text-[13px] text-brand-ink hover:bg-brand-goldSoft hover:text-brand-navy font-medium">Thi công hoàn thiện</a>
            <a href="#cong-trinh-thuc-te" onclick="filterWorks('noi-that')" class="block px-4 py-2 text-[13px] text-brand-ink hover:bg-brand-goldSoft hover:text-brand-navy font-medium">Thi công nội thất</a>
          </div>
        </div>

        <!-- Dropdown: Mẫu thiết kế -->
        <div class="rh-nav-item py-3">
          <a href="#du-an-da-nang" class="whitespace-nowrap inline-flex items-center gap-1 text-[12px] xl:text-[13px] font-semibold uppercase tracking-tight text-brand-navy hover:text-brand-gold transition">
            <span>Dự án Đà Nẵng</span>
            <svg class="w-3 h-3 opacity-70" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2.5" d="M19 9l-7 7-7-7"/></svg>
          </a>
          <div class="rh-dropdown absolute left-0 top-full w-56 bg-white border border-slate-200 rounded-lg shadow-lg py-1.5 z-50">
            <a href="#du-an-da-nang" onclick="filterDanang('all')" class="block px-4 py-2 text-[13px] text-brand-ink hover:bg-brand-goldSoft hover:text-brand-navy font-medium">Tất cả dự án Đà Nẵng</a>
            <a href="#du-an-da-nang" onclick="filterDanang('nha-pho')" class="block px-4 py-2 text-[13px] text-brand-ink hover:bg-brand-goldSoft hover:text-brand-navy font-medium">Mẫu thiết kế nhà phố</a>
            <a href="#du-an-da-nang" onclick="filterDanang('biet-thu')" class="block px-4 py-2 text-[13px] text-brand-ink hover:bg-brand-goldSoft hover:text-brand-navy font-medium">Biệt thự &amp; Villa</a>
            <a href="#du-an-da-nang" onclick="filterDanang('noi-that')" class="block px-4 py-2 text-[13px] text-brand-ink hover:bg-brand-goldSoft hover:text-brand-navy font-medium">Mẫu thiết kế nội thất</a>
          </div>
        </div>

        <!-- Dropdown: Báo giá -->
        <div class="rh-nav-item py-3">
          <a href="#bao-gia" class="whitespace-nowrap inline-flex items-center gap-1 text-[12px] xl:text-[13px] font-semibold uppercase tracking-tight text-brand-navy hover:text-brand-gold transition">
            <span>Báo giá</span>
            <svg class="w-3 h-3 opacity-70" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2.5" d="M19 9l-7 7-7-7"/></svg>
          </a>
          <div class="rh-dropdown absolute right-0 top-full w-60 bg-white border border-slate-200 rounded-lg shadow-lg py-1.5 z-50">
            <a href="#bao-gia" class="block px-4 py-2 text-[13px] text-brand-ink hover:bg-brand-goldSoft hover:text-brand-navy font-medium">Báo giá thiết kế kiến trúc</a>
            <a href="#bao-gia" class="block px-4 py-2 text-[13px] text-brand-ink hover:bg-brand-goldSoft hover:text-brand-navy font-medium">Báo giá thi công phần thô</a>
            <a href="#bao-gia" class="block px-4 py-2 text-[13px] text-brand-ink hover:bg-brand-goldSoft hover:text-brand-navy font-medium">Báo giá thi công hoàn thiện</a>
            <a href="#bao-gia" class="block px-4 py-2 text-[13px] text-brand-ink hover:bg-brand-goldSoft hover:text-brand-navy font-medium">Báo giá thi công trọn gói</a>
          </div>
        </div>

        <a href="#bai-viet" class="whitespace-nowrap text-[12px] xl:text-[13px] font-semibold uppercase tracking-tight text-brand-navy hover:text-brand-gold transition">
          Tin tức
        </a>
        <a href="#doi-tac" class="whitespace-nowrap text-[12px] xl:text-[13px] font-semibold uppercase tracking-tight text-brand-navy hover:text-brand-gold transition">
          Đối tác
        </a>
        <a href="#lien-he" class="whitespace-nowrap text-[12px] xl:text-[13px] font-semibold uppercase tracking-tight text-brand-navy hover:text-brand-gold transition">
          Liên hệ
        </a>
      </nav>

      <!-- NÚT MENU ĐIỆN THOẠI (CHỈ HIỂN THỊ DƯỚI 1024px) -->
      <button id="mobileMenuBtn" type="button" class="lg:hidden inline-flex items-center justify-center p-2.5 rounded-lg text-brand-navy hover:bg-slate-100 focus:outline-none" aria-label="Mở danh mục điều hướng">
        <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24">
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2.2" d="M4 6h16M4 12h16M4 18h16"/>
        </svg>
      </button>
    </div>

    <!-- MENU XỔ XUỐNG TRÊN ĐIỆN THOẠI -->
    <div id="mobileMenu" class="hidden lg:hidden bg-white border-t border-slate-200 shadow-lg">
      <div class="rh-container py-3 flex flex-col divide-y divide-slate-100 text-sm font-semibold text-brand-navy">
        <a href="#trang-chu" class="py-2.5 hover:text-brand-gold mobile-link">Trang chủ</a>
        <a href="#gioi-thieu" class="py-2.5 hover:text-brand-gold mobile-link">Giới thiệu</a>
        <a href="#linh-vuc" class="py-2.5 hover:text-brand-gold mobile-link">Lĩnh vực hoạt động</a>
        <a href="#cong-trinh-thuc-te" class="py-2.5 hover:text-brand-gold mobile-link">Công trình thực tế</a>
        <a href="#du-an-da-nang" class="py-2.5 hover:text-brand-gold mobile-link">Dự án tại Đà Nẵng</a>
        <a href="#bao-gia" class="py-2.5 hover:text-brand-gold mobile-link">Báo giá &amp; Tư vấn</a>
        <a href="#bai-viet" class="py-2.5 hover:text-brand-gold mobile-link">Tin tức xây dựng</a>
        <a href="#doi-tac" class="py-2.5 hover:text-brand-gold mobile-link">Đối tác chiến lược</a>
        <a href="#lien-he" class="py-2.5 hover:text-brand-gold mobile-link">Liên hệ &amp; Bản đồ</a>
      </div>
    </div>
  </header>

  <main id="trang-chu" class="w-full overflow-x-hidden">

    <!-- ===================================================================== -->
    <!-- SECTION 1 (UX BUILDER SLIDER): 2 ẢNH BANNER TỰ TRƯỢT KÍCH THƯỚC BẰNG NHAU -->
    <!-- CHỮ & HÌNH NẰM GỌN BÊN TRONG, CÁCH XA VIỀN, KHÔNG THIẾU CHỮ TRÊN MOBILE/PC -->
    <!-- ===================================================================== -->
    <section class="w-full bg-brand-navyDark py-3 sm:py-5">
      <div class="rh-container">
        <div id="heroSlider" class="relative w-full rounded-xl overflow-hidden shadow-lg bg-brand-navy">

          <!-- Grid overlap giúp 2 slide luôn có chiều cao và chiều rộng BẰNG NHAU 100% ở mọi kích thước màn hình -->
          <div class="rh-hero-grid w-full">

            <!-- BANNER 1 -->
            <div class="rh-hero-slide is-active relative w-full flex items-center" data-slide="0">
              <img
                src="https://drive.google.com/thumbnail?id=157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT&sz=w1600"
                alt="Thiết kế và thi công nhà trọn gói Rin House Đà Nẵng"
                referrerpolicy="no-referrer"
                onerror="handleDriveError(this, '157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT', 'RIN+HOUSE+XAY+DUNG+DA+NANG')"
                class="absolute inset-0 w-full h-full object-cover object-center"
              >
              <!-- Lớp phủ tối tạo độ tương phản cao cho chữ -->
              <div class="absolute inset-0 bg-gradient-to-r from-brand-navyDark/90 via-brand-navy/75 to-brand-navyDark/55"></div>

              <!-- Khung nội dung cách xa viền banner ở cả 4 phía -->
              <div class="relative z-10 w-full px-10 py-10 sm:px-16 sm:py-16 md:px-24 md:py-20 lg:px-28 lg:py-24">
                <div class="max-w-2xl">
                  <div class="w-12 h-1 bg-brand-gold rounded-full mb-3 sm:mb-4"></div>
                  <p class="text-[11px] sm:text-xs md:text-sm font-semibold uppercase tracking-[0.18em] text-brand-gold mb-2">
                    CÔNG TY TNHH XÂY DỰNG RIN HOUSE
                  </p>
                  <h1 class="text-lg sm:text-2xl md:text-4xl lg:text-[42px] font-extrabold text-white leading-snug md:leading-tight mb-3 sm:mb-4">
                    THIẾT KẾ &amp; THI CÔNG NHÀ TRỌN GÓI CHUYÊN NGHIỆP TẠI ĐÀ NẴNG
                  </h1>
                  <p class="text-xs sm:text-sm md:text-base text-slate-200 leading-relaxed mb-5 sm:mb-7">
                    Kiến tạo không gian sống bền vững với tiêu chuẩn kỹ thuật cao, tiến độ minh bạch và chi phí tối ưu cho mọi công trình nhà phố, biệt thự, căn hộ.
                  </p>
                  <div class="flex flex-wrap items-center gap-2.5 sm:gap-3">
                    <a href="#bao-gia" class="inline-flex items-center justify-center px-4 py-2 sm:px-6 sm:py-3 rounded-lg bg-brand-gold hover:bg-brand-goldHover text-white font-semibold text-xs sm:text-sm transition shadow-md">
                      Nhận Báo Giá Miễn Phí
                    </a>
                    <a href="#du-an-da-nang" class="inline-flex items-center justify-center px-4 py-2 sm:px-6 sm:py-3 rounded-lg bg-white/15 hover:bg-white/25 border border-white/40 text-white font-semibold text-xs sm:text-sm transition">
                      Xem Dự Án Đà Nẵng
                    </a>
                  </div>
                </div>
              </div>
            </div>

            <!-- BANNER 2 -->
            <div class="rh-hero-slide is-inactive relative w-full flex items-center" data-slide="1">
              <img
                src="https://drive.google.com/thumbnail?id=13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz&sz=w1600"
                alt="Thi công phần thô, hoàn thiện và nội thất Rin House"
                referrerpolicy="no-referrer"
                onerror="handleDriveError(this, '13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz', 'THI+CONG+THUC+TE+RIN+HOUSE')"
                class="absolute inset-0 w-full h-full object-cover object-center"
              >
              <div class="absolute inset-0 bg-gradient-to-r from-brand-navyDark/90 via-brand-navy/75 to-brand-navyDark/55"></div>

              <!-- Khung nội dung cách xa viền banner ở cả 4 phía -->
              <div class="relative z-10 w-full px-10 py-10 sm:px-16 sm:py-16 md:px-24 md:py-20 lg:px-28 lg:py-24">
                <div class="max-w-2xl">
                  <div class="w-12 h-1 bg-brand-gold rounded-full mb-3 sm:mb-4"></div>
                  <p class="text-[11px] sm:text-xs md:text-sm font-semibold uppercase tracking-[0.18em] text-brand-gold mb-2">
                    NHÀ Ở GIA ĐÌNH – TIÊU CHUẨN CÔNG TRÌNH
                  </p>
                  <h2 class="text-lg sm:text-2xl md:text-4xl lg:text-[42px] font-extrabold text-white leading-snug md:leading-tight mb-3 sm:mb-4">
                    THI CÔNG PHẦN THÔ, HOÀN THIỆN &amp; NỘI THẤT CHUẨN KỸ THUẬT
                  </h2>
                  <p class="text-xs sm:text-sm md:text-base text-slate-200 leading-relaxed mb-5 sm:mb-7">
                    Đội ngũ kỹ sư và kiến trúc sư giàu kinh nghiệm trực tiếp giám sát từng hạng mục, cam kết vật tư chính hãng và bảo hành kết cấu dài lâu.
                  </p>
                  <div class="flex flex-wrap items-center gap-2.5 sm:gap-3">
                    <a href="#cong-trinh-thuc-te" class="inline-flex items-center justify-center px-4 py-2 sm:px-6 sm:py-3 rounded-lg bg-brand-gold hover:bg-brand-goldHover text-white font-semibold text-xs sm:text-sm transition shadow-md">
                      Xem Công Trình Thực Tế
                    </a>
                    <a href="tel:0394234956" class="inline-flex items-center justify-center px-4 py-2 sm:px-6 sm:py-3 rounded-lg bg-white/15 hover:bg-white/25 border border-white/40 text-white font-semibold text-xs sm:text-sm transition">
                      Hotline: 0394.234.956
                    </a>
                  </div>
                </div>
              </div>
            </div>

          </div>

          <!-- Nút chuyển trái / phải cách mép hợp lý -->
          <button type="button" onclick="prevSlide()" aria-label="Banner trước" class="absolute left-2 sm:left-4 top-1/2 -translate-y-1/2 z-20 w-7 h-7 sm:w-10 sm:h-10 rounded-full bg-black/35 hover:bg-brand-gold text-white flex items-center justify-center transition">
            <svg class="w-4 h-4 sm:w-5 sm:h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2.5" d="M15 19l-7-7 7-7"/></svg>
          </button>
          <button type="button" onclick="nextSlide()" aria-label="Banner tiếp theo" class="absolute right-2 sm:right-4 top-1/2 -translate-y-1/2 z-20 w-7 h-7 sm:w-10 sm:h-10 rounded-full bg-black/35 hover:bg-brand-gold text-white flex items-center justify-center transition">
            <svg class="w-4 h-4 sm:w-5 sm:h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2.5" d="M9 5l7 7-7 7"/></svg>
          </button>

          <!-- Chấm chỉ báo 2 banner -->
          <div class="absolute bottom-3 sm:bottom-4 left-1/2 -translate-x-1/2 z-20 flex items-center gap-2">
            <button type="button" onclick="goToSlide(0)" id="dot-0" aria-label="Chọn banner 1" class="w-6 h-2 rounded-full bg-brand-gold transition-all"></button>
            <button type="button" onclick="goToSlide(1)" id="dot-1" aria-label="Chọn banner 2" class="w-2.5 h-2 rounded-full bg-white/50 hover:bg-white transition-all"></button>
          </div>

        </div>
      </div>
    </section>

    <!-- ===================================================================== -->
    <!-- SECTION 2 (UX BUILDER 3 COLUMNS): DỊCH VỤ TIÊU BIỂU (GIỐNG WEB MẪU)   -->
    <!-- ===================================================================== -->
    <section id="linh-vuc" class="py-10 sm:py-14 bg-white">
      <div class="rh-container">
        <div class="text-center mb-7 sm:mb-10">
          <h2 class="text-xl sm:text-2xl lg:text-3xl font-extrabold text-brand-navy uppercase tracking-tight">
            Dịch Vụ Tiêu Biểu
          </h2>
          <div class="w-16 h-1 bg-brand-gold mx-auto mt-2.5 rounded-full"></div>
        </div>

        <div class="grid grid-cols-1 md:grid-cols-3 gap-4 sm:gap-6">
          <!-- Dịch vụ 1: THIẾT KẾ -->
          <div class="rh-card group rounded-xl overflow-hidden border border-slate-200 bg-white shadow-sm hover:shadow-md transition">
            <div class="aspect-[16/10] overflow-hidden bg-slate-100">
              <img
                src="https://drive.google.com/thumbnail?id=1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff&sz=w900"
                alt="Thiết kế kiến trúc Rin House"
                referrerpolicy="no-referrer"
                onerror="handleDriveError(this, '1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff', 'THIET+KE+KIEN+TRUC')"
                class="rh-card-img w-full h-full object-cover"
              >
            </div>
            <div class="p-4 sm:p-5 text-center">
              <h3 class="text-base sm:text-lg font-bold text-brand-navy uppercase mb-1.5 group-hover:text-brand-gold transition">
                Thiết Kế Kiến Trúc
              </h3>
              <p class="text-xs sm:text-sm text-brand-muted leading-relaxed">
                Thiết kế nhà phố, biệt thự, khách sạn, căn hộ và văn phòng tối ưu công năng, ánh sáng tự nhiên và thẩm mỹ bền vững.
              </p>
            </div>
          </div>

          <!-- Dịch vụ 2: THI CÔNG -->
          <div class="rh-card group rounded-xl overflow-hidden border border-slate-200 bg-white shadow-sm hover:shadow-md transition">
            <div class="aspect-[16/10] overflow-hidden bg-slate-100">
              <img
                src="https://drive.google.com/thumbnail?id=1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR&sz=w900"
                alt="Thi công xây dựng trọn gói Rin House"
                referrerpolicy="no-referrer"
                onerror="handleDriveError(this, '1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR', 'THI+CONG+XAY+DUNG')"
                class="rh-card-img w-full h-full object-cover"
              >
            </div>
            <div class="p-4 sm:p-5 text-center">
              <h3 class="text-base sm:text-lg font-bold text-brand-navy uppercase mb-1.5 group-hover:text-brand-gold transition">
                Thi Công Xây Dựng
              </h3>
              <p class="text-xs sm:text-sm text-brand-muted leading-relaxed">
                Thi công phần thô, thi công hoàn thiện và xây nhà trọn gói chìa khóa trao tay, đảm bảo đúng vật tư và tiến độ hợp đồng.
              </p>
            </div>
          </div>

          <!-- Dịch vụ 3: NỘI THẤT -->
          <div class="rh-card group rounded-xl overflow-hidden border border-slate-200 bg-white shadow-sm hover:shadow-md transition">
            <div class="aspect-[16/10] overflow-hidden bg-slate-100">
              <img
                src="https://drive.google.com/thumbnail?id=1Q8VoCbT7s09UNaoI8GNcYdvKpJ2wz78N&sz=w900"
                alt="Thiết kế và thi công nội thất Rin House"
                referrerpolicy="no-referrer"
                onerror="handleDriveError(this, '1Q8VoCbT7s09UNaoI8GNcYdvKpJ2wz78N', 'THI+CONG+NOI+THAT')"
                class="rh-card-img w-full h-full object-cover"
              >
            </div>
            <div class="p-4 sm:p-5 text-center">
              <h3 class="text-base sm:text-lg font-bold text-brand-navy uppercase mb-1.5 group-hover:text-brand-gold transition">
                Hoàn Thiện Nội Thất
              </h3>
              <p class="text-xs sm:text-sm text-brand-muted leading-relaxed">
                Sản xuất và lắp đặt nội thất gỗ đồng bộ cho phòng khách, bếp, phòng ngủ và không gian kinh doanh sang trọng.
              </p>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- ===================================================================== -->
    <!-- SECTION 3 (UX BUILDER 2 COLUMNS + 6 ICON BOXES): GIỚI THIỆU & THẾ MẠNH -->
    <!-- ===================================================================== -->
    <section id="gioi-thieu" class="py-10 sm:py-14 bg-brand-surface border-y border-slate-200/80">
      <div class="rh-container">
        <!-- Giới thiệu công ty -->
        <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 sm:gap-10 items-center mb-10 sm:mb-14">
          <div class="lg:col-span-6">
            <p class="text-xs font-bold uppercase tracking-widest text-brand-gold mb-2">Về Chúng Tôi</p>
            <h2 class="text-xl sm:text-2xl lg:text-3xl font-extrabold text-brand-navy leading-snug mb-4">
              CÔNG TY TNHH XÂY DỰNG RIN HOUSE
            </h2>
            <p class="text-sm sm:text-[15px] text-brand-muted leading-relaxed mb-3.5">
              <strong class="text-brand-navy">RIN HOUSE</strong> chuyên Thiết kế – Xây dựng – Hoàn thiện Nội thất các công trình Nhà phố, Biệt thự, Khách sạn, Căn hộ cho thuê và Văn phòng tại khu vực TP. Đà Nẵng và Quảng Nam.
            </p>
            <p class="text-sm sm:text-[15px] text-brand-muted leading-relaxed mb-5">
              Với phương châm <strong class="text-brand-navy">“Nhà ở Gia đình – Tiêu chuẩn Công trình”</strong>, chúng tôi đặt chữ <strong class="text-brand-gold">TÂM</strong> lên hàng đầu trong từng hạng mục thi công để mỗi ngôi nhà luôn đảm bảo: <em>An toàn – Chất lượng – Tiến độ – Sự hài lòng bền lâu của Chủ đầu tư.</em>
            </p>
            <div class="grid grid-cols-3 gap-3 pt-2 border-t border-slate-200">
              <div class="bg-white rounded-lg p-3 border border-slate-200/80 text-center">
                <div class="text-lg sm:text-2xl font-extrabold text-brand-navy">100%</div>
                <div class="text-[11px] sm:text-xs text-brand-muted mt-0.5">Vật tư chuẩn</div>
              </div>
              <div class="bg-white rounded-lg p-3 border border-slate-200/80 text-center">
                <div class="text-lg sm:text-2xl font-extrabold text-brand-gold">24/7</div>
                <div class="text-[11px] sm:text-xs text-brand-muted mt-0.5">Tư vấn tận tâm</div>
              </div>
              <div class="bg-white rounded-lg p-3 border border-slate-200/80 text-center">
                <div class="text-lg sm:text-2xl font-extrabold text-brand-navy">5 Năm</div>
                <div class="text-[11px] sm:text-xs text-brand-muted mt-0.5">Bảo hành kết cấu</div>
              </div>
            </div>
          </div>

          <div class="lg:col-span-6">
            <div class="rounded-xl overflow-hidden shadow-md border border-slate-200 bg-white">
              <img
                src="https://drive.google.com/thumbnail?id=1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv&sz=w1000"
                alt="Thi công công trình thực tế Công ty TNHH Xây Dựng Rin House"
                referrerpolicy="no-referrer"
                onerror="handleDriveError(this, '1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv', 'CONG+TY+XAY+DUNG+RIN+HOUSE')"
                class="w-full h-64 sm:h-80 lg:h-[360px] object-cover"
              >
            </div>
          </div>
        </div>

        <!-- Thế mạnh của Rin House (6 cột Flatsome Icon Box giống mẫu tintruongthinh.com) -->
        <div class="text-center mb-6 sm:mb-8">
          <h3 class="text-lg sm:text-xl lg:text-2xl font-extrabold text-brand-navy uppercase">
            Thế Mạnh Của Chúng Tôi
          </h3>
          <div class="w-14 h-1 bg-brand-gold mx-auto mt-2 rounded-full"></div>
        </div>

        <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-4 sm:gap-5">
          <div class="bg-white p-5 rounded-xl border border-slate-200 shadow-sm">
            <div class="w-10 h-10 rounded-lg bg-brand-navy text-brand-gold flex items-center justify-center mb-3">
              <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 20h5v-2a3 3 0 00-5.356-1.857M17 20H7m10 0v-2c0-.656-.126-1.283-.356-1.857M7 20H2v-2a3 3 0 015.356-1.857M7 20v-2c0-.656.126-1.283.356-1.857m0 0a5.002 5.002 0 019.288 0M15 7a3 3 0 11-6 0 3 3 0 016 0z"/></svg>
            </div>
            <h4 class="text-sm sm:text-base font-bold text-brand-navy mb-1.5">Đội ngũ kiến trúc sư, kỹ sư chuyên nghiệp</h4>
            <p class="text-xs sm:text-sm text-brand-muted leading-relaxed">Kiến trúc sư sáng tạo cùng kỹ sư giám sát hiện trường giàu kinh nghiệm và đội thợ lành nghề trực tiếp thi công.</p>
          </div>

          <div class="bg-white p-5 rounded-xl border border-slate-200 shadow-sm">
            <div class="w-10 h-10 rounded-lg bg-brand-navy text-brand-gold flex items-center justify-center mb-3">
              <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9.663 17h4.673M12 3v1m6.364 1.636l-.707.707M21 12h-1M4 12H3m3.343-5.657l-.707-.707m2.828 9.9a5 5 0 117.072 0l-.548.547A3.374 3.374 0 0014 18.469V19a2 2 0 11-4 0v-.531c0-.895-.356-1.754-.988-2.386l-.548-.547z"/></svg>
            </div>
            <h4 class="text-sm sm:text-base font-bold text-brand-navy mb-1.5">Cập nhật xu hướng thiết kế hiện đại</h4>
            <p class="text-xs sm:text-sm text-brand-muted leading-relaxed">Liên tục cải tiến giải pháp kiến trúc, vật liệu mới và biện pháp thi công tiên tiến phù hợp khí hậu miền Trung.</p>
          </div>

          <div class="bg-white p-5 rounded-xl border border-slate-200 shadow-sm">
            <div class="w-10 h-10 rounded-lg bg-brand-navy text-brand-gold flex items-center justify-center mb-3">
              <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z"/></svg>
            </div>
            <h4 class="text-sm sm:text-base font-bold text-brand-navy mb-1.5">Giám sát tiến độ chuẩn xác</h4>
            <p class="text-xs sm:text-sm text-brand-muted leading-relaxed">Báo cáo hình ảnh công trường thường xuyên, nghiệm thu từng giai đoạn rõ ràng giúp chủ nhà an tâm theo dõi từ xa.</p>
          </div>

          <div class="bg-white p-5 rounded-xl border border-slate-200 shadow-sm">
            <div class="w-10 h-10 rounded-lg bg-brand-navy text-brand-gold flex items-center justify-center mb-3">
              <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m5.618-4.016A11.955 11.955 0 0112 2.944a11.955 11.955 0 01-8.618 3.04A12.02 12.02 0 003 9c0 5.591 3.824 10.29 9 11.622 5.176-1.332 9-6.03 9-11.622 0-1.042-.133-2.052-.382-3.016z"/></svg>
            </div>
            <h4 class="text-sm sm:text-base font-bold text-brand-navy mb-1.5">Bảo hành công trình lâu dài</h4>
            <p class="text-xs sm:text-sm text-brand-muted leading-relaxed">Chế độ bảo hành kết cấu và chống thấm dài hạn, hỗ trợ bảo trì nhanh chóng với tinh thần trách nhiệm cao nhất.</p>
          </div>

          <div class="bg-white p-5 rounded-xl border border-slate-200 shadow-sm">
            <div class="w-10 h-10 rounded-lg bg-brand-navy text-brand-gold flex items-center justify-center mb-3">
              <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 8c-1.657 0-3 .895-3 2s1.343 2 3 2 3 .895 3 2-1.343 2-3 2m0-8c1.11 0 2.08.402 2.599 1M12 8V7m0 1v8m0 0v1m0-1c-1.11 0-2.08-.402-2.599-1M21 12a9 9 0 11-18 0 9 9 0 0118 0z"/></svg>
            </div>
            <h4 class="text-sm sm:text-base font-bold text-brand-navy mb-1.5">Chi phí hợp lý, không phát sinh</h4>
            <p class="text-xs sm:text-sm text-brand-muted leading-relaxed">Dự toán chi tiết từng hạng mục ngay từ đầu, cân đối ngân sách tối ưu và cam kết không phát sinh chi phí ẩn.</p>
          </div>

          <div class="bg-white p-5 rounded-xl border border-slate-200 shadow-sm">
            <div class="w-10 h-10 rounded-lg bg-brand-navy text-brand-gold flex items-center justify-center mb-3">
              <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M18.364 5.636l-3.536 3.536m0 5.656l3.536 3.536M9.172 9.172L5.636 5.636m3.536 9.192l-3.536 3.536M21 12a9 9 0 11-18 0 9 9 0 0118 0zm-5 0a4 4 0 11-8 0 4 4 0 018 0z"/></svg>
            </div>
            <h4 class="text-sm sm:text-base font-bold text-brand-navy mb-1.5">Hỗ trợ tư vấn miễn phí 24/7</h4>
            <p class="text-xs sm:text-sm text-brand-muted leading-relaxed">Tư vấn pháp lý, xin giấy phép xây dựng, thiết kế sơ bộ và bóc tách dự toán hoàn toàn miễn phí cho khách hàng.</p>
          </div>
        </div>
      </div>
    </section>

    <!-- ===================================================================== -->
    <!-- SECTION 4 (UX BUILDER GRID): CÔNG TRÌNH THỰC TẾ & SẢN PHẨM THI CÔNG   -->
    <!-- 9 ẢNH THỰC TẾ GOOGLE DRIVE - 2 CỘT TRÊN MOBILE - KHÔNG NHÃN DÁN       -->
    <!-- ===================================================================== -->
    <section id="cong-trinh-thuc-te" class="py-10 sm:py-14 bg-white">
      <div class="rh-container">
        <div class="text-center mb-5 sm:mb-7">
          <h2 class="text-xl sm:text-2xl lg:text-3xl font-extrabold text-brand-navy uppercase tracking-tight">
            Công Trình Thực Tế &amp; Hạng Mục Thi Công
          </h2>
          <div class="w-16 h-1 bg-brand-gold mx-auto mt-2.5 rounded-full"></div>
          <p class="text-xs sm:text-sm text-brand-muted mt-2.5 max-w-2xl mx-auto">
            Hình ảnh thực tế quá trình thi công xây dựng phần thô, hoàn thiện và bàn giao công trình của đội ngũ kỹ sư Rin House.
          </p>
        </div>

        <!-- Thanh danh mục lọc nhỏ gọn: tên danh mục viết liền không xuống dòng, tối ưu trên PC & Mobile -->
        <div id="workCategoryTabs" class="flex flex-wrap justify-center gap-1.5 sm:gap-2 mb-6 sm:mb-8">
          <button type="button" onclick="filterWorks('all')" data-cat="all" class="work-tab whitespace-nowrap px-3 py-1.5 rounded-lg text-[11px] sm:text-xs font-semibold bg-brand-navy text-white border border-brand-navy transition">
            Tất cả
          </button>
          <button type="button" onclick="filterWorks('thi-cong-tho')" data-cat="thi-cong-tho" class="work-tab whitespace-nowrap px-3 py-1.5 rounded-lg text-[11px] sm:text-xs font-semibold bg-brand-surface text-brand-navy border border-slate-200 hover:border-brand-gold transition">
            Thi công phần thô
          </button>
          <button type="button" onclick="filterWorks('hoan-thien')" data-cat="hoan-thien" class="work-tab whitespace-nowrap px-3 py-1.5 rounded-lg text-[11px] sm:text-xs font-semibold bg-brand-surface text-brand-navy border border-slate-200 hover:border-brand-gold transition">
            Thi công hoàn thiện
          </button>
          <button type="button" onclick="filterWorks('nha-pho')" data-cat="nha-pho" class="work-tab whitespace-nowrap px-3 py-1.5 rounded-lg text-[11px] sm:text-xs font-semibold bg-brand-surface text-brand-navy border border-slate-200 hover:border-brand-gold transition">
            Nhà phố
          </button>
          <button type="button" onclick="filterWorks('biet-thu')" data-cat="biet-thu" class="work-tab whitespace-nowrap px-3 py-1.5 rounded-lg text-[11px] sm:text-xs font-semibold bg-brand-surface text-brand-navy border border-slate-200 hover:border-brand-gold transition">
            Biệt thự
          </button>
          <button type="button" onclick="filterWorks('khach-san-can-ho')" data-cat="khach-san-can-ho" class="work-tab whitespace-nowrap px-3 py-1.5 rounded-lg text-[11px] sm:text-xs font-semibold bg-brand-surface text-brand-navy border border-slate-200 hover:border-brand-gold transition">
            Khách sạn - Căn hộ - Phòng trọ
          </button>
          <button type="button" onclick="filterWorks('van-phong')" data-cat="van-phong" class="work-tab whitespace-nowrap px-3 py-1.5 rounded-lg text-[11px] sm:text-xs font-semibold bg-brand-surface text-brand-navy border border-slate-200 hover:border-brand-gold transition">
            Văn phòng
          </button>
          <button type="button" onclick="filterWorks('noi-that')" data-cat="noi-that" class="work-tab whitespace-nowrap px-3 py-1.5 rounded-lg text-[11px] sm:text-xs font-semibold bg-brand-surface text-brand-navy border border-slate-200 hover:border-brand-gold transition">
            Thi công nội thất
          </button>
        </div>

        <!-- Lưới sản phẩm / công trình thực tế: 2 cột trên điện thoại, 3 cột trên máy tính bảng/máy tính -->
        <div id="worksGrid" class="grid grid-cols-2 md:grid-cols-3 gap-2.5 sm:gap-5">
          <!-- Render tự động bằng JS từ danh sách 9 ảnh thực tế Google Drive -->
        </div>
      </div>
    </section>

    <!-- ===================================================================== -->
    <!-- SECTION 5 (UX BUILDER GRID): DANH MỤC CÁC DỰ ÁN Ở ĐÀ NẴNG             -->
    <!-- 10 ẢNH DỰ ÁN GOOGLE DRIVE - 2 CỘT TRÊN MOBILE - KHÔNG NHÃN DÁN        -->
    <!-- ===================================================================== -->
    <section id="du-an-da-nang" class="py-10 sm:py-14 bg-brand-surface border-y border-slate-200/80">
      <div class="rh-container">
        <div class="text-center mb-5 sm:mb-7">
          <h2 class="text-xl sm:text-2xl lg:text-3xl font-extrabold text-brand-navy uppercase tracking-tight">
            Các Dự Án Tiêu Biểu Tại Đà Nẵng
          </h2>
          <div class="w-16 h-1 bg-brand-gold mx-auto mt-2.5 rounded-full"></div>
          <p class="text-xs sm:text-sm text-brand-muted mt-2.5 max-w-2xl mx-auto">
            Tổng hợp các dự án nhà phố, biệt thự, căn hộ và công trình dân dụng do Rin House thiết kế và thi công tại TP. Đà Nẵng.
          </p>
        </div>

        <!-- Bộ lọc danh mục dự án Đà Nẵng gọn đẹp 1 hàng -->
        <div id="danangTabs" class="flex flex-wrap justify-center gap-1.5 sm:gap-2 mb-6 sm:mb-8">
          <button type="button" onclick="filterDanang('all')" data-dn="all" class="dn-tab whitespace-nowrap px-3 py-1.5 rounded-lg text-[11px] sm:text-xs font-semibold bg-brand-navy text-white border border-brand-navy transition">
            Tất cả dự án Đà Nẵng
          </button>
          <button type="button" onclick="filterDanang('nha-pho')" data-dn="nha-pho" class="dn-tab whitespace-nowrap px-3 py-1.5 rounded-lg text-[11px] sm:text-xs font-semibold bg-white text-brand-navy border border-slate-200 hover:border-brand-gold transition">
            Nhà phố Đà Nẵng
          </button>
          <button type="button" onclick="filterDanang('biet-thu')" data-dn="biet-thu" class="dn-tab whitespace-nowrap px-3 py-1.5 rounded-lg text-[11px] sm:text-xs font-semibold bg-white text-brand-navy border border-slate-200 hover:border-brand-gold transition">
            Biệt thự Đà Nẵng
          </button>
          <button type="button" onclick="filterDanang('can-ho')" data-dn="can-ho" class="dn-tab whitespace-nowrap px-3 py-1.5 rounded-lg text-[11px] sm:text-xs font-semibold bg-white text-brand-navy border border-slate-200 hover:border-brand-gold transition">
            Căn hộ - Khách sạn
          </button>
          <button type="button" onclick="filterDanang('noi-that')" data-dn="noi-that" class="dn-tab whitespace-nowrap px-3 py-1.5 rounded-lg text-[11px] sm:text-xs font-semibold bg-white text-brand-navy border border-slate-200 hover:border-brand-gold transition">
            Thiết kế nội thất
          </button>
        </div>

        <!-- Lưới 10 dự án Đà Nẵng: 2 cột mobile, 4-5 cột desktop gọn đẹp -->
        <div id="danangGrid" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-5 gap-2.5 sm:gap-4">
          <!-- Render tự động bằng JS từ danh sách 10 ảnh dự án Đà Nẵng Google Drive -->
        </div>
      </div>
    </section>

    <!-- ===================================================================== -->
    <!-- SECTION 6 (UX BUILDER 4 COLUMNS): BÁO GIÁ DỊCH VỤ XÂY DỰNG            -->
    <!-- ===================================================================== -->
    <section id="bao-gia" class="py-10 sm:py-14 bg-white">
      <div class="rh-container">
        <div class="text-center mb-7 sm:mb-10">
          <h2 class="text-xl sm:text-2xl lg:text-3xl font-extrabold text-brand-navy uppercase tracking-tight">
            Bảng Giá Tham Khảo 2026
          </h2>
          <div class="w-16 h-1 bg-brand-gold mx-auto mt-2.5 rounded-full"></div>
          <p class="text-xs sm:text-sm text-brand-muted mt-2.5">
            Đơn giá minh bạch, bóc tách chi tiết theo từng hạng mục vật tư tại khu vực TP. Đà Nẵng.
          </p>
        </div>

        <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5 mb-10 sm:mb-12">
          <!-- Gói 1 -->
          <div class="rounded-xl border border-slate-200 bg-brand-surface p-4 sm:p-5 flex flex-col justify-between hover:border-brand-gold transition">
            <div>
              <h3 class="text-xs sm:text-sm font-bold text-brand-navy uppercase mb-2 break-words">Báo Giá Thiết Kế Kiến Trúc</h3>
              <div class="text-lg sm:text-2xl font-extrabold text-brand-gold mb-2">150.000đ<span class="text-xs font-normal text-brand-muted">/m²</span></div>
              <ul class="text-[11px] sm:text-xs text-brand-muted space-y-1.5 mb-4">
                <li>• Phối cảnh 3D mặt tiền &amp; công năng</li>
                <li>• Hồ sơ kết cấu, điện nước MEP</li>
                <li>• Hỗ trợ xin giấy phép xây dựng</li>
              </ul>
            </div>
            <a href="#form-tu-van" class="block text-center py-2 px-3 rounded-lg bg-brand-navy hover:bg-brand-gold text-white text-xs font-semibold transition">
              Yêu cầu báo giá
            </a>
          </div>

          <!-- Gói 2 -->
          <div class="rounded-xl border border-slate-200 bg-brand-surface p-4 sm:p-5 flex flex-col justify-between hover:border-brand-gold transition">
            <div>
              <h3 class="text-xs sm:text-sm font-bold text-brand-navy uppercase mb-2 break-words">Báo Giá Thi Công Phần Thô</h3>
              <div class="text-lg sm:text-2xl font-extrabold text-brand-gold mb-2">3.650.000đ<span class="text-xs font-normal text-brand-muted">/m²</span></div>
              <ul class="text-[11px] sm:text-xs text-brand-muted space-y-1.5 mb-4">
                <li>• Thép Hòa Phát, xi măng chính hãng</li>
                <li>• Nhân công hoàn thiện chuẩn kỹ thuật</li>
                <li>• Bảo hành kết cấu 5 năm</li>
              </ul>
            </div>
            <a href="#form-tu-van" class="block text-center py-2 px-3 rounded-lg bg-brand-navy hover:bg-brand-gold text-white text-xs font-semibold transition">
              Yêu cầu báo giá
            </a>
          </div>

          <!-- Gói 3 -->
          <div class="rounded-xl border border-slate-200 bg-brand-surface p-4 sm:p-5 flex flex-col justify-between hover:border-brand-gold transition">
            <div>
              <h3 class="text-xs sm:text-sm font-bold text-brand-navy uppercase mb-2 break-words">Báo Giá Thi Công Hoàn Thiện</h3>
              <div class="text-lg sm:text-2xl font-extrabold text-brand-gold mb-2">2.400.000đ<span class="text-xs font-normal text-brand-muted">/m²</span></div>
              <ul class="text-[11px] sm:text-xs text-brand-muted space-y-1.5 mb-4">
                <li>• Ốp lát gạch, sơn nước Dulux / Jotun</li>
                <li>• Cửa nhôm Xingfa, thiết bị vệ sinh</li>
                <li>• Trần thạch cao, đèn chiếu sáng</li>
              </ul>
            </div>
            <a href="#form-tu-van" class="block text-center py-2 px-3 rounded-lg bg-brand-navy hover:bg-brand-gold text-white text-xs font-semibold transition">
              Yêu cầu báo giá
            </a>
          </div>

          <!-- Gói 4 -->
          <div class="rounded-xl border-2 border-brand-gold bg-brand-goldSoft/50 p-4 sm:p-5 flex flex-col justify-between">
            <div>
              <h3 class="text-xs sm:text-sm font-bold text-brand-navy uppercase mb-2 break-words">Báo Giá Xây Nhà Trọn Gói</h3>
              <div class="text-lg sm:text-2xl font-extrabold text-brand-navy mb-2">5.950.000đ<span class="text-xs font-normal text-brand-muted">/m²</span></div>
              <ul class="text-[11px] sm:text-xs text-brand-muted space-y-1.5 mb-4">
                <li>• Miễn phí 100% hồ sơ thiết kế</li>
                <li>• Chìa khóa trao tay, không phát sinh</li>
                <li>• Bảo hành chống thấm &amp; kết cấu</li>
              </ul>
            </div>
            <a href="#form-tu-van" class="block text-center py-2 px-3 rounded-lg bg-brand-gold hover:bg-brand-goldHover text-white text-xs font-semibold transition">
              Nhận dự toán ngay
            </a>
          </div>
        </div>

        <!-- =================================================================== -->
        <!-- SECTION 7 (UX BUILDER FORM): FORM YÊU CẦU TƯ VẤN & BÁO GIÁ TRANG CHỦ -->
        <!-- =================================================================== -->
        <div id="form-tu-van" class="rounded-2xl overflow-hidden bg-brand-navy text-white shadow-lg">
          <div class="grid grid-cols-1 lg:grid-cols-12">
            <!-- Cột thông tin tư vấn -->
            <div class="lg:col-span-5 p-6 sm:p-8 lg:p-10 bg-brand-navyDark flex flex-col justify-center">
              <p class="text-xs font-bold uppercase tracking-widest text-brand-gold mb-2">Miễn Phí Tư Vấn</p>
              <h3 class="text-xl sm:text-2xl font-extrabold text-white mb-3 leading-snug">
                ĐĂNG KÝ YÊU CẦU &amp; NHẬN BÁO GIÁ CHI TIẾT
              </h3>
              <p class="text-xs sm:text-sm text-slate-300 leading-relaxed mb-6">
                Để lại thông tin diện tích và nhu cầu xây dựng, kiến trúc sư của Rin House sẽ liên hệ khảo sát và gửi bảng dự toán chi tiết trong vòng 30 phút.
              </p>
              <div class="space-y-3 text-xs sm:text-sm text-slate-200">
                <div class="flex items-start gap-3">
                  <svg class="w-4 h-4 text-brand-gold shrink-0 mt-0.5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"/></svg>
                  <span>Hotline / Zalo: <strong class="text-brand-gold">0394.234.956</strong></span>
                </div>
                <div class="flex items-start gap-3">
                  <svg class="w-4 h-4 text-brand-gold shrink-0 mt-0.5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z"/><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 11a3 3 0 11-6 0 3 3 0 016 0z"/></svg>
                  <span>Trụ sở: 202 Bích Khê, Phường Hòa Xuân, TP Đà Nẵng</span>
                </div>
                <div class="flex items-start gap-3">
                  <svg class="w-4 h-4 text-brand-gold shrink-0 mt-0.5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M21 12a9 9 0 01-9 9m9-9a9 9 0 00-9-9m9 9H3m9 9a9 9 0 01-9-9m9 9c1.657 0 3-4.03 3-9s-1.343-9-3-9m0 18c-1.657 0-3-4.03-3-9s1.343-9 3-9"/></svg>
                  <span>Website: rinhouse.com</span>
                </div>
              </div>
            </div>

            <!-- Cột Form nhập liệu -->
            <div class="lg:col-span-7 p-6 sm:p-8 lg:p-10">
              <form id="quoteForm" class="grid grid-cols-1 sm:grid-cols-2 gap-3.5 sm:gap-4" novalidate>
                <div>
                  <label for="qName" class="block text-xs font-semibold text-slate-200 mb-1.5">Họ và tên *</label>
                  <input id="qName" type="text" required placeholder="Nhập họ và tên của bạn" class="w-full px-3.5 py-2.5 rounded-lg bg-white text-brand-ink text-sm focus:outline-none focus:ring-2 focus:ring-brand-gold">
                </div>
                <div>
                  <label for="qPhone" class="block text-xs font-semibold text-slate-200 mb-1.5">Số điện thoại *</label>
                  <input id="qPhone" type="tel" required placeholder="VD: 0394.234.956" class="w-full px-3.5 py-2.5 rounded-lg bg-white text-brand-ink text-sm focus:outline-none focus:ring-2 focus:ring-brand-gold">
                </div>
                <div>
                  <label for="qType" class="block text-xs font-semibold text-slate-200 mb-1.5">Loại công trình</label>
                  <select id="qType" class="w-full px-3.5 py-2.5 rounded-lg bg-white text-brand-ink text-sm focus:outline-none focus:ring-2 focus:ring-brand-gold">
                    <option value="Nhà phố">Nhà phố</option>
                    <option value="Biệt thự">Biệt thự</option>
                    <option value="Khách sạn - Căn hộ cho thuê - Phòng trọ">Khách sạn – Căn hộ – Phòng trọ</option>
                    <option value="Văn phòng">Văn phòng</option>
                    <option value="Cải tạo sửa chữa">Cải tạo sửa chữa</option>
                    <option value="Thi công nội thất">Thi công nội thất</option>
                  </select>
                </div>
                <div>
                  <label for="qBudget" class="block text-xs font-semibold text-slate-200 mb-1.5">Mức đầu tư dự kiến</label>
                  <select id="qBudget" class="w-full px-3.5 py-2.5 rounded-lg bg-white text-brand-ink text-sm focus:outline-none focus:ring-2 focus:ring-brand-gold">
                    <option value="Chưa xác định">Chưa xác định</option>
                    <option value="Dưới 500 triệu">Dưới 500 triệu</option>
                    <option value="500 triệu - 1 tỷ">500 triệu – 1 tỷ</option>
                    <option value="1 tỷ - 2 tỷ">1 tỷ – 2 tỷ</option>
                    <option value="2 tỷ - 3 tỷ">2 tỷ – 3 tỷ</option>
                    <option value="Trên 3 tỷ">Trên 3 tỷ</option>
                  </select>
                </div>
                <div class="sm:col-span-2">
                  <label for="qNote" class="block text-xs font-semibold text-slate-200 mb-1.5">Diện tích &amp; yêu cầu chi tiết</label>
                  <textarea id="qNote" rows="3" placeholder="VD: Xây nhà phố 3 tầng diện tích 5x20m tại Hòa Xuân, Đà Nẵng..." class="w-full px-3.5 py-2.5 rounded-lg bg-white text-brand-ink text-sm focus:outline-none focus:ring-2 focus:ring-brand-gold"></textarea>
                </div>
                <div class="sm:col-span-2 flex flex-col sm:flex-row sm:items-center justify-between gap-3 pt-1">
                  <button type="submit" class="w-full sm:w-auto px-7 py-3 rounded-lg bg-brand-gold hover:bg-brand-goldHover text-white font-bold text-sm transition shadow-md">
                    Gửi Yêu Cầu Báo Giá
                  </button>
                  <span id="formFeedback" class="text-xs text-brand-gold font-medium hidden"></span>
                </div>
              </form>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- ===================================================================== -->
    <!-- SECTION 8 (UX BUILDER BLOG POSTS): DANH MỤC CÁC BÀI VIẾT TRANG CHỦ    -->
    <!-- ===================================================================== -->
    <section id="bai-viet" class="py-10 sm:py-14 bg-brand-surface border-t border-slate-200/80">
      <div class="rh-container">
        <div class="text-center mb-7 sm:mb-9">
          <h2 class="text-xl sm:text-2xl lg:text-3xl font-extrabold text-brand-navy uppercase tracking-tight">
            Tin Tức &amp; Kinh Nghiệm Xây Dựng
          </h2>
          <div class="w-16 h-1 bg-brand-gold mx-auto mt-2.5 rounded-full"></div>
        </div>

        <div id="articlesGrid" class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5">
          <!-- Render tự động bằng JS -->
        </div>
      </div>
    </section>

    <!-- ===================================================================== -->
    <!-- SECTION 9 (UX BUILDER PARTNERS): DANH MỤC CÁC ĐỐI TÁC                 -->
    <!-- ===================================================================== -->
    <section id="doi-tac" class="py-10 sm:py-12 bg-white border-t border-slate-200/80">
      <div class="rh-container">
        <div class="text-center mb-6 sm:mb-8">
          <h2 class="text-lg sm:text-2xl font-extrabold text-brand-navy uppercase tracking-tight">
            Đối Tác Cung Ứng Vật Tư Chiến Lược
          </h2>
          <div class="w-14 h-1 bg-brand-gold mx-auto mt-2 rounded-full"></div>
        </div>

        <div class="grid grid-cols-2 sm:grid-cols-4 lg:grid-cols-8 gap-2.5 sm:gap-3.5">
          <!-- 8 Đối tác vật liệu xây dựng hàng đầu -->
          <div class="h-16 sm:h-20 rounded-xl border border-slate-200 bg-brand-surface flex flex-col items-center justify-center p-2 hover:border-brand-gold transition">
            <span class="text-xs sm:text-sm font-extrabold tracking-tight text-brand-navy">HÒA PHÁT</span>
            <span class="text-[9px] text-brand-muted uppercase">Thép xây dựng</span>
          </div>
          <div class="h-16 sm:h-20 rounded-xl border border-slate-200 bg-brand-surface flex flex-col items-center justify-center p-2 hover:border-brand-gold transition">
            <span class="text-xs sm:text-sm font-extrabold tracking-tight text-brand-navy">SÔNG GIANH</span>
            <span class="text-[9px] text-brand-muted uppercase">Xi măng</span>
          </div>
          <div class="h-16 sm:h-20 rounded-xl border border-slate-200 bg-brand-surface flex flex-col items-center justify-center p-2 hover:border-brand-gold transition">
            <span class="text-xs sm:text-sm font-extrabold tracking-tight text-brand-navy">DULUX</span>
            <span class="text-[9px] text-brand-muted uppercase">Sơn cao cấp</span>
          </div>
          <div class="h-16 sm:h-20 rounded-xl border border-slate-200 bg-brand-surface flex flex-col items-center justify-center p-2 hover:border-brand-gold transition">
            <span class="text-xs sm:text-sm font-extrabold tracking-tight text-brand-navy">XINGFA</span>
            <span class="text-[9px] text-brand-muted uppercase">Nhôm kính</span>
          </div>
          <div class="h-16 sm:h-20 rounded-xl border border-slate-200 bg-brand-surface flex flex-col items-center justify-center p-2 hover:border-brand-gold transition">
            <span class="text-xs sm:text-sm font-extrabold tracking-tight text-brand-navy">AN CƯỜNG</span>
            <span class="text-[9px] text-brand-muted uppercase">Gỗ nội thất</span>
          </div>
          <div class="h-16 sm:h-20 rounded-xl border border-slate-200 bg-brand-surface flex flex-col items-center justify-center p-2 hover:border-brand-gold transition">
            <span class="text-xs sm:text-sm font-extrabold tracking-tight text-brand-navy">TOTO</span>
            <span class="text-[9px] text-brand-muted uppercase">Thiết bị vệ sinh</span>
          </div>
          <div class="h-16 sm:h-20 rounded-xl border border-slate-200 bg-brand-surface flex flex-col items-center justify-center p-2 hover:border-brand-gold transition">
            <span class="text-xs sm:text-sm font-extrabold tracking-tight text-brand-navy">CADIVI</span>
            <span class="text-[9px] text-brand-muted uppercase">Dây cáp điện</span>
          </div>
          <div class="h-16 sm:h-20 rounded-xl border border-slate-200 bg-brand-surface flex flex-col items-center justify-center p-2 hover:border-brand-gold transition">
            <span class="text-xs sm:text-sm font-extrabold tracking-tight text-brand-navy">ĐỒNG TÂM</span>
            <span class="text-[9px] text-brand-muted uppercase">Gạch ốp lát</span>
          </div>
        </div>
      </div>
    </section>

    <!-- ===================================================================== -->
    <!-- SECTION 10 (UX BUILDER 2 COLUMNS): GOOGLE MAP & FANPAGE TRANG CHỦ     -->
    <!-- ===================================================================== -->
    <section id="lien-he" class="py-10 sm:py-14 bg-brand-surface border-t border-slate-200">
      <div class="rh-container">
        <div class="text-center mb-7 sm:mb-9">
          <h2 class="text-xl sm:text-2xl lg:text-3xl font-extrabold text-brand-navy uppercase tracking-tight">
            Vị Trí Văn Phòng &amp; Kết Nối Fanpage
          </h2>
          <div class="w-16 h-1 bg-brand-gold mx-auto mt-2.5 rounded-full"></div>
        </div>

        <div class="grid grid-cols-1 lg:grid-cols-12 gap-5 sm:gap-6 items-stretch">
          <!-- Cột Trái: Bản đồ Google Map thực tế đưa ra ngoài trang chủ -->
          <div class="lg:col-span-7 bg-white rounded-xl border border-slate-200 shadow-sm overflow-hidden flex flex-col">
            <div class="px-4 py-3 border-b border-slate-100 flex flex-wrap items-center justify-between gap-2">
              <div class="flex items-center gap-2 text-xs sm:text-sm font-bold text-brand-navy">
                <svg class="w-4 h-4 text-brand-gold shrink-0" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z"/><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 11a3 3 0 11-6 0 3 3 0 016 0z"/></svg>
                <span>202 Bích Khê, Phường Hòa Xuân, TP Đà Nẵng</span>
              </div>
              <a href="https://www.google.com/maps/search/?api=1&query=202+Bich+Khe+Hoa+Xuan+Da+Nang" target="_blank" rel="noopener noreferrer" class="text-xs font-semibold text-brand-gold hover:underline">
                Mở chỉ đường &rarr;
              </a>
            </div>
            <div class="w-full flex-1 min-h-[280px] sm:min-h-[340px]">
              <iframe
                title="Bản đồ Công ty TNHH Xây Dựng Rin House - 202 Bích Khê, Hòa Xuân, Đà Nẵng"
                src="https://maps.google.com/maps?q=202%20B%C3%ADch%20Kh%C3%AA,%20H%C3%B2a%20Xu%C3%A2n,%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=16&ie=UTF8&iwloc=&output=embed"
                class="w-full h-full min-h-[280px] sm:min-h-[340px] border-0"
                loading="lazy"
                referrerpolicy="no-referrer-when-downgrade">
              </iframe>
            </div>
          </div>

          <!-- Cột Phải: Fanpage Facebook đưa ra ngoài trang chủ -->
          <div class="lg:col-span-5 bg-white rounded-xl border border-slate-200 shadow-sm overflow-hidden flex flex-col justify-between">
            <div>
              <!-- Header Fanpage -->
              <div class="px-4 py-3 border-b border-slate-100 flex items-center justify-between">
                <div class="flex items-center gap-2 text-xs sm:text-sm font-bold text-brand-navy">
                  <svg class="w-4 h-4 text-[#1877F2]" fill="currentColor" viewBox="0 0 24 24"><path d="M22 12c0-5.523-4.477-10-10-10S2 6.477 2 12c0 4.991 3.657 9.128 8.438 9.878v-6.987h-2.54V12h2.54V9.797c0-2.506 1.492-3.89 3.777-3.89 1.094 0 2.238.195 2.238.195v2.46h-1.26c-1.243 0-1.63.771-1.63 1.562V12h2.773l-.443 2.89h-2.33v6.988C18.343 21.128 22 16.991 22 12z"/></svg>
                  <span>Fanpage Chính Thức</span>
                </div>
                <span class="text-[11px] text-brand-muted">Facebook</span>
              </div>

              <!-- Ảnh bìa Fanpage lấy từ ảnh thực tế dự án -->
              <div class="relative h-36 sm:h-40 bg-brand-navy overflow-hidden">
                <img
                  src="https://drive.google.com/thumbnail?id=1wkzckXZhRrWh3V2GIOfdqBmOwQTBVFhz&sz=w900"
                  alt="Ảnh bìa Fanpage Rin House"
                  referrerpolicy="no-referrer"
                  onerror="handleDriveError(this, '1wkzckXZhRrWh3V2GIOfdqBmOwQTBVFhz', 'FANPAGE+RIN+HOUSE')"
                  class="w-full h-full object-cover opacity-80"
                >
                <div class="absolute inset-0 bg-gradient-to-t from-brand-navyDark/90 via-brand-navyDark/30 to-transparent"></div>
                <div class="absolute bottom-3 left-4 right-4 flex items-center gap-3">
                  <div class="w-12 h-12 rounded-lg bg-brand-navy border-2 border-white shadow flex items-center justify-center shrink-0">
                    <svg class="w-8 h-8" viewBox="0 0 48 48" fill="none">
                      <path d="M9 24.5L24 11L39 24.5" stroke="#C88A2B" stroke-width="4" stroke-linecap="round" stroke-linejoin="round"/>
                      <path d="M15 23V37H33V23" stroke="#FFFFFF" stroke-width="3" stroke-linecap="round" stroke-linejoin="round"/>
                      <path d="M21 37V28H27V37" fill="#C88A2B"/>
                    </svg>
                  </div>
                  <div class="min-w-0 text-white">
                    <div class="text-sm font-bold leading-tight truncate">Xây Dựng Rin House Đà Nẵng</div>
                    <div class="text-[11px] text-slate-200 truncate">Thiết kế &amp; Thi công trọn gói • Đà Nẵng</div>
                  </div>
                </div>
              </div>

              <!-- Nội dung cập nhật mới trên Fanpage -->
              <div class="p-4 space-y-3">
                <p class="text-xs sm:text-[13px] text-brand-muted leading-relaxed">
                  Theo dõi Fanpage của <strong class="text-brand-navy">CÔNG TY TNHH XÂY DỰNG RIN HOUSE</strong> để cập nhật hình ảnh tiến độ thi công thực tế mỗi ngày, mẫu nhà đẹp Đà Nẵng và chương trình ưu đãi thiết kế mới nhất.
                </p>
                <div class="p-3 rounded-lg bg-brand-surface border border-slate-200/80 text-xs text-brand-ink">
                  <div class="font-semibold text-brand-navy mb-1">Cập nhật công trình thực tế tại Hòa Xuân, Đà Nẵng</div>
                  <p class="text-brand-muted leading-relaxed">Hoàn thiện công tác đổ sàn, chống thấm và lắp đặt hệ cửa nhôm kính theo đúng tiêu chuẩn kỹ thuật bàn giao khách hàng.</p>
                </div>
              </div>
            </div>

            <!-- Nút tương tác Fanpage -->
            <div class="px-4 pb-4 pt-1 flex items-center gap-2.5">
              <a href="https://www.facebook.com/search/top/?q=Xay+Dung+Rin+House+Da+Nang" target="_blank" rel="noopener noreferrer" class="flex-1 inline-flex items-center justify-center gap-1.5 py-2.5 px-3 rounded-lg bg-[#1877F2] hover:bg-[#1465D0] text-white text-xs font-semibold transition">
                <svg class="w-4 h-4" fill="currentColor" viewBox="0 0 24 24"><path d="M22 12c0-5.523-4.477-10-10-10S2 6.477 2 12c0 4.991 3.657 9.128 8.438 9.878v-6.987h-2.54V12h2.54V9.797c0-2.506 1.492-3.89 3.777-3.89 1.094 0 2.238.195 2.238.195v2.46h-1.26c-1.243 0-1.63.771-1.63 1.562V12h2.773l-.443 2.89h-2.33v6.988C18.343 21.128 22 16.991 22 12z"/></svg>
                <span>Thích Fanpage</span>
              </a>
              <a href="https://zalo.me/0394234956" target="_blank" rel="noopener noreferrer" class="flex-1 inline-flex items-center justify-center gap-1.5 py-2.5 px-3 rounded-lg bg-brand-navy hover:bg-brand-gold text-white text-xs font-semibold transition">
                <span>Nhắn Tin Tư Vấn</span>
              </a>
            </div>
          </div>
        </div>
      </div>
    </section>

  </main>

  <!-- ===================================================================== -->
  <!-- FOOTER CHUYÊN NGHIỆP (PHONG CÁCH FLATSOME ĐỒNG BỘ MÀU LOGO)           -->
  <!-- ===================================================================== -->
  <footer class="bg-brand-navyDark text-slate-300 border-t-4 border-brand-gold">
    <div class="rh-container py-10 sm:py-12">
      <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-8">

        <!-- Cột 1: Thông tin doanh nghiệp -->
        <div class="sm:col-span-2 lg:col-span-1">
          <div class="flex items-center gap-2.5 mb-4">
            <svg class="w-9 h-9 shrink-0" viewBox="0 0 48 48" fill="none">
              <rect width="48" height="48" rx="9" fill="#0F2C4C" stroke="#C88A2B" stroke-width="1.5"/>
              <path d="M9 24.5L24 11L39 24.5" stroke="#C88A2B" stroke-width="3.4" stroke-linecap="round" stroke-linejoin="round"/>
              <path d="M15 23V37H33V23" stroke="#FFFFFF" stroke-width="2.6" stroke-linecap="round" stroke-linejoin="round"/>
              <path d="M21 37V27.5H27V37" fill="#C88A2B"/>
            </svg>
            <div class="leading-none">
              <div class="text-base font-extrabold text-white">RIN <span class="text-brand-gold">HOUSE</span></div>
              <div class="text-[9px] tracking-[0.14em] text-slate-400 uppercase mt-1">rinhouse.com</div>
            </div>
          </div>
          <p class="text-xs font-bold text-white uppercase mb-2">CÔNG TY TNHH XÂY DỰNG RIN HOUSE</p>
          <ul class="space-y-2 text-xs text-slate-300 leading-relaxed">
            <li><strong>Trụ sở:</strong> 202 Bích Khê, Phường Hòa Xuân, TP Đà Nẵng</li>
            <li><strong>Hotline / Zalo:</strong> <a href="tel:0394234956" class="text-brand-gold font-semibold hover:underline">0394.234.956</a></li>
            <li><strong>Mã số thuế:</strong> 0402226631</li>
            <li><strong>Website:</strong> rinhouse.com</li>
          </ul>
        </div>

        <!-- Cột 2: Lĩnh vực hoạt động -->
        <div>
          <h4 class="text-xs sm:text-sm font-bold text-white uppercase tracking-wide mb-3 pb-2 border-b border-white/10">
            Lĩnh Vực Hoạt Động
          </h4>
          <ul class="space-y-2 text-xs">
            <li><a href="#linh-vuc" class="hover:text-brand-gold transition">Thiết kế Kiến trúc – Nội thất</a></li>
            <li><a href="#cong-trinh-thuc-te" onclick="filterWorks('thi-cong-tho')" class="hover:text-brand-gold transition">Thi công phần thô</a></li>
            <li><a href="#cong-trinh-thuc-te" onclick="filterWorks('hoan-thien')" class="hover:text-brand-gold transition">Thi công hoàn thiện</a></li>
            <li><a href="#cong-trinh-thuc-te" onclick="filterWorks('noi-that')" class="hover:text-brand-gold transition">Thi công nội thất trọn gói</a></li>
            <li><a href="#bao-gia" class="hover:text-brand-gold transition">Báo giá xây nhà trọn gói</a></li>
          </ul>
        </div>

        <!-- Cột 3: Danh mục công trình -->
        <div>
          <h4 class="text-xs sm:text-sm font-bold text-white uppercase tracking-wide mb-3 pb-2 border-b border-white/10">
            Danh Mục Công Trình
          </h4>
          <ul class="space-y-2 text-xs">
            <li><a href="#cong-trinh-thuc-te" onclick="filterWorks('nha-pho')" class="hover:text-brand-gold transition">Nhà phố hiện đại</a></li>
            <li><a href="#cong-trinh-thuc-te" onclick="filterWorks('biet-thu')" class="hover:text-brand-gold transition">Biệt thự sang trọng</a></li>
            <li><a href="#cong-trinh-thuc-te" onclick="filterWorks('khach-san-can-ho')" class="hover:text-brand-gold transition">Khách sạn – Căn hộ – Phòng trọ</a></li>
            <li><a href="#cong-trinh-thuc-te" onclick="filterWorks('van-phong')" class="hover:text-brand-gold transition">Văn phòng làm việc</a></li>
            <li><a href="#du-an-da-nang" class="hover:text-brand-gold transition">Dự án tiêu biểu tại Đà Nẵng</a></li>
          </ul>
        </div>

        <!-- Cột 4: Cam kết & Hỗ trợ -->
        <div>
          <h4 class="text-xs sm:text-sm font-bold text-white uppercase tracking-wide mb-3 pb-2 border-b border-white/10">
            Hỗ Trợ Khách Hàng
          </h4>
          <p class="text-xs text-slate-300 leading-relaxed mb-3">
            Làm việc tất cả các ngày trong tuần từ 07:30 – 18:00. Tư vấn khảo sát công trình miễn phí tại TP. Đà Nẵng và các khu vực lân cận.
          </p>
          <a href="#form-tu-van" class="inline-flex items-center justify-center px-4 py-2 rounded-lg bg-brand-gold hover:bg-brand-goldHover text-white text-xs font-semibold transition">
            Đăng Ký Tư Vấn Ngay
          </a>
        </div>

      </div>
    </div>

    <div class="border-t border-white/10 bg-black/20">
      <div class="rh-container py-3.5 text-center text-[11px] sm:text-xs text-slate-400">
        Copyright 2026 &copy; <strong class="text-white">CÔNG TY TNHH XÂY DỰNG RIN HOUSE</strong> — rinhouse.com. All rights reserved.
      </div>
    </div>
  </footer>

  <!-- ===================================================================== -->
  <!-- CÁC NÚT LIÊN HỆ NỔI BẬT: ZALO, FACEBOOK, HOTLINE (TƯƠNG THÍCH PC & MOBILE) -->
  <!-- ===================================================================== -->
  <div class="fixed right-3 sm:right-5 bottom-4 sm:bottom-6 z-50 flex flex-col items-end gap-2.5">
    <!-- Nút Facebook -->
    <a href="https://www.facebook.com/search/top/?q=Xay+Dung+Rin+House+Da+Nang" target="_blank" rel="noopener noreferrer" aria-label="Facebook Rin House" class="group flex items-center gap-2 bg-[#1877F2] hover:bg-[#1465D0] text-white rounded-full shadow-lg p-2.5 sm:px-3.5 sm:py-2.5 transition">
      <svg class="w-5 h-5 shrink-0" fill="currentColor" viewBox="0 0 24 24"><path d="M22 12c0-5.523-4.477-10-10-10S2 6.477 2 12c0 4.991 3.657 9.128 8.438 9.878v-6.987h-2.54V12h2.54V9.797c0-2.506 1.492-3.89 3.777-3.89 1.094 0 2.238.195 2.238.195v2.46h-1.26c-1.243 0-1.63.771-1.63 1.562V12h2.773l-.443 2.89h-2.33v6.988C18.343 21.128 22 16.991 22 12z"/></svg>
      <span class="hidden sm:inline text-xs font-bold pr-1">Facebook</span>
    </a>

    <!-- Nút Zalo -->
    <a href="https://zalo.me/0394234956" target="_blank" rel="noopener noreferrer" aria-label="Chat Zalo Rin House" class="group flex items-center gap-2 bg-[#0068FF] hover:bg-[#0055D4] text-white rounded-full shadow-lg p-2.5 sm:px-3.5 sm:py-2.5 transition">
      <span class="w-5 h-5 rounded-full bg-white text-[#0068FF] text-[10px] font-black flex items-center justify-center shrink-0">Zalo</span>
      <span class="hidden sm:inline text-xs font-bold pr-1">Chat Zalo</span>
    </a>

    <!-- Nút Hotline nổi bật có vòng tỏa -->
    <a href="tel:0394234956" aria-label="Gọi Hotline 0394.234.956" class="relative flex items-center gap-2 bg-brand-gold hover:bg-brand-goldHover text-white rounded-full shadow-xl p-2.5 sm:px-4 sm:py-2.5 transition">
      <span class="rh-pulse-ring absolute inset-0 rounded-full bg-brand-gold -z-10"></span>
      <svg class="w-5 h-5 shrink-0" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2.2" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"/></svg>
      <span class="hidden sm:inline text-xs font-extrabold tracking-wide">0394.234.956</span>
    </a>
  </div>

  <!-- ===================================================================== -->
  <!-- MODAL XEM CHI TIẾT HÌNH ẢNH CÔNG TRÌNH / BÀI VIẾT (KHÔNG DÙNG ALERT)  -->
  <!-- ===================================================================== -->
  <div id="detailModal" class="fixed inset-0 z-50 hidden items-center justify-center bg-black/75 p-3 sm:p-6">
    <div class="bg-white rounded-2xl max-w-2xl w-full max-h-[90vh] overflow-y-auto shadow-2xl relative">
      <button type="button" onclick="closeModal()" aria-label="Đóng cửa sổ" class="sticky top-3 float-right mr-3 mt-3 z-10 w-8 h-8 rounded-full bg-brand-navy text-white hover:bg-brand-gold flex items-center justify-center transition">
        <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2.5" d="M6 18L18 6M6 6l12 12"/></svg>
      </button>
      <div id="modalContent" class="p-4 sm:p-6"></div>
    </div>
  </div>

  <!-- ===================================================================== -->
  <!-- JAVASCRIPT ĐIỀU KHIỂN SLIDER, LỌC DANH MỤC, DỮ LIỆU ẢNH GOOGLE DRIVE  -->
  <!-- ===================================================================== -->
  <script>
    /* -----------------------------------------------------------------------
       1. HÀM XỬ LÝ DỰ PHÒNG ẢNH GOOGLE DRIVE ĐỂ LUÔN HIỂN THỊ ỔN ĐỊNH
       ----------------------------------------------------------------------- */
    function handleDriveError(imgEl, fileId, fallbackText) {
      const step = parseInt(imgEl.dataset.errStep || '0', 10);
      if (step === 0) {
        imgEl.dataset.errStep = '1';
        imgEl.src = 'https://lh3.googleusercontent.com/d/' + fileId + '=w1000';
      } else if (step === 1) {
        imgEl.dataset.errStep = '2';
        imgEl.src = 'https://drive.google.com/uc?export=view&id=' + fileId;
      } else {
        imgEl.onerror = null;
        imgEl.src = 'https://placehold.co/800x600/0F2C4C/C88A2B?text=' + fallbackText;
      }
    }

    function driveImgUrl(fileId) {
      return 'https://drive.google.com/thumbnail?id=' + fileId + '&sz=w1000';
    }

    /* -----------------------------------------------------------------------
       2. DỮ LIỆU 9 ẢNH THỰC TẾ THI CÔNG XÂY DỰNG (PHÂN ĐÚNG DANH MỤC MẪU)
       ----------------------------------------------------------------------- */
    const constructionWorks = [
      {
        id: '13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz',
        title: 'Thi Công Phần Thô & Kết Cấu Móng Băng Nhà Phố',
        category: 'thi-cong-tho',
        categoryLabel: 'Thi công phần thô',
        location: 'Hòa Xuân, TP. Đà Nẵng',
        desc: 'Công tác gia công cốt thép, cốp pha và đổ bê tông kết cấu móng đạt chuẩn cường độ thiết kế, nghiệm thu trực tiếp cùng chủ đầu tư.'
      },
      {
        id: '1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR',
        title: 'Thi Công Kết Cấu Khung Cột & Đổ Bê Tông Sàn Tầng',
        category: 'thi-cong-tho',
        categoryLabel: 'Thi công phần thô',
        location: 'Cẩm Lệ, TP. Đà Nẵng',
        desc: 'Lắp dựng giàn giáo, cốt thép sàn 2 lớp đúng bản vẽ kết cấu và bảo dưỡng bê tông liên tục giúp công trình bền chắc vượt thời gian.'
      },
      {
        id: '1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv',
        title: 'Xây Tường Bao & Tô Trát Hoàn Thiện Công Trình Nhà Phố',
        category: 'hoan-thien',
        categoryLabel: 'Thi công hoàn thiện',
        location: 'Hải Châu, TP. Đà Nẵng',
        desc: 'Xây gạch chuẩn mạch, đóng lưới chống nứt vị trí tiếp giáp cột tường và tô trát phẳng tuyệt đối trước công đoạn sơn bả.'
      },
      {
        id: '1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_',
        title: 'Thi Công Trọn Gói Nhà Phố 3 Tầng Mặt Tiền Hiện Đại',
        category: 'nha-pho',
        categoryLabel: 'Nhà phố',
        location: 'Khu Đô Thị Hòa Xuân, Đà Nẵng',
        desc: 'Thi công đồng bộ từ phần thô đến hoàn thiện mặt tiền, tối ưu thông gió tự nhiên và không gian sinh hoạt tiện nghi cho gia đình.'
      },
      {
        id: '1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO',
        title: 'Thi Công Chống Thấm Sân Thượng & Hoàn Thiện Mái Bằng',
        category: 'hoan-thien',
        categoryLabel: 'Thi công hoàn thiện',
        location: 'Ngũ Hành Sơn, TP. Đà Nẵng',
        desc: 'Quy trình xử lý chống thấm đa lớp chuyên sâu kết hợp ngâm thử nước nghiệm thu 48 giờ, ngăn ngừa thấm dột tuyệt đối mùa mưa bão.'
      },
      {
        id: '1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t',
        title: 'Thi Công Biệt Thự Phố & Hoàn Thiện Mặt Dựng Ngoại Thất',
        category: 'biet-thu',
        categoryLabel: 'Biệt thự',
        location: 'Nam Việt Á, TP. Đà Nẵng',
        desc: 'Hoàn thiện kiến trúc ngoại thất sang trọng với hệ sơn phủ chống thời tiết, ốp đá tự nhiên và hệ thống chiếu sáng kiến trúc.'
      },
      {
        id: '1UB12E_spzIvo7TNREjBJXUV9o_HVWOv_',
        title: 'Thi Công Căn Hộ Cho Thuê & Hệ Thống Điện Nước MEP',
        category: 'khach-san-can-ho',
        categoryLabel: 'Khách sạn - Căn hộ - Phòng trọ',
        location: 'Sơn Trà, TP. Đà Nẵng',
        desc: 'Lắp đặt hệ thống cấp thoát nước, điện âm tường, phòng cháy chữa cháy và hoàn thiện chuỗi căn hộ cho thuê chuẩn vận hành.'
      },
      {
        id: '1wHGqk7znpnGmrOjz4_EdpHnHK8xKyxkT',
        title: 'Thi Công Cải Tạo & Hoàn Thiện Không Gian Văn Phòng',
        category: 'van-phong',
        categoryLabel: 'Văn phòng',
        location: 'Thanh Khê, TP. Đà Nẵng',
        desc: 'Thi công vách kính cường lực, trần thạch cao tiêu âm, hệ thống chiếu sáng và sàn hoàn thiện chuyên nghiệp cho khối văn phòng.'
      },
      {
        id: '1-eBgG9wF3I6_gyPir2CmCnwJg4sP7Bnn',
        title: 'Thi Công Hoàn Thiện Nội Thất Gỗ & Bàn Giao Trọn Gói',
        category: 'noi-that',
        categoryLabel: 'Thi công nội thất',
        location: 'Liên Chiểu, TP. Đà Nẵng',
        desc: 'Lắp đặt hoàn thiện tủ bếp, hệ tủ âm tường, ốp lát gạch khổ lớn và bàn giao chìa khóa trao tay đúng tiến độ cam kết.'
      }
    ];

    /* -----------------------------------------------------------------------
       3. DỮ LIỆU 10 ẢNH DỰ ÁN TIÊU BIỂU TẠI ĐÀ NẴNG (GOOGLE DRIVE)
       ----------------------------------------------------------------------- */
    const danangProjects = [
      {
        id: '157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT',
        title: 'Nhà Phố 3 Tầng Hiện Đại – KĐT Hòa Xuân, Đà Nẵng',
        type: 'nha-pho',
        area: '100m² (5x20m)',
        desc: 'Công trình nhà phố 3 tầng phong cách hiện đại với mặt tiền thông thoáng, nhiều mảng xanh và tối ưu ánh sáng tự nhiên tại Hòa Xuân.'
      },
      {
        id: '1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff',
        title: 'Biệt Thự Phố 2 Mặt Tiền – Khu Nam Việt Á, Đà Nẵng',
        type: 'biet-thu',
        area: '180m²',
        desc: 'Thiết kế và thi công trọn gói biệt thự phố 2 mặt tiền sang trọng, đường nét kiến trúc tinh tế kết hợp không gian sân vườn.'
      },
      {
        id: '1wkzckXZhRrWh3V2GIOfdqBmOwQTBVFhz',
        title: 'Nhà Phố Thương Mại – Đường Bích Khê, Hòa Xuân',
        type: 'nha-pho',
        area: '105m²',
        desc: 'Mẫu nhà phố kết hợp ở và kinh doanh với mặt tiền rộng thoáng, hệ cửa kính cường lực cách âm và công năng bố trí khoa học.'
      },
      {
        id: '1I7lc3ghS0tyqh6Pq3xsZTidKsr0oT-8k',
        title: 'Tòa Căn Hộ Dịch Vụ Cao Cấp – Quận Sơn Trà, Đà Nẵng',
        type: 'can-ho',
        area: '150m² x 5 tầng',
        desc: 'Dự án căn hộ cho thuê cao cấp gần biển Mỹ Khê, tối ưu số lượng phòng khai thác và tiện nghi nội thất hiện đại.'
      },
      {
        id: '1Q8VoCbT7s09UNaoI8GNcYdvKpJ2wz78N',
        title: 'Thiết Kế & Thi Công Nội Thất Nhà Phố – Hải Châu',
        type: 'noi-that',
        area: '240m² sàn',
        desc: 'Không gian phòng khách liên thông bếp ăn ấm cúng với vật liệu gỗ công nghiệp chống ẩm cao cấp kết hợp ánh sáng dịu nhẹ.'
      },
      {
        id: '1tkQlfZJTkaSunwOIMhfnzkEG2YHwxhML',
        title: 'Nhà Phố Hiện Đại Có Giếng Trời – Quận Cẩm Lệ',
        type: 'nha-pho',
        area: '95m²',
        desc: 'Giải pháp kiến trúc nhà ống thông minh với khoảng thông tầng trung tâm giúp đối lưu không khí mát mẻ quanh năm.'
      },
      {
        id: '1An7LyMVwj3rhKZlsVnYQ2UrLe48IeTBF',
        title: 'Biệt Thự Vườn Nghỉ Dưỡng – Ngũ Hành Sơn, Đà Nẵng',
        type: 'biet-thu',
        area: '250m²',
        desc: 'Công trình biệt thự sân vườn với hệ mái hiện đại, không gian mở kết nối trực tiếp thiên nhiên và tiểu cảnh thư giãn.'
      },
      {
        id: '1R1Da04pAYI9-NJz1IsAfa7pVKkuK7J-A',
        title: 'Khách Sạn Boutique Mini – Biển Mỹ Khê, Đà Nẵng',
        type: 'can-ho',
        area: '140m² x 6 tầng',
        desc: 'Thiết kế mặt tiền nổi bật, sảnh đón tiếp sang trọng và hệ thống kỹ thuật vận hành chuẩn tiêu chuẩn lưu trú du lịch.'
      },
      {
        id: '1FdQEsiEBrIW5TiN22dvzV5g6amDPp-80',
        title: 'Hoàn Thiện Nội Thất Phòng Khách & Bếp – Hòa Quý',
        type: 'noi-that',
        area: '210m² sàn',
        desc: 'Thi công hoàn thiện nội thất trọn gói đồng bộ tone màu trung tính thanh lịch, đảm bảo thẩm mỹ và công năng lưu trữ.'
      },
      {
        id: '1So_3V4rw1y7lHegiIkYmh2Z9UIdozAL4',
        title: 'Nhà Phố 2 Tầng Mái Hiện Đại – Liên Chiểu, Đà Nẵng',
        type: 'nha-pho',
        area: '100m²',
        desc: 'Mẫu nhà phố 2 tầng tối ưu chi phí cho gia đình trẻ với bố cục 3 phòng ngủ rộng rãi, sân để xe và ban công xanh mát.'
      }
    ];

    /* -----------------------------------------------------------------------
       4. DỮ LIỆU BÀI VIẾT TRANG CHỦ
       ----------------------------------------------------------------------- */
    const articles = [
      {
        title: 'Kinh nghiệm xây nhà trọn gói tại Đà Nẵng không phát sinh chi phí',
        date: '15/11/2026',
        imgId: '157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT',
        excerpt: 'Nắm rõ 5 bước chuẩn bị hồ sơ thiết kế, lựa chọn vật tư và ký kết hợp đồng minh bạch trước khi khởi công xây dựng.',
        content: 'Để xây dựng tổ ấm tại Đà Nẵng mà không lo phát sinh ngân sách, chủ đầu tư nên hoàn thiện hồ sơ thiết kế chi tiết trước khi khởi công, thống nhất bảng chủng loại vật tư phần thô lẫn hoàn thiện ngay trong phụ lục hợp đồng và lựa chọn nhà thầu có kỹ sư giám sát trực tiếp tại công trình như Rin House.'
      },
      {
        title: 'Hướng dẫn bảo dưỡng bê tông móng và sàn đúng tiêu chuẩn kỹ thuật',
        date: '08/11/2026',
        imgId: '13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz',
        excerpt: 'Bảo dưỡng ẩm bê tông trong 7 ngày đầu sau khi đổ là yếu tố then chốt giúp kết cấu đạt cường độ tối đa và hạn chế nứt bề mặt.',
        content: 'Sau khi đổ bê tông từ 4 đến 6 giờ, cần tiến hành che phủ giữ ẩm và tưới nước định kỳ tối thiểu 7 ngày liên tục, đặc biệt trong điều kiện nắng gió tại Đà Nẵng. Điều này giúp quá trình thủy hóa xi măng diễn ra hoàn toàn, tăng độ bền kết cấu và chống thấm tự nhiên cho sàn mái.'
      },
      {
        title: '03 lưu ý quan trọng về chống thấm cho nhà phố miền Trung',
        date: '29/10/2026',
        imgId: '1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO',
        excerpt: 'Khí hậu mưa bão đặc thù đòi hỏi quy trình chống thấm sân thượng, nhà vệ sinh và tường tiếp giáp phải được xử lý kỹ lưỡng ngay từ phần thô.',
        content: 'Các vị trí dễ xảy ra thấm dột nhất gồm sàn sân thượng, khu vực cổ ống thoát sàn, hộp kỹ thuật và tường giáp ranh. Rin House luôn áp dụng quy trình vệ sinh bề mặt, bo góc chân tường, quét 2-3 lớp vật liệu chống thấm chuyên dụng và ngâm thử nước nghiệm thu trước khi cán nền ốp lát.'
      },
      {
        title: 'Xu hướng thiết kế nhà phố thông thoáng kết hợp mảng xanh 2026',
        date: '19/10/2026',
        imgId: '1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff',
        excerpt: 'Tận dụng giếng trời, lam chắn nắng và vật liệu tự nhiên giúp nhà phố Đà Nẵng luôn mát mẻ, tiết kiệm điện năng và giàu sức sống.',
        content: 'Xu hướng kiến trúc nhà phố hiện đại ưu tiên không gian mở, kết nối phòng khách và bếp ăn thông qua khoảng sân vườn nhỏ hoặc giếng trời giữa nhà. Kết hợp hệ cửa kính lớn lấy sáng cùng ban công trồng cây xanh tạo nên môi trường sống khỏe mạnh và thư giãn cho cả gia đình.'
      }
    ];

    /* -----------------------------------------------------------------------
       5. RENDER LƯỚI CÔNG TRÌNH THỰC TẾ (2 CỘT MOBILE, KHÔNG NHÃN DÁN, KHÔNG CẮT CHỮ)
       ----------------------------------------------------------------------- */
    function renderWorks(filterCat = 'all') {
      const grid = document.getElementById('worksGrid');
      const items = filterCat === 'all'
        ? constructionWorks
        : constructionWorks.filter(item => item.category === filterCat);

      grid.innerHTML = items.map((item, idx) => `
        <article onclick="openWorkModal('${item.id}')" class="rh-card cursor-pointer group rounded-xl overflow-hidden border border-slate-200 bg-white shadow-sm hover:shadow-md transition flex flex-col">
          <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
            <img
              src="${driveImgUrl(item.id)}"
              alt="${item.title}"
              loading="lazy"
              referrerpolicy="no-referrer"
              onerror="handleDriveError(this, '${item.id}', 'CONG+TRINH+RIN+HOUSE')"
              class="rh-card-img w-full h-full object-cover"
            >
          </div>
          <div class="p-2.5 sm:p-4 flex-1 flex flex-col justify-between">
            <h3 class="text-[12px] sm:text-[14px] font-bold text-brand-navy leading-snug break-words group-hover:text-brand-gold transition">
              ${item.title}
            </h3>
            <div class="mt-2 pt-2 border-t border-slate-100 flex items-center justify-between gap-1 text-[10.5px] sm:text-xs text-brand-muted">
              <span class="break-words">${item.location}</span>
              <span class="text-brand-gold font-semibold shrink-0">Chi tiết</span>
            </div>
          </div>
        </article>
      `).join('');
    }

    function filterWorks(cat) {
      renderWorks(cat);
      document.querySelectorAll('.work-tab').forEach(btn => {
        if (btn.dataset.cat === cat) {
          btn.className = 'work-tab whitespace-nowrap px-3 py-1.5 rounded-lg text-[11px] sm:text-xs font-semibold bg-brand-navy text-white border border-brand-navy transition';
        } else {
          btn.className = 'work-tab whitespace-nowrap px-3 py-1.5 rounded-lg text-[11px] sm:text-xs font-semibold bg-brand-surface text-brand-navy border border-slate-200 hover:border-brand-gold transition';
        }
      });
    }

    /* -----------------------------------------------------------------------
       6. RENDER LƯỚI DỰ ÁN ĐÀ NẴNG (10 ẢNH, 2 CỘT MOBILE, KHÔNG NHÃN DÁN, KHÔNG CẮT CHỮ)
       ----------------------------------------------------------------------- */
    function renderDanang(filterType = 'all') {
      const grid = document.getElementById('danangGrid');
      const items = filterType === 'all'
        ? danangProjects
        : danangProjects.filter(item => item.type === filterType);

      grid.innerHTML = items.map(item => `
        <article onclick="openDanangModal('${item.id}')" class="rh-card cursor-pointer group rounded-xl overflow-hidden border border-slate-200 bg-white shadow-sm hover:shadow-md transition flex flex-col">
          <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
            <img
              src="${driveImgUrl(item.id)}"
              alt="${item.title}"
              loading="lazy"
              referrerpolicy="no-referrer"
              onerror="handleDriveError(this, '${item.id}', 'DU+AN+DA+NANG')"
              class="rh-card-img w-full h-full object-cover"
            >
          </div>
          <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
            <h3 class="text-[12px] sm:text-[13px] font-bold text-brand-navy leading-snug break-words group-hover:text-brand-gold transition">
              ${item.title}
            </h3>
            <div class="mt-2 text-[10.5px] sm:text-xs text-brand-muted">
              Quy mô: <span class="text-brand-ink font-medium">${item.area}</span>
            </div>
          </div>
        </article>
      `).join('');
    }

    function filterDanang(type) {
      renderDanang(type);
      document.querySelectorAll('.dn-tab').forEach(btn => {
        if (btn.dataset.dn === type) {
          btn.className = 'dn-tab whitespace-nowrap px-3 py-1.5 rounded-lg text-[11px] sm:text-xs font-semibold bg-brand-navy text-white border border-brand-navy transition';
        } else {
          btn.className = 'dn-tab whitespace-nowrap px-3 py-1.5 rounded-lg text-[11px] sm:text-xs font-semibold bg-white text-brand-navy border border-slate-200 hover:border-brand-gold transition';
        }
      });
    }

    /* -----------------------------------------------------------------------
       7. RENDER BÀI VIẾT TRANG CHỦ
       ----------------------------------------------------------------------- */
    function renderArticles() {
      const grid = document.getElementById('articlesGrid');
      grid.innerHTML = articles.map((art, index) => `
        <article onclick="openArticleModal(${index})" class="rh-card cursor-pointer group rounded-xl overflow-hidden border border-slate-200 bg-white shadow-sm hover:shadow-md transition flex flex-col">
          <div class="aspect-[16/10] w-full overflow-hidden bg-slate-100">
            <img
              src="${driveImgUrl(art.imgId)}"
              alt="${art.title}"
              loading="lazy"
              referrerpolicy="no-referrer"
              onerror="handleDriveError(this, '${art.imgId}', 'TIN+TUC+RIN+HOUSE')"
              class="rh-card-img w-full h-full object-cover"
            >
          </div>
          <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
            <div>
              <div class="text-[10.5px] text-brand-gold font-semibold mb-1">${art.date}</div>
              <h3 class="text-[12px] sm:text-sm font-bold text-brand-navy leading-snug break-words group-hover:text-brand-gold transition mb-1.5">
                ${art.title}
              </h3>
              <p class="hidden sm:block text-xs text-brand-muted leading-relaxed">
                ${art.excerpt}
              </p>
            </div>
            <div class="mt-2.5 text-[11px] sm:text-xs font-semibold text-brand-navy group-hover:text-brand-gold">
              Đọc chi tiết &rarr;
            </div>
          </div>
        </article>
      `).join('');
    }

    /* -----------------------------------------------------------------------
       8. MODAL CHI TIẾT CÔNG TRÌNH & BÀI VIẾT
       ----------------------------------------------------------------------- */
    function openModalWithHtml(html) {
      const modal = document.getElementById('detailModal');
      document.getElementById('modalContent').innerHTML = html;
      modal.classList.remove('hidden');
      modal.classList.add('flex');
      document.body.style.overflow = 'hidden';
    }

    function closeModal() {
      const modal = document.getElementById('detailModal');
      modal.classList.add('hidden');
      modal.classList.remove('flex');
      document.body.style.overflow = '';
    }

    function openWorkModal(id) {
      const item = constructionWorks.find(w => w.id === id);
      if (!item) return;
      openModalWithHtml(`
        <img src="${driveImgUrl(item.id)}" alt="${item.title}" referrerpolicy="no-referrer" onerror="handleDriveError(this, '${item.id}', 'RIN+HOUSE')" class="w-full max-h-[380px] object-cover rounded-xl mb-4 bg-slate-100">
        <div class="text-xs font-semibold text-brand-gold uppercase mb-1">${item.categoryLabel} • ${item.location}</div>
        <h3 class="text-lg sm:text-xl font-extrabold text-brand-navy mb-2">${item.title}</h3>
        <p class="text-sm text-brand-muted leading-relaxed mb-5">${item.desc}</p>
        <div class="flex flex-wrap gap-2.5">
          <a href="#form-tu-van" onclick="closeModal()" class="px-5 py-2.5 rounded-lg bg-brand-gold hover:bg-brand-goldHover text-white text-xs sm:text-sm font-semibold transition">Nhận báo giá công trình tương tự</a>
          <a href="tel:0394234956" class="px-5 py-2.5 rounded-lg bg-brand-navy hover:bg-brand-navyDark text-white text-xs sm:text-sm font-semibold transition">Gọi 0394.234.956</a>
        </div>
      `);
    }

    function openDanangModal(id) {
      const item = danangProjects.find(p => p.id === id);
      if (!item) return;
      openModalWithHtml(`
        <img src="${driveImgUrl(item.id)}" alt="${item.title}" referrerpolicy="no-referrer" onerror="handleDriveError(this, '${item.id}', 'DU+AN+DA+NANG')" class="w-full max-h-[380px] object-cover rounded-xl mb-4 bg-slate-100">
        <div class="text-xs font-semibold text-brand-gold uppercase mb-1">Dự án Đà Nẵng • Quy mô: ${item.area}</div>
        <h3 class="text-lg sm:text-xl font-extrabold text-brand-navy mb-2">${item.title}</h3>
        <p class="text-sm text-brand-muted leading-relaxed mb-5">${item.desc}</p>
        <div class="flex flex-wrap gap-2.5">
          <a href="#form-tu-van" onclick="closeModal()" class="px-5 py-2.5 rounded-lg bg-brand-gold hover:bg-brand-goldHover text-white text-xs sm:text-sm font-semibold transition">Yêu cầu tư vấn mẫu này</a>
          <a href="https://zalo.me/0394234956" target="_blank" rel="noopener noreferrer" class="px-5 py-2.5 rounded-lg bg-[#0068FF] text-white text-xs sm:text-sm font-semibold transition">Tư vấn qua Zalo</a>
        </div>
      `);
    }

    function openArticleModal(index) {
      const art = articles[index];
      if (!art) return;
      openModalWithHtml(`
        <img src="${driveImgUrl(art.imgId)}" alt="${art.title}" referrerpolicy="no-referrer" onerror="handleDriveError(this, '${art.imgId}', 'TIN+TUC')" class="w-full max-h-[320px] object-cover rounded-xl mb-4 bg-slate-100">
        <div class="text-xs font-semibold text-brand-gold mb-1">Đăng ngày ${art.date} • RIN HOUSE</div>
        <h3 class="text-lg sm:text-xl font-extrabold text-brand-navy mb-3">${art.title}</h3>
        <p class="text-sm text-brand-ink leading-relaxed mb-3 font-medium">${art.excerpt}</p>
        <p class="text-sm text-brand-muted leading-relaxed mb-5">${art.content}</p>
        <a href="#form-tu-van" onclick="closeModal()" class="inline-block px-5 py-2.5 rounded-lg bg-brand-navy hover:bg-brand-gold text-white text-xs sm:text-sm font-semibold transition">Liên hệ kỹ sư Rin House tư vấn miễn phí</a>
      `);
    }

    document.getElementById('detailModal').addEventListener('click', function(e) {
      if (e.target === this) closeModal();
    });

    /* -----------------------------------------------------------------------
       9. ĐIỀU KHIỂN 2 BANNER TỰ TRƯỢT + HỖ TRỢ VUỐT TRÊN ĐIỆN THOẠI
       ----------------------------------------------------------------------- */
    let currentSlide = 0;
    const totalSlides = 2;
    let slideInterval = null;

    function updateSlideUI() {
      document.querySelectorAll('.rh-hero-slide').forEach((slide, i) => {
        if (i === currentSlide) {
          slide.classList.add('is-active');
          slide.classList.remove('is-inactive');
        } else {
          slide.classList.remove('is-active');
          slide.classList.add('is-inactive');
        }
      });

      for (let i = 0; i < totalSlides; i++) {
        const dot = document.getElementById('dot-' + i);
        if (!dot) continue;
        if (i === currentSlide) {
          dot.className = 'w-6 h-2 rounded-full bg-brand-gold transition-all';
        } else {
          dot.className = 'w-2.5 h-2 rounded-full bg-white/50 hover:bg-white transition-all';
        }
      }
    }

    function nextSlide() {
      currentSlide = (currentSlide + 1) % totalSlides;
      updateSlideUI();
      resetAutoSlide();
    }

    function prevSlide() {
      currentSlide = (currentSlide - 1 + totalSlides) % totalSlides;
      updateSlideUI();
      resetAutoSlide();
    }

    function goToSlide(idx) {
      currentSlide = idx;
      updateSlideUI();
      resetAutoSlide();
    }

    function resetAutoSlide() {
      clearInterval(slideInterval);
      slideInterval = setInterval(() => {
        currentSlide = (currentSlide + 1) % totalSlides;
        updateSlideUI();
      }, 5000);
    }

    // Hỗ trợ vuốt cảm ứng trên điện thoại cho Slider
    let touchStartX = 0;
    const sliderEl = document.getElementById('heroSlider');
    sliderEl.addEventListener('touchstart', (e) => {
      touchStartX = e.changedTouches[0].screenX;
    }, { passive: true });
    sliderEl.addEventListener('touchend', (e) => {
      const diff = e.changedTouches[0].screenX - touchStartX;
      if (Math.abs(diff) > 45) {
        if (diff < 0) nextSlide();
        else prevSlide();
      }
    }, { passive: true });

    /* -----------------------------------------------------------------------
       10. MENU ĐIỆN THOẠI & XỬ LÝ FORM BÁO GIÁ (KHÔNG DÙNG ALERT)
       ----------------------------------------------------------------------- */
    const mobileBtn = document.getElementById('mobileMenuBtn');
    const mobileMenu = document.getElementById('mobileMenu');
    mobileBtn.addEventListener('click', () => {
      mobileMenu.classList.toggle('hidden');
    });
    document.querySelectorAll('.mobile-link').forEach(link => {
      link.addEventListener('click', () => mobileMenu.classList.add('hidden'));
    });

    document.getElementById('quoteForm').addEventListener('submit', function(e) {
      e.preventDefault();
      const name = document.getElementById('qName').value.trim();
      const phone = document.getElementById('qPhone').value.trim();
      const feedback = document.getElementById('formFeedback');

      if (!name || !phone) {
        feedback.textContent = 'Vui lòng nhập đầy đủ Họ tên và Số điện thoại để Rin House liên hệ.';
        feedback.className = 'text-xs text-amber-300 font-medium block';
        return;
      }

      feedback.textContent = 'Cảm ơn ' + name + '! Yêu cầu báo giá đã được ghi nhận. Kỹ sư Rin House sẽ gọi lại qua số ' + phone + ' sớm nhất.';
      feedback.className = 'text-xs text-emerald-300 font-semibold block';
      this.reset();
    });

    /* -----------------------------------------------------------------------
       11. KHỞI TẠO TOÀN BỘ GIAO DIỆN KHI TẢI TRANG
       ----------------------------------------------------------------------- */
    document.addEventListener('DOMContentLoaded', () => {
      renderWorks('all');
      renderDanang('all');
      renderArticles();
      updateSlideUI();
      resetAutoSlide();
    });
  </script>
</body>
</html>
