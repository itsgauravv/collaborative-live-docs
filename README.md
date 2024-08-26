# Collaborative Live Docs Web App

<img width="1440" alt="ss1" src="https://github.com/user-attachments/assets/09681239-81c5-4665-a4c5-b70c11cfc1d3"> 

## Overview

This is a Collaborative Live Docs Web App that enables real-time collaboration on documents. The app provides a seamless user experience with features like user authentication, document editing, and live collaboration. Built with modern web technologies, this app is designed to be scalable, secure, and user-friendly.

## Features

- **User Authentication:** Secure sign-in and sign-up powered by [Clerk](https://clerk.dev).
- **Real-Time Collaboration:** Live document editing using [Liveblocks](https://liveblocks.io) for synchronized user interactions.
- **Document Management:** 
  - Create, edit, and delete documents with ease.
  - Invite users and assign view/edit permissions.
  - Lexical editor for endless document customization.
- **Commenting & Mentions:**
  - Add comments to the entire document or specific sections.
  - Mention other users and track mentions via a notification panel.
- **Notification System:** Stay updated with mentions and changes in the documents.
- **Modern UI/UX:** Styled with [Tailwind CSS](https://tailwindcss.com) and [Shadcn](https://shadcn.dev) for a sleek and responsive interface.
- **Error Tracking:** Integrated with [Sentry.io](https://sentry.io) for monitoring and fixing issues.
- **Deployment:** Hosted on [Vercel](https://vercel.com) with TypeScript support for robust development.

## Tech Stack

- **Frontend:** [Next.js](https://nextjs.org), [TypeScript](https://www.typescriptlang.org), [Tailwind CSS](https://tailwindcss.com), [Shadcn](https://shadcn.dev)
- **Authentication:** [Clerk](https://clerk.dev)
- **Real-Time Collaboration:** [Liveblocks](https://liveblocks.io)
- **Error Monitoring:** [Sentry.io](https://sentry.io)
- **Deployment:** [Vercel](https://vercel.com)

## Getting Started

### Prerequisites

- Node.js (>= 14.x)
- Yarn or npm

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/collaborative-live-docs.git
   cd collaborative-live-docs
   ```


2. **Install dependencies:**


   ```bash
   yarn install
   # or
   npm install
   ```


3. **Set up environment variables:**

   ```bash
   yarn dev
   # or
   npm run dev
   ```


## Development

To deploy this project, push your code to a GitHub repository and connect it to Vercel for continuous deployment.

## Contribution

Contributions are welcome! Please fork the repository and submit a pull request for any feature requests, bug fixes, or enhancements.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.



