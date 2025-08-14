# GhibliGen - AI Art Generator

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Spring](https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)

An AI-powered art generator that creates beautiful, Ghibli-style artwork from text descriptions or existing images. This full-stack application uses React.js for the frontend and a powerful Spring Boot backend to connect with the Stability AI service.

---

### 🟢 Live Demo

**[https://ghibli-art-generator-ashen.vercel.app/](https://ghibli-art-generator-ashen.vercel.app/)**

**Note:** The live demo showcases the complete frontend UI and user experience. As the backend is not currently deployed, the AI generation features are inactive in this demo. To test the full functionality, please follow the local setup instructions below.

---



### ✨ Features

* **Text-to-Image Generation:** Describe a scene in detail and watch the AI bring it to life in the Ghibli art style.
* **Image-to-Image Transformation:** Upload an existing image and a prompt to reimagine it with Ghibli aesthetics.
* **Responsive Design:** A clean and fully responsive interface that works seamlessly on both desktop and mobile devices.
* **Modern UI/UX:** User-friendly navigation with separate tabs for each generation workflow.

---

### 🛠️ Tech Stack

| Frontend          | Backend                             |
| ----------------- | ----------------------------------- |
| React.js          | Spring Boot (Java)                  |
| Tailwind CSS      | Stability AI API                    |
| React Router      | FeignClient                         |
| Lucide React      | REST API                            |

---

### 🚀 Getting Started

To get a local copy up and running, follow these simple steps.

#### Prerequisites

* Node.js & npm (`v18` or later)
* Java JDK (`v17` or later)
* Maven

#### ⚙️ Backend Setup

1.  **Clone the repository:**
    ```sh
    git clone [https://github.com/VairagPatel/ghibli-art-generator.git](https://github.com/VairagPatel/ghibli-art-generator.git)
    cd ghibli-art-generator
    ```

2.  **Navigate to the backend directory:**
    ```sh
    cd backend
    ```

3.  **Set up your API Key:**
    * Go to the `src/main/resources` folder.
    * Open the `application.properties` file.
    * Add your Stability AI API key:
        ```properties
        stability.api.key=sk-YourSecretKeyGoesHere
        ```

4.  **Run the backend server:**
    ```sh
    ./mvnw spring-boot:run
    ```
    The backend will start on `http://localhost:8080`.

#### 🎨 Frontend Setup

1.  **Navigate to the frontend directory** (from the root folder):
    ```sh
    cd frontend
    ```

2.  **Install NPM packages:**
    ```sh
    npm install
    ```

3.  **Run the frontend development server:**
    ```sh
    npm run dev
    ```
    Open [http://localhost:5173](http://localhost:5173) in your browser to see the application.
