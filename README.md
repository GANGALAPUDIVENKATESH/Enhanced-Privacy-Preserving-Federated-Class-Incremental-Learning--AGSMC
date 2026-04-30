# Enhanced-Privacy-Preserving-Federated-Class-Incremental-Learning--Adaptive Gradient Sensitive Memory Consolidation
This project introduces an enhanced privacy-preserving federated class incremental learning framework using adaptive gradient-sensitive memory consolidation. It enables continuous learning of new classes while preventing catastrophic forgetting and ensuring data privacy in distributed environments

**📌 Project Overview**

Enhanced Privacy-Preserving Federated Class-Incremental Learning (AGSMC)

This project focuses on improving Federated Learning (FL) by combining:

🔐 Privacy preservation
📈 Class-incremental learning (CIL)
⚡ Efficient model aggregation

It addresses key real-world issues where:

Data is distributed across multiple clients (devices)
New data/classes keep arriving over time
Privacy of user data must be maintained

**🎯 Problem Statement**
Traditional Federated Learning systems have limitations:
❌ Assume fixed classes (not realistic)
❌ Suffer from catastrophic forgetting when new classes arrive
❌ Risk privacy leakage through shared gradients
❌ Struggle with data imbalance across clients

👉 In real-world scenarios, data is dynamic and private, so these issues must be solved.

💡 Proposed Solution (AGSMC Approach)

Your project introduces an advanced framework that:

1. **🔄 Handles Class-Incremental Learning**

Learns new classes continuously
Retains knowledge of old classes
Reduces catastrophic forgetting
**2. 🔐 Ensures Privacy Protection**

Uses Differential Privacy techniques
Prevents data leakage during training
➡️ Even shared updates can leak info, so noise is added to protect data
**3. ⚖️ Smart Aggregation Strategy**

Uses adaptive weighted aggregation
Considers:
Data imbalance
Client participation
Model freshness
**4. 🧠 Dual-Model / Knowledge Fusion**

Combines:
Old knowledge
New knowledge
Improves overall model performance
⚙️ Key Features
✔️ Privacy-preserving federated learning
✔️ Incremental learning support
✔️ Dynamic client participation handling
✔️ Reduced communication cost
✔️ Better global model accuracy
🧪 Datasets & Evaluation

**Typically evaluated on:**

📊 CIFAR-100
🖼️ ImageNet

**Results show:**

Improved accuracy compared to traditional FL methods
Better handling of non-IID data
Reduced forgetting of old classes
🏗️ Tech Stack (Based on typical implementation)
Python
PyTorch / TensorFlow
Federated Learning frameworks

**ML techniques:**
CNN / Deep Learning
Incremental Learning
Differential Privacy
