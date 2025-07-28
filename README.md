# 🏏 Decoding the Sixes: An Analytical Deep Dive into the T20 World Cup 2024

![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python)
![Pandas](https://img.shields.io/badge/Pandas-2.x-blue?style=for-the-badge&logo=pandas)
![MySQL](https://img.shields.io/badge/MySQL-8.x-blue?style=for-the-badge&logo=mysql)
![Seaborn](https://img.shields.io/badge/Seaborn-0.12-blue?style=for-the-badge&logo=seaborn)

---

### 📖 Project Overview

From nail-biting finishes to dominant performances, the ICC Men's T20 World Cup 2024 was a spectacle of skill and strategy. This analysis goes beyond the highlights to explore the data-driven narratives that defined the tournament. Using a combination of SQL for data extraction and Python libraries like Pandas, Matplotlib, and Seaborn for analysis, this project dissects match results, player heroics, and tactical trends to reveal which teams and individuals truly conquered the pitch. [cite: Decoding_The_Sixes.ipynb]

---

### ❓ Key Questions Analyzed

This analysis sought to answer a range of questions to uncover the tournament's key dynamics:
1.  Which teams secured the most victories?
2.  How was the match distribution across the different venues?
3.  What were the average first innings scores at each stage of the tournament?
4.  Which players achieved the highest individual scores?
5.  How significantly did the toss decision impact the match outcome?
6.  What was the distribution of winning margins (by Runs vs. Wickets)?
7.  Which players were most frequently named Player of the Match?
8.  Who were the leading wicket-takers?
9.  How did the average first and second innings scores compare?

---

### 📊 Key Insights & Findings

The analysis of the T20 World Cup 2024 data has revealed several key narratives:

* **🏆 Team Dominance:** **India** and **South Africa** were the tournament's front-runners, each with 8 wins. **Afghanistan** also had a remarkable campaign with 6 victories. [cite: Decoding_The_Sixes.ipynb]

* **🪙 The Decisive Toss:** The coin toss proved to be a significant factor. Teams choosing to **field first** won an overwhelming **82.1%** of the matches, highlighting a clear strategic advantage in chasing. [cite: Decoding_The_Sixes.ipynb]

* **⭐ Standout Performers:**
    * **Nicholas Pooran** stood out with the bat, recording the highest individual score of the tournament (**98 runs**). [cite: Decoding_The_Sixes.ipynb]
    * **Fazalhaq Farooqi** was arguably the most impactful player, earning the most **Player of the Match awards (3)** and finishing as the joint **top wicket-taker (11 wickets)** alongside **Rashid Khan**. [cite: Decoding_The_Sixes.ipynb]

* **🏏 Scoring Trends:** The tournament saw a dramatic fluctuation in scoring, with the **Final** producing the highest average first innings score (**176**), while the **1st Semi-Final** saw a surprising collapse with an average of just **56**. [cite: Decoding_The_Sixes.ipynb]

---

### 📈 Visualizations Showcase

<table>
  <tr>
    <td align="center"><strong>Toss Decision Impact</strong></td>
    <td align="center"><strong>Average Score per Stage</strong></td>
  </tr>
  <tr>
    <td><img src="path/to/your/toss_decision_plot.png" alt="Toss Decision Pie Chart" width="400"></td>
    <td><img src="path/to/your/avg_score_plot.png" alt="Average Score Line Chart" width="400"></td>
  </tr>
    <tr>
    <td align="center"><strong>Player of the Match Awards</strong></td>
    <td align="center"><strong>Top Wicket Takers</strong></td>
  </tr>
   <tr>
    <td><img src="path/to/your/potm_plot.png" alt="Player of the Match Bar Chart" width="400"></td>
    <td><img src="path/to/your/wickets_plot.png" alt="Top Wicket Takers Bar Chart" width="400"></td>
  </tr>
</table>

*Note: To display these images, save your plots as `.png` files and replace `path/to/your/plot.png` with the correct file paths in your repository.*

---

### 🛠️ Tech Stack & Libraries

* **Database:** `MySQL`
* **Data Manipulation & Analysis:** `Python`, `Pandas`, `SQLAlchemy`
* **Data Visualization:** `Matplotlib`, `Seaborn`
* **File Export:** `Openpyxl`

---

### ⚙️ How to Run This Project

To run this analysis on your local machine, follow these steps:

1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/your-username/Decoding_The_Sixes.git](https://github.com/your-username/Decoding_The_Sixes.git)
    cd Decoding_The_Sixes
    ```

2.  **Set up a Python Environment:**
    It is recommended to use a virtual environment to manage dependencies.
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3.  **Install Dependencies:**
    Install the required libraries from the `requirements.txt` file.
    ```bash
    pip install -r requirements.txt
    ```
    *(If you don't have a `requirements.txt` file, you can create one using `pip freeze > requirements.txt`)*

4.  **Database Setup:**
    * Ensure you have a local MySQL server running.
    * Create a new database and import the T20 World Cup 2024 dataset into a table (e.g., `t20_worldcup`).
    * Update the database connection string in the Jupyter Notebook to match your credentials:
        ```python
        # Update with your MySQL username, password, host, and database name
        engine = create_engine("mysql+pymysql://user:password@localhost/database_name")
        ```

5.  **Run the Notebook:**
    Launch Jupyter Notebook and open the `Decoding_The_Sixes.ipynb` file to view and run the analysis.
    ```bash
    jupyter notebook
    ```

---

### 🚀 Future Analysis

This project provides a solid foundation, but further analysis could yield even deeper insights:

* **Venue-Specific Toss Impact:** Does the "field first" advantage hold true across all venues?
* **Performance in Knockout vs. Group Stages:** How did player and team performances change under pressure?
* **Bowler Economy Rates:** Who were the most economical bowlers?
* **Batsman Strike Rates:** Which batsmen had the most impactful strike rates?

---

### 💬 Connect with Me

Feel free to connect with me on social media:

- **GitHub:** [github.com/NaveenKumar1822](https://github.com/NaveenKumar1822)
- **LinkedIn:** [linkedin.com/in/naveen840/](https://linkedin.com/in/naveen840/)
- **Instagram:** [naveentheog](https://www.instagram.com/naveentheog/)

---
**Author:** Naveen Kumar K