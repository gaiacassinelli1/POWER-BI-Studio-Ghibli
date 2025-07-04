# 🎥 Studio Ghibli Dashboard in Power BI

## 📌 Project Overview

This Power BI dashboard project provides a comprehensive analysis of **Studio Ghibli's filmography** focusing on **popularity**, **financial performance**, and **audience reception**. It is designed to offer both high-level insights and detailed drill-through capabilities for each film.

The project includes:

- A **user-friendly dashboard** with interactive visualizations
- A **technical data model** with well-structured relationships and DAX measures
- A **multi-source dataset** combining critic reviews, fan ratings, financial data, and metadata

---

## 🧰 Tools & Technologies

- **Power BI Desktop**
- **DAX (Data Analysis Expressions)**
- **External data sources** (Rotten Tomatoes, MyAnimeList, Box Office Mojo, Anikore, etc.)
- **Manual and automated data cleaning and transformation**

---

## 📂 Repository Contents

| File/Folder                                | Description                                                  |
|--------------------------------------------|--------------------------------------------------------------|
| `Studio Ghibli Dashboard.pbix`             | Main Power BI report file                                    |
| `Studio Ghibli Dashboard Technical Manual.docx` | Technical documentation of the data model, sources, and DAX logic |
| `Ghibli Dashboard User Manual.docx`        | User guide for navigating and interpreting the dashboard     |
| `images/`                                  | Screenshots of the dashboard pages                           |
| `datasets/`                                | Folder containing all datasets used in the project           |
| `LICENSE`                                  | License file specifying usage and distribution terms         |
| `README.md`                                | This documentation file                                      |

---

## 📊 Dashboard Structure

The dashboard is divided into **four main pages**:

1. **Overview**
    
    - Regional filters (Japan, International, Worldwide)
    - KPIs: number of films, box office revenue, average review score
    - Trends over time and director-based analysis
    
2. **Popularity**
    
    - Audience segments: Critics, Japanese fans, Western fans
    - Top N film rankings and comparative score charts
    
3. **Finance**
    
    - Box office performance (Opening vs. Year-to-Date)
    - ROI visualization, genre and director-based revenue breakdown
    
4. **In-Depth Report**
    
    - Drill-through page for detailed film analysis
    - Poster, synopsis, director, soundtrack, financials, and popularity metrics

---

## 🧠 Data Model & Sources

The dashboard integrates data from multiple curated sources:

- **Critic and fan ratings**: Rotten Tomatoes, MyAnimeList, Anikore
- **Box office data**: Box Office Mojo, Eiren (Japan)
- **Metadata**: Ghibli Wiki, manual entries
- **Soundtracks and descriptions**: Ghibli Fandom, curated sources

The Power BI model includes:

- Cleaned and normalized datasets
- One-to-one and many-to-one relationships
- Custom DAX measures for dynamic filtering and scoring

---

## 📌 Key DAX Measures

- `OVW.BoxOffice`: Region-sensitive box office total
- `OVW.Score`: Average review score by region
- `Total Average For Each Movie`: Combined score across all segments
- `SelectedTopN`: Dynamic selector for Top 1/3/5/10 rankings
- `Critic Score Top`, `Japanese Score Top`, `Western Score Top`: Segment-specific top scores

---

## 🚀 How to Use

1. Open the `.pbix` file in **Power BI Desktop**
2. Use the slicers and filters to explore different regions, years, and audience segments
3. Click on any film to access the **In-Depth Report** via drill-through
4. Refer to the **User Manual** for a guided walkthrough

---

## 🛠️ Maintenance & Updates

- Update data sources as needed
- Modify or add DAX measures using Power BI or Tabular Editor
- Republish to Power BI Service for sharing

---

## 📬 Contact

For questions, suggestions, or contributions, feel free to open an issue or contact the project maintainer at 
**[Gaia Cassinelli](cassinelligaia@gmail.com)**
**[Mattia Stefanizzi](lux.mattiastef@gmail.com)**
**[Barbara Geroli](b.geroliz@gmail.com)**
**[Francesco Beretta](fra.brtt05@gmail.com)**
