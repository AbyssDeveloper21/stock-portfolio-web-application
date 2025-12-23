# 📈 Stock Portfolio App

![Demo](demo/stock-portfolio-app-demo.gif)

A **full-stack stock portfolio web application** that allows users to register, authenticate, and manage a virtual stock portfolio by buying and selling stocks using **real-time market data from IEX Cloud**.

Built to demonstrate **end-to-end MERN + Next.js development**, including authentication, API integration, and database-driven state management.

---

## 🧭 Table of Contents

* [About the Project](#about-the-project)
* [Technology Stack](#technology-stack)
* [Getting Started](#getting-started)

  * [Prerequisites](#prerequisites)
  * [Installation](#installation)
* [License](#license)

---

## 📌 About the Project

This application enables users to:

* Register and securely authenticate accounts
* Buy and sell stocks using real-time pricing data
* Track portfolio holdings and total value
* View complete transaction history

The project showcases **full-stack architecture**, **secure authentication**, and **external API integration** using modern JavaScript technologies.

---

## 🧰 Technology Stack

### Frontend

* **Next.js** – Server-side rendering & routing
* **React** – UI component library

### Backend

* **Node.js** – JavaScript runtime
* **Express.js** – RESTful API framework

### Database

* **MongoDB** – NoSQL document database

### External Services

* **IEX Cloud API** – Real-time stock pricing

---

## 🚀 Getting Started

Follow the steps below to run the project locally.

---

### ✅ Prerequisites

* **Node.js & npm**

Update npm to the latest version:

```bash
npm install npm@latest -g
```

* **MongoDB**

  * Install locally: [https://docs.mongodb.com/manual/installation/](https://docs.mongodb.com/manual/installation/)
  * Or use **MongoDB Atlas**: [https://www.mongodb.com/cloud](https://www.mongodb.com/cloud)

---

### 🛠️ Installation

#### 1️⃣ Obtain an IEX Cloud API Key

Sign up at:
[https://iexcloud.io/](https://iexcloud.io/)

---

#### 2️⃣ Clone the Repository

```bash
git clone https://github.com/username/stock-portfolio-app-demo.git
cd stock-portfolio-app-demo
```

---

#### 3️⃣ Install Dependencies

```bash
npm install
```

---

#### 4️⃣ Configure Environment Variables

Create a `.env` file in the project root:

```env
PORT=3000

MONGODB_URI=YOUR_MONGODB_ATLAS_URI
MONGODB_URI_DEV=YOUR_LOCAL_MONGODB_URI
MONGODB_URI_TEST=YOUR_TEST_MONGODB_URI

IEX_URI=https://cloud.iexapis.com/stable
IEX_KEY=YOUR_IEX_API_KEY

JWT_SECRET=YOUR_JWT_SECRET
```

---

#### 5️⃣ Start MongoDB (Local Only)

```bash
sudo service mongod start
```

---

#### 6️⃣ Run the Application

```bash
npm run dev
```

Open your browser and navigate to:
👉 **[http://localhost:3000](http://localhost:3000)**

--