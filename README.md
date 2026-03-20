# AI-Insurance-Gig-Workers
AI-powered parametric insurance platform for gig delivery workers in India, providing automated income protection against external disruptions like weather and pollution using dynamic pricing, fraud detection, and a hybrid risk model.

# AI-Powered Parametric Insurance for Gig Workers 🚀

## 🚩 Problem Statement

India’s gig delivery workers (Zomato, Swiggy, Blinkit, Amazon) frequently lose income due to external disruptions such as heavy rain, floods, pollution, and curfews. These events can reduce their earnings by up to 20–30%, and currently, there is no system to protect them from such income loss.
Note: This solution focuses only on compensating income loss and does not cover health, accidents, or vehicle damage.
---

## 👤 Target Persona

**Food Delivery Partner (Swiggy/Zomato Rider)**

### Scenario:

* Works ~8 hours/day
* Earns ~₹800/day
* Heavy rain occurs → fewer orders
* Earnings drop to ₹200

👉 Income loss = ₹600 (unprotected)

---

## 🔄 System Workflow

1. User registers on mobile app
2. Selects a weekly insurance plan
3. AI calculates personalized premium
4. System continuously monitors:

   * Weather data
   * Location (GPS)
   * Environmental conditions
5. If disruption occurs:

   * Claim is automatically triggered
   * Income loss is estimated
   * Instant payout is processed

---

## 💰 Weekly Premium Model

Premium is calculated dynamically using AI based on:

* Location risk (flood-prone, pollution levels)
* Historical weather data
* Average weekly earnings

### Example Pricing:

| Risk Level  | Weekly Premium |
| ----------- | -------------- |
| Low Risk    | ₹25/week       |
| Medium Risk | ₹40/week       |
| High Risk   | ₹60/week       |

👉 Premium updates weekly using ML-based risk scoring

---

## ⚡ Parametric Triggers (Automatic)

Claims are triggered automatically based on real-world data:

* 🌧 Rainfall > 50mm
* 🌫 AQI > 300
* 🚫 Curfew / zone closure
* 🌊 Flood alerts
* 📉 Significant drop in activity (proxy-based)

👉 No manual claim process required

---

## 🤖 AI/ML Integration

### 1. Risk Assessment Model

* Inputs:

  * Weather history
  * Location
  * Work patterns
* Outputs:

  * Risk score
  * Premium price

---

### 2. Fraud Detection

* GPS validation
* Activity verification
* Duplicate claim detection
* Anomaly detection

---

### 3. Predictive Model

* Forecasts probability of disruptions
* Adjusts weekly pricing dynamically

---

## 🔐 Fraud Prevention

* Location tracking (GPS)
* Cross-verification with weather APIs
* Detection of unusual claim patterns
* Duplicate claim blocking

---

## 🔗 Integrations

* Weather API (OpenWeatherMap)
* Maps/GPS APIs
* Mock delivery platform APIs
* Payment Gateway (Razorpay sandbox)

---

## 📊 Dashboard Features

### Worker Dashboard:

* Active coverage
* Earnings protected
* Claim history

### Admin Dashboard:

* Risk analytics
* Claim statistics
* Fraud alerts

---

## 🧑‍💻 Tech Stack

### Frontend:

* React.js / Flutter

### Backend:

* Node.js + Express

### Database:

* MongoDB

### AI/ML:

* Python (Scikit-learn)

---

## 📱 Platform Choice

👉 Mobile-first application

Reason:

* Gig workers primarily use smartphones
* Enables real-time tracking and notifications

---

## 🌍 Regional Risk Segmentation

India has diverse climate risks, so users are divided into regions:

| Region          | Risk Type        |
| --------------- | ---------------- |
| West (Mumbai)   | Extreme rainfall |
| South (Chennai) | Flood risk       |
| North (Delhi)   | Pollution        |
| East (Kolkata)  | Cyclones         |
| Central         | Moderate         |

👉 Each region has separate risk pricing

---

## 🧩 Hybrid Risk Model (Scalability)

To ensure financial stability:

* Regional pools handle local claims
* National pool acts as backup for extreme events

👉 Prevents system collapse during large-scale disruptions

---

## 📈 Financial Viability

* Premium collected from all users
* Partial payout model (not full income replacement)
* Controlled claim probability

👉 Ensures long-term sustainability

---

## 🛠 Development Plan

### Week 1:

* Finalize idea
* Design system
* Setup backend

### Week 2:

* Implement:

  * User registration
  * Risk model (basic)
  * Trigger simulation

---

## 💡 Innovation Highlights

* AI-based dynamic pricing
* Fully automated parametric claims
* Fraud detection system
* Hybrid risk pooling model
* Weekly micro-insurance approach

---

For real-world deployment, this platform can work in collaboration with licensed insurance providers while acting as a technology layer for automation and risk assessment.

---

## 📌 Conclusion

This system provides a **scalable and realistic financial safety net** for gig workers by combining AI, parametric insurance, and smart risk management. It ensures income stability during uncontrollable disruptions while remaining financially sustainable.

---
