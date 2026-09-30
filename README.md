# CATALOGO-DE-LUMINARIAS
LANDING PAGE DE LUMINARIAS
<!DOCTYPE html>

<html class="scroll-smooth" lang="es"><head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<title>LUMINA Atelier — Catálogo de Iluminación Arquitectónica</title>
<link href="https://fonts.googleapis.com" rel="preconnect"/>
<link crossorigin="" href="https://fonts.gstatic.com" rel="preconnect"/>
<link href="https://fonts.googleapis.com/css2?family=EB+Garamond:ital,wght@0,400..700;1,400..700&amp;family=Hanken+Grotesk:ital,wght@0,300..700;1,300..700&amp;family=Space+Mono:ital,wght@0,400;0,700;1,400&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
<script id="tailwind-config">
    tailwind.config = {
      darkMode: "class",
      theme: {
        extend: {
          colors: {
            "on-secondary-container": "#784401",
            "primary-fixed-dim": "#cac6c4",
            "secondary-fixed-dim": "#ffb874",
            "surface-container": "#efeeeb",
            "on-primary-container": "#868382",
            "inverse-surface": "#2f312f",
            "surface-container-low": "#f4f3f1",
            "surface-tint": "#605e5c",
            "on-surface-variant": "#4a4640",
            "on-background": "#1a1918",
            "background": "#faf9f6",
            "surface-container-highest": "#e3e2e0",
            "on-secondary-fixed-variant": "#6a3b00",
            "surface": "#faf9f6",
            "tertiary-fixed": "#ffddba",
            "on-error-container": "#93000a",
            "on-surface": "#1a1918",
            "primary": "#1a1918",
            "surface-bright": "#faf9f6",
            "surface-container-high": "#e9e8e5",
            "on-secondary": "#ffffff",
            "secondary": "#895110",
            "on-tertiary-container": "#b07831",
            "error-container": "#ffdad6",
            "secondary-container": "#ffb46c",
            "on-secondary-fixed": "#2d1600",
            "on-tertiary": "#ffffff",
            "on-primary-fixed-variant": "#484645",
            "inverse-on-surface": "#f2f1ee",
            "primary-container": "#1c1b1a",
            "surface-dim": "#dbdad7",
            "tertiary": "#000000",
            "tertiary-fixed-dim": "#fcba6c",
            "error": "#ba1a1a",
            "outline-variant": "#dcd7cf",
            "primary-fixed": "#e6e2df",
            "on-tertiary-fixed": "#2b1700",
            "tertiary-container": "#2b1700",
            "surface-variant": "#e3e2e0",
            "secondary-fixed": "#ffdcbf",
            "surface-container-lowest": "#ffffff",
            "on-primary": "#ffffff",
            "on-tertiary-fixed-variant": "#663d00",
            "on-primary-fixed": "#1c1b1a",
            "inverse-primary": "#cac6c4",
            "on-error": "#ffffff",
            "outline": "#7b766f"
          },
          fontFamily: {
            "serif": ["EB Garamond", "serif"],
            "sans": ["Hanken Grotesk", "sans-serif"],
            "mono": ["Space Mono", "monospace"]
          }
        }
      }
    };
  </script>
<style>
    body {
      background-color: #faf9f6;
      color: #1a1918;
      font-family: 'Hanken Grotesk', sans-serif;
    }
    .font-serif {
      font-family: 'EB Garamond', serif;
    }
    .font-mono {
      font-family: 'Space Mono', monospace;
    }
  </style>
