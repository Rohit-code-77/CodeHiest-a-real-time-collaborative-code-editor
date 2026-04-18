# CodeHiest

A real-time collaborative code editor built to allow multiple users to write and share code simultaneously in shared rooms.

## Features

- **Real-Time Collaboration**: Multiple users can join the same room and edit code simultaneously without noticeable latency.
- **Syntax Highlighting**: Supports rich text editing with syntax highlighting using CodeMirror.
- **Unique Rooms**: Users can generate unique room IDs to create private sessions and invite others to collaborate.
- **Instant Updates**: Changes made by one user are instantly reflected on all connected clients' screens.
- **User Presence**: Real-time tracking of clients joining and leaving a room.

## Tech Stack

This project is built using the following technologies:

- **React**: Frontend library for building the interactive user interface.
- **Node.js & Express.js**: Backend environment and web framework handling the server and API routing.
- **Socket.IO**: Enables real-time, bidirectional, and event-based communication between the web clients and the server.
- **CodeMirror**: A versatile text editor component for the web, providing the core code editing experience and syntax highlighting.
- **uuid**: Used to generate secure, unique identifiers for collaboration rooms.

## Getting Started

1. Clone the repository.
2. Run `npm install` to install dependencies.
3. Run `npm start` to start the React development server.

## Ownership

**Rohit Kadian**  
Email: [rohitkadian8689@gmail.com](mailto:rohitkadian8689@gmail.com)
