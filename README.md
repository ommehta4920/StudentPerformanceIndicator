# Student Performance Indicator – Machine Learning Project  

This project predicts **student academic performance** based on various socio-economic, demographic, and academic features. It uses **Machine Learning models** to provide insights into factors affecting student success.  

**Live Demo:** [Student Performance Indicator](https://student-performance-indicator-zs7g.onrender.com/)  

---

## Tech Stack  

- **Python**
- **Flask** (for backend web app)  
- **Scikit-learn, Pandas, NumPy** (for ML model & data handling)  
- **HTML, CSS, Bootstrap** (for frontend)  
- **Render** (for deployment)  

---

## Software & Tools Requirements  

1. [GitHub Account](https://github.com) – For version control & collaboration  
2. [Render Account](https://render.com) – For deployment  
3. [VS Code IDE](https://code.visualstudio.com/) – For development  
4. [Git CLI](https://git-scm.com/book/en/v2/Getting-Started-The-Command-Line) – To interact with Git  

---

## Getting Started  

### 1. Clone the Repository  
```bash
git clone https://github.com/ommehta4920/StudentPerformanceIndicator.git
cd student-performance-indicator
```

### 2. Create a Virtual Environment
```bash
python -m venv venv
```

#### Windows
```bash
venv\Scripts\activate
```

#### Mac/Linux
```bash
source venv/bin/activate
```

### 3. Install Dependencies
```bash
pip install -r requirements.txt
```

### 4. Run the Application
```bash
python app.py
```
### 5. Open Your Browser and Visit  
**http://127.0.0.1:5000/**  

---

## Deployment on Render  

Easily deploy your project live using **Render**:  

**1. Push your project** to GitHub
**2. Create a new Web Service** on [Render](https://render.com) 
**3. Connect your GitHub repository**
**4. Configure the settings:**  
   - **Environment:** Python 3  
   - **Build Command:**  
     ```bash
     pip install -r requirements.txt
     ```  
   - **Start Command:**  
     ```bash
     gunicorn app:app
     ```  
**5.** Click **Deploy** 
**6.** After successful deployment, Render will provide you with a **Live URL**  

**Example Live App:** [Student Performance Indicator](https://student-performance-indicator-zs7g.onrender.com/)  