</head>
<body class="bg-surface text-on-surface antialiased selection:bg-secondary-fixed selection:text-on-secondary-fixed flex flex-col min-h-screen">
<!-- Desktop Top Navigation Header -->
<header class="sticky top-0 w-full z-50 bg-[#faf9f6]/90 backdrop-blur-md border-b border-outline-variant/60 transition-all">
<div class="max-w-7xl mx-auto px-6 lg:px-12 h-20 flex items-center justify-between">
<!-- Brand Logo -->
<a class="flex items-center gap-3 group focus:outline-none" href="#">
<img alt="Lumina Atelier Logo" class="h-9 w-auto object-contain transition-transform group-hover:scale-105 duration-300" src="https://lh3.googleusercontent.com/aida/AEtjO1VmdO7VfGc_DnIdBn0KZi__tnNE4DLFKiliTi0GTx-vNwSWDrQNMtnSa88ar2Su7brIsk7cwj9zHnsIYfxn8JYbVlIk2bWVQ7gwLGPGkr0SQiEHayEahzY__LOSlS2bFLwzC3btXVlbOcWmp8vzvLn9AKf073pmUdZ28fsbyjid6YP0ZOMq6AjM1HjQEuY6r0MVJncrSreYhqDNtfaeJvSXiO4DAQNxPMoKS_fQOXgmVGomILK_4ezCBVw"/>
<div class="hidden sm:flex flex-col border-l border-outline-variant/80 pl-3">
<span class="font-mono text-[10px] tracking-[0.25em] text-secondary uppercase font-semibold">Atelier d'Art</span>
<span class="font-serif text-sm tracking-wide text-on-surface text-opacity-80">Arquitectura de la Luz</span>
</div>
</a>
<!-- Desktop Navigation Links -->
<nav class="hidden lg:flex items-center gap-8 xl:gap-10">
<a class="text-xs uppercase tracking-[0.18em] font-medium text-on-surface/80 hover:text-secondary transition-colors duration-200" href="#coleccion">Colección</a>
<a class="text-xs uppercase tracking-[0.18em] font-medium text-on-surface/80 hover:text-secondary transition-colors duration-200" href="#luminarias">Luminarias</a>
<a class="text-xs uppercase tracking-[0.18em] font-medium text-on-surface/80 hover:text-secondary transition-colors duration-200" href="#tecnico">Rigor Técnico</a>
<a class="text-xs uppercase tracking-[0.18em] font-medium text-on-surface/80 hover:text-secondary transition-colors duration-200" href="#profesional">Área Profesional</a>
<a class="text-xs uppercase tracking-[0.18em] font-medium text-on-surface/80 hover:text-secondary transition-colors duration-200" href="#manifiesto">Manifiesto</a>
</nav>
<!-- Search & Desktop CTAs -->
<div class="flex items-center gap-4">
<!-- Search Bar -->
<div class="relative hidden md:block">
<span class="material-symbols-outlined absolute left-3 top-1/2 -translate-y-1/2 text-[18px] text-on-surface-variant">search</span>
<input class="pl-9 pr-4 py-1.5 text-xs font-mono bg-surface-container/70 border border-outline-variant/60 rounded-full text-on-surface placeholder:text-on-surface-variant/70 focus:outline-none focus:border-secondary focus:bg-surface w-44 xl:w-56 transition-all" placeholder="Buscar luminaria, CRI, IES..." type="text"/>
</div>
<a class="hidden sm:inline-flex items-center gap-2 px-5 py-2.5 rounded-full bg-primary text-surface text-xs font-mono tracking-wider uppercase hover:bg-secondary transition-all shadow-sm" href="#profesional">
<span>Pedir Muestras</span>
<span class="material-symbols-outlined text-[15px]">arrow_outward</span>
</a>
<!-- User / Catalog Bookmarks -->
<button aria-label="Guardados" class="w-10 h-10 rounded-full border border-outline-variant/60 flex items-center justify-center text-on-surface hover:text-secondary hover:border-secondary transition-colors">
<span class="material-symbols-outlined text-[20px]">bookmark_border</span>
</button>
</div>
</div>
</header>
<main class="flex-grow">
<!-- 1. Editorial Hero Section (Desktop Split Composition) -->
<section class="max-w-7xl mx-auto px-6 lg:px-12 pt-10 pb-20 lg:py-16">
<div class="grid grid-cols-1 lg:grid-cols-12 gap-10 lg:gap-14 items-center">
<!-- Left: Editorial Content & Typography -->
<div class="lg:col-span-5 flex flex-col justify-center">
<div class="flex items-center gap-2 mb-4">
<span class="inline-block w-2 h-2 rounded-full bg-secondary"></span>
<span class="font-mono text-xs text-secondary tracking-[0.2em] uppercase font-semibold">Colección 2025 / Arquitectónica</span>
</div>
<h1 class="font-serif text-4xl sm:text-5xl xl:text-6xl text-on-surface leading-[1.12] tracking-[-0.02em] mb-6">
            La Escultura de la Luz Invisible
          </h1>
<p class="text-base sm:text-lg text-on-surface-variant leading-relaxed font-light mb-8 max-w-xl">
            Nueva serie de luminarias artesanales concebidas para dialogar con el espacio y la materia. Acabados en latón cepillado, travertino poroso y vidrio soplado artesanal.
          </p>
