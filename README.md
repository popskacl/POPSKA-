<!DOCTYPE html>

<html class="dark" lang="es"><head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<link href="https://fonts.googleapis.com/css2?family=Epilogue:wght@400;500;600;700;800&amp;family=Plus+Jakarta+Sans:wght@400;500;600;700;800&amp;family=Space+Grotesk:wght@500;700&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=block" rel="stylesheet"/>
<script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
<script id="tailwind-config">
        tailwind.config = {
            darkMode: "class",
            theme: {
                extend: {
                    "colors": {
                        "surface-bright": "#393939",
                        "secondary-fixed": "#e5e2e1",
                        "on-surface": "#e5e2e1",
                        "primary": "#ffe49f",
                        "surface-tint": "#f2c000",
                        "inverse-on-surface": "#313030",
                        "error": "#ffb4ab",
                        "on-secondary-container": "#b7b5b4",
                        "secondary-fixed-dim": "#c8c6c5",
                        "inverse-primary": "#745b00",
                        "background": "#131313",
                        "on-secondary": "#303030",
                        "outline-variant": "#4e4632",
                        "primary-fixed-dim": "#f2c000",
                        "on-primary-fixed": "#241a00",
                        "surface-container-highest": "#353534",
                        "surface-variant": "#353534",
                        "surface-dim": "#131313",
                        "tertiary": "#e9e6e5",
                        "inverse-surface": "#e5e2e1",
                        "on-primary": "#3d2f00",
                        "on-background": "#e5e2e1",
                        "surface-container": "#201f1f",
                        "on-primary-container": "#695200",
                        "primary-fixed": "#ffe08c",
                        "on-tertiary": "#303030",
                        "secondary-container": "#474746",
                        "primary-container": "#f6c400",
                        "on-secondary-fixed-variant": "#474746",
                        "on-primary-fixed-variant": "#584400",
                        "surface-container-high": "#2a2a2a",
                        "on-error": "#690005",
                        "on-tertiary-fixed": "#1b1c1c",
                        "surface-container-lowest": "#0e0e0e",
                        "outline": "#9a9078",
                        "surface": "#131313",
                        "secondary": "#c8c6c5",
                        "tertiary-container": "#cccaca",
                        "on-secondary-fixed": "#1b1b1c",
                        "on-error-container": "#ffdad6",
                        "error-container": "#93000a",
                        "on-surface-variant": "#d2c5ab",
                        "tertiary-fixed-dim": "#c8c6c6",
                        "tertiary-fixed": "#e4e2e1",
                        "surface-container-low": "#1c1b1b",
                        "on-tertiary-container": "#555555",
                        "on-tertiary-fixed-variant": "#474747"
                    },
                    "borderRadius": {
                        "DEFAULT": "0.25rem",
                        "lg": "0.5rem",
                        "xl": "0.75rem",
                        "full": "9999px"
                    },
                    "spacing": {
                        "md": "24px",
                        "lg": "48px",
                        "xl": "80px",
                        "container-max": "1280px",
                        "sm": "12px",
                        "base": "8px",
                        "xs": "4px",
                        "gutter": "24px",
                        "margin-mobile": "16px",
                        "margin-desktop": "64px"
                    },
                    "fontFamily": {
                        "headline-xl": ["Epilogue"],
                        "headline-lg-mobile": ["Epilogue"],
                        "body-md": ["Plus Jakarta Sans"],
                        "body-lg": ["Plus Jakarta Sans"],
                        "label-caps": ["Space Grotesk"],
                        "headline-md": ["Epilogue"],
                        "headline-lg": ["Epilogue"],
                        "label-bold": ["Space Grotesk"]
                    },
                    "fontSize": {
                        "headline-xl": ["64px", {"lineHeight": "1.1", "letterSpacing": "-0.02em", "fontWeight": "700"}],
                        "headline-lg-mobile": ["32px", {"lineHeight": "1.2", "fontWeight": "600"}],
                        "body-md": ["16px", {"lineHeight": "1.5", "fontWeight": "400"}],
                        "body-lg": ["18px", {"lineHeight": "1.6", "fontWeight": "400"}],
                        "label-caps": ["12px", {"lineHeight": "1.0", "letterSpacing": "0.1em", "fontWeight": "500"}],
                        "headline-md": ["24px", {"lineHeight": "1.3", "fontWeight": "600"}],
                        "headline-lg": ["48px", {"lineHeight": "1.2", "letterSpacing": "-0.01em", "fontWeight": "600"}],
                        "caption": ["12px", {"lineHeight": "16px", "fontWeight": "500"}]
                    }
                },
            },
        }
    </script>
