# SAP Order-to-Cash (O2C) Complete Sales Cycle Simulator

**KIIT SAP Capstone Project · SAP SD Module**  
**Student:** VAISHNAVI UTTAM KUMAR

**Roll No:** 2305178  
**Batch:** B.Tech CSE  
**Program:** SAP Business Data Cloud
**Submission Date:** April 18, 2026  

---

## Live Demo
Open `index.html` in any modern web browser. No server setup or installation is required.

---

## Project Overview
This project demonstrates the complete **Order-to-Cash (O2C)** business process in **SAP SD (Sales and Distribution)** through an interactive browser-based simulator. The O2C cycle starts from receiving a customer request and ends with billing and final payment collection.

The project is based on the SAP O2C process explained in the accompanying report and shows how SAP integrates **Sales, Inventory, Shipping, Billing, and Finance** into one structured workflow. The simulator helps users understand the sequence of activities, document generation, and overall transaction flow in a simple and visual way.

Unlike a purely theoretical report, this project adds an interactive layer where the user can move through the main business stages of the O2C cycle. It highlights how process automation reduces manual effort, improves coordination, and supports faster and more reliable execution of customer transactions.

---

## Problem Statement
In traditional business environments, customer order management is often handled manually or through disconnected systems. This creates several challenges such as:

- Errors in order entry  
- Delays in delivery  
- Poor tracking of invoices and payments  
- Lack of coordination between departments  
- Limited real-time visibility into sales and inventory  

This project addresses these challenges by presenting an integrated SAP-inspired O2C workflow that demonstrates how businesses can manage the complete sales cycle more efficiently.

---

## O2C Process Flow
The simulator follows the core O2C business process below:

**Inquiry → Quotation → Sales Order → Delivery → Billing → Payment**

### Simulated SAP Transaction Flow

| Step | T-Code | Activity |
|------|--------|----------|
| 1 | VA11 | Create Customer Inquiry |
| 2 | VA21 | Create Quotation |
| 3 | VA01 | Create Sales Order |
| 4 | VL01N | Create Outbound Delivery |
| 5 | VF01 | Create Billing Document |
| 6 | F-28 | Post Incoming Payment |

---

## Features
- Interactive browser-based O2C simulator  
- SAP-inspired transaction flow interface  
- Step-by-step navigation across the sales cycle  
- Dynamic document generation for each process stage  
- Document flow tracking panel  
- Order summary with quantity, pricing, discount, and total value  
- System log showing executed transactions  
- Final completion screen after full O2C cycle execution  

---

## Tech Stack

| Component | Details |
|----------|---------|
| ERP Concept | SAP ERP |
| Core Business Module | SAP SD (Sales and Distribution) |
| Integrated Business Areas | SAP MM, SAP FI |
| Frontend | HTML5, CSS3, Vanilla JavaScript |
| Interface Style | SAP-inspired workflow simulator |
| Execution Mode | Client-side, browser-based |

---

## Project Scope
This project focuses on understanding and simulating the complete Order-to-Cash workflow in SAP SD. It is designed to explain how customer transactions move from the initial inquiry stage to final payment while maintaining coordination across different business functions.

The simulator is intended for educational and demonstration purposes. It does not connect to a live SAP server, but it models the logical process flow, transaction sequence, and business events involved in a real SAP O2C cycle.

---

## How to Run

### Option 1: Directly Open in Browser
1. Download or clone this repository  
2. Locate the file `index.html`  
3. Double-click the file or open it in any browser  

### Option 2: Clone with Git
```bash
git clone https://github.com/<your-username>/sap-o2c-simulator.git
cd sap-o2c-simulator