<!-- Technical Photometric Micro Badges -->
<div class="flex flex-wrap items-center gap-2.5 mb-8">
<div class="inline-flex items-center gap-2 px-3.5 py-1.5 bg-surface-container rounded-md border border-outline-variant/50 font-mono text-xs text-on-surface">
<span class="material-symbols-outlined text-[16px] text-secondary">flare</span>
<span>CRI &gt; 98 Museo</span>
</div>
<div class="inline-flex items-center gap-2 px-3.5 py-1.5 bg-surface-container rounded-md border border-outline-variant/50 font-mono text-xs text-on-surface">
<span class="material-symbols-outlined text-[16px] text-secondary">thermostat</span>
<span>2700K Cálido</span>
</div>
<div class="inline-flex items-center gap-2 px-3.5 py-1.5 bg-surface-container rounded-md border border-outline-variant/50 font-mono text-xs text-on-surface">
<span class="material-symbols-outlined text-[16px] text-secondary">tune</span>
<span>DALI-2 / Casambi</span>
</div>
</div>
<!-- CTAs -->
<div class="flex flex-col sm:flex-row items-stretch sm:items-center gap-3">
<a class="px-7 py-3.5 bg-primary text-surface font-mono text-xs tracking-[0.15em] uppercase rounded flex items-center justify-center gap-2 hover:bg-secondary transition-colors duration-200 text-center" href="#luminarias">
<span>Explorar Catálogo</span>
<span class="material-symbols-outlined text-[18px]">arrow_downward</span>
</a>
<a class="px-6 py-3.5 bg-surface-container-low hover:bg-surface-container text-on-surface font-mono text-xs tracking-[0.15em] uppercase rounded border border-outline-variant/70 flex items-center justify-center gap-2 transition-colors duration-200 text-center" href="#profesional">
<span class="material-symbols-outlined text-[18px] text-secondary">file_download</span>
<span>Catálogo PDF (48MB)</span>
</a>
</div>
</div>
<!-- Right: Uncropped Framed Luminaire Photography -->
<div class="lg:col-span-7">
<div class="relative bg-surface-container-low rounded-2xl p-3 sm:p-4 border border-outline-variant/70 shadow-sm group">
<div class="relative overflow-hidden rounded-xl bg-[#e9e6e0] aspect-[4/3] sm:aspect-[16/11] w-full flex items-center justify-center">
<img alt="Aura Pendant Light en latón y alabastro suspendida sobre mesa de comedor de roble y hormigón visto" class="w-full h-full object-cover sm:object-cover transition-transform duration-700 ease-out group-hover:scale-[1.02]" src="https://lh3.googleusercontent.com/aida/AEtjO1VR0BXeE2vTek-06LXBdlvnkrBd4-6QQXTSZhFLk03dsmopOTX3OtwQn7UvHu74DVfVuu50gZdiCq10QG1PxwD9J-KnYTmC4_UpdhWmDUQ39V4Q9CFlZM2wxK4c6qqFDNmcFE95QPJS-Sy92zfEXil72zAT9AosPyKHXyoh75fK9WZddJeB7k9-vywjSp-eG3BVM2coGMoWtAuiaD_gYxDNypsmQZhtxSF5hb5Pq8stz2juL17EYSdfWl5B"/>
<div class="absolute inset-0 bg-gradient-to-t from-black/70 via-black/10 to-transparent pointer-events-none"></div>
<!-- Floating Image Meta -->
<div class="absolute bottom-5 left-5 right-5 flex items-end justify-between text-white pointer-events-none">
<div>
<span class="font-mono text-xs uppercase tracking-widest text-[#ffdcbf] block drop-shadow-sm">Éthéré No. 01</span>
<h2 class="font-serif text-2xl lg:text-3xl text-white drop-shadow-md">Aura Pendant Light</h2>
<p class="text-xs text-stone-200 mt-0.5">Latón satinado · Vidrio opalino soplado a mano</p>
</div>
<div class="bg-black/40 backdrop-blur-md px-3.5 py-1.5 rounded border border-white/20 font-mono text-xs text-white">
                  2700K · 2200 lm
                </div>
