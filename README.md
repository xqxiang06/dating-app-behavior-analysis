# 📱 Dating App Behavior & Sentiment Analysis

This repository contains an exploratory data analysis project examining **online dating app reviews** across major platforms such as Tinder, Bumble, Hinge, and OkCupid.  
The goal is to understand **user sentiment, trends in ratings, common complaints/praises, and engagement patterns** using text mining and visualization in **R**.

---

## 👩‍💻 Author
**Xiaoqian Xiang**  
UCLA Stats 20 — Summer Session

---

## 🔍 Project Focus

This study investigates:

- How star ratings and sentiment vary by app
- Whether sentiment changes over time
- What themes appear most frequently in negative and positive reviews
- Whether developer replies correlate with sentiment or rating
- How review volume differs across platforms

---

## 📦 Repository Contents

| File | Description |
|------|-------------|
| `DatingApp Reviews.Rmd` | Main R Markdown script containing the full analysis |
| `Stats_20_Group_Report.pdf` | Course submission PDF (contains additional documentation) |
| `DatingApp-Reviews.html` *(if present locally)* | HTML version of the analysis |
| `datas-csv` or dataset file | Cleaned dataset used for the analysis |
| `dating_pic.png` | Plot image referenced in analysis |

> ⚠️ Some files may not display preview in GitHub due to size, but can be downloaded and viewed locally.

---

## 📊 Key Findings

- **Review sentiment decreases over time** across all apps
- **Tinder receives the highest number of negative reviews**, especially about spam and fake accounts
- **Developer feedback is low overall**, showing a disconnect between user concerns and platform responses
- **Positive sentiment comes mainly from users who successfully matched or started relationships**
- **User frustration spikes around monetization features**, such as pay-to-message or subscription requirements

---

## 🧰 Tools & Libraries Used

| Category | Technologies |
|---------|--------------|
| Language | R |
| Data wrangling | `dplyr`, `tidyr`, `stringr` |
| Visualization | `ggplot2`, `scales` |
| Text mining / sentiment | `tidytext` |
| Reporting | R Markdown, PDF/HTML export |

---

## ▶️ How to Run the Notebook

1. Clone or download this repository.
2. Open the file in **RStudio** (`DatingApp Reviews.Rmd`).
3. Make sure required packages are installed:
   ```r
   install.packages(c("dplyr", "tidyr", "stringr", "readr", "ggplot2", "tidytext"))
4. Knit the R Markdown file to HTML or PDF in RStudio


## 🧩 Future Work
- Topic modeling (LDA / STM) for deeper semantic theme extraction
- Word-embedding sentiment models (BERT / RoBERTa)
- Cross-app comparison dashboard using Shiny
- Predicting user ratings from review text
- Time-series forecasting of sentiment over the next 6–12 months
