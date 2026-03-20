# 🚀 AI-Powered Parametric Insurance for Gig Workers

## 📌 Overview
An AI-driven parametric insurance platform designed to protect gig workers (Zomato, Swiggy, Zepto, etc.) from **income loss caused by external disruptions** like extreme weather, pollution, and unexpected events.

Unlike traditional insurance, this system:
- ⚡ Detects disruptions automatically  
- 💸 Triggers instant payouts  
- 🧠 Uses AI for risk prediction, pricing, and fraud detection  

---

## 🚨 Problem Statement
Gig workers depend on daily earnings. External disruptions such as:
- 🌧️ Heavy rain  
- 🌊 Floods  
- 😷 Pollution  
- 🚫 Curfews / strikes  

can reduce their working hours and cause **20–30% income loss**.

Currently, there is **no structured income protection system** for such situations.

👉 This project strictly focuses on **LOSS OF INCOME ONLY** (no health, accident, or vehicle coverage).

---

## 👤 Target Users
- 🍔 Food delivery (Zomato, Swiggy)  
- 🛒 Grocery (Zepto, Blinkit)  
- 📦 E-commerce (Amazon, Flipkart)  

### 📉 Real Scenario
- Works ~8 hours/day  
- Earns ~₹800/day  
- Heavy rain → fewer orders  
- Earnings drop to ₹200  

👉 Income loss = ₹600 (unprotected)

---

## 💡 Solution
We propose a **parametric insurance system** that:
- Monitors real-world disruptions in real time  
- Automatically detects income loss conditions  
- Triggers claims without user intervention  
- Instantly compensates workers  

---

## ⚙️ System Workflow

```
Worker Registers → AI Risk Profiling → Weekly Plan Activated
        ↓
Real-time Monitoring (Weather / Events / Location)
        ↓
Disruption Detected (Rain / Pollution / Curfew)
        ↓
Automatic Claim Trigger
        ↓
AI Fraud Detection
        ↓
Instant Payout 💸
```

---

## 🧠 AI/ML Integration

### 🔍 Risk Assessment Model
- Inputs:
  - Weather history  
  - Location  
  - Work patterns  
- Outputs:
  - Risk score  
  - Weekly premium  

### 🛡️ Fraud Detection
- GPS validation  
- Activity verification  
- Duplicate claim detection  
- Anomaly detection  

### 📈 Predictive Modeling
- Forecasts disruptions  
- Dynamically adjusts pricing  
- Helps manage reserves  

---

## 💰 Weekly Premium Model

Premium is calculated dynamically using AI based on:
- Location risk  
- Historical disruptions  
- Average earnings  

### Example Pricing

| Risk Level  | Weekly Premium |
|-------------|---------------|
| Low Risk    | ₹25/week      |
| Medium Risk | ₹40/week      |
| High Risk   | ₹60/week      |

---

## ⚡ Parametric Triggers (Automatic Claims)

Claims are triggered when:
- 🌧 Rainfall > threshold  
- 🌫 AQI > limit  
- 🌊 Flood alerts  
- 🚫 Curfew / zone closure  
- 📉 Significant drop in activity  

👉 No manual claim process required  

---

# 💰 Hybrid Financial Model (Core Strength)

## 🔄 Model Overview
We use a **Hybrid Risk Pooling System**:
- 📍 Regional Pools (city/zone-based)  
- 🌍 National Pool (backup + large-scale crises)  

---

## 📊 Regional Distribution Table

| Region Type | Risk Level | Weekly Premium | Regional Pool % | National Pool % |
|-------------|------------|---------------|-----------------|-----------------|
| Metro (Flood-prone) | High | ₹40 | 75% | 25% |
| Urban | Medium | ₹30 | 70% | 30% |
| Semi-Urban | Low | ₹20 | 65% | 35% |
| Rural / Low Risk | Very Low | ₹15 | 60% | 40% |

---

## 📊 Regional Risk Segmentation

| Region          | Risk Type        |
|----------------|------------------|
| West (Mumbai)   | Extreme rainfall |
| South (Chennai) | Flood risk       |
| North (Delhi)   | Pollution        |
| East (Kolkata)  | Cyclones         |
| Central         | Moderate         |

---

## 📊 Fund Allocation Logic

```
Total Premium Collection
   ├── 70% → Regional Pool
   └── 30% → National Pool
```

---

## 📊 Regional Crisis Handling

| Condition | Regional Usage | National Usage | Outcome |
|----------|----------------|----------------|---------|
| Small local disruption | ✅ Full | ❌ None | Fast payout |
| Medium disruption | ✅ Partial | ✅ Backup | Balanced payout |
| Regional pool exhausted | ❌ None | ✅ Full | Stability ensured |

---

## 📊 National Crisis Handling

| Scenario | Action |
|----------|--------|
| Multi-city flood / cyclone | Use National Pool |
| Widespread pollution | Use National Pool |
| Large-scale disruption | National Pool dominates |

---

## 📊 Profit & Reserve Strategy

| Condition | Action |
|----------|--------|
| Profit exceeds threshold | Cap profit |
| Excess funds | Move to reserve |
| High-risk prediction | Increase buffer |
| Low-claim period | Strengthen reserves |

---

## 📈 Financial Viability
- Premium collected weekly  
- Partial payout model (not full income replacement)  
- Controlled claim probability  

👉 Ensures long-term sustainability  

---

