# 🧩 A/B Test Results Analysis

## 🎯 Project Objective
The goal of this project is to perform a detailed **A/B test analysis** using Python to evaluate the impact of a design or feature change on user conversion.  
The analysis includes:
- Estimation of confidence intervals (Wilson 95% CI)
- Statistical significance testing (two-proportion z-test)
- Comparison of conversion rates between groups A and B
- Data visualization and business interpretation

---

## 🗂️ Project Structure
📁 A_B_Test_Result/
 ├── data/                         # source data files
 ├── notebooks/                    # Jupyter notebooks with analysis
 ├── docs/                         # optional documentation files
 ├── plots/                        # visualizations (images)
 ├── README.md                     # project description
 └── .gitignore                    # ignored files configuration

---

## ⚙️ Tools & Technologies
- **Python 3.x**
- **Pandas / NumPy** – data analysis and manipulation  
- **Matplotlib / Seaborn** – visualization  
- **SciPy / Statsmodels** – hypothesis testing and confidence intervals  
- **Jupyter Notebook** – interactive analytics environment  

---

## 📊 Analytical Steps
1. Data loading and preprocessing  
2. Calculation of conversion rates for groups A and B  
3. Building Wilson 95% confidence intervals  
4. Conducting a two-proportion z-test  
5. Evaluating statistical significance (p-value)  
6. Visualization of conversion results and insights  

---

## 💡 Business Insights
> Group **B** demonstrated a statistically significant increase in conversion (p < 0.05),  
> suggesting that the implemented change positively influenced user engagement.  
> Scaling the change to the entire user base is recommended after extended validation.

---

## 📈 Example Visualization
![Conversion Rates Comparison](plots/conversion_rate.png)

---

## 👨‍💻 Author
**Yauheni Vesialukha**  
Data Analyst | Business & Security Management background  
📍 Wettingen, Aargau, Switzerland  
📧 yauhenivesialukha@icloud.com  
🔗 [LinkedIn](https://www.linkedin.com/in/yauheni-vesialukha/) | [Portfolio](https://yauheni-vesialukha.netlify.app/)
