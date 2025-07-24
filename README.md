<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Welcome to GitHub Page</title>
    <!-- Tailwind CSS CDN for basic styling -->
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        /* Custom styles for the body to ensure full height and centering */
        body {
            font-family: "Inter", sans-serif; /* Using Inter font as per instructions */
            min-height: 100vh; /* Ensure body takes full viewport height */
            display: flex; /* Use flexbox for centering content */
            justify-content: center; /* Center horizontally */
            align-items: center; /* Center vertically */
            background-color: #e0f2f7; /* Lighter blue background color */
            margin: 0; /* Remove default body margin */
        }
    </style>
</head>
<body class="bg-blue-50 flex items-center justify-center min-h-screen">
    <div class="bg-gradient-to-r from-blue-500 to-purple-600 p-10 rounded-xl shadow-2xl text-center transform hover:scale-105 transition-transform duration-300">
        <h1 class="text-5xl md:text-6xl font-extrabold text-white mb-4 drop-shadow-lg">Welcome to GitHub!</h1>
        <p class="text-xl md:text-2xl text-blue-100 italic">Your journey into open source begins here.</p>
    </div>
</body>
</html>
