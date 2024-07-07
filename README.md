<p align="center">
  <img src="explode.png" alt="Explode Logo" width="25%" height="auto">
</p>

# <p align="center">Explode Music Streaming Platform WebApp</p>


# [Looking for the EXPLODE-Server?](https://github.com/Explode-Media-Group/EXPLODE-Server/tree/main)

Explode is a federated music streaming platform that allows users to submit and stream music and podcasts. The platform includes an artist portal, user roles system, subscription system, and integrates with Stripe for payments. This repository includes both the frontend and backend components.




# Table of Contents 📖

- [Features](#features)
- [Federated Infrastructure](#federated-infrastructure)
- [Frontend](#frontend)
- [Installation Guide](#installation-guide)


## Features 🔔

- **Artist Portal**: Artists can submit music and podcasts with title, artist, album, description, image for album art, and tags.
- **User Roles System**: Manage different user roles such as admin, artist, and listener.
- **Subscription System**: Three subscription options with Stripe integration for payments.
- **Mobile Friendly**: Optimized for mobile devices.
- **Music Player**: Features play/pause button, share button, add to playlist button, and tip artist button using Stripe Connect API.




# Federated Infrastructure 👥

Explode is built with a federated infrastructure using ActivityPub, enabling decentralized and distributed networking. This ensures scalability, resilience, and interoperability with other federated services.

Here's how it works:

### Federated Networking

Federated networking in Explode allows for a distributed architecture where multiple servers (instances) can communicate and share data seamlessly. Each instance of Explode acts as a node in a network, capable of independently managing users, content, and interactions.

### ActivityPub Integration

ActivityPub is a protocol that Explode uses to achieve federated social networking capabilities. It enables instances of Explode to exchange messages and notifications in a standardized way, promoting interoperability and user engagement across different servers.

### Key Features of Federated Networking and ActivityPub in Explode

  1. *Decentralization:* Users can join any instance of Explode and interact with users on other instances seamlessly. This decentralization ensures resilience and reduces dependency on a single server.
  
  2. *Interoperability:* ActivityPub allows users on different federated platforms (not just Explode instances) to follow, share, and interact with content from Explode. This opens up possibilities for broader audience reach and community building.

  3. *Privacy and Control:* Users retain control over their data and interactions. They can choose which instances to join and have the flexibility to migrate their accounts without losing their data, fostering trust and user empowerment.

  4. *Scalability:* Federated networking and ActivityPub support scalability by distributing the load across multiple servers. This architecture adapts well to growing user bases and varying traffic patterns without compromising performance.


### Implementation in Explode

  - *Frontend:* The frontend, built with Svelte and SvelteKit, integrates features that allow users to seamlessly navigate between different instances while maintaining a cohesive user experience.





# Frontend 📱

The frontend of Explode is built using Svelte with SvelteKit for a fast and reactive user experience.

- **Express**
- **Svelte**: A modern, lightweight framework for building user interfaces.
- **SvelteKit**: A framework for building fast, server-rendered applications with Svelte.
- Framework: Svelte with SvelteKit
- UI Framework: Tailwind CSS for responsive design




# Installation Guide 🚧

Follow these steps to set up the Explode music streaming platform locally.


## Prerequisites

- svelte: Frontend framework
- svelte-kit: Full-stack application framework
- tailwindcss: Utility-first CSS framework
- axios: HTTP client for API requests
- stripe: Stripe API integration


### Clone the Repository

```
git clone https://github.com/yourusername/explode.git
cd explode
```

### Frontend Setup

1. Navigate to the frontend directory:

```
cd frontend
```

2. Install frontend dependencies:

```
npm install
```

3. Configure environment variables:
Create a .env file in the frontend directory with the following variables.

```
VITE_API_URL=http://localhost:3000
```

4. Start the frontend server:

```
npm run dev
```




# Running the Application 🏃‍♂️

Once both the backend and frontend servers are running, open your browser and navigate to http://localhost:3000 to access the Explode music streaming platform.




# Contributing ➕

We welcome contributions from the community. Please read our Contributing Guidelines for more details.




# License 🪪

This project is licensed under the MIT License. See the LICENSE file for details.




# Contact 🗨️

For any inquiries or support, please join [Explode's Discord Community](https://discord.gg/JqKeyyVXa2).
