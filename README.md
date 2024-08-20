# Solutions Engineer Code Challege and Demo
## August 2024

# FusionAuth Code Challenge

Welcome to the FusionAuth Code Challenge! This challenge will help you familiarize yourself with FusionAuth by setting up a local instance and enhancing a basic application. Follow the instructions below to get started.

## Challenge Overview

### Action Item 1: Quickstart and Local Setup

**FusionAuth Quickstart**: 
   - Go through a [FusionAuth quickstart](https://fusionauth.io/docs/quickstarts/) in the language of your choice (choose from one of the **web application** options, not the 5-minute/mobile/SPA/API quickstarts).
   - Set up a local FusionAuth instance running on port 9011 with a basic application.

1. **Enhance the Application**:
   - Add a page in the app that allows a user to add additional data like a nickname, favorite snack, hobby, or any other data points.
   - Store these values in the `FusionAuth` `user.data` object.
_Hint: Use FusionAuth’s custom data fields and ensure proper validation and storage._

2. **Implement 2Factor Authentication**:
   - Implement Two-Factor Authentication using FusionAuth. Users should be able to enable or disable 2FA from their profile settings, and if enabled, they should be prompted for a second authentication factor on login.
_Hint: Explore FusionAuth’s multi-factor authentication features and integrate with an TOTP (Time Based One-Time Password) provider._

3. **Implement a Role-Based Access Control system.**
  - Create roles such as “Admin”, “Editor”, and “Viewer”, and restrict access to certain parts of your application based on the user’s role.
_Hint: Use FusionAuth’s role management and authorization features._

### Technical Demo Presentation

**Title:** Introduction to FusionAuth: Simplifying User Authentication

**Duration:** 15 Minutes

**Objective:** Showcase the key features and benefits of FusionAuth, demonstrating its ease of use and integration capabilities.

#### 1. Introduction (2 minutes)
- **Slide 1:** Welcome & Introduction
  - Brief introduction of the presenter.
  - Overview of the agenda.

#### 2. What is FusionAuth? (3 minutes)
- **Slide 2:** Overview of FusionAuth
  - Brief description of FusionAuth.
  - Key features and benefits.
- **Slide 3:** Use Cases
  - Common use cases and scenarios where FusionAuth is beneficial.

#### 3. Demo Setup (1 minute)
- **Slide 4:** Demo Environment
  - Explanation of the demo environment.
  - Brief overview of the application being integrated with FusionAuth.

#### 4. Live Demo (6 minutes)
- **Step 1:** Setting Up FusionAuth
  - Walkthrough of the installation process.
  - Configuration of the initial settings.
- **Step 2:** Creating Users and Roles
  - Demonstration of how to create users and assign roles.
- **Step 3:** Integrating FusionAuth with an Application
  - Show how to integrate FusionAuth with a sample application (e.g., a simple web app).
- **Step 4:** Authentication and Authorization
  - Demonstrate the login process and role-based access control.

#### 5. Q&A and Conclusion (3 minutes)
- Questions and Answers
  - Open the floor for any questions.
- Conclusion
  - Recap of the key points.
  - Provide additional resources and contact information.


### Scorecard

**Criteria for Evaluation:**

1. **Introduction and Clarity (20 points)**
   - Clear and engaging introduction.
   - Overview of the agenda.

2. **Content and Technical Depth (30 points)**
   - Comprehensive explanation of FusionAuth.
   - Explanation of key features and use cases.

3. **Demo Execution (30 points)**
   - Smooth and error-free demonstration.
   - Clear explanation of each step.
   - Demonstration of key features (user creation, role assignment, integration, etc.).

4. **Engagement and Interaction (10 points)**
   - Engagement with the audience.
   - Ability to answer questions effectively.

5. **Conclusion and Resources (10 points)**
   - Clear and concise conclusion.
   - Provision of additional resources.

### Alternative Software Suggestions

If you prefer a different software to demo, consider the following:

1. **Docker**
   - Demonstrate how to set up and run containers.
   - Showcase container orchestration with Docker Compose.

2. **Kubernetes**
   - Basic deployment of applications.
   - Demonstration of scaling and managing containers.

3. **Elastic Stack (ELK)**
   - Setting up Elasticsearch, Logstash, and Kibana.
   - Demonstrating log aggregation and visualization.

4. **Postman**
   - API testing and automation.
   - Creating and running API test collections.


---

Good luck with your code challenge! If you have any questions or need further assistance, feel free to contact Holly or Kahlil.

Happy coding! 🚀
