# requirement-analysis
# 📋 Requirement Analysis

## ❓ What is Requirement Analysis?

**Requirement Analysis** is a vital phase in the **Software Development Life Cycle (SDLC)** where the team gathers, analyzes, and defines the functional and non-functional needs of the system. The goal is to ensure all stakeholders share a clear and unified understanding of what the software should do and how it should behave.

---

## 🧠 Why is Requirement Analysis Important?

- 🔍 **Clarity and Understanding:** Helps identify stakeholder expectations and reduces ambiguity.
- 📌 **Scope Definition:** Prevents scope creep by setting clear project boundaries.
- 🏗️ **Foundation for Design & Development:** Guides the design, development, and testing phases.
- 💰 **Cost & Time Estimation:** Supports accurate planning of resources, budget, and timeline.
- ✅ **Quality Assurance:** Ensures the final product aligns with stakeholder needs, increasing satisfaction.

---

## 🛠️ Key Activities in Requirement Analysis

### 1. Requirement Gathering 🗂️

- **Interviews:** One-on-one or group discussions with stakeholders.
- **Surveys & Questionnaires:** Collect feedback from a broader audience.
- **Workshops:** Collaborative sessions to explore needs and solutions.
- **Observation:** Monitoring users in their actual working environment.
- **Document Analysis:** Reviewing existing systems and documents.

### 2. Requirement Elicitation ✍️

- **Brainstorming:** Generating ideas from multiple stakeholders.
- **Focus Groups:** Structured discussions with key users.
- **Prototyping:** Developing mockups to refine and clarify requirements.

### 3. Requirement Documentation 📚

- **SRS (Software Requirements Specification):** Formal document listing all requirements.
- **User Stories:** Descriptions of features from the user's perspective.
- **Use Cases:** Diagrams showing system interactions with users.

### 4. Requirement Analysis & Modeling 📊

- **Prioritization:** Ranking requirements by business value and urgency.
- **Feasibility Analysis:** Assessing technical, time, and budget constraints.
- **Modeling Tools:** Creating diagrams like DFDs or ER diagrams for better visualization.

### 5. Requirement Validation ✅

- **Review & Approval:** Getting stakeholder sign-off on documented requirements.
- **Acceptance Criteria:** Setting clear conditions for feature completion.
- **Traceability:** Mapping each requirement to development and testing to ensure completeness.

---

## 🧾 Types of Requirements

### ⚙️ Functional Requirements

Describe **what the system should do**.

#### Examples:

- **Search Properties:** Filter by location, price, availability.
- **User Registration:** Create accounts and log in.
- **Property Listings:** View detailed property info with images.
- **Booking System:** Book, view, and manage reservations.
- **User Authentication:** Secure login and registration.

### 🛡️ Non-Functional Requirements

Describe **how the system should perform**.

#### Examples:

- **Performance:** Pages should load within 2 seconds for up to 1000 users.
- **Security:** Data encryption, secure login, protection from vulnerabilities.
- **Scalability:** Support for increased user load via horizontal scaling.
- **Usability:** Intuitive and user-friendly UI/UX.
- **Reliability:** 99.9% uptime and fast recovery from failures.

---

## 🎯 Use Case Diagrams

**Use Case Diagrams** are part of UML (Unified Modeling Language) used to show the interaction between actors and the system. They help visualize requirements, system scope, and user behavior.

### ✅ Benefits

- Clarifies system functionality and scope  
- Improves communication among stakeholders  
- Helps prioritize features  
- Guides development and testing  

### 🛏️ Use Case Diagram for Booking System (`alx-booking-uc`)

**Actors:**

- Guest  
- Host  
- Admin

**Use Cases:**

- Register/Login  
- Search Listings  
- View Property Details  
- Book Property  
- Manage Booking  
- List Property *(Host only)*  
- Edit/Delete Listing *(Host only)*  
- Approve Listing *(Admin only)*  

> *[Optional: Insert visual diagram here]*

---

## 📌 Acceptance Criteria

### 🎯 Objective

Define measurable conditions for feature completion and stakeholder approval.

### ✅ What is Acceptance Criteria?

A set of predefined rules a feature must meet to be considered complete and acceptable.

### ✍️ How to Define

- Be **specific** and **measurable**
- Include **functional** and **non-functional** aspects

### 📌 Example (Booking System)

> “Users should be able to select available dates, confirm booking, and receive a confirmation email within 2 minutes.”

### ✔️ Benefits

- Sets clear expectations  
- Acts as a foundation for testing  
- Ensures quality and alignment with user needs  