</head>
<body class="bg-background text-on-surface font-body-md selection:bg-primary-container selection:text-on-primary-container">
<!-- 1. HEADER -->
<header class="fixed top-0 left-0 w-full z-50 bg-background/80 backdrop-blur-md border-b border-surface-variant">
<nav class="max-w-[1440px] mx-auto px-margin-mobile md:px-margin-desktop py-base flex justify-between items-center h-20">
<a class="font-headline-md text-headline-md font-black text-primary-container tracking-tight" href="#">
<img alt="Popska Logo" class="h-12 md:h-14 w-auto object-contain" src="https://lh3.googleusercontent.com/aida-public/AB6AXuBFksAvgkIxZB8nIOMeLD16Er7a4eXKvNt0CGl39K_JUNuM-SuFnjCReLtNbIHmZ1AYuZy4MY_M2yh2vkh6sZ4KMadoe8-bnJdzwKRKfymHUXaDkROAiKJgX4v2w6myJYNQ0abm4HZxbzmGW2vld2Jm94i0evhdV_xV2QbCSovJi9-LeUMUvusmWj-YtbVczaXRB36zz0OtGXLO3EyWN7RP_00JvoyUdqv0b003QHqgD3-O2BcojjNBeuJJuK3K_bki7RKXLSEcBSM"/>
</a>
<div class="hidden lg:flex items-center gap-gutter">
<a class="font-body-md text-body-md text-primary-container font-bold border-b-2 border-primary-container hover:scale-105 transition-transform duration-200" href="#">Inicio</a>
<a class="font-body-md text-body-md text-on-surface font-medium hover:text-primary-container hover:scale-105 transition-transform duration-200" href="#">Sabores</a>
<a class="font-body-md text-body-md text-on-surface font-medium hover:text-primary-container hover:scale-105 transition-transform duration-200" href="#">Combos</a>
<a class="font-body-md text-body-md text-on-surface font-medium hover:text-primary-container hover:scale-105 transition-transform duration-200" href="#">Eventos</a>
<a class="font-body-md text-body-md text-on-surface font-medium hover:text-primary-container hover:scale-105 transition-transform duration-200" href="#">Delivery</a>
<a class="font-body-md text-body-md text-on-surface font-medium hover:text-primary-container hover:scale-105 transition-transform duration-200" href="#">Contacto</a>
</div>
<div class="flex items-center gap-sm md:gap-md">
<button class="material-symbols-outlined text-on-surface-variant hover:text-primary-container transition-colors">shopping_cart</button>
<button class="material-symbols-outlined text-on-surface-variant hover:text-primary-container transition-colors">person</button>
<a class="hidden md:flex items-center bg-primary-container text-on-primary-container px-md py-xs rounded-xl font-label-bold hover:scale-105 active:scale-95 transition-all shadow-md" href="https://wa.me/something">
                Pedir por WhatsApp
            </a>
<button class="lg:hidden material-symbols-outlined text-on-surface">menu</button>
</div>
</nav>
</header>
<!-- 2. HERO -->
<section class="relative h-[85vh] md:h-screen w-full flex items-center pt-20">
<div class="absolute inset-0 z-0">
<img class="w-full h-full object-cover" src="https://lh3.googleusercontent.com/aida-public/AB6AXuCUgwQ4ByC41zdhpFnfJPkjARQVDIWr8jiybev_MqD3wphv6V9uvHOza1sb00pMrW4hS1PSHZD8ZTPsDiir-T05NFW8T54oeSXj-pdcgtsF9qwHh9mYx810AD8zJYwe6mlrKUkb_0luUIHBEDvu2sUO7e7gyA894Z1t9tgNxOOnmc0k8glsldSEtn-TYXUhTYSbKtlaOmdufCHMgbM0w4zmUxtEMgFdkep3PdYCEa9ZmrXrfno1oinz0beBfCCDlH6qWHWxSYbxgH8"/>
<div class="absolute inset-0 bg-gradient-to-r from-background via-background/60 to-transparent"></div>
</div>
<div class="relative z-10 px-margin-mobile md:px-margin-desktop max-w-4xl">
<span class="inline-block px-sm py-xs bg-primary-container text-on-primary-container rounded-full text-caption font-bold mb-md uppercase tracking-widest">Premium Snacks Chile</span>
<h1 class="font-headline-xl text-headline-xl md:text-[64px] text-on-surface leading-tight mb-md">
            Cabritas Artesanales &amp; Gourmet: <br/>
<span class="text-primary-container">El Sabor que amas, la mas POPular.</span>
</h1>
<p class="font-body-lg text-body-lg text-on-surface-variant max-w-2xl mb-lg">
            Hechas a mano con amor en Chile, perfectas para tus momentos especiales. Calidad premium en cada bocado, directo a tu puerta.
        </p>
<div class="flex flex-col sm:flex-row gap-md">
<button class="bg-primary-container text-on-primary-container px-xl py-md rounded-xl font-headline-md hover:brightness-110 hover:scale-[1.02] transition-all shadow-xl">
                Pedir Ahora
            </button>
<button class="border-2 border-on-surface text-on-surface px-xl py-md rounded-xl font-headline-md hover:bg-on-surface/10 transition-all backdrop-blur-sm">
                Ver Sabores
            </button>
</div>
</div>
</section>
<!-- 3. TRUST BAR -->
<section class="bg-surface-container py-md border-y border-surface-variant">
<div class="max-w-[1440px] mx-auto px-margin-mobile md:px-margin-desktop flex flex-wrap justify-between items-center gap-md">
<div class="flex items-center gap-sm">
<span class="material-symbols-outlined text-primary-container" style='font-variation-settings: "FILL" 1;'>favorite</span>
<span class="font-label-bold text-on-surface">Cada dia somos +</span>
</div>
<div class="flex items-center gap-sm">
<span class="material-symbols-outlined text-primary-container" style='font-variation-settings: "FILL" 1;'>auto_awesome</span>
<span class="font-label-bold text-on-surface">100% Artesanal</span>
</div>
<div class="flex items-center gap-sm">
<span class="material-symbols-outlined text-primary-container" style='font-variation-settings: "FILL" 1;'>verified</span>
<span class="font-label-bold text-on-surface">Frescas</span>
</div>
<div class="flex items-center gap-sm">
<span class="material-symbols-outlined text-primary-container" style='font-variation-settings: "FILL" 1;'>timer</span>
<span class="font-label-bold text-on-surface">Hecho al momento</span>
</div>
</div>
</section>
<!-- 4. FLAVORS CATALOG -->
<section class="py-xl bg-background">
<div class="max-w-[1440px] mx-auto px-margin-mobile md:px-margin-desktop">
<div class="flex justify-between items-end mb-xl">
<div>
<h2 class="font-headline-lg text-headline-lg text-on-surface mb-xs">Nuestros Sabores Estrella</h2>
<p class="font-body-md text-on-surface-variant">Explora una explosión de sabor artesanal.</p>
</div>
<button class="text-primary-container font-label-bold flex items-center gap-xs hover:gap-sm transition-all underline underline-offset-4">
                Ver todo el catálogo <span class="material-symbols-outlined">arrow_forward</span>
