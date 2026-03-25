# 🤖 Resume.AI — Smart ATS Resume Editor

> **Paste or upload your resume → Enter a job role → Get an ATS-optimized version with keyword analysis, scoring, and downloadable output — powered by Groq AI (free)**

---

## 🌐 Live Demo

**[▶ Try it Live]([https://somathghara.github.io/resume-ai-editor](https://somgit001.github.io/resume-ai-editor/))**

---

## 📸 Preview

| Step 1 — Input | Step 2 — Optimized Resume | Step 3 — ATS Score |
|---|---|---|
| Paste or upload your resume | AI-edited with keywords added | Full ATS breakdown & suggestions |

---

## ✨ Features

- **📄 Upload or Paste** — Supports PDF, DOCX, DOC, TXT upload with automatic text extraction
- **🤖 AI Optimization** — Subtly edits your resume for a specific job role without rewriting it
- **🔑 Keyword Injection** — Adds role-specific keywords naturally into your existing content
- **💪 Bullet Enhancement** — Strengthens weak action verbs and improves impact statements
- **📊 ATS Score** — Scores your resume across 5 dimensions with visual progress bars
- **✅ Keyword Analysis** — Shows which keywords were found vs missing
- **💡 Suggestions** — Specific tips to improve your resume further
- **📥 Download as PDF** — Clean, properly formatted A4 PDF via jsPDF
- **📝 Download as DOCX** — Real Word-compatible `.docx` file (opens in Word, LibreOffice, Google Docs)
- **📋 Copy to Clipboard** — One-click copy of the optimized text
- **🌑 Dark Theme** — Glint-inspired dark UI with green accents
- **📱 Fully Responsive** — Works on mobile, tablet, and desktop

---

## 🚀 How to Use

### 1. Get a Free Groq API Key
1. Go to **[console.groq.com](https://console.groq.com)**
2. Sign up (free, no credit card needed)
3. Navigate to **API Keys** → **Create API Key**
4. Copy the key — it starts with `gsk_...`

### 2. Open the App
- Use the **[live demo](https://somathghara.github.io/resume-ai-editor)** directly in your browser
- Or download `resume-editor.html` and open it locally — no server needed

### 3. Optimize Your Resume
1. **Paste** your resume text or **upload** a PDF/DOCX/TXT file
2. Enter your **target job role** (e.g. `DevOps Engineer`, `Data Analyst`)
3. Optionally paste the **job description** for better keyword matching
4. Enter your **Groq API key** in the settings panel
5. Click **▶ Optimize Resume**
6. Review the optimized version → check ATS score → download

---

## 🧠 How It Works

```
Your Resume + Job Role
        ↓
  Groq AI (LLaMA 3.3 70B)
        ↓
  ┌─────────────────────────────┐
  │  1. Analyze resume structure │
  │  2. Add role-specific keywords│
  │  3. Strengthen bullet points │
  │  4. Add professional summary │
  └─────────────────────────────┘
        ↓
  Optimized Resume Text
        ↓
  ATS Scoring Analysis
        ↓
  ┌────────────────────────────────────┐
  │  Overall Score  │  Keyword Match   │
  │  Format Score   │  Role Relevance  │
  │  Experience     │  Missing Keywords│
  └────────────────────────────────────┘
        ↓
  Download as PDF or DOCX
```

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| **Vanilla HTML/CSS/JS** | Single-file app, no framework needed |
| **Groq API** (`llama-3.3-70b-versatile`) | AI resume optimization & ATS scoring |
| **PDF.js** | Extract text from uploaded PDF files |
| **Mammoth.js** | Extract text from uploaded DOCX files |
| **jsPDF** | Generate downloadable PDF output |
| **Pure JS ZIP builder** | Generate real `.docx` files without any library |
| **localStorage** | Save Groq API key across sessions |

---

## 📁 Project Structure

```
resume-ai-editor/
│
├── resume-editor.html    ← The entire app (single file)
└── README.md             ← This file
```

> The entire app is a **single HTML file** — no dependencies to install, no build step, no server required. Just open in a browser.

---

## 🔒 Privacy & Security

- ✅ Your resume text **never leaves your browser** except to the Groq API for processing
- ✅ Your Groq API key is stored only in your browser's `localStorage` — never in the code
- ✅ No database, no backend, no tracking
- ✅ Safe to use with personal resume data
- ✅ Open source — inspect every line of code

---

## 💡 Tips for Best Results

| Tip | Why |
|---|---|
| Paste the actual job description | Gives AI exact keywords to target |
| Use "Both ATS + Readability" mode | Best balance for most applications |
| Select the correct industry | Tailors keyword suggestions to your field |
| Check the "Keywords Missing" section | Add those manually for a higher score |
| Download as DOCX to edit further | Opens in Word/Google Docs for final tweaks |

---

## 📊 ATS Score Breakdown

| Score | Meaning |
|---|---|
| 🟢 80–100 | Strong match — likely to pass ATS filters |
| 🟡 60–79 | Moderate match — some improvements needed |
| 🔴 0–59 | Weak match — significant keyword gaps |

---

## 🙋 About the Developer

**Som Athghara**
Final-year BCA Student @ Sri Sri University

[![LinkedIn](https://img.shields.io/badge/LinkedIn-somathghara-blue?style=flat&logo=linkedin)](https://linkedin.com/in/somathghara)
[![Portfolio](https://img.shields.io/badge/Portfolio-som15.onrender.com-green?style=flat&logo=web)](https://som15.onrender.com)
[![GitHub](https://img.shields.io/badge/GitHub-somathghara-black?style=flat&logo=github)](https://github.com/somathghara)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

## ⭐ Support

If you found this useful, please **star the repo** — it helps others find it!

[![GitHub stars](https://img.shields.io/github/stars/somathghara/resume-ai-editor?style=social)](https://github.com/somathghara/resume-ai-editor)

---

*Built with ❤️ to help freshers and job seekers land their dream roles faster.*
