# IEM-Sound-Explorer
I built an app to explore the different available sound signatures on my IEMs.

IEM Sound Explorer
A sleek, modern, and futuristic web application designed to help users visualize and understand the sound profiles of their In-Ear Monitors (IEMs) based on different configuration settings. This app allows users to explore various sound modes and acoustic filters, view the resulting frequency response curves, and discover music genres best suited for each configuration.
Features
 * Dynamic Frequency Response Visualization: See real-time updates of the frequency response curve as you change sound modes and acoustic filters.
 * Mode Selection: Easily switch between "Pop Mode" and "Monitor Mode" to observe their distinct sound signatures.
 * Acoustic Filter Selection: Choose from a variety of colored filters (Stainless Steel, Red, Blue, Green, Gold, Silver) to fine-tune the audio output.
 * Genre-Based Recommendations: Select your favorite music genre from a predefined list, and the app will recommend the optimal IEM configuration for that genre, along with a descriptive explanation.
 * Configuration-Based Genre Suggestions: When you manually select a configuration, the app will suggest music genres that would sound best with that specific sound profile.
 * Sleek & Futuristic UI: A dark, modern interface with vibrant accents and smooth transitions, designed for an engaging user experience.
 * Responsive Design: Optimized for seamless use across various devices, from mobile phones to desktop computers.
How It Works
The application uses hardcoded frequency response data and genre recommendations, which are approximated from the provided IEM manual images. This allows for quick visualization and recommendation without requiring external API calls.
Getting Started
To run this application locally, you will need to:
 * Save the provided React code (from the previous response) as App.js.
 * Save the index.html code (from this response) as index.html in the same directory as App.js.
 * Open the index.html file in your web browser.
The index.html file includes the necessary CDN links for React, ReactDOM, Babel, and Tailwind CSS, allowing the application to run directly in your browser without a complex build setup.
Technologies Used
 * React: For building the user interface.
 * Tailwind CSS: For rapid and responsive styling.
 * Recharts: For creating the interactive frequency response graph.
 * Lucide React: For modern, customizable icons.
Data Source
The frequency response curves and genre recommendations are based on approximations derived from the provided manual images of a specific IEM model. While efforts were made to accurately represent the curves, they are illustrative and may not perfectly match real-world measurements.
Contribution
This project is a demonstration of a visualizer app. Feel free to modify the frequencyResponseData and genreRecommendations within App.js to match other IEMs or refine the existing data.
