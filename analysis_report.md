# 📊 Netflix Insights Dashboard — Analysis Report

## 1. Project Overview

This analysis is based on the **Netflix Titles Dataset**, which contains information about Movies and TV Shows available on Netflix, including details on content type, country of origin, ratings, genres, release year, duration, cast, and directors.

The dashboard was built in **Tableau** to extract meaningful patterns from Netflix's content library and provide actionable insights for content strategy decisions.

---

## 2. Dashboard Charts & Analysis

---

### 📌 Chart 1: Titles by Country

**Business Question:** Which countries contribute the most content to Netflix's library?

#### 🔍 What it Shows
- A geographic distribution of Netflix titles by country of production
- Highlights dominant content-producing regions across the globe
- Allows comparison of content volume between developed and emerging markets

#### 💡 Insight
- The **United States** leads by a significant margin, contributing over 35% of all titles
- **India, United Kingdom, Canada, and Japan** are among the top 5 contributors
- A large number of countries have minimal representation, indicating Netflix's library remains heavily Western-centric
- Emerging markets like **South Korea and India** are growing contributors but still trail the US by a wide gap

#### ✅ Recommendation
- Netflix should **increase investment in local-language originals** in underrepresented regions like Southeast Asia, Middle East, and Africa to grow new subscriber bases
- Given India's massive subscriber potential, **doubling down on Indian-origin content** could directly improve regional retention and acquisition

---

### 📌 Chart 2: No. of Shows by Seasons

**Business Question:** How are TV Shows distributed by the number of seasons?

#### 🔍 What it Shows
- A breakdown of TV Shows based on how many seasons they have on Netflix
- Helps understand the depth and longevity of Netflix's TV content library
- Reveals the balance between limited series and long-running shows

#### 💡 Insight
- The **majority of TV Shows have only 1 season**, suggesting a high volume of limited series, mini-series, or early-cancelled shows
- Multi-season shows (3+ seasons) are significantly fewer in comparison
- This pattern indicates Netflix may be experimenting broadly with content but not committing to long-running series at scale

#### ✅ Recommendation
- **Invest more in multi-season renewals** — long-running shows build deeper audience loyalty and reduce subscriber churn compared to one-off limited series
- Identify high-performing 1-season shows and **fast-track renewals** to convert casual viewers into committed subscribers

---

### 📌 Chart 3: No. of Titles by Rating

**Business Question:** What is the content maturity distribution across Netflix's library?

#### 🔍 What it Shows
- Count of titles grouped by maturity rating categories (TV-MA, TV-14, TV-PG, R, PG-13, G, etc.)
- Provides a clear picture of which audience segments Netflix is producing content for
- Highlights the balance (or imbalance) between adult, teen, and family content

#### 💡 Insight
- **TV-MA (Mature Audiences)** is by far the most common rating, showing Netflix's library skews heavily adult
- **TV-14** is the second most frequent, indicating a solid presence of teen-appropriate content
- Family-friendly ratings like **G, TV-G, and TV-Y** are significantly underrepresented
- Netflix is clearly positioned as an **adult and young-adult content platform** rather than a family-first service

#### ✅ Recommendation
- **Expand family and kids content** (G, TV-G, TV-Y) to capture the household subscriber segment — parents choosing a streaming platform for the whole family are a high-value, low-churn audience
- The **TV-14 segment** is underserved but highly engaged — investing in teen-targeted originals could significantly boost this category

---

### 📌 Chart 4: Distribution by Rating & Content Type

**Business Question:** How does content type (Movie vs TV Show) vary across different rating categories?

#### 🔍 What it Shows
- A side-by-side comparison of Movies vs TV Shows across each rating category
- Reveals which content format dominates in each maturity segment
- Helps understand whether Netflix's movie and TV strategies target the same or different audiences

#### 💡 Insight
- **Movies dominate across most rating categories**, especially in TV-MA and R ratings
- TV Shows are more evenly distributed across rating levels compared to Movies
- **Adult-rated Movies significantly outnumber adult-rated TV Shows**, suggesting Netflix's film catalogue is more mature-skewed than its TV catalogue
- The gap between Movies and TV Shows is widest in the **mature content categories**

#### ✅ Recommendation
- Netflix should **commission more adult-rated TV Shows** (TV-MA) to match the high volume of adult Movies — TV series keep audiences engaged over multiple episodes and seasons, driving higher retention
- For **family and kids ratings**, the focus should shift toward TV Shows over Movies, as serialized kids content drives higher repeat viewership

---

## 3. Tools & Dataset

| Item | Details |
|---|---|
| **Tool** | Tableau Desktop / Tableau Public |
| **Dataset** | Netflix Titles Dataset (`netflix_titles.xlsx`) |
| **Records** | ~6,200+ titles |
| **Tables Used** | netflix_titles, netflix_titles_cast, netflix_titles_category, netflix_titles_countries, netflix_titles_directors |
| **Key Fields** | type, rating, country, duration_seasons, duration_minutes, listed_in, release_year |

---

*Analysis by Shubham | Netflix Insights Dashboard Project*