</div>
</div>
<div class="flex items-center justify-between pt-3 px-2 text-[11px] font-mono text-on-surface-variant">
<span>PROYECTO: RESIDENCIA NORDEN, COPENHAGUE</span>
<span>FOTOGRAFÍA DE INTERIORISMO EDITORIAL</span>
</div>
</div>
</div>
</div>
</section>
<!-- 2. Curated Releases Catalog Section (3-Column Desktop Grid) -->
<section class="w-full bg-surface-container-lowest border-y border-outline-variant/60 py-20" id="luminarias">
<div class="max-w-7xl mx-auto px-6 lg:px-12">
<!-- Header & Category Switcher -->
<div class="flex flex-col md:flex-row md:items-end justify-between gap-6 mb-12">
<div>
<span class="font-mono text-xs uppercase text-secondary tracking-[0.2em] font-semibold block mb-2">Colección Permanente</span>
<h2 class="font-serif text-3xl sm:text-4xl text-on-surface">Luminarias de Autor</h2>
</div>
<!-- Category Tabs -->
<div class="flex flex-wrap items-center gap-2" id="collection-filters">
<button class="filter-pill px-4 py-2 bg-primary text-surface font-mono text-xs rounded tracking-wider uppercase transition-colors" data-filter="all">Todos (03)</button>
<button class="filter-pill px-4 py-2 bg-surface-container text-on-surface-variant hover:text-on-surface font-mono text-xs rounded tracking-wider uppercase transition-colors" data-filter="suspension">Suspensión</button>
<button class="filter-pill px-4 py-2 bg-surface-container text-on-surface-variant hover:text-on-surface font-mono text-xs rounded tracking-wider uppercase transition-colors" data-filter="mesa">Mesa &amp; Suelo</button>
<button class="filter-pill px-4 py-2 bg-surface-container text-on-surface-variant hover:text-on-surface font-mono text-xs rounded tracking-wider uppercase transition-colors" data-filter="apliques">Apliques de Pared</button>
</div>
</div>
<!-- 3-Column Desktop Cards Grid -->
<div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
<!-- Product Card 1: Aura Pendant -->
<article class="product-item flex flex-col bg-surface rounded-xl border border-outline-variant/60 overflow-hidden hover:shadow-lg transition-all duration-300 group" data-category="suspension">
<!-- Full Architectural Image Container (Uncropped, 4:3 Proportion) -->
<div class="relative w-full aspect-[4/3] bg-[#f0eee9] overflow-hidden">
<img alt="Aura Pendant - luminaria suspendida en latón cepillado" class="w-full h-full object-cover transition-transform duration-500 group-hover:scale-105" src="https://lh3.googleusercontent.com/aida/AEtjO1VR0BXeE2vTek-06LXBdlvnkrBd4-6QQXTSZhFLk03dsmopOTX3OtwQn7UvHu74DVfVuu50gZdiCq10QG1PxwD9J-KnYTmC4_UpdhWmDUQ39V4Q9CFlZM2wxK4c6qqFDNmcFE95QPJS-Sy92zfEXil72zAT9AosPyKHXyoh75fK9WZddJeB7k9-vywjSp-eG3BVM2coGMoWtAuiaD_gYxDNypsmQZhtxSF5hb5Pq8stz2juL17EYSdfWl5B"/>
<span class="absolute top-4 left-4 px-2.5 py-1 bg-surface/90 backdrop-blur text-on-surface font-mono text-[10px] tracking-widest uppercase rounded border border-outline-variant/40">
                Novedad 2025
              </span>
<button aria-label="Añadir a selección" class="absolute top-4 right-4 w-9 h-9 rounded-full bg-surface/85 backdrop-blur flex items-center justify-center text-on-surface hover:text-secondary shadow-sm transition-colors">
<span class="material-symbols-outlined text-[18px]">bookmark_border</span>
</button>
</div>
<!-- Details -->
<div class="p-6 flex flex-col flex-grow justify-between bg-surface">
<div>
<div class="flex items-baseline justify-between mb-2">
<h3 class="font-serif text-2xl text-on-surface">Aura Pendant</h3>
<span class="font-mono text-sm font-semibold text-secondary">Desde 840 €</span>
</div>
<p class="text-sm text-on-surface-variant font-light mb-4 line-clamp-2">
                  Luminaria suspendida lineal en latón y alabastro. Proyección difusa 360° envolvente y libre de deslumbramiento.
                </p>
<!-- Technical Specification Pill -->
<div class="bg-surface-container-low px-3 py-2 rounded border border-outline-variant/40 font-mono text-[11px] text-on-surface mb-6">
<div class="flex items-center justify-between">
<span>24W LED · 2200 lm</span>
<span class="text-secondary font-medium">Warm Dim</span>
</div>
</div>
</div>
<!-- Actions -->
<div class="pt-3 border-t border-outline-variant/50 flex items-center justify-between">
<a class="font-mono text-xs tracking-wider uppercase text-secondary hover:underline inline-flex items-center gap-1" href="#profesional">
<span>Ficha Técnica</span>
<span class="material-symbols-outlined text-[15px]">description</span>
</a>
<button class="px-4 py-2 bg-primary text-surface font-mono text-xs tracking-wider uppercase rounded hover:bg-secondary transition-colors">
                  Especificar
                </button>
