Hi, I'm Chandana Gaddapara  – a Machine Learning enthusiast with a passion for practical, real-world applications.  
This is my project SMART SORTING to Identifying Rotten fruits and Vegetables . 
I enjoy bridging AI with intuitive design through Python, Flask, and modern web technologies.

# 🚀 Smart Sorting –transfer learning for identifying Rotten Fruit & Vegetable Classification

---

## 1. Introduction

### 1.1 Project Overview  
Smart Sorting is a transfer-learning -powered web application that classifies fruits and vegetables as Healthy or Rotten using Transfer Learning (VGG16). It helps reduce food waste and enhance quality control in households, markets, and supply chains.

### 1.2 Purpose  
To automate the sorting process of produce, ensuring faster and more accurate identification of items that are unfit for consumption.

---

## 2. Ideation Phase

### 2.1 Problem Statement  
Manual sorting is prone to human error and inconsistency, leading to food waste, quality loss, and inefficiency in produce distribution.

### 2.2 Empathy Map Canvas  
**👤 User Persona:**  
Produce quality checker in a supermarket / Vendor at a local market

**🗣️ Says**  
- “I can’t always tell which items are still fresh.”  
- “I wish there was a faster, more reliable way to sort produce.”  
- “I don’t want to throw away good fruits by mistake.”

**💭 Thinks**  
- “Am I sorting these items correctly?”  
- “Customers might complain if I miss something bad.”  
- “I could save time and waste if I had a smart tool.”

**🤲 Does**  
- Inspects fruits and vegetables manually  
- Relies on experience or guesswork  
- Sorts quickly to keep up with workflow

**💡 Feels**  
- Stressed and uncertain during decision-making  
- Frustrated by mistakes or complaints  
- Hopeful that technology could help

### 2.3 Brainstorming  
- Use VGG16 for transfer learning  
- Web interface for uploads and predictions  
- Display confidence and feedback  
- Grad-CAM for model transparency

---

## 3. Requirement Analysis

### 3.1 Customer Journey Map  
User → Upload Image → Model Predicts Class → Result Displayed 

### 3.2 Solution Requirement  
**Functional:**  
- Upload & classify images  
- Display freshness result  
- Feedback collection

**Non-functional:**  
- Easy to use  
- Fast performance  
- Reliable predictions

### 3.3 Data Flow Diagram  
[User Upload] → [Flask API] → [Preprocessing] → [Model Prediction] → [Result Page]

### 3.4 Technology Stack  
**Frontend:** HTML5, CSS3  
**Backend:** Python, Flask  
**Database:** Not applicable  
**Others:** TensorFlow, Keras, PIL, NumPy

---

## 4. Project Design

### 4.1 Problem Solution Fit  
Automates traditional sorting with a pre-trained CNN, offering consistent and fast decisions.

### 4.2 Proposed Solution  
Flask-powered web interface with a VGG16 model to classify 29 categories based on freshness.

### 4.3 Solution Architecture  
User Upload → Flask Server → Model Prediction → Output to Frontend

---

## 5. Project Planning & Scheduling

### 5.1 Project Planning  
- Week 1: Data handling & cleaning  
- Week 2: Model setup and training  
- Week 3: Flask integration  
- Week 4: Testing & documentation

---

## 6. Functional and Performance Testing

### 6.1 Performance Testing  
- Accuracy evaluated on validation set  
- Testing on unseen samples  
- Grad-CAM validation to interpret model focus

---

## 7. Results

### 7.1 Output Screenshots  
![home page](/static/assets/Screenshot2025-06-27092736.png)

## 8. Advantages & Disadvantages

**Advantages**  
- Reduces waste  
- Increases sorting efficiency  
- Easy to deploy

**Disadvantages**  
- Limited to dataset categories  
- Needs good lighting for optimal accuracy

---

## 9. Conclusion  
Smart Sorting shows how deep learning and web deployment can simplify a real-world challenge, with meaningful social and commercial impact.

---

## 10. Future Scope  
- Mobile and camera input support  
- Expand category classes  
- Add feedback-based retraining module

---

## 11. Appendix  

**Dataset:** [https://www.kaggle.com/datasets/muhammad0subhan/fruit-and-vegetable-disease-healthy-vs-rotten]  
**GitHub Repository:** [https://github.com/chandana-0/smart-sorting-transfer-learning-for-identifying-rotten-fruits-and-vegetables]  







