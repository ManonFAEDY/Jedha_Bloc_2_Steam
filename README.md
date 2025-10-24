# 🎮 Steam Marketplace Analysis

[![Python](https://img.shields.io/badge/Python-3.11+-blue.svg)](https://www.python.org/downloads/)
[![Spark](https://img.shields.io/badge/Apache%20Spark-3.0+-orange.svg)](https://spark.apache.org/)
[![Databricks](https://img.shields.io/badge/Databricks-free-red.svg)](https://databricks.com/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

> **Global analysis of the Steam marketplace to understand video game ecosystem trends**

## 📋 Table of Contents
- [Context](#-context)
- [Project Objective](#-project-objective)
- [Data](#-data)
- [Technologies](#-technologies)
- [Project Structure](#-project-structure)
- [Installation](#-installation)
- [Methodology](#-methodology)
- [Key Insights](#-key-insights)
- [Visualizations](#-visualizations)
- [Future Improvements](#-future-improvements)
- [Author](#-author)

---

## 🎯 Context

**Steam** is a digital distribution service and online store developed by Valve Corporation. Launched in September 2003, Steam has become the world's largest PC gaming platform, offering:
- 🎮 Automated game updates
- 🔐 Digital Rights Management (DRM)
- 🌐 Game server matchmaking and Valve Anti-Cheat measures
- 👥 Social networking and game streaming
- ☁️ Cloud storage for game progress
- 🛒 Virtual marketplace for collectible items

With **thousands of games** available and **millions of active users**, Steam represents a critical ecosystem for understanding the video game industry.

---

## 🚀 Project Objective

**Client**: Ubisoft, a leading French video game publisher

**Mission**: Conduct a comprehensive analysis of games available on the Steam marketplace to support the launch of a revolutionary new game.

### Key Questions
- 📊 What are the current trends in the video game industry?
- 🎯 Which game genres are most popular?
- 💰 What are the pricing strategies?
- ⭐ What factors influence game ratings and success?
- 🌍 How does the gaming market vary globally?
- 🕹️ What features do successful games have in common?

### Deliverables
- Comprehensive data analysis of Steam marketplace
- Actionable insights for game development strategy
- Market positioning recommendations
- Trend identification and forecasting

---

## 📊 Data

### Source
**Steam Marketplace** dataset containing comprehensive information about games available on the platform.

### File
| File | Description |
|------|-------------|
| `steam_game_output.json` | JSON dataset with detailed game information |

### Data Features
The dataset includes:
- **Game metadata**: Title, developer, publisher, release date
- **Pricing**: Original price, discounts, regional pricing
- **Ratings**: User reviews, metacritic scores
- **Categories**: Genres, tags, features
- **Technical specs**: System requirements, supported platforms
- **Engagement metrics**: Number of reviews, playtime statistics
- **Content**: Descriptions, screenshots, videos

---

## 🛠️ Technologies

### Platform
- **Databricks Community Edition** (Cloud-based analytics platform)
- **Apache Spark 3.0+** (Distributed computing framework)

### Languages & Libraries
```python
pyspark              # Distributed data processing
pandas               # Data manipulation
matplotlib           # Static visualizations
seaborn              # Statistical visualizations
plotly               # Interactive visualizations
numpy                # Numerical computing
```

### Big Data Stack
- **Spark SQL**: Structured data queries
- **Spark DataFrame API**: Data transformations
- **Databricks notebooks**: Interactive analysis environment

---

## 📁 Project Structure

```
steam-marketplace-analysis/
│
├── 📓 Steam_databricks.ipynb            # Main analysis notebook (Databricks)
├── 📊 steam_game_output.json            # Raw dataset
├── 📝 README.md                         # This file
├── 📝 Steam_databricks.lnk              # Link to Public Notebook on Databricks Community Edition
├── 🖼️ img/                              # Doc with exported charts and graphs

```

---

## 💻 Installation

### Option 1 : Databricks Community Edition

**Click on the link to open the notebook in Databricks Community Edition**
   - [Public Notebook on Databricks Community Edition](https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/12985744048688/658096807172125/11395721381550/latest.html)

### Option 2: Databricks Free Edition

1. **Create a Databricks account**
   - Go to [Databricks Free Edition](https://www.databricks.com/fr/learn/free-edition)
   - Sign up for free

2. **Import the notebook**
   - Click "Import" in Databricks workspace
   - Upload `Steam_databricks.ipynb`

3. **Upload the dataset**
   - Go to "Data" tab
   - Upload `steam_game_output.json`

4. **Run the notebook**
   - Attach notebook to cluster
   - Execute cells sequentially

---

## 🔬 Methodology

### 1. Data Ingestion & Exploration
- Load JSON data into Spark DataFrame
- Schema analysis and data profiling
- Initial data quality assessment
- Missing value detection

### 2. Data Cleaning & Preprocessing
- Handle missing values and duplicates
- Standardize data formats (dates, prices)
- Parse nested JSON structures
- Feature extraction and engineering

### 3. Exploratory Data Analysis (EDA)
- **Genre Analysis**: Distribution and popularity
- **Pricing Strategy**: Price ranges, discount patterns
- **Rating Analysis**: Correlation with success metrics
- **Temporal Trends**: Release patterns over time
- **Platform Distribution**: Windows, Mac, Linux support

### 4. Visualization & Insights
- Create compelling visualizations
- Extract actionable insights
- Formulate strategic recommendations

---

## 🛠️ Technical Challenges Addressed

- **Big Data Processing**: Efficient handling of large JSON dataset with Spark
- **Nested Data Structures**: Parsing complex JSON hierarchies
- **Data Quality**: Handling missing values and inconsistencies
- **Scalability**: Leveraging distributed computing for performance
- **Visualization**: Creating informative charts from large datasets

---

## 📚 Key Technologies Explained

### Why Databricks?
- Cloud-based collaborative environment
- Built-in Spark optimization
- Free community edition available
- Notebook version control

### Why Spark?
- Handles large-scale data processing
- In-memory computing for speed
- Scalable architecture
- Industry-standard for big data

---

## 👤 Author

**[Manon FAEDY]**
- 🐙 [GitHub](https://github.com/ManonFAEDY)

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 🙏 Acknowledgments

- **Jedha** for the online trainings
- **Valve Corporation** for the Steam platform
- **Databricks Community** for free cloud platform
- **Apache Spark** for distributed computing framework
- **Ubisoft** for the project opportunity

---

<div align="center">
  <strong>⭐ If this analysis was helpful, don't forget to star the repository! ⭐</strong>
</div>
