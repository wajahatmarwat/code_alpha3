# code_alpha3
internship
### 🧪 Model Performance (Simulated Data)

Since the features were randomly generated (to simulate extracted MFCC-like features), the model's accuracy is low, as expected.

This demo is intended to show the **pipeline of speech emotion recognition**, including:
- Dataset simulation
- Label encoding
- Model training (Random Forest)
- Evaluation using classification report

In a real-world scenario, we would:
- Use real audio datasets like **RAVDESS**, **TESS**, or **CREMA-D**
- Extract features such as **MFCC**, **Chroma**, **Spectral Contrast** using `librosa`
- Train more complex models like **CNNs**, **LSTMs**, or **transformers**

> ⚠️ Note: This is a realistic simulation for educational purposes, not a final deployable model.
