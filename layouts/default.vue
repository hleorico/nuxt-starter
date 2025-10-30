<template>
  <div class="min-h-screen bg-[#F8EBD7] text-[#4A4A4A]">
    <!-- Header -->
    <header class="py-5 border-b border-[#E0D8C8] bg-white/80 backdrop-blur">
      <div class="max-w-6xl mx-auto px-6 flex items-center justify-between">
        <a href="/" class="text-lg font-semibold">Leo H</a>
        <nav class="flex gap-6 text-sm">
          <a href="#about" class="hover:text-[#5CA9C7]">About</a>
          <a href="#skills" class="hover:text-[#5CA9C7]">Skills</a>
          <a href="#projects" class="hover:text-[#5CA9C7]">Projects</a>
          <a href="#contact" class="hover:text-[#5CA9C7]">Contact</a>
        </nav>
      </div>
    </header>

    <!-- Page content -->
    <main>
      <slot />
    </main>

    <!-- Footer -->
    <footer class="mt-16 py-8 border-t border-[#E0D8C8] text-center text-sm text-[#4A4A4A]/70">
      © 2025 Leo H · Nuxt + Netlify
    </footer>
  </div>
</template>
