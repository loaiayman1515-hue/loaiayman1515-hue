<div align="center">
  <h1 align="center">👋 Hello, I'm <a href="[YOUR_PORTFOLIO_URL]" target="_blank">[YOUR NAME]</a></h1>
  
  <a href="[YOUR_PORTFOLIO_URL]">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=25D366&center=true&vCenter=true&width=600&lines=Architect+of+the+AI-Powered+Portfolio;Data+Analyst+%7C+AI+Integrator;Chat+with+my+AI+Assistant+Below!+%E2%AC%87%EF%B8%8F" alt="Typing SVG" />
  </a>

  <br/>

  <a href="[YOUR_PORTFOLIO_URL]">
    <img src="https://img.shields.io/badge/🚀_Launch_Live_Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white&border=green" height="50" />
  </a>
  
  <p><i>"I build data-driven applications that speak for themselves."</i></p>
</div>

---

### 🧠 The Engineering Behind the Portfolio

You might have seen my **Personal Portfolio with the Gemini AI Chatbot**. Here is the system architecture I designed to make it secure and responsive:

```mermaid
%%{init: {'theme': 'dark'}}%%
graph LR
    User(User / Recruiter) -->|Asks Question| Frontend(HTML/JS Portfolio)
    Frontend -->|Secure Request| Backend(Secure Node.js Server)
    Backend -->|API Call + Context| Gemini[🤖 Google Gemini API]
    Gemini -->|AI Response| Backend
    Backend -->|Sanitized Reply| Frontend
    Frontend -->|Display| User
