<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Video Library</title>
    <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-gray-900 text-white">

    <nav class="p-5 bg-black flex justify-between items-center">
        <h1 class="text-2xl font-bold text-red-600">MYFLIX</h1>
        <div class="space-x-4">
            <a href="#" class="hover:text-red-500">Home</a>
            <a href="#" class="hover:text-red-500">Koleksi</a>
        </div>
    </nav>

    <div class="p-10 text-center">
        <h2 class="text-4xl font-bold mb-4">Koleksi Video Saya</h2>
        <p class="text-gray-400">Belajar membangun interface streaming modern.</p>
    </div>

    <div class="container mx-auto grid grid-cols-1 md:grid-cols-3 gap-6 p-5">
        
        <div class="bg-gray-800 rounded-lg overflow-hidden shadow-lg">
            <div class="aspect-video bg-gray-700 flex items-center justify-center">
                <span class="text-sm">Thumbnail Video 1</span>
            </div>
            <div class="p-4">
                <h3 class="font-bold">Judul Video 1</h3>
                <button class="mt-3 bg-red-600 px-4 py-2 rounded text-sm hover:bg-red-700">Tonton Sekarang</button>
            </div>
        </div>

        </div>

</body>
</html>
