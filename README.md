
## 🚀 Jathpatseva – Hyperlocal On-Demand Service Platform
Due to large size of zip file, we uploaded it to drive. Here is the drive link to access the file : https://drive.google.com/file/d/136PNZmV6BRCPSYig2SP4ioh5mRhtuVgF/view?usp=sharing
**Jathpatseva** is a smart hyperlocal service platform designed to connect people with nearby service providers such as plumbers 🔧, electricians ⚡, carpenters 🪚, technicians 🧰, and other essential household workers.

Finding a reliable service provider in urgent situations can often be frustrating. People usually rely on phone contacts, local references, or spend time searching for workers. **Jathpatseva solves this real-world problem** by creating a digital platform where users can request services instantly and get connected with nearby professionals in real time.

---

## 💡 How It Works

1️⃣ A **customer** selects a service category and submits a request with their location 📍.
2️⃣ The system finds nearby available **service providers** using geolocation-based matching.
3️⃣ Providers receive **instant notifications** about the job.
4️⃣ A provider accepts the request and travels to the customer's location.
5️⃣ After the work is completed, the job is verified using **OTP authentication** 🔐.
6️⃣ The customer can rate the service provider ⭐ to maintain service quality.

This simple but powerful workflow reduces waiting time and makes local services more accessible and reliable.

---

## 🧠 Smart System Design

The backend of Jathpatseva is built using **FastAPI ⚡**, a high-performance Python framework, with **PostgreSQL 🗄️** as the database. **SQLAlchemy** is used as the ORM to manage database operations efficiently.

To find nearby providers, the system uses **geolocation-based matching with the Haversine formula 🌍**, which calculates the distance between the customer's and provider's coordinates.

For instant communication, **WebSockets 🔔** are used to deliver real-time notifications such as:

* New job requests
* Job acceptance updates
* Status changes

This ensures the platform feels fast and responsive without constantly refreshing the app.

---

## 📱 Mobile Application

The frontend is built using **Flutter 💙**, enabling a smooth cross-platform mobile experience. The app supports two main user roles:

👤 **Customers**

* Request services
* Track service status
* View request history
* Rate providers

🧑‍🔧 **Service Providers**

* Toggle availability (online/offline)
* Receive nearby job requests
* Accept and complete jobs
* Manage active tasks

The app uses **Riverpod** for state management, ensuring efficient UI updates and clean architecture.

---

## 🔐 Security & Reliability

To ensure a secure and trustworthy platform:

* 🔑 **JWT Authentication** secures API access
* 🔒 **Password hashing** protects user credentials
* 📲 **OTP verification** confirms job completion
* ⭐ **Ratings & reviews** maintain service quality

---

## 🏗️ Scalable Architecture

Jathpatseva follows a **modular client–server architecture**, separating the frontend, backend APIs, authentication logic, and matching algorithms.

This makes the system **easy to scale and extend** in the future.

---

## 🔮 Future Enhancements

The platform can be further enhanced with advanced features such as:

🤖 AI-based provider recommendations
💳 Secure digital payment integration
📊 Smart demand prediction for services
🛡️ Fraud detection systems
☁️ Cloud deployment for multi-city support

---

✨ **Jathpatseva aims to simplify everyday life by making essential local services faster, smarter, and more accessible for everyone.**
