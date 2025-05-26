# World-Happiness-Report
**🌍 World Happiness Report**

**📌 Overview**

The World Happiness Report is an annual publication analyzing global happiness and well-being trends. It ranks countries based on indicators such as GDP per capita, social support, life expectancy, freedom, generosity, and corruption perceptions.

**📂 Data Format**

The dataset is provided in CSV format, including the following attributes:
- Country – Name of the country
- Happiness Score – Overall ranking based on survey responses
- GDP per Capita – Economic influence on happiness
- Social Support – Strength of family and community ties
- Life Expectancy – Health factors affecting well-being
- Freedom to Make Choices – Personal autonomy and governance impact
- Generosity – Charitable giving and community engagement
- Perceptions of Corruption – Trust in public institutions
- 
**🔧 Installation**

Clone the repository to start analyzing global happiness trends:
git clone https://github.com/yourusername/World-Happiness-Report.git
cd World-Happiness-Report


**📊 Usage Example**

Load and visualize happiness data in Python:
import pandas as pd
import matplotlib.pyplot as plt  

data = pd.read_csv("World_Happiness_Data.csv")  
print(data.head())  

plt.scatter(data["GDP per Capita"], data["Happiness Score"])  
plt.title("Happiness vs. GDP per Capita")  
plt.xlabel("GDP per Capita")  
plt.ylabel("Happiness Score")  
plt.show()


**🤝 Contributions**

We welcome contributions! If you have additional datasets or improved analysis models, feel free to submit a pull request.

**📜 License**

This project is licensed under the MIT License. See the LICENSE file for details

