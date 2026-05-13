# 🎬 Netflix Data Analysis Project 📊

Welcome to my **Netflix Data Analysis** project! In this project, I performed an in-depth exploration of Netflix movies using Python 🐍 and a variety of powerful data science tools and libraries.

---

## 📁 Dataset
The dataset contains detailed metadata on movies including:
- 🎞️ **Title**
- 📅 **Release Date**
- 🔥 **Popularity**
- 🗳️ **Vote Count**
- ⭐ **Vote Average**
- 🎭 **Genres**
- 🌐 **Original Language**
- 🖼️ **Poster URL**
- 🧾 **Overview**

---

## 🧰 Tools & Libraries Used

| Purpose             | Libraries/Tools Used |
|---------------------|----------------------|
| 📥 Data Handling    | `pandas`, `numpy`    |
| 🧹 Data Cleaning    | `pandas`, `numpy`    |
| 📊 Data Visualization | `matplotlib`, `seaborn` |
| 🧠 Data Analysis    | Custom Python functions for categorization and transformation |

---

## 🧹 Data Cleaning Steps

✔️ Removed unnecessary columns like `Overview`, `Original Language`, and `Poster URL`  
✔️ Handled missing values and incorrect datatypes  
✔️ Categorized `Vote_Average` into 4 groups:  
- 🟢 `popular`
- 🟡 `average`
- 🔴 `below_avg`
- ⚫ `not_popular`

✔️ Exploded multi-genre entries into single-genre rows  
✔️ Converted datatypes for memory optimization

---

## 📈 Visualizations

🔎 Answered several key questions using beautiful and informative charts:
- 📌 **Most frequent genre** (🎭 *Drama* topped the list!)
- 🎯 **Most popular movie** (*Spider-Man: No Way Home* with highest popularity 💥)
- 🗓️ **Year with most released movies**
- 🧮 **Genres with highest vote count**

All visualizations were created using `matplotlib` and `seaborn`.

---

## 🔍 Key Insights

✨ **Drama** is the most frequent genre, appearing in over **14%** of entries  
✨ **Spider-Man: No Way Home** is the most popular movie in the dataset  
✨ The dataset spans a wide range of genres and vote patterns  
✨ Cleaned and optimized dataset has **25,000+** rows after genre explosion

---

## 📌 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/netflix-data-analysis.git
   cd netflix-data-analysis
2.Install dependencies:

pip install -r requirements.txt

3.Run the notebook or script:

jupyter notebook netflix_analysis.ipynb

💬 Feedback
If you liked this project or have suggestions for improvements, feel free to ⭐ star the repo or open an issue.

🙏 Thank You!
Thanks for checking out this project!
Made with ❤️ by Lakshya Shukla
