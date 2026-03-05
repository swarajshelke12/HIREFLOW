<div align="center">
  <img src="https://via.placeholder.com/150x150?text=🤖" alt="HireFlow Logo" width="120">
  
  <h1>🔥 HIREFLOW: The Final Boss of Applicant Tracking 🚀</h1>
  <p><i>Because manual resume screening is for the weak. Welcome to the automated future.</i></p>
  
  <p>
    <img alt="Next.js" src="https://img.shields.io/badge/Next.js%2014-Black?style=for-the-badge&logo=next.js&logoColor=white">
    <img alt="n8n" src="https://img.shields.io/badge/n8n-Workflow%20Automation-FF6600?style=for-the-badge&logo=n8n">
    <img alt="Gemini" src="https://img.shields.io/badge/Google%20Gemini-AI%20Vision-4285F4?style=for-the-badge&logo=google">
    <img alt="Groq" src="https://img.shields.io/badge/Groq%20Llama%203-Crazy%20Fast%20LLM-F55036?style=for-the-badge">
    <img alt="Spline" src="https://img.shields.io/badge/Spline-3D%20Magic-black?style=for-the-badge&logo=spline">
  </p>
</div>

## 🤯 What is HireFlow?
**HireFlow** is an absolute powerhouse of an intelligent recruitment automation platform. It completely obliterates manual screening by using Large Language Models (LLMs) and Optical Character Recognition (OCR) to rip text from resumes, ruthlessly score candidates on semantic fit, and automate all the boring communication. 

You drop a resume in, and the AI brain takes over. 🧠⚡

## ✨ Functions & Features 
* 🌌 **3D God-Mode UI:** A visually stunning application portal built with Next.js 14, Tailwind CSS, and Spline 3D (`@splinetool/react-spline`) that makes uploading resumes feel like a literal video game. 
* 📄 **Universal Resume Shredder (Parsing):** Automatically extracts text from both PDFs and Scanned Images using specialized AI agents. 
* ⚖️ **Savage AI Scoring Engine:** Evaluates candidates from 0 to 100 based on Technical Proficiency, Communication & Design Sense, and Builder Mindset using Google Gemini and Groq (Llama 3).
* 🚦 **Ruthless Filtering System:** Scores of 75-100 get an auto-interview, 41-74 trigger a human review, and 0-40 get auto-rejected to the shadow realm. 
* 💔 **Smart Rejection Logic:** For candidates scoring under 45, the system automatically drafts a personalized, constructive rejection email that actually points out their specific technical gaps.
* 👀 **Human-in-the-Loop:** HR isn't dead yet! The "Wait for Approval" workflow sends an email with HTML "Approve" and "Reject" buttons so humans can make the final call on border-line candidates directly from their inbox.
* 🛡️ **Strict Frontend Guards:** Forces proper country-code specific phone inputs and rejects files bigger than 5MB for PDFs or 1MB for Images. Plus, you get blasted with a `canvas-confetti` celebration when you apply successfully! 🎉.

## 🛠️ The Ultimate Tech Stack

### **Frontend (The Drip 💧)**
* **Framework:** Next.js 14 & React 19
* **Styling:** Tailwind CSS
* **Animations:** Framer Motion & Canvas Confetti
* **3D Elements:** Spline 3D

### **Backend & AI (The Brains 🧠)**
* **Orchestrator:** n8n (Handling the entire webhook/workflow automation)
* **AI Vision Model:** Google Gemini 1.5 Pro (Extracting text from images/PDFs like a champ)
* **Decision LLM:** Llama 3 / GPT-OSS-20b via Groq (For hyper-fast, logical resume scoring)
* **Database:** Real-time Google Sheets Syncing
* **Comms:** Automated customized HTML templates via Gmail/SMTP

## ⚙️ How the Magic Actually Happens
1. **Candidate Uploads:** User drags and drops their resume into the highly-interactive frontend portal.
2. **Webhook Fires:** The frontend blasts a `FormData` payload straight to the secure n8n webhook (`http://localhost:5678/webhook/hireflow-apply`).
3. **Data Splitting:** The workflow intelligently routes based on MIME type (PDF vs. Image). 
4. **Agent Analysis:** * The **OCR Agent** reads images using Gemini.
    * The **Analysis Agent** (acting as a strict "Senior Engineering Manager") judges the parsed text and returns a structured JSON response.
5. **Decision Execution:** Data goes into dedicated Google Sheets (All Candidates, Rejected, Review, Interview).
6. **Instant Comm:** Emails are automatically generated and sent to candidates (Rejections, Interview Invites with Calendly links, or "Under Review" notifications).

## 💻 Spin It Up Quick
1. Clone the repo.
2. Run `npm install`.
3. Run `npm run dev` to start the Next.js server on localhost:3000.
4. Import the `AiPowered_Applicant_Tracking_System.json` file into your n8n instance to activate the god-tier backend.
5. Watch the system do the heavy lifting.

---
<div align="center">
  <i>Built with too much caffeine by <b>Swaraj Shelke</b>. If this blew your mind, smash that ⭐ button!</i>
</div>

## 👨‍💻 Developed By
**Swaraj Shelke**
- 🌐 [LinkedIn](https://www.linkedin.com/in/swaraj-shelke-0a3a752b8)
- 📸 [Instagram](https://www.instagram.com/swarajshelke12)
- 🎥 [YouTube](https://youtube.com/@swaraj_shelke)

-----
