# AWS AI Dashboard 🚀

A **serverless project** that integrates 6 AWS AI services (Lex, Polly, Textract, Rekognition, Translate, and Comprehend) through **API Gateway** and **AWS Lambda**, enabling real-time demos, training, and business prototyping — all from a live dashboard.

---

## 🌟 Features
- 🎙 **Lex** – Conversational chatbot service  
- 🗣 **Polly** – Text-to-Speech (TTS) conversion  
- 📑 **Textract** – Extract text from scanned documents  
- 🖼 **Rekognition** – Image and video analysis  
- 🌍 **Translate** – Real-time language translation  
- 💬 **Comprehend** – Natural language processing and sentiment analysis  

---

## ⚙️ Architecture
1. User interacts with the **dashboard**.  
2. Request goes to **Amazon API Gateway**.  
3. **Lambda function** processes the request.  
4. Lambda calls the selected **AWS AI service**.  
5. The response is returned to the dashboard in real-time.  

---

## 📌 Use Cases
1. **Training & Education** → Students can explore AWS AI services hands-on.  
2. **Business & Prototyping** → Companies can test multiple AI services in one place.  
3. **Demo & Showcase** → Quickly demonstrate AWS AI capabilities in workshops or presentations.  

---

## 🛠 Tech Stack
- **AWS Lambda** – Serverless backend logic  
- **Amazon API Gateway** – Expose Lambda functions as REST APIs  
- **AWS AI Services** – Lex, Polly, Textract, Rekognition, Translate, Comprehend  
- **Frontend Dashboard** – Interactive UI for real-time testing  

---

## 🚀 Getting Started

### Prerequisites
- AWS account  
- Node.js / Python (for Lambda functions)  
- API Gateway & Lambda setup  

### Deployment
1. Clone the repo:  
   ```bash
   git clone https://github.com/your-username/aws-ai-dashboard.git
   cd aws-ai-dashboard