</div>
</div>
</article>
<!-- Product Card 2: Orbita Table Lamp -->
<article class="product-item flex flex-col bg-surface rounded-xl border border-outline-variant/60 overflow-hidden hover:shadow-lg transition-all duration-300 group" data-category="mesa">
<!-- Full Architectural Image Container (Uncropped, 4:3 Proportion) -->
<div class="relative w-full aspect-[4/3] bg-[#f0eee9] overflow-hidden">
<img alt="Orbita Table Lamp - lámpara de sobremesa en mármol travertino con orbe opal luminoso" class="w-full h-full object-cover transition-transform duration-500 group-hover:scale-105" src="https://lh3.googleusercontent.com/aida/AEtjO1VS-xHecsWUoFy1dIrWqg-3IoTl8_luvY5N9P8U65u8ulXpq2OKL4sB7oKE44wwKkfvI5NFBDQ9tMnZyp8TLy8_6_5YNUvEL3es_ATR4uylC-Th_iiopE_-ZfZx36x6ugodlnl5LBSyL-1CKEzm2zlDTjE9J80RyeheBJtysCOji_LOsGhzFVsepu5Otj0EGPWnFaJAjWD6sd5ZyF8eV2A4kh2W2atPgaTk6JKA-awUYT6NM7zzWfOZUVRA"/>
<span class="absolute top-4 left-4 px-2.5 py-1 bg-secondary-fixed text-on-secondary-fixed font-mono text-[10px] tracking-widest uppercase rounded border border-secondary-fixed-dim/40">
                Edición Limitada
              </span>
<button aria-label="Añadir a selección" class="absolute top-4 right-4 w-9 h-9 rounded-full bg-surface/85 backdrop-blur flex items-center justify-center text-on-surface hover:text-secondary shadow-sm transition-colors">
<span class="material-symbols-outlined text-[18px]">bookmark_border</span>
</button>
</div>
<!-- Details -->
<div class="p-6 flex flex-col flex-grow justify-between bg-surface">
<div>
<div class="flex items-baseline justify-between mb-2">
<h3 class="font-serif text-2xl text-on-surface">Orbita Table Lamp</h3>
<span class="font-mono text-sm font-semibold text-secondary">Desde 490 €</span>
</div>
<p class="text-sm text-on-surface-variant font-light mb-4 line-clamp-2">
                  Lámpara de sobremesa en mármol travertino y orbe opal. Silueta táctil orgánica para mesitas, escritorios y plintos.
                </p>
<!-- Technical Specification Pill -->
<div class="bg-surface-container-low px-3 py-2 rounded border border-outline-variant/40 font-mono text-[11px] text-on-surface mb-6">
<div class="flex items-center justify-between">
<span>Touch dimmer · Batería 12h</span>
<span class="text-secondary font-medium">USB-C</span>
</div>
</div>
</div>
<!-- Actions -->
<div class="pt-3 border-t border-outline-variant/50 flex items-center justify-between">
<a class="font-mono text-xs tracking-wider uppercase text-secondary hover:underline inline-flex items-center gap-1" href="#profesional">
<span>Ficha Técnica</span>
<span class="material-symbols-outlined text-[15px]">description</span>
</a>
<button class="px-4 py-2 bg-primary text-surface font-mono text-xs tracking-wider uppercase rounded hover:bg-secondary transition-colors">
                  Especificar
                </button>
</div>
</div>
</article>
<!-- Product Card 3: Eclipse Wall Sconce -->
<article class="product-item flex flex-col bg-surface rounded-xl border border-outline-variant/60 overflow-hidden hover:shadow-lg transition-all duration-300 group" data-category="apliques">
<!-- Full Architectural Image Container (Uncropped, 4:3 Proportion) -->
<div class="relative w-full aspect-[4/3] bg-[#f0eee9] overflow-hidden">
<img alt="Eclipse Wall Sconce - aplique de pared escultórico de luz indirecta rasante sobre estuco" class="w-full h-full object-cover transition-transform duration-500 group-hover:scale-105" src="https://lh3.googleusercontent.com/aida/AEtjO1XNaGF5ebPbCQ85V7D-pIo5zn27twVZhlV1yr6or98lnWi7gOrOWPXLJkZEcynw4pwmHPg_uxC_Zs1Dp0qPcssM177ZMKu6ekcsu2g8CP1poBKN0SoFM4f_i79b5Z7Zs89cJNzDUtrnksBOMaYZZz-rIoBlja5ZMtcAaDSmedxhLkZOFs2Q93ddycS2a6_f3xXvehl3PqoYzPzE__8csDNglEhSGi5U-6RLbPHHFh8ND2CyVW5CCjGYemse"/>
<span class="absolute top-4 left-4 px-2.5 py-1 bg-surface/90 backdrop-blur text-on-surface font-mono text-[10px] tracking-widest uppercase rounded border border-outline-variant/40">
                Arquitectura
              </span>
<button aria-label="Añadir a selección" class="absolute top-4 right-4 w-9 h-9 rounded-full bg-surface/85 backdrop-blur flex items-center justify-center text-on-surface hover:text-secondary shadow-sm transition-colors">
<span class="material-symbols-outlined text-[18px]">bookmark_border</span>
</button>
</div>
<!-- Details -->
<div class="p-6 flex flex-col flex-grow justify-between bg-surface">
<div>
<div class="flex items-baseline justify-between mb-2">
<h3 class="font-serif text-2xl text-on-surface">Eclipse Wall Sconce</h3>
<span class="font-mono text-sm font-semibold text-secondary">Desde 360 €</span>
</div>
<p class="text-sm text-on-surface-variant font-light mb-4 line-clamp-2">
                  Aplique de pared escultórico de luz indirecta rasante. Modela el relieve y la textura física del paramento de cal.
                </p>
