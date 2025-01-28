# **Website Sentiment Analysis App** 🎭💬  

A **Streamlit**-based web app to predict emotions in text using a pre-trained machine learning model. The app supports two input modes:  

1. **Manual Text Input** ✍️: Enter text directly to analyze its emotional tone.  
2. **Web Scraping** 🌐: Provide a URL to scrape text from the web, preprocess it, and predict the emotions.  

### **Features** 🚀:  
- Predicts emotions like **anger** 😠, **joy** 😂, **sadness** 😔, and more with emoji representation.  
- Displays prediction probabilities 📊 using an interactive bar chart.  
- Simple, user-friendly interface for both manual and web-based input.  

### **Machine Learning Algorithms** 🤖:  
The app leverages multiple ML models for accurate emotion detection:  
- **Support Vector Classifier (SVC)** 📈: Ensures robust separation of text classes.  
- **Logistic Regression** 🧠: Ideal for interpreting probabilities and classifying emotions.  
- **Random Forest Classifier** 🌲: Combines multiple decision trees for better accuracy and generalization.  

### **Tech Stack** 🛠️:  
- **Streamlit** for the frontend.  
- **Scikit-learn** for the pre-trained emotion detection model.  
- **BeautifulSoup** for web scraping.  
- **Altair** for data visualization.  

Run and detect emotions in any text instantly! ✨💡  

__________________________________________________________

**Installation Instructions** 📥

Clone this repository:
git clone https://github.com/yourusername/TextEmotionDetectionApp.git
cd TextEmotionDetectionApp

Install the required dependencies just if in case :
!pip install pandas

!pip install numpy

!pip install BS4

!pip install streamlit

!pip install joblib

!pip install scikit-learn

!pip install altair



Run the app:     streamlit run app.py


__________________________________________________________

Contributing 🤝
