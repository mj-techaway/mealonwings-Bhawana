
# MealOnWings

## Project Structure

- `backend/`: Contains the server-side code.
- `frontend/`: Contains the client-side code.
- `.gitignore`: Specifies files and directories to be ignored by Git.
- `README.md`: Project documentation.
- `package.json`: Project metadata and dependencies for the root.

## Prerequisites

- Node.js (v14.x or higher)
- npm (v6.x or higher) or yarn (v1.x or higher)
- MongoDB (Ensure it is running locally or provide a remote connection string)

## Getting Started

### Backend Setup

1. **Navigate to the backend directory:**
   ```sh
   cd backend
   ```

2. **Install backend dependencies:**
   ```sh
   npm install
   # or
   yarn install
   ```

3. **Configure the environment variables:**
   - Create a `.env` file in the `backend` directory with the following content:
     ```
  MONGO_URI = mongodb://0.0.0.0:27017/mealonwings


JWT_SECRET = 3Cc8oOehNoOehNxUcJDiBNUfGE


CLOUDINARY_CLOUD_NAME = drewchvth
CLOUDINARY_API_KEY = 174773262335467
CLOUDINARY_API_SECRET = 3Cc8oOehNxUcSzC2MSJDiBNUfGE

     ```

4. **Run the backend server:**
   ```sh
   npm start
   # or
   yarn start
   ```

   The backend server should now be running on `http://localhost:5000`.

### Frontend Setup

1. **Navigate to the frontend directory:**
   ```sh
   cd frontend
   ```

2. **Install frontend dependencies:**
   ```sh
   npm install
   # or
   yarn install
   ```

3. **Run the frontend development server:**
   ```sh
   npm start
   # or
   yarn start
   ```

   The frontend server should now be running on `http://localhost:3000`.

## Running the Application

1. Ensure MongoDB is running.
2. Start the backend server as described in the "Backend Setup" section.
3. Start the frontend server as described in the "Frontend Setup" section.
4. Open your browser and navigate to `http://localhost:3000` to access the website.

## Additional Scripts

- **Backend:**
  - `npm run dev` or `yarn dev`: Runs the backend server with hot-reloading for development.

- **Frontend:**
  - `npm run build` or `yarn build`: Builds the frontend application for production.
  - `npm test` or `yarn test`: Runs frontend tests.

## Project Dependencies

- **Backend:**
  - Express.js
  - Mongoose
  - Other middleware and utilities (see `backend/package.json`)

- **Frontend:**
  - React.js
  - Axios
  - React Router
  - Other utilities and components (see `frontend/package.json`)

## Contributing

1. Fork the repository.
2. Create a new feature branch (`git checkout -b feature/YourFeature`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/YourFeature`).
5. Open a Pull Request.



