# 🚀 AI-Powered Parametric Insurance for Delivery Partners

## 📌 Problem Statement

Delivery partners (Zomato, Swiggy, Amazon, Zepto, etc.) lose income due to external disruptions like heavy rain, extreme heat, pollution, curfews, or platform outages. Currently, there is **no system to protect their lost income**.

## 🎯 Objective

Build an **AI-powered parametric insurance platform** that:

* Protects delivery workers from **income loss**
* Automatically detects disruptions
* Triggers **instant payouts**
* Uses a **weekly premium model**

⚠️ Scope Limitation:

* Only covers **income loss**
* Does NOT cover health, accidents, or vehicle damage

---

## 👤 Target Persona

**Food Delivery Partner (Swiggy/Zomato)**

* Works 8–10 hours daily
* Earns per order
* Depends heavily on weather and demand

---

## 🔄 Application Workflow

1. User registers/login
2. Selects insurance plan (weekly)
3. System calculates premium using AI
4. Worker starts daily delivery work
5. System monitors external conditions (weather, AQI, etc.)
6. If disruption detected → claim triggered automatically
7. Income loss calculated
8. Instant payout sent to worker

---

## 💰 Weekly Premium Model

* Premium is charged **weekly**
* Based on:

  * Location risk
  * Weather history
  * Delivery frequency

### Example:

* ₹20/week premium
* Coverage up to ₹1000 income loss

---

## ⚡ Parametric Triggers

Triggers automatically activate claims:

* Rainfall > 50mm
* Temperature > 45°C
* AQI > 400
* Curfew / city lockdown
* Platform outage

---

## 🤖 AI/ML Integration

* **Risk Assessment:** Predict high-risk zones
* **Dynamic Pricing:** Adjust weekly premium
* **Fraud Detection:** Detect fake claims, GPS spoofing
* **Income Estimation:** Estimate expected daily earnings

---

## 🛠️ Tech Stack

### Frontend

* React.js
* Tailwind CSS

### Backend

* FastAPI (Python)

### Database

* SQLite / PostgreSQL

### APIs

* Weather API (OpenWeather)
* AQI API
* Mock Traffic API

---

## 📊 Future Scope (Phase 2 & 3)

* Automated claim system
* Fraud detection using ML
* Real-time dashboard
* Instant payment integration (Razorpay/Stripe)

---

## 🎥 Phase 1 Deliverables

* ✅ Idea Document (this README)
* ✅ GitHub Repository
* ⏳ 2-minute explanation video

---

## 📌 Summary

This project aims to create a **smart insurance safety net** for delivery workers by combining:

* AI
* Real-time data
* Automated payouts

👉 Helping gig workers stay financially secure even during disruptions.
