
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta="viewport" content="width=device-width, initial-scale=1.0">
    <title> Hello I'm Toyin Akande Salesforce BA Portfolio</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        /* Custom CSS for Inter font and general body styling */
        body {
            font-family: 'Inter', sans-serif;
            background-color: #f0f4f8; /* Light gray background */
            color: #333; /* Dark text color */
            line-height: 1.6;
        }
        /* Custom scrollbar for a cleaner look */
        ::-webkit-scrollbar {
            width: 8px;
        }
        ::-webkit-scrollbar-track {
            background: #f0f4f8;
            border-radius: 10px;
        }
        ::-webkit-scrollbar-thumb {
            background: #888;
            border-radius: 10px;
        }
        ::-webkit-scrollbar-thumb:hover {
            background: #555;
        }

        /* Basic styles for elements to ensure responsiveness and good spacing */
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 1rem; /* Responsive padding */
        }

        /* Hero section background and text alignment */
        #hero {
            background: linear-gradient(to right, #6366f1, #8b5cf6); /* Purple gradient */
            color: white;
            padding: 4rem 1rem;
            text-align: center;
        }

        /* Section padding and background */
        section {
            padding: 3rem 1rem;
            background-color: white;
            margin-bottom: 2rem;
            border-radius: 0.75rem; /* Rounded corners for sections */
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1); /* Subtle shadow */
        }

        /* Skill card styling */
        .skill-card {
            background-color: #e0e7ff; /* Light blue background for skill cards */
            padding: 1.5rem;
            border-radius: 0.5rem;
            text-align: center;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.05);
            transition: transform 0.2s ease-in-out;
        }

        .skill-card:hover {
            transform: translateY(-5px); /* Lift effect on hover */
        }

        /* Project card styling */
        .project-card {
            background-color: #f8fafc; /* Lighter background for project cards */
            padding: 1.5rem;
            border-radius: 0.75rem;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            transition: transform 0.2s ease-in-out;
        }

        .project-card:hover {
            transform: scale(1.02); /* Slightly grow on hover */
        }

        /* Call to action button styling */
        .cta-button {
            display: inline-block;
            background-color: #6366f1; /* Purple background */
            color: white;
            padding: 0.75rem 1.5rem;
            border-radius: 0.5rem;
            text-decoration: none;
            font-weight: 600;
            transition: background-color 0.2s ease-in-out;
        }

        .cta-button:hover {
            background-color: #4f46e5; /* Darker purple on hover */
        }

        /* Responsive images */
        img {
            max-width: 100%;
            height: auto;
            border-radius: 0.5rem;
        }

        /* Footer styling */
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 2rem 1rem;
            margin-top: 2rem;
            border-top-left-radius: 0.75rem;
            border-top-right-radius: 0.75rem;
        }

        /* Responsive breakpoints for skill grid */
        @media (min-width: 640px) { /* Small screens and up */
            .sm\:grid-cols-2 {
                grid-template-columns: repeat(2, minmax(0, 1fr));
            }
        }
        @media (min-width: 768px) { /* Medium screens and up */
            .md\:grid-cols-3 {
                grid-template-columns: repeat(3, minmax(0, 1fr));
            }
        }
        @media (min-width: 1024px) { /* Large screens and up */
            .lg\:grid-cols-4 {
                grid-template-columns: repeat(4, minmax(0, 1fr));
            }
        }
    </style>
