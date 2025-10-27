# Deep-Fake Detection System

Deepfake Detection System | Powered by ResNeXt + LSTM Technology

## Overview

This project focuses on developing a robust deepfake detection system leveraging the strengths of both ResNeXt and LSTM neural networks. The system is designed to analyze video and image data to identify manipulated or synthetic content.

## Key Features

*   **ResNeXt Integration:** Utilizes ResNeXt for feature extraction, capturing rich spatial hierarchies within the input data.
*   **LSTM for Temporal Analysis:** Employs LSTM networks to model temporal dependencies in video sequences, crucial for detecting subtle inconsistencies indicative of deepfakes.
*   **Next.js Frontend:** A modern web interface built with Next.js for easy interaction and visualization of detection results

## Technologies Used

*   Python
*   ResNeXt
*   LSTM
*   Next.js
*   [Other libraries/frameworks used, e.g., TensorFlow, PyTorch]

High-Level Architecture:
<img width="450" height="327" alt="image" src="https://github.com/user-attachments/assets/bf9cdcd0-9cc0-4092-965a-828a429a113d" />

Technology Stack:
Frontend Framework: React with TypeScript
Build Tool: Vite
Styling: Tailwind CSS
Package Manager: Bun
Component Library: ShadCN UI components
Routing: React Router DOM
State Management: React Hooks, TanStack Query
Notification System: Toast/Sonner
Directory Structure:

<img width="499" height="447" alt="image" src="https://github.com/user-attachments/assets/f24cb1bc-ba84-4f97-a73b-4c049be30973" />

Core Components
1. User Interface Layer
Header: Navigation and branding
FileUpload: Drag-and-drop or browse file selection
MediaPreview: Displays uploaded media content
ResultCard: Shows detection results with confidence metrics
Dashboard: Main layout with responsive grid
2. State Management
React Hooks: useState, useEffect for component state
TanStack Query: Server state management for API calls
Context Providers: Theme, toast, and tooltip providers
3. Business Logic Layer
Detection Service:
Handles file processing simulation
Generates mock detection results
Manages processing delays
Calculates confidence scores
4. Data Flow
User uploads media file via FileUpload
File is passed to detection service in Index
Detection service simulates analysis in detection-service.ts
Results are displayed in ResultCard
Media preview updates in MediaPreview
Key Features
Responsive Design: Mobile-first approach with Tailwind CSS
Component-Based Architecture: Reusable, modular components
Mock Detection Service: Simulates deepfake analysis
Real-time Feedback: Processing states and notifications
Accessibility: Proper labeling and keyboard navigation
Development Workflow
Development Server: bun run dev (runs on port 8081)
Production Build: bun run build
Code Linting: bun run lint
This architecture separates concerns effectively, making the application maintainable and scalable for future enhancements such as integrating with actual deepfake detection APIs.



Prerequisites
Make sure you have Node.js installed (version 16 or higher)
Install Bun globally: npm install -g bun
Commands to Run the Project
1. Navigate to the project directory:
bash
cd c:\Users\volet\OneDrive\Desktop\Deep-Fake-Detection-System--main\Deep-Fake-Detection-System--main
2. Install dependencies:
bash
bun install
3. Start the development server:
bash
bun run dev
Alternatively, you can also use npm:
bash
npm install
npm run dev
4. Access the application:
Once the server starts, you can access the application at:
Local URL: http://localhost:8081/
Network URL: http://your-network-ip:8081/
Other Available Commands:
Build for production: bun run build or npm run build
Preview production build: bun run preview or npm run preview
Lint code: bun run lint or npm run lint
The development server will automatically reload when you make changes to the code. Port 8081 is used because port 8080 was already in use on your system.




🧩 Usage

Upload an image or video using the upload interface.

The system processes the file using ResNeXt + LSTM models.

View the confidence score and side-by-side media preview to assess authenticity.

Download or save the detection report for verification.

🤝 Contributing

We welcome contributions from the community!

Fork the repository and create a new branch for your feature or fix.

Ensure code readability and follow standard ESLint/Prettier conventions.

Submit a pull request with a clear description of your changes.

📜 License

This project is released under the MIT License.
You are free to use, modify, and distribute this software for educational or research purposes, provided that proper credit is given to the original authors.

## Contact

contact voletyvijay@gmail.com for information or links to relevant resources.
