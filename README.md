# Notes Manager
This project demonstrates the implementation of CRUD (Create, Read, Update, Delete) operations using React.js and Axios.
It’s a simple yet effective example to understand how to connect a React frontend with an API, manage state and handle data dynamically.

### Features
- Create new records using POST request.
- Fetch and display data dynamically using GET request.
- Update existing records using PUT request.
- Delete records using DELETE request.
- Fully responsive and interactive UI.
- Clean and reusable React components.

### Tech Stack
- React.js (Frontend Library)
- Axios (HTTP Client for API Calls)
- JavaScript (ES6+)
- HTML5 & CSS3
- Vite (for fast build and development)

### Installation & Setup
Follow these steps to run the project locally:

Clone the repository
git clone: https://github.com/Chahal-Yashika/CRUD_AXIOS

Navigate into the project folder:
cd axios_project

Install dependencies:
npm install

Start the development server:
npm run dev

The application will run at: http://localhost:5173

### API Integration (Axios)
The project uses Axios for all CRUD operations:

import axios from "axios";

export const getPost = () => axios.get("https://jsonplaceholder.typicode.com/posts");

Each operation (GET, POST, PUT, DELETE) is managed through clean, separate functions inside the Postapi.js file.

### Preview
<p align="center">
  <img src="https://github.com/user-attachments/assets/416fe96e-4ae5-4a0d-b991-a2ffe36aea46" width="800" alt="CRUD Project Preview" />
</p>

### Deployment
The live version of the project is available at:https://axiospro.netlify.app/

### Learnings
Through this project, I learned:
- How to integrate Axios with React components.
- Managing data flow between frontend and API.
- Handling state updates efficiently.
- Structuring a React app with clean reusable components.







