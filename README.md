# 🚗 Indian Used Car Price Prediction

![Used Car GIF](http://cdn.dribbble.com/users/1239720/screenshots/3506944/car_mg.gif)

## 📌 Overview

This project focuses on predicting the price of used cars in major Indian metro cities using machine learning. The model leverages multiple car features such as brand, fuel type, color, kilometers driven, transmission type, car age, and more. The goal is to help both buyers and sellers understand pricing dynamics and make informed decisions.

---

## 📊 Dataset

The dataset contains listings of used cars sold across Indian cities in 2023. It includes the following features:

| Feature            | Description                                |
|--------------------|--------------------------------------------|
| ID                 | Unique listing ID                          |
| Company            | Car manufacturer                           |
| Model              | Car model name                             |
| Variant            | Variant of the car                         |
| Fuel Type          | Petrol / Diesel / CNG / Electric           |
| Color              | Exterior color                             |
| Kilometer          | Kilometers driven                          |
| Body Style         | Hatchback / Sedan / SUV etc.               |
| Transmission Type  | Manual / Automatic                         |
| Manufacture Date   | Date of manufacture                        |
| Model Year         | Model year                                 |
| CngKit             | Whether CNG kit is available               |
| Owner Type         | Number of previous owners                  |
| Price              | Target variable – resale price             |
| Dealer State       | State where car is sold                    |
| Dealer Name        | Name of the dealer                         |
| City               | City of sale                               |
| Warranty           | Warranty offered by dealer                 |
| Quality Score      | Quality rating given to the car            |

---

## 📈 Key Insights

- **Price vs Demand**: Lower-priced cars attract more buyers.
- **Fuel Type**: Diesel cars tend to be priced higher than petrol.
- **Color Impact**: Common colors (white, silver) are in demand; exotic colors fetch premium prices.
- **Mileage**: Cars driven under 10,000 km usually have higher prices.
- **Body Style**: Hatchbacks, SUVs, and Sedans are most popular.
- **Car Age**: Newer cars (<5 years old) have better resale value.
- **Location Variance**: Delhi, Maharashtra, and Rajasthan have higher average prices.
- **First Owner & Warranty**: These features increase the car’s value.
- **Quality Score**: Directly impacts pricing.

---

## 🤖 Machine Learning Models

- **Decision Tree Regressor**
- **Random Forest Regressor** ✅ *(Best Performance)*

### 🔍 Feature Importance (from Random Forest):
- Car Age
- Body Style
- Manufacturer
- Kilometers Driven
- Quality Score

---

## 🧠 Tools & Libraries

- Python
- Pandas & NumPy
- Matplotlib & Seaborn (for EDA)
- Scikit-learn (for modeling)

---

## 🏁 Conclusion

This data science project effectively uses ML models to predict used car prices based on several key features. The insights derived from the data can help consumers make better decisions and enable dealerships to price their inventory strategically.

---

## 🚀 Future Work

- Deploy the model using **Streamlit** or **Flask**
- Add **model evaluation metrics** (RMSE, MAE, R²)
- Build a simple **price prediction UI**
- Integrate a live data scraping module from car listing websites

---

## 📬 Contact

For questions or collaboration:  
**Pirai Chandran**  
📧 [YourEmail@example.com]  
🌐 [GitHub/LinkedIn Profile]

