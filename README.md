Full Stack Authentication

This is a full-stack authentication application built using Next.js, MongoDB, and JWT. The project demonstrates secure user authentication, including login, registration, password hashing, and session management.

Table of Contents
1. Tech Stack
2.Project Structure
3.Installation
4.Usage
5.Video Explanation

1. Tech Stack
- Frontend: Next.js, React
- Backend: Node.js, MongoDB, bcryptjs, JWT
- Styling: Tailwind CSS

2.Project Structure
Here is the file structure of the project:


├── assets

│   └── videos

│       └── your_video.mp4

├── components

│   └── Header.js

│   └── Navbar.js

├── models

│   └── UserModel.js

├── pages

│   └── api

│       └── users

│           ├── login

│           └── signup

├── public

├── styles

└── .gitignore


3.Installation

 1. Clone the repository:

``bash
git clone https://github.com/Smuktha/PRODIGY_FS_01.git
cd PRODIGY_FS_01
``

 2. Install dependencies:

`bash
npm install


 3. Set up environment variables:

Create a `.env` file in the root directory and add the following:

``env
MONGO_URI=mongodb+srv://<username>:<password>@yourcluster.mongodb.net/<dbname>?retryWrites=true&w=majority
TOKEN_SECRET=yourSecretKey
DOMAIN=http://localhost:3000


Replace `<username>`, `<password>`, and `<dbname>` with your MongoDB credentials.

 4. Run the development server:

`bash
npm run dev
``

This will start the application at `http://localhost:3000`.

4. Usage

- Signup: Users can create a new account by providing their username, email, and password.
- Login: After signup, users can log in using their credentials.
- Protected Routes: Certain routes, like the dashboard, are protected and require a valid session or token to access.

5.Video Explanation

Here is a video explaining how the project works:

[Watch Video](https://drive.google.com/file/d/1zO_1sh_khJUeTV2k793TeUdlLBM_L3mR/view?usp=sharing)

## Contributing

Feel free to fork this repository, make improvements, and create pull requests. Contributions are welcome!
