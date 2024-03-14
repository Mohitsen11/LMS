# Learning Management System (LMS)

Learning Management System (LMS) is a full-stack MERN (MongoDB, Express.js, React.js, Node.js) project designed to provide a comprehensive platform for managing courses and user profiles.

## Features

- **Authentication and Authorization**: Secure user authentication and authorization with role-based access control.
- **Course Listing**: Display courses fetched from the backend via API calls, providing users with access to course details and descriptions.
- **Frontend Design**: Utilizes Daisy UI and Tailwind CSS to create an aesthetically pleasing and responsive frontend interface.
- **User Profile Functionality**: Enables users to perform CRUD (Create, Read, Update, Delete) operations on their profiles, including updating personal information and uploading profile images.
- **Admin Role**: Grants administrative privileges to create, update, and manage courses, as well as perform CRUD operations on user profiles.
- **Mailing Mechanism**: Implements a mailing mechanism for the "forgot password" functionality, ensuring seamless user experience and security.
- **Cloudinary Integration**: Utilizes Cloudinary for storing user profile images, providing efficient and reliable image storage and retrieval.
- **Password Hashing**: Uses bcrypt to securely hash user and admin passwords before storing them in MongoDB.
- **Course Subscription**: Enables users to subscribe and unsubscribe from courses, with smooth payment integration using Razorpay.

## Technologies Used

- **Frontend**: React.js, Daisy UI, Tailwind CSS
- **Backend**: Node.js, Express.js, MongoDB, Mongoose
- **Authentication**: JSON Web Tokens (JWT), bcrypt
- **Payment Integration**: Razorpay
- **Image Storage**: Cloudinary

## Getting Started

To get started with the Learning Management System (LMS), follow these steps:

1. Clone the repository: `git clone https://github.com/Mohitsen11/LMS.git`
2. Navigate to the project directory: `cd LMS`
3. Then navigate to the project directory: `cd lms/lms-backend`
4. Install dependencies: `npm install`
5. Start the backend server: `npm run dev`
6. Then do: `cd ..`
7. Then navigate to the project directory: `cd lms/lms-frontend`
8. Install dependencies: `npm install`
9. Start the frontend server: `npm run dev`
10. Click on the frontend server: `http://localhost:5173/`

## Contributing

Contributions to the Learning Management System (LMS) project are welcome! If you find any bugs or have suggestions for improvements, please open an issue or submit a pull request.
