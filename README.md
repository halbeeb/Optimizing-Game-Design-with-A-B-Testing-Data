🎮 Optimizing Game Design with A/B Testing
Striking the perfect balance between player engagement and monetization through data-driven insights.


(Replace the placeholder link above with your custom image/banner)

Table of Contents
📌 Project Overview
📊 Metrics and Methodology
🧰 Repository Contents
🚀 How to Use
🔍 Key Insights and Findings
📈 Visualizations
🌟 Purpose and Future Scope
🤝 Contributing
📧 Contact
📌 Project Overview
In the dynamic world of game development, balancing player engagement with monetization is a critical challenge. Over-monetizing risks alienating players, while focusing solely on engagement may fail to generate revenue.

This project explores how A/B testing was used to optimize a specific in-game mechanic for:

📈 Boosting player engagement.
💰 Enhancing monetization opportunities without disrupting gameplay.
We analyzed the impact of new game mechanics by comparing control and test groups with robust statistical methods, offering actionable insights to developers and stakeholders.

📊 Metrics and Methodology
Key Metrics
Engagement Score
Reflects player involvement based on:

Number of sessions.
Time spent in-game.
Actions per session.
Formula:

𝐸
𝑛
𝑔
𝑎
𝑔
𝑒
𝑚
𝑒
𝑛
𝑡
 
𝑆
𝑐
𝑜
𝑟
𝑒
=
Sessions
+
Time Spent
+
Actions Per Session
3
Engagement Score= 
3
Sessions+Time Spent+Actions Per Session
​
 
Monetization Score (Primary Metric)
Measures player revenue contribution via:

Number of purchases.
Average purchase value.
Formula:

𝑀
𝑜
𝑛
𝑒
𝑡
𝑖
𝑧
𝑎
𝑡
𝑖
𝑜
𝑛
 
𝑆
𝑐
𝑜
𝑟
𝑒
=
Purchases
×
Average Purchase Value
10
Monetization Score= 
10
Purchases×Average Purchase Value
​
 
Methodology
Hypothesis Testing:
Primary Hypothesis: New mechanics will increase monetization.
Secondary Hypothesis: New mechanics will enhance engagement.
Power Analysis: Ensured statistical robustness with effect size and sample size calculations.
Experiment Design:
Control Group: Current mechanics.
Test Group: Enhanced mechanics designed to increase engagement and spending.
🧰 Repository Contents
File	Description
Optimizing Game Design with Data.ipynb	Jupyter Notebook with analysis and visualizations.
Control_Group_Data.csv	Dataset for the control group.
Test_Group_Data.csv	Dataset for the test group.
Optimizing Game Design with Data.docx	Detailed documentation on experiment design and findings.
🚀 How to Use
1. Clone the Repository
bash
Copy code
git clone https://github.com/halbeeb/Optimizing-Game-Design-with-A-B-Testing-Data.git
cd Optimizing-Game-Design-with-A-B-Testing-Data
2. Install Dependencies
Ensure Python 3.x is installed. Install required libraries via:

bash
Copy code
pip install -r requirements.txt
3. Run the Analysis
Open and run Optimizing Game Design with Data.ipynb to:

Analyze metrics.
Visualize test results.
Generate actionable insights.
🔍 Key Insights and Findings
Monetization Score (Primary Metric)
Control Mean: 1.98
Test Mean: 2.31
Improvement: Significant (Z-Score: 4.60, p-value: 0.000002)
Engagement Score (Secondary Metric)
Control Mean: 46.65
Test Mean: 48.79
Improvement: Significant (Z-Score: 39.92, p-value: 0.000000)
Takeaway: The new mechanics significantly improved both engagement and monetization metrics, confirming their effectiveness in creating a more engaging and profitable game experience.

📈 Visualizations
The repository includes rich visualizations to make insights clear and accessible:

Histograms: Engagement and monetization score distributions.
Boxplots: Compare metrics across genders and groups.
Correlation Heatmaps: Highlight relationships between metrics.
Example Visualization:

(Replace placeholder with an actual chart from your analysis)

🌟 Purpose and Future Scope
This repository serves as a blueprint for:

Game developers seeking to balance player retention with revenue generation.
Product managers optimizing in-game features using data-driven decisions.
Data scientists applying A/B testing to dynamic user environments.
Future Enhancements
Implement behavioral segmentation to tailor mechanics to casual and competitive players.
Conduct longer-term tests to assess the sustainability of improvements.
Explore machine learning for predictive analytics in player behavior.
🤝 Contributing
Contributions are welcome!

Fork the repository.
Create a new branch: git checkout -b feature-name.
Submit a pull request with a detailed explanation of your changes.
📧 Contact
👤 Author: Habeeb Abdulrasaq
📩 Email: habeebabdulrasaq@gmail.com

