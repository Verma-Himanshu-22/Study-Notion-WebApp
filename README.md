 # StudyNotion

StudyNotion is a fully functional ed-tech learning platform that enables users to create, consume, and rate educational content. The platform is built using the **MERN stack** (MongoDB, Express.js, React.js, Node.js), with features aimed at providing a seamless and interactive learning experience for students and instructors alike.

## Key Features

### For Students:
- **Homepage**: Introduction to the platform, with links to course lists and user details.
- **Course List**: View a list of available courses with descriptions and ratings.
- **Wishlist**: See courses you've added to your wishlist.
- **Cart Checkout**: Complete the course purchase checkout process.
- **Course Content**: Access course materials, including videos and documents.
- **User Details**: View and edit your account details.
- **Edit Details**: Update your personal account information.

### For Instructors:
- **Dashboard**: Overview of your courses, ratings, and feedback.
- **Insights**: Metrics on your course’s performance such as views and clicks.
- **Course Management**: Manage your courses (create, update, delete).
- **Profile Management**: Edit personal information and view account details.

### For Admin:
- **Admin Dashboard**: View a summary of all courses, instructors, and students.
- **Metrics Insights**: Understand platform-wide data including the number of users and revenue.
- **Instructor Management**: Administer instructor profiles, courses, and ratings.

## Back-end Features

- **User Authentication & Authorization**: Students and instructors can sign up, log in, and securely access their accounts.
- **OTP & Password Recovery**: A seamless OTP-based login process and password recovery functionality for extra security.
- **Course Management**: Instructors can manage their courses and media, while students can access, rate, and wishlist courses.
- **Razorpay Payment Integration**: Handle transactions for course enrollments via Razorpay.
- **Media Management via Cloudinary**: Store and manage course media content like images and videos.
- **Markdown Support**: Courses use Markdown format for easy content formatting and rendering.

## Demo

Check out the demo of the platform here:  
**[Demo Link – StudyNotion](https://study-notion-git-main-himanshu-sahus-projects.vercel.app/)**

## Technologies Used

- **Frontend**: React.js, TailwindCSS (for styling)
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: JWT (JSON Web Tokens)
- **Payment Processing**: Razorpay
- **Cloud Storage**: Cloudinary
- **Content Formatting**: Markdown

## Installation and Setup

To run this project locally, follow the steps below:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/HimanshuSahu-1/Study-Notion.git
    ```
   
2. **Install dependencies for both frontend and backend**:

    **Frontend**:
    ```bash
    cd frontend
    npm install
    ```

    **Backend**:
    ```bash
    cd backend
    npm install
    ```

3. **Start the Development Server**:

    - For the frontend:
    ```bash
    npm start
    ```

    - For the backend:
    ```bash
    npm run dev
    ```

4. Open your browser and navigate to [http://localhost:3000](http://localhost:3000) to view the frontend.