</button>
</div>
<div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-gutter">
<!-- Caramel Card -->
<div class="group bg-surface-container-low rounded-[32px] overflow-hidden border border-surface-variant/50 hover:border-primary-container/30 shadow-sm hover:shadow-xl transition-all duration-300 transform hover:-translate-y-2">
<div class="aspect-square relative overflow-hidden">
<img class="w-full h-full object-cover group-hover:scale-110 transition-transform duration-500" src="https://lh3.googleusercontent.com/aida-public/AB6AXuDVsSRFd3wXwm5C4USXSWM876IxwqUnOKp-xFf8PSOWWSmoN2F4JXymdHU_e5fKfjj0iNKXHT1RmWbLIZUbAXW9jBH_US2gIYBUAg3QCXB8c4sp48ZViovdSEJgOHWvqZkrCExgk5U3nUb7jUmyZbZwv5qs-pXK2e-cHLkg3NzRY99HldOXxGqgsEGto5itXs3riXp3D2uphdPftnegy1o4VKBybpPnG5Pl1gYHPY-JVwC4jrOA9bjNw8ZBEC-4wF4fcpiXRpBrSLngYQ"/>
<span class="absolute top-md left-md bg-primary-container text-on-primary-container px-sm py-xs rounded-full text-caption font-bold">BEST SELLER</span>
</div>
<div class="p-md">
<h3 class="font-headline-md text-headline-md text-on-surface mb-xs">POPSKA Dulce Clasico</h3>
<p class="font-body-md text-on-surface-variant mb-md h-12 line-clamp-2">Cabritas clasicas, con un toque de vainilla y pizca de sal. (100 gr)</p>
<div class="flex justify-between items-center">
<span class="font-headline-md text-primary-container">$2.000</span>
<button class="bg-primary-container text-on-primary-container w-12 h-12 rounded-full flex items-center justify-center hover:scale-110 active:scale-95 transition-all">
<span class="material-symbols-outlined">add_shopping_cart</span>
</button>
</div>
</div>
</div>
<!-- Cheese Card -->
<div class="group bg-surface-container-low rounded-[32px] overflow-hidden border border-surface-variant/50 hover:border-primary-container/30 shadow-sm hover:shadow-xl transition-all duration-300 transform hover:-translate-y-2">
<div class="aspect-square relative overflow-hidden">
<img class="w-full h-full object-cover group-hover:scale-110 transition-transform duration-500" src="https://lh3.googleusercontent.com/aida-public/AB6AXuDczUfLShuKCcqm9M6Pc1-8jCBqwO-z9F4tvJOKcvgpFO-1zGPwlfk9aQ1snlw3f8vnoPXp3GOVK35SZYOxoXANTawIt58SyYsOU5_UNnlyGTy2ZpA5ev9-ukD7QBl4SetNXNcpoCn2-MxJc9Ir-yiq5O_5GsnR4y_iLMI8sERQcK0zJWLEV5YO6JA8IgcfLoveSUy3-Vl7aTawWubgOswmbOL4lGwtDu59fIQIDLrL7RJAXkv3L_aKBSOoCSIPrulIKrPRaxASVCh_-g"/>
</div>
<div class="p-md">
<h3 class="font-headline-md text-headline-md text-on-surface mb-xs">POPSKA Dulce Arcoiris</h3>
<p class="font-body-md text-on-surface-variant mb-md h-12 line-clamp-2">Cabritas dulces, con azucar de colores vegetal (100 gr)</p>
<div class="flex justify-between items-center">
<span class="font-headline-md text-primary-container">$2.500</span>
<button class="bg-primary-container text-on-primary-container w-12 h-12 rounded-full flex items-center justify-center hover:scale-110 active:scale-95 transition-all">
<span class="material-symbols-outlined">add_shopping_cart</span>
</button>
</div>
</div>
</div>
<!-- Chocolate Card -->
<div class="group bg-surface-container-low rounded-[32px] overflow-hidden border border-surface-variant/50 hover:border-primary-container/30 shadow-sm hover:shadow-xl transition-all duration-300 transform hover:-translate-y-2">
<div class="aspect-square relative overflow-hidden">
<img class="w-full h-full object-cover group-hover:scale-110 transition-transform duration-500" src="https://lh3.googleusercontent.com/aida-public/AB6AXuBuzcrV49kjEfIkJwkA4-kOXfGN8ySse371GAfVBBq-cEn4xYq4SC7dnKcEFgnwLliM2FAY6lPszjZp8BGfZWhW8e0WriXiwaM6Ze5ZS7YgDjvX0HJQbVv3PQxNyG8dyXaz8syELJWYX7CTbC6COn0Cs1cHGfrtQB5wQh2JYHq9XYwAq9RtHh2jzGyvEQzLDzAush_yIHZlG7hydJwa48eIufgSHM8OBdthXBAh0z4n4FZyKGDReJk_RdO5QTidRj3VJ82pLLhQusd0eA"/>
<span class="absolute top-md left-md bg-on-surface text-background px-sm py-xs rounded-full text-caption font-bold">PREMIUM</span>
</div>
<div class="p-md">
<h3 class="font-headline-md text-headline-md text-on-surface mb-xs">POPSKA Saladas</h3>
<p class="font-body-md text-on-surface-variant mb-md h-12 line-clamp-2">Cabritas Saladas (100 gr)</p>
<div class="flex justify-between items-center">
<span class="font-headline-md text-primary-container">$2.000</span>
<button class="bg-primary-container text-on-primary-container w-12 h-12 rounded-full flex items-center justify-center hover:scale-110 active:scale-95 transition-all">
<span class="material-symbols-outlined">add_shopping_cart</span>
</button>
</div>
</div>
</div>
<!-- Berries Card -->
<div class="group bg-surface-container-low rounded-[32px] overflow-hidden border border-surface-variant/50 hover:border-primary-container/30 shadow-sm hover:shadow-xl transition-all duration-300 transform hover:-translate-y-2">
<div class="aspect-square relative overflow-hidden">
<img class="w-full h-full object-cover group-hover:scale-110 transition-transform duration-500" src="https://lh3.googleusercontent.com/aida-public/AB6AXuAqdUFNXR-VODnRQguo0U7hReVbgt2kQWCnxsygbGFTVjysJaTuT-KgM5n-y8jtKDn2EWtC0fAzTshxai65tXBGS2H8xWjhseFygjQtFrgvdV367x3Wm2LzJG85fPUas7kwbd9wNMM7HV_pkAnPv-Eq9-S15BI61ti8Sl4J2jYJSMZK4zrbvOjNPaw4ASNO06XLi2k-7klkmhSjvCVNsitox_A_7CzIEtnZ_Avpoki-eTp0OgzpFpd4PfrYhyQ1yMcE5mBC6NBGFC5-LQ"/>
</div>
<div class="p-md">
<h3 class="font-headline-md text-headline-md text-on-surface mb-xs">POPSKA Mantequilla Dulce</h3>
<p class="font-body-md text-on-surface-variant mb-md h-12 line-clamp-2">Cabritas dulces, con sabor mantequilla y pizca de sal. (100 gr)</p>
<div class="flex justify-between items-center">
<span class="font-headline-md text-primary-container">$3.000</span>
<button class="bg-primary-container text-on-primary-container w-12 h-12 rounded-full flex items-center justify-center hover:scale-110 active:scale-95 transition-all">
<span class="material-symbols-outlined">add_shopping_cart</span>
</button>
</div>
</div>
</div>
</div>
</div>
</section>
<!-- 5. WHY US -->
<section class="py-xl bg-surface-container-lowest">
<div class="max-w-[1440px] mx-auto px-margin-mobile md:px-margin-desktop">
<h2 class="font-headline-lg text-headline-lg text-center mb-xl text-on-surface">¿Por qué elegir Popska?</h2>
<div class="grid grid-cols-1 md:grid-cols-4 gap-xl">
<div class="text-center group">
<div class="w-20 h-20 bg-surface-bright mx-auto rounded-3xl flex items-center justify-center mb-md group-hover:rotate-6 transition-transform border border-surface-variant">
<span class="material-symbols-outlined text-primary-container text-[40px]">eco</span>
</div>
<h4 class="font-headline-md mb-xs text-on-surface">Ingredientes Premium</h4>
<p class="font-body-md text-on-surface-variant">Maíz mushroom gigante y coberturas de origen natural.</p>
</div>
<div class="text-center group">
<div class="w-20 h-20 bg-surface-bright mx-auto rounded-3xl flex items-center justify-center mb-md group-hover:-rotate-6 transition-transform border border-surface-variant">
<span class="material-symbols-outlined text-primary-container text-[40px]">restaurant</span>
</div>
<h4 class="font-headline-md mb-xs text-on-surface">Receta Artesanal</h4>
<p class="font-body-md text-on-surface-variant">Hechas a mano en pequeños lotes para garantizar frescura.</p>
</div>
<div class="text-center group">
<div class="w-20 h-20 bg-surface-bright mx-auto rounded-3xl flex items-center justify-center mb-md group-hover:rotate-6 transition-transform border border-surface-variant">
<span class="material-symbols-outlined text-primary-container text-[40px]">health_and_safety</span>
</div>
<h4 class="font-headline-md mb-xs text-on-surface">100% Sin Sellos</h4>
<p class="font-body-md text-on-surface-variant">Disfruta sin culpas de un snack saludable y delicioso.</p>
</div>
<div class="text-center group">
<div class="w-20 h-20 bg-surface-bright mx-auto rounded-3xl flex items-center justify-center mb-md group-hover:-rotate-6 transition-transform border border-surface-variant">
<span class="material-symbols-outlined text-primary-container text-[40px]">star</span>
</div>
<h4 class="font-headline-md mb-xs text-on-surface">Variedad Única</h4>
<p class="font-body-md text-on-surface-variant">Sabores exclusivos que no encontrarás en ningún otro lugar.</p>
</div>
</div>
</div>
</section>
<!-- 6. DELIVERY ZONE -->
<section class="py-xl bg-surface-container-high text-on-surface overflow-hidden relative">
<div class="max-w-[1440px] mx-auto px-margin-mobile md:px-margin-desktop relative z-10 flex flex-col md:flex-row items-center gap-xl">
<div class="flex-1">
<h2 class="font-headline-lg text-headline-lg mb-md text-on-surface">Delivery en Santiago &amp; Regiones</h2>
<p class="font-body-lg text-on-surface-variant mb-xl">Llegamos a cada rincón con la frescura de Popska. Haz tu pedido directo o búscanos en tus apps favoritas.</p>
<div class="space-y-lg mb-xl">
<div class="flex items-start gap-md">
<span class="material-symbols-outlined text-primary-container">location_on</span>
<div>
<p class="font-label-bold text-on-surface">Despacho Express</p>
<p class="font-body-md text-on-surface-variant">La Florida, Santiago (RM) en menos de 24 horas.</p>
</div>
</div>
<div class="flex items-start gap-md">
<span class="material-symbols-outlined text-primary-container">local_shipping</span>
<div>
<p class="font-label-bold text-on-surface">Envíos a Regiones</p>
<p class="font-body-md text-on-surface-variant">Vía Blue Express y Starken a todo Chile.</p>
</div>
</div>
</div>
<div class="flex flex-wrap gap-md items-center opacity-80 hover:opacity-100 transition-all duration-500">
<span class="font-label-bold text-on-surface-variant mr-md">Búscanos PRONTO en:</span>
<div class="bg-surface-bright px-md py-xs rounded-lg font-bold border border-surface-variant">Uber Eats</div>
<div class="bg-surface-bright px-md py-xs rounded-lg font-bold border border-surface-variant">Rappi</div>
<div class="bg-surface-bright px-md py-xs rounded-lg font-bold border border-surface-variant">PedidosYa</div>
</div>
<button class="mt-xl w-full md:w-auto bg-[#25D366] text-white px-xl py-md rounded-2xl font-headline-md flex items-center justify-center gap-md hover:scale-105 active:scale-95 transition-all shadow-lg">
<span class="material-symbols-outlined">message</span> Pedir por WhatsApp
            </button>
