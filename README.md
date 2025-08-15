
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Rescue Spa Miami - Premium Skincare & Beauty Services</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://cdn.jsdelivr.net/npm/font-awesome@4.7.0/css/font-awesome.min.css" rel="stylesheet">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        primary: '#4A6FA5',
                        secondary: '#E07A5F',
                        accent: '#F4F1DE',
                        dark: '#3D405B',
                        light: '#F8F9FA'
                    },
                    fontFamily: {
                        inter: ['Inter', 'sans-serif'],
                    },
                }
            }
        }
    </script>
    
    <style type="text/tailwindcss">
        @layer utilities {
            .content-auto {
                content-visibility: auto;
            }
            .text-shadow {
                text-shadow: 0 2px 4px rgba(0,0,0,0.1);
            }
            .text-shadow-lg {
                text-shadow: 0 4px 8px rgba(0,0,0,0.2);
            }
            .bg-blur {
                backdrop-filter: blur(8px);
            }
            .scrollbar-hide::-webkit-scrollbar {
                display: none;
            }
            .scrollbar-hide {
                -ms-overflow-style: none;
                scrollbar-width: none;
            }
        }
    </style>
</head>
<body class="font-inter bg-light text-dark antialiased">
    <!-- Navigation -->
    <header id="navbar" class="fixed w-full top-0 z-50 transition-all duration-300">
        <nav class="bg-transparent py-4 px-4 md:px-8 transition-all duration-300">
            <div class="max-w-7xl mx-auto flex justify-between items-center">
                <a href="#" class="flex items-center">
                  <img src="https://i.pinimg.com/736x/04/5f/4d/045f4de293afeb4da59c7bae8706ca97.jpg" class="h-12 w-auto">
                </a>
                
                <!-- Desktop Menu -->
                <div class="hidden md:flex items-center space-x-8">
                    <a href="#about" class="text-light hover:text-secondary transition-colors duration-300 font-medium">About</a>
                    <a href="#services" class="text-light hover:text-secondary transition-colors duration-300 font-medium">Services</a>
                    <a href="#products" class="text-light hover:text-secondary transition-colors duration-300 font-medium">Products</a>
                    <a href="#team" class="text-light hover:text-secondary transition-colors duration-300 font-medium">Our Team</a>
                    <a href="#testimonials" class="text-light hover:text-secondary transition-colors duration-300 font-medium">Testimonials</a>
                    <a href="#contact" class="bg-secondary hover:bg-secondary/90 text-white px-6 py-2 rounded-full transition-all duration-300 shadow-lg hover:shadow-xl transform hover:-translate-y-1">Book Now</a>
                </div>
                
                <!-- Mobile Menu Button -->
                <button id="menu-toggle" class="md:hidden text-light focus:outline-none">
                    <i class="fa fa-bars text-2xl"></i>
                </button>
            </div>
        </nav>
        
        <!-- Mobile Menu -->
        <div id="mobile-menu" class="hidden md:hidden bg-white shadow-lg absolute w-full">
            <div class="container mx-auto px-4 py-4 flex flex-col space-y-4">
                <a href="#about" class="text-dark hover:text-secondary transition-colors duration-300 font-medium py-2 border-b border-gray-100">About</a>
                <a href="#services" class="text-dark hover:text-secondary transition-colors duration-300 font-medium py-2 border-b border-gray-100">Services</a>
                <a href="#products" class="text-dark hover:text-secondary transition-colors duration-300 font-medium py-2 border-b border-gray-100">Products</a>
                <a href="#team" class="text-dark hover:text-secondary transition-colors duration-300 font-medium py-2 border-b border-gray-100">Our Team</a>
                <a href="#testimonials" class="text-dark hover:text-secondary transition-colors duration-300 font-medium py-2 border-b border-gray-100">Testimonials</a>
                <a href="#contact" class="bg-secondary hover:bg-secondary/90 text-white px-6 py-3 rounded-full transition-all duration-300 shadow-lg text-center">Book Now</a>
            </div>
        </div>
    </header>

    <!-- Hero Section with Video Background -->
    <section class="relative h-screen flex items-center justify-center overflow-hidden">
        <div class="absolute inset-0 z-0">
            <video class="object-cover w-full h-full" autoplay muted loop>
                <source src="https://sns-video-hw.xhscdn.com/stream/1/110/258/01e7bdb0645617bc01037001953cf9ba81_258.mp4" type="video/mp4">
                Your browser does not support the video tag.
            </video>
            <div class="absolute inset-0 bg-dark/50"></div>
        </div>
        
        <div class="container mx-auto px-4 z-10 text-center">
            <h1 class="text-[clamp(2.5rem,8vw,5rem)] font-bold text-white leading-tight text-shadow-lg mb-6 animate-fadeIn">
                Rescue Your Skin <span class="text-secondary">Renew Your Beauty</span>
            </h1>
            <p class="text-[clamp(1rem,3vw,1.5rem)] text-light/90 max-w-3xl mx-auto mb-10 text-shadow">
                Premium skincare services tailored to your unique needs in the heart of Miami
            </p>
            <div class="flex flex-col sm:flex-row justify-center gap-4">
                <a href="#services" class="bg-primary hover:bg-primary/90 text-white px-8 py-4 rounded-full transition-all duration-300 shadow-lg hover:shadow-xl transform hover:-translate-y-1 text-lg font-medium">
                    Explore Services
                </a>
                <a href="#contact" class="bg-transparent border-2 border-white hover:border-secondary hover:bg-secondary/10 text-white px-8 py-4 rounded-full transition-all duration-300 shadow-lg hover:shadow-xl transform hover:-translate-y-1 text-lg font-medium">
                    Book Consultation
                </a>
            </div>
        </div>
        
        <div class="absolute bottom-10 left-0 right-0 flex justify-center animate-bounce">
            <a href="#about" class="text-white text-3xl">
                <i class="fa fa-angle-down"></i>
            </a>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="py-20 bg-white">
        <div class="container mx-auto px-4">
            <div class="flex flex-col md:flex-row items-center gap-12">
                <div class="md:w-1/2">
                    <img src="https://i.pinimg.com/736x/68/e4/75/68e47530ce25d717c467271755bf8eee.jpg" alt="Rescue Spa Miami Interior" class="rounded-2xl shadow-xl w-full h-auto transform hover:scale-[1.02] transition-transform duration-500">
                </div>
                
                <div class="md:w-1/2">
                    <h2 class="text-[clamp(1.5rem,3vw,2.5rem)] font-bold text-dark mb-6">About <span class="text-primary">Rescue Spa Miami</span></h2>
                    <div class="w-20 h-1 bg-secondary mb-8"></div>
                    
                    <p class="text-gray-700 mb-6 text-lg leading-relaxed">
                        Founded in Philadelphia by award-winning esthetician Danuta Mieloch, Rescue Spa has been transforming skin for over 30 years. Our Miami location brings the same commitment to excellence, offering personalized treatments that address the unique challenges of Miami's sunny climate.
                    </p>
                    
                    <p class="text-gray-700 mb-8 text-lg leading-relaxed">
                        At Rescue Spa Miami, we believe that beautiful skin is a choice, not a chance. Our philosophy combines advanced technology with natural ingredients to deliver results that are both effective and sustainable.
                    </p>
                    
                    <div class="grid grid-cols-1 sm:grid-cols-2 gap-6 mb-8">
                        <div class="flex items-start">
                            <div class="bg-primary/10 p-3 rounded-full mr-4">
                                <i class="fa fa-certificate text-primary text-xl"></i>
                            </div>
                            <div>
                                <h3 class="font-semibold text-lg mb-2">Expert Care</h3>
                                <p class="text-gray-600">Our team of certified estheticians provides personalized care based on your unique skin needs.</p>
                            </div>
                        </div>
                        
                        <div class="flex items-start">
                            <div class="bg-primary/10 p-3 rounded-full mr-4">
                                <i class="fa fa-leaf text-primary text-xl"></i>
                            </div>
                            <div>
                                <h3 class="font-semibold text-lg mb-2">Premium Products</h3>
                                <p class="text-gray-600">We use only the finest luxury skincare brands known for their efficacy and safety.</p>
                            </div>
                        </div>
                        
                        <div class="flex items-start">
                            <div class="bg-primary/10 p-3 rounded-full mr-4">
                                <i class="fa fa-heart text-primary text-xl"></i>
                            </div>
                            <div>
                                <h3 class="font-semibold text-lg mb-2">Relaxing Environment</h3>
                                <p class="text-gray-600">Our spa provides a tranquil escape where you can unwind and rejuvenate.</p>
                            </div>
                        </div>
                        
                        <div class="flex items-start">
                            <div class="bg-primary/10 p-3 rounded-full mr-4">
                                <i class="fa fa-lightbulb-o text-primary text-xl"></i>
                            </div>
                            <div>
                                <h3 class="font-semibold text-lg mb-2">Advanced Technology</h3>
                                <p class="text-gray-600">State-of-the-art equipment delivers cutting-edge treatments with visible results.</p>
                            </div>
                        </div>
                    </div>
                    
                    <a href="#team" class="inline-flex items-center text-primary font-medium hover:text-secondary transition-colors duration-300">
                        Meet Our Team <i class="fa fa-long-arrow-right ml-2"></i>
                    </a>
                </div>
            </div>
        </div>
    </section>

    <!-- Services Section -->
    <section id="services" class="py-20 bg-accent/30">
        <div class="container mx-auto px-4">
            <div class="text-center max-w-3xl mx-auto mb-16">
                <h2 class="text-[clamp(1.5rem,3vw,2.5rem)] font-bold text-dark mb-6">Our <span class="text-primary">Signature Services</span></h2>
                <div class="w-20 h-1 bg-secondary mx-auto mb-8"></div>
                <p class="text-gray-700 text-lg">
                    Discover our range of premium skincare services designed to address your specific concerns and leave you feeling refreshed and rejuvenated.
                </p>
            </div>
            
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Service Card 1 -->
                <div class="bg-white rounded-2xl shadow-lg overflow-hidden transform hover:-translate-y-2 transition-all duration-500 group">
                    <div class="relative h-60 overflow-hidden">
                        <img src="https://static.wixstatic.com/media/4272c2_79f8f01237904464a58318d20b7fe012~mv2.png/v1/fill/w_431,h_397,al_c,q_85,usm_0.66_1.00_0.01,enc_avif,quality_auto/beauty-by-us-image-1.png" alt="Facial Treatments" class="w-full h-full object-cover transform group-hover:scale-110 transition-transform duration-700">
                        <div class="absolute inset-0 bg-gradient-to-t from-dark/70 to-transparent"></div>
                        <h3 class="absolute bottom-4 left-4 text-white text-xl font-bold">Facial Treatments</h3>
                    </div>
                    
                    <div class="p-6">
                        <p class="text-gray-700 mb-4">
                            Our facial treatments are tailored to your skin type and concerns, using premium products and advanced techniques to deliver visible results.
                        </p>
                        
                        <ul class="space-y-2 mb-6">
                            <li class="flex items-center">
                                <i class="fa fa-check text-primary mr-2"></i>
                                <span>Antioxidant Repair Facial</span>
                            </li>
                            <li class="flex items-center">
                                <i class="fa fa-check text-primary mr-2"></i>
                                <span>Hydrating & Brightening Facial</span>
                            </li>
                            <li class="flex items-center">
                                <i class="fa fa-check text-primary mr-2"></i>
                                <span>Anti-Aging & Collagen Boost</span>
                            </li>
                            <li class="flex items-center">
                                <i class="fa fa-check text-primary mr-2"></i>
                                <span>Acne Treatment & Clarifying</span>
                            </li>
                        </ul>
                        
                        <div class="flex justify-between items-center">
                            <span class="text-primary font-bold text-xl">$180+</span>
                            <a href="#contact" class="bg-secondary hover:bg-secondary/90 text-white px-5 py-2 rounded-full transition-all duration-300">Book Now</a>
                        </div>
                    </div>
                </div>
                
                <!-- Service Card 2 -->
                <div class="bg-white rounded-2xl shadow-lg overflow-hidden transform hover:-translate-y-2 transition-all duration-500 group">
                    <div class="relative h-60 overflow-hidden">
                        <img src="https://i.pinimg.com/736x/9f/67/ed/9f67ed6d6c6b85870fddc781fd92bf4b.jpg" alt="Advanced Skincare" class="w-full h-full object-cover transform group-hover:scale-110 transition-transform duration-700">
                        <div class="absolute inset-0 bg-gradient-to-t from-dark/70 to-transparent"></div>
                        <h3 class="absolute bottom-4 left-4 text-white text-xl font-bold">Advanced Skincare</h3>
                    </div>
                    
                    <div class="p-6">
                        <p class="text-gray-700 mb-4">
                            Harness the power of cutting-edge technology with our advanced skincare treatments for transformative results.
                        </p>
                        
                        <ul class="space-y-2 mb-6">
                            <li class="flex items-center">
                                <i class="fa fa-check text-primary mr-2"></i>
                                <span>RF Skin Tightening</span>
                            </li>
                            <li class="flex items-center">
                                <i class="fa fa-check text-primary mr-2"></i>
                                <span>IPL Photofacial</span>
                            </li>
                            <li class="flex items-center">
                                <i class="fa fa-check text-primary mr-2"></i>
                                <span>Microneedling</span>
                            </li>
                            <li class="flex items-center">
                                <i class="fa fa-check text-primary mr-2"></i>
                                <span>Chemical Peels</span>
                            </li>
                        </ul>
                        
                        <div class="flex justify-between items-center">
                            <span class="text-primary font-bold text-xl">$250+</span>
                            <a href="#contact" class="bg-secondary hover:bg-secondary/90 text-white px-5 py-2 rounded-full transition-all duration-300">Book Now</a>
                        </div>
                    </div>
                </div>
                
                <!-- Service Card 3 -->
                <div class="bg-white rounded-2xl shadow-lg overflow-hidden transform hover:-translate-y-2 transition-all duration-500 group">
                    <div class="relative h-60 overflow-hidden">
                        <img src="https://i.pinimg.com/736x/0e/d4/74/0ed474b14f6761fb5934be2cf48537ac.jpg" alt="Body Treatments" class="w-full h-full object-cover transform group-hover:scale-110 transition-transform duration-700">
                        <div class="absolute inset-0 bg-gradient-to-t from-dark/70 to-transparent"></div>
                        <h3 class="absolute bottom-4 left-4 text-white text-xl font-bold">Body Treatments</h3>
                    </div>
                    
                    <div class="p-6">
                        <p class="text-gray-700 mb-4">
                            Indulge in our luxurious body treatments designed to exfoliate, hydrate, and rejuvenate your skin from head to toe.
                        </p>
                        
                        <ul class="space-y-2 mb-6">
                            <li class="flex items-center">
                                <i class="fa fa-check text-primary mr-2"></i>
                                <span>Full Body Exfoliation</span>
                            </li>
                            <li class="flex items-center">
                                <i class="fa fa-check text-primary mr-2"></i>
                                <span>Deep Tissue Massage</span>
                            </li>
                            <li class="flex items-center">
                                <i class="fa fa-check text-primary mr-2"></i>
                                <span>Hot Stone Therapy</span>
                            </li>
                            <li class="flex items-center">
                                <i class="fa fa-check text-primary mr-2"></i>
                                <span>Body Wrap & Detox</span>
                            </li>
                        </ul>
                        
                        <div class="flex justify-between items-center">
                            <span class="text-primary font-bold text-xl">$200+</span>
                            <a href="#contact" class="bg-secondary hover:bg-secondary/90 text-white px-5 py-2 rounded-full transition-all duration-300">Book Now</a>
                        </div>
                    </div>
                </div>
            </div>
            
            <div class="text-center mt-12">
                <a href="#contact" class="inline-block bg-primary hover:bg-primary/90 text-white px-8 py-4 rounded-full transition-all duration-300 shadow-lg hover:shadow-xl transform hover:-translate-y-1 text-lg font-medium">
                    View All Services
                </a>
            </div>
        </div>
    </section>

    <!-- Featured Treatment Section -->
    <section class="py-20 bg-white relative overflow-hidden">
        <div class="absolute top-0 right-0 w-1/2 h-full bg-primary/5 -skew-x-12 transform origin-top-right"></div>
        
        <div class="container mx-auto px-4 relative z-10">
            <div class="flex flex-col md:flex-row items-center gap-12">
                <div class="md:w-1/2">
                    <h2 class="text-[clamp(1.5rem,3vw,2.5rem)] font-bold text-dark mb-6">Featured <span class="text-primary">Treatment</span></h2>
                    <div class="w-20 h-1 bg-secondary mb-8"></div>
                    
                    <h3 class="text-2xl font-semibold text-primary mb-4">Antioxidant Repair Facial</h3>
                    <p class="text-gray-700 mb-6 text-lg leading-relaxed">
                        Specially formulated for Miami's sun-exposed skin, this treatment combats the effects of UV damage with high-potency antioxidants like vitamin C, E, and ferulic acid.
                    </p>
                    
                    <div class="mb-8">
                        <h4 class="font-semibold text-lg mb-3">Treatment Benefits:</h4>
                        <ul class="space-y-3">
                            <li class="flex items-start">
                                <i class="fa fa-circle text-secondary text-xs mt-1.5 mr-3"></i>
                                <span>Repairs sun damage and photoaging</span>
                            </li>
                            <li class="flex items-start">
                                <i class="fa fa-circle text-secondary text-xs mt-1.5 mr-3"></i>
                                <span>Boosts collagen production for firmer skin</span>
                            </li>
                            <li class="flex items-start">
                                <i class="fa fa-circle text-secondary text-xs mt-1.5 mr-3"></i>
                                <span>Reduces the appearance of hyperpigmentation</span>
                            </li>
                            <li class="flex items-start">
                                <i class="fa fa-circle text-secondary text-xs mt-1.5 mr-3"></i>
                                <span>Improves skin texture and tone</span>
                            </li>
                            <li class="flex items-start">
                                <i class="fa fa-circle text-secondary text-xs mt-1.5 mr-3"></i>
                                <span>Provides long-lasting hydration</span>
                            </li>
                        </ul>
                    </div>
                    
                    <div class="flex items-center mb-8">
                        <div class="flex">
                            <i class="fa fa-star text-yellow-400"></i>
                            <i class="fa fa-star text-yellow-400"></i>
                            <i class="fa fa-star text-yellow-400"></i>
                            <i class="fa fa-star text-yellow-400"></i>
                            <i class="fa fa-star text-yellow-400"></i>
                        </div>
                        <span class="ml-2 text-gray-600">Based on 120+ reviews</span>
                    </div>
                    
                    <div class="flex flex-wrap gap-4">
                        <a href="#contact" class="bg-secondary hover:bg-secondary/90 text-white px-8 py-4 rounded-full transition-all duration-300 shadow-lg hover:shadow-xl transform hover:-translate-y-1 text-lg font-medium">
                            Book This Treatment
                        </a>
                        <a href="#services" class="bg-transparent border-2 border-primary hover:bg-primary/10 text-primary px-8 py-4 rounded-full transition-all duration-300 shadow-lg hover:shadow-xl transform hover:-translate-y-1 text-lg font-medium">
                            Explore More
                        </a>
                    </div>
                </div>
                
                <div class="md:w-1/2 relative">
                    <img src="https://static.wixstatic.com/media/4272c2_a7ee2ade005a4409bf9946f74930e0bc~mv2.png/v1/fill/w_487,h_510,al_c,q_85,usm_0.66_1.00_0.01,enc_avif,quality_auto/beauty-by-us-image-2.png" alt="Antioxidant Repair Facial" class="rounded-2xl shadow-xl w-full h-auto">
                    <div class="absolute -bottom-6 -left-6 bg-white p-6 rounded-xl shadow-lg max-w-xs">
                        <div class="flex items-center mb-3">
                            <div class="w-12 h-12 rounded-full overflow-hidden mr-4">
                                <img src="https://4gtvimg2.4gtv.tv/4gtv-Image/Production/Article/2023062105000008/202306210505188128.jpg" alt="Client" class="w-full h-full object-cover">
                            </div>
                            <div>
                                <h4 class="font-semibold">Jennifer L.</h4>
                                <div class="flex text-yellow-400 text-xs">
                                    <i class="fa fa-star"></i>
                                    <i class="fa fa-star"></i>
                                    <i class="fa fa-star"></i>
                                    <i class="fa fa-star"></i>
                                    <i class="fa fa-star"></i>
                                </div>
                            </div>
                        </div>
                        <p class="text-gray-700 text-sm italic">
                            "After just one treatment, my skin felt smoother and looked brighter. The redness from sun exposure had significantly reduced. Can't wait for my next appointment!"
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Products Section -->
    <section id="products" class="py-20 bg-accent/30">
        <div class="container mx-auto px-4">
            <div class="text-center max-w-3xl mx-auto mb-16">
                <h2 class="text-[clamp(1.5rem,3vw,2.5rem)] font-bold text-dark mb-6">Premium <span class="text-primary">Skincare Products</span></h2>
                <div class="w-20 h-1 bg-secondary mx-auto mb-8"></div>
                <p class="text-gray-700 text-lg">
                    We use only the finest luxury skincare brands known for their efficacy, safety, and commitment to sustainable practices.
                </p>
            </div>
            
            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-8">
                <!-- Product 1 -->
                <div class="bg-white rounded-xl shadow-md overflow-hidden group hover:shadow-xl transition-all duration-300">
                    <div class="relative h-64 overflow-hidden">
                        <img src="https://i.pinimg.com/736x/da/8a/27/da8a27ebd897e09b55602eb1adfd4b0f.jpg" alt="Valmont" class="w-full h-full object-cover transform group-hover:scale-105 transition-transform duration-500">
                        <div class="absolute inset-0 bg-gradient-to-t from-dark/70 to-transparent opacity-0 group-hover:opacity-100 transition-opacity duration-300 flex items-center justify-center">
                            <a href="#contact" class="bg-white text-primary px-4 py-2 rounded-full transform -translate-y-4 group-hover:translate-y-0 transition-transform duration-300">Learn More</a>
                        </div>
                    </div>
                    <div class="p-4">
                        <h3 class="font-semibold text-lg mb-1">Valmont</h3>
                        <p class="text-gray-600 text-sm">Swiss luxury skincare known for its innovative formulas and cutting-edge technology.</p>
                    </div>
                </div>
                
                <!-- Product 2 -->
                <div class="bg-white rounded-xl shadow-md overflow-hidden group hover:shadow-xl transition-all duration-300">
                    <div class="relative h-64 overflow-hidden">
                        <img src="https://i.pinimg.com/736x/ac/f4/eb/acf4ebe576ae92d57fb47193b4446e88.jpg" alt="Erno Laszlo" class="w-full h-full object-cover transform group-hover:scale-105 transition-transform duration-500">
                        <div class="absolute inset-0 bg-gradient-to-t from-dark/70 to-transparent opacity-0 group-hover:opacity-100 transition-opacity duration-300 flex items-center justify-center">
                            <a href="#contact" class="bg-white text-primary px-4 py-2 rounded-full transform -translate-y-4 group-hover:translate-y-0 transition-transform duration-300">Learn More</a>
                        </div>
                    </div>
                    <div class="p-4">
                        <h3 class="font-semibold text-lg mb-1">Erno Laszlo</h3>
                        <p class="text-gray-600 text-sm">Iconic skincare brand with a heritage of over 80 years, trusted by celebrities worldwide.</p>
                    </div>
                </div>
                
                <!-- Product 3 -->
                <div class="bg-white rounded-xl shadow-md overflow-hidden group hover:shadow-xl transition-all duration-300">
                    <div class="relative h-64 overflow-hidden">
                        <img src="https://i.pinimg.com/736x/f4/1e/2e/f41e2ea840bccff940ec91767c2dcbbc.jpg" alt="Dermalogica" class="w-full h-full object-cover transform group-hover:scale-105 transition-transform duration-500">
                        <div class="absolute inset-0 bg-gradient-to-t from-dark/70 to-transparent opacity-0 group-hover:opacity-100 transition-opacity duration-300 flex items-center justify-center">
                            <a href="#contact" class="bg-white text-primary px-4 py-2 rounded-full transform -translate-y-4 group-hover:translate-y-0 transition-transform duration-300">Learn More</a>
                        </div>
                    </div>
                    <div class="p-4">
                        <h3 class="font-semibold text-lg mb-1">Dermalogica</h3>
                        <p class="text-gray-600 text-sm">Professional-grade products developed by skin experts for targeted skin solutions.</p>
                    </div>
                </div>
                
                <!-- Product 4 -->
                <div class="bg-white rounded-xl shadow-md overflow-hidden group hover:shadow-xl transition-all duration-300">
                    <div class="relative h-64 overflow-hidden">
                        <img src="https://i.pinimg.com/736x/e3/09/85/e30985db0dd0450a0a2c553b2268fd3c.jpg" alt="Elemis" class="w-full h-full object-cover transform group-hover:scale-105 transition-transform duration-500">
                        <div class="absolute inset-0 bg-gradient-to-t from-dark/70 to-transparent opacity-0 group-hover:opacity-100 transition-opacity duration-300 flex items-center justify-center">
                            <a href="#contact" class="bg-white text-primary px-4 py-2 rounded-full transform -translate-y-4 group-hover:translate-y-0 transition-transform duration-300">Learn More</a>
                        </div>
                    </div>
                    <div class="p-4">
                        <h3 class="font-semibold text-lg mb-1">Elemis</h3>
                        <p class="text-gray-600 text-sm">British luxury brand that combines science and nature for effective skincare solutions.</p>
                    </div>
                </div>
            </div>
            
            <div class="text-center mt-12">
                <p class="text-gray-700 mb-6">Interested in purchasing our products for home use?</p>
                <a href="#contact" class="inline-block bg-primary hover:bg-primary/90 text-white px-8 py-4 rounded-full transition-all duration-300 shadow-lg hover:shadow-xl transform hover:-translate-y-1 text-lg font-medium">
                    Contact Us
                </a>
            </div>
        </div>
    </section>

    <!-- Team Section -->
    <section id="team" class="py-20 bg-white">
        <div class="container mx-auto px-4">
            <div class="text-center max-w-3xl mx-auto mb-16">
                <h2 class="text-[clamp(1.5rem,3vw,2.5rem)] font-bold text-dark mb-6">Meet Our <span class="text-primary">Expert Team</span></h2>
                <div class="w-20 h-1 bg-secondary mx-auto mb-8"></div>
                <p class="text-gray-700 text-lg">
                    Our team of certified estheticians and skincare experts are dedicated to helping you achieve your skin goals with personalized care and attention.
                </p>
            </div>
            
            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Team Member 1 -->
                <div class="bg-white rounded-xl shadow-md overflow-hidden group hover:shadow-xl transition-all duration-300">
                    <div class="relative overflow-hidden">
                        <img src="https://i.pinimg.com/736x/ad/2a/a5/ad2aa5515cbfbbbddc48746e4b13bdb0.jpg" alt="Danuta Mieloch" class="w-full h-96 object-cover object-center transform group-hover:scale-105 transition-transform duration-500">
                        <div class="absolute inset-0 bg-gradient-to-t from-dark/70 to-transparent opacity-0 group-hover:opacity-100 transition-opacity duration-300 flex items-end justify-center pb-8">
                            <div class="flex space-x-4">
                                <a href="#" class="bg-white text-primary p-2 rounded-full hover:bg-primary hover:text-white transition-colors duration-300">
                                    <i class="fa fa-instagram"></i>
                                </a>
                                <a href="#" class="bg-white text-primary p-2 rounded-full hover:bg-primary hover:text-white transition-colors duration-300">
                                    <i class="fa fa-linkedin"></i>
                                </a>
                                <a href="#" class="bg-white text-primary p-2 rounded-full hover:bg-primary hover:text-white transition-colors duration-300">
                                    <i class="fa fa-envelope"></i>
                                </a>
                            </div>
                        </div>
                    </div>
                    <div class="p-6">
                        <h3 class="font-bold text-xl mb-1">Danuta Mieloch</h3>
                        <p class="text-primary font-medium mb-3">Founder & Lead Esthetician</p>
                        <p class="text-gray-700">
                            With over 30 years of experience in the industry, Danuta is an award-winning esthetician and skincare expert who has trained with some of the world's leading dermatologists.
                        </p>
                    </div>
                </div>
                
                <!-- Team Member 2 -->
                <div class="bg-white rounded-xl shadow-md overflow-hidden group hover:shadow-xl transition-all duration-300">
                    <div class="relative overflow-hidden">
                        <img src="https://i.pinimg.com/736x/6a/cf/a3/6acfa319b71d3cb8e1047f222eacfa6d.jpg" alt="Julie Kim" class="w-full h-96 object-cover object-center transform group-hover:scale-105 transition-transform duration-500">
                        <div class="absolute inset-0 bg-gradient-to-t from-dark/70 to-transparent opacity-0 group-hover:opacity-100 transition-opacity duration-300 flex items-end justify-center pb-8">
                            <div class="flex space-x-4">
                                <a href="#" class="bg-white text-primary p-2 rounded-full hover:bg-primary hover:text-white transition-colors duration-300">
                                    <i class="fa fa-instagram"></i>
                                </a>
                                <a href="#" class="bg-white text-primary p-2 rounded-full hover:bg-primary hover:text-white transition-colors duration-300">
                                    <i class="fa fa-linkedin"></i>
                                </a>
                                <a href="#" class="bg-white text-primary p-2 rounded-full hover:bg-primary hover:text-white transition-colors duration-300">
                                    <i class="fa fa-envelope"></i>
                                </a>
                            </div>
                        </div>
                    </div>
                    <div class="p-6">
                        <h3 class="font-bold text-xl mb-1">Julie Kim</h3>
                        <p class="text-primary font-medium mb-3">Investor Shareholder&Skin Specialist</p>
                        <p class="text-gray-700">
                           Julie Kim's net worth reflects her success in transforming her lifelong passion for skincare into a world-renowned luxury business. She has built an empire rooted in results, education, and innovation. Her philosophy of "beautiful skin is by choice, not by chance" guides her every step, influencing her signature treatments, product curation, and approach to customer care.
                        </p>
                    </div>
                </div>
                
                <!-- Team Member 3 -->
                <div class="bg-white rounded-xl shadow-md overflow-hidden group hover:shadow-xl transition-all duration-300">
                    <div class="relative overflow-hidden">
                        <img src="https://i.pinimg.com/736x/ad/32/10/ad3210d62156a68651ac566938371ec6.jpg" alt="Sophia Rodriguez" class="w-full h-96 object-cover object-center transform group-hover:scale-105 transition-transform duration-500">
                        <div class="absolute inset-0 bg-gradient-to-t from-dark/70 to-transparent opacity-0 group-hover:opacity-100 transition-opacity duration-300 flex items-end justify-center pb-8">
                            <div class="flex space-x-4">
                                <a href="#" class="bg-white text-primary p-2 rounded-full hover:bg-primary hover:text-white transition-colors duration-300">
                                    <i class="fa fa-instagram"></i>
                                </a>
                                <a href="#" class="bg-white text-primary p-2 rounded-full hover:bg-primary hover:text-white transition-colors duration-300">
                                    <i class="fa fa-linkedin"></i>
                                </a>
                                <a href="#" class="bg-white text-primary p-2 rounded-full hover:bg-primary hover:text-white transition-colors duration-300">
                                    <i class="fa fa-envelope"></i>
                                </a>
                            </div>
                        </div>
                    </div>
                    <div class="p-6">
                        <h3 class="font-bold text-xl mb-1">Sophia Rodriguez</h3>
                        <p class="text-primary font-medium mb-3">Master Esthetician</p>
                        <p class="text-gray-700">
                            Sophia is a certified master esthetician with expertise in advanced facial treatments and body therapies, focusing on holistic skincare solutions.
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Testimonials Section -->
    <section id="testimonials" class="py-20 bg-accent/30 relative overflow-hidden">
        <div class="absolute top-0 left-0 w-full h-full opacity-10">
            <svg viewBox="0 0 100 100" preserveAspectRatio="none" class="w-full h-full">
                <path d="M0,0 L100,0 L100,100 L0,100 Z" fill="url(#grid)" />
                <defs>
                    <pattern id="grid" width="10" height="10" patternUnits="userSpaceOnUse">
                        <path d="M 10 0 L 0 0 0 10" fill="none" stroke="#4A6FA5" stroke-width="0.5" />
                    </pattern>
                </defs>
            </svg>
        </div>
        
        <div class="container mx-auto px-4 relative z-10">
            <div class="text-center max-w-3xl mx-auto mb-16">
                <h2 class="text-[clamp(1.5rem,3vw,2.5rem)] font-bold text-dark mb-6">What Our <span class="text-primary">Clients Say</span></h2>
                <div class="w-20 h-1 bg-secondary mx-auto mb-8"></div>
                <p class="text-gray-700 text-lg">
                    Discover why our clients love their experience at Rescue Spa Miami and how our treatments have transformed their skin.
                </p>
            </div>
            
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Testimonial 1 -->
                <div class="bg-white p-8 rounded-2xl shadow-lg relative">
                    <div class="text-primary text-5xl absolute -top-4 left-4 opacity-20">"</div>
                    <div class="flex text-yellow-400 mb-4">
                        <i class="fa fa-star"></i>
                        <i class="fa fa-star"></i>
                        <i class="fa fa-star"></i>
                        <i class="fa fa-star"></i>
                        <i class="fa fa-star"></i>
                    </div>
                    <p class="text-gray-700 mb-6 relative z-10">
                        "I've been coming to Rescue Spa for over a year now, and the difference in my skin is remarkable. The antioxidant facial has significantly reduced the sun damage from living in Miami, and my skin looks brighter and feels smoother."
                    </p>
                    <div class="flex items-center">
                        <img src="https://i.pinimg.com/736x/2f/21/6e/2f216e31544dcb688853c547202fe89d.jpg" alt="Client" class="w-12 h-12 rounded-full object-cover mr-4">
                        <div>
                            <h4 class="font-semibold">Sarah Johnson</h4>
                            <p class="text-gray-600 text-sm">Client for 1 year</p>
                        </div>
                    </div>
                </div>
                
                <!-- Testimonial 2 -->
                <div class="bg-white p-8 rounded-2xl shadow-lg relative">
                    <div class="text-primary text-5xl absolute -top-4 left-4 opacity-20">"</div>
                    <div class="flex text-yellow-400 mb-4">
                        <i class="fa fa-star"></i>
                        <i class="fa fa-star"></i>
                        <i class="fa fa-star"></i>
                        <i class="fa fa-star"></i>
                        <i class="fa fa-star"></i>
                    </div>
                    <p class="text-gray-700 mb-6 relative z-10">
                        "The staff at Rescue Spa is incredibly knowledgeable and professional. They took the time to understand my skin concerns and created a personalized treatment plan. After just a few sessions, my skin has never looked better!"
                    </p>
                    <div class="flex items-center">
                        <img src="https://i.pinimg.com/736x/ab/98/13/ab9813f6a29bdb221245eac84b25f973.jpg" alt="Client" class="w-12 h-12 rounded-full object-cover mr-4">
                        <div>
                            <h4 class="font-semibold">Michael Torres</h4>
                            <p class="text-gray-600 text-sm">Client for 6 months</p>
                        </div>
                    </div>
                </div>
                
                <!-- Testimonial 3 -->
                <div class="bg-white p-8 rounded-2xl shadow-lg relative">
                    <div class="text-primary text-5xl absolute -top-4 left-4 opacity-20">"</div>
                    <div class="flex text-yellow-400 mb-4">
                        <i class="fa fa-star"></i>
                        <i class="fa fa-star"></i>
                        <i class="fa fa-star"></i>
                        <i class="fa fa-star"></i>
                        <i class="fa fa-star-half-o"></i>
                    </div>
                    <p class="text-gray-700 mb-6 relative z-10">
                        "I was skeptical about the RF skin tightening treatment, but the results speak for themselves. My skin feels firmer, and the fine lines around my eyes have diminished. The spa itself is beautiful and the perfect place to relax."
                    </p>
                    <div class="flex items-center">
                        <img src="https://i.pinimg.com/736x/7e/fa/73/7efa7395c1cd2857ab5a82516dfdfeb5.jpg" class="w-12 h-12 rounded-full object-cover mr-4">
                        <div>
                            <h4 class="font-semibold">Elena Martinez</h4>
                            <p class="text-gray-600 text-sm">Client for 3 months</p>
                        </div>
                    </div>
                </div>
            </div>
            
            <div class="text-center mt-12">
                <a href="#contact" class="inline-block bg-primary hover:bg-primary/90 text-white px-8 py-4 rounded-full transition-all duration-300 shadow-lg hover:shadow-xl transform hover:-translate-y-1 text-lg font-medium">
                    Share Your Experience
                </a>
            </div>
        </div>
    </section>

    <!-- Before & After Section -->
    <section class="py-20 bg-white">
        <div class="container mx-auto px-4">
            <div class="text-center max-w-3xl mx-auto mb-16">
                <h2 class="text-[clamp(1.5rem,3vw,2.5rem)] font-bold text-dark mb-6">Real <span class="text-primary">Results</span></h2>
                <div class="w-20 h-1 bg-secondary mx-auto mb-8"></div>
                <p class="text-gray-700 text-lg">
                    See the transformative power of our treatments through these before and after photos of our clients.
                </p>
            </div>
            
            <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
                <!-- Before & After 1 -->
                <div class="bg-white rounded-xl shadow-lg overflow-hidden">
                    <div class="relative h-80">
                        <div class="absolute inset-0 flex">
                            <div class="w-1/2 h-full overflow-hidden">
                                <img src="https://i.pinimg.com/736x/04/34/92/043492258a5a3e6db54b40bb658e6729.jpg" alt="Before" class="w-full h-full object-cover">
                                <div class="absolute bottom-0 left-0 bg-dark/70 text-white px-4 py-2">Before</div>
                            </div>
                            <div class="w-1/2 h-full overflow-hidden">
                                <img src="https://i.pinimg.com/736x/4e/e5/9c/4ee59ccecdf46693c71812b5367f273c.jpg" alt="After" class="w-full h-full object-cover">
                                <div class="absolute bottom-0 right-0 bg-primary/70 text-white px-4 py-2">After</div>
                            </div>
                        </div>
                    </div>
                    <div class="p-6">
                        <h3 class="font-semibold text-xl mb-2">Antioxidant Repair Facial</h3>
                        <p class="text-gray-700">
                            4 sessions over 2 months targeting sun damage and hyperpigmentation. Notice the reduction in redness and improvement in skin texture.
                        </p>
                    </div>
                </div>
                
                <!-- Before & After 2 -->
                <div class="bg-white rounded-xl shadow-lg overflow-hidden">
                    <div class="relative h-80">
                        <div class="absolute inset-0 flex">
                            <div class="w-1/2 h-full overflow-hidden">
                                <img src="https://i.pinimg.com/736x/0f/b8/21/0fb8211469305ede009e02c443ebdec3.jpg" alt="Before" class="w-full h-full object-cover">
                                <div class="absolute bottom-0 left-0 bg-dark/70 text-white px-4 py-2">Before</div>
                            </div>
                            <div class="w-1/2 h-full overflow-hidden">
                                <img src="https://i.pinimg.com/736x/a3/cd/f2/a3cdf27cb1016d79d640e7740564a067.jpg" alt="After" class="w-full h-full object-cover">
                                <div class="absolute bottom-0 right-0 bg-primary/70 text-white px-4 py-2">After</div>
                            </div>
                        </div>
                    </div>
                    <div class="p-6">
                        <h3 class="font-semibold text-xl mb-2">RF Skin Tightening</h3>
                        <p class="text-gray-700">
                            3 treatments spaced 4 weeks apart. Notice the improvement in skin laxity and definition in the jawline.
                        </p>
                    </div>
                </div>
            </div>
            
            <div class="text-center mt-12">
                <a href="#contact" class="inline-block bg-secondary hover:bg-secondary/90 text-white px-8 py-4 rounded-full transition-all duration-300 shadow-lg hover:shadow-xl transform hover:-translate-y-1 text-lg font-medium">
                    Schedule Your Consultation
                </a>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-20 bg-accent/30">
        <div class="container mx-auto px-4">
            <div class="flex flex-col md:flex-row gap-12">
                <div class="md:w-1/2">
                    <h2 class="text-[clamp(1.5rem,3vw,2.5rem)] font-bold text-dark mb-6">Get in <span class="text-primary">Touch</span></h2>
                    <div class="w-20 h-1 bg-secondary mb-8"></div>
                    
                    <p class="text-gray-700 mb-8 text-lg leading-relaxed">
                        Ready to transform your skin? Schedule a consultation with our expert team to discuss your skincare goals and discover the perfect treatment plan for you.
                    </p>
                    
                    <div class="space-y-6 mb-8">
                        <div class="flex items-start">
                            <div class="bg-primary/10 p-3 rounded-full mr-4">
                                <i class="fa fa-map-marker text-primary text-xl"></i>
                            </div>
                            <div>
                                <h3 class="font-semibold text-lg mb-1">Location</h3>
                                <p class="text-gray-600">123 Beauty Avenue, Miami, FL 33101</p>
                            </div>
                        </div>
                        
                        <div class="flex items-start">
                            <div class="bg-primary/10 p-3 rounded-full mr-4">
                                <i class="fa fa-phone text-primary text-xl"></i>
                            </div>
                            <div>
                                <h3 class="font-semibold text-lg mb-1">Phone</h3>
                                <p class="text-gray-600">(305) 555-1234</p>
                            </div>
                        </div>
                        
                        <div class="flex items-start">
                            <div class="bg-primary/10 p-3 rounded-full mr-4">
                                <i class="fa fa-envelope text-primary text-xl"></i>
                            </div>
                            <div>
                                <h3 class="font-semibold text-lg mb-1">Email</h3>
                                <p class="text-gray-600">info@rescuespamiami.com</p>
                            </div>
                        </div>
                        
                        <div class="flex items-start">
                            <div class="bg-primary/10 p-3 rounded-full mr-4">
                                <i class="fa fa-clock-o text-primary text-xl"></i>
                            </div>
                            <div>
                                <h3 class="font-semibold text-lg mb-1">Hours</h3>
                                <p class="text-gray-600">Monday - Friday: 9AM - 7PM</p>
                                <p class="text-gray-600">Saturday: 9AM - 5PM</p>
                                <p class="text-gray-600">Sunday: Closed</p>
                            </div>
                        </div>
                    </div>
                    
                    <div class="flex space-x-4">
                        <a href="#" class="bg-primary hover:bg-primary/90 text-white p-3 rounded-full transition-all duration-300">
                            <i class="fa fa-facebook"></i>
                        </a>
                        <a href="#" class="bg-primary hover:bg-primary/90 text-white p-3 rounded-full transition-all duration-300">
                            <i class="fa fa-instagram"></i>
                        </a>
                        <a href="#" class="bg-primary hover:bg-primary/90 text-white p-3 rounded-full transition-all duration-300">
                            <i class="fa fa-twitter"></i>
                        </a>
                        <a href="#" class="bg-primary hover:bg-primary/90 text-white p-3 rounded-full transition-all duration-300">
                            <i class="fa fa-pinterest"></i>
                        </a>
                    </div>
                </div>
                
                <div class="md:w-1/2">
                    <div class="bg-white p-8 rounded-2xl shadow-xl">
                        <h3 class="font-bold text-2xl mb-6">Book Your Appointment</h3>
                        
                        <form id="appointment-form" class="space-y-6">
                            <div class="grid grid-cols-1 sm:grid-cols-2 gap-6">
                                <div>
                                    <label for="first-name" class="block text-gray-700 font-medium mb-2">First Name</label>
                                    <input type="text" id="first-name" class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-primary/50 focus:border-primary transition-colors duration-300" placeholder="Your first name">
                                </div>
                                
                                <div>
                                    <label for="last-name" class="block text-gray-700 font-medium mb-2">Last Name</label>
                                    <input type="text" id="last-name" class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-primary/50 focus:border-primary transition-colors duration-300" placeholder="Your last name">
                                </div>
                            </div>
                            
                            <div>
                                <label for="email" class="block text-gray-700 font-medium mb-2">Email</label>
                                <input type="email" id="email" class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-primary/50 focus:border-primary transition-colors duration-300" placeholder="Your email address">
                            </div>
                            
                            <div>
                                <label for="phone" class="block text-gray-700 font-medium mb-2">Phone</label>
                                <input type="tel" id="phone" class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-primary/50 focus:border-primary transition-colors duration-300" placeholder="Your phone number">
                            </div>
                            
                            <div>
                                <label for="service" class="block text-gray-700 font-medium mb-2">Service Interested In</label>
                                <select id="service" class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-primary/50 focus:border-primary transition-colors duration-300">
                                    <option value="">Select a service</option>
                                    <option value="facial">Facial Treatments</option>
                                    <option value="advanced">Advanced Skincare</option>
                                    <option value="body">Body Treatments</option>
                                    <option value="consultation">Consultation</option>
                                </select>
                            </div>
                            
                            <div>
                                <label for="date" class="block text-gray-700 font-medium mb-2">Preferred Date</label>
                                <input type="date" id="date" class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-primary/50 focus:border-primary transition-colors duration-300">
                            </div>
                            
                            <div>
                                <label for="message" class="block text-gray-700 font-medium mb-2">Message</label>
                                <textarea id="message" rows="4" class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-primary/50 focus:border-primary transition-colors duration-300" placeholder="Any specific concerns or questions"></textarea>
                            </div>
                            
                            <button type="submit" class="w-full bg-primary hover:bg-primary/90 text-white font-medium py-3 px-6 rounded-lg transition-all duration-300 shadow-lg hover:shadow-xl transform hover:-translate-y-1">
                                Schedule Appointment
                            </button>
                        </form>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Map Section -->
    <section class="h-96 relative">
        <div class="absolute inset-0">
            <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3592.728639338522!2d-80.19178828455272!3d25.76167988360582!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x88d9b6b2a3cc414b%3A0x92f2e1e4a558b998!2sMiami%2C%20FL%2C%20USA!5e0!3m2!1sen!2s!4v1624338537903!5m2!1sen!2s" width="100%" height="100%" style="border:0;" allowfullscreen="" loading="lazy"></iframe>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-dark text-white py-16">
        <div class="container mx-auto px-4">
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8">
                <div>
                    <a href="#" class="inline-block mb-6">
                        <img src="https://i.pinimg.com/736x/44/66/38/446638e594a9d16d34d9d85a185923a0.jpg">
                    </a>
                    <p class="text-gray-400 mb-6">
                        Premium skincare services tailored to your unique needs in the heart of Miami.
                    </p>
                    <div class="flex space-x-4">
                        <a href="#" class="text-gray-400 hover:text-white transition-colors duration-300">
                            <i class="fa fa-facebook"></i>
                        </a>
                        <a href="#" class="text-gray-400 hover:text-white transition-colors duration-300">
                            <i class="fa fa-instagram"></i>
                        </a>
                        <a href="#" class="text-gray-400 hover:text-white transition-colors duration-300">
                            <i class="fa fa-twitter"></i>
                        </a>
                        <a href="#" class="text-gray-400 hover:text-white transition-colors duration-300">
                            <i class="fa fa-pinterest"></i>
                        </a>
                    </div>
                </div>
                
                <div>
                    <h3 class="text-xl font-semibold mb-6">Quick Links</h3>
                    <ul class="space-y-3">
                        <li><a href="#about" class="text-gray-400 hover:text-white transition-colors duration-300">About Us</a></li>
                        <li><a href="#services" class="text-gray-400 hover:text-white transition-colors duration-300">Services</a></li>
                        <li><a href="#products" class="text-gray-400 hover:text-white transition-colors duration-300">Products</a></li>
                        <li><a href="#team" class="text-gray-400 hover:text-white transition-colors duration-300">Our Team</a></li>
                        <li><a href="#testimonials" class="text-gray-400 hover:text-white transition-colors duration-300">Testimonials</a></li>
                        <li><a href="#contact" class="text-gray-400 hover:text-white transition-colors duration-300">Contact Us</a></li>
                    </ul>
                </div>
                
                <div>
                    <h3 class="text-xl font-semibold mb-6">Services</h3>
                    <ul class="space-y-3">
                        <li><a href="#services" class="text-gray-400 hover:text-white transition-colors duration-300">Facial Treatments</a></li>
                        <li><a href="#services" class="text-gray-400 hover:text-white transition-colors duration-300">Advanced Skincare</a></li>
                        <li><a href="#services" class="text-gray-400 hover:text-white transition-colors duration-300">Body Treatments</a></li>
                        <li><a href="#services" class="text-gray-400 hover:text-white transition-colors duration-300">Antioxidant Repair</a></li>
                        <li><a href="#services" class="text-gray-400 hover:text-white transition-colors duration-300">RF Skin Tightening</a></li>
                        <li><a href="#services" class="text-gray-400 hover:text-white transition-colors duration-300">IPL Photofacial</a></li>
                    </ul>
                </div>
                
                <div>
                    <h3 class="text-xl font-semibold mb-6">Contact Info</h3>
                    <ul class="space-y-4">
                        <li class="flex items-start">
                            <i class="fa fa-map-marker text-secondary mt-1 mr-3"></i>
                            <span class="text-gray-400">123 Beauty Avenue, Miami, FL 33101</span>
                        </li>
                        <li class="flex items-start">
                            <i class="fa fa-phone text-secondary mt-1 mr-3"></i>
                            <span class="text-gray-400">(305) 555-1234</span>
                        </li>
                        <li class="flex items-start">
                            <i class="fa fa-envelope text-secondary mt-1 mr-3"></i>
                            <span class="text-gray-400">info@rescuespamiami.com</span>
                        </li>
                        <li class="flex items-start">
                            <i class="fa fa-clock-o text-secondary mt-1 mr-3"></i>
                            <span class="text-gray-400">Mon-Fri: 9AM - 7PM<br>Sat: 9AM - 5PM<br>Sun: Closed</span>
                        </li>
                    </ul>
                </div>
            </div>
            
            <div class="border-t border-gray-800 mt-12 pt-8 flex flex-col md:flex-row justify-between items-center">
                <p class="text-gray-500 mb-4 md:mb-0">© 2025 Rescue Spa Miami. All rights reserved.</p>
                <div class="flex space-x-6">
                    <a href="#" class="text-gray-500 hover:text-white transition-colors duration-300">Privacy Policy</a>
                    <a href="#" class="text-gray-500 hover:text-white transition-colors duration-300">Terms of Service</a>
                    <a href="#" class="text-gray-500 hover:text-white transition-colors duration-300">Sitemap</a>
                </div>
            </div>
        </div>
    </footer>

    <!-- Back to Top Button -->
    <button id="back-to-top" class="fixed bottom-8 right-8 bg-primary text-white p-3 rounded-full shadow-lg transform hover:scale-110 transition-all duration-300 opacity-0 invisible">
        <i class="fa fa-arrow-up"></i>
    </button>

    <!-- JavaScript -->
    <script>
        // Navigation scroll effect
        const navbar = document.getElementById('navbar');
        const backToTop = document.getElementById('back-to-top');
        
        window.addEventListener('scroll', function() {
            if (window.scrollY > 100) {
                navbar.classList.add('bg-dark/90', 'shadow-lg');
                navbar.classList.remove('bg-transparent');
                backToTop.classList.remove('opacity-0', 'invisible');
                backToTop.classList.add('opacity-100');
            } else {
                navbar.classList.remove('bg-dark/90', 'shadow-lg');
                navbar.classList.add('bg-transparent');
                backToTop.classList.add('opacity-0', 'invisible');
                backToTop.classList.remove('opacity-100');
            }
        });
        
        // Mobile menu toggle
        const menuToggle = document.getElementById('menu-toggle');
        const mobileMenu = document.getElementById('mobile-menu');
        
        menuToggle.addEventListener('click', function() {
            mobileMenu.classList.toggle('hidden');
        });
        
        // Smooth scrolling for anchor links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                
                // Close mobile menu if open
                if (!mobileMenu.classList.contains('hidden')) {
                    mobileMenu.classList.add('hidden');
                }
                
                const targetId = this.getAttribute('href');
                if (targetId === '#') return;
                
                const targetElement = document.querySelector(targetId);
                if (targetElement) {
                    window.scrollTo({
                        top: targetElement.offsetTop - 80,
                        behavior: 'smooth'
                    });
                }
            });
        });
        
        // Back to top button
        backToTop.addEventListener('click', function() {
            window.scrollTo({
                top: 0,
                behavior: 'smooth'
            });
        });
        
        // Form submission
        const appointmentForm = document.getElementById('appointment-form');
        
        appointmentForm.addEventListener('submit', function(e) {
            e.preventDefault();
            
            // Simple validation
            const firstName = document.getElementById('first-name').value;
            const lastName = document.getElementById('last-name').value;
            const email = document.getElementById('email').value;
            const phone = document.getElementById('phone').value;
            const service = document.getElementById('service').value;
            const date = document.getElementById('date').value;
            
            if (!firstName || !lastName || !email || !phone || !service || !date) {
                alert('Please fill in all required fields');
                return;
            }
            
            // Here you would normally send the form data to a server
            // For demo purposes, we'll just show a success message
            alert('Thank you for your appointment request! We will contact you shortly to confirm.');
            appointmentForm.reset();
        });
        
        // Add animation to elements when they come into view
        const animateOnScroll = function() {
            const elements = document.querySelectorAll('.animate-on-scroll');
            
            elements.forEach(element => {
                const elementPosition = element.getBoundingClientRect().top;
                const screenPosition = window.innerHeight / 1.3;
                
                if (elementPosition < screenPosition) {
                    element.classList.add('fade-in');
                }
            });
        };
        
        // Initialize animations
        window.addEventListener('scroll', animateOnScroll);
        window.addEventListener('load', animateOnScroll);
    </script>
</body>
</html>
