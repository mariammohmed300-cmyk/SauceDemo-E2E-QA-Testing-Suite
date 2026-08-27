# 🚀 SauceDemo E2E & QA Testing Suite

A professional QA portfolio project documenting End-to-End (E2E) test execution steps, edge cases, negative flows, and Jira board tracking for the [SauceDemo](https://www.saucedemo.com/) e-commerce web application.

---

## 📂 Project Structure & Visual Test Steps

Below is the complete sequence of test cases from **TC-1 to TC-21**, including their step-by-step variation images:

### 📋 Board Overview
* **Jira Kanban Board:** 
  
  ![Board List Example](./Board%20List%20Exmaple.png)

---

### 🛒 Positive E2E Purchase Flows
* **TC-1 (Single-Item Purchase):**
  
  ![TC-1](./TC-1.png)  
  *Variations:* 
  ![TC-1(1)](./TC-1(1).png) | ![TC-1(2)](./TC-1(2).png) | ![TC-1(3)](./TC-1(3).png) | ![TC-1(4)](./TC-1(4).png) | ![TC-1(5)](./TC-1(5).png) | ![TC-1(6)](./TC-1(6).png)

* **TC-2 (Multi-Item Purchase):**
  
  ![TC-2](./TC-2.png)  
  *Variations:* 
  ![TC-2(1)](./TC-2(1).png) | ![TC-2(2)](./TC-2(2).png) | ![TC-2(3)](./TC-2(3).png)

* **TC-3 (Sorted Products Purchase):**
  
  ![TC-3](./TC-3.png)  
  *Variations:* 
  ![TC-3(1)](./TC-3(1).png) | ![TC-3(2)](./TC-3(2).png)

* **TC-4 (Remove Item & Complete Checkout):**
  
  ![TC-4](./TC-4.png)  
  *Variations:* 
  ![TC-4(1)](./TC-4(1).png) | ![TC-4(2)](./TC-4(2).png)

---

### 🔒 Authentication & Error Flows
* **TC-5 (Locked-out User Login Attempt):**
  
  ![TC-5](./TC-5.png) | Variation: ![TC-5(1)](./TC-5(1).png)

* **TC-6 (Wrong Password Correction Flow):**
  
  ![TC-6](./TC-6.png) | Variation: ![TC-6(1)](./TC-6(1).png)

* **TC-7 (Empty Fields Login Validation):**
  
  ![TC-7](./TC-7.png) | Variation: ![TC-7(1)](./TC-7(1).png)

---

### 📝 Checkout Form Field Validations
* **TC-8 (Missing First Name):**
  
  ![TC-8](./TC-8.png) | Variation: ![TC-8(1)](./TC-8(1).png)

* **TC-9 (Missing Last Name):**
  
  ![TC-9](./TC-9.png) | Variation: ![TC-9(1)](./TC-9(1).png)

* **TC-10 (Missing Postal Code):**
  
  ![TC-10](./TC-10.png) | Variation: ![TC-10(1)](./TC-10(1).png)

* **TC-11 (All Fields Empty):**
  
  ![TC-11](./TC-11.png) | Variation: ![TC-11(1)](./TC-11(1).png)

---

### 🔄 Cancellation & Resume Flows
* **TC-12 (Cancel on Information Page & Resume):**
  
  ![TC-12](./TC-12.png) | Variation: ![TC-12(1)](./TC-12(1).png)

* **TC-13 (Cancel on Overview Page & Resume):**
  
  ![TC-13](./TC-13.png) | Variation: ![TC-13(1)](./TC-13(1).png)

---

### 👥 Account Variants & Session Flows
* **TC-14 (Performance Glitch User Full Purchase):**
  
  ![TC-14](./TC-14.png) | Variation: ![TC-14(1)](./TC-14(1).png)

* **TC-15 (Problem User Full Purchase):**
  
  ![TC-15](./TC-15.png) | Variation: ![TC-15(1)](./TC-15(1).png)

* **TC-16 (Error User Full Purchase Attempt):**
  
  ![TC-16](./TC-16.png) | Variation: ![TC-16(1)](./TC-16(1).png)

* **TC-17 (Visual User Full Purchase):**
  
  ![TC-17](./TC-17.png) | Variation: ![TC-17(1)](./TC-17(1).png)

* **TC-18 (Full Purchase & Session Termination Check):**
  
  ![TC-18](./TC-18.png) | Variation: ![TC-18(1)](./TC-18(1).png)

---

### ⚠️ Negative & Edge Case Flows
* **TC-19 (SQL-Injection Login Attempt):**
  
  ![TC-19](./TC-19.png) | Variation: ![TC-19(1)](./TC-19(1).png)

* **TC-20 (Browser Back Button After Order Completion):**
  
  ![TC-20](./TC-20.png) | Variation: ![TC-20(1)](./TC-20(1).png)

* **TC-21 (Page Refresh Mid-Flow & Non-Numeric Postal Code):**
  
  ![TC-21](./TC-21.png) | Variation: ![TC-21(1)](./TC-21(1).png)

---

## 🛠️ Tools Used
* **Target Application:** SauceDemo
* **Test Management:** Jira (Agile/Kanban Boards)
* **Documentation & Evidence:** Snipping Tool / Visual Test Logs