</div>
<div class="flex-1 w-full h-[400px] rounded-[40px] overflow-hidden shadow-2xl border border-surface-variant">
<div class="w-full h-full bg-surface-container relative">
<img class="w-full h-full object-cover opacity-80" src="https://lh3.googleusercontent.com/aida-public/AB6AXuCP5FUqzoeL9DSei_KUk2eMDSAl18eGTEd9TySTql7Sj1Y4SifFm2JaxdNi52wVVI8CVvHY-VqgeM36eslQU1AsrOxGskQlJL3v90ukTwTU7Cf0-znYbUePr9SR73KEP6HPtRoO3mtUATD-D0-OceZlyPFfZBykthbZwasUxbCf-LR4E1MlusZ1u1EnipMiSuwi50m888ocl4J3GebJZIYttBWH96p_nlRbUeNFTSiM1wiugqlqdYqnEtGbTXpslnH0O3uaJyBpxwg"/>
</div>
</div>
</div>
</section>
<!-- 7. COMBOS -->
<section class="py-xl bg-background">
<div class="max-w-[1440px] mx-auto px-margin-mobile md:px-margin-desktop">
<h2 class="font-headline-lg text-headline-lg mb-xl text-center text-on-surface">Nuestros Packs para Disfrutar</h2>
<div class="grid grid-cols-1 md:grid-cols-3 gap-gutter">
<!-- Pack 1 -->
<div class="bg-surface-container-low p-lg rounded-[40px] flex flex-col items-center text-center border border-surface-variant/30 shadow-sm hover:shadow-xl transition-all">
<span class="material-symbols-outlined text-primary-container text-[64px] mb-md">person</span>
<h3 class="font-headline-md mb-xs text-on-surface">Pack Pareja</h3>
<p class="font-body-md text-on-surface-variant mb-lg">3 sabores a elección para tu maratón de series.</p>
<span class="font-headline-lg text-on-surface mb-lg">$12.900</span>
<button class="mt-auto w-full border-2 border-primary-container text-primary-container py-md rounded-xl font-label-bold hover:bg-primary-container hover:text-on-primary-container transition-all">Comprar</button>
</div>
<!-- Pack 2 -->
<div class="bg-primary-container text-on-primary-container p-lg rounded-[40px] flex flex-col items-center text-center shadow-xl scale-105 relative border-4 border-background">
<div class="absolute -top-4 bg-on-background text-background px-md py-xs rounded-full font-bold text-caption">MÁS POPULAR</div>
<div class="w-full h-48 rounded-2xl overflow-hidden mb-md shadow-inner">
<img alt="Combo Compartir" class="w-full h-full object-cover" src="https://lh3.googleusercontent.com/aida-public/AB6AXuCczfu4HbE6mP912ql-mzJn6VHsxxuQRV1Ph9hZ-uCpUfCE6lc9DwYP0tL2ijt5MoTK61FCdToeOtT_vMJ9gRcbCk0_tv6pIKeRAa9VMC688ncM4pwULIRRThokRHtO2PfRFl-OhTzvtdvziFoWoeH9W3HleBgbJm_v_EniCbaO_HNeKYHldQ_LJ06usHB7u_3-dFSj1yDH-BRMC91-F9XOedtSHP70HCkA3lg62Tih3tagnO1V_dq2sUTlZzFttnBNSblEtrANNLc"/>
</div>
<h3 class="font-headline-md mb-xs">Combo Compartir</h3>
<p class="font-body-md text-on-primary-container/80 mb-lg">Balde gigante + 4 bebidas. Perfecto para 4 personas.</p>
<span class="font-headline-lg mb-lg">$24.900</span>
<button class="mt-auto w-full bg-background text-on-surface py-md rounded-xl font-label-bold hover:brightness-125 transition-all">Comprar</button>
</div>
<!-- Pack 3 -->
<div class="bg-surface-container-low p-lg rounded-[40px] flex flex-col items-center text-center border border-surface-variant/30 shadow-sm hover:shadow-xl transition-all">
<span class="material-symbols-outlined text-primary-container text-[64px] mb-md">celebration</span>
<h3 class="font-headline-md mb-xs text-on-surface">Fiesta Pack</h3>
<p class="font-body-md text-on-surface-variant mb-lg">10 minipacks variados para cumpleaños y eventos.</p>
<span class="font-headline-lg text-on-surface mb-lg">$35.000</span>
<button class="mt-auto w-full border-2 border-primary-container text-primary-container py-md rounded-xl font-label-bold hover:bg-primary-container hover:text-on-primary-container transition-all">Comprar</button>
</div>
</div>
</div>
</section>
<!-- 8. EVENTS -->
<section class="py-xl">
<div class="max-w-[1440px] mx-auto px-margin-mobile md:px-margin-desktop">
<div class="relative rounded-[48px] overflow-hidden bg-surface-container h-[500px] group border border-surface-variant">
<img alt="Event Popcorn Cart" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-[2s] opacity-70" src="https://lh3.googleusercontent.com/aida-public/AB6AXuBNXBx3SFNlnnu3poTB_CWQ60YUuTt0jfF29QKTtS9eHlFi7rTgHiFp_D8aDGue_0kfd1-Y9ZFhN_E0nA4Pq1NwdgUA1Ivh9lyS7oTzA1wSd6zoDlUNYOAkbsjNXVt3l9WOwLFBrmKHsik-PxLt5x_qEQoSncxQqjl81zqQCIRsC52oFLqYgzIqx-cI5Da1QGRAFNwY90mgLjsnHirH2W7UnwrMb_-Z_XkZajQhDS4YRHksOgOmUdAbGG817sLvtsljKTjm_e6a2lQ"/>
<div class="absolute inset-0 bg-gradient-to-t from-background via-background/40 to-transparent flex items-end p-xl">
<div class="max-w-2xl">
<h2 class="font-headline-xl text-headline-xl text-on-surface mb-md">Lleva la diversión a tu evento</h2>
<p class="font-body-lg text-on-surface-variant mb-lg">Cumpleaños, eventos corporativos, bodas y más. Nuestro carrito de cabritas es el alma de la fiesta.</p>
<button class="bg-primary-container text-on-primary-container px-xl py-md rounded-xl font-headline-md hover:scale-105 transition-all shadow-lg">
                        Cotizar mi evento
                    </button>
