# 📄 AI Powered SaaS Web Application - PDF Translator & Q&A Assistant

Welcome to **AISejong** — an AI-powered SaaS web application that helps users **upload, understand, and translate** complex official documents like government forms, legal contracts, and bank statements.

🧠 Ask questions in your **own language**, and get **accurate, context-aware answers** powered by GPT-4 Turbo + RAG.  
📅 Download a **fully translated PDF** (currently supports Korean 🇰🇷) that mirrors your original document layout. *(Formatting currently simplified; enhanced layout preservation in progress)*

---

🔗 **Live App**: [https://www.aisejong.com](https://www.aisejong.com)  
📁 **Source Code**: *Private Production Repository*

---

## 🧱INFRASTRUCTURE
![AI-wrapper](https://github.com/user-attachments/assets/948ead1a-396f-4e32-8d0b-12992b4491ae)


---

## 💡 What Can You Do?

- ✅ **Upload your own PDF**
- ❓ **Ask questions** in your preferred language about the content
- 🧠 **AI understands context** using Retrieval-Augmented Generation (RAG)
- 🌐 **Multilingual input**: Ask in Korean, English, etc.
- 📄 **Download a translated version** of the entire PDF (currently supports Korean 🇰🇷)
- 🔐 **Private & secure**: your documents are never shared

---

## 🧱 Tech Stack

### Frontend
- **Next.js (App Router)**
- **TypeScript**
- **Tailwind CSS**

### Backend / AI Layer
- **Next.js API Routes** (Node.js runtime)
- **TypeScript**
- **Custom AI Wrapper** – Handles multilingual input/output and context slicing

### Storage & Data
- **PostgreSQL + Drizzle ORM** – Document & user metadata (hosted on Neon)

### PDF Translation Engine
- Uses **NotoSansKR** for Korean font rendering
- Maintains original document formatting (headings, paragraphs, tables)

### Deployment
- **Render** (Frontend + API/Web Service + DB Hosting)

### Third-Party Services
- **Clerk** – User authentication and session management
- **Google Docs Viewer** – PDF preview
- **Socket.IO** – Real-time chat updates
- **OpenAI API** (GPT-4 Turbo)
- **Pinecone** – Vector similarity search (RAG for smarter Q&A)
- **AWS S3** – Stores original and translated PDFs

---

## 🛠️ Key Features

- 📄 **PDF Upload** – Drag & drop or browse
- 💬 **Multilingual Q&A** – Ask anything about the uploaded file
- 🧠 **Context-Aware Answers** – Uses RAG (GPT-4 + Pinecone)
- 🖨️ **Download Translated PDF** – Korean version preserves formatting
- 🕵️ **Private, Secure, Serverless** – Built with data privacy in mind

---

## 📦 Setup (Internal Use Only)

> ⚠️ This project is under active development and the source code is private.  
> Interested in licensing, partnership, or collaboration? [Contact me](mailto:kang0057@algonquinlive.com).

---

## 🚀 Future Roadmap

- ↺ Support for more languages (French, Spanish, Chinese)
- 📊 Translation confidence scores
- 🖋️ Preserve original PDF formatting in translated downloads (currently simplified)

---

## 🙇‍♂️ About the Developer

Hi, I’m **Hans Kang**, a full-stack developer focused on building tools that bridge language and accessibility barriers.

- 🌐 [Portfolio](https://hanskang.com)  
- 📢 [LinkedIn](https://www.linkedin.com/in/hanskkang)

