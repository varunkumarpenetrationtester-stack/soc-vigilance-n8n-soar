# 🔐 SOC Vigilance – Automated SOAR using n8n

An automated Security Orchestration and Response (SOAR) workflow built using **Wazuh + n8n + Discord**.

---

## 🚨 Use Case
Detect SSH brute-force attacks and automatically notify SOC teams in real time.

---

## 🧱 Architecture
Wazuh → Webhook → n8n SOAR → Discord

---

## ⚙️ Workflow Stages
- Webhook intake
- Alert normalization
- Fingerprinting
- Deduplication
- Risk scoring
- Conditional filtering
- Discord alert via HTTP Request

---

## 🔔 Alert Details
- Rule: SSH Brute Force
- Source IP
- Target Host
- Severity
- Risk Score

---

## 📂 Repository Structure

workflows/ → n8n workflow JSON
samples/ → Test payload
screenshots/→ Proof of execution


---

## 🚀 How to Use
1. Import workflow JSON into n8n
2. Configure webhook in Wazuh
3. Add Discord webhook URL
4. Activate workflow

---

## 🧪 Testing
Use sample payload with webhook to test alerts.

---

## 👨‍💻 Author
Varun Kumar  
SOC | SOAR | Detection Engineering
