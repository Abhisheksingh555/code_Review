# 🚀 Smart Code Reviewer  

**Smart Code Reviewer** is a sleek, modern web app featuring a live **multi-language code editor** with an integrated **AI-powered review panel**.  
It helps developers **analyze, debug, and optimize** their code in real time — providing **instant feedback**, **syntax highlighting**, and **intelligent suggestions** for writing cleaner, faster, and more efficient code.  

---

## 🌐 Live Demo  
👉 **Try it here:** [Smart Code Reviewer](https://jocular-gumption-354525.netlify.app/)  

---

## 🧠 Key Features  

- ⚡ **Live Code Editing**  
  Write, edit, and test code in real time with smooth and responsive syntax highlighting.  

- 🤖 **AI-Powered Code Reviews**  
  Submit your code and get instant, detailed feedback including:  
  - ❌ What’s wrong in your code  
  - 🧩 Why it’s wrong  
  - 💡 How to fix or optimize it  

- 🎨 **Modern & Responsive UI**  
  Clean, distraction-free design that adapts perfectly across devices.  

- 🔍 **Syntax Highlighting**  
  Powered by **PrismJS** and **highlight.js** for elegant and consistent code visuals.  

- 💬 **Instant Smart Suggestions**  
  AI recommends code improvements for better performance and readability.  

---

## 🖼️ Preview  

### 🧩 Code Editor  
![Code Editor Preview](https://github.com/Abhisheksingh555/code_review/blob/main/preview_01.png)  

### 🤖 AI Review Panel  
![AI Review Panel Preview](https://github.com/Abhisheksingh555/code_review/blob/main/preview_02.png)  

---

## 🛠️ Tech Stack  

| Layer | Technology |
|-------|-------------|
| **Frontend** | React (Vite) |
| **Styling** | Tailwind CSS |
| **Code Editor** | react-simple-code-editor + PrismJS |
| **Syntax Highlighting** | highlight.js |
| **AI Integration** | Axios + Backend API |
| **Deployment** | Netlify |

---

## ⚙️ Setup Instructions  

```bash
# 1️⃣ Clone the repository
git clone https://github.com/Abhisheksingh555/code_review.git

# 2️⃣ Navigate to the project directory
cd code_review

# 3️⃣ Install dependencies
npm install

# 4️⃣ Create a .env file in the frontend root and add your backend URL
VITE_API_URL=your_backend_api_url

# 5️⃣ Create a .env file in your backend folder and add your Gemini API key
GOOGLE_GEMINI_KEY=your_google_gemini_api_key

# 6️⃣ Run the app locally
npm run dev
