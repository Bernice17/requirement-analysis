# requirement-analysis

# Requirement Analysis in Software Development

This repository contains the Requirement Analysis documentation for a Booking Management System.  
The goal is to analyze, gather, structure, and visualize system requirements by applying SDLC requirement analysis methods.

## What is Requirement Analysis?

Requirement Analysis is a crucial phase in the Software Development Lifecycle (SDLC) where the needs, expectations, and features of a proposed system are collected, analyzed, refined, and documented. It helps the development team understand what the system should do and how it should behave before development begins.

It serves as the foundation for system planning, design, implementation, and validation.

## Why is Requirement Analysis Important?

Requirement Analysis is important because:
1. **Ensures Clarity & Understanding**  
   It clearly defines what stakeholders expect, reducing misunderstandings.
2. **Prevents Scope Creep**  
   Establishes the project boundaries and avoids uncontrolled feature additions.
3. **Foundation for System Design & Development**  
   All design decisions depend on well-documented requirements.
4. **Improves Cost & Time Estimation**  
   Helps estimate resources, timelines, and development effort accurately.
5. **Ensures Quality Delivery**  
   Leads to a final product that meets user needs and expectations.

## Key Activities in Requirement Analysis

The requirement analysis phase includes five major activities:

- **Requirement Gathering** – collecting raw requirements from stakeholders using interviews, surveys, observation, document review, etc.
- **Requirement Elicitation** – refining and expanding requirements using brainstorming, prototyping, and focus groups.
- **Requirement Documentation** – recording requirements in clear structured documents like SRS, user stories, and use cases.
- **Requirement Analysis & Modeling** – prioritizing, evaluating feasibility, and visualizing data using diagrams.
- **Requirement Validation** – reviewing requirements with stakeholders to confirm accuracy and completeness.

## Types of Requirements

### 1. Functional Requirements
These describe what the system should do.

Examples:
- Users can search for available rooms/properties.
- Users can create an account and log in.
- System allows booking reservations.
- Admin can manage property listings.
- System sends booking confirmation notifications.

### 2. Non-functional Requirements
These define system quality attributes.

Examples:
- **Performance:** Pages should load within 2 seconds.
- **Security:** Passwords must be encrypted.
- **Scalability:** Should support 1000+ concurrent users.
- **Usability:** Interface must be easy to navigate.
- **Reliability:** System uptime should be at least 99.9%.

## Use Case Diagrams

A Use Case Diagram visually represents interactions between system users (actors) and system functionalities (use cases).

### Benefits:
- Clearly displays system scope and features.
- Enhances communication among developers and stakeholders.
- Helps identify all user interactions before development.

### Actors:
- Guest User
- Registered User
- Admin

### Example Use Cases:
- Search Property
- Create Account / Login
- Book Property
- Make Payment / Checkout
- View Booking History
- Manage Listings (Admin)

![Use Case Diagram](https://drive.google.com/file/d/1G-IuvycIY653u5ESwWBTPh0WcoRK1Onw/view?usp=sharing)
![Use Case Diagram](https://drive.google.com/file/d/1G-IuvycIY653u5ESwWBTPh0WcoRK1Onw/view?usp=sharing)

## Acceptance Criteria

Acceptance Criteria define the conditions a feature must meet to be approved and considered complete. They ensure that requirements are testable, measurable, and aligned with user/business expectations.

### Example – Checkout Feature for Booking System:

- User can select available dates.
- System displays booking summary and total cost.
- User can proceed to payment securely.
- Booking is confirmed only after payment.
- Confirmation email/SMS should be sent within 2 minutes.

