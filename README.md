# Cognifyz Data Analysis Internship

Remote, task-based Data Analysis internship at **Cognifyz IT Solutions Pvt. Ltd.** (Sep - Oct 2026).
I completed **Level 1** and **Level 2** tasks on a restaurant dataset using Python.

## Dataset
- 9,551 restaurants, 21 columns
- Columns include cuisines, city, price range, aggregate rating, votes, online delivery, table booking, latitude and longitude
- Only the `Cuisines` column had missing values (9 rows)

## Tools Used
Python, Pandas, NumPy, Matplotlib, Seaborn, Jupyter Notebook

## Files
| File | Description |
|------|-------------|
| `Level1_Cognifyz_Data_Analysis.ipynb` | Top Cuisines, City Analysis, Price Range Distribution, Online Delivery |
| `Level2_Cognifyz_Data_Analysis.ipynb` | Restaurant Ratings, Cuisine Combination, Geographic Analysis, Restaurant Chains |
| `Dataset_.csv` | Dataset provided by Cognifyz |

## Tasks Completed

### Level 1
1. **Top Cuisines** - top 3 cuisines and the percentage of restaurants serving them
2. **City Analysis** - city with most restaurants, average rating per city
3. **Price Range Distribution** - bar chart and percentage of each price range
4. **Online Delivery** - delivery percentage and rating comparison

### Level 2
1. **Restaurant Ratings** - rating distribution, most common range, average votes
2. **Cuisine Combination** - most common combinations and their ratings
3. **Geographic Analysis** - location plots and clusters (Delhi NCR)
4. **Restaurant Chains** - chains, their ratings and popularity

## Key Findings
- Top 3 cuisines: **North Indian (41.5%)**, **Chinese (28.7%)**, **Fast Food (20.8%)**
- **New Delhi** has the most restaurants (5,473). Among cities with 20+ restaurants, **London** has the highest average rating (4.54)
- Price range 1 is the most common (46.5%); about 79% of restaurants are in range 1 or 2
- Only **25.7%** of restaurants offer online delivery. Delivery restaurants look better rated (3.25 vs 2.47), but after removing unrated (0) restaurants the gap almost disappears (3.38 vs 3.47)
- Most common rating range is **3-4** (about 59% of rated restaurants). Average votes is 156.9 but the median is only 31
- Specialised cuisines like Japanese/Sushi and Italian are rated higher than fast food combinations
- **Barbeque Nation** is the best rated and most popular chain (avg rating ~4.35, 1000+ votes per outlet), while bigger chains like Domino's and Cafe Coffee Day are rated around 3

## Data Cleaning Notes
- 2,148 restaurants have rating 0 which means "Not rated", so they are treated separately in rating analysis
- 497 rows have longitude and latitude as 0 (missing coordinates), removed only for the map plots

## How to Run
1. Download or clone this repository
2. Keep `Dataset_.csv` in the same folder as the notebooks
3. Install the libraries: `pip install pandas numpy matplotlib seaborn jupyter`
4. Run: `jupyter notebook`

## Author
**Gaurav Govind Nikam**
[LinkedIn](https://linkedin.com/in/gaurav-nikam-ds) | [Portfolio](https://gauravnikam.vercel.app)
