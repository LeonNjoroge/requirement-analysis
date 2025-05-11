# Requirement Analysis in Software Development.
Requirement Analysis Project focuses on crafting a comprehensive foundation for software development by documenting, analyzing, and structuring requirements

## What is Requirement Analysis?
Requirement Analysis is a crucial phase in the Software Development Life Cycle (SDLC) that involves gathering, analyzing, and documenting what a software system must do. It ensures a clear understanding between stakeholders and developers about the system’s goals and functionality.

### 🔍 Why It Matters
- Defines the scope of the project.
- Guides design and development by outlining what to build.
- Reduces rework and cost by identifying issues early.
- Improves communication among stakeholders.
- Supports accurate planning and resource allocation.

### 🛠 Types of Requirements
- Functional: What the system should do.
- Non-functional: How the system should perform.
- Business: High-level objectives.
- User: What users need from the system.

## Why is Requirement Analysis Important?
Requirement Analysis plays a vital role in the success of any software project. Here are three key reasons why it's critical in the Software Development Life Cycle (SDLC):

1. Prevents Costly Rework
   Identifying and clarifying requirements early helps avoid misunderstandings and scope changes later in the project. Fixing issues at later stages (like development or testing) is far more expensive than resolving them during analysis.

2. Ensures Stakeholder Alignment
   It creates a shared understanding among clients, users, and development teams. This alignment minimizes confusion, ensures expectations are met, and increases customer satisfaction.

3. Provides a Clear Project Roadmap
   Well-documented requirements act as a blueprint for the design, development, and testing phases. They guide the project team, help in accurate time and resource estimation, and keep the project on track.

## Key Activities in Requirement Analysis
Requirement Analysis involves several structured activities to ensure the software meets business and user needs. Below are the five key activities:

- Requirement Gathering
Collecting initial information from stakeholders, documents, and existing systems to understand high-level needs.

- Requirement Elicitation
Engaging stakeholders through interviews, surveys, workshops, or observation to extract detailed and specific requirements.

- Requirement Documentation
Recording the gathered and elicited requirements in a clear and organized format, such as a Software Requirements Specification (SRS).

- Requirement Analysis and Modeling
Analyzing requirements to identify gaps, overlaps, or conflicts and representing them through models like use cases, flowcharts, or UML diagrams for better clarity.

- Requirement Validation
Reviewing the documented and modeled requirements with stakeholders to ensure accuracy, feasibility, and alignment with business goals.

## Types of Requirements
Requirement types are generally categorized into two main groups: Functional Requirements and Non-functional Requirements. Below are definitions and practical examples based on a hotel booking system like Airbnb, Booking.com, or OYO.

### 1️⃣ Functional Requirements
Functional requirements describe what the system should do. These are specific behaviors or functions of the system.

Examples for a Booking Management Project:
- Hotel Listing Management: Hotel managers must be able to add, update, or remove hotel listings through a dedicated portal.
- Hotel Search and Filtering: Customers should be able to search for hotels using location, price, ratings, and availability.
- Hotel Booking: Users must be able to select a hotel, enter booking details, and confirm a reservation.
- Payment Integration: The system should integrate with third-party payment gateways for secure transactions.
- Notification System: Notifications should be sent to customers and hotel managers when bookings or cancellations occur.

### 2️⃣ Non-functional Requirements
Non-functional requirements define how the system performs its functions. These include performance, reliability, scalability, and more.

Examples for a Booking Management Project:
- Performance: The system should support high traffic with minimal latency during peak times (e.g., through Redis caching and CDN usage).
- Scalability: Services should be scalable using a microservice architecture to handle different modules independently (e.g., search, booking, hotel management).
- Availability: The system must be available 99.9% of the time, ensuring smooth operation without frequent downtimes.
- Security: All user data and transactions must be secured using encryption and secure APIs.
- Data Consistency & Reliability: Systems like Kafka and Cassandra should ensure data integrity, even under heavy loads or failures.

## Acceptance Criteria
Acceptance Criteria are a set of conditions that a software feature must meet to be accepted by stakeholders. They play a vital role in Requirement Analysis by clearly defining the scope, expectations, and testability of a feature.

### 🔍 Importance in Requirement Analysis
**Clarifies Requirements:** Translates vague requirements into actionable conditions.

**Aligns Stakeholders:** Ensures everyone—developers, testers, and product owners—share the same understanding of when a feature is "done."

**Enables Testability:** Serves as a foundation for writing test cases and validating features.

**Reduces Rework:** By setting clear expectations early, it prevents misinterpretation and minimizes future changes.

#### 🧾 Example: Acceptance Criteria for Checkout Feature
**Feature:** Hotel Booking Checkout

**Acceptance Criteria:**

    ✅ User must be able to review booking details before confirming.

    ✅ The checkout form must require valid payment details.

    ✅ The system should validate availability before finalizing the booking.

    ✅ A confirmation message must be displayed upon successful payment.

    ✅ A booking summary and receipt should be emailed to the user.

