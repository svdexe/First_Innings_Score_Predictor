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
  <p>A web application that predicts first innings scores for Indian Premier League matches using regression algorithms.</p>
</div>

---

## 📸 Screenshots

<div align="center">
  <img src="https://github.com/svdexe/First_Innings_Score_Predictor/blob/main/Web_Input_img.png" alt="Web Input Interface" width="90%">
  <br><br>
  <img src="https://github.com/svdexe/First_Innings_Score_Predictor/blob/main/Web_Result_Image.png" alt="Prediction Result" width="90%">
</div>

## ✨ Features

- **🤖 Machine Learning Powered** - Uses Linear Regression, Ridge, and Lasso models
- **🎨 Modern UI/UX** - Sleek gradient design with smooth animations
- **📱 Responsive Design** - Works seamlessly across all devices
- **⚡ Real-time Predictions** - Instant score predictions based on match situation

## 🛠️ Technologies Used

- **Python & Flask** - Backend web framework
- **Scikit-learn** - Machine learning models
- **Pandas & NumPy** - Data processing
- **HTML/CSS/JavaScript** - Frontend interface

## 🔧 Quick Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/svdexe/First_Innings_Score_Predictor.git
   cd First_Innings_Score_Predictor
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the application**
   ```bash
   python app.py
   ```

4. **Open browser at** `http://localhost:5000`

## 📁 Project Structure

```
├── 📄 app.py                          # Flask application
├── 🤖 first-innings-score-lr-model.pkl # Trained ML model
├── 🎨 templates/                       # HTML templates
├── 🖼️ static/                         # Static files
├── 📊 ipl.csv                         # Training dataset
└── 📋 requirements.txt                # Dependencies
```

## 🎯 How It Works

**Input Parameters:**
- 🏏 Batting & Bowling Teams  
- ⏰ Current Over (≥ 5.0)
- 🏃 Current Runs & Wickets
- 📊 Last 5 Overs Statistics

**Process:** Data → Feature Engineering → ML Prediction → Score Range Display

## 🏆 Supported Teams

Chennai Super Kings • Mumbai Indians • Royal Challengers Bangalore • Kolkata Knight Riders • Sunrisers Hyderabad • Rajasthan Royals • Kings XI Punjab • Delhi Daredevils

## 📈 Model Performance

| Model | RMSE | R² Score |
|-------|------|----------|
| Linear Regression | 16.9 | 0.842 |
| Ridge Regression | 16.7 | 0.846 |
| Lasso Regression | 16.8 | 0.844 |

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
- **CampusX** · for the comprehensive [original tutorial](https://www.youtube.com/watch?v=1YoD0fg3_EM&t=5947s) that served as the foundation for this project  




## 📧 Contact

**Shivam Dali** - [LinkedIn](https://www.linkedin.com/in/shivam-dali-86b0a1201/) - [GitHub](https://github.com/svdexe)

Project Link: [https://github.com/svdexe/IPL_First_Inning_score_predictor](https://github.com/svdexe/IPL_First_Inning_score_predictor)

---

<div align="center">
  <p>Made with ❤️ and lots of ☕</p>
  <p>⭐ Star this repo if you found it helpful!</p>
</div>