<!-- Technical Specification Pill -->
<div class="bg-surface-container-low px-3 py-2 rounded border border-outline-variant/40 font-mono text-[11px] text-on-surface mb-6">
<div class="flex items-center justify-between">
<span>IP44 apto baño</span>
<span class="text-secondary font-medium">Difusor Cerámico</span>
</div>
</div>
</div>
<!-- Actions -->
<div class="pt-3 border-t border-outline-variant/50 flex items-center justify-between">
<a class="font-mono text-xs tracking-wider uppercase text-secondary hover:underline inline-flex items-center gap-1" href="#profesional">
<span>Ficha Técnica</span>
<span class="material-symbols-outlined text-[15px]">description</span>
</a>
<button class="px-4 py-2 bg-primary text-surface font-mono text-xs tracking-wider uppercase rounded hover:bg-secondary transition-colors">
                  Especificar
                </button>
</div>
</div>
</article>
</div>
</div>
</section>
<!-- 3. Architectural Excellence & Rigor Fotométrico (Desktop 3-Column Section) -->
<section class="max-w-7xl mx-auto px-6 lg:px-12 py-20 lg:py-24" id="tecnico">
<div class="max-w-2xl mb-12">
<span class="font-mono text-xs uppercase text-secondary tracking-[0.2em] font-semibold block mb-2">Rigor Fotométrico</span>
<h2 class="font-serif text-3xl sm:text-4xl text-on-surface mb-4">Calidad Lumínica sin Compromisos</h2>
<p class="text-base text-on-surface-variant font-light">
          Diseñamos la ingeniería óptica para que pase desapercibida, garantizando confort biológico y reproducción cromática del más alto estándar de conservación.
        </p>
</div>
<div class="grid grid-cols-1 md:grid-cols-3 gap-8">
<!-- Feature 1 -->
<div class="bg-surface-container-low p-8 rounded-xl border border-outline-variant/60 flex flex-col justify-between hover:border-secondary/40 transition-colors">
<div>
<div class="w-12 h-12 rounded-lg bg-surface flex items-center justify-center text-secondary border border-outline-variant/50 mb-6">
<span class="material-symbols-outlined text-[24px]">palette</span>
</div>
<h3 class="font-serif text-xl text-on-surface mb-3">Calidad Cromática Pura (CRI &gt; 98)</h3>
<p class="text-sm text-on-surface-variant font-light leading-relaxed">
              Espectro continuo que reproduce los matices de maderas nobles, estucos de cal y texturas pétreas con la máxima fidelidad exigida en galerías y museos.
            </p>
</div>
<div class="mt-6 pt-4 border-t border-outline-variant/40 font-mono text-[11px] text-secondary">
            R9 &gt; 95 · TM-30 Rf 97 / Rg 100
          </div>
</div>
<!-- Feature 2 -->
<div class="bg-surface-container-low p-8 rounded-xl border border-outline-variant/60 flex flex-col justify-between hover:border-secondary/40 transition-colors">
<div>
<div class="w-12 h-12 rounded-lg bg-surface flex items-center justify-center text-secondary border border-outline-variant/50 mb-6">
<span class="material-symbols-outlined text-[24px]">settings_input_component</span>
</div>
<h3 class="font-serif text-xl text-on-surface mb-3">Integración Domótica Avanzada</h3>
<p class="text-sm text-on-surface-variant font-light leading-relaxed">
              Compatibilidad nativa con sistemas Lutron, KNX, Casambi y regulaciones analógicas 0-10V con curvas logarítmicas ultra-suaves sin parpadeo perceptible.
            </p>
</div>
<div class="mt-6 pt-4 border-t border-outline-variant/40 font-mono text-[11px] text-secondary">
            IEEE 1789 Compliant (Flicker-Free)
          </div>
</div>
<!-- Feature 3 -->
<div class="bg-surface-container-low p-8 rounded-xl border border-outline-variant/60 flex flex-col justify-between hover:border-secondary/40 transition-colors">
<div>
<div class="w-12 h-12 rounded-lg bg-surface flex items-center justify-center text-secondary border border-outline-variant/50 mb-6">
<span class="material-symbols-outlined text-[24px]">eco</span>
</div>
<h3 class="font-serif text-xl text-on-surface mb-3">Materialidad Sostenible</h3>
<p class="text-sm text-on-surface-variant font-light leading-relaxed">
              Ensamblado a mano en Europa con metales nobles reciclados, alabastro español y vidrio soplado artesanal libre de plomo, concebidos para durar décadas.
            </p>
