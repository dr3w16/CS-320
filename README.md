# CS-320
1. Ensuring Code, Program, or Software is Functional and Secure

Functionality

Unit Testing: Write automated tests (JUnit, pytest, etc.) to check whether each function or method works as intended.

Integration Testing: Validate how different components interact. Example: testing login + database interaction.

System Testing: Run the program end-to-end to confirm it meets requirements.

User Acceptance Testing (UAT): Have real users test the program to ensure it solves their problem.

Security

Input Validation: Always sanitize and validate user inputs to prevent SQL injection, XSS, or buffer overflows.

Authentication & Authorization: Enforce strong password policies and role-based access control.

Encryption: Use HTTPS, encrypt sensitive data at rest and in transit.

Dependency Management: Keep third-party libraries updated to avoid known vulnerabilities.

Static & Dynamic Analysis Tools: Use tools like SonarQube, OWASP ZAP, or Bandit to catch security flaws.

Example: If building a registration form, don’t just test that it accepts valid input—also test what happens if a user tries to submit HTML tags, overly long text, or malicious scripts.

2. Interpreting User Needs and Incorporating Them into a Program

Gather Requirements: Use interviews, surveys, or user stories (e.g., “As a user, I want to reset my password so that I can recover my account.”).

Create Use Cases: Define step-by-step how users will interact with the system.

Prototyping: Develop mockups or wireframes to show users what the program will look like.

Iterative Feedback: Share early builds with users and refine based on their feedback.

Prioritize Needs: Use frameworks like MoSCoW (Must-have, Should-have, Could-have, Won’t-have) to balance features and timelines.

Example: If users say they want a “fast login,” that could mean reducing login steps, enabling social sign-in, or making authentication faster. Asking clarifying questions helps translate vague needs into actionable requirements.

3. Approaching Software Design

Define the Problem Clearly: Understand what the software should do before designing how it will do it.

Choose a Methodology: Agile (iterative, flexible) vs. Waterfall (structured, sequential) depending on project type.

Use Design Principles:

Modularity: Break down software into small, reusable components.

Separation of Concerns: Keep business logic, data, and UI separate (e.g., MVC pattern).

Scalability: Design for future growth in users, data, or functionality.

Security by Design: Bake in authentication, validation, and encryption from the start.

Create Models: Use UML diagrams, flowcharts, or entity-relationship diagrams to visualize structure.

Prototype & Iterate: Start with a minimal viable product (MVP) and build upon it.

Example: If designing a banking app, start with core features (balance check, transaction history), design secure login flow, and later expand to extras like notifications or budgeting tools.

In short:

You ensure functionality and security with systematic testing and secure coding practices.

You interpret user needs through requirement gathering, user stories, and continuous feedback.

You design software using modular, scalable, and secure principles, supported by diagrams and iterative development.
