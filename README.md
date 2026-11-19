# Closer — Making Connection Easier

**A human-centered social connection app designed to help people remember meaningful moments and reach out with intention.**

**Project status:** Interactive portfolio prototype · Full-stack application in development

**[View Live Demo](https://MrBejvan.github.io/Closer-Showcase/)**

## Overview

Closer is a mobile-first social connection application concept inspired by the challenges of maintaining relationships while managing ADHD.

Remembering birthdays, interviews, celebrations, and important personal milestones can require significant mental effort. Closer explores how thoughtful interface design, timely reminders, and context-aware message drafting can reduce that friction without replacing genuine human connection.

The goal is simple: **make it easier to show people you care.**

## Features

### Interactive prototype

- Calm, mobile-first interface with accessible design principles
- Combined dashboard for upcoming moments and social connections
- Event creation and management demonstration
- Friendship and connection interface
- Context-aware message drafting with editable text
- Warm, casual, and brief message styles
- Synthetic demonstration data

The public prototype runs entirely in the browser. It does not require an account, connect to a live database, or send messages.

### Full-stack application — In development

The application architecture uses:

- **Frontend:** Next.js, React, TypeScript
- **Backend and authentication:** Supabase
- **Database:** PostgreSQL
- **Security:** Row-level security, explicit sharing permissions, and threat modeling
- **Testing:** Synthetic data, automated security checks, and planned multi-account integration tests

Backend functionality and security controls are not yet fully verified or approved for real-user deployment.

## Design Philosophy

Closer is guided by four principles:

**Low cognitive friction:** Minimize unnecessary decisions, overwhelming interfaces, and repetitive steps.

**Human control:** AI-assisted communication should support personal expression, not replace it. Users review and edit messages before sending.

**Privacy by default:** Personal events should only be visible to explicitly authorized users.

**Accessible interaction:** Prioritize readable typography, clear navigation, keyboard accessibility, and adaptable notification preferences.

## Technical Architecture

The planned application separates the user interface, authenticated application logic, relational database, and future notification and AI services.

Security-sensitive operations are designed around server-side authorization and database access policies rather than relying solely on client-side checks.

The public portfolio demonstration is intentionally separate from the unfinished application backend.

## Security and Responsible Development

Closer is intended to handle personal information, making privacy and security central to the development process.

Current engineering work includes:

- Threat modeling and risk assessment
- Explicit event-sharing permissions
- Database authorization policies
- User-blocking and relationship-revocation logic
- Synthetic multi-user testing infrastructure
- Transactional event-creation design

**Security status:** These controls require further integration testing and review. The public demo does not collect or store real personal information.

## Roadmap

- [x] Define product concept and user journeys
- [x] Create interactive mobile-first prototype
- [x] Design initial application architecture
- [x] Implement initial application source and database migrations
- [x] Establish threat model and synthetic test fixtures
- [ ] Verify full application build and database authorization
- [ ] Complete security and abuse-prevention controls
- [ ] Implement operational reminders and notification preferences
- [ ] Integrate privacy-conscious AI message drafting
- [ ] Conduct accessibility and usability testing
- [ ] Prepare a controlled adult-user pilot

## Running the Public Prototype

This repository contains a static HTML demonstration.

1. Download or clone the repository.
2. Open `index.html` in a browser.
3. Select the interactive prototype from the portfolio page.

No API keys, dependencies, or backend services are required.

## Project Context

Closer is an independent project exploring the intersection of software engineering, human-centered design, accessibility, and responsible AI.

It is being developed iteratively, with an emphasis on documenting architectural decisions, identifying weaknesses, and validating security before collecting real user information.

## License

Unless otherwise indicated, original project code and design are not offered under an open-source license. All rights are reserved by their respective copyright holders.

Third-party components and assets remain subject to their respective licenses.

The public demonstration is provided for portfolio evaluation and is not a production service.
