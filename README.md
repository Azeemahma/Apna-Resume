# Apna Resume

Apna Resume is a modern AI-powered platform designed to help users create professional, job-winning resumes with ease. With its intuitive interface and secure backend, the application ensures a seamless experience from drafting to final download. Whether you’re a fresher or an experienced professional, Apna Resume refines your profile into a standout resume that gets noticed.


## Tech Stack

- **Frontend:** React.js, TailwindCSS, Redux Toolkit  
- **Backend:** Node.js, Express.js, Docker  
- **Database:** MongoDB  

## Demo



🌐 Live demo: [Apna Resume](https://apna-resume-1.onrender.com/)  


---
## Installation

To run Apna Resume locally, follow these steps:

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/Azeemahma/Apna-Resume.git
cd Apna-Resume
```

### 2️⃣ Create Environment Files  

Before proceeding, create the necessary environment files for **both frontend and backend**.

#### 🔹 Backend (`Backend/.env`)  

Create a `.env` file inside the `Backend/` directory and add the following:  

```plaintext
MONGODB_URI={Your MongoDB URI} # If using Docker: mongodb://mongodb:27017/ai-resume-builder
PORT=5001
JWT_SECRET_KEY={Your Secret Key} #example "secret"
JWT_SECRET_EXPIRES_IN="1d"
NODE_ENV=Dev
ALLOWED_SITE=http://localhost:5173
```

#### 🔹 Frontend (`Frontend/.env.local`)  

Create a `.env.local` file inside the `Frontend/` directory and add the following:  

```plaintext
VITE_GEMENI_API_KEY={Your Gemini API Key}
VITE_APP_URL=http://localhost:5001/
```

### 3️⃣ Choose a Setup Method  

Now, you can **choose** to set up the project **with or without Docker**.

---

### 🚀 Setup with Docker

1. Navigate to the backend directory:
    ```bash
    cd Backend/
    ```

2. Run the Docker Compose file:
    ```bash
    docker-compose up -d
    ```

3. Start the frontend server:
    ```bash
    cd ../Frontend/
    npm install
    npm run dev
    ```

---

### 🔧 Setup without Docker

#### **Frontend Setup**

1. Navigate to the frontend directory and install dependencies:
    ```bash
    cd Frontend/
    npm install
    ```

2. Start the frontend server:
    ```bash
    npm run dev
    ```

#### **Backend Setup**

1. Navigate to the backend directory and install dependencies:
    ```bash
    cd Backend/
    npm install
    ```

2. Start the backend server:
    ```bash
    npm run dev
    ```

---

## Features

### 1. 🔒 Secure User Authentication  
- Custom authentication with **bcrypt** password hashing  
- **JWT-based** session management  

![Sign In](./Screenshot/SignIn.png)  
![Sign Up](./Screenshot/SignUp.png)  

### 2. 🏠 User Dashboard  
- View and manage previous resume versions  

![User Dashboard](./Screenshot/Dashboard.png)  

### 3. 🎨 Customizable Templates  
- Choose from multiple resume templates  

![Template Customization](./Screenshot/apnatheme.png)  

### 4. 🤖 AI-Powered Suggestions  
- Smart resume content suggestions  

![AI Suggestions](./Screenshot/apnaaisuggestion.png)  

### 5. 🔍 Live Preview  
- See real-time resume updates  

![Live Preview](./Screenshot/apnalivepreview.png)  

### 6. 📄 Export Options  
- Download resumes in **PDF format**  

![Download & Share](./Screenshot/apnascreenshot.png)  

---


## Developers 👨‍💻👩‍💻

