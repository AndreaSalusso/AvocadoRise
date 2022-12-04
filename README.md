# AvocadoRise

Due to the rise of vegetarianism, I was wondering if the price of the avocado, depending on the varieties increased over time and if it has an impact on the total volume sold as well as the volume sold for three different PLU codes:PLU4046: 

- Hass smallPLU4225
- Hass largePLU4770
- Hass extra large

I downloaded the data from the years 2015 to 2021 on the website click here: [HassAvocadoBoard](https://hassavocadoboard.com/category-data/%20)  (primary data source)

I then compiled them in one single sheet and cleaned the data, formatted the cells, and cleaned the region data as we had duplicates like “BaltimoreWashington” and “Baltimore/Washington” so I put all that in one single style. I then uploaded the dataset in my cluster on Databricks and started the analysis

### **QUESTIONS TO ANSWER**

1. Does the price have an influence on the volume?

2. Which areas consumed avocados the most from 2015 to 2021?

3. The plu4770 being the biggest Hass variety, is it also the one consumed the most?

4. Is the trend in the most consuming city a mirror image of the general trend in the U.S?

### **HYPOTHESIS**

1. Yes, the price has an influence on the volume and vice versa

2. Mostly the highly developped areas because of the vegetarian and vegan trend

3. The consumer always going for the biggest, the cleanest, the most beautiful product, is more likely to choose the biggest avocado variety

4. Yes
