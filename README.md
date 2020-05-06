# AvocadoPrices
This repository contains an EDA of avocado prices in USA

COLUMNS
index -> row index
date -> The date of the observation
average_prices ->the average price of a single avocado
total_volume -> Total number of avocados sold
plu_4046 -> Total number of avocados with PLU 4046 sold
plu_4225 -> Total number of avocados with PLU 4225 sold
plu_4770 -> Total number of avocados with PLU 4770 sold
total_bags -> Total Bags
small_bags -> Small Bags
large_bags -> Large Bags
xlarge_bags -> XLarge Bags
type -> conventional or organic
year -> the year
region ->the city or region of the observation


steps
0. read a csv file as data frame
1. Convert data to proper format
2. Extract month and day column
3. Add "calendar quarters" columns
4. Add currency column (prices are in USD)
