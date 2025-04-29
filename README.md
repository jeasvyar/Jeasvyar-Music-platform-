
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Mortal Music</title>
  <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
</head>
<body class="bg-gray-900 text-white font-sans">
  <header class="p-4 bg-gray-800 shadow-md">
    <div class="container mx-auto flex justify-between items-center">
      <h1 class="text-2xl font-bold">Mortal Music</h1>
      <nav class="space-x-4">
        <a href="#home" class="hover:text-yellow-400">Home</a>
        <a href="#browse" class="hover:text-yellow-400">Browse</a>
        <a href="#upload" class="hover:text-yellow-400">Upload</a>
      </nav>
    </div>
  </header>

  <main class="container mx-auto px-4 py-8">
    <!-- Hero Section -->
    <section id="home" class="text-center py-12">
      <h2 class="text-4xl font-bold mb-4">Discover Independent Sound</h2>
      <p class="text-gray-300 mb-6">Stream, share, and support emerging artists.</p>
      <a href="#upload" class="bg-yellow-400 text-gray-900 px-6 py-2 rounded-full font-bold hover:bg-yellow-300">Upload Your Track</a>
    </section>

    <!-- Browse Section -->
    <section id="browse" class="py-8">
      <h3 class="text-2xl font-semibold mb-4">Trending Tracks</h3>
      <div class="grid md:grid-cols-3 gap-6">
        <!-- Placeholder track cards -->
        <div class="bg-gray-800 p-4 rounded-lg shadow">
          <h4 class="font-bold">Track Title</h4>
          <p class="text-sm text-gray-400">Artist Name</p>
          <audio controls class="w-full mt-2">
            <source src="sample.mp3" type="audio/mpeg">
            Your browser does not support the audio element.
          </audio>
        </div>
        <!-- More tracks can be added here -->
      </div>
    </section>

    <!-- Upload Section -->
    <section id="upload" class="py-8">
      <h3 class="text-2xl font-semibold mb-4">Upload Your Music</h3>
      <form class="bg-gray-800 p-6 rounded-lg">
        <div class="mb-4">
          <label class="block mb-1">Track Title</label>
          <input type="text" class="w-full p-2 rounded bg-gray-700 border border-gray-600" placeholder="Enter track title" />
        </div>
        <div class="mb-4">
          <label class="block mb-1">Artist Name</label>
          <input type="text" class="w-full p-2 rounded bg-gray-700 border border-gray-600" placeholder="Your name or alias" />
        </div>
        <div class="mb-4">
          <label class="block mb-1">Upload MP3</label>
          <input type="file" accept="audio/mpeg" class="w-full text-white" />
        </div>
        <button type="submit" class="bg-yellow-400 text-gray-900 px-4 py-2 rounded font-bold hover:bg-yellow-300">Submit</button>
      </form>
    </section>
  </main>

  <footer class="text-center text-sm text-gray-500 py-6 border-t border-gray-700">
    &copy; 2025 Mortal Music. All rights reserved.
  </footer>
</body>
</html>
