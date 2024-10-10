# Federaed_learning-DP-HE
# Differential Privacy and Homomorphic Encryption in Federated Learning

This project presents a **privacy-preserving framework for federated learning** that leverages **Fully Homomorphic Encryption (FHE)** and **Differential Privacy (DP)** to ensure data security and maintain model accuracy, particularly in sensitive medical data applications. The solution eliminates the need for sharing raw data by using encryption and privacy techniques to protect individual data points while allowing effective model training.

### Project Overview

In this study, we apply the framework to the **Pima Indians Diabetes Database**, utilizing the **FedAvg algorithm** for secure and efficient model updates exchange. FHE is used to perform encrypted computations during model aggregation, which prevents adversarial attacks by ensuring that computations happen without exposing the underlying data. DP is employed to ensure that individual contributions to the model remain indistinguishable, enhancing data privacy.

The combination of FHE and DP offers a balanced trade-off between **privacy** and **computational efficiency**. This setup helps maintain data integrity, protects against adversarial attacks, and ensures that model performance remains robust for healthcare-related applications.

### Key Features

- **Federated Learning:** Implements the FedAvg algorithm to distribute learning across multiple devices while preserving data privacy.
- **Fully Homomorphic Encryption (FHE):** Enables secure encrypted computations on model updates, protecting sensitive data throughout the process.
- **Differential Privacy (DP):** Ensures that individual data contributions remain indistinguishable, preventing any potential privacy leaks.
- **Application to Healthcare:** Applied to the Pima Indians Diabetes Database to demonstrate effectiveness in real-world healthcare scenarios.
- **Adversarial Attack Prevention:** The framework provides robust protection against data breaches and adversarial attacks during model aggregation.


### How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/fhe-dp-federated-learning.git
   cd fhe-dp-federated-learning
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the federated learning with encrypted model updates:
   ```bash
   python main.py
   ```

### Results

The framework effectively balances privacy and computational efficiency, preserving model performance in healthcare applications. The evaluation demonstrates that integrating FHE with DP safeguards sensitive medical data without compromising the quality of the learning process.

### Technologies Used

- **Fully Homomorphic Encryption (FHE)**
- **Differential Privacy (DP)**
- **Python**
- **Pima Indians Diabetes Database**
- **FedAvg Algorithm**

### Future Work

This framework can be expanded to incorporate additional privacy-preserving techniques, further enhance computational efficiency, and apply it to other datasets in the healthcare domain.

### License

This project is licensed under the MIT License. See the `LICENSE` file for more details.



