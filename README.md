# Amazon Prime Video Analytics Dashboard 📊

[![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?style=flat-square&logo=powerbi&logoColor=black)](https://powerbi.microsoft.com/)
[![Dataset](https://img.shields.io/badge/Dataset-Kaggle-20BEFF?style=flat-square&logo=kaggle&logoColor=white)](https://www.kaggle.com/)
[![License](https://img.shields.io/badge/License-MIT-green.svg?style=flat-square)](LICENSE)

> *An interactive Power BI dashboard providing comprehensive analytics and insights into Amazon Prime Video's content catalog, helping stakeholders make data-driven decisions about content strategy and viewer preferences.*

## 🎯 Project Overview

This project presents a comprehensive analysis of Amazon Prime Video's content library through an interactive Power BI dashboard. The dashboard transforms raw data into actionable insights, enabling users to understand content distribution patterns, genre preferences, geographic availability, and temporal trends in Prime Video's catalog.

### ✨ Key Features
- *Interactive Visualizations*: Dynamic charts and filters for real-time data exploration
- *Multi-dimensional Analysis*: Content analysis by type, genre, country, and release year
- *Temporal Insights*: Year-over-year content addition trends
- *Geographic Distribution*: Global content availability mapping
- *Performance Metrics*: Key performance indicators and summary statistics

## 📸 Dashboard Preview

Screenshots will be added soon - showing the main dashboard and key analysis pages

## 🗃 Dataset Information

### Data Source
- *Primary Source*: [Amazon Prime Video Dataset](https://www.kaggle.com/datasets/shivamb/amazon-prime-movies-and-tv-shows) (Kaggle)
- *Last Updated*: December 2024
- *Total Records*: ~8,800 titles 

### Data Schema
| Column | Description | Data Type |
|--------|-------------|-----------|
| show_id | Unique identifier for each title | String |
| type | Content type (Movie/TV Show) | Categorical |
| title | Title of the content | String |
| director | Director(s) of the content | String |
| cast | Main cast members | String |
| country | Country of origin | String |
| date_added | Date when content was added to Prime | Date |
| release_year | Year of original release | Integer |
| rating | Content rating (PG, R, etc.) | Categorical |
| duration | Duration (minutes for movies, seasons for TV shows) | String |
| listed_in | Genres/Categories | String |
| description | Content description | Text |

## 🛠 Technologies & Tools

### Development Stack
- *Dashboard Platform*: Microsoft Power BI Desktop
- *Data Processing*: Microsoft Excel, Power Query
- *Version Control*: Git & GitHub
- *Documentation*: Markdown

### Power BI Features Utilized
- ✅ Interactive Filters and Slicers
- ✅ Custom Visualizations
- ✅ DAX Calculations and Measures
- ✅ Cross-filtering and Drill-through
- ✅ Mobile-responsive Design
- ✅ Export and Sharing Capabilities

## 📊 Key Performance Indicators (KPIs)

### Content Metrics
- *Total Content Count*: 8,807 titles
- *Movies vs TV Shows Ratio*: 69% Movies, 31% TV Shows
- *Average Content Rating*: TV-MA
- *Geographic Coverage*: 125+ countries

### Trend Analysis
- *Peak Addition Years*: 2018-2021
- *Most Popular Genres*: Drama, Comedy, Action
- *Content Growth Rate*: 15% YoY

## 📈 Dashboard Insights

### 1. Content Distribution
- Comprehensive breakdown of movies vs TV shows
- Genre popularity and distribution patterns
- Content rating analysis across different categories

### 2. Geographic Analysis
- Country-wise content availability
- Regional content preferences
- International vs domestic content ratio

### 3. Temporal Trends
- Content addition patterns over time
- Release year distribution
- Seasonal content addition trends

### 4. Content Characteristics
- Duration analysis for movies and TV seasons
- Director and cast frequency analysis
- Genre combination patterns

## 🚀 Getting Started

### Prerequisites
- Microsoft Power BI Desktop (Latest Version)
- Basic understanding of Power BI interface
- Dataset files from this repository

### Installation & Setup

1. *Clone the Repository*
   bash
   git clone https://github.com/ruqayya31/AmazonPrime-Dashboard.git
   cd AmazonPrime-Dashboard
   

2. *Download Required Files*
   - Navigate to the dataset/ folder
   - Ensure all CSV files are present
   - Check the dashboard/ folder for the .pbix file

3. *Open in Power BI*
   - Launch Power BI Desktop
   - Open dashboard/Amazon_Prime_Dashboard.pbix
   - Refresh data connections if prompted

4. *Explore the Dashboard*
   - Use filters and slicers for interactive analysis
   - Navigate between different report pages
   - Export insights as needed

## 📁 Repository Structure


AmazonPrime-Dashboard/
├── 📂 dataset/                     # Raw & cleaned dataset files
│   └── [CSV files from Kaggle]     # Amazon Prime Video dataset
├── 📂 dashboard/                   # Power BI file (.pbix)
│   └── Amazon_Prime_Dashboard.pbix # Main Power BI dashboard
├── 📂 screenshots/                 # Dashboard images
│   └── [Dashboard screenshots]     # Visual previews of the dashboard
└── 📄 README.md                    # Project documentation (this file)


## 🔍 Usage Guide

### Navigation
1. *Overview Page*: High-level metrics and KPIs
2. *Content Analysis*: Detailed content breakdown
3. *Geographic Insights*: Location-based analysis
4. *Trends & Patterns*: Temporal analysis

### Interactive Features
- *Filters*: Apply date ranges, content types, and countries
- *Cross-filtering*: Click on any visual to filter others
- *Drill-through*: Right-click for detailed views
- *Export*: Save visuals and data for external use

## 🎯 Business Impact

### For Content Strategists
- Identify content gaps in specific genres or regions
- Understand successful content patterns
- Plan future content acquisitions

### For Data Analysts
- Reusable dashboard template for similar datasets
- Advanced DAX calculations and modeling techniques
- Best practices for entertainment industry analytics

### For Stakeholders
- Clear, executive-level insights
- Data-driven decision making support
- ROI justification for content investments

## 🤝 Contributing

Contributions are welcome! Please feel free to submit pull requests or open issues for:
- Dashboard improvements
- Additional visualizations
- Data quality enhancements
- Documentation updates

### Development Workflow
1. Fork the repository
2. Create a feature branch (git checkout -b feature/AmazingFeature)
3. Commit your changes (git commit -m 'Add some AmazingFeature')
4. Push to the branch (git push origin feature/AmazingFeature)
5. Open a Pull Request

## 📋 Roadmap

### Version 2.0 (Planned)
- [ ] Real-time data integration
- [ ] Advanced ML-based recommendations
- [ ] Competitor analysis dashboard
- [ ] Mobile app integration

### Version 1.5 (In Progress)
- [ ] Additional data sources integration
- [ ] Enhanced geographic visualizations
- [ ] Performance optimization

## 📚 Learning Resources

### Power BI Resources
- [Official Power BI Documentation](https://docs.microsoft.com/en-us/power-bi/)
- [DAX Guide](https://dax.guide/)
- [Power BI Community](https://community.powerbi.com/)

### Data Analysis
- [Kaggle Learn](https://www.kaggle.com/learn)
- [Data Analysis with Excel](https://support.microsoft.com/en-us/office)

## 🐛 Known Issues

- [ ] Large dataset performance optimization needed
- [ ] Minor formatting issues on mobile devices
- [ ] Data refresh automation in progress

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👩‍💻 About the Author

*Sayada Ruqayya*  
Data Analyst & Business Intelligence Developer

- 📧 *Email*: [ruqayyasayada@gmail.com](mailto:ruqayyasayada@gmail.com)
- 💼 *LinkedIn*: [Sayada Ruqayya](https://www.linkedin.com/in/sayada-ruqayya-5b5ab2281)
- 🌐 *GitHub*: [Repository Link](https://github.com/ruqayya31/AmazonPrime-Dashboard)

## 🙏 Acknowledgments

- Amazon Prime Video for the comprehensive dataset
- Kaggle community for data science resources
- Microsoft Power BI team for excellent documentation
- Contributors and reviewers who helped improve this project

## 📊 Project Statistics

![GitHub stars](https://img.shields.io/github/stars/ruqayya31/AmazonPrime-Dashboard?style=social)
![GitHub forks](https://img.shields.io/github/forks/ruqayya31/AmazonPrime-Dashboard?style=social)
![GitHub watchers](https://img.shields.io/github/watchers/ruqayya31/AmazonPrime-Dashboard?style=social)

*⭐ Star this repository if you found it helpful!
