## 🚀 Interactive Developer Dashboard

[](https://www.linkedin.com/in/mdtausifhussain/)
[](https://github.com/Md-Tausif-Hussain)

This repository hosts my personal **Developer Insight Dashboard**, a dynamic Single-Page Application (SPA) designed to showcase my academic, technical, and competitive strengths in a rich, interactive format. It serves as a data-driven alternative to a traditional resume.

-----

### 🌟 Interactive & Visual Highlights (Implementation Details)

The profile is engineered for engagement, replacing static text with data visualization and micro-interactions:

| Feature | Technology | Technical Implementation Detail |
| :--- | :--- | :--- |
| 🌐 **3D Data Core** | **Three.js** | Uses an **IcosahedronGeometry** with a `MeshPhongMaterial` and `wireframe: true`. Animation involves constant rotation combined with a **sine wave-driven radial vertex displacement** (a subtle pulsating/exploding effect) via `geometry.attributes.position.needsUpdate = true`. |
| 📊 **Skills Breakdown** | **Chart.js** | Renders a **Radar Chart** with fixed `suggestedMax: 100` and customized point labels. The **Doughnut Chart** uses an `onClick` handler to trigger an external function (`updateInsightText`) for dynamic text feedback. |
| 💡 **Dynamic Insights** | **Vanilla JS** | Uses event delegation on chart clicks to fetch context-specific data, applying **CSS opacity transitions** to the insight box for a smooth fade-in/out effect. |
| 💥 **The Snap** | **Tone.js & CSS** | Implements the effect by cloning the text block, replacing letters with individual `<span>` **particle elements**, and applying a randomized `snap-disintegrate` keyframe animation (simulating dust scattering) over 2.5s. A **Tone.NoiseSynth** triggers a short white noise burst for the sound effect. |
| 👂 **Haptic Feedback** | **Tone.js** | Employs a **Tone.Synth** with a short, sharp ADSR envelope (`attack: 0.005, decay: 0.1, sustain: 0, release: 0.1`) to generate an audible 'pop' that simulates haptic touch confirmation on link clicks. |
| **Responsive Design** | **Tailwind CSS** | Uses utilities to hide the Doughnut chart on mobile and dynamically renders **fluid progress bars** using CSS transitions (`.progress-bar-fill`) to ensure optimal mobile data display. |

-----

### 🛠️ Core Tech Stack and Architecture

The application is built entirely client-side using a clean, modern stack relying on CDNs for minimal setup complexity.

| Category | Technology | Usage/Rationale |
| :--- | :--- | :--- |
| **Styling & Structure** | **HTML5 / Tailwind CSS** | Utility-first styling for high maintainability. Layout uses a flexible grid system combined with responsive classes (`md:`, `lg:`) for optimal viewport adaptation. |
| **Data Visualization** | **Chart.js (CDN)** | Utilized for efficient rendering of **`radar`** and **`doughnut`** chart types, focusing on performance and lightweight interactivity. |
| **Interactive Graphics** | **Three.js (CDN)** | Provides low-level GPU access for 3D geometry rendering and dynamic vertex manipulation. |
| **Audio Synthesis** | **Tone.js (CDN)** | Acts as a Web Audio API abstraction layer, generating sound effects programmatically rather than playing static sound files. |
| **Control Logic** | **Vanilla JavaScript** | Employs clean functions for state management, scroll-to-section navigation, and responsive event handling (e.g., drag control for Three.js). |

-----

### 📂 Project Structure

This project is a highly optimized static site condensed into a single HTML file for portability and ease of deployment.

  * `index.html`: Contains all HTML structure, inline Tailwind CSS utility classes, and all JavaScript logic (`Chart.js`, `Three.js`, `Tone.js` initialization).

### ⚙️ How to Run Locally

Since this is a client-side application, running it is instantaneous:

1.  **Clone the Repository:**
    ```bash
    git clone https://github.com/Md-Tausif-Hussain/interactive-profile-repo
    cd interactive-profile-repo
    ```
2.  **Launch:**
    Open the `index.html` file directly in your preferred web browser.

-----

### 📧 Connect & Collaborate

I am open to discussions on software development roles, DSA challenges, or any collaborative opportunities.

| Platform | Link |
| :--- | :--- |
| **GitHub** | [Md-Tausif-Hussain](https://github.com/Md-Tausif-Hussain) |
| **LinkedIn** | [Connect Professionally](https://www.linkedin.com/in/mdtausifhussain/) |
| **LeetCode** | [Track My Progress](https://leetcode.com/u/Tausif_21/) |
| **Codeforces** | [View My Rating](https://codeforces.com/profile/Tausif_21) |
| **GeeksforGeeks** | [Check My Submissions](https://www.geeksforgeeks.org/user/tausifh21/) |
| **Unstop** | [Competitive Profile](https://unstop.com/u/Tausif_21) |