</head>
<body>
    <!-- Header Section -->
    <header class="bg-white shadow-md py-4">
        <nav class="container flex justify-between items-center">
            <h1 class="text-2xl font-bold text-indigo-700 rounded-lg p-2 bg-indigo-100">Your Name</h1>
            <ul class="flex space-x-6">
                <li><a href="#about" class="text-gray-700 hover:text-indigo-600 font-medium transition duration-300">About</a></li>
                <li><a href="#skills" class="text-gray-700 hover:text-indigo-600 font-medium transition duration-300">Skills</a></li>
                <li><a href="#portfolio" class="text-gray-700 hover:text-indigo-600 font-medium transition duration-300">Portfolio</a></li>
                <li><a href="#contact" class="text-gray-700 hover:text-indigo-600 font-medium transition duration-300">Contact</a></li>
            </ul>
        </nav>
    </header>

    <!-- Hero Section -->
    <section id="hero" class="py-20">
        <div class="container">
            <h2 class="text-5xl font-extrabold mb-4 leading-tight">Salesforce Business Analyst</h2>
            <p class="text-xl mb-8 opacity-90">Bridging the gap between business needs and Salesforce solutions.</p>
            <a href="#portfolio" class="cta-button">View My Work</a>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="container">
        <h3 class="text-4xl font-bold text-gray-800 mb-8 text-center">About Me</h3>
        <div class="md:flex md:items-center md:space-x-8">
            <div class="md:w-1/3 mb-6 md:mb-0">
                <!-- Placeholder for an image of yourself or a professional icon -->
                <img src="https://placehold.co/400x400/8b5cf6/ffffff?text=Your+Photo" alt="Your Photo" class="rounded-full mx-auto md:mx-0 shadow-lg border-4 border-indigo-300">
            </div>
            <div class="md:w-2/3 text-lg text-gray-700">
                <p class="mb-4">
                    As a dedicated Salesforce Business Analyst, I specialize in transforming complex business requirements into scalable and efficient Salesforce solutions. With a keen eye for detail and a passion for optimizing processes, I excel at facilitating communication between stakeholders and technical teams.
                </p>
                <p>
                    My expertise spans the entire project lifecycle, from initial requirement gathering and meticulous documentation to process mapping, user story creation, and robust quality assurance using tools like Copado. I am committed to delivering high-quality solutions that drive business value and ensure user satisfaction through comprehensive UAT support and hypercare activities.
                </p>
            </div>
        </div>
    </section>

    <!-- Skills Section -->
    <section id="skills" class="container">
        <h3 class="text-4xl font-bold text-gray-800 mb-8 text-center">My Core Skills</h3>
        <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-6">
            <div class="skill-card">
                <h4 class="text-xl font-semibold text-indigo-700 mb-2">Requirement Gathering</h4>
                <p class="text-gray-600">Expert in eliciting, analyzing, and documenting comprehensive business requirements.</p>
            </div>
            <div class="skill-card">
                <h4 class="text-xl font-semibold text-indigo-700 mb-2">Requirement Analysis & Documentation</h4>
                <p class="text-gray-600">Skilled in translating raw needs into clear, concise, and actionable specifications.</p>
            </div>
            <div class="skill-card">
                <h4 class="text-xl font-semibold text-indigo-700 mb-2">User Story Writing</h4>
                <p class="text-gray-600">Crafting detailed and user-centric agile user stories for development.</p>
            </div>
            <div class="skill-card">
                <h4 class="text-xl font-semibold text-indigo-700 mb-2">Business Process Architecture & Mapping</h4>
                <p class="text-gray-600">Designing and visualizing optimized business processes for efficiency.</p>
            </div>
            <div class="skill-card">
                <h4 class="text-xl font-semibold text-indigo-700 mb-2">Test Case & Script Creation</h4>
                <p class="text-gray-600">Developing thorough test cases and scripts to ensure solution quality.</p>
            </div>
            <div class="skill-card">
                <h4 class="text-xl font-semibold text-indigo-700 mb-2">Quality Assurance (Copado)</h4>
                <p class="text-gray-600">Executing robust QA processes, leveraging Copado for release management.</p>
            </div>
            <div class="skill-card">
                <h4 class="text-xl font-semibold text-indigo-700 mb-2">UAT Support</h4>
                <p class="text-gray-600">Providing comprehensive support and guidance during User Acceptance Testing.</p>
            </div>
            <div class="skill-card">
                <h4 class="text-xl font-semibold text-indigo-700 mb-2">Hypercare Activities</h4>
                <p class="text-gray-600">Ensuring smooth post-go-live transitions and ongoing user assistance.</p>
            </div>
        </div>
    </section>

    <!-- Portfolio/Projects Section -->
    <section id="portfolio" class="container">
        <h3 class="text-4xl font-bold text-gray-800 mb-8 text-center">My Portfolio Projects</h3>
        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
            <!-- Project 1 Placeholder -->
            <div class="project-card">
                <img src="https://placehold.co/600x400/6366f1/ffffff?text=Project+1+Image" alt="Project 1" class="mb-4">
                <h4 class="text-2xl font-semibold text-gray-800 mb-2">Sales Cloud Implementation for [Client Name]</h4>
                <p class="text-gray-700 mb-4">
                    Led the business analysis efforts for a comprehensive Sales Cloud implementation, streamlining lead-to-cash processes. Developed detailed user stories, process flows, and facilitated UAT.
                </p>
                <a href="#" class="text-indigo-600 hover:underline font-medium">View Case Study &rarr;</a>
            </div>

            <!-- Project 2 Placeholder -->
            <div class="project-card">
                <img src="https://placehold.co/600x400/8b5cf6/ffffff?text=Project+2+Image" alt="Project 2" class="mb-4">
                <h4 class="text-2xl font-semibold text-gray-800 mb-2">Service Cloud Optimization Initiative</h4>
                <p class="text-gray-700 mb-4">
                    Architected improved service processes within Service Cloud, reducing case resolution times by 15%. Created test scripts and managed QA cycles with Copado.
                </p>
                <a href="#" class="text-indigo-600 hover:underline font-medium">View Case Study &rarr;</a>
            </div>

            <!-- Project 3 Placeholder -->
            <div class="project-card">
                <img src="https://placehold.co/600x400/6366f1/ffffff?text=Project+3+Image" alt="Project 3" class="mb-4">
                <h4 class="text-2xl font-semibold text-gray-800 mb-2">Custom App Development: Requirements to Go-Live</h4>
                <p class="text-gray-700 mb-4">
                    Facilitated requirements gathering for a custom Salesforce application, translating complex needs into actionable design specifications and supporting post-launch hypercare.
                </p>
                <a href="#" class="text-indigo-600 hover:underline font-medium">View Case Study &rarr;</a>
            </div>

            <!-- Add more project placeholders here following the same structure -->
            <!--
            <div class="project-card">
                <img src="https://placehold.co/600x400/8b5cf6/ffffff?text=Future+Project" alt="Future Project" class="mb-4">
                <h4 class="text-2xl font-semibold text-gray-800 mb-2">Future Project Title Here</h4>
                <p class="text-gray-700 mb-4">
                    Brief description of your future project, focusing on the skills you utilized.
                </p>
                <a href="#" class="text-indigo-600 hover:underline font-medium">Coming Soon &rarr;</a>
            </div>
            -->
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="container text-center">
        <h3 class="text-4xl font-bold text-gray-800 mb-8">Get in Touch</h3>
        <p class="text-lg text-gray-700 mb-6">
            I'm always open to discussing new projects, opportunities, or how my Salesforce Business Analyst skills can benefit your organization.
        </p>
        <div class="flex flex-col items-center space-y-4">
            <a href="mailto:your.email@example.com" class="cta-button">Email Me: your.email@example.com</a>
            <p class="text-gray-600">Connect with me on:</p>
            <div class="flex space-x-6">
                <!-- LinkedIn Icon/Link (use a simple text link or find a Font Awesome CDN if allowed, otherwise plain text) -->
                <a href="https://www.linkedin.com/in/yourprofile" target="_blank" class="text-indigo-600 hover:text-indigo-800 font-medium">LinkedIn</a>
                <!-- Optional: Add a simple placeholder for other platforms if desired -->
                <!-- <a href="#" target="_blank" class="text-indigo-600 hover:text-indigo-800 font-medium">Your Blog/Website</a> -->
            </div>
        </div>
    </section>

    <!-- Footer Section -->
    <footer>
        <p>&copy; 2025 Your Name. All rights reserved.</p>
        <p>Built with ❤️ and Tailwind CSS.</p>
    </footer>
</body>
</html>
