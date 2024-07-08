# Student-Expert Chat Platform

## Project Overview
This project is a chat application where students can connect with college project experts in private chat rooms. It facilitates real-time communication between students and experts, providing a platform for students to seek guidance and advice on their projects.

## Technologies Used
- **Frontend:** Next.js, TypeScript, Tailwind CSS, HTML
- **Backend:** Node.js, Express.js, Socket.io
- **Database:** MongoDB
- **Hosting:** Vercel

## Features
- User login with username and password.
- Students can request to connect with an expert.
- Private chat rooms for each student-expert pair.
- Real-time messaging with timestamps and usernames.
- Chat history stored in MongoDB with retrieval of the last 10 messages upon entering the chat room.

## Demonstration Video
![Demonstration Video](https://github.com/Pranesh04092003/Chat-Application/blob/main/Demo%20Video.mp4)

## Code Structure
- **frontend/**: Contains the Next.js frontend code.
- **backend/**: Contains the Node.js backend code.
- **database/**: MongoDB setup and schema definitions.

## Challenges Faced
- Real-time communication setup with Socket.io.
- Ensuring secure storage of user data with encryption.
- Handling unique chat rooms for each student-expert pair.

I hosted the application on Vercel. Users need to sign up first, and by default, they are assigned the student role. Experts also start with the student role when they sign up, but the admin can change their role to experts. Students can select from available experts and send them private messages. Experts can see messages from students and reply to them, enabling real-time chat. The application uses Socket.io for real-time communication, and all sent messages have timestamps.

## How to Run
1. Clone the repository:
    ```bash
    git clone https://github.com/Pranesh04092003/Chat-Application.git
    ```
2. Install dependencies for both frontend and backend:
    ```bash
    # For backend
    cd backend
    npm install

    # For frontend
    cd frontend
    npm install
    ```
3. Start the backend server:
    ```bash
    cd backend
    npm start
    ```
4. Start the frontend application:
    ```bash
    cd frontend
    npm run dev
    ```
5. Access the application via the provided URL (typically `http://localhost:3000`).

## Contact
If you have any questions, feel free to reach out to **[praneshvijay2003@gmail.com](mailto:praneshvijay2003@gmail.com)**.
