# polynomial-approximation-with-neural-network
Function approximation of a cubic polynomial using a simple Artificial Neural Network (ANN) implemented in PyTorch.

---

This project demonstrates how an **Artificial Neural Network (ANN)** can learn to approximate a **cubic polynomial function** using **PyTorch**.

The goal is to train a simple feedforward neural network to model the function:
```

f(x) = x³ - 3x² + 2x + 1

````

---

## 📊 **Project Overview**

- **Objective:** Approximate a cubic polynomial function using a neural network.
- **Framework:** PyTorch
- **Key Concepts Covered:**
  - Data generation and preprocessing
  - ANN model architecture (using `torch.nn`)
  - Loss function (Mean Squared Error)
  - Optimizer (Adam)
  - Training loop (forward pass, backpropagation)
  - Visualizing model predictions vs the true function

---

## 🧑‍💻 **Project Structure**
| File/Folder           | Description                                     |
|-----------------------|-------------------------------------------------|
| `main.py`              | Main Python script with the full code workflow |
| `README.md`            | Project documentation (this file)              |
| `requirements.txt`     | Python dependencies                            |
| `output_plot.png`      | Sample output plot (optional, if you add one)  |

---

## ⚙️ **How to Run**

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/cubic-polynomial-approximation.git
   cd cubic-polynomial-approximation
````

2. **Install dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

3. **Run the script:**

   ```bash
   python main.py
   ```

4. **Output:**

   * The script will train the ANN to approximate the cubic function.
   * A plot will display comparing the **Analytical Solution (True Function)** with the **ANN Prediction**.

---

## 🧠 **Model Architecture**

* **Input Layer:** 1 neuron (input `x`)
* **Hidden Layer 1:** 64 neurons + ReLU
* **Hidden Layer 2:** 32 neurons + ReLU
* **Output Layer:** 1 neuron (predicted `y`)

---

## 📝 **Example Output Plot**

![<img width="853" height="547" alt="image" src="https://github.com/user-attachments/assets/8d9e8893-1973-4987-a2c3-527400c4d1fc" />]

---

## 📚 **Skills & Concepts Demonstrated**

* Function Approximation using Neural Networks
* PyTorch basics (model definition, training loop)
* Understanding of forward and backward propagation
* Loss minimization with optimizers (Adam)
* Visualization using Matplotlib

---

## 🔮 **Future Improvements**

* Compare with polynomial regression (as baseline)
* Experiment with deeper/wider networks
* Use different activation functions (LeakyReLU, Tanh, etc.)
* Turn this into a general function approximation playground

---

## 📎 **Requirements**

* Python 3.x
* torch
* numpy
* matplotlib

---

## 🚀 **License**

This project is open-source under the MIT License.

---

## 🙌 **Author**

Richard Olamide Olanite
[GitHub]((https://github.com/thatboypage?tab=repositories)) | [LinkedIn](www.linkedin.com/in/richard-olanite-55b4b0241)

```