</div>
</div>
</div>
</div>
</section>
<!-- 9. TESTIMONIALS -->
<section class="py-xl bg-surface-container-lowest">
<div class="max-w-[1440px] mx-auto px-margin-mobile md:px-margin-desktop">
<h2 class="font-headline-lg text-headline-lg text-center mb-xl text-on-surface">Lo que dicen nuestros clientes</h2>
<div class="flex gap-gutter overflow-x-auto scroll-hide pb-md">
<div class="min-w-[320px] bg-surface-container-low p-lg rounded-3xl shadow-sm border border-surface-variant">
<div class="flex text-primary-container mb-md">
<span class="material-symbols-outlined" style='font-variation-settings: "FILL" 1;'>star</span>
<span class="material-symbols-outlined" style='font-variation-settings: "FILL" 1;'>star</span>
<span class="material-symbols-outlined" style='font-variation-settings: "FILL" 1;'>star</span>
<span class="material-symbols-outlined" style='font-variation-settings: "FILL" 1;'>star</span>
<span class="material-symbols-outlined" style='font-variation-settings: "FILL" 1;'>star</span>
</div>
<p class="font-body-md italic mb-md text-on-surface">"Las mejores cabritas que he probado en Chile. El sabor a Caramelo es simplemente de otro planeta."</p>
<div class="flex items-center gap-sm">
<div class="w-10 h-10 rounded-full bg-surface-bright"></div>
<span class="font-label-bold text-on-surface">Carolina M.</span>
</div>
</div>
<div class="min-w-[320px] bg-surface-container-low p-lg rounded-3xl shadow-sm border border-surface-variant">
<div class="flex text-primary-container mb-md">
<span class="material-symbols-outlined" style='font-variation-settings: "FILL" 1;'>star</span>
<span class="material-symbols-outlined" style='font-variation-settings: "FILL" 1;'>star</span>
<span class="material-symbols-outlined" style='font-variation-settings: "FILL" 1;'>star</span>
<span class="material-symbols-outlined" style='font-variation-settings: "FILL" 1;'>star</span>
<span class="material-symbols-outlined" style='font-variation-settings: "FILL" 1;'>star</span>
</div>
<p class="font-body-md italic mb-md text-on-surface">"Me encanta que no tengan sellos. Mis hijos las aman y yo estoy tranquila dándoselas."</p>
<div class="flex items-center gap-sm">
<div class="w-10 h-10 rounded-full bg-surface-bright"></div>
<span class="font-label-bold text-on-surface">Andrés P.</span>
</div>
</div>
<div class="min-w-[320px] bg-surface-container-low p-lg rounded-3xl shadow-sm border border-surface-variant">
<div class="flex text-primary-container mb-md">
<span class="material-symbols-outlined" style='font-variation-settings: "FILL" 1;'>star</span>
<span class="material-symbols-outlined" style='font-variation-settings: "FILL" 1;'>star</span>
<span class="material-symbols-outlined" style='font-variation-settings: "FILL" 1;'>star</span>
<span class="material-symbols-outlined" style='font-variation-settings: "FILL" 1;'>star</span>
<span class="material-symbols-outlined" style='font-variation-settings: "FILL" 1;'>star</span>
</div>
<p class="font-body-md italic mb-md text-on-surface">"El servicio de delivery es ultra rápido. Llegaron calentitas y crujientes."</p>
<div class="flex items-center gap-sm">
<div class="w-10 h-10 rounded-full bg-surface-bright"></div>
<span class="font-label-bold text-on-surface">Francisca L.</span>
</div>
</div>
</div>
</div>
</section>
<!-- 10. INSTAGRAM FEED -->
<section class="py-xl bg-background">
<div class="max-w-[1440px] mx-auto px-margin-mobile md:px-margin-desktop">
<div class="text-center mb-xl">
<h2 class="font-headline-lg text-headline-lg mb-xs text-on-surface">@Popska.cl</h2>
<p class="font-body-md text-on-surface-variant">Síguenos para promos y nuevos sabores.</p>
</div>
<div class="grid grid-cols-2 md:grid-cols-6 gap-sm mb-xl">
<div class="aspect-square rounded-xl overflow-hidden cursor-pointer hover:opacity-80 transition-opacity border border-surface-variant">
<img class="w-full h-full object-cover" src="https://lh3.googleusercontent.com/aida-public/AB6AXuBGu5LyBQgMAFFDNDFwikPYEqasw-Z-Qf2QAxQ_eegktjOovnxGkpEQPrB-c4DHdRE59kk-ita-0SAMKQpV5Ra7w16dCLUHg3AHlAARVIG3c07c888KMdVVjD14GDpIWYFwCvGLPExH2eKytn_GwRBIdtUOrQie27yVFcGCCYZ3jWXJU9oncDfEX7QzGHWS0c7TD7QyQUCiD3KAQstEhi2bHY44wN0eqcwoNiQQ-yvqI8RrlukF0muQzldiZAw2nA-4qRU8wos29sQo9w"/>
</div>
<div class="aspect-square rounded-xl overflow-hidden cursor-pointer hover:opacity-80 transition-opacity border border-surface-variant">
<img class="w-full h-full object-cover" src="https://lh3.googleusercontent.com/aida-public/AB6AXuAzvN9cZ4t3LPGALY4LKdT1oQz4PWcIS7bhAVF9PfYWAJ85mQ8n3U-bDoq6SB4jxA7QCJt4TWdJ7Q95kS4uAmmg7-3cVS_scTX4dVSZk1TdSzquusbzVL8s4xS_YUcGQVbMRWxJXDUyXZ9RVRk0aY0UP7lhoPvK7VOm9Pt5ZZzptEhtLWv6VJc_SLnCo2n0s6Zo4EYDAxQ2QDroPAfSVs26lAk7TPstg5QjDhDJb7BYKQi3tW7EvUC-69DP9IOs_gIa5yNF_acmyTCH0Q"/>
</div>
<div class="aspect-square rounded-xl overflow-hidden cursor-pointer hover:opacity-80 transition-opacity border border-surface-variant">
<img class="w-full h-full object-cover" src="https://lh3.googleusercontent.com/aida-public/AB6AXuDZ46lSeW1fdAxAUHoVmUCttked9UDGqixJ227op1QVKsAxQbjbPhFqPI2jlvUCd-0nuJp1mF1JyqDMQ0xck4Pa7VISvxmkIHoWqUawWyYjJ-tTZvffPKNekksK72D8fSHLBJfNjpw7fLXvrrFv5xT1xOQyXpo0A4R7EJZtoQjiYYvpF27ZV000ImCjX7i-U-fWPFnBBwN7TP8sLp96oWN6wQoUnzdEINBIAZeVI8eC77aLbmv288ZRYKQeD9ulsMf3Yu9vDINTfD7aKw"/>
</div>
<div class="aspect-square rounded-xl overflow-hidden cursor-pointer hover:opacity-80 transition-opacity border border-surface-variant">
<img class="w-full h-full object-cover" src="https://lh3.googleusercontent.com/aida-public/AB6AXuBTCCfpMeKkR-KznvmU0Phns4gqrZGUmL2fEN4xPFMcENB7yTXmMUBaA76fFnOnT23DDRmQXQ2OYQjYWBuF6MZuSeMq0Artdq1-gWUiXbyh2SNbB2aD8OVqj6gQXTBzHLGfjldOdJZ8kPDUd7pvou_iEJIMliYQxFlWC3dsgDmuN7xcwHSdEX_8c2aU4zIjoROdZQuy5Q0OVrXJOZtU7dlstLEtomlGkDW7pLqGziQfvNGZD2JGUt5W0PymbIrJW6M6a1KDtrP2-4ZXlg"/>
</div>
<div class="aspect-square rounded-xl overflow-hidden cursor-pointer hover:opacity-80 transition-opacity border border-surface-variant">
<img class="w-full h-full object-cover" src="https://lh3.googleusercontent.com/aida-public/AB6AXuApv2e4XlNlZ_e2W4GQ1bavc_vnkj4ZoNaQKie6VkGbT3j1TuFLqu2OMVD1lP_nvaFFEyDlqPUsawDZH4F4xoVNtQ-e4e8ddQAUsYz6GIGQnSEf1wif-fNIfy_Y7pyomzSssFYtpcz9E-SwvoTSb6Y63OxYHxCzJ2cAhUZSoCZxjfMNy4OREj9hPNrjgNgy6McOR0Cn0lqyjglumuedSw9kYv_JNJuSAKUIglYTdJuQXBh7yOQ88RnRX3YYIPprZt8IErZcMMXmuX6EAg"/>
</div>
<div class="aspect-square rounded-xl overflow-hidden cursor-pointer hover:opacity-80 transition-opacity border border-surface-variant">
<img class="w-full h-full object-cover" src="https://lh3.googleusercontent.com/aida-public/AB6AXuDZGxorSZv38DQqTY4j4XwceMWL38Rne5oZFWURSbfguCCQpm_W_VR6FenOaMofb44etDD-HHBdST5KqXtqqvTaoI-7LZ5LxA_giRlrMCMixKXC_T1f-GcadmUqLOnj1J_r2Ln8UWoDg-4rIDDz2J4b8C2ddOg-W0IMmYg-YkUF2haEuQFaegmtaNVhzRdENEFyLC0pFG-G3N7le2-qk17Wfeota17mqX224JPr_N4Xzq5JyfUky-dmmGR5RllPSOBdsulQw2jerRSGiA"/>
</div>
</div>
<div class="text-center">
<button class="inline-flex items-center gap-sm bg-surface-bright text-on-surface px-lg py-md rounded-xl font-label-bold hover:scale-105 transition-all border border-surface-variant">
                Síguenos en Instagram
            </button>
