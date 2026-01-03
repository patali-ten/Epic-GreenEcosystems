#  <p align="center">🌿**Epic Green Ecosystems**</p>

<p align="center">
  <img src="assets/Screenshot 2025-12-08 211801.png" alt="Epic Green Ecosystems Landing Page - Spices" width="49%">
  <img src="assets/Screenshot 2025-12-08 212047.png" alt="Epic Green Ecosystems Landing Page - Taste Matters" width="49%">
</p>

Epic Green Ecosystems is a Spice Management System designed to manage all aspects of spice production and sales. The system is divided into five main subsystems, developed collaboratively by our team, ensuring comprehensive management from plantation to analytics.

> ⚠️ *Note:* This repository is a fork of the original group project.  
> The modifications in this fork highlight my individual contributions, primarily in the Order and Sales Management subsystem.


## 👤 My Role & Contributions
I was fully responsible for designing and implementing the **Order and Sales Management subsystem**, handling both **customer-facing** and **sales-officer-facing** workflows.

**Key contributions:**
- Designed and implemented complete order flows for **both local and export customers**, ensuring clear state transitions from request to completion.
- Developed a **spice catalogue** with **Stripe payment integration**, including receipt generation and email/download delivery.
- Built a **quotation request and approval workflow**, allowing customers to request quotes and sales officers to review and respond.
- Implemented **automatic pricing**, **currency conversion**, and **tax calculation** based on destination country.
- Generated finalized **quotation reports as PDFs**, enabling customer accept/reject decisions.
- Implemented **order status tracking** for all order types with real-time updates.
- Designed and maintained **separate dashboards** for customers and sales officers.
- Developed **sales analytics** (monthly sales, top-selling spices) with downloadable reports.
- Conducted domain research to ensure **realistic and logically consistent sales workflows**.

**Tech Stack Used:**
- MongoDB
- Express.js
- React.js
- Node.js
- Stripe API

## 🌱 **Subsystems/Features**
### 1. Plantation and Harvesting Management 
- Track spice cultivation cycles and harvesting schedules.
- Monitor yield and optimise plantation resources.
### 2. Inventory Management 
- Maintain stock levels and spices' conditions.
- Generate inventory reports for efficient operations.
### 3. Supplier Management
- Manage supplier details, orders, and deliveries.
- Track supplier performance and reliability.
### 4. Admin and HR Analytics Management 
- Manage employee records and HR functions.
- Provide analytics for workforce and operational insights.

## 🛠 **Installation / Setup**
-  **Clone the repository or download it**
    ```bash
    git clone https://github.com/savidi/Epic-GreenEcosystems.git
    ```
-  Ensure required software/dependencies are installed (database, server, etc.).
-  Project Setup (MERN Stack):

    *1. Backend Setup:*
    
      - Navigate to the backend directory
      - Install dependencies (npm install)
      - start the server (npm start)
       
    *2. Frontend Setup:*
    
      - Navigate to the frontend directory
      - Install dependencies (npm install)
      - start the client application (npm start)

## ✏️ **Demo Credentials**

> ⚠️ *Note:* For this fork, demo credentials are provided primarily for roles related to the **Order and Sales Management subsystem**, which was my area of contribution.

### **Customer**
Email: `eve@gmail.com`  
Password: `eve@123`

---

### **Sales Manager**
Email: `salesmng@gmail.com`  
Password: `3333`
***

You can also create a new account for a Customer using the **Register** page.

# 🚀 **Usage**
- Access each subsystem via the main interface.
- Utilise dashboards for analytics and reports.
- Monitor inventory, sales, and HR efficiently.
- Covers the whole supply chain from plantation to exportation with automated processes included

