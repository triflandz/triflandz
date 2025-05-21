<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Triflandz Construction Inc.</title>
  <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
</head>
<body class="bg-gray-50 text-gray-800">
  <!-- Header -->
  <header class="bg-white shadow p-4">
    <div class="container mx-auto flex justify-between items-center">
      <h1 class="text-xl font-bold">Triflandz Construction Inc.</h1>
      <nav class="space-x-4">
        <a href="#home" class="hover:text-blue-600">Home</a>
        <a href="#about" class="hover:text-blue-600">About</a>
        <a href="#services" class="hover:text-blue-600">Services</a>
        <a href="#projects" class="hover:text-blue-600">Projects</a>
        <a href="#contact" class="hover:text-blue-600">Contact</a>
      </nav>
    </div>
  </header>

  <!-- Hero -->
  <section id="home" class="bg-blue-600 text-white text-center py-20">
    <h2 class="text-4xl font-bold mb-4">Building Your Vision, Delivering Excellence</h2>
    <p class="text-lg">Your trusted partner in construction and engineering</p>
    <a href="#contact" class="mt-6 inline-block bg-white text-blue-600 px-6 py-2 rounded-full font-semibold">Get a Quote</a>
  </section>

  <!-- About Us -->
  <section id="about" class="py-16 px-6 bg-white">
    <div class="container mx-auto max-w-4xl">
      <h3 class="text-3xl font-bold mb-4">About Us</h3>
      <p class="mb-4">Triflandz Construction Inc. is a trusted name in the Philippine construction industry, offering expert services in general construction, electrical systems, and project management. Based in Davao City, we are committed to quality, innovation, and reliability.</p>
      <p><strong>Vision:</strong> To be a leading construction company in the Philippines, recognized for excellence, innovation, and integrity in all our projects.</p>
      <p><strong>Mission:</strong> Deliver high-quality projects on time, within budget, and beyond expectations while prioritizing safety and sustainability.</p>
    </div>
  </section>

  <!-- Services -->
  <section id="services" class="py-16 px-6 bg-gray-100">
    <div class="container mx-auto max-w-5xl">
      <h3 class="text-3xl font-bold mb-6 text-center">Our Services</h3>
      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">
        <div class="p-6 bg-white rounded shadow">
          <h4 class="font-semibold text-lg mb-2">General Construction</h4>
          <p>We handle residential, commercial, and industrial construction projects from start to finish.</p>
        </div>
        <div class="p-6 bg-white rounded shadow">
          <h4 class="font-semibold text-lg mb-2">Electrical Design & Installation</h4>
          <p>Expert electrical engineering services for safe and efficient power systems.</p>
        </div>
        <div class="p-6 bg-white rounded shadow">
          <h4 class="font-semibold text-lg mb-2">Civil & Structural Works</h4>
          <p>Reliable infrastructure development and building construction services.</p>
        </div>
        <div class="p-6 bg-white rounded shadow">
          <h4 class="font-semibold text-lg mb-2">Renovations</h4>
          <p>Modernize and upgrade existing properties with our skilled renovation team.</p>
        </div>
        <div class="p-6 bg-white rounded shadow">
          <h4 class="font-semibold text-lg mb-2">Mechanical and Plumbing</h4>
          <p>Comprehensive MEP services tailored to project requirements.</p>
        </div>
        <div class="p-6 bg-white rounded shadow">
          <h4 class="font-semibold text-lg mb-2">Project Management</h4>
          <p>From planning to execution, we ensure your projects run smoothly and successfully.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Projects -->
  <section id="projects" class="py-16 px-6">
    <div class="container mx-auto max-w-5xl">
      <h3 class="text-3xl font-bold mb-6 text-center">Our Projects</h3>
      <p class="text-center mb-8">A showcase of our completed and ongoing construction work.</p>
      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">
        <!-- Example project -->
        <div class="bg-white rounded shadow p-4">
          <img src="https://via.placeholder.com/400x200" alt="Project 1" class="mb-4 rounded">
          <h4 class="font-semibold">Residential Housing Project</h4>
          <p class="text-sm text-gray-600">Completed 2024, Davao City</p>
        </div>
        <!-- Add more projects similarly -->
      </div>
    </div>
  </section>

  <!-- Contact -->
  <section id="contact" class="py-16 px-6 bg-gray-100">
    <div class="container mx-auto max-w-3xl">
      <h3 class="text-3xl font-bold mb-6 text-center">Contact Us</h3>
      <form class="bg-white p-6 rounded shadow space-y-4">
        <input type="text" placeholder="Your Name" class="w-full border p-2 rounded" required>
        <input type="email" placeholder="Your Email" class="w-full border p-2 rounded" required>
        <textarea placeholder="Your Message" class="w-full border p-2 rounded h-32" required></textarea>
        <button type="submit" class="bg-blue-600 text-white px-4 py-2 rounded">Send Message</button>
      </form>
      <div class="mt-8 text-center">
        <p><strong>Address:</strong> Phase 6 Block 11 Lot 7, Decahomes Mintal, Davao City</p>
        <p><strong>Email:</strong> info@triflandzconstruction.com</p>
        <p><strong>Phone:</strong> +63 900 000 0000</p>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer class="bg-white text-center p-4 shadow-inner mt-10">
    <p class="text-sm">&copy; 2025 Triflandz Construction Inc. All rights reserved.</p>
  </footer>
</body>
</html>
