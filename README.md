# Trails

Welcome to the Trails repository! This project aims to centralize university resources and provide a seamless experience for students seeking information about the application process, academic planning, and campus life. The platform uses AI to ensure students receive accurate and timely answers to their questions.

## Overview

Trails is designed to revolutionize the university experience by bridging communication gaps between students, alumni, and university departments. Our platform fosters meaningful interactions and promotes a connected and engaged university community.

### Website

Check out the [Trails website](https://www.trailscommunity.com) to see the platform in action.

## Features

The following are the features I've specifically worked on, encompassing both the frontend and the backend SQL database which hosts the data.

### Landing Page

The landing page serves as the entry point to Trails. It provides an overview of the platform, its benefits, and how it can help students, alumni, and university departments. The design is user-friendly and aims to capture the essence of the university experience.

### Forum

The forum is the heart of Trails, where users can engage in discussions, ask questions, and share knowledge. It is designed to be an interactive and user-friendly platform where students and alumni can connect.

- **Thread Creation:** Users can create new discussion threads on various topics.
- **Commenting:** Users can comment on threads to provide answers or engage in discussions.
- **Upvoting/Downvoting:** Users can upvote or downvote threads and comments to highlight the most useful information.
- **Hot Ranking System:** Posts are ranked based on their popularity and engagement, with the hottest posts appearing at the top to ensure that the most relevant and trending discussions are easily accessible

### Direct Messaging (DM) System

The DM system allows users to have private conversations. This feature is crucial for one-on-one mentorship, networking, and personalized support.

- **One-on-One Chats:** Users can initiate private conversations.
- **Group Chats:** Users can create group chats for more collaborative discussions.
- **Notifications:** Users receive notifications for new messages.

### Community Page

The community page helps connect people they may find helpful. It is a central hub for students to find and engage with others who share their interests or can offer valuable insights and support.

- **User Profiles:** Detailed profiles to help users find and connect with like-minded individuals.
- **Networking Opportunities:** Facilitates connections between students, alumni, and professionals.

### Backend Database

The backend database is hosted on Azure PostgreSQL, which ensures data integrity and security. We also use Redis for caching and real-time updates, ensuring a smooth user experience.

- **User Data:** Stores information about users, their roles, and preferences.
- **Forum Data:** Manages discussion threads, comments, and votes.
- **Messaging Data:** Handles private and group chat messages.
- **Event and Group Data:** Maintains information about university events and student organizations.

## Technologies Used

### Frontend

- **Next.js:** A React framework for server-side rendering and generating static websites.
- **TypeScript:** A typed superset of JavaScript that helps catch errors early and ensures better code quality.
- **Redux:** A state management tool to manage the application's state in a predictable way.
- **Vercel:** A platform for frontend developers, providing hosting and serverless functions.

### Backend

- **Azure PostgreSQL:** A managed database service providing a scalable and secure database solution.
- **Redis:** An in-memory data structure store used for caching and real-time updates.
- **Prisma ORM:** An open-source database toolkit that simplifies database access with an auto-generated query builder for TypeScript and Node.js.


**Note:** The code for this project is private and confidential; thus, it cannot be shared. However, you can explore the live website for a detailed understanding of the functionality.
