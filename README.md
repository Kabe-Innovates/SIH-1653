# Smart India Hackathon Workshop  

## Date:  13 / 03 / 2025
## Register Number: 212224110027
## Name: KABELAN G K

---

## Problem Title  
**SIH 1653: Web-based Selector-Applicant Simulation Software**  

## Problem Description  
**Background:** Recruitment and Assessment Centre (RAC) under DRDO, Ministry of Defence, carries out interviews for applications received against advertised vacancies and for promotion to the next higher grade for scientific manpower within DRDO.  

**Description:** Conducting unbiased and objective interviews is a challenging task. The process involves posing a set of questions by an interviewer and evaluating responses from candidates. To ensure fairness, the questions asked should match the expertise of the applicant, and responses should be evaluated for their relevance.  

**Expected Solution:**  
The proposed solution should provide a **real-life Board Room experience** for both experts and candidates, beginning with ice-breaking questions and leading into **in-depth techno-managerial** discussions. It should:  
✅ Provide **quantifiable scores** for both candidates and interviewers.  
✅ Ensure **relevant questions** based on candidate expertise.  
✅ **Grade candidate responses** for relevancy.  
✅ Assist in arriving at an **overall subject knowledge score** to determine suitability for the role.  

---

## Problem Creator's Organization  
**Ministry of Defence & DRDO**  

---

## Idea  
The web-based **Selector-Applicant Simulation Software** aims to create a **smart, unbiased, and data-driven interview process** using **AI-powered assessments, real-time proctoring, and automated evaluation mechanisms**.  

---

## Proposed Solution / Architecture Diagram  
*(Architecture diagram will be added separately.)*  

---

## Use Cases  
### **🔹 Use Case 1: Automated Interview Process**  
- AI dynamically generates **relevant questions** for the candidate.  
- The system evaluates **answers based on accuracy and relevance**.  
- Interviewers have an **override option** for AI-generated scores.  

### **🔹 Use Case 2: Secure Examination & Anti-Cheating Mechanisms**  
- Uses **Secure Exam Browser (SEB)-like features** to prevent malpractice.  
- **AI-powered proctoring** detects face changes, tab switching, and background noise.  

### **🔹 Use Case 3: AI-Powered Applicant Ranking & Decision Making**  
- **Applicant Tracking System (ATS) integration** for ranking candidates.  
- **Final scoring and reporting** for easy decision-making by DRDO recruiters.  

---

## Workflow  
### **🔹 1. User Registration & Authentication**  
✔ Users: **Candidates, Interviewers, Admins**  
✔ Secure **OTP-based login**  
✔ **Resume Upload & ATS Scoring** (AI-based resume parsing)  

### **🔹 2. Pre-Screening Test** *(Before the Interview)*  
✔ **SEB-like Secure Mode** prevents tab switching and screen recording  
✔ **AI-powered proctoring** (Face detection, voice tracking)  
✔ **Gamified pre-screening test** (Aptitude & technical questions)  
✔ **Automated shortlisting** for interviews  

### **🔹 3. Intelligent Interview Scheduling**  
✔ Candidate **selects available slots**  
✔ AI suggests **expert panelists** based on job role  
✔ **Virtual interview link generated**  

### **🔹 4. AI-Powered Interview Process** *(Main Interview)*  
✔ **Ice-breaking questions** (AI-generated based on profile)  
✔ **Techno-managerial questions** based on experience level  
✔ **Live AI Response Evaluation** (NLP-based grading, speech analysis)  
✔ **Expert panel scoring** with **manual override option**  
✔ **Proctoring in real-time** (Face tracking, voice anomaly detection)  

### **🔹 5. Post-Interview Analysis & Reporting**  
✔ **Candidate Performance Dashboard** (Graphical insights)  
✔ **Comparative Analysis** with past candidates  
✔ **Final Scoring (AI + Expert Weighted Average)**  
✔ **Tamper-proof records** stored via **blockchain**  

### **🔹 6. Candidate Feedback & Final Selection**  
✔ Candidates receive **detailed feedback reports**  
✔ **Final selection decision** (AI + Expert committee)  
✔ **Automated job offer & onboarding process** for selected candidates  

---

## Technology Stack  
| Component         | Technology Used |
|------------------|----------------|
| **Frontend**     | React.js / Angular |
| **Backend**      | Node.js / Django |
| **Database**     | PostgreSQL / MongoDB |
| **AI/ML**        | NLP, Speech Analysis, Face Detection |
| **Security**     | Blockchain, Secure Browser, AI Proctoring |

---

## Dependencies  
- **Machine Learning Models** for NLP-based question generation and response evaluation  
- **Secure Exam Browser (SEB) APIs** for monitoring candidate activity  
- **AI Proctoring Tools** for live fraud detection  
- **Blockchain Framework** for tamper-proof candidate records  

---

