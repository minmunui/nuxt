<template>
  <div class="flex flex-col min-h-screen bg-slate-900 text-white">
    <header class="bg-slate-800 shadow-md">
      <nav class="container mx-auto px-6 py-4">
        <div class="text-2xl font-bold">
          My Awesome Blog
        </div>
      </nav>
    </header>

    <main class="flex-grow container mx-auto px-6 py-8">
      <slot />
    </main>
    
    <footer class="bg-slate-800 py-4">
      <div class="container mx-auto px-6 text-center text-slate-400">
        &copy; 2025 My Awesome Blog. All rights reserved.
      </div>
    </footer>
  </div>
</template>


