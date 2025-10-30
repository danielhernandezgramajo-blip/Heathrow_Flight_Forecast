# ✈️ Heathrow Flight Forecast

This project analyzes flight data and uses an **ARIMA model** to forecast daily flight arrivals at **London Heathrow Airport**.  
The model predicts flight arrivals **two weeks ahead** based on the patterns observed in September 2023.

---

## 📊 Project Structure

- `Cleaning_&_EDA.ipynb` → Data cleaning, preprocessing, and exploratory analysis.
- `ATMProject_ARIMA.ipynb` → ARIMA modeling, diagnostics, and forecast visualization.

---

## 🔍 Key Findings
- No duplicate rows found after data cleaning.  
- All time columns converted successfully to datetime.  
- Potential outliers detected in “Actual Distance Flown (NM)”.  
- ARIMA(5,0,2) chosen as the best configuration for short-term forecasting.  
- Forecast visualizations show consistent patterns with the training data.

---

## 🧠 Model Summary
The ARIMA(5,0,2) model produced the lowest AIC and provided a realistic short-term forecast.  
Residual diagnostics confirmed stable variance and normally distributed residuals.

---

## 📈 Results
The model forecasts the next 14 days of flight arrivals with a stable confidence interval.  
![Forecast Example](https://via.placeholder.com/800x400?text=Forecast+Graph)

---

## ⚙️ Technologies Used
- Python (Pandas, NumPy, Matplotlib, Statsmodels)
- Google Colab
- GitHub Desktop for version control
