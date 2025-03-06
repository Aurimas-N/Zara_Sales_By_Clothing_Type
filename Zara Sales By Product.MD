# Zara Sales By Product

## This project was completed for practise.

# Corporate Background:
Zara, founded in 1975 in Spain, is a leading fast fashion brand. Known for its quick response to trends, it offers affordable clothing, accessories, and footwear globally. With a vertically integrated supply chain, Zara efficiently designs, produces, and distributes new styles.
It operates in over 90 countries and emphasizes sustainability through eco-friendly initiatives.

# Tasks:
* Which clothing types generate the highest sales volume and revenue, and how does price impact their performance?
* Analyze category-level performance by comparing sales volume and revenue between promoted and non-promoted products with a pivot table.
* Prepare data for further analysis.

# Data Description:
* Data is [public in Kaggle](https://www.kaggle.com/datasets/xontoloyo/data-penjualan-zara/data) and released under [MIT License](https://www.mit.edu/~amini/LICENSE.md).
* Data is in one `.csv` format file and contains (83.15 kB) of information.
* The dataset contains records of **`Product ID`,	`Product Position`,	`Promotion`,	`Product Category`,	`Seasonal`,	`Sales Volume`,	`brand	url`,	`sku`,	`name`,	`description`,	`price`,	`currency`,	`scraped_at`,	`terms	section`** coulmns and has 253 rows.
* Data is stored in Google Sheets.

# Data Processing And Cleaning:
* [View of data exploration, cleaning and manupilation process](path/to/Exploration, cleaning, transformation.MD). process done in Google Sheets.
* Vizualisation developed with Tableau.
* Adding 4 new columns - `price range`(where low indicates price lower then 50$ and equal, medium between 50$ and 100$(equal) and high over 100$), `sales performance` column ( low below 1000 and equal sales, ,medium between 1000 and 2000(equal), high over 2000), `promotion flag` column for promotion status (1 for promoted, 0 for not promoted) for easier filtering or comparing, `revenue`(sales x price).

# Analyze And Share:
[Cleaned sheet and pivot table](https://docs.google.com/spreadsheets/d/1qM-US_Z5_eA7O50pTH4mnvdmK9CdFFQiH45qe5BHRhE/edit?usp=sharing) in Google Sheets, also can be seen in .csv format [cleaned table]Zara sales cleaned.csv) and [pivot](pivot table.csv).

Tableau dashboard was created to answer question - Which clothing types generate the highest sales volume and revenue, and how does price impact their performance??





