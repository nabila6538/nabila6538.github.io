<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Graphic Designer CV</title>
    <script src="https://cdn.tailwindcss.com"></script>
  </head>
  <body class="bg-gray-100 text-gray-900">
    <header
      class="w-full bg-white shadow-md py-4 px-6 flex justify-between items-center"
    >
      <h1 class="text-2xl font-bold">My CV</h1>
      <nav>
        <ul class="flex space-x-6">
          <li><a href="#about" class="hover:text-blue-500">About</a></li>
          <li>
            <a href="#experience" class="hover:text-blue-500">Experience</a>
          </li>
          <li><a href="#skills" class="hover:text-blue-500">Skills</a></li>
          <li><a href="#projects" class="hover:text-blue-500">Projects</a></li>
          <li>
            <a href="#education" class="hover:text-blue-500">Education</a>
          </li>
          <li><a href="#contact" class="hover:text-blue-500">Contact</a></li>
        </ul>
      </nav>
    </header>

    <section
      id="about"
      class="text-center py-20 bg-gradient-to-r from-blue-500 to-purple-600 text-white"
    >
      <div
        class="py-16 px-6 max-w-5xl mx-auto flex justify-between items-center"
      >
        <div>
          <img
            src="haii.jpg"
            alt="Profile Picture"
            class="mx-auto rounded-full mb-4"
          />
        </div>
        <div>
          <h2 class="text-4xl font-bold">Hello, I'm a Graphic Designer</h2>
          <p class="mt-4 text-lg">
            Creating stunning visuals that tell a story.
          </p>
        </div>
      </div>
    </section>

    <section id="experience" class="py-16 px-6 max-w-5xl mx-auto">
      <h2 class="text-3xl font-bold text-center mb-8">Experience</h2>
      <ul class="space-y-4">
        <li>
          <strong>Senior Graphic Designer</strong> - ABC Agency (2020 - Present)
        </li>
        <li>
          <strong>Freelance Designer</strong> - Self-employed (2017 - 2020)
        </li>
        <li><strong>Junior Designer</strong> - XYZ Studio (2015 - 2017)</li>
      </ul>
    </section>

    <section id="skills" class="py-16 px-6 max-w-5xl mx-auto">
      <h2 class="text-3xl font-bold text-center mb-8">Skills</h2>
      <div class="grid grid-cols-2 md:grid-cols-3 gap-4 text-center">
        <span class="bg-white shadow-md py-2 px-4 rounded-lg"
          >Adobe Photoshop</span
        >
        <span class="bg-white shadow-md py-2 px-4 rounded-lg">Illustrator</span>
        <span class="bg-white shadow-md py-2 px-4 rounded-lg">Figma</span>
        <span class="bg-white shadow-md py-2 px-4 rounded-lg"
          >UI/UX Design</span
        >
        <span class="bg-white shadow-md py-2 px-4 rounded-lg">Branding</span>
        <span class="bg-white shadow-md py-2 px-4 rounded-lg">Typography</span>
      </div>
    </section>

    <section id="projects" class="py-16 px-6 max-w-5xl mx-auto">
      <h2 class="text-3xl font-bold text-center mb-8">My Work</h2>
      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">
        <div class="bg-white shadow-md p-4 rounded-lg">
          <img
            src="Nabila.jpg"
            alt="Project 1"
            class="rounded-lg"
          />
          <h3 class="mt-4 text-xl font-bold">Project 1</h3>
        </div>
        <div class="bg-white shadow-md p-4 rounded-lg">
          <img
            src="projek.jpg"
            alt="Project 2"
            class="rounded-lg"
          />
          <h3 class="mt-4 text-xl font-bold">Project 2</h3>
        </div>
        <div class="bg-white shadow-md p-4 rounded-lg">
          <img
            src="projek2.jpg"
            alt="Project 3"
            class="rounded-lg"
          />
          <h3 class="mt-4 text-xl font-bold">Project 3</h3>
        </div>
      </div>
    </section>

    <section id="education" class="py-16 px-6 max-w-5xl mx-auto">
      <h2 class="text-3xl font-bold text-center mb-8">Education</h2>
      <p>
        <strong>Bachelor of Arts in Graphic Design</strong> - ABC University
        (2011 - 2015)
      </p>
    </section>

    <section id="contact" class="py-16 px-6 text-center bg-gray-200">
      <h2 class="text-3xl font-bold mb-4">Get in Touch</h2>
      <p>Reach out via email at <strong>your@email.com</strong></p>
    </section>

    <footer class="text-center py-4 bg-gray-900 text-white">
      <p>&copy; 2025 Your Name. All rights reserved.</p>
    </footer>
  </body>
</html>