</div>
<div class="mt-6 pt-4 border-t border-outline-variant/40 font-mono text-[11px] text-secondary">
            Garantía de Atelier 10 Años
          </div>
</div>
</div>
</section>
<!-- 4. Trade & Architecture Partnership Banner (Desktop Landscape View) -->
<section class="max-w-7xl mx-auto px-6 lg:px-12 pb-20" id="profesional">
<div class="relative bg-primary-container text-surface rounded-2xl p-8 lg:p-14 overflow-hidden border border-outline-variant/20 shadow-xl">
<!-- Ambient Warm Glow Backdrop -->
<div class="absolute -right-20 -top-20 w-96 h-96 bg-secondary/20 rounded-full blur-3xl pointer-events-none"></div>
<div class="relative z-10 grid grid-cols-1 lg:grid-cols-12 gap-8 items-center">
<div class="lg:col-span-8">
<div class="flex items-center gap-3 mb-4">
<span class="px-3 py-1 bg-surface/10 rounded font-mono text-xs text-[#ffdcbf] tracking-widest uppercase">
                Área Profesional
              </span>
<span class="font-mono text-xs text-[#dcd7cf]/70">BIM / REVIT / CAD / IES PHOTOMETRICS</span>
</div>
<h3 class="font-serif text-3xl sm:text-4xl text-white mb-4">
              Para Estudios de Arquitectura &amp; Interiorismo
            </h3>
<p class="text-stone-300 font-light text-base sm:text-lg mb-8 max-w-2xl leading-relaxed">
              Disponemos de librería técnica completa para tus renders y planos de prescripción. Solicita el muestrario físico 1:1 de acabados metálicos y minerales para tu atelier.
            </p>
<!-- Mini Swatch Visual Indicator -->
<div class="flex flex-wrap items-center gap-4">
<span class="text-xs font-mono text-[#dcd7cf]/80 uppercase">Muestras físicas de acabado:</span>
<div class="flex items-center gap-3">
<span class="flex items-center gap-1.5 text-xs text-stone-200">
<span class="w-5 h-5 rounded-full bg-[#c4823f] border border-white/30 inline-block shadow-sm"></span>
                  Latón Satinado
                </span>
<span class="flex items-center gap-1.5 text-xs text-stone-200">
<span class="w-5 h-5 rounded-full bg-[#1c1b1a] border border-white/30 inline-block shadow-sm"></span>
                  Bronce Ennegrecido
                </span>
<span class="flex items-center gap-1.5 text-xs text-stone-200">
<span class="w-5 h-5 rounded-full bg-[#e3ded9] border border-white/30 inline-block shadow-sm"></span>
                  Travertino Romano
                </span>
<span class="flex items-center gap-1.5 text-xs text-stone-200">
<span class="w-5 h-5 rounded-full bg-[#f4f0ea] border border-white/30 inline-block shadow-sm"></span>
                  Alabastro
                </span>
</div>
</div>
</div>
<div class="lg:col-span-4 flex flex-col gap-3">
<button class="w-full py-4 px-6 bg-surface text-primary hover:bg-[#ffdcbf] transition-colors rounded font-mono text-xs tracking-wider uppercase flex items-center justify-center gap-2 font-semibold">
<span>Solicitar Kit de Acabados</span>
<span class="material-symbols-outlined text-[18px]">mail</span>
</button>
<button class="w-full py-3.5 px-6 bg-transparent hover:bg-surface/10 text-surface border border-surface/30 transition-colors rounded font-mono text-xs tracking-wider uppercase flex items-center justify-center gap-2">
<span class="material-symbols-outlined text-[18px]">download</span>
<span>Descargar Archivos BIM / IES</span>
</button>
</div>
</div>
</div>
</section>
<!-- 5. Editorial Philosophy Quote -->
<section class="w-full py-20 bg-surface-container-low border-t border-outline-variant/60 text-center" id="manifiesto">
<div class="max-w-4xl mx-auto px-6">
<span class="material-symbols-outlined text-secondary text-4xl mb-4">format_quote</span>
<blockquote class="font-serif text-2xl sm:text-3xl lg:text-4xl text-on-surface italic leading-relaxed mb-6 font-normal">
          “La luz no solo ilumina un espacio, define la atmósfera de cómo vivimos dentro de él.”
        </blockquote>
<cite class="font-mono text-xs tracking-[0.25em] uppercase text-secondary font-semibold not-italic">
          Atelier Lumina — Manifiesto de Arquitectura &amp; Luz 2025
        </cite>
