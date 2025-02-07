# datafun-04-eda-
# Module 4 - Fundamentals of Data Analytics

##**Summary:**
This Jupyter notebook investigates the relationship between sepal size and petal size across three species of Iris: Setosa, Versicolor, and Virginica. The analysis focuses on how the sepal area, derived from sepal length and sepal width, impacts petal width, petal length, and petal area.

##**Key Insights:**
Setosa: Generally smaller has the largest sepal width of all the species. Increases in sepal area have minimal effect on petal length and width, and no effect on petal area.

Versicolor and Virginica: Both species show a positive trend and noticeable correlation between larger sepal area and larger petal dimensions (width, length, and area).

The exploratory data analysis (EDA) includes data cleaning, descriptive statistics, data visualization, analysis, and storytelling. The results support the hypothesis that larger sepal width is associated with larger petal area for Versicolor and Virginica.


##**How to run the project yourself**

**Cloned and Opened my Github project**
- cd \Projects
- git clone https://github.com/dennykami1/datafun-04-eda-
- cd datafun-04-eda-
- code .

**Created a .gitignore file, and pasted in contents from example**
      #Python virtual environment
      .venv/

      #Visual Studio Code settings and workspace
      .vscode/

      # Compiled Python files
      __pycache__/

      # macOS system files
      .DS_Store

**Commited Changes to Github**
- git add .
- git commit -m "Add .gitignore"
- git push -u origin main

**Created Virtual Environment and Activated**
- Commited Changes to Github
- py -m venv .venv
- .venv\Scripts\activate

**Upgrade pip & install requirements.txt**
- py -m pip install --upgrade pip setuptools wheel
- py -m pip install -r requirements.txt

**Created Jupyter Notebook and Selected Kernel**
- added new file with extension .ipynb
- Opened and selected Notebook Kernel .venv
