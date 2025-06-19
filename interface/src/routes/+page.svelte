<script>
    // No complex Svelte logic needed for this static page example.
    // Dynamic content or interactions would go here.
</script>

<div class="min-h-screen bg-black text-white font-sans antialiased">

    <header class="navbar bg-black text-white p-4 sticky top-0 z-50 shadow-xl border-b border-gray-800">
        <div class="navbar-start">
            <div class="dropdown">
                <label tabindex="0" class="btn btn-ghost lg:hidden">
                    <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h8m-8 6h16" /></svg>
                </label>
                <ul tabindex="0" class="menu menu-sm dropdown-content mt-3 z-[1] p-2 shadow bg-base-100 rounded-box w-52 text-base-content">
                    <li><a href="#features">Features</a></li>
                    <li><a href="#pricing">Pricing</a></li>
                    <li><a href="#testimonials">Testimonials</a></li>
                    <li><a href="#faq">FAQ</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </div>
            <a href="/" class="btn btn-ghost normal-case text-2xl font-bold text-transparent bg-clip-text bg-gradient-to-r from-blue-400 to-purple-600">
                <img src="/assets/icons/indie-kit.svg" alt="Indie Kit Logo" class="h-9 w-9 mr-2" />
                Indie Kit
            </a>
        </div>
        <div class="navbar-center hidden lg:flex">
            <ul class="menu menu-horizontal px-1">
                <li><a href="#features" class="font-medium text-lg hover:text-blue-400 transition-colors">Features</a></li>
                <li><a href="#pricing" class="font-medium text-lg hover:text-blue-400 transition-colors">Pricing</a></li>
                <li><a href="#testimonials" class="font-medium text-lg hover:text-blue-400 transition-colors">Testimonials</a></li>
                <li><a href="#faq" class="font-medium text-lg hover:text-blue-400 transition-colors">FAQ</a></li>
                <li><a href="#contact" class="font-medium text-lg hover:text-blue-400 transition-colors">Contact</a></li>
            </ul>
        </div>
        <div class="navbar-end">
            <a href="#" class="btn btn-primary rounded-full px-8 py-3 text-lg"
               style="background: linear-gradient(to right, #60A5FA, #A78BFA); color: white; border: none; /* Custom gradient */">
                Get started
            </a>
        </div>
    </header>

    <main>
        <section class="hero min-h-screen flex items-center justify-center text-center p-8 relative overflow-hidden bg-gradient-to-br from-gray-950 via-black to-gray-900">
            <div class="max-w-5xl mx-auto px-4 z-10">
                <h1 class="text-7xl md:text-8xl lg:text-9xl font-extrabold mb-6 tracking-tight leading-none text-transparent bg-clip-text bg-gradient-to-r from-blue-400 via-purple-500 to-pink-500">
                    Launch your AI SaaS <br class="hidden sm:inline" /> in a weekend.
                </h1>
                <p class="text-2xl md:text-3xl mb-10 opacity-80 max-w-3xl mx-auto leading-relaxed text-white">
                    Indie Kit is a NextJS 15 boilerplate with all the features you need to build your SaaS, AI, or B2B application and get it to market faster.
                </p>
                <div class="flex flex-col sm:flex-row gap-6 justify-center">
                    <a href="#" class="btn btn-lg rounded-full px-10 py-4 text-xl shadow-lg"
                       style="background: linear-gradient(to right, #60A5FA, #A78BFA); color: white; border: none; /* Custom gradient */">
                        Get Started
                    </a>
                    <a href="#" class="btn btn-lg btn-outline text-white border-2 border-white rounded-full px-10 py-4 text-xl shadow-lg hover:bg-white hover:text-black">
                        View Demo
                    </a>
                </div>
                <div class="mt-20 relative">
                    <img src="/assets/images/video-thumbnail.jpeg" alt="Product Demo Thumbnail" class="rounded-xl shadow-2xl mx-auto max-w-full h-auto border-4 border-gray-700" />
                    <div class="absolute inset-0 flex items-center justify-center bg-black bg-opacity-50 rounded-xl cursor-pointer hover:bg-opacity-30 transition-opacity duration-300">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-20 w-20 text-white opacity-80" viewBox="0 0 20 20" fill="currentColor">
                            <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zM9.555 7.168A1 1 0 008 8v4a1 1 0 001.555.832l3-2a1 1 0 000-1.664l-3-2z" clip-rule="evenodd" />
                        </svg>
                    </div>
                </div>
            </div>
        </section>

        <section id="features" class="py-24 bg-gray-950 text-white">
            <div class="container mx-auto px-4 text-center">
                <h2 class="text-6xl font-extrabold mb-6 text-transparent bg-clip-text bg-gradient-to-r from-blue-300 to-purple-500">Features</h2>
                <p class="text-2xl mb-16 opacity-80 max-w-3xl mx-auto leading-relaxed">Everything you need to ship. Nothing you don't. Build with confidence.</p>

                <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-10">
                    <div class="card bg-gray-900 shadow-xl p-8 text-left rounded-xl border border-gray-800 hover:border-blue-500 transition-colors duration-300">
                        <figure class="mb-6 flex justify-center md:justify-start">
                            <img src="/assets/icons/indie-kit.svg" alt="NextJS Icon" class="h-16 w-16" />
                        </figure>
                        <h3 class="card-title text-3xl font-bold mb-3 text-blue-400">NextJS 15 Ready</h3>
                        <p class="text-gray-400 text-lg leading-relaxed">Built with the latest NextJS for optimal performance and a cutting-edge developer experience.</p>
                    </div>
                    <div class="card bg-gray-900 shadow-xl p-8 text-left rounded-xl border border-gray-800 hover:border-green-400 transition-colors duration-300">
                        <figure class="mb-6 flex justify-center md:justify-start">
                            <img src="/assets/icons/inngest.svg" alt="Inngest Icon" class="h-16 w-16" />
                        </figure>
                        <h3 class="card-title text-3xl font-bold mb-3 text-green-400">Automated Workflows (Inngest)</h3>
                        <p class="text-gray-400 text-lg leading-relaxed">Integrated with Inngest for powerful background jobs, email sending, and reliable event-driven automation.</p>
                    </div>
                    <div class="card bg-gray-900 shadow-xl p-8 text-left rounded-xl border border-gray-800 hover:border-purple-400 transition-colors duration-300">
                        <figure class="mb-6 flex justify-center md:justify-start">
                            <img src="/assets/icons/seo.svg" alt="SEO Icon" class="h-16 w-16" />
                        </figure>
                        <h3 class="card-title text-3xl font-bold mb-3 text-purple-400">SEO Optimized</h3>
                        <p class="text-gray-400 text-lg leading-relaxed">Comes with built-in SEO best practices, meta tag management, and sitemap generation for top search rankings.</p>
                    </div>
                    <div class="card bg-gray-900 shadow-xl p-8 text-left rounded-xl border border-gray-800 hover:border-red-400 transition-colors duration-300">
                        <figure class="mb-6 flex justify-center md:justify-start">
                            <img src="/assets/icons/cursor.svg" alt="Auth Icon" class="h-16 w-16" />
                        </figure>
                        <h3 class="card-title text-3xl font-bold mb-3 text-red-400">Authentication (Auth.js)</h3>
                        <p class="text-gray-400 text-lg leading-relaxed">Robust and secure user authentication with various providers (Google, GitHub, Email) using Auth.js.</p>
                    </div>
                    <div class="card bg-gray-900 shadow-xl p-8 text-left rounded-xl border border-gray-800 hover:border-pink-400 transition-colors duration-300">
                        <figure class="mb-6 flex justify-center md:justify-start">
                            <img src="/assets/icons/neon.svg" alt="Neon DB Icon" class="h-16 w-16" />
                        </figure>
                        <h3 class="card-title text-3xl font-bold mb-3 text-pink-400">Scalable Database (Neon)</h3>
                        <p class="text-gray-400 text-lg leading-relaxed">PostgreSQL database integration with Neon for serverless, scalable, and high-performance data storage.</p>
                    </div>
                    <div class="card bg-gray-900 shadow-xl p-8 text-left rounded-xl border border-gray-800 hover:border-yellow-400 transition-colors duration-300">
                        <figure class="mb-6 flex justify-center md:justify-start">
                            <img src="/assets/icons/magic-ui.png" alt="Magic UI Icon" class="h-16 w-16" />
                        </figure>
                        <h3 class="card-title text-3xl font-bold mb-3 text-yellow-400">Stunning UI (Magic UI)</h3>
                        <p class="text-gray-400 text-lg leading-relaxed">Includes beautiful, customizable, and accessible UI components to accelerate your frontend development.</p>
                    </div>
                </div>
            </div>
        </section>

        <section id="testimonials" class="py-24 bg-gray-950 text-white">
            <div class="container mx-auto px-4 text-center">
                <h2 class="text-6xl font-extrabold mb-6 text-transparent bg-clip-text bg-gradient-to-r from-green-300 to-teal-500">What people are saying</h2>
                <p class="text-2xl mb-16 opacity-80 max-w-3xl mx-auto leading-relaxed">Don't just take our word for it. See what real users think.</p>

                <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                    <div class="card bg-gray-900 shadow-xl p-8 rounded-xl border border-gray-800">
                        <p class="text-xl font-medium mb-6 text-gray-300 leading-relaxed">"Indie Kit saved me weeks of development time! The features are exactly what a SaaS needs from day one. Highly recommend for any startup."</p>
                        <div class="flex items-center justify-center sm:justify-start">
                            <div class="avatar mr-4">
                                <div class="w-16 rounded-full border-2 border-blue-400">
                                    <img src="https://picsum.photos/seed/person1/80/80" alt="Avatar" />
                                </div>
                            </div>
                            <div>
                                <h4 class="text-xl font-semibold text-white">Alex Johnson</h4>
                                <p class="text-gray-400">Founder, InnovateNow</p>
                            </div>
                        </div>
                    </div>
                    <div class="card bg-gray-900 shadow-xl p-8 rounded-xl border border-gray-800">
                        <p class="text-xl font-medium mb-6 text-gray-300 leading-relaxed">"The codebase is incredibly clean and well-structured. Getting started was a breeze, and the included integrations are a lifesaver. Top-notch boilerplate!"</p>
                        <div class="flex items-center justify-center sm:justify-start">
                            <div class="avatar mr-4">
                                <div class="w-16 rounded-full border-2 border-purple-400">
                                    <img src="https://picsum.photos/seed/person2/80/80" alt="Avatar" />
                                </div>
                            </div>
                            <div>
                                <h4 class="text-xl font-semibold text-white">Maria Garcia</h4>
                                <p class="text-gray-400">CTO, TechSpark Solutions</p>
                            </div>
                        </div>
                    </div>
                    <div class="card bg-gray-900 shadow-xl p-8 rounded-xl border border-gray-800">
                        <p class="text-xl font-medium mb-6 text-gray-300 leading-relaxed">"Finally, a boilerplate that understands what indie hackers truly need. The speed to market it provides is unparalleled. Worth every penny!"</p>
                        <div class="flex items-center justify-center sm:justify-start">
                            <div class="avatar mr-4">
                                <div class="w-16 rounded-full border-2 border-pink-400">
                                    <img src="https://picsum.photos/seed/person3/80/80" alt="Avatar" />
                                </div>
                            </div>
                            <div>
                                <h4 class="text-xl font-semibold text-white">David Lee</h4>
                                <p class="text-gray-400">Indie Developer</p>
                            </div>
                        </div>
                    </div>
                </div>
                <a href="#" class="btn btn-outline btn-lg mt-16 px-10 py-4 text-xl rounded-full text-white border-white hover:bg-white hover:text-black">Read More Testimonials</a>
            </div>
        </section>

        <section id="pricing" class="py-24 bg-black text-white">
            <div class="container mx-auto px-4 text-center">
                <h2 class="text-6xl font-extrabold mb-6 text-transparent bg-clip-text bg-gradient-to-r from-yellow-300 to-orange-500">Pricing</h2>
                <p class="text-2xl mb-16 opacity-80 max-w-3xl mx-auto leading-relaxed">Choose the perfect plan to kickstart your next big idea.</p>

                <div class="grid grid-cols-1 lg:grid-cols-2 gap-10 max-w-5xl mx-auto">
                    <div class="card bg-gray-900 shadow-xl p-10 rounded-xl border border-gray-800 flex flex-col items-center">
                        <h3 class="text-4xl font-bold mb-4 text-blue-400">Starter</h3>
                        <p class="text-6xl font-extrabold mb-8">$199 <span class="text-2xl opacity-70 ml-2">one-time</span></p>
                        <ul class="list-none text-left w-full mb-10 space-y-4 text-xl">
                            <li class="flex items-center"><svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8 mr-3 text-success" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7" /></svg> Access to Boilerplate</li>
                            <li class="flex items-center"><svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8 mr-3 text-success" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7" /></svg> Basic Documentation</li>
                            <li class="flex items-center"><svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8 mr-3 text-success" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7" /></svg> Community Support</li>
                            <li class="flex items-center text-gray-500"><svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8 mr-3" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12" /></svg> Advanced Components</li>
                            <li class="flex items-center text-gray-500"><svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8 mr-3" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12" /></svg> Priority Email Support</li>
                            <li class="flex items-center text-gray-500"><svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8 mr-3" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12" /></svg> Lifetime Updates</li>
                        </ul>
                        <a href="#" class="btn btn-primary btn-lg rounded-full w-full py-4 text-xl shadow-lg"
                           style="background: linear-gradient(to right, #60A5FA, #A78BFA); color: white; border: none; /* Custom gradient */">
                            Get Started
                        </a>
                    </div>

                    <div class="card bg-gray-900 shadow-xl p-10 rounded-xl border border-blue-600 flex flex-col items-center relative">
                        <div class="badge badge-primary absolute -top-4 right-8 bg-blue-500 text-white p-3 px-6 rounded-full text-lg font-semibold shadow-lg transform rotate-3">Recommended</div>
                        <h3 class="text-4xl font-bold mb-4 text-blue-400">Pro</h3>
                        <p class="text-6xl font-extrabold mb-8">$399 <span class="text-2xl opacity-70 ml-2">one-time</span></p>
                        <ul class="list-none text-left w-full mb-10 space-y-4 text-xl">
                            <li class="flex items-center"><svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8 mr-3 text-success" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7" /></svg> All Starter Features</li>
                            <li class="flex items-center"><svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8 mr-3 text-success" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7" /></svg> Advanced Components</li>
                            <li class="flex items-center"><svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8 mr-3 text-success" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7" /></svg> Priority Email Support</li>
                            <li class="flex items-center"><svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8 mr-3 text-success" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7" /></svg> Lifetime Updates</li>
                        </ul>
                        <a href="#" class="btn btn-primary btn-lg rounded-full w-full py-4 text-xl shadow-lg"
                           style="background: linear-gradient(to right, #3B82F6, #8B5CF6); color: white; border: none; /* Custom gradient for recommended */">
                            Go Pro
                        </a>
                    </div>
                </div>
            </div>
        </section>

        <section id="faq" class="py-24 bg-gray-950 text-white">
            <div class="container mx-auto px-4">
                <h2 class="text-6xl font-extrabold text-center mb-16 text-transparent bg-clip-text bg-gradient-to-r from-orange-300 to-red-500">Frequently Asked Questions</h2>

                <div class="max-w-4xl mx-auto space-y-6">
                    <div class="collapse collapse-plus bg-gray-900 border border-gray-800 rounded-xl shadow-md">
                        <input type="radio" name="my-accordion-3" checked="checked" />
                        <div class="collapse-title text-2xl font-semibold text-white">
                            What is Indie Kit?
                        </div>
                        <div class="collapse-content text-gray-400 text-lg leading-relaxed">
                            <p>Indie Kit is a comprehensive NextJS 15 boilerplate meticulously crafted to help you rapidly launch your SaaS, AI, or B2B application. It includes all the essential features you need from secure authentication to a scalable database, allowing you to focus on your unique product idea.</p>
                        </div>
                    </div>
                    <div class="collapse collapse-plus bg-gray-900 border border-gray-800 rounded-xl shadow-md">
                        <input type="radio" name="my-accordion-3" />
                        <div class="collapse-title text-2xl font-semibold text-white">
                            Who is Indie Kit for?
                        </div>
                        <div class="collapse-content text-gray-400 text-lg leading-relaxed">
                            <p>It's perfectly suited for indie hackers, startup founders, and developers who want to save significant time and resources by starting with a robust, feature-rich foundation rather than building everything from scratch. If you're looking to launch faster and smarter, Indie Kit is for you.</p>
                        </div>
                    </div>
                    <div class="collapse collapse-plus bg-gray-900 border border-gray-800 rounded-xl shadow-md">
                        <input type="radio" name="my-accordion-3" />
                        <div class="collapse-title text-2xl font-semibold text-white">
                            What technologies are included?
                        </div>
                        <div class="collapse-content text-gray-400 text-lg leading-relaxed">
                            <p>Indie Kit is built on a modern stack including NextJS 15 for the frontend/backend, Auth.js for robust authentication, Neon for a scalable PostgreSQL database, Inngest for background workflows, and Tailwind CSS with Magic UI for stunning design and components.</p>
                        </div>
                    </div>
                    <div class="collapse collapse-plus bg-gray-900 border border-gray-800 rounded-xl shadow-md">
                        <input type="radio" name="my-accordion-3" />
                        <div class="collapse-title text-2xl font-semibold text-white">
                            Is support provided?
                        </div>
                        <div class="collapse-content text-gray-400 text-lg leading-relaxed">
                            <p>Yes, all plans include access to our community support. Pro plan users receive priority email support for a faster response to their inquiries, ensuring you're never stuck.</p>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <section id="contact" class="py-24 bg-gradient-to-br from-blue-700 to-purple-900 text-white text-center shadow-inner">
            <div class="container mx-auto px-4">
                <h2 class="text-6xl font-extrabold mb-8">Ready to launch your product?</h2>
                <p class="text-2xl mb-12 max-w-3xl mx-auto opacity-95 leading-relaxed">
                    Join hundreds of successful founders who are already building amazing products with Indie Kit. Your journey to a faster launch starts here.
                </p>
                <a href="#" class="btn btn-lg bg-white text-black hover:bg-gray-200 border-none rounded-full px-12 py-5 text-2xl font-bold shadow-xl">
                    Get Started Today
                </a>
            </div>
        </section>
    </main>

    <footer class="footer footer-center p-10 bg-black text-white border-t border-gray-800">
        <aside>
            <img src="/assets/icons/indie-kit.svg" alt="Indie Kit Logo" class="h-12 w-12 mb-4" />
            <p class="font-bold text-2xl text-transparent bg-clip-text bg-gradient-to-r from-blue-300 to-purple-500">
                Indie Kit.
            </p>
            <p class="text-gray-400 text-lg mt-2">Your foundation for SaaS success. <br />Copyright © {new Date().getFullYear()} - All rights reserved</p>
        </aside>
        <nav>
            <div class="grid grid-flow-col gap-6 text-xl">
                <a href="#" class="link link-hover hover:text-blue-400 transition-colors">Home</a>
                <a href="#features" class="link link-hover hover:text-blue-400 transition-colors">Features</a>
                <a href="#pricing" class="link link-hover hover:text-blue-400 transition-colors">Pricing</a>
                <a href="#testimonials" class="link link-hover hover:text-blue-400 transition-colors">Testimonials</a>
                <a href="#faq" class="link link-hover hover:text-blue-400 transition-colors">FAQ</a>
            </div>
        </nav>
        <nav class="mt-8">
            <div class="grid grid-flow-col gap-6">
                <a href="#" target="_blank" rel="noopener noreferrer" class="text-gray-400 hover:text-white transition-colors">
                    <svg xmlns="http://www.w3.org/2000/svg" width="30" height="30" viewBox="0 0 24 24" fill="currentColor"><path d="M24 4.557c-.883.392-1.832.656-2.828.775 1.017-.609 1.798-1.574 2.165-2.724-.951.564-2.005.974-3.127 1.195-.897-.957-2.178-1.555-3.594-1.555-3.179 0-5.515 2.966-4.797 6.045-4.091-.205-7.719-2.165-10.148-5.144-1.29 2.213-.669 5.108 1.523 6.574-.806-.026-1.566-.247-2.229-.616-.054 2.281 1.581 4.415 3.949 4.89-.693.188-1.452.232-2.224.084.626 1.956 2.444 3.379 4.607 3.419-2.071 1.623-4.664 2.603-7.493 2.603-.483 0-.957-.029-1.424-.084 2.59 1.944 5.64 3.097 8.956 3.097 10.133 0 15.683-8.373 15.683-15.683 0-.533-.01-1.054-.029-1.562.774-.555 1.449-1.246 1.996-2.146z"/></svg>
                </a>
                <a href="#" target="_blank" rel="noopener noreferrer" class="text-gray-400 hover:text-white transition-colors">
                    <svg xmlns="http://www.w3.org/2000/svg" width="30" height="30" viewBox="0 0 24 24" fill="currentColor"><path d="M12 0c-6.626 0-12 5.373-12 12 0 5.302 3.438 9.8 8.207 11.387.599.111.793-.261.793-.577v-2.234c-3.338.726-4.033-1.416-4.033-1.416-.546-1.387-1.333-1.756-1.333-1.756-1.082-.745.083-.729.083-.729 1.205.084 1.839 1.237 1.839 1.237 1.07 1.835 2.809 1.305 3.492.997.107-.775.418-1.305.762-1.604-2.665-.305-5.467-1.334-5.467-5.931 0-1.311.469-2.381 1.236-3.221-.124-.303-.535-1.524.117-3.176 0 0 1.008-.322 3.301 1.23.957-.266 1.983-.399 3.003-.404 1.02.005 2.047.138 3.006.404 2.291-1.552 3.297-1.23 3.297-1.23.653 1.653.242 2.874.118 3.176.77.84 1.235 1.911 1.235 3.221 0 4.609-2.807 5.624-5.479 5.921.43.372.823 1.102.823 2.222v3.293c0 .319.192.694.801.576 4.765-1.589 8.196-6.086 8.196-11.386 0-6.627-5.373-12-12-12z"/></svg>
                </a>
            </div>
        </nav>
    </footer>
</div>

<style lang="postcss">
    /*
      Custom PostCSS for gradient text animations,
      as this specific effect is not a standard DaisyUI component.
    */
    @keyframes gradient-pulse {
        0% { background-position: 0% 50%; }
        50% { background-position: 100% 50%; }
        100% { background-position: 0% 50%; }
    }

    .animate-gradient-pulse {
        background-size: 200% auto;
        animation: gradient-pulse 4s ease-in-out infinite;
    }
</style>