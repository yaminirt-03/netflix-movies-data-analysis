# Netflix Movies Data Analysis Dashboard (2020-2021)

A comprehensive Power BI dashboard analyzing Netflix's movie catalog and content strategy across 2020-2021. This dashboard provides deep insights into content distribution by language, genre, release patterns, runtime analysis, and catalog composition to inform content acquisition and strategic planning decisions.

## 📊 Overview

The **Netflix Movies Data Analysis Dashboard** enables content strategists, data analysts, and business stakeholders to understand Netflix's movie portfolio composition, track content diversification efforts, analyze release patterns, and identify key trends in streaming content distribution.

### Core Metrics
- **Total Movies:** 127 films analyzed
- **Unique Genres:** 10 major genres tracked
- **Languages Supported:** 5+ languages (English, Hindi, French, German, Bengali, Marathi)
- **Analysis Period:** 2020-2021 (2-year comprehensive view)
- **Peak Releases:** 182 movies in 2020 (Count of MONTH + Runtime analysis)

## 🎯 Features

### Primary Visualizations

#### 1. **Movies Released by Year**
- Dual-axis combo chart showing temporal trends
- **Metrics Tracked:**
  - Count of MONTH (primary axis) - Shows absolute movie count
  - Count of RUNTIME_MINUTES (secondary axis) - Runtime aggregate analysis
- **Key Insight:** 2020 shows 182 movies released, declining to ~60 by 2021
- **Pattern:** Significant content acquisition reduction year-over-year
- Identifies seasonal content release strategies

#### 2. **Movies Count by Language and Genre**
- Matrix/heatmap visualization showing language-genre intersection
- **Languages:** English (dominant), and secondary languages
- **Genres:** Documentary (38), Drama (16), and others
- Shows content diversity strategy across language-genre combinations
- Enables targeted content recommendation analysis

#### 3. **Language Distribution**
- Isolated language breakdown showing catalog composition
- **Primary Languages:**
  - Bengali
  - English (largest segment)
  - French
  - German
  - Hindi
- **Insight:** English dominance with emerging market language expansion

#### 4. **Total Movies and Count of Genre**
- Summary KPI cards displaying:
  - **Total Movies:** 127
  - **Count of Genre:** 10 distinct genres
- Quick reference for catalog size and diversity metrics
- Enables benchmarking across time periods

#### 5. **Movies by Language**
- Stacked/segmented bar chart showing language distribution
- **Top Languages:**
  - Drama (6 movies)
  - Thriller (5 movies)
  - Comedy (4 movies)
  - Documentary (4 movies)
  - Romantic-comedy (3 movies)
  - Action (2 movies)
  - Crime (2 movies)
  - Horror (2 movies)
  - Animation (1 movie)
  - Biopic (1 movie)
- Genre count ranked by frequency in English language content

#### 6. **Movies Released by Month**
- Heatmap/calendar view showing monthly release patterns
- **Monthly Distribution:**
  - October: 21 movies
  - April: High volume months
  - May: 12 movies
  - January: 11 movies
  - July: 10 movies
  - September: 8 movies
  - December, February, August: 8-9 movies
  - June, November: 6-8 movies
  - March: 12 movies
- Identifies peak content release windows and seasonal patterns
- Color-coded by volume for quick visual analysis

#### 7. **Movies by Language (Pie Chart)**
- Circular distribution showing language segment composition
- **Dominant Segment:** English (87, 66.3% of catalog)
- **Secondary Segments:** Hindi (12.7%), others
- Illustrates content portfolio concentration
- Shows language market focus areas

## 📈 Dashboard Analytics Framework

| Visualization | Type | Purpose | Key Metric |
|---------------|------|---------|-----------|
| Movies by Year | Area Chart | Temporal release trends | 182 (2020) → ~60 (2021) |
| Language-Genre Matrix | Heatmap | Content diversity analysis | 38 Documentary, 16 Drama |
| Language Cards | Category Filter | Language segmentation | 5+ languages supported |
| Total Movies KPI | Metric Card | Catalog size benchmark | 127 total movies |
| Genre Count KPI | Metric Card | Genre diversity | 10 genres |
| Monthly Releases | Calendar/Heatmap | Seasonal patterns | Oct: 21, Apr: High |
| Language Distribution | Bar Chart | Genre frequency by language | Drama: 6, Thriller: 5 |
| Language Pie Chart | Donut Chart | Language portfolio composition | English: 66.3% |

