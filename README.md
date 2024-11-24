# Unsupervised reconstruction of high-quality images from low light images

## Project Overview  
This project is part of the **IE643 course** and focuses on the **unsupervised enhancement of low-light images**. The goal is to transform **low-light, low-resolution images** into **high-light, high-resolution images**, addressing challenges like poor visibility and limited details.

---

## Implementation Steps  

### 1. **Setup WANDB**  
To implement the solution, you need a [Weights & Biases (WANDB)](https://wandb.ai/) account. If you do not already have one, create an account and retrieve your API key from the profile settings. The key is required for training the model and logging results.  

### 2. **Pre-Trained Model**  
If you prefer not to train the model:  
- Download the pre-trained `model.h5` file.  
- Place it in the **Colab working directory** for direct inference.  

---

### 3. **Streamlit UI**  

The code for the **Streamlit UI** is included under the **Streamlit UI** section at the end of the project.  

#### Instructions:  
1. Ensure the pre-trained model (`model.h5`) is placed in the Colab working directory.  
2. Run the commands provided under the **Streamlit UI** section to test the interface:  

   ```bash
   !wget -q -O - ipv4.icanhazip.com
   ```  

   This generates a **tunnel password**, which must be entered after clicking the link generated in the terminal.  

3. Upload the images as directed on the UI screen to observe the results.  

---

## References  

- [Zero-DCE Keras](https://youtu.be/PGOWjMCMB8I?si=pefyKe2gfMt3O-xJ)  
- [Image Enhancing with TensorFlow Hub](https://www.tensorflow.org/hub/tutorials/image_enhancing)  
