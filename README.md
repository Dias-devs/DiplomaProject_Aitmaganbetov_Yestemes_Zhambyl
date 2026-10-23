# Design and Evaluation of a Gamified Mobile Application for Basic Digital Literacy in Children Aged 6–10

## Project Overview
This diploma project aims to design and evaluate a gamified mobile application prototype that helps children aged 6–10 practise foundational digital-literacy skills through short interactive tasks, immediate feedback and progress tracking.

Diploma Project: Development of an Application for Enhancing Digital Skills in Primary School Students

The initial learning flow is: <br />
Select lesson => Complete task => Submit answer => Receive feedback => Save progress

## Problem Statement
Access to digital devices does not necessarily mean that children can use digital information safely and independently. The project explores how an age-appropriate mobile application can support basic digital literacy through structured activities and clear guidance.

## Research Questions
To what extent can children aged 6–10 independently complete basic digital-literacy tasks in a gamified mobile application prototype?

Our aim is to design a gamified mobile prototype for foundational digital literacy and evaluate independent completion of its learning tasks.

## Target Users
- Primary users: Children aged 6–10.
- Secondary users: Parents/guardians and teachers.
- Authorized administrators: Content management (may be excluded from the final implementation).

This application can be submitted to the public education sector to support the integration of digital literacy into primary school pupils.

## Expected Outcomes
- A mobile application prototype containing interactive digital-literacy learning tasks.
- Immediate feedback and hints to help learners understand their answers.
- A mechanism for recording and displaying learning progress.
- A set of functional tests and an evaluation plan.
- An assessment of task completion and usability, subject to appropriate permissions and participant access.

## Team Members
Member             | Main responsibilities
-------------------|------------------------------------------------------
Dulat Zhambyl      |Backend, APIs, database and progress persistence
Murat Aitmaganbetov|Flutter client structure, navigation and UI
Dias Yestemes      |Interactive tasks, feedback UI and functional testing

Supervisor: Aliya Dyusenbekovna Katyetova

## Project Scope
The initial MVP is planned to include:
1. Lesson and task selection.
2. Interactive multiple-choice or picture-selection activities.
3. Answer checking and immediate feedback.
4. Optional hints.
5. Attempt recording and progress retrieval.
6. Basic privacy and access-control requirements.

Open-ended chat, unrestricted web browsing, algorithmically varied/auto-generated exercises and advanced adaptive AI tutoring are outside the initial scope.

## Current Development Status

Current stage: Analysis, design, and pre-defense preparation.

&nbsp;&nbsp;The project proposal, preliminary literature review, existing-system comparison, technology comparison, initial requirements, and verification and evaluation plan have been drafted. <br />
&nbsp;&nbsp;The formal System Context, Use Case, and Component diagrams, visual prototype, and application implementation remain pending until completed and reviewed. <br />
&nbsp;&nbsp;No completed application, executed functional tests, or user-pilot results are claimed at this stage.

## Selected Technologies
Component            | Proposed technology | Purpose
---------------------|---------------------|----------------------------------------------------
Mobile application   |Flutter / Dart       |Cross-platform mobile interface
Backend              |Node.js / Express    |API and application logic
Database             |To be finalized      |Store learning content, attempts, and progress
Version control      |Git / GitHub         |Source code, documentation, and collaboration
Project management   |YouTrack             |Tasks, priorities, responsibilities, and milestones
Architecture diagrams|diagrams.net         |Editable system and architecture diagrams
UX prototyping       |Figma                |Mockups and interactive prototype

## Links
YouTrack Link: https://diasyestemes.youtrack.cloud/projects/DLM

### Documentation
- Project Proposal, Project Scope, Literature Review, Existing Systems Comparison, Technology Comparison, Requirements Specification, Architecture Decisions, Verification and Evaluation Plan: docs/
- Architecture Diagrams: diagrams/
- Prototype Materials: prototype/

## Setup, Execution, and Testing Instructions
Current status: Provisional. <br />
These instructions are examples based on the proposed Flutter/Dart and Node.js/Express stack and may change during final implementation.

### Prerequisites
- Git
- Flutter SDK and Dart
- Node.js and npm
- Android/iOS emulator or compatible mobile device

### Installation and Execution
Clone the repository: <br />
``git clone <repository-url>`` <br />
``cd digital-literacy-mobile-app``

Install dependencies: <br />
``cd mobile`` <br />
``flutter pub get`` <br />

``cd backend`` <br />
``npm install``

Run the application: <br />
``flutter run``

Start the backend separately using npm run dev when it is implemented and configured.

## Testing
Planned tests will cover application startup, navigation, answer evaluation, feedback, and progress tracking.

``flutter test``

Backend tests may be run using npm test once the relevant test scripts are available.

**Note:** These commands and directory names are illustrative and have not yet been verified. This section will be updated to match the final implementation, actual project structure, and tested commands.