</div>
</div>
</section>
<!-- 11. NEWSLETTER -->
<section class="py-xl bg-primary-container relative overflow-hidden">
<div class="absolute inset-0 opacity-10">
<div class="grid grid-cols-12 gap-2 h-full">
<div class="col-span-1 border-r border-on-primary-container/20"></div>
<div class="col-span-1 border-r border-on-primary-container/20"></div>
<div class="col-span-1 border-r border-on-primary-container/20"></div>
<div class="col-span-1 border-r border-on-primary-container/20"></div>
</div>
</div>
<div class="max-w-[1440px] mx-auto px-margin-mobile md:px-margin-desktop relative z-10">
<div class="bg-background rounded-[40px] p-lg md:p-xl flex flex-col md:flex-row items-center justify-between gap-xl shadow-2xl border border-surface-variant">
<div class="max-w-xl">
<h2 class="font-headline-lg text-headline-lg mb-md text-primary-container">¡Únete a la Pop-Lista!</h2>
<p class="font-body-lg text-on-surface-variant">Regístrate en nuestra lista de WhatsApp y recibe un <span class="font-bold text-primary-container">10% OFF</span> en tu primera compra.</p>
</div>
<div class="w-full md:w-auto flex flex-col sm:flex-row gap-md">
<input class="px-md py-md bg-surface-container rounded-xl border border-surface-variant text-on-surface focus:ring-2 focus:ring-primary-container w-full md:w-80 font-body-md" placeholder="Tu número de WhatsApp" type="text"/>
<button class="bg-primary-container text-on-primary-container px-lg py-md rounded-xl font-headline-md hover:brightness-110 shadow-lg whitespace-nowrap">
                    Quiero mi Descuento
                </button>
</div>
</div>
</div>
</section>
<!-- 12. FOOTER -->
<footer class="bg-surface-container-lowest text-on-surface py-xl border-t border-surface-variant">
<div class="max-w-[1440px] mx-auto px-margin-mobile md:px-margin-desktop">
<div class="flex flex-col md:flex-row justify-between items-start gap-gutter mb-xl">
<div>
<img alt="Popska Logo" class="h-16 md:h-20 w-auto object-contain mb-md" src="https://lh3.googleusercontent.com/aida-public/AB6AXuBFksAvgkIxZB8nIOMeLD16Er7a4eXKvNt0CGl39K_JUNuM-SuFnjCReLtNbIHmZ1AYuZy4MY_M2yh2vkh6sZ4KMadoe8-bnJdzwKRKfymHUXaDkROAiKJgX4v2w6myJYNQ0abm4HZxbzmGW2vld2Jm94i0evhdV_xV2QbCSovJi9-LeUMUvusmWj-YtbVczaXRB36zz0OtGXLO3EyWN7RP_00JvoyUdqv0b003QHqgD3-O2BcojjNBeuJJuK3K_bki7RKXLSEcBSM"/>
<p class="font-body-md text-on-surface-variant max-w-sm mt-md">Las mejores cabritas gourmet de Chile, hechas con amor y sin sellos para tus mejores momentos.</p>
</div>
<div class="grid grid-cols-2 gap-xl">
<div>
<h4 class="font-label-bold text-on-surface mb-md uppercase tracking-wider">Menú</h4>
<ul class="space-y-sm">
<li class=""><a class="font-body-md text-on-surface-variant hover:text-primary-container transition-colors" href="#">Inicio</a></li>
<li class=""><a class="font-body-md text-on-surface-variant hover:text-primary-container transition-colors" href="#">Sabores</a></li>
<li class=""><a class="font-body-md text-on-surface-variant hover:text-primary-container transition-colors" href="#">Combos</a></li>
</ul>
</div>
<div>
<h4 class="font-label-bold text-on-surface mb-md uppercase tracking-wider">Ayuda</h4>
<ul class="space-y-sm">
<li class=""><a class="font-body-md text-on-surface-variant hover:text-primary-container transition-colors" href="#">Preguntas Frecuentes</a></li>
<li class=""><a class="font-body-md text-on-surface-variant hover:text-primary-container transition-colors" href="#">Envíos</a></li>
<li class=""><a class="font-body-md text-on-surface-variant hover:text-primary-container transition-colors" href="#">Contacto</a></li>
</ul>
</div>
</div>
<div class="">
<h4 class="font-label-bold text-on-surface mb-md uppercase tracking-wider">Legal</h4>
<ul class="space-y-sm">
<li class=""><a class="font-body-md text-on-surface-variant hover:text-primary-container transition-colors" href="#">Privacidad</a></li>
<li class=""><a class="font-body-md text-on-surface-variant hover:text-primary-container transition-colors" href="#">Términos y Condiciones</a></li>
</ul>
</div>
</div>
<div class="pt-xl border-t border-surface-variant flex flex-col md:flex-row justify-between items-center gap-md">
<p class="font-body-md text-on-surface-variant">© 2024 Popska Gourmet Popcorn. Hecho con sabor.</p>
<div class="flex gap-md">
<button class="material-symbols-outlined text-on-surface-variant hover:text-primary-container">facebook</button>
</div>
</div>
</div>
</footer>
</body></html>