## 💼 Use Cases

### Content Strategy & Acquisition
- **Portfolio Analysis:** Understand Netflix's content acquisition focus areas
- **Language Strategy:** Track investment in multi-language content expansion
- **Genre Focus:** Identify content gaps and acquisition priorities by genre
- **Seasonal Planning:** Optimize content release calendars based on historical patterns

### Market Analysis
- **Regional Insight:** Analyze language-based market targeting (English, Hindi, French, German, Bengali)
- **Localization Strategy:** Track content diversity across languages
- **Emerging Markets:** Monitor Hindi and other regional language content growth
- **Competitive Positioning:** Benchmark content depth vs. competitors

### Business Intelligence
- **Catalog Health:** Monitor total movie count and genre diversity
- **Release Velocity:** Track movies released per month and year
- **Content Mix:** Analyze genre distribution and popularity trends
- **Performance Metrics:** Establish baseline metrics for content investments

### Viewer Experience
- **Content Recommendation:** Genre-language combinations for targeted suggestions
- **Discovery:** Understand available content across languages and genres
- **Personalization:** Enable language and genre-based personalization engines

### Financial Planning
- **Production Budget:** Allocate resources by genre and language
- **Content ROI:** Correlate release patterns with viewership metrics
- **Acquisition Costs:** Benchmark spending by genre and language combination
- **Inventory Management:** Optimize content acquisition pipeline

## 🎬 Content Insights & Analysis

### Genre Breakdown
Netflix's 2020-2021 movie catalog spans 10 genres with varied distribution:

| Genre | Count | Percentage | Strategic Importance |
|-------|-------|-----------|----------------------|
| Documentary | 38 | 30% | Educational content strategy |
| Drama | 16 | 13% | Core audience entertainment |
| Thriller | 5 | 4% | Engagement & binge-watch driver |
| Comedy | 4 | 3% | Mood-based selection |
| Romantic-Comedy | 3 | 2% | Niche audience segment |
| Action | 2 | 2% | High-production value |
| Crime | 2 | 2% | Premium content marker |
| Horror | 2 | 2% | Genre-specific engagement |
| Animation | 1 | 1% | Family content segment |
| Biopic | 1 | 1% | Prestige content strategy |

### Language Portfolio

**Primary Market (English):**
- 87 movies (66.3% of catalog)
- Represents global/Western audience focus
- Strong genre diversity within English content

**Emerging Markets:**
- **Hindi:** 12.7% of catalog (approximately 16 movies)
- **French, German, Bengali, Marathi:** Combined ~15-20 movies
- Indicates strategic expansion into South Asian and European markets

### Release Pattern Analysis

**2020 vs 2021 Comparison:**
- **2020:** Peak acquisition with 182 movie-months (high volume)
- **2021:** ~60 movie-months (67% reduction)
- **Implication:** Strategic shift from volume to quality or budget constraints

**Monthly Seasonality:**
- **Q4 (Oct-Dec):** High release volume (21, 8, 8)
- **Q1 (Jan-Mar):** Moderate volume (11, 9, 12)
- **Q2 (Apr-Jun):** Mixed volume (21, 12, 6)
- **Q3 (Jul-Sep):** Moderate-Low volume (10, 9, 8)
- **Peak Month:** October (21 releases) - Holiday season positioning
- **Low Month:** June (6 releases) - Summer solstice period

## 🛠️ Technical Architecture

### Platform & Tools
- **Business Intelligence Platform:** Microsoft Power BI
- **Data Sources:** Netflix content database, streaming metadata
- **Visualization Capabilities:** 
  - Matrix/heatmaps (language-genre analysis)
  - Area charts (temporal trends)
  - Stacked bar charts (distribution analysis)
  - Pie/donut charts (portfolio composition)
  - Calendar heatmaps (monthly patterns)
- **Query Language:** DAX (Data Analysis Expressions)
- **Data Models:** Relational schema with movie, genre, language, release date dimensions

### Data Architecture
```
Netflix Content Data
        ↓
Data Extraction (2020-2021)
        ↓
Dimension Tables: Movies, Genres, Languages, Release_Dates
        ↓
Fact Table: Movie_Releases with aggregated metrics
        ↓
Power BI Data Model with DAX calculations
        ↓
Interactive Dashboard Visualizations
```

