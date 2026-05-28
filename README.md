KAVACH AI: Smart Safety Assistance System

Kolkata Municipal Corporation (KMC) Edition

Kavach AI is an intelligent, real-time safety assistance system designed to protect sanitation workers in hazardous underground sewer environments. By integrating IoT sensor telemetry, predictive analytics, and emergency response protocols, Kavach AI transforms high-risk municipal sewer work into a data-driven, secure operation.
🚀 Project Overview

This platform acts as a tactical Command Centre that monitors environmental hazards (H₂S, CH₄, CO levels), structural integrity, and worker vitals. It ensures that no worker enters a hazardous zone without proper risk assessment and supervisor clearance.
Key Features

    8-Factor Risk Engine: Analyzes real-time environmental data to provide "Safe," "Supervisor Approval Required," or "Entry Prohibited" verdicts.

    Live Sensor Grid: Monitors gas levels and structural health with real-time WebSocket updates.

    SOS Multi-Tier Dispatch: Automated emergency escalation to Ward Supervisors, Central Control, and 108 Emergency Services.

    Worker Health Monitoring: Tracks heart rate, temperature, and SpO₂ for field workers in real-time.

    Tactical Map: Live canvas visualization of KMC zones and active operational sites.

🛠 Tech Stack

    Frontend: Vanilla JavaScript (ES6+), CSS3 (Custom animations), Canvas API (for live mapping/charts).

    Backend: Node.js, Express.js.

    Database: MongoDB (via Mongoose).

    Communication: WebSockets (ws) for real-time telemetry streaming.

⚙ Getting Started
Prerequisites

    Node.js (v18+)

    MongoDB Instance (or local Compass)

    NPM

Installation

    Clone the repository:
    Bash

    git clone https://github.com/anandaashutosh206/kavach-Al-for-ideatex.git
    cd kavach-Al-for-ideatex

    Install dependencies:
    Bash

    # Run in the root directory
    npm install

    Environment Setup:
    Create a .env file in the root directory and add the following:
    Code snippet

    PORT=3000
    MONGO_URI=your_mongodb_connection_string
    JWT_SECRET=your_super_secret_key

    Run the project:
    Bash

    npm run dev

👥 Team Collaboration Workflow

To ensure smooth collaboration, please follow these guidelines:

    Branches: Create a new branch for every feature or bug fix:
    git checkout -b feature/your-feature-name

    Commits: Write clear, concise commit messages (e.g., feat: add sos emergency dispatch logic).

    Pull Requests: Before merging any code into main, please open a PR and ensure at least one other team member has reviewed it.

    Secrets: NEVER push your .env file to the repository.

📜 License

This project is licensed under the MIT License. See the LICENSE file for details.
Developed for Ideatex / Kolkata Municipal Corporation (KMC)

Project by the Engineering Team.
