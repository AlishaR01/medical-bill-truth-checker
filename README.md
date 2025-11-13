# Medical Bill Truth Checker 🏥🔍

The **Medical Bill Truth Checker** is a Streamlit-based application designed to help consumers verify the accuracy of medical bills. It identifies unusual or suspicious charges using a simple risk-scoring model and stores results in a blockchain-style ledger for transparency and integrity.

---

## 💡 Features

- **Upload Medical Bill Data**  
  Enter claim details such as provider, total amount, number of line items, and in-network status.

- **Automated Risk Detection**  
  Flags high-risk medical bills based on patterns associated with overbilling or fraudulent claims.

- **Blockchain-Style Ledger**  
  Each bill evaluation is stored as a cryptographically hashed block to ensure traceability and tamper resistance.

- **Interactive Web App**  
  Built with Streamlit, allowing the user to interact with the system via a user-friendly interface.

---

## 🛠️ Technologies Used

- **Python 3**
- **Streamlit**
- **RandomForestClassifier (simulated model)**
- **JSON / Hashlib for blockchain structure**

---

## 🚀 How to Run the App

1. Install dependencies:
