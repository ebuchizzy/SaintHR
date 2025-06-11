<template>
   <AppHeader />
   <div class="relative bg-gray-800 h-96 md:h-screen max-h-screen">
    
    <!-- Background Image -->
    <div class="absolute inset-0">
      <div class="absolute inset-0 bg-black bg-opacity-40"></div>
      <img
        src="/assets/images/image_fx (12).jpg" 
        alt="Business professionals in meeting" 
        class="w-full h-full object-cover opacity-70"
      >
    </div>



    <!-- Hero Content -->
    <div class="relative h-full container mx-auto px-6 flex items-center">
      <div class="max-w-4xl text-white">
        <div class="max-w-4xl text-white bg-opacity-50 p-8 rounded-lg border-x-2 backdrop-blur-md">
        <h1 class="text-4xl md:text-5xl font-bold leading-tight mb-4">
            Your Business, Your People, Our Priority
        </h1>
        
        <a 
          href="#" 
          class="inline-flex items-center justify-center bg-blue-900 hover:bg-blue-800 text-white px-6 py-3 rounded-2xl font-medium transition-colors"
        >
          Join Us
          <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 ml-2" viewBox="0 0 20 20" fill="currentColor">
            <path fill-rule="evenodd" d="M10.293 3.293a1 1 0 011.414 0l6 6a1 1 0 010 1.414l-6 6a1 1 0 01-1.414-1.414L14.586 11H3a1 1 0 110-2h11.586l-4.293-4.293a1 1 0 010-1.414z" clip-rule="evenodd" />
          </svg>
        </a>
      </div>
    </div>
  </div>
  </div>
    <section class="py-16 bg-white">
      <div class="container mx-auto px-4">
        <!-- Header with title and view all services button -->
        <div class="flex justify-between items-center mb-12">
          <h2 class="text-3xl md:text-4xl font-bold text-gray-900">
            Your Business, Your People, Our Priority
          </h2>
          <a href="#" class="flex items-center text-gray-600 border border-gray-300 rounded-full px-4 py-2 hover:bg-gray-50 transition-colors">
            View All Services
            <svg class="ml-2 h-4 w-4" viewBox="0 0 20 20" fill="currentColor">
              <path fill-rule="evenodd" d="M10.293 3.293a1 1 0 011.414 0l6 6a1 1 0 010 1.414l-6 6a1 1 0 01-1.414-1.414L14.586 11H3a1 1 0 110-2h11.586l-4.293-4.293a1 1 0 010-1.414z" clip-rule="evenodd" />
            </svg>
          </a>
        </div>
  
        <!-- Services Grid -->
        <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
          <!-- Service 1: Recruitment & Talent Acquisition -->
          <div class="service-card">
            <div class="mb-4">
              <svg class="h-8 w-8 text-blue-800" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z" />
              </svg>
            </div>
            <h3 class="text-xl font-semibold mb-3">Recruitment & Talent Acquisition</h3>
            <p class="text-gray-600">
              We help businesses find and hire top talent by managing the entire recruitment process, from job postings and candidate screening to interviews and onboarding. Our goal is to connect you with professionals who fit your company culture and drive growth.
            </p>
          </div>
  
          <!-- Service 2: Payroll & Benefits Administration -->
          <div class="service-card">
            <div class="mb-4">
              <svg class="h-8 w-8 text-blue-800" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z" />
              </svg>
            </div>
            <h3 class="text-xl font-semibold mb-3">Payroll & Benefits Administration</h3>
            <p class="text-gray-600">
              Managing payroll and benefits can be complex, but we simplify it by ensuring accurate salary processing, tax filings, and benefits administration. Our system guarantees that your employees are paid on time while keeping your business legally compliant.
            </p>
          </div>
  
          <!-- Service 3: HR Compliance & Legal Advisory -->
          <div class="service-card">
            <div class="mb-4">
              <svg class="h-8 w-8 text-blue-800" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 21V5a2 2 0 00-2-2H7a2 2 0 00-2 2v16m14 0h2m-2 0h-5m-9 0H3m2 0h5M9 7h1m-1 4h1m4-4h1m-1 4h1m-5 10v-5a1 1 0 011-1h2a1 1 0 011 1v5m-4 0h4" />
              </svg>
            </div>
            <h3 class="text-xl font-semibold mb-3">HR Compliance & Legal Advisory</h3>
            <p class="text-gray-600">
              Staying up to date with labor laws is crucial for every business. We assist with employee contracts, workplace policies, and regulatory compliance, reducing the risk of legal issues and ensuring a safe and structured work environment.
            </p>
          </div>
  
          <!-- Service 4: Employee Training & Development -->
          <div class="service-card">
            <div class="mb-4">
              <svg class="h-8 w-8 text-blue-800" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M8 10h.01M12 10h.01M16 10h.01M9 16H5a2 2 0 01-2-2V6a2 2 0 012-2h14a2 2 0 012 2v8a2 2 0 01-2 2h-5l-5 5v-5z" />
              </svg>
            </div>
            <h3 class="text-xl font-semibold mb-3">Employee Training & Development</h3>
            <p class="text-gray-600">
              We provide customized training programs to enhance employee skills, improve productivity, and foster leadership development. Our learning solutions help businesses create a workforce that is engaged, efficient, and ready to grow.
            </p>
          </div>
  
          <!-- Service 5: Performance & Employee Engagement -->
          <div class="service-card">
            <div class="mb-4">
              <svg class="h-8 w-8 text-blue-800" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 19v-6a2 2 0 00-2-2H5a2 2 0 00-2 2v6a2 2 0 002 2h2a2 2 0 002-2zm0 0V9a2 2 0 012-2h2a2 2 0 012 2v10m-6 0a2 2 0 002 2h2a2 2 0 002-2m0 0V5a2 2 0 012-2h2a2 2 0 012 2v14a2 2 0 01-2 2h-2a2 2 0 01-2-2z" />
              </svg>
            </div>
            <h3 class="text-xl font-semibold mb-3">Performance & Employee Engagement</h3>
            <p class="text-gray-600">
              Motivated workforce leads to higher productivity and better retention. We implement performance management systems, create employee engagement programs, and develop recognition systems that help businesses create a positive and inspiring work culture.
            </p>
          </div>
  
          <!-- Service 6: HR Technology & Automation -->
          <div class="service-card">
            <div class="mb-4">
              <svg class="h-8 w-8 text-blue-800" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 3v2m6-2v2M9 19v2m6-2v2M5 9H3m2 6H3m18-6h-2m2 6h-2M7 19h10a2 2 0 002-2V7a2 2 0 00-2-2H7a2 2 0 00-2 2v10a2 2 0 002 2zM9 9h6v6H9V9z" />
              </svg>
            </div>
            <h3 class="text-xl font-semibold mb-3">HR Technology & Automation</h3>
            <p class="text-gray-600">
              We integrate modern HR technology into your operations to streamline recruiting, payroll, performance tracking, and employee data management. Our digital solutions streamline processes and improve efficiency, allowing you to focus on strategic growth.
            </p>
          </div>
        </div>
      </div>
    </section>

  </template>
  
  <style scoped>
  .service-card {
    padding: 1.5rem;
    border-radius: 0.5rem;
    transition: all 0.3s ease;
  }
  
  .service-card:hover {
    box-shadow: 0 10px 15px -3px rgba(0, 0, 0, 0.1), 0 4px 6px -2px rgba(0, 0, 0, 0.05);
  }
  </style>