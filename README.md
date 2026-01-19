# Game Review Platform

A full-stack web application enabling community-driven reviews for video games across all distribution channels—official releases, indie titles, and popular mods.

**🔗 [Backend Repository](https://github.com/SamUnderscoreAsd/GameReviewWebAppBackEnd) | [Frontend Repository](https://github.com/SamUnderscoreAsd/GameReviewWebAppFrontEnd) | [The Website](https://gamereviewproject.up.railway.app/)**

## Overview

Most gaming review platforms focus exclusively on official releases, leaving a gap for the indie and modding communities. This project addresses that by providing a unified platform where users can discover and review any gaming experience, regardless of distribution method.

## Technical Implementation

**Tech Stack:** Node.js, MySQL, Docker, Tailwind CSS, Jest, Javascript, Next.js, Express.js, React

**Architecture & Features:**
* RESTful API with comprehensive endpoint structure for user authentication, review management, and content discovery
* Normalized relational database (3NF) designed to handle complex relationships between games, mods, and user-generated content
* Fully containerized with Docker, enabling consistent development environments across multiple machines and streamlined deployment
* Three-tier MVC architecture separating routing/controllers, business logic, and database interactions for maintainable code organization

**Key Technical Challenges Solved:**
* Designed flexible data model accommodating diverse game types (official releases, mods, indie games) while maintaining referential integrity
* Implemented authentication and authorization flow securing user data and review submissions
	* Applied secure coding practices including parameterized queries and input sanitization to prevent SQL injection vulnerabilities
* Established development workflow using Docker Compose for multi-service orchestration

## Development Roadmap

**Current Phase - Quality & User Experience:**
* Expanding test coverage from current baseline to 80% across backend services
* Redesigning frontend interface with improved navigation and responsive layouts
* Implementing email verification for enhanced account security

**Next Phase - DevOps & Automation:**
* Integrating CI/CD pipeline for automated testing and deployment
* Setting up staging environment for pre-production validation

## Motivation

This project combines my technical growth goals with addressing a real need in the gaming community. Building this platform has strengthened my full-stack development skills while creating something genuinely useful for gamers who explore beyond mainstream releases.

