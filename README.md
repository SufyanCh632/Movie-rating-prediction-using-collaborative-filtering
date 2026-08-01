# 🎬 Movie Recommendation System using Collaborative Filtering (SVD)

## 📌 Project Overview

This project implements a **Movie Recommendation System** using **Collaborative Filtering** with the **Singular Value Decomposition (SVD)** algorithm from the **Surprise** library. The model is trained on the MovieLens ratings dataset to predict user preferences and recommend movies based on historical ratings.

---

## 🚀 Features

* Load and preprocess the MovieLens ratings dataset.
* Train a recommendation model using the SVD algorithm.
* Split data into training and testing sets.
* Evaluate model performance using RMSE.
* Predict ratings for specific users and movies.
* Visualize the distribution of movie ratings.

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-Surprise
* Matplotlib
* Seaborn

---

## 📂 Dataset

The project uses the **MovieLens Ratings Dataset**.

**Dataset Columns:**

* `userId` – Unique user identifier
* `movieId` – Unique movie identifier
* `rating` – User rating (1–5)
* `timestamp` – Time when the rating was given

---

## 📁 Project Structure

```text
Movie-Recommendation-System/
│
├── ratings.csv
├── movie_recommendation.py
├── README.md
└── requirements.txt
```

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/Movie-Recommendation-System.git
```

Navigate to the project folder:

```bash
cd Movie-Recommendation-System
```

Install the required packages:

```bash
pip install pandas numpy matplotlib seaborn scikit-surprise
```

---

## ▶️ Usage

Run the Python script:

```bash
python movie_recommendation.py
```

The program will:

1. Load the MovieLens dataset.
2. Train an SVD recommendation model.
3. Evaluate the model using RMSE.
4. Predict a user's rating for a selected movie.
5. Display a histogram of movie ratings.

---

## 📊 Model Evaluation

The model is evaluated using **Root Mean Squared Error (RMSE)**.

Lower RMSE values indicate better prediction accuracy.

Example output:

```text
RMSE: 0.89
Predicted Rating for User 196 on Movie 492: 4.23
```

---

## 📈 Visualization

The project generates a histogram showing the distribution of movie ratings, helping understand user rating behavior.

---

## 💡 Future Improvements

* Recommend Top-N movies for each user.
* Add Content-Based Filtering.
* Build a Hybrid Recommendation System.
* Develop a web interface using Flask or Streamlit.
* Deploy the model online.

---

## 📚 Learning Outcomes

Through this project, you will learn:

* Recommendation system fundamentals
* Collaborative Filtering techniques
* Matrix Factorization with SVD
* Model evaluation using RMSE
* Data preprocessing with Pandas
* Data visualization with Seaborn and Matplotlib

---

## 🤝 Contributing

Contributions, suggestions, and improvements are welcome. Feel free to fork the repository and submit a pull request.

---

## 📄 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Muhammad Suffiyan Rafi**

**Dataset** got from MovieGo

* GitHub: https://github.com/SufyanCh632
