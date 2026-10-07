# ListoYA
<img width="1600" height="474" alt="app_image_all" src="https://github.com/user-attachments/assets/c3fc787d-5faf-45b8-9a89-e7b264242bdd" />

## Overview

ListoYA supports multiple account types with different interfaces, permissions, and user flows.

Users can:

 - Discover jobs, tasks, and services
 - Create and manage profiles
 - Publish and manage content
 - Interact with individuals and companies
 - Apply to opportunities and manage related activities

This case study highlights selected frontend areas I worked on during the development of ListoYA.

## Frontend Case Study — Mobile Job & Service Marketplace

A portfolio case study documenting selected frontend development work on ListoYA, a mobile marketplace designed to connect individuals, service providers, and companies through jobs, tasks, and services.

**Role:** Frontend Contributor  
**Project Type:** Team Project  
**Frontend Stack:** React Native · TypeScript · JavaScript · RESTful APIs · Expo  
**Development Tools:** Git · GitHub · Figma · Postman · VS Code

---
### Visual Preview
<img width="300" alt="ListoYA Login Screen" src="https://github.com/user-attachments/assets/4b273025-2418-49e2-9278-1a06b9f44a67" />
<img width="300" alt="ListoYa Home Screen" src="https://github.com/user-attachments/assets/0f5ed25a-df78-466b-960e-da1734024fd2" />


---

### My Contributions

This section focuses on selected frontend areas I worked on and can discuss in more technical detail.

### Role & Ownership Logic

Worked on conditional UI behavior based on:

 - Authenticated user
 - Account type
 - Content ownership
 - Content status
 - Application status

One example involved ensuring that editing actions were only available when the authenticated user owned the corresponding content.
```
Authenticated User
        +
Content Owner
        ↓
Ownership Check
        ↓
Available UI Actions
```
### REST API Integration

Worked on selected frontend flows that retrieve and update application data through RESTful APIs.

This included working with:

- Data fetching and updates
- Backend responses
- Loading states
- Error states
- Updating the interface after user actions
User Action
    ↓
Frontend Handler
    ↓
REST API Request
    ↓
Backend Response
    ↓
State / UI Update

# Reusable UI Components

Worked with reusable UI components for selected marketplace and profile interfaces, including:

-Service cards
-Profile interfaces
-Action buttons
-Status-based controls

This gave me practical experience working with component-based development, frontend state, conditional rendering, and shared UI behavior.

### Frontend UI & User Flows

Worked on selected frontend flows related to:

 - Authentication and onboarding
 - Persona / Empresa account experiences
 - Profiles
 - Jobs and tasks
 - Services
 - Marketplace interactions

## Problem

In Paraguay and many local markets, job and service opportunities are often shared through informal channels such as word of mouth, social media, or messaging apps. This makes it harder for companies to find suitable candidates and for individuals to discover reliable opportunities in one organized place.

## Solution

ListoYA provides a mobile-first platform where Persona and Empresa users can publish, discover, apply to, and manage jobs, tasks, services, and company-related opportunities.

### Development Experience

During the project, I worked with:

 - JavaScript and TypeScript
 - React Native and Expo
 - ES Module import / export
 - RESTful API integration
 - Component-based UI development
 - Git feature branches and commits
 - Pull / rebase workflows
 - Basic merge conflict resolution

### What I Learned

Working on ListoYA gave me hands-on experience with a larger frontend application involving interconnected user flows, reusable components, REST APIs, role-based interfaces, and team-based Git development.

I am continuing to strengthen my understanding of:

- JavaScript fundamentals
- ES Modules
- React concepts
- TypeScript
- REST API integration
- Modern web frontend development
