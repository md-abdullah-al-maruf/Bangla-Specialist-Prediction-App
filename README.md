# 🩺 Specialist Prediction Model

This project is a **Bangla Specialist Prediction Model** powered by deep learning (TensorFlow/Keras).  
It predicts the most relevant **medical specialist category** based on a given Bangla health-related sentence.

---

## 🚀 Features
- Accepts **Bangla health-related queries** as input  
- Predicts the most suitable **medical specialist**  
- Built with **TensorFlow / Keras** and fine-tuned ResNet model  
- Deployed via **Flask + Gunicorn** for production-ready API  
- Supports **real-time predictions**  

---

## 🌟 Model Performance
- **Accuracy:** 0.95070 (~95%)  
- Highly reliable predictions for common medical symptoms  
- Model will be improved further with **larger datasets** in the future  

---

## 🌐 Live Demo
🔗 Link: [Specialist Prediction Web App](https://www.shebapabo.com/prediction/?text=%E0%A6%86%E0%A6%AE%E0%A6%BE%E0%A6%B0%20%E0%A6%B9%E0%A6%BE%E0%A6%A4%E0%A7%87%E0%A6%B0%20%E0%A6%A4%E0%A6%BE%E0%A6%B2%E0%A7%81%20%E0%A6%93%20%E0%A6%AA%E0%A6%BE%E0%A6%AF%E0%A6%BC%E0%A7%87%E0%A6%B0%20%E0%A6%A4%E0%A6%BE%E0%A6%B2%E0%A7%81%E0%A6%B0%20%E0%A6%A4%E0%A7%8D%E0%A6%AC%E0%A6%95%20%E0%A6%AE%E0%A7%8B%E0%A6%9F%E0%A6%BE%20%E0%A6%B9%E0%A6%AF%E0%A6%BC%E0%A7%87%20%E0%A6%97%E0%A7%87%E0%A6%9B%E0%A7%87%20%E0%A6%8F%E0%A6%AC%E0%A6%82%20%E0%A6%97%E0%A6%AD%E0%A7%80%E0%A6%B0%20%E0%A6%AB%E0%A6%BE%E0%A6%9F%E0%A6%B2%20%E0%A6%A6%E0%A7%87%E0%A6%96%E0%A6%BE%20%E0%A6%A6%E0%A6%BF%E0%A6%AF%E0%A6%BC%E0%A7%87%E0%A6%9B%E0%A7%87%E0%A5%A4)

Example Input:  
<pre>
https://www.shebapabo.com/prediction/?text=আমার হাতের তালু ও পায়ের তালুর ত্বক মোটা হয়ে গেছে এবং গভীর ফাটল দেখা দিয়েছে।
</pre>

Example Output:  
<pre>
{
  "input": "আমার হাতের তালু ও পায়ের তালুর ত্বক মোটা হয়ে গেছে এবং গভীর ফাটল দেখা দিয়েছে।",
  "predicted_specialist": "Skin"
}
</pre>

---

## 📖 How It Works
1. Input a **Bangla health sentence**  
2. Text is **preprocessed** and tokenized  
3. Model predicts the **most probable specialist**  
4. Result is displayed instantly  

---

## ⚙️ Tech Stack
- **Python 3.10+**
- **TensorFlow / Keras**
- **scikit-learn**
- **Flask**
- **Gunicorn**
- **HTML/CSS/JS** for frontend

---

## 🔮 Future Improvements
- Expand training dataset for **more rare diseases**  
- Increase model **accuracy and reliability**  
- Improve **response speed** for real-time predictions  
- Add **multi-language support**  

---

## 📜 License
This project is licensed under the **MIT License**.

---

## 👨‍💻 Author
Developed by **Md Abdullah Al Maruf**  
<p>
  <a href="mailto:mdabdullahalmaruf723@gmail.com"> Email</a> •
  <a href="https://github.com/md-abdullah-al-maruf"> GitHub</a> •
  <a href="https://www.linkedin.com/in/mdabdullahalmaruf"> LinkedIn</a>
</p>
