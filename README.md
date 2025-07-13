# Green City Analytics 🌳

## Project : Smart City Competition

### 📋 Project Overview
This project is focusing on data analysis and optimization for urban planning. The goal is to analyze tree data from Paris to optimize maintenance routes and urban forestry management.

### 🎯 Objectives
- Perform exploratory data analysis on Paris urban tree inventory
- Identify patterns in tree distribution across the city
- Optimize maintenance routes for city services
- Provide data-driven insights for urban planning

### 📊 Dataset
- **Source**: OpenData Paris - "Les Arbres" (Trees)
- **Size**: 200,137 tree records with 18 features
- **Key Features**: Location, species, height, circumference, planting date

### 🛠️ Technical Stack
- **Python 3.x**
- **Libraries**:
  - `pandas` - Data manipulation and analysis
  - `numpy` - Numerical computations
  - `matplotlib` - Data visualization
  - `seaborn` - Statistical graphics
  - `scikit-learn` - Machine learning utilities

### 📁 Repository Structure
```
green-city-analytics/
├── P2_01_jnotebook.ipynb    # Main analysis notebook
└── README.md                 # This file
```

### 🔍 Key Findings
1. **Tree Distribution**: 
   - 52% in street alignments
   - 23% in gardens
   - 16% in cemeteries
   
2. **Data Quality Issues**:
   - Missing values in height and circumference
   - Potential duplicates in geographical coordinates
   - Inconsistent measurements requiring cleaning

### 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/DerrazSofiane/green-city-analytics.git
   ```

2. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn jupyter
   ```

3. Open and run the notebook:
   ```bash
   jupyter notebook P2_01_jnotebook.ipynb
   ```

### 📈 Future Improvements
- Implement route optimization algorithms
- Add interactive map visualizations
- Integrate real-time maintenance data
- Develop predictive models for tree health

### 📝 Skills Demonstrated
- Data cleaning and preprocessing
- Exploratory data analysis
- Statistical analysis
- Data visualization
- Problem-solving for urban planning

---
*Note: This was an educational project. The insights and methodologies developed here can be applied to real-world urban planning and smart city initiatives.*
