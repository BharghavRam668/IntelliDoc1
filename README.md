# 🚀 **IntelliDoc AI**

### 🔁 **Recurring Series**
- RRULE support  
- Exclusion dates  
- Recurrence expansion  

### 🔔 **Reminders & Attendees**
- Notification support  
- Event participation tracking  

---

# 🧩 **AI Service (FastAPI)**

The AI service runs independently from the frontend.

### **Endpoints**
- `GET /healthz` – Health check  
- `POST /chat` – Contextual AI chat endpoint  

### **Responsibilities**
- Maintain embeddings per user  
- Graph-based document linking  
- Context selection (workspace / folder / file)  
- LLM orchestration  

---

# 🛠 **Tech Stack**

## **Frontend**
- Next.js (App Router)  
- TypeScript  
- Tailwind CSS  
- Prisma ORM  

## **Backend (AI Service)**
- FastAPI  
- Uvicorn  
- Python  
- Embedding models  
- Graph RAG architecture  

## **Database**
- Prisma  
- PostgreSQL  
- Vector store integration  

## **Deployment**
- Vercel (Frontend)  
- Independent AI microservice  

---

# ⚙️ **Local Development**

## **Frontend Setup**

```bash
npm install
npm run dev