</div>
</section>
</main>
<!-- Comprehensive Desktop Footer -->
<footer class="w-full bg-[#1c1b1a] text-stone-300 py-16 border-t border-stone-800">
<div class="max-w-7xl mx-auto px-6 lg:px-12">
<div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-5 gap-10 pb-12 border-b border-stone-800">
<!-- Brand Info -->
<div class="lg:col-span-2">
<div class="flex items-center gap-3 mb-4">
<div class="w-7 h-7 rounded-full border border-secondary flex items-center justify-center">
<span class="w-2 h-2 rounded-full bg-secondary"></span>
</div>
<span class="font-serif text-2xl text-white tracking-widest font-semibold">LUMINA</span>
</div>
<p class="text-sm font-light text-stone-400 max-w-sm mb-6 leading-relaxed">
            Taller artesanal de iluminación arquitectónica. Esculturas de luz desarrolladas a medida para residencias singulares, hoteles boutique y espacios contemporáneos.
          </p>
<div class="font-mono text-xs text-stone-500">
            Barcelona · Copenhague · Milán
          </div>
</div>
<!-- Links 1 -->
<div>
<h4 class="font-mono text-xs uppercase tracking-widest text-white mb-4">Catálogo</h4>
<ul class="space-y-2.5 text-sm font-light text-stone-400">
<li><a class="hover:text-secondary transition-colors" href="#luminarias">Luminarias de Suspensión</a></li>
<li><a class="hover:text-secondary transition-colors" href="#luminarias">Lámparas de Sobremesa</a></li>
<li><a class="hover:text-secondary transition-colors" href="#luminarias">Apliques de Textura</a></li>
<li><a class="hover:text-secondary transition-colors" href="#luminarias">Ediciones Numeradas</a></li>
<li><a class="hover:text-secondary transition-colors" href="#profesional">Proyectos a Medida</a></li>
</ul>
</div>
<!-- Links 2 -->
<div>
<h4 class="font-mono text-xs uppercase tracking-widest text-white mb-4">Estudio &amp; Técnica</h4>
<ul class="space-y-2.5 text-sm font-light text-stone-400">
<li><a class="hover:text-secondary transition-colors" href="#tecnico">Filtros Fotométricos CRI 98</a></li>
<li><a class="hover:text-secondary transition-colors" href="#tecnico">Protocolos DALI &amp; KNX</a></li>
<li><a class="hover:text-secondary transition-colors" href="#profesional">Fichas Técnicas PDF</a></li>
<li><a class="hover:text-secondary transition-colors" href="#profesional">Modelos BIM &amp; 3D</a></li>
<li><a class="hover:text-secondary transition-colors" href="#manifiesto">Manifiesto de Taller</a></li>
</ul>
</div>
<!-- Links 3 / Contact -->
<div>
<h4 class="font-mono text-xs uppercase tracking-widest text-white mb-4">Contacto</h4>
<ul class="space-y-2.5 text-sm font-light text-stone-400">
<li>atelier@lumina-lighting.com</li>
<li>+34 93 412 89 00</li>
<li>Carrer de Mallorca 240, Eixample</li>
<li class="pt-2">
<span class="inline-block px-2.5 py-1 bg-stone-800 rounded font-mono text-[11px] text-secondary">
                Visitas con Cita Previa
              </span>
</li>
</ul>
</div>
</div>
<div class="pt-8 flex flex-col sm:flex-row items-center justify-between text-xs font-mono text-stone-500 gap-4">
<div>
          © 2025 LUMINA Atelier S.L. Todos los derechos reservados.
        </div>
<div class="flex items-center gap-6">
<a class="hover:text-stone-300 transition-colors" href="#">Privacidad</a>
<a class="hover:text-stone-300 transition-colors" href="#">Términos de Especificación</a>
<a class="hover:text-stone-300 transition-colors" href="#">Aviso Legal</a>
</div>
</div>
</div>
</footer>
<!-- Filter tabs script -->
<script>
    (function() {
      const filterButtons = document.querySelectorAll('#collection-filters .filter-pill');
      const products = document.querySelectorAll('.product-item');

      filterButtons.forEach(btn => {
        btn.addEventListener('click', () => {
          filterButtons.forEach(b => {
            b.classList.remove('bg-primary', 'text-surface');
            b.classList.add('bg-surface-container', 'text-on-surface-variant');
          });

          btn.classList.add('bg-primary', 'text-surface');
          btn.classList.remove('bg-surface-container', 'text-on-surface-variant');

          const filter = btn.getAttribute('data-filter');

          products.forEach(prod => {
            if (filter === 'all' || prod.getAttribute('data-category') === filter) {
              prod.style.display = 'flex';
            } else {
              prod.style.display = 'none';
            }
          });
        });
      });
    })();
  </script>
</body></html>
