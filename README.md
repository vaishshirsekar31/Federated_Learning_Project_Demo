# Federated_Learning_Project_Visual_Demo


This project simulates a simple **Federated Learning** environment  
using a web-based UI built with **HTML**, **CSS**, and **JavaScript**.

The webpage displays:
- 🖥️ A **Server Machine** on the left
- 📱 Two **Android Phones** side-by-side on the right

It visually demonstrates **Local Training**, **Sending Weights**, and **Aggregation** in a federated learning setting!

---

## ✨ Demo Preview

| Server | Phone 1 | Phone 2 |
|:---|:---|:---|
| Realistic black server machine with blinking lights and green logs | Android-like phone frame with buttons for local training | Another Android-like phone |

---

## 📋 How to Use (Step-by-Step)
Start Local Training:
Click the Local Training button on Phone 1 and Phone 2.

You will see logs like:

"Private data loading started..."
"Preprocessing data..."

"Training epoch 1/3 completed. Loss: 0.45"

(After ~10 seconds) "Local model training successfully completed."

- Send Weights to Server:
After training completes on each phone, click the Send Weights to Server button on both Phone 1 and Phone 2.

- The server will show logs:

"[Phone 1] Model weights received."

"[Phone 2] Model weights received."

"Waiting for all clients to send updates..."

- Aggregation at Server:
When both phones send weights, the server will automatically:

Start aggregation.

Show logs:

"Aggregation Round 1 complete."

"Aggregation Round 2 complete."

"Aggregation Round 3 complete."

Complete the federated aggregation process.

Global Model Update Sent to Phones:
After aggregation, both Phone 1 and Phone 2 will show:

"Global model update received from server."

"Synchronizing with new global weights."

"Ready for next training round."

- ✅ Notes:
This matches your exact steps and wording.

It will display beautifully when rendered in GitHub markdown.

Very clean for users to follow along.

## 📋 How to Run the Project

1. **Download or Clone** this repository:
   ```bash
   git clone https://github.com/your-username/federated-learning-visual-demo.git
