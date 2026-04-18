# Tarea-3.1-Frame-CSS
<!DOCTYPE html>
<!--codigo para ejutar Tailwind:  npx @tailwindcss/cli -i ./style.css -o ./dist/output.css --watch-->
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href="output.css" rel="stylesheet">
    <title>Urban Kickz</title>
</head>
<body>
    <header class="bg-white p-3.5 flex items-center justify-between shadow-sm">
    <div>
        <img src="Logo_navegacion (1).png" alt="Logo de Urban Kickz" class="h-11 w-11 object-contain">
    </div>
    <nav>
        <ul class="flex items-center gap-8 ">
            <li><a href="#" class="text-sm font-semibold text-gray-900 hover:text-gray-600">Productos</a></li>
            <li><a href="#" class="text-sm font-semibold text-gray-900 hover:text-gray-600">Acerca de</a></li>
            <li><a href="#" class="text-sm font-semibold text-gray-900 hover:text-gray-600">Contáctanos</a></li>
        </ul>
    </nav>
</header>
<h1 class="font-extrabold text-5xl flex justify-center mt-9">Lo Más Vendido</h1>
<h1 class="text-1xl flex justify-center text-gray-500 mt-2.5">Mira nuestros produtos mas buscados por nuestros clientes</h1>

<div class="justify-center flex mt-7">
<button class="bg-black  hover:bg-gray-800 text-white rounded py-2 px-4"><strong>Comprar</strong></button>
<div class="ml-6">
<button class="bg-gray-50 hover:bg-gray-200 rounded py-2 px-4 "><strong>Carrito</strong></button>
</div></div>

<div class="overflow-hidden w-full mt-12">
    <div class="flex animate-marquee gap-8 w-max">
        
        <div class="flex gap-8">
            <img src="recorrido1.png" class="w-100 h-100 object-cover rounded-xl">
            <img src="recorrido2.png" class="w-100 h-100 object-cover rounded-xl">
            <img src="recorrido3.png" class="w-100 h-100 object-cover rounded-xl">
            <img src="recorrido4.png" class="w-100 h-100 object-cover rounded-xl">
        </div>

        <div class="flex gap-8">
            <img src="recorrido1.png" class="w-100 h-100 object-cover rounded-xl">
            <img src="recorrido2.png" class="w-100 h-100 object-cover rounded-xl">
            <img src="recorrido3.png" class="w-100 h-100 object-cover rounded-xl">
            <img src="recorrido4.png" class="w-100 h-100 object-cover rounded-xl">
        </div>
        
    </div>
</div>


<div class="mt-20 px-6 max-w-7xl mx-auto">
    <h2 class="text-2xl md:text-3xl font-extrabold text-black mb-10 text-center md:text-left">
        Lo Más Vendido
    </h2>

    <div class="grid grid-cols-1 md:grid-cols-2 gap-x-8 gap-y-12">
        
        <div class="group cursor-pointer">
            <div class="bg-[#f6f6f6] aspect-[4/5] flex justify-center items-center overflow-hidden rounded-sm">
                <img src="Imagenes/jersey_blanco_liga.png" alt="Jersey Blanco" class="w-full h-full object-cover transition-transform duration-500 group-hover:scale-105">
            </div>
            <div class="mt-4 flex justify-between items-start gap-4">
                <h3 class="text-sm font-bold text-black leading-tight">
                    Equipo México Mundial Clásico Baseball 2026 (blanco)
                </h3>
                <p class="text-sm text-gray-500">$2,999</p>
            </div>
        </div>

        <div class="group cursor-pointer">
            <div class="bg-[#f6f6f6] aspect-[4/5] flex justify-center items-center overflow-hidden rounded-sm">
                <img src="Imagenes/jersey_verde_liga.png" alt="Jersey Verde" class="w-full h-full object-cover transition-transform duration-500 group-hover:scale-105">
            </div>
            <div class="mt-4 flex justify-between items-start gap-4">
                <h3 class="text-sm font-bold text-black leading-tight">
                    Equipo México Mundial Clásico Baseball 2026 (verde)
                </h3>
                <p class="text-sm text-gray-500">$2,999</p>
            </div>
        </div>

        <div class="group cursor-pointer">
            <div class="bg-[#f6f6f6] aspect-[4/5] flex justify-center items-center overflow-hidden rounded-sm">
                <img src="Imagenes/af1.png" alt="Tenis Nike AF1" class="w-full h-full object-cover transition-transform duration-500 group-hover:scale-105">
            </div>
            <div class="mt-4 flex justify-between items-start gap-4">
                <h3 class="text-sm font-bold text-black leading-tight">
                    Tenis Nike Air Force One (AF1)
                </h3>
                <p class="text-sm text-gray-500">$2,999</p>
            </div>
        </div>

        <div class="group cursor-pointer">
            <div class="bg-[#f6f6f6] aspect-[4/5] flex justify-center items-center overflow-hidden rounded-sm">
                <img src="Imagenes/af1_premium.png" alt="Tenis Nike AF1 Premium" class="w-full h-full object-cover transition-transform duration-500 group-hover:scale-105">
            </div>
            <div class="mt-4 flex justify-between items-start gap-4">
                <h3 class="text-sm font-bold text-black leading-tight">
                    Tenis Nike Air Force 1 '07 Premium +
                </h3>
                <p class="text-sm text-gray-500">$2,999</p>
            </div>
        </div>

    </div>
</div>

<footer class="mt-24 pt-12 pb-16 px-6 border-t border-gray-200 max-w-7xl mx-auto">
    <div class="grid grid-cols-1 md:grid-cols-2 gap-12 md:gap-24">
        
        <div>
            <h3 class="text-lg font-bold text-black mb-4">Terminos & Condiciones</h3>
            <p class="text-sm text-gray-500 leading-relaxed">
                Al acceder y utilizar este sitio web, usted acepta cumplir con nuestros
                términos de servicio. Urban Kickz se reserva el derecho de actualizar
                estos términos en cualquier momento para reflejar cambios en nuestras
                operaciones o regulaciones legales.
            </p>
        </div>

        <div>
            <h3 class="text-lg font-bold text-black mb-4">Contactanos</h3>
            <ul class="text-sm text-gray-500 flex flex-col gap-3">
                <li><a href="mailto:urbankickz2026@gmail.com" class="hover:text-black transition-colors">urbankickz2026@gmail.com</a></li>
                <li><a href="#" class="hover:text-black transition-colors">@Urban_Kickz_26</a></li>
                <li><a href="#" class="hover:text-black transition-colors">Linkedin</a></li>
            </ul>
        </div>
        
    </div>
</footer>
</body>
</html>
