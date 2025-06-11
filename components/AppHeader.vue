<template>
  <nav class="bg-white shadow-md">
    <div class="container mx-auto px-4">
      <div class="flex justify-between items-center h-16">
        <!-- Logo on the left -->
        <div class="flex-shrink-0">
          <nuxt-link to="/" class="flex items-center">
            <!-- <img src="/Logo.png" alt="Company Logo" class="h-8 w-auto" /> -->
          </nuxt-link>
        </div>

        <!-- Mobile menu button -->
        <div class="flex md:hidden">
          <button @click="isOpen = !isOpen" type="button" class="text-gray-500 hover:text-gray-700 focus:outline-none">
            <svg class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
              <path v-if="isOpen" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12" />
              <path v-else stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16" />
            </svg>
          </button>
        </div>

        <!-- Desktop navigation links on the right -->
        <div class="hidden md:flex md:items-center md:space-x-6">
          <nuxt-link to="/" class="text-gray-700 hover:text-blue-600 px-3 py-2 font-medium">Home</nuxt-link>
          <nuxt-link to="/about" class="text-gray-700 hover:text-blue-600 px-3 py-2 font-medium">About Us</nuxt-link>
          <nuxt-link to="/services" class="text-gray-700 hover:text-blue-600 px-3 py-2 font-medium">Services</nuxt-link>
          <nuxt-link to="/jobs" class="text-gray-700 hover:text-blue-600 px-3 py-2 font-medium">Jobs</nuxt-link>
          <nuxt-link to="/careers" class="text-gray-700 hover:text-blue-600 px-3 py-2 font-medium">Career</nuxt-link>
          <nuxt-link to="/contact" class="text-gray-700 hover:text-blue-600 px-3 py-2 font-medium">Contact Us</nuxt-link>
        </div>
      </div>

      <!-- Mobile menu -->
      <div v-if="isOpen" class="md:hidden">
        <div class="px-2 pt-2 pb-3 space-y-1 sm:px-3">
          <nuxt-link to="/" class="block px-3 py-2 text-gray-700 hover:text-blue-600 font-medium">Home</nuxt-link>
          <nuxt-link to="/about" class="block px-3 py-2 text-gray-700 hover:text-blue-600 font-medium">About Us</nuxt-link>
          <nuxt-link to="/services" class="block px-3 py-2 text-gray-700 hover:text-blue-600 font-medium">Services</nuxt-link>
          <nuxt-link to="/jobs" class="block px-3 py-2 text-gray-700 hover:text-blue-600 font-medium">Jobs</nuxt-link>
          <nuxt-link to="/careers" class="block px-3 py-2 text-gray-700 hover:text-blue-600 font-medium">Career</nuxt-link>
          <nuxt-link to="/contact" class="block px-3 py-2 text-gray-700 hover:text-blue-600 font-medium">Contact Us</nuxt-link>
        </div>
      </div>
    </div>
  </nav>
</template>

<script>
export default {
  data() {
    return {
      isOpen: false
    }
  }
}
</script>