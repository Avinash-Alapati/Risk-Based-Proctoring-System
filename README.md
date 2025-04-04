# Risk-Based-Proctoring-System


# 👁️ Risk-Based Proctoring System

Welcome to the **Risk-Based Proctoring System** — an AI-powered smart exam monitoring solution designed to evaluate suspicious behavior during online assessments without invading user privacy.

---

## 🚀 What It Does

This project uses **real-time face and eye detection**, **typing behavior**, and **risk scoring** to monitor candidates during online exams. Instead of recording the whole session, our system calculates a **risk score** based on behavioral anomalies and only raises alerts when something looks fishy 🐟.

---

## 🧠 How It Works

1. **Face & Eye Detection** (OpenCV):
   - Detects number of faces.
   - Monitors if eyes are visible.
   - Absence of face/eyes increases risk score.

2. **Risk Evaluation**:
   - Assigns a risk score per frame.
   - Maintains an average risk over time.
   - Categorizes behavior as **Low Risk** or **High Risk**.

3. **Typing Behavior Monitoring** (JavaScript):
   - Detects abnormal typing patterns.
   - Alerts for sudden stops or rapid bursts in typing (a.k.a “thinking gap then speed race” 🏁).

4. **Real-time Feedback**:
   - Displays live camera feed.
   - Shows risk score and alert status in UI.

---

## 💡 Why This Project?

Online exams are booming — but cheating methods are boom-boom-max too. Traditional proctoring systems record video endlessly, invade privacy, and are inefficient.  
**This system is lightweight, smart, and privacy-conscious.**

---

## 📁 Folder Structure

