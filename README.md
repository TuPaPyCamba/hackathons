# Hackathons 🚀

## Overview
**Hackathons** is a web platform designed to streamline the creation, management, and participant experience of virtual hackathons. By leveraging deep Discord integration, the platform automates community management, letting organizers focus on the event itself while providing participants with a frictionless onboarding experience. 

Users can log in directly with their Discord accounts, join events, and instantly gain access to the right servers, channels, and team roles—all managed automatically behind the scenes.

## ✨ Key Features
* **Discord OAuth Integration:** Seamless login and authentication using Discord.
* **Automated Server Management:** When a user joins a hackathon, they are automatically added to the designated Discord server.
* **Smart Channel Access:** Automatically provisions and restricts channel visibility based on event participation.
* **Team Role Provisioning:** For team-based hackathons, the platform automatically assigns and manages specific team roles within the Discord server.
* **Custom Event Creation:** Organizers can spin up new virtual events and customize the participant experience from a central dashboard.

## 🛠 Tech Stack
This project is built with a modern, scalable architecture:

* **Frontend:** Next.js (App Router), TypeScript
* **Backend:** Node.js
* **Infrastructure:** Docker (for containerized development and deployment)
* **Database:** *TBD* (Currently evaluating options like MongoDB or Supabase)

## 🚀 Getting Started

### Prerequisites
Before you begin, ensure you have the following installed on your local machine:
* [Node.js](https://nodejs.org/)
* [pnpm](https://pnpm.io/)
* [Docker](https://www.docker.com/)
* A Discord Developer Account (for OAuth and Bot configuration)

### Installation
1. **Clone the repository:**
   ```bash
   git clone [git@github.com:TuPaPyCamba/hackathons.git](git@github.com:TuPaPyCamba/hackathons.git)
   cd hackathons