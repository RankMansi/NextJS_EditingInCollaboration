This project is a collaborative LiveDocs clone built with Next.js, Liveblocks, and TailwindCSS, providing a real-time collaborative text editor similar to Google Docs. Key features include user authentication, document management, real-time editing, comments, and notifications. It’s designed for learning with visual instructions, making it beginner-friendly and ideal for hands-on practice in a live environment.

Follow these steps to set up the project locally on your machine.

Prerequisites

Make sure you have the following installed on your machine:

Git
Node.js
npm (Node Package Manager)
Cloning the Repository

git clone https://github.com/RankMansi/NextJS_EditingInCollaboration.git
cd collaborative-editor
Installation

Install the project dependencies using npm:

npm install
Set Up Environment Variables

Create a new file named .env in the root of your project and add the following content:

#Clerk
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up

#Liveblocks
NEXT_PUBLIC_LIVEBLOCKS_PUBLIC_KEY=
LIVEBLOCKS_SECRET_KEY=
Replace the placeholder values with your actual Clerk & LiveBlocks credentials. You can obtain these credentials by signing up on the Clerk and Liveblocks website.

Running the Project

npm run dev
Open http://localhost:3000 in your browser to view the project.
