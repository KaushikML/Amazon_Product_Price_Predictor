
# Amazon Product Price Predictor

Welcome to the **Amazon Product Price Predictor** project! This repository showcases an end-to-end machine learning and AI solution for predicting Amazon product prices based on their descriptions. The project combines advanced data preprocessing, feature engineering, traditional machine learning models, and state-of-the-art AI techniques to achieve remarkable results.

---

## 🔍 **Overview**
Predicting product prices is a challenging task due to the variability and complexity of textual descriptions. Using a dataset of **400,000 data points**, this project explores a variety of models and techniques to deliver accurate price predictions.  

Key highlights:
- Fine-tuning large language models like **LLaMA 3.1** with **LoRA/QLoRA**.
- Experimenting with traditional machine learning models such as **Random Forest** and **Logistic Regression**.
- Leveraging **state-of-the-art AI models** like GPT-40 and its mini versions.
- Tracking and visualizing experiments with **Weights & Biases (W&B)**.

---

## 🧑‍💻 **Models Used**
We explored a variety of models to evaluate and improve prediction accuracy:
1. **Machine Learning Models**:
   - Features + Logistic Regression
   - Random Forest
   - Word2Vec (w2v) + Logistic Regression, SVM, and Random Forest
2. **AI Frontier Models**:
   - **GPT-40** (achieved $76 average error)
   - Fine-tuned **GPT-40-mini**
3. **Fine-Tuned LLaMA Model**:
   - **LLaMA 3.1 (8B parameters)** fine-tuned with **LoRA/QLoRA**:
     - Delivered the **best result yet** with an average prediction error of **$47**.

---

## 📈 **Results**
The progression of results highlights the improvements achieved through advanced techniques and model fine-tuning:

| Model                        | Average Prediction Error |
|------------------------------|--------------------------|
| Constant Baseline            | $146                    |
| Features + Logistic Regression | $139                  |
| Random Forest                | $97                     |
| Human Benchmark              | $127                    |
| GPT-40                       | $76                     |
| Fine-tuned LLaMA (LoRA)      | **$47**                 |

---

## 🚀 **Key Features**
- **Data Curation**: A robust pipeline for cleaning and preprocessing a massive dataset of 400,000 product descriptions.
- **Model Fine-Tuning**: Leveraging advanced fine-tuning techniques like **LoRA** and **QLoRA** for lightweight, efficient updates to large language models.
- **Visualization with W&B**: Seamless experiment tracking and visualization for model comparison, hyperparameter tuning, and error analysis.

---

## 📚 **How to Use**
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/KaushikML/Amazon_Product_Price_Predictor.git
   cd Amazon_Product_Price_Predictor
   ```


---

## 🛠️ **Technologies Used**
- **Languages**: Python
- **Machine Learning**: Logistic Regression, Random Forest
- **NLP**: Word2Vec, GPT-40, LLaMA 3.1
- **Fine-Tuning**: LoRA, QLoRA
- **Visualization**: Weights & Biases (W&B)

---

## 📈 **Visualization**
We relied heavily on **Weights & Biases (W&B)** for tracking experiments, comparing results, and analyzing model performance. The integration enabled us to iteratively improve and optimize our models effectively.

---

## 🧑‍🏫 **Acknowledgments**
This project was made possible under the guidance of **Ed Donner**, whose mentorship and expertise were instrumental in achieving these results.  

---

## 🌟 **Key Takeaways**
1. **Fine-Tuned AI Models Excel**: The fine-tuned **LLaMA 3.1** model outperformed all other methods, showcasing the potential of large language models in predictive tasks.
2. **Hybrid Approaches Work**: Combining traditional machine learning with modern AI models delivered significant improvements.
3. **Experiment Tracking Is Critical**: Tools like **W&B** made it easier to manage, analyze, and refine our models.

---

## 🤝 **Contributing**
Contributions are welcome! Feel free to open issues or submit pull requests to improve this repository.

---

## 📧 **Contact**
For any questions or collaborations, feel free to reach out via LinkedIn or email.

