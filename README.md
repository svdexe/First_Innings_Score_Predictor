# 🏏 IPL First Innings Score Predictor

<div align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white" alt="Flask">
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" alt="Scikit-learn">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3">
</div>

<div align="center">
  <h3>🎯 Predict IPL cricket scores with Machine Learning precision</h3>
  <p>A sleek web application that predicts first innings scores for Indian Premier League matches using advanced regression algorithms.</p>
</div>

---

## ✨ Features

- **🤖 Machine Learning Powered** - Uses Linear Regression, Ridge, and Lasso models
- **🎨 Modern UI/UX** - Sleek gradient design with smooth animations
- **📱 Responsive Design** - Works seamlessly across all devices
- **⚡ Real-time Predictions** - Instant score predictions based on match situation
- **🏆 IPL Team Support** - Covers all major IPL franchises

## 🚀 Live Demo

[View Live Application](your-heroku-app-url) • [API Documentation](link-to-docs)

## 📸 Screenshots

<div align="center">
  <img src="screenshot1.png" alt="Home Page" width="45%">
  <img src="screenshot2.png" alt="Prediction Result" width="45%">
</div>

## 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| **Python** | Backend development |
| **Flask** | Web framework |
| **Scikit-learn** | Machine learning models |
| **Pandas** | Data manipulation |
| **NumPy** | Numerical computing |
| **HTML/CSS** | Frontend design |
| **JavaScript** | Interactive elements |

## 📊 Model Performance

| Model | MAE | MSE | RMSE | R² Score |
|-------|-----|-----|------|----------|
| Linear Regression | 15.2 | 284.5 | 16.9 | 0.842 |
| Ridge Regression | 14.8 | 278.3 | 16.7 | 0.846 |
| Lasso Regression | 15.0 | 281.2 | 16.8 | 0.844 |

## 🔧 Installation & Setup

### Prerequisites
- Python 3.7+
- pip package manager

### Quick Start

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/ipl-score-predictor.git
   cd ipl-score-predictor
   ```

2. **Create virtual environment**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the application**
   ```bash
   python app.py
   ```

5. **Open your browser**
   ```
   http://localhost:5000
   ```

## 📁 Project Structure

```
ipl-score-predictor/
├── 📄 app.py                          # Flask application
├── 🤖 first-innings-score-lr-model.pkl # Trained ML model
├── 📊 First Innings Score Prediction - IPL.py # Model training script
├── 🎨 templates/
│   ├── index.html                     # Home page
│   └── result.html                    # Results page
├── 🖼️ static/
│   ├── images/                        # Team logos
│   └── favicon.ico                    # Site icon
├── 📊 ipl.csv                         # Training dataset
└── 📋 requirements.txt                # Dependencies
```

## 🎯 How It Works

1. **Data Input** - User selects batting/bowling teams and enters match statistics
2. **Feature Engineering** - Categorical variables are one-hot encoded
3. **Prediction** - Trained model predicts the final score
4. **Result Display** - Shows predicted score range with confidence interval

### Input Parameters
- 🏏 **Batting Team** - Team currently batting
- 🥎 **Bowling Team** - Team currently bowling  
- ⏰ **Overs** - Current over (≥ 5.0)
- 🏃 **Runs** - Current runs scored
- 🚫 **Wickets** - Current wickets fallen
- 📊 **Last 5 Overs Stats** - Runs and wickets in previous 5 overs

## 🏆 Supported Teams

<div align="center">
  <table>
    <tr>
      <td>🔵 Mumbai Indians</td>
      <td>🟡 Chennai Super Kings</td>
      <td>🔴 Royal Challengers Bangalore</td>
      <td>🟣 Kolkata Knight Riders</td>
    </tr>
    <tr>
      <td>🟠 Sunrisers Hyderabad</td>
      <td>🌸 Rajasthan Royals</td>
      <td>❤️ Kings XI Punjab</td>
      <td>🔷 Delhi Daredevils</td>
    </tr>
  </table>
</div>

## 📈 Model Training

The model was trained on historical IPL data with the following steps:

1. **Data Cleaning** - Removed inconsistent teams and early overs data
2. **Feature Engineering** - One-hot encoding for categorical variables
3. **Train-Test Split** - 2008-2016 for training, 2017+ for testing
4. **Model Selection** - Compared Linear, Ridge, and Lasso regression
5. **Hyperparameter Tuning** - Grid search for optimal parameters

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgements

- **IPL** for the exciting cricket data
- **Scikit-learn** for the machine learning tools
- **Flask** for the web framework
- **Heroku** for deployment platform

## 📧 Contact

**Shivam Dali** - [LinkedIn](https://www.linkedin.com/in/shivam-dali-86b0a1201/) - [GitHub](https://github.com/svdexe)

Project Link: [https://github.com/svdexe/IPL_First_Inning_score_predictor](https://github.com/svdexe/IPL_First_Inning_score_predictor)

---

<div align="center">
  <p>Made with ❤️ and lots of ☕</p>
  <p>⭐ Star this repo if you found it helpful!</p>
</div>
