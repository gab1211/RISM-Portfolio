<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>RISM: GITHUB PORTFOLIO</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap');
        
        body {
            font-family: 'Poppins', sans-serif;
            scroll-behavior: smooth;
        }
        
        .nav-link {
            position: relative;
        }
        
        .nav-link::after {
            content: '';
            position: absolute;
            width: 0;
            height: 2px;
            bottom: -2px;
            left: 0;
            background-color: #3b82f6;
            transition: width 0.3s ease;
        }
        
        .nav-link:hover::after {
            width: 100%;
        }
        
        .hero-image {
            background-image: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)), url("background.jpg");
            background-size: cover;
            background-position: center;
        }
        
        .project-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 25px rgba(0, 0, 0, 0.1);
        }
        
        .skill-pill:hover {
            background-color: #3b82f6;
            color: white;
        }
    </style>
</head>
<body class="bg-gray-50">
    <!-- Navigation -->
    <nav class="bg-white shadow-sm fixed w-full z-10">
        <div class="max-w-6xl mx-auto px-4 py-3 flex justify-between items-center">
            <div class="text-2xl font-bold text-blue-500">Student<span class="text-gray-800">Portfolio</span></div>
            <div class="hidden md:flex space-x-8">
                <a href="#home" class="nav-link text-gray-700 hover:text-blue-500">Home</a>
                <a href="#projects" class="nav-link text-gray-700 hover:text-blue-500">Projects</a>
                <a href="#skills" class="nav-link text-gray-700 hover:text-blue-500">Skills</a>
                <a href="#contact" class="nav-link text-gray-700 hover:text-blue-500">Contact</a>
            </div>
            <button class="md:hidden text-gray-700">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16" />
                </svg>
            </button>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="home" class="hero-image h-screen flex items-center justify-center text-center text-white pt-16">
        <div class="px-4">
            <h1 class="text-4xl md:text-6xl font-bold mb-4">Good Day! We are <span class="text-blue-400">RISM: Building Our GitHub Portfolio Together</span></h1>
            <p class="text-xl md:text-2xl mb-8">BS Info Tech Students & Aspiring Developer</p>
            <div class="space-x-4">
                <a href="#projects" class="bg-blue-500 hover:bg-blue-600 text-white px-6 py-3 rounded-md inline-block">View Student Profiles</a>
                <a href="#contact" class="bg-transparent hover:bg-white hover:text-blue-500 text-white border-2 border-white px-6 py-3 rounded-md inline-block">Contact</a>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="py-20 bg-white">
        <div class="max-w-6xl mx-auto px-4">
            <h2 class="text-3xl font-bold text-center mb-12">About Our Portfolio</h2>
            <div class="flex flex-col md:flex-row items-center gap-12">
                <div class="w-full md:w-1/3">
                    <img src="grup.jpg" />
                </div>
                <div class="w-full md:w-2/3">
                    <h3 class="text-2xl font-semibold mb-4">Our Portfolio Mission</h3>
                    <p class="text-gray-600 mb-6">
                        This portfolio showcases the collective work of talented students from our BS Information Technology program. We specialize in creating innovative web solutions and Website that solve real-world problems. Our team collaborates to push the boundaries of technology while maintaining high standards of quality and usability.
                    </p>
                    <h3 class="text-2xl font-semibold mb-4">Academic Background</h3>
                    <div class="space-y-4">
                        <div class="border-l-4 border-blue-500 pl-4">
                            <h4 class="font-semibold">CvSU CCAT</h4>
                            <p class="text-gray-600">Department of Computer Studies</p>
                            <p class="text-gray-500 text-sm">Since 2022</p>
                        </div>
                        <div class="border-l-4 border-blue-500 pl-4">
                            <h4 class="font-semibold">Collective Experience</h4>
                            <p class="text-gray-600">500+ completed student projects</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Projects Section -->
    <section id="projects" class="py-20 bg-gray-50">
        <div class="max-w-6xl mx-auto px-4">
            <h2 class="text-3xl font-bold text-center mb-12">Student Profiles</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Project 1 -->
                <div class="project-card bg-white rounded-lg shadow-md overflow-hidden transition-all duration-300">
                    <div class="h-48 overflow-hidden">
                        <img src="batul.jpg" />
                    </div>
                    <div class="p-6">
                        <h3 class="text-xl font-semibold mb-2">Isiah Gabrielle Batul</h3>
                        <p class="text-gray-600 mb-4">A Singer, Choir Member for Almost 7 Years, Livestreamer/Artist during
                            Pandemic, Developer, Documentator, Banner Editor, Video Editor, Old Soul.</p>
                        <div class="flex flex-wrap gap-2 mb-4">
                            <span class="text-xs bg-gray-100 px-2 py-1 rounded">React</span>
                            <span class="text-xs bg-gray-100 px-2 py-1 rounded">Node.js</span>
                            <span class="text-xs bg-gray-100 px-2 py-1 rounded">MongoDB</span>
                        </div>
                        <a href="https://gab1211.github.io/" class="text-blue-500 hover:text-blue-600 font-medium inline-flex items-center">
                            View Profile 
                            <svg xmlns="https://github.com/Ry2003-bit/ry.github.io/tree/master" class="h-4 w-4 ml-1" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M14 5l7 7m0 0l-7 7m7-7H3" />
                            </svg>
                        </a>
                    </div>
                </div>
                
                <!-- Project 2 -->
                <div class="project-card bg-white rounded-lg shadow-md overflow-hidden transition-all duration-300">
                    <div class="h-48 overflow-hidden">
                        <img src="serolf.jpg" />
                    </div>
                    <div class="p-6">
                        <h3 class="text-xl font-semibold mb-2">Serolf Flores</h3>
                        <p class="text-gray-600 mb-4">A sporty Developer, NC 2 Passer of AutoCAD, Tall, Dark and Handsome.</p>
                        <div class="flex flex-wrap gap-2 mb-4">
                            <span class="text-xs bg-gray-100 px-2 py-1 rounded">Vue.js</span>
                            <span class="text-xs bg-gray-100 px-2 py-1 rounded">Firebase</span>
                            <span class="text-xs bg-gray-100 px-2 py-1 rounded">Tailwind CSS</span>
                        </div>
                        <a href="seroks.html" class="text-blue-500 hover:text-blue-600 font-medium inline-flex items-center">
                            View Profile 
                            <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4 ml-1" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M14 5l7 7m0 0l-7 7m7-7H3" />
                            </svg>
                        </a>
                    </div>
                </div>
                
                <!-- Project 3 -->
                <div class="project-card bg-white rounded-lg shadow-md overflow-hidden transition-all duration-300">
                    <div class="h-48 overflow-hidden">
                        <img src="eco.jpg" />
                    </div>
                    <div class="p-6">
                        <h3 class="text-xl font-semibold mb-2">Ryan Eco</h3>
                        <p class="text-gray-600 mb-4">AI/ML specialist with expertise in Python, TensorFlow, and natural language processing.</p>
                        <div class="flex flex-wrap gap-2 mb-4">
                            <span class="text-xs bg-gray-100 px-2 py-1 rounded">HTML</span>
                            <span class="text-xs bg-gray-100 px-2 py-1 rounded">TensorFlow</span>
                            <span class="text-xs bg-gray-100 px-2 py-1 rounded">Flask</span>
                        </div>
                        <a href="RyanPortfolio.html" class="text-blue-500 hover:text-blue-600 font-medium inline-flex items-center">
                            View Profile
                            <svg xmlns="" class="h-4 w-4 ml-1" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M14 5l7 7m0 0l-7 7m7-7H3" />
                            </svg>
                        </a>
                    </div>
                </div>
            </div>
            <!-- Additional Student -->
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8 mt-8">
                <div class="project-card bg-white rounded-lg shadow-md overflow-hidden transition-all duration-300">
                    <div class="h-48 overflow-hidden">
                        <img src="dhea.jpg" />
                    </div>
                    <div class="p-6">
                        <h3 class="text-xl font-semibold mb-2">Dhea Panizares</h3>
                        <p class="text-gray-600 mb-4">Mobile app developer specializing in React Native and Flutter cross-platform applications.</p>
                        <div class="flex flex-wrap gap-2 mb-4">
                            <span class="text-xs bg-gray-100 px-2 py-1 rounded">React Native</span>
                            <span class="text-xs bg-gray-100 px-2 py-1 rounded">Flutter</span>
                            <span class="text-xs bg-gray-100 px-2 py-1 rounded">Firebase</span>
                        </div>
                        <a href="dhea.html" class="text-blue-500 hover:text-blue-600 font-medium inline-flex items-center">
                            View Profile 
                            <svg xmlns="c:\Users\asus\Downloads\RyanPortfolio.html" class="h-4 w-4 ml-1" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M14 5l7 7m0 0l-7 7m7-7H3" />
                            </svg>
                        </a>
                    </div>
                </div>
            </div>
            <div class="text-center mt-12">
                <a href="#" class="inline-block px-6 py-3 border-2 border-blue-500 text-blue-500 hover:bg-blue-500 hover:text-white rounded-md transition-colors duration-300">
                    View All Student Profiles
                </a>
            </div>
        </div>
    </section>

    <!-- Skills Section -->
    <section id="skills" class="py-20 bg-white">
        <div class="max-w-6xl mx-auto px-4">
            <h2 class="text-3xl font-bold text-center mb-12">Technical Skills</h2>
            <div class="grid grid-cols-2 md:grid-cols-4 gap-6">
                <div class="text-center p-6 rounded-lg bg-gray-50 hover:shadow-md transition-shadow">
                    <div class="w-16 h-16 mx-auto mb-4">
                        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="#E34F26" class="w-full h-full">
                            <path d="M1.5 4.5l3 3v12l-3 3h-1.5v-18h1.5zm4.5 15l9-15h3l-9 15h-3zm12-15h1.5v18h-1.5l-3-3v-12l3-3z"/>
                        </svg>
                    </div>
                    <h3 class="font-semibold mb-2">HTML5</h3>
                    <p class="text-gray-600 text-sm">Advanced</p>
                </div>
                <div class="text-center p-6 rounded-lg bg-gray-50 hover:shadow-md transition-shadow">
                    <div class="w-16 h-16 mx-auto mb-4">
                        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="#1572B6" class="w-full h-full">
                            <path d="M1.5 4.5l3 3v12l-3 3h-1.5v-18h1.5zm4.5 15l9-15h3l-9 15h-3zm12-15h1.5v18h-1.5l-3-3v-12l3-3z"/>
                        </svg>
                    </div>
                    <h3 class="font-semibold mb-2">CSS3</h3>
                    <p class="text-gray-600 text-sm">Advanced</p>
                </div>
                <div class="text-center p-6 rounded-lg bg-gray-50 hover:shadow-md transition-shadow">
                    <div class="w-16 h-16 mx-auto mb-4">
                        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="#F7DF1E" class="w-full h-full">
                            <path d="M1.5 4.5h3v15h-3v-15zm4.5 0h3v15h-3v-15zm4.5 0h3v15h-3v-15zm4.5 0h3v15h-3v-15z"/>
                        </svg>
                    </div>
                    <h3 class="font-semibold mb-2">JavaScript</h3>
                    <p class="text-gray-600 text-sm">Advanced</p>
                </div>
                <div class="text-center p-6 rounded-lg bg-gray-50 hover:shadow-md transition-shadow">
                    <div class="w-16 h-16 mx-auto mb-4">
                        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="#61DAFB" class="w-full h-full">
                            <path d="M12 0c-6.627 0-12 5.373-12 12s5.373 12 12 12 12-5.373 12-12-5.373-12-12-12zm-2 15.5v-7h2v7h-2zm2-10v2h-2v-2h2z"/>
                        </svg>
                    </div>
                    <h3 class="font-semibold mb-2">React</h3>
                    <p class="text-gray-600 text-sm">Intermediate</p>
                </div>
                <div class="text-center p-6 rounded-lg bg-gray-50 hover:shadow-md transition-shadow">
                    <div class="w-16 h-16 mx-auto mb-4">
                        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="#339933" class="w-full h-full">
                            <path d="M12 0c-6.627 0-12 5.373-12 12s5.373 12 12 12 12-5.373 12-12-5.373-12-12-12zm-2 16h-2v-8h2v8zm4 0h-2v-12h2v12z"/>
                        </svg>
                    </div>
                    <h3 class="font-semibold mb-2">Node.js</h3>
                    <p class="text-gray-600 text-sm">Intermediate</p>
                </div>
                <div class="text-center p-6 rounded-lg bg-gray-50 hover:shadow-md transition-shadow">
                    <div class="w-16 h-16 mx-auto mb-4">
                        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="#339933" class="w-full h-full">
                            <path d="M12 0c-6.627 0-12 5.373-12 12s5.373 12 12 12 12-5.373 12-12-5.373-12-12-12zm-1 17v-10h2v10h-2zm2-12v-2h-2v2h2z"/>
                        </svg>
                    </div>
                    <h3 class="font-semibold mb-2">Python</h3>
                    <p class="text-gray-600 text-sm">Intermediate</p>
                </div>
                <div class="text-center p-6 rounded-lg bg-gray-50 hover:shadow-md transition-shadow">
                    <div class="w-16 h-16 mx-auto mb-4">
                        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="#4479A1" class="w-full h-full">
                            <path d="M12 0c-6.627 0-12 5.373-12 12s5.373 12 12 12 12-5.373 12-12-5.373-12-12-12zm-1 18v-8h2v8h-2zm2-12v-2h-2v2h2z"/>
                        </svg>
                    </div>
                    <h3 class="font-semibold mb-2">MongoDB</h3>
                    <p class="text-gray-600 text-sm">Beginner</p>
                </div>
                <div class="text-center p-6 rounded-lg bg-gray-50 hover:shadow-md transition-shadow">
                    <div class="w-16 h-16 mx-auto mb-4">
                        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="#CC6699" class="w-full h-full">
                            <path d="M12 0c-6.627 0-12 5.373-12 12s5.373 12 12 12 12-5.373 12-12-5.373-12-12-12zm-1 16h-2v-6h2v6zm0-8h-2v-2h2v2zm4 8h-2v-8h2v8zm0-10h-2v-2h2v2z"/>
                        </svg>
                    </div>
                    <h3 class="font-semibold mb-2">Django</h3>
                    <p class="text-gray-600 text-sm">Beginner</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-20 bg-gray-50">
        <div class="max-w-4xl mx-auto px-4">
            <h2 class="text-3xl font-bold text-center mb-12">Get In Touch</h2>
            <div class="bg-white rounded-lg shadow-md p-8">
                <form id="contactForm" class="space-y-6">
                    <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
                        <div>
                            <label for="name" class="block text-sm font-medium text-gray-700 mb-1">Your Name</label>
                            <input type="text" id="name" class="w-full px-4 py-2 border rounded-md focus:ring-blue-500 focus:border-blue-500" required>
                        </div>
                        <div>
                            <label for="email" class="block text-sm font-medium text-gray-700 mb-1">Email Address</label>
                            <input type="email" id="email" class="w-full px-4 py-2 border rounded-md focus:ring-blue-500 focus:border-blue-500" required>
                        </div>
                    </div>
                    <div>
                        <label for="subject" class="block text-sm font-medium text-gray-700 mb-1">Subject</label>
                        <input type="text" id="subject" class="w-full px-4 py-2 border rounded-md focus:ring-blue-500 focus:border-blue-500" required>
                    </div>
                    <div>
                        <label for="message" class="block text-sm font-medium text-gray-700 mb-1">Message</label>
                        <textarea id="message" rows="5" class="w-full px-4 py-2 border rounded-md focus:ring-blue-500 focus:border-blue-500" required></textarea>
                    </div>
                    <button type="submit" class="w-full bg-blue-500 hover:bg-blue-600 text-white py-3 px-6 rounded-md transition-colors duration-300">
                        Send Message
                    </button>
                </form>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-800 text-white py-12">
        <div class="max-w-6xl mx-auto px-4">
            <div class="flex flex-col md:flex-row justify-between items-center">
                <div class="mb-6 md:mb-0">
                    <h3 class="text-2xl font-bold mb-2">RISM</h3>
                    <p class="text-gray-400">INFORMATION TECHNOLOGY</p>
                </div>
                <div class="flex space-x-6">
                    <a href="#" class="hover:text-blue-400 transition-colors">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="currentColor" viewBox="0 0 24 24">
                            <path d="M12 0c-6.626 0-12 5.373-12 12 0 5.302 3.438 9.8 8.207 11.387.599.111.793-.261.793-.577v-2.234c-3.338.726-4.033-1.416-4.033-1.416-.546-1.387-1.333-1.756-1.333-1.756-1.089-.745.083-.729.083-.729 1.205.084 1.839 1.237 1.839 1.237 1.07 1.834 2.807 1.304 3.492.997.107-.775.418-1.305.762-1.604-2.665-.305-5.467-1.334-5.467-5.931 0-1.311.469-2.381 1.236-3.221-.124-.303-.535-1.524.117-3.176 0 0 1.008-.322 3.301 1.23.957-.266 1.983-.399 3.003-.404 1.02.005 2.047.138 3.006.404 2.291-1.552 3.297-1.23 3.297-1.23.653 1.653.242 2.874.118 3.176.77.84 1.235 1.911 1.235 3.221 0 4.609-2.807 5.624-5.479 5.921.43.372.823 1.102.823 2.222v3.293c0 .319.192.694.801.576 4.765-1.589 8.199-6.086 8.199-11.386 0-6.627-5.373-12-12-12z"/>
                        </svg>
                    </a>
                    <a href="#" class="hover:text-blue-400 transition-colors">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="currentColor" viewBox="0 0 24 24">
                            <path d="M19 0h-14c-2.761 0-5 2.239-5 5v14c0 2.761 2.239 5 5 5h14c2.762 0 5-2.239 5-5v-14c0-2.761-2.238-5-5-5zm-11 19h-3v-11h3v11zm-1.5-12.268c-.966 0-1.75-.79-1.75-1.764s.784-1.764 1.75-1.764 1.75.79 1.75 1.764-.783 1.764-1.75 1.764zm13.5 12.268h-3v-5.604c0-3.368-4-3.113-4 0v5.604h-3v-11h3v1.765c1.396-2.586 7-2.777 7 2.476v6.759z"/>
                        </svg>
                    </a>
                    <a href="#" class="hover:text-blue-400 transition-colors">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="currentColor" viewBox="0 0 24 24">
                            <path d="M19.615 3.184c-3.604-.246-11.631-.245-15.23 0-3.897.266-4.356 2.62-4.385 8.816.029 6.185.484 8.549 4.385 8.816 3.6.245 11.626.246 15.23 0 3.897-.266 4.356-2.62 4.385-8.816-.029-6.185-.484-8.549-4.385-8.816zm-10.615 12.816v-8l8 3.993-8 4.007z"/>
                        </svg>
                    </a>
                    <a href="#" class="hover:text-blue-400 transition-colors">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="currentColor" viewBox="0 0 24 24">
                            <path d="M24 4.557c-.883.392-1.832.656-2.828.775 1.017-.609 1.798-1.574 2.165-2.724-.951.564-2.005.974-3.127 1.195-.897-.957-2.178-1.555-3.594-1.555-3.179 0-5.515 2.966-4.797 6.045-4.091-.205-7.719-2.165-10.148-5.144-1.29 2.213-.669 5.108 1.523 6.574-.806-.026-1.566-.247-2.229-.616-.054 2.281 1.581 4.415 3.949 4.89-.693.188-1.452.232-2.224.084.626 1.956 2.444 3.379 4.6 3.419-2.07 1.623-4.678 2.348-7.29 2.04 2.179 1.397 4.768 2.212 7.548 2.212 9.142 0 14.307-7.721 13.995-14.646.962-.695 1.797-1.562 2.457-2.549z"/>
                        </svg>
                    </a>
                </div>
            </div>
            <div class="border-t border-gray-700 mt-8 pt-8 text-center text-gray-400">
                <p>&copy;</p>
            </div>
        </div>
    </footer>

    <!-- Back to Top Button -->
    <button id="backToTop" class="fixed bottom-8 right-8 bg-blue-500 text-white rounded-full p-3 shadow-lg hidden">
        <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 10l7-7m0 0l7 7m-7-7v18" />
        </svg>
    </button>

    <script>
        // Back to top button
        const backToTopButton = document.getElementById('backToTop');
        
        window.addEventListener('scroll', () => {
            if (window.pageYOffset > 300) {
                backToTopButton.classList.remove('hidden');
            } else {
                backToTopButton.classList.add('hidden');
            }
        });
        
        backToTopButton.addEventListener('click', () => {
            window.scrollTo({ top: 0, behavior: 'smooth' });
        });
        
        // Mobile menu toggle
        document.querySelector('nav button').addEventListener('click', () => {
            document.querySelector('nav div:nth-child(2)').classList.toggle('hidden');
        });
        
        // Form submission
        document.getElementById('contactForm').addEventListener('submit', (e) => {
            e.preventDefault();
            alert('Thank you for your message! I will get back to you soon.');
            e.target.reset();
        });
        
        // Smooth scrolling for navigation links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function(e) {
                e.preventDefault();
                
                const targetId = this.getAttribute('href');
                const targetElement = document.querySelector(targetId);
                
                window.scrollTo({
                    top: targetElement.offsetTop - 80,
                    behavior: 'smooth'
                });
            });
        });
    </script>
</body>
</html>
```
