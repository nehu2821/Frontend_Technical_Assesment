🚀 VectorShift – Frontend Technical Assessment

A modern node-based workflow builder inspired by VectorShift’s core platform.
This project demonstrates clean frontend architecture, dynamic node abstraction, and seamless backend validation using a real-world pipeline/DAG model.

The goal was not just to recreate functionality, but to deliver a scalable, intuitive, and production-ready experience with a strong focus on usability and maintainability.

🌐 Live Demo & Resources

Frontend Live Site: https://vectorshift-task.vercel.app/

Code Repository: https://github.com/nehu2821/Frontend_Technical_Assesment

Demo Walkthrough Video: Add Video Link

✨ Project Highlights
🔗 Node-Based Workflow Builder

An interactive canvas that allows users to visually create and connect workflows using different node types—designed for clarity, flexibility, and performance.

🧩 Smart Node Abstraction

A reusable base node architecture enables:

Easy creation of new node types

Consistent behavior across nodes

Clean separation of logic and UI

Implemented node types include:

Input Nodes

Output Nodes

LLM Nodes

Text Nodes

Additional custom nodes to demonstrate extensibility

📝 Dynamic Text Node

One of the standout features of the project:

Automatically resizes based on content

Parses variables using {{ variable }} syntax

Dynamically generates input handles for each detected variable

Updates connections in real time

⚡ Real-Time Pipeline Validation

Integrated with a FastAPI backend to:

Validate Directed Acyclic Graph (DAG) structures

Detect invalid pipelines

Count nodes and edges

Provide clear, user-friendly validation feedback

🎨 Modern & Responsive UI

Built with a clean design system using:

Tailwind CSS for utility-first styling

shadcn/ui for accessible, reusable components

Smooth interactions powered by ReactFlow

🛠 Tech Stack
Frontend

React.js – Core UI framework

TypeScript – Type safety and maintainability

ReactFlow – Node-based workflow canvas

Tailwind CSS – Utility-first styling

shadcn/ui – Component library

React Context API – State management

Backend

FastAPI – Lightweight and high-performance backend

Python – Pipeline validation logic

DAG Algorithms – Graph validation and integrity checks

Deployment

Vercel – Frontend hosting

⚙️ Implementation Breakdown
1️⃣ Node Abstraction System

Designed a base node structure for shared functionality

Extended it to create specialized nodes

Demonstrated scalability by adding multiple custom node types

2️⃣ Advanced Text Node Logic

Regex-based variable parser

Dynamic handle generation

State-driven UI updates for seamless user interaction

3️⃣ Backend Validation Engine

Validates graph correctness

Prevents cyclic dependencies

Returns structured, readable validation results to the frontend

▶️ Getting Started
Prerequisites

Node.js v18+

Python 3.8+

npm or yarn

pip

uvicorn

🔧 Frontend Setup
git clone https://github.com/nehu2821/Frontend_Technical_Assesment
cd frontend
cp .env.example .env
npm install
npm start

🧠 Backend Setup
cd backend
pip install -r requirements.txt
uvicorn main:app --reload

🚧 Challenges & Solutions
🧩 Node Abstraction

Challenge: Balancing flexibility with maintainability
Solution: Introduced a base node class with specialized extensions

🔄 Dynamic Variable Handling

Challenge: Parsing variables and updating handles dynamically
Solution: Regex-based parsing combined with React state management

🔐 Pipeline Validation

Challenge: Ensuring correctness of complex node graphs
Solution: Implemented efficient DAG validation logic on the backend

⚡ Optimizations & Best Practices
Performance

Optimized ReactFlow rendering

Reduced unnecessary re-renders

Efficient state updates

Code Quality

Modular and reusable components

Clear separation of concerns

Consistent styling patterns

User Experience

Intuitive drag-and-drop interactions

Responsive design

Clear validation feedback

🎯 Final Outcome

This project successfully fulfills all assessment requirements while emphasizing clean architecture, scalability, and user experience.

Key Achievements:

✅ Robust and extensible node abstraction system

✅ Dynamic and intelligent Text Node implementation

✅ Seamless frontend–backend integration

✅ Real-time pipeline validation

✅ Modern, clean, and responsive UI
# Screenshots

![0](https://github.com/user-attachments/assets/ea8464d2-580f-4a19-a263-504f148d93c7)
![1](https://github.com/user-attachments/assets/30c1533d-6029-462b-a80f-4c679a640d2c)
![2](https://github.com/user-attachments/assets/3de071a6-b1f6-4d14-8a10-9bc084b62e23)
![3](https://github.com/user-attachments/assets/2239d747-ece2-453c-b696-68f283cc4551)
![4](https://github.com/user-attachments/assets/ca0cf29d-9c7c-48f0-82f2-832eba6c31e1)
![5](https://github.com/user-attachments/assets/5430c311-e2b7-46fb-8271-8167ce05db25)
