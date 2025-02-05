<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kavishka Photography</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="style.css">
</head>
<body class="bg-gray-900 text-white">

    <!-- Navbar -->
    <nav class="flex justify-between items-center p-5 bg-gray-800 shadow-md">
        <h1 class="text-2xl font-bold">Kavishka Photography</h1>
        <ul class="flex space-x-6">
            <li><a href="#" class="hover:text-gray-400">Home</a></li>
            <li><a href="#" class="hover:text-gray-400">Gallery</a></li>
            <li><a href="#" class="hover:text-gray-400">Services</a></li>
            <li><a href="#" class="hover:text-gray-400">Contact</a></li>
        </ul>
    </nav>

    <!-- Hero Section -->
    <section class="relative h-screen flex items-center justify-center text-center">
        <div class="absolute inset-0 bg-cover bg-center opacity-50" style="background-image: url('https://source.unsplash.com/1600x900/?photography')"></div>
        <div class="relative z-10">
            <h2 class="text-4xl font-extrabold">Capture the Perfect Moment</h2>
            <p class="mt-4 text-lg text-gray-300">Professional photography services to make your memories last forever.</p>
            <a href="#" class="mt-6 px-6 py-3 bg-blue-600 hover:bg-blue-700 text-white font-bold rounded-lg shadow-lg inline-block">Explore Gallery</a>
        </div>
    </section>

    <!-- Features Section -->
    <section class="p-10">
        <h3 class="text-3xl font-bold text-center mb-6">Why Choose Us?</h3>
        <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
            <div class="p-6 bg-gray-800 rounded-lg shadow-md">
                <h4 class="text-xl font-semibold">High-Quality Photos</h4>
                <p class="mt-2 text-gray-300">We deliver crisp, high-resolution images with professional editing.</p>
            </div>
            <div class="p-6 bg-gray-800 rounded-lg shadow-md">
                <h4 class="text-xl font-semibold">Experienced Team</h4>
                <p class="mt-2 text-gray-300">Our team consists of passionate photographers with years of experience.</p>
            </div>
            <div class="p-6 bg-gray-800 rounded-lg shadow-md">
                <h4 class="text-xl font-semibold">Affordable Pricing</h4>
                <p class="mt-2 text-gray-300">We offer high-quality photography services at budget-friendly rates.</p>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <footer class="text-center py-5 bg-gray-800">
        <p>&copy; 2025 Kavishka Photography. All Rights Reserved.</p>
    </footer>

</body>
</html>