## 🔐 Fraud Prevention
- Location verification  
- Worker activity validation  
- Cross-check with external data  
- AI anomaly detection  

---

## 🔗 Integrations
- Weather APIs (OpenWeatherMap)  
- GPS / Maps APIs  
- Mock delivery platform APIs  
- Payment gateway (Razorpay / UPI sandbox)  

---

## 📊 Dashboard

### 👤 Worker Dashboard
- Coverage status  
- Earnings protected  
- Claim history  

### 🧑‍💼 Admin Dashboard
- Risk analytics  
- Pool monitoring  
- Fraud alerts  
- Loss ratio  

---

## 🛠 Tech Stack

**Frontend:** React / Flutter  
**Backend:** Node.js / Python  
**Database:** MongoDB  
**AI/ML:** Scikit-learn  
**Payments:** Razorpay / UPI  

---

## 📱 Platform Choice
👉 Mobile-first approach  
- Gig workers primarily use smartphones  
- Enables real-time tracking and notifications  

---

## 🧩 System Architecture (High-Level)

```
                           ┌────────────────────────────┐
                           │     Gig Worker (User)      │
                           │   Mobile App / Web App     │
                           └─────────────┬──────────────┘
                                         │
                                         ▼
                           ┌────────────────────────────┐
                           │        API Gateway         │
                           │  (Authentication + Routing)│
                           └─────────────┬──────────────┘
                                         │
        ┌────────────────────────────────┼────────────────────────────────┐
        ▼                                ▼                                ▼
┌────────────────────┐        ┌────────────────────┐        ┌────────────────────┐
│   User Service     │        │   Policy Service   │        │   Payment Service  │
│ - Registration     │        │ - Weekly Plans     │        │ - Payout Handling  │
│ - Profile Data     │        │ - Premium Storage  │        │ - Razorpay / UPI   │
└─────────┬──────────┘        └─────────┬──────────┘        └─────────┬──────────┘
          │                             │                             │
          └──────────────┬──────────────┴──────────────┬──────────────┘
                         ▼                             ▼
              ┌────────────────────┐        ┌────────────────────────┐
              │   AI Risk Engine   │        │ Fraud Detection Engine │
              │ - Risk Scoring     │        │ - GPS Validation       │
              │ - Dynamic Pricing  │        │ - Activity Check       │
              │ - Zone Analysis    │        │ - Duplicate Detection  │
              └─────────┬──────────┘        └─────────┬──────────────┘
                        │                             │
                        ▼                             ▼
              ┌────────────────────────────────────────────┐
              │        Parametric Trigger Engine           │
              │ - Threshold Check (Rain / Pollution etc.)  │
              │ - Event Matching                           │
              │ - Auto Claim Trigger                       │
              └─────────────────────┬──────────────────────┘
                                    │
                                    ▼
              ┌────────────────────────────────────────────┐
              │        Event Monitoring System             │
              │ - Weather API                              │
              │ - Pollution API                            │
              │ - External Disruption Data                 │
              └─────────────────────┬──────────────────────┘
                                    │
                                    ▼
              ┌────────────────────────────────────────────┐
              │         Financial Engine (CORE)            │
              │                                            │
              │ - Regional Pool Management                 │
              │ - National Pool Management                 │
              │ - Fund Allocation Logic                    │
              │ - Profit Cap + Reserve Buffer              │
              └─────────────────────┬──────────────────────┘
                                    │
                                    ▼
              ┌────────────────────────────────────────────┐
              │               Claim Engine                 │
              │ - Claim Validation                         │
              │ - Approval Logic                           │
              │ - Loss Calculation                         │
              └─────────────────────┬──────────────────────┘
                                    │
                                    ▼
              ┌────────────────────────────────────────────┐
              │               Payout System                │
              │ - Instant Transfer                         │
              │ - UPI / Razorpay Integration               │
              └─────────────────────┬──────────────────────┘
                                    │
                                    ▼
              ┌────────────────────────────────────────────┐
              │                Dashboards                  │
              │  Worker View        |    Admin View        │
              │ - Coverage Status   | - Risk Analytics     │
              │ - Claims History    | - Pool Monitoring    │
              └────────────────────────────────────────────┘
```

## 🔹 System Flow Explanation

- The gig worker registers and selects a weekly insurance plan.  
- The AI Risk Engine calculates the premium based on location and risk factors.  
- The Event Monitoring System continuously collects real-time data (weather, pollution, disruptions).  
- When thresholds are crossed, the Parametric Trigger Engine automatically detects a valid disruption.  
- The Fraud Detection Engine verifies user authenticity (location, activity, duplicates).  
- The Financial Engine decides the payout source:
  - Regional Pool (for local events)
  - National Pool (for large-scale events)  
- The Claim Engine validates and processes the claim automatically.  
- The Payout System transfers money instantly via UPI / Razorpay.  
- Dashboards provide insights for both workers and admins.  

---

## 🎯 Key Features

✔ AI-based pricing  
✔ Weekly subscription model  
✔ Fully automated claims  
✔ Instant payouts  
✔ Fraud detection system  
✔ Hybrid risk pooling  

---

## 🚀 Future Scope
- Real platform integration  
- Advanced ML models  
- Nationwide scaling  

---

## 💥 Conclusion

This system introduces a **financially sustainable, AI-driven insurance model** that protects gig workers from income loss while balancing **regional efficiency and national stability**.
