# Skincare at Sephora: From a Few Giants to a Crowded Field

![Summary](images/sephora_summary.png)

**How the brands that dominate Sephora skincare reviews changed between 2019 and 2022, based on about 745,000 customer reviews from 2018 to 2022.**

## The Question

Who leads a category, and does it last? I looked at which skincare brands received the most customer reviews on Sephora each year from 2018 to 2022, to see how much attention the biggest brands held and whether the same names stayed on top.

## What I Found

**In 2019, a handful of brands dominated.** The five most-reviewed brands held 32.2% of all skincare reviews that year. Drunk Elephant alone held 9.7%, about 1 review in 10.

**Then it loosened quickly.** The top five's share fell to 26.0% in 2020 and 18.2% in 2021, then held at 18.0% in 2022. The biggest brand in 2022, Glow Recipe, held 4.1%.

![Top-five share of reviews](images/sephora_top5_share.png)

**The leaders changed.** None of the 2019 top five were in the 2022 top five. Drunk Elephant went from first to 19th (12,558 reviews to 3,065), and Tatcha from third to 20th. Glow Recipe rose from 19th to first, Shiseido from 34th to fourth, and Dermalogica from 27th to fifth. Only three of the 2019 top ten (The Ordinary, fresh and LANEIGE) were still in the 2022 top ten, all ranked lower.

![Leaders in 2019 vs 2022](images/sephora_leaders.png)

**The field got more crowded.** 50 brands had at least 1,000 reviews in 2022, up from 38 in 2019, and 134 brands received at least one review, up from 86.

## Why It Matters

Leading a category isn't permanent. Brands that held the top spots in 2019 were outside the top ten by 2022. A retailer or brand team could use review volume as one signal of where customer attention is moving, and how quickly it can move.

## What This Data Can't Tell Us

- **Reviews are not sales.** A brand with more reviews isn't necessarily selling more.
- **It shows who moved, not why.** Launches, promotions, review campaigns and changes to a brand's product line could all play a part, and none are measured here.
- **Some of the drop reflects a bigger field.** More brands received reviews each year, which lowers any single brand's share.
- **Earlier years may be undercounted.** The dataset contains products listed on Sephora when the data was collected (through March 2023), so discontinued products are missing.
- **Duplicates were removed.** The same review can appear under several product listings (minis, sets, sizes). I counted each once, treating a review as a duplicate when the reviewer, brand, timestamp, rating and text all matched. This removed 122,926 rows (11.2%) and left 971,485 unique reviews across all years.

## Explore the Full Analysis

- **[Interactive Tableau Dashboard →](YOUR_TABLEAU_LINK_HERE)**: start on the Summary tab for the quick take
- **[Python Notebook →](Sephora_Skincare_Brand_Shift.ipynb)**: duplicate removal, calculations and exports

## About the Data

Source: the Sephora Products and Skincare Reviews dataset on Kaggle ([add link]). Reviews run from 2008 to March 2023. This analysis covers 2018 to 2022, the years with enough reviews and a complete calendar year. "Top brand" means most reviews in that year. The raw Kaggle files are too large for GitHub and are not included.

## Repository Contents

- `Sephora_Skincare_Brand_Shift.ipynb`: the full analysis
- `skincare_concentration.csv` and `skincare_brands_by_year.csv`: the summary tables behind the dashboard
- `images/`: dashboard screenshots used in this README

## Tools

Python (Pandas) · Jupyter Notebook · Tableau Public · GitHub

## Author

Hazeezat Adebayo | Data Analyst | Python · Tableau