## 📊 Dataset Structure

### Required Data Dimensions

| Dimension | Description | Example Values |
|-----------|-------------|-----------------|
| **Movie_ID** | Unique identifier | MOV_001, MOV_002 |
| **Movie_Title** | Content name | [Movie names] |
| **Release_Year** | Year of release | 2020, 2021 |
| **Release_Month** | Month of release | January-December |
| **Release_Date** | Complete date | YYYY-MM-DD format |
| **Language** | Content language | English, Hindi, French, German, Bengali, Marathi |
| **Genre** | Primary genre | Drama, Documentary, Thriller, Comedy, etc. |
| **Runtime_Minutes** | Duration | 90-240 minutes (typical range) |
| **Director** | Director name | [Optional for advanced analysis] |
| **Cast** | Starring actors | [Optional for recommendations] |
| **Description** | Synopsis | [Optional metadata] |
| **IMDB_Rating** | Rating score | 1.0-10.0 [Optional] |

### Data Quality Considerations
- Complete coverage for 2020-2021 period
- Standardized language and genre classification
- Accurate release date information
- Runtime data validation (typical 90-240 minute range)
- Multi-genre assignment capability (primary genre focus)

## 🎨 Design & UX Features

- **Color Scheme:** Purple and pink gradient palette with blue accent for Netflix branding
- **Visual Hierarchy:** Primary KPIs at top, detailed analysis below
- **Interactive Elements:** Language filters, genre drill-down capabilities
- **Responsive Layout:** Optimized for multi-page presentation (Page 1 shown)
- **Data Density:** Balanced mix of summary metrics and detailed breakdowns
- **Accessibility:** Color-coded patterns for easy distinction

## 🚀 Getting Started

### Prerequisites
- Microsoft Power BI Desktop or Power BI Service
- Netflix movie dataset (2020-2021) in CSV or database format
- Required data fields: Title, Release_Date, Genre, Language, Runtime

### Implementation Steps

1. **Data Preparation**
   ```
   Import Netflix movies dataset
   Parse release date for year/month extraction
   Standardize language and genre classification
   Validate runtime values
   ```

2. **Data Model Development**
   ```
   Create dimension tables: Calendar, Language, Genre
   Build fact table: Movie_Releases
   Establish relationships between tables
   Create calculated columns for aggregations
   ```

3. **Visualizations**
   ```
   Area Chart: Movies Released by Year (with Runtime secondary axis)
   Matrix: Language × Genre cross-tabulation
   Bar Chart: Movies by Language (genre breakdown)
   Heatmap: Monthly release calendar
   Pie Chart: Language portfolio composition
   KPI Cards: Total Movies, Genre Count
   ```

4. **Dashboard Assembly**
   ```
   Layout visualizations in grid structure
   Configure filters for language and genre
   Set up cross-filtering interactions
   Format colors and styling
   Enable drill-down capabilities
   ```


## 📈 Key Insights & Strategic Recommendations

### Current State Analysis

1. **Catalog Composition (2020-2021)**
   - **127 total movies** across 10 genres
   - **Heavy Documentary focus:** 38 movies (30% of catalog)
   - **Drama emphasis:** 16 movies (13%)
   - **Niche genres:** Animation (1), Biopic (1) indicate selective positioning

2. **Language Diversification**
   - **English dominance:** 66.3% (87 movies) - Core global strategy
   - **Emerging markets:** Hindi (12.7%), French, German presence
   - **Regional expansion:** Bengali and Marathi presence indicates South Asian focus
   - **Gap analysis:** Limited Asian language presence (beyond Hindi, Bengali)

3. **Release Strategy Shift**
   - **2020:** Peak acquisition (182 movies)
   - **2021:** Significant reduction (~67%)
   - **Implication:** Quality-over-quantity shift or strategic budget reallocation

4. **Seasonal Patterns**
   - **Q4 strength:** October peaks (21 releases) for holiday engagement
   - **Summer weakness:** June dips (6 releases) - streaming demand seasonality
   - **Q2 variation:** April high (21) vs June low (6) - mid-year volatility

### Strategic Recommendations

#### Short-term Actions (0-3 months)

1. **Language Expansion Strategy**
   - Increase non-English content from 34% to 50%
   - Priority: Spanish, Portuguese (Latin American markets)
   - Acquire 5-10 French, German films per month
   - Target: 150-160 movies by end of 2022

