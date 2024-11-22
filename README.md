# Crop Recommendation System 🌾  

The **Crop Recommendation System** is a machine learning-powered web application designed to assist farmers in making informed decisions about which crops to plant. By analyzing critical environmental and soil parameters, the system provides personalized, data-driven recommendations to optimize agricultural productivity.  

This project combines the power of **data science**, **software development**, and **agriculture technology** to create a practical solution for farmers, empowering them with actionable insights for sustainable farming practices.  

---

## 🚀 Key Features  
### 🌍 Multi-Parameter Analysis  
Our model utilizes **six vital parameters**:  
- **Nitrogen (N)**  
- **Phosphorus (P)**  
- **Potassium (K)**  
- **pH**  
- **Humidity**  
- **Temperature**  
- **Rainfall**  

By incorporating these factors, the system delivers accurate, region-specific crop recommendations tailored to the user’s soil and climate conditions.  

### 🔍 Comprehensive Data Handling  
- The dataset was sourced from [Kaggle](https://www.kaggle.com/atharvaingle/crop-recommendation-dataset).  
- **Data Collection**: Ensured by **Jatin**, ensuring high-quality, diverse, and relevant data.  
- **Data Preprocessing & Visualization**: Managed by **Rahul**, who transformed raw data into actionable insights for model training.  

### 🤖 Machine Learning Model  
- Algorithm: **Random Forest**  
- Model selection, training, and testing were conducted collaboratively by **Pramath** and **Saksham**.  
- Assisted by **Kuldeep**, the team fine-tuned the model to achieve high accuracy and reliability, ensuring optimal recommendations.  

### 🌐 Full-Stack Development  
- **Frontend Development**: Designed using **HTML, CSS, and JavaScript** for an intuitive and user-friendly interface.  
- **Backend Development**: Built with **Flask** to integrate the machine learning model seamlessly with the application.  

---

## Technology Stack  
### Frontend:  
- **HTML5**  
- **CSS3**  
- **JavaScript**  

### Backend:  
- **Flask**  

### Machine Learning:  
- **Python**  
- **Scikit-learn** for building the Random Forest model  
- **Pickle** for model serialization  

---

## Installation  
### Prerequisites  
- Python 3.x  
- Flask  
- Virtual Environment (optional)  

### Steps  
1. Clone the repository:  
   ```bash  
   git clone https://github.com/parthmax2/crop-recommendation.git  
   ```  
2. Navigate to the project directory:  
   ```bash  
   cd crop-recommendation  
   ```  
3. Create a virtual environment (optional):  
   ```bash  
   python -m venv env  
   source env/bin/activate  # On Windows: .\env\Scripts\activate  
   ```  
4. Install dependencies:  
   ```bash  
   pip install -r requirements.txt  
   ```  
5. Run the application:  
   ```bash  
   python app.py  
   ```  
6. Open your browser and navigate to:  
   ```
   http://127.0.0.1:5000  
   ```  

---

## Usage  
1. Enter the required inputs in the respective fields:  
   - Nitrogen (N), Phosphorus (P), Potassium (K), Temperature, Humidity, pH, and Rainfall.  
2. Click the **"Get Recommendation"** button to see the most suitable crop.  
3. Use the **Search** feature to look up specific crops.  
4. Explore the **About** and **Contact Us** sections for additional information.  

---

## Contributors  

### Team Members:  
- **Saksham Pathak** *(Team Lead)*: Full-stack web development and integration.  
- **Jatin Saini**: Data collection and management.  
- **Rahul Bunker**: Data preprocessing and visualization.  
- **Pramath Dwivedi**: Model training, testing, and fine-tuning.  
- **Kuldeep Mishra**: Assisted in model selection and optimization.  

---

## Screenshots  
(Add screenshots of your application showcasing its features.)  

---

## License  
This project is licensed under the MIT License. See the `LICENSE` file for details.  
