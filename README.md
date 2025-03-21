<h1 align="center">Carbon Crunch</h1>

<p align="center">
  <img src="https://img.shields.io/badge/React-18.0.0-blue" alt="React">
  <img src="https://img.shields.io/badge/Three.js-0.160.0-green" alt="Three.js">
  <img src="https://img.shields.io/badge/GSAP-3.12.2-purple" alt="GSAP">
  <img src="https://img.shields.io/badge/License-MIT-yellow" alt="License">
</p>

<p align="center">
  A modern web application for sustainability reporting and carbon footprint tracking with interactive 3D visualizations.
</p>

<p align="center">
  <img src="./public/screenshot.png" alt="Carbon Crunch Preview" width="800">
</p>

<h2>Overview</h2>

<p>
  Carbon Crunch helps businesses track, visualize, and report on their sustainability metrics with an intuitive, animated interface. The application features interactive 3D card visualizations of key ESG metrics and responsive design for all devices.
</p>

<h2>Dependencies</h2>

<p>Before running the application, install the following dependencies:</p>

<pre><code># Core dependencies
npm install react react-dom

# Routing
npm install react-router-dom

# 3D and Animation libraries
npm install three gsap

# UI utilities
npm install classnames
</code></pre>

<h2>Quick Start</h2>

<ol>
  <li>Clone the repository:
<pre><code>git clone https://github.com/yourusername/carbon-crunch.git
cd carbon-crunch</code></pre>
  </li>
  <li>Install dependencies:
<pre><code>npm install</code></pre>
  </li>
  <li>Start the development server:
<pre><code>npm start</code></pre>
  </li>
  <li>Open your browser and navigate to <code>http://localhost:3000</code></li>
</ol>

<h2>Features</h2>

<ul>
  <li> <strong>Interactive 3D Card Animation</strong>: Visualize sustainability metrics with animated 3D cards</li>
  <li><strong>Responsive Design</strong>: Optimized for desktop, tablet, and mobile devices</li>
  <li> <strong>Animated Background</strong>: Dynamic particle network that responds to user movement</li>
  <li> <strong>Page Animations</strong>: Smooth transitions and scroll-triggered animations for enhanced UX</li>
  <li><strong>Real-time Data Visualization</strong>: Interactive charts and statistics displays</li>
</ul>

<h2>Project Structure</h2>

<pre><code>carbon-crunch/
├── public/                  # Static files
├── src/
│   ├── animations/          # Animation system files
│   ├── components/          # React components
│   │   ├── Navbar.js        # Navigation bar
│   │   ├── Hero.js          # Hero section
│   │   ├── ThreeJsCardSection.js  # 3D card animation 
│   │   └── ...
│   ├── styles/              # CSS styles
│   ├── App.js               # Main application component
│   └── index.js             # Entry point
└── package.json             # Project dependencies
</code></pre>

<h2>Browser Support</h2>

<p>The application works best on modern browsers that support WebGL:</p>
<ul>
  <li>Chrome (latest)</li>
  <li>Firefox (latest)</li>
  <li>Safari (latest)</li>
  <li>Edge (latest)</li>
</ul>

<h2>Performance Notes</h2>

<ul>
  <li>The 3D card animation uses ThreeJS and may be resource-intensive on older devices</li>
  <li>A responsive fallback is provided for devices that can't handle 3D graphics</li>
  <li>Animation intensity automatically scales based on device capabilities</li>
</ul>

<h2>Credits</h2>

<ul>
  <li><a href="https://threejs.org/">Three.js</a> for 3D rendering</li>
  <li><a href="https://greensock.com/gsap/">GSAP</a> for animations</li>
  <li><a href="https://fonts.google.com/specimen/Inter">Inter</a> font family by Google Fonts</li>
</ul>



<p>Contributions are welcome! Please feel free to submit a Pull Request.</p>

<h2>Contact</h2>

<p>For questions or feedback, please open an issue on this repository.</p>
