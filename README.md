# Smart India Hackathon Workshop
# Date:26/3/2025
## Register Number:212223100019
## Name:KAVINRAJ S
## Problem Title
SIH 1653: Web based Selector-Applicant Simulation Software
## Problem Description
Background: Recruitment and Assessment Centre (RAC) under DRDO, Ministry of Defence carries out interviews for applications received against advertised vacancies and for promotion to next higher grade for scientific manpower inducted within DRDO. Description: The process of interviewing is a challenging task. An unbiased objective interviewing process helps identify the right talent. The basic process of an interview involves posing a set of questions by an interviewer and thereafter evaluating responses from candidates. Thus, the questions asked should be relevant and match the area/ expertise of the applicant and the responses should also be of relevance w.r.t. the question asked. Expected Solution: The proposed solution should provide experts as well as candidates a real life Board Room experience, starting with initial ice-breaking questions leading to in-depth techno-managerial (depending on the level of candidate) questions. It shall also be able to provide a quantifiable score for experts as well as the candidate for the relevancy of questions w.r.t. the area/ expertise of the applicant. Similarly, candidate responses should also be graded for relevancy w.r.t. the question asked, finally assisting in arriving at an overall score for the subject knowledge of the candidate and thus his/ her suitability against the advertised post.

## Problem Creater's Organization
Ministry of Defence

## Idea
1. Realistic Interview Simulation
Virtual Boardroom Setup: The software will replicate the feel of a physical interview environment through video conferencing or 3D virtual spaces.
Dynamic Interaction Flow: The interview will progress in stages, starting with ice-breaking questions and moving towards specialized technical/managerial discussions.
2. Intelligent Question Selection
A question bank categorized by topics, difficulty, and job role.
Questions dynamically chosen based on:
Candidate’s expertise (skills, qualifications, and job role).
Interview phase (ice-breaking vs. in-depth technical/managerial).
3. AI-Powered Response Evaluation
Use Natural Language Processing (NLP) to:
Analyze candidate responses for relevance, depth, and accuracy.
Provide a score or qualitative feedback for each response.
Gradual improvement of the system through machine learning, using real-world data to refine evaluation criteria.


## Proposed Solution / Architecture Diagram
![image](https://github.com/user-attachments/assets/85a8aa7b-ff61-4c39-8e34-f9da70634be0)



## Use Cases
1. Recruitment and Selection
Purpose: Streamline the recruitment process and make hiring decisions more objective.
Actors: HR teams, technical interviewers, candidates.
Workflow:
Candidates attend interviews virtually.
Interviewers use the AI-powered interface to ask relevant questions.
AI evaluates the responses and provides quantifiable scores.
Benefits:
Objective evaluation of candidates.
Reduces interviewer bias.
Scalable for large applicant pools.
2. Promotions and Internal Assessments
Purpose: Assess employees for suitability in higher roles or promotions.
Actors: Internal committees, managerial candidates.
Workflow:
Internal candidates are assessed for techno-managerial competencies.
The system provides performance scores based on pre-set criteria.
Benefits:
Ensures fairness in promotions.
Identifies skill gaps for internal employees.


## Technology Stack
1. Frontend Technologies
The frontend will focus on creating an intuitive and interactive user interface.

Framework:

React.js: A popular framework for building dynamic and responsive web interfaces.
Next.js (Optional): For server-side rendering and improved SEO if needed for public-facing components.
Styling:

Tailwind CSS: For a modern, clean, and responsive design.
Framer Motion: To add smooth animations and transitions.
Real-Time Features:

WebRTC: For real-time video conferencing between candidates and interviewers.
Socket.IO: For real-time chat and notifications during interviews.
2. Backend Technologies
The backend will manage user roles, workflows, data processing, and AI integration.

Framework:

Node.js with Express: For building fast and scalable REST APIs.
Django or Flask (Python): If AI/ML integration requires direct interaction with Python-based libraries.
Database:

PostgreSQL: A relational database for storing structured data like users, questions, and interview scores.
MongoDB: For semi-structured data like logs, AI model configurations, and response analytics.
Real-Time Communication:

Firebase Realtime Database or Redis: For handling live updates during interviews.
Authentication:

OAuth 2.0 or JWT (JSON Web Tokens): For secure and role-based authentication.


## Dependencies
1. Frontend Dependencies
These libraries and frameworks are essential for building an interactive and modern user interface.

Core Frameworks:

react: For building the user interface.
next: For server-side rendering and routing (optional but recommended for SEO).
Styling:

tailwindcss: For a responsive and modern design.
framer-motion: For smooth animations and transitions.
Real-Time Communication:

socket.io-client: For client-side real-time updates.
simple-peer or peerjs: For WebRTC-based video conferencing.
Utilities:

axios or fetch: For making HTTP requests to the backend.
react-query: For efficient data fetching and state management.
Testing:

jest and react-testing-library: For unit testing and integration testing.
cypress: For end-to-end testing.
2. Backend Dependencies
These libraries are required to handle the business logic, user authentication, AI integration, and database management.

Core Frameworks:

express: For building REST APIs with Node.js.
fastify (alternative): For faster API development.
Authentication:

jsonwebtoken: For handling JWT-based authentication.
bcrypt: For hashing user passwords.
passport: For OAuth and session-based authentication.
Real-Time Communication:

socket.io: For real-time updates during interviews.
AI and NLP:

openai or huggingface: For integrating pre-trained AI models.
spaCy or nltk: For text processing and natural language understanding.
scikit-learn: For building scoring algorithms.
Database Management:

pg: For connecting to PostgreSQL.
mongoose: For connecting to MongoDB (if using a NoSQL database).
Utilities:

dotenv: For managing environment variables.
multer: For handling file uploads (e.g., storing video recordings).
Testing:

mocha, chai, and supertest: For backend testing.

