# Anomaly Detection in Smart Grids Using Blockchain-Integrated Collaborative Decision-Making Systems  

## Project Overview  
This project presents a decentralized system for detecting anomalies in smart grids. It integrates blockchain technology for secure, collaborative decision-making, ensuring tamper-proof validation. The primary objective is to improve anomaly detection accuracy and enhance the security of smart grids by combining machine learning with blockchain consensus mechanisms.

---

###  Features  
- Decentralized Anomaly Detection: Utilizes 10 distinct machine learning models (LSTM, CNN, Autoencoder, SVM, Random Forest, KNN, MLP, RNN, TCN, Logistic Regression) to detect unusual patterns in smart grid data.  
- Blockchain Integration: Uses Proof of Authority (PoA) for decentralized consensus, enabling secure and tamper-proof anomaly validation.  
- Tamper-Proof Validation: Anomalies detected by ML models are verified using blockchain voting, and the results are stored immutably.  
- Efficient Processing: Utilizes LSTM and CNN for accurate temporal and spatial anomaly identification.  
- Hybrid System Architecture: Integrates ML-based detection with blockchain for secure decision-making and auditability.  

---

###  Technologies  
- Blockchain: Solidity, Web3.py, Ganache, Remix IDE  
- ML Models: LSTM, CNN, Autoencoder, SVM, Random Forest, KNN, MLP, RNN, TCN, Logistic Regression  
- Environment: Google Colab (Model Training), Localhost (Blockchain Testing)  
- Programming Language: Python  
- Data Handling: Pandas  



###  Project Structure  
- src/: Core modules for ML model training, blockchain interaction, and anomaly detection  
- contracts/: Solidity smart contracts for anomaly validation and voting  
- scripts/: Python scripts for ML prediction and blockchain integration  
- docs/: Technical documentation and research papers  
- examples/: Sample anomaly datasets and detection scenarios  
- tests/: Unit and integration tests for ML and blockchain components  
- assets/: Visualizations and performance metrics  



###  Getting Started  
 Clone the repository:  
   ```bash
   git clone https://github.com/ArafaNawaz/Thesis-Anomaly-Detection-System.git
   cd Thesis-Anomaly-Detection-System
