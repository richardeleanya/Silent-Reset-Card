This GitHub repository description is designed to be authoritative, technically transparent, and professional. It follows the industry standard for high-impact open-source or private enterprise projects, ensuring that developers and stakeholders understand the system architecture at a glance.
GitHub Repository: Silent Reset Cards (SRC) Digital Ecosystem
📋 Project Overview
Silent Reset Cards (SRC) is a privacy-first, ultra-lightweight web application designed to provide instant emotional grounding via physical QR-to-Digital interaction. This repository contains the source code for the "90-Second Reset" frontend, the Dynamic Routing API, and the Institutional Analytics Dashboard.
The project is engineered for University and Healthcare environments where speed, ADA compliance, and data privacy (GDPR) are non-negotiable.
🛠 Technical Stack
 * Frontend: Vanilla JavaScript (ES6+), HTML5, CSS3 (Zero-framework architecture for <1s load times).
 * Backend: Node.js / Cloudflare Workers (Edge computing for global low latency).
 * Database: DynamoDB / Redis (High-speed, non-relational aggregate logging).
 * Infrastructure: Terraform (Infrastructure as Code) for UK-based AWS/Azure deployment.
 * CI/CD: GitHub Actions for automated WCAG accessibility auditing and unit testing.
🚀 Key Features
1. Zero-Friction Frontend
 * No-Log Architecture: No cookies, local storage, or PII (Personally Identifiable Information) collection.
 * Performance Optimized: Critical path CSS rendering ensures the breathing animation is functional before the full page loads.
 * Offline Support: PWA (Progressive Web App) capabilities via Service Workers to handle "dead zones" in campus buildings.
2. The 90-Second Grounding Logic
A structured, state-controlled sequence programmed via CSS Keyframes and JS Intersection Observers:
 * Module A (Box Breathing): 4-4-4-4 rhythm visualizer with prefers-reduced-motion fallbacks.
 * Module B (Sensory Grounding): High-contrast text prompts (3-2-1 method).
 * Module C (Resource Bridge): Dynamic CTA (Call to Action) buttons linked to LocationID specific resources.
3. Enterprise Analytics Dashboard
 * Aggregate Data Visualization: Chart.js implementation for monitoring environmental stress spikes.
 * Dynamic QR Routing: A single codebase serving multiple institutions via URL-path parameters (/uk/oxford/lib-01).
📂 Repository Structure
├── .github/workflows       # CI/CD: Accessibility (Pa11y) & Security scans
├── src/
│   ├── assets/             # Optimized SVG icons & branding
│   ├── css/                # Main styles & 60fps animations
│   ├── js/                 # Experience logic & Service Worker registration
│   └── index.html          # Entry point (optimized for TTFB)
├── api/                    # Cloudflare Workers / Serverless functions
├── dashboard/              # Admin-facing React/Vue dashboard (Optional)
├── docs/                   # Pilot Application & Technical Spec (PDFs)
├── tests/                  # Jest unit tests & Lighthouse performance scripts
└── README.md               # You are here

♿ Accessibility (WCAG 2.1 AAA)
This repository prioritizes inclusive design:
 * Aria-Live Regions: Real-time audio descriptions for breathing cues.
 * Semantic HTML: Strict adherence to header hierarchy.
 * Color Contrast: All UI elements maintain a minimum 7:1 contrast ratio.
🔒 Security & Privacy
 * GDPR Compliant: No user data is ever persisted. Logs are limited to Timestamp + LocationID.
 * CSP Headers: Strict Content Security Policy to prevent XSS and clickjacking.
 * Subresource Integrity (SRI): Ensuring third-party assets (if any) are not tampered with.
🛠 Installation & Local Development
 * Clone the repo: git clone https://github.com/org/silent-reset-cards.git
 * Install dependencies: npm install (primarily for testing and linting).
 * Run local server: npm start (utilizes a simple browserSync for real-time mobile testing).
 * Build for production: npm run build (minifies CSS/JS and optimizes SVGs).
📄 License
This project is licensed under the MIT License - see the LICENSE file for details.
Next Step: Would you like me to write the CONTRIBUTING.md file, which outlines the rules for developers who want to add new grounding exercises to the code?
