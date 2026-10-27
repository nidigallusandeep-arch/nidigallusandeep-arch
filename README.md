
# 👋 Hi, I'm Sandeep!

 Aspiring Data Scientist | AI & ML Enthusiast

I am learning Python, SQL, Data Science, Machine Learning, and Deep Learning.

##  About Me
-  Learning Data Science and Deep Learning.
-  Interested in Data Analysis and Visualization.
-  Exploring Machine Learning, Deep Learning, and AI.
-  Building real-world projects.
-  Goal: Become a skilled Data Scientist.

## 🛠️ Skills
Python | SQL | Pandas | NumPy | Excel | Power BI | Machine Learning | Deep Learning

## 📂 Projects
- Python Projects
- SQL Projects
- Data Analysis Projects
- Machine Learning Projects
- Deep Learning Projects

##  My Motto
**As the discipline, so the victory.** 

*యథా క్రమశిక్షణ, తథా విజయం.*

## 🎯 My Goal
Learn every day, build real-world projects, and become a skilled Data Scientist.

⭐ Keep Learning | Keep Growing 🚀


### 🐍 Python
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

### 🗄️ SQL
![SQL](https://img.shields.io/badge/SQL-336791?style=for-the-badge&logo=mysql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

### 🐼 Pandas
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)

### 📈 Statistics
![Statistics](https://img.shields.io/badge/Statistics-4B8BBE?style=for-the-badge&logo=googleanalytics&logoColor=white)

### 📊 Power BI
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)

### 🤖 Machine Learning
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-102230?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Scikit Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)

### 📁 Projects
![Data Analytics Projects](https://img.shields.io/badge/Data%20Analytics%20Projects-1F6FEB?style=for-the-badge&logo=github&logoColor=white)
![Data Science Projects](https://img.shields.io/badge/Data%20Science%20Projects-00A67E?style=for-the-badge&logo=python&logoColor=white)

### 🎯 Interview Preparation
![SQL Interview](https://img.shields.io/badge/SQL%20Interview-336791?style=for-the-badge&logo=mysql&logoColor=white)
![Python Interview](https://img.shields.io/badge/Python%20Interview-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Data Analyst Interview](https://img.shields.io/badge/Data%20Analyst%20Interview-217346?style=for-the-badge&logo=googleanalytics&logoColor=white)

### 🔧 Tools
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter%20Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)

---
##  GitHub Streak

![GitHub Streak](https://streak-stats.demolab.com?user=nidigallusandeep-arch&theme=dark)

---

## 📈 My Goals

-  Become a skilled Data Analyst
-  Build real-world Data Analytics projects
-  Learn Machine Learning deeply
-  Improve Python & SQL skills
-  Contribute to open-source projects

---

##  Connect With Me

 Email:nidigallusandeep@gmail.com

 LinkedIn: https://www.linkedin.com/in/sandeepnidigallu

---

⭐ **Thanks for visiting my profile!**

###  Keep Learning | Keep Building | Keep Growing



name: Generate Snake Animation

on:
  schedule:
    - cron: "0 0 * * *"
  workflow_dispatch:
  push:
    branches:
      - main

permissions:
  contents: write

jobs:
  generate:
    runs-on: ubuntu-latest

    steps:
      - name: Generate contribution snake
        uses: Platane/snk@v3
        with:
          github_user_name: nidigallusandeep-arch
          outputs: |
            dist/github-snake.svg
            dist/github-snake-dark.svg?palette=github-dark

      - name: Push snake animation
        uses: crazy-max/ghaction-github-pages@v4
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}


## 🐍 Contribution Snake

![GitHub Snake](https://raw.githubusercontent.com/nidigallusandeep-arch/nidigallusandeep-arch/output/github-snake.svg)




