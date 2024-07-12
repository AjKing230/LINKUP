# LinkUp

LinkUp is a social media web application built with MERN stack (MongoDB, Express.js, React.js, Node.js) and Redux Toolkit. It allows users to connect with friends, share posts, and manage their profiles.

## Features

- **User Authentication**: Register and login securely using JWT tokens.
- **Profile Management**: Upload profile pictures.
- **Friend Connections**: Add and manage friends.
- **Post Sharing**: Create posts.
- **Responsive Design**: Mobile-friendly interface using Material-UI with dark mode support.

## Technologies Used

- **Frontend**:
  - React.js
  - Redux Toolkit
  - Material-UI
  - React Router
  - React Dropzone for file uploads

- **Backend**:
  - Node.js
  - Express.js
  - MongoDB (via Mongoose)
  - JWT for authentication


## Getting Started

To get a local copy up and running follow these simple steps.

### Prerequisites

- Node.js installed on your machine
- MongoDB Atlas account (or local MongoDB installation)

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/AjKing230/LINKUP.git
   cd linkup
2. **Install dependencies**:
```bash
npm install

3. **Set up environment variables**:
   - Create a `.env` file in the root directory.
   - Add environment variables for frontend and backend configurations.
4. **Start the development server**:
   ```bash
   npm start
5. **Run the backend server**:
   ```bash
   npm run server
6. **Access the application**:
   - Open `http://localhost:3000` to view the frontend in the browser.
   - The backend server runs on `http://localhost:5000`.
