# PassOP - Your Own Password Manager

PassOP is a simple, full-stack password manager built with React, Express, and MongoDB. It allows you to securely store, manage, and copy your passwords for different websites.

## Features

- Add, edit, and delete passwords for any website
- Copy site, username, or password to clipboard with one click
- All data stored securely in MongoDB
- Responsive UI built with React and Tailwind CSS
- Toast notifications for user feedback
- Modern, clean design

## Project Structure

Passop-Mongo/ │ ├── Backend/ # Express + MongoDB backend │ ├── .env # Environment variables (Mongo URI, DB name) │ ├── package.json │ └── server.js # Express server │ ├── public/ # Static assets (icons, images) │ ├── src/ # React frontend │ ├── App.jsx │ ├── main.jsx │ ├── index.css │ ├── App.css │ └── components/ │ ├── Footer.jsx │ ├── Manager.jsx │ └── Navbar.jsx │ ├── index.html ├── package.json ├── tailwind.config.js ├── vite.config.js └── README.md

## Getting Started

### Prerequisites

- Node.js & npm
- MongoDB running locally or remotely

### Backend Setup

1. Go to the `Backend` directory:
   ```sh
   cd Backend
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Create a `.env` file with your MongoDB URI and database name:
   ```
   MONGO_URI=mongodb://localhost:27017
   DB_NAME=passop
   ```
4. Start the backend server:
   ```sh
   node [server.js](http://_vscodecontentref_/14)
   ```
   The backend will run on [http://localhost:3000](http://localhost:3000).

### Frontend Setup

1. Go back to the root directory:
   ```sh
   cd ..
   ```
2. Install frontend dependencies:
   ```sh
   npm install
   ```
3. Start the development server:
   ```sh
   npm run dev
   ```
   The app will be available at [http://localhost:5173](http://localhost:5173) (default Vite port).

## Usage

- Use the form to add a new password (site, username, password).
- Click the copy icon to copy any field to your clipboard.
- Edit or delete passwords using the action icons.
- All changes are synced with your MongoDB database.

## Credits

- [React](https://react.dev/)
- [Express](https://expressjs.com/)
- [MongoDB](https://www.mongodb.com/)
- [Tailwind CSS](https://tailwindcss.com/)
- [react-toastify](https://fkhadra.github.io/react-toastify/)
- [Lordicon](https://lordicon.com/) for animated icons

## License

This project is licensed under the MIT License.

---

Created with ❤️ by Abhay_Rajput
