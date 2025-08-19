# 🤖 NovaAI – AI-Powered SaaS Platform  

✨ NovaAI is a cutting-edge 🤖 AI-powered SaaS platform built with the MERN stack + PostgreSQL 🗄️.
It delivers scalable 🚀, secure 🔐, and cloud-enabled ☁️ solutions for AI content generation 📝🤖.
Key features include role-based authentication 👥, cloud media storage 🗂️, and optimized PostgreSQL queries ⚡, ensuring seamless performance. 

🌐 **Live Demo**  
🔗 Live Site: http://nova-ai-lime-one.vercel.app/  

---

## 🖼️ Screenshots  

🚀 **Landing Page**  

![Landing Page](https://raw.githubusercontent.com/Nayasha2003/Nova-ai-public/ee2ec9ba17eaa4c4962a5d41dfdf725574c12873/NovaAI-Full-Stack/client/src/assets/1.png)


⚡ **Dashboard with AI Tools**  

![Dashboard](https://raw.githubusercontent.com/Nayasha2003/Nova-ai-public/ee2ec9ba17eaa4c4962a5d41dfdf725574c12873/NovaAI-Full-Stack/client/src/assets/2.png)


🔐 **Reviews**  

![Reviews](https://raw.githubusercontent.com/Nayasha2003/Nova-ai-public/ee2ec9ba17eaa4c4962a5d41dfdf725574c12873/NovaAI-Full-Stack/client/src/assets/3.png)

📂 **Subscription**  

![Media Upload](https://raw.githubusercontent.com/Nayasha2003/Nova-ai-public/ee2ec9ba17eaa4c4962a5d41dfdf725574c12873/NovaAI-Full-Stack/client/src/assets/4.png)

📂 **Login Page**  

![Login Page](https://raw.githubusercontent.com/Nayasha2003/Nova-ai-public/ee2ec9ba17eaa4c4962a5d41dfdf725574c12873/NovaAI-Full-Stack/client/src/assets/5.png)




---

## 💡 Features  

- 🔐 **Role-Based Authentication** (Clerk integration)  
- 🤖 **AI-Powered Content Generation** using OpenAI  
- 📂 **Cloudinary Integration** for media uploads  
- ⚡ **Optimized PostgreSQL queries** (30% faster data efficiency)  
- 📊 **Scalable SaaS architecture** with modular APIs  
- 🎨 Modern, responsive UI with TailwindCSS  
- 🐳 Dockerized for seamless deployment  

---

## 🛠 Tech Stack  

**Frontend:**  
- React.js  
- TailwindCSS  
- Axios  

**Backend:**  
- Node.js  
- Express.js  
- PostgreSQL  

**APIs & Services:**  
- OpenAI  
- Clerk (Authentication)  
- Cloudinary (Media storage)  

**Tools & Deployment:**  
- Docker  
- Vercel (Frontend)  
- AWS EC2 / Render (Backend optional)  
- Git & GitHub  

---

## 📦 Installation & Setup  

### 📥 Clone the Repository  
```bash
git clone https://github.com/Nayasha2003/Nova-ai-public.git
⚙️ Backend Setup

cd novaai-backend
npm install
Create a .env file in the backend root:


PORT=5000
DATABASE_URL=your_postgresql_connection_string
OPENAI_API_KEY=your_openai_api_key
CLERK_SECRET_KEY=your_clerk_secret_key
CLOUDINARY_API_KEY=your_cloudinary_api_key
Start the backend server:


npm start
🎨 Frontend Setup

cd ../novaai-frontend
npm install
Create a .env file in the frontend root:


VITE_BACKEND_URL=http://localhost:5000
VITE_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
Run the frontend dev server:


npm run dev
The frontend runs at http://localhost:5173.

🚀 Access the Application
Open http://localhost:5173 in your browser.

Register/Login with Clerk authentication.

Start generating AI-powered content.

✨ Key Highlights
🤖 AI-powered tools for smarter content creation

🔐 Secure, role-based authentication system

☁️ Cloud storage for seamless media handling

⚡ Optimized PostgreSQL queries for faster performance
