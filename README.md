# GDG25

GDG25 is a web application built using **Next.js (TypeScript)** and **Firebase**.  
The project follows a modular structure with reusable components, constants, and type definitions for easy scaling and maintenance.

---

## 🚀 Features

- Built with **Next.js + TypeScript**  
- **Firebase** integration (Auth, Database, Storage, etc.)  
- Organized folder structure (components, lib, constants, types)  
- Easy to extend and maintain  
- Ready for deployment  

---

## 🛠 Tech Stack

- **Frontend:** Next.js, React, TypeScript  
- **Backend / Services:** Firebase  
- **Styling:** CSS (custom or framework if added)  
- **Linting & Config:** ESLint, TypeScript, Next.js  

---

## 📂 Project Structure

/GDG25
├── app/ # Next.js app directory
├── components/ # Reusable UI components
├── constants/ # Project-wide constants
├── firebase/ # Firebase config & setup
├── lib/ # Utility/helper functions
├── public/ # Static assets (images, icons, etc.)
├── types/ # TypeScript type definitions
├── next.config.ts # Next.js configuration
├── tsconfig.json # TypeScript configuration
├── eslint.config.mjs # ESLint configuration
└── package.json # Dependencies & scripts


---

## ⚙️ Getting Started

### Prerequisites

- Node.js (>= 14.x recommended)  
- npm or yarn  
- Firebase project setup  

### Installation

# Clone the repository
git clone https://github.com/patel-heet/GDG25.git

# Navigate to the folder
cd GDG25

# Install dependencies
npm install
# or
yarn install

Environment Setup

Create a .env.local file in the root folder and add your Firebase config:

NEXT_PUBLIC_FIREBASE_API_KEY=your_api_key
NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN=your_project.firebaseapp.com
NEXT_PUBLIC_FIREBASE_PROJECT_ID=your_project_id
NEXT_PUBLIC_FIREBASE_STORAGE_BUCKET=your_project.appspot.com
NEXT_PUBLIC_FIREBASE_MESSAGING_SENDER_ID=your_sender_id
NEXT_PUBLIC_FIREBASE_APP_ID=your_app_id

Open http://localhost:3000
 in your browser.

Build & Start

npm run build
npm run start