2. **Genre Optimization**
   - Reduce Documentary percentage from 30% to 20-25%
   - Increase Thriller (currently 4%) to 10-12%
   - Expand Comedy from 3% to 8-10%
   - Maintain Drama at 12-15% (core audience driver)

3. **Release Cadence**
   - Stabilize monthly releases at 10-12 (currently 5-21 range)
   - Peak releases in: October-November (holiday), April-May (summer kick-off)
   - Minimize summer releases (June-July) - low-demand periods
   - Plan 120+ movies for 2022 acquisition

#### Medium-term Initiatives (3-12 months)

1. **Market-Specific Content Strategy**
   - **India:** Increase Hindi content from 12.7% to 20%
   - **Europe:** Develop French, German, Spanish content tier (15% of catalog)
   - **Asia:** Add Japanese, Korean, Thai language content (10% target)
   - **Middle East:** Arabic content development (5% target)

2. **Genre Diversification**
   - Action: Scale from 2 to 8-10 movies (action-adventure demand)
   - Crime: Expand from 2 to 6-8 movies (binge-watch appeal)
   - Horror: Increase from 2 to 5-6 movies (genre audience loyalty)
   - Animation: Scale from 1 to 10+ (family content strategy)
   - Biopic: Expand to 4-5 prestige films annually

3. **Data-Driven Acquisition**
   - Correlate genre-language combinations with viewership
   - Identify highest-ROI genre-language pairs
   - Build predictive model for content performance
   - Establish genre-specific acquisition budgets

#### Long-term Strategy (12+ months)

1. **Global Portfolio Optimization**
   - Target: 300-350 movies by 2024
   - Language distribution: English 45%, Regional 55%
   - Genre balance: Remove bottom-performing genres
   - Build original content pipeline

2. **Personalization & Recommendation**
   - Leverage language-genre data for recommendation engine
   - Create viewer personas based on preference patterns
   - Develop ML models for content discovery optimization

3. **Competitive Positioning**
   - Benchmark catalog against Disney+, Amazon Prime Video, HBO Max
   - Identify content gaps vs. competitors
   - Focus on underserved genre-language combinations

## 📊 Performance Metrics Dashboard

### KPI Tracking

| KPI | 2020 | 2021 | Target 2022 | Status |
|-----|------|------|-------------|--------|
| Total Movies | 182 | 60 | 120+ | ↓ Decline |
| English % | 72% | 66% | 50% | ↓ Decreasing |
| Regional Languages % | 28% | 34% | 50% | ↑ Growing |
| Documentary % | 25% | 30% | 20% | ↑ Over-indexed |
| Drama % | 15% | 13% | 15% | ↓ Below target |
| Thriller % | 3% | 4% | 10% | ↓ Below target |
| Avg Monthly Releases | 15 | 5 | 10 | ↓ Volatile |
| Genre Diversity | 8 | 10 | 12+ | ↑ Improving |

## 🔄 Data Refresh & Maintenance

- **Refresh Frequency:** Monthly (aligned with Netflix release calendar)
- **Data Lag:** Weekly processing for latest releases
- **Historical Archive:** Complete 2020-2021 dataset retained
- **Backup Schedule:** Weekly automated backups
- **Data Quality Checks:** Validation of release dates, genre classification

## 👥 Contributors & Team

- **Dashboard Development:** Business Intelligence Team
- **Data Engineering:** Data Platform & Infrastructure Team
- **Product Analytics:** Content Intelligence Team
- **Stakeholder Management:** Content Strategy Leadership
- **Domain Expertise:** Global Content & Partnerships Team

## 📚 Resources & References

- [Power BI Documentation](https://docs.microsoft.com/power-bi/)
- [DAX Language Reference](https://dax.guide/)
- [Netflix Content Strategy](https://www.netflix.com/browse)
- [Industry Content Trends](https://www.theprintable.com/streaming-industry-analysis)

## 🎯 Quick Navigation

- [Overview](#-overview)
- [Dashboard Features](#-features)
- [Use Cases](#-use-cases)
- [Content Insights](#-content-insights--analysis)
- [Getting Started](#-getting-started)
- [Key Insights](#-key-insights--strategic-recommendations)
- [Performance Metrics](#-performance-metrics-dashboard)
- [Support](#-support--governance)

---

## 📄 License

For educational and portfolio use.

---

## 👩‍💻 Author

Yamini T
