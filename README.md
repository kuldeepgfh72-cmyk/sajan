# sajan<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>KuldeepAmazon | Shop Unique</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        :root {
            --brand-gold: #ff9900;
            --brand-dark: #131921;
        }
        body { background-color: #f3f4f6; }
        .hero-gradient {
            background: linear-gradient(180deg, rgba(0,0,0,0.7) 0%, rgba(243,244,246,1) 100%), 
                        url('https://images.unsplash.com/photo-1607082348824-0a96f2a4b9da?auto=format&fit=crop&q=80&w=2000');
            background-size: cover;
            height: 400px;
        }
    </style>
</head>
<body>

    <!-- Navigation -->
    <nav class="bg-[#131921] text-white p-3 flex items-center justify-between sticky top-0 z-50">
        <div class="flex items-center gap-4">
            <h1 class="text-2xl font-bold text-[#ff9900] tracking-tighter">kuldeepamazon</h1>
            <div class="hidden md:flex text-sm items-center gap-1 border border-transparent hover:border-white p-1 cursor-pointer">
                <span>📍</span>
                <div><p class="text-gray-400 text-xs">Deliver to</p><p class="font-bold">India</p></div>
            </div>
        </div>

        <div class="flex-grow mx-4 hidden sm:flex">
            <input type="text" class="w-full p-2 rounded-l-md text-black outline-none" placeholder="Search KuldeepAmazon Unique Finds...">
            <button class="bg-[#ff9900] p-2 rounded-r-md hover:bg-yellow-500 transition">🔍</button>
        </div>

        <div class="flex items-center gap-6 text-sm">
            <div class="cursor-pointer">
                <p>Hello, Sign in</p>
                <p class="font-bold">Account & Lists</p>
            </div>
            <div class="cursor-pointer font-bold text-xl">
                🛒 <span class="text-[#ff9900]">0</span>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <div class="hero-gradient flex items-end p-8">
        <h2 class="text-4xl font-bold text-white mb-10">Welcome to the Unique Side of Shopping.</h2>
    </div>

    <!-- Product Grid -->
    <main class="max-w-7xl mx-auto -mt-20 p-4 grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-6">
        
        <!-- Category Card 1 -->
        <div class="bg-white p-6 shadow-md rounded-sm">
            <h3 class="text-xl font-bold mb-4">Unique Electronics</h3>
            <img src="https://images.unsplash.com/photo-1526733158272-a1b42a2d3558?auto=format&fit=crop&q=80&w=500" alt="tech" class="mb-4">
            <a href="#" class="text-blue-600 hover:underline">Explore now</a>
        </div>

        <!-- Category Card 2 -->
        <div class="bg-white p-6 shadow-md rounded-sm">
            <h3 class="text-xl font-bold mb-4">Kuldeep's Picks</h3>
            <img src="https://images.unsplash.com/photo-1523275335684-37898b6baf30?auto=format&fit=crop&q=80&w=500" alt="watch" class="mb-4">
            <a href="#" class="text-blue-600 hover:underline">See more</a>
        </div>

        <!-- Category Card 3 -->
        <div class="bg-white p-6 shadow-md rounded-sm">
            <h3 class="text-xl font-bold mb-4">Home Decor</h3>
            <img src="https://images.unsplash.com/photo-1513506494265-99b159db444b?auto=format&fit=crop&q=80&w=500" alt="home" class="mb-4">
            <a href="#" class="text-blue-600 hover:underline">Shop styles</a>
        </div>

        <!-- Category Card 4 -->
        <div class="bg-white p-6 shadow-md rounded-sm">
            <h3 class="text-xl font-bold mb-4">Sign in for Best Experience</h3>
            <button class="w-full bg-[#ffd814] py-2 rounded-md shadow-sm border border-yellow-400 mb-2">Sign in securely</button>
            <p class="text-xs text-gray-500">New customer? <a href="#" class="text-blue-600">Start here.</a></p>
        </div>

    </main>

    <footer class="mt-20 bg-[#232f3e] text-white p-10 text-center">
        <p class="text-sm">© 2026, KuldeepAmazon.com, Inc. or its affiliates</p>
    </footer>

</body>
</html>
