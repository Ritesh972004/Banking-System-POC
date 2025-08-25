# 🏦 Banking System POC  

A simplified core banking system that demonstrates **transaction processing**, **card validation**, **secure PIN handling**, and **role-based transaction monitoring**.  

🔗 **Live Demo:** [Banking System POC](https://studio--banksim-oqbqo.us-central1.hosted.app/)  

---

## 🚀 Features  

- 💳 **Supports withdrawals and top-ups**  
- 🔑 **Secure PIN authentication** with SHA-256 hashing  
- 🛡️ **Role-based access**: *Super Admin* & *Customer*  
- 🌐 **Modern stack**: Spring Boot + React.js (recommended)  
- 🚦 **Card routing** based on card number range (Visa cards start with `4`)  
- 📊 **Real-time transaction monitoring & history**  

---

## 🛠️ Setup & Usage  

### 1️⃣ Prerequisites  
- Install **Java (JDK 17+)**  
- Install **Maven**  
- Install **Node.js (v16+)** & **npm**  

---

### 2️⃣ Backend Setup (Spring Boot)  

Clone the Repository:  
```bash
git clone https://github.com/Ritesh972004/banking-system-poc.git
cd banking-system-poc/backend
```

Build and Run:  
```bash
mvn clean install
mvn spring-boot:run
```  

➡️ Backend runs at: **http://localhost:8080**  

---

### 3️⃣ Frontend Setup (React.js)  

Navigate to frontend:  
```bash
cd ../frontend
```

Install dependencies:  
```bash
npm install
```

Run frontend:  
```bash
npm run dev
```  

➡️ Frontend runs at: **http://localhost:5173** 🚀  

---

## 📌 API Endpoints  

- `POST /transaction` → Handles withdrawals & top-ups (**System 1**)  
- `POST /process` → Validates card & executes transaction (**System 2**)  

---

## ✅ Test Cases  

- ✅ Successful withdrawal/top-up with valid card & PIN  
- ❌ Decline invalid card or wrong PIN  
- ❌ Decline insufficient balance (withdrawal)  
- ❌ Decline unsupported card range  
- 👨‍💼 **Super Admin** → View all transactions  
- 👤 **Customer** → View own balance & history  

---

## 🤝 Contributing  

Want to improve this project? Follow these steps:  

1. **Fork the repository**  
2. **Clone it locally**  
   ```bash
   git clone https://github.com/Ritesh972004/banking-system-poc.git
   ```  
3. **Create a new branch**  
   ```bash
   git checkout -b feature-branch
   ```  
4. **Make your changes & commit**  
   ```bash
   git commit -m "Added new feature"
   ```  
5. **Push changes**  
   ```bash
   git push origin feature-branch
   ```  
6. **Open a Pull Request on GitHub**  

---

🔥 **Star this repo ⭐ if you like this project!** 🚀  
