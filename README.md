# CoDev - A Realtime Editor

![screenshot](./screenshots/preview.png)

CoDev is a collaborative, real-time code editor where users can seamlessly code together. It provides a platform for multiple users to enter a room, share a unique room ID, and collaborate on code simultaneously.

## 🔮 Features

-   💻 Real-time collaboration on code editing across multiple files
-   🚀 Unique room generation with room ID for collaboration
-   🌈 Syntax highlighting for various file types with auto-language detection
-   💡 Auto suggestion based on programming language
-   ⏱️ Instant updates and synchronization of code changes across all files
-   📣 Notifications for user join and leave events
-   🎨 Multiple themes for personalized coding experience
-   🌍 Comprehensive language support for versatile programming
-   🔠 Option to change font size and font family
-   👥 User presence list of users currently in the collaboration session, including online/offline status indicators
-   📁 Open, edit, save, and delete file functionalities
-   💾 Option to download files edited within the collaboration session
-   💬 **Group chatting** allows users to communicate in real-time while working on code.

## 🚀 Live Preview

You can view the live preview of the project [here](https://co-dev-one.vercel.app/).

## 💻 Tech Stack

![JavaScript](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![React Router](https://img.shields.io/badge/React_Router-CA4245?style=for-the-badge&logo=react-router&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![NodeJS](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)
![ExpressJS](https://img.shields.io/badge/Express.js-404D59?style=for-the-badge)
![Socket io](https://img.shields.io/badge/Socket.io-ffffff?style=for-the-badge)
![Git](https://img.shields.io/badge/GIT-E44C30?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)


## ⚙️ Installation

1. **Fork this repository:** Click the Fork button located in the top-right corner of this page to fork the repository.
2. **Clone the repository:**
    ```bash
    git clone https://github.com/<your-username>/Code-Sync.git
    ```
3. **Set .env file:**
   Inside the client and server directory, create or edit the .env file and add the following line:  
   Frontend:

    ```bash
    VITE_BACKEND_URL=<your_server_url>
    ```

    Backend:

    ```bash
    PORT=3000
    ```

4. **Install dependencies:**
   Navigate to the frontend and backend directories separately and run:
    ```bash
     npm install
    ```
5. **Start the frontend and backend servers:**  
   Frontend:
    ```bash
    cd client
    npm run dev
    ```
    Backend:
    ```bash
    cd server
    npm run dev
    ```
6. **Access the application:**
   Open a browser and enter the following URL:
    ```bash
    http://localhost:5173/
    ```

## 🔮 Future Enhancements:
**1) Terminal Integration:**
   - Access a terminal within the editor to view code output, enhancing the development experience.

**2) Collaboration Tools:**
   - Introduce a whiteboard and video calling feature within the editor room, facilitating real-time communication and brainstorming.

**3) Autocompletion:**
   - Implement an autocompletion feature, inspired by Copilot, to assist developers with code suggestions and enhancements.

**4) GitHub Integration:**
   - Enable direct integration with GitHub, allowing seamless code pushing from the editor room without the need for external IDEs like VSCode.


## 📈 Roadmap

![screenshot](./screenshots/roadmap.jpeg)


## 🧾 License

This project is licensed under the [MIT License](LICENSE).
