# data-science-portfolio

This repository collects my data science projects I’ve prepared to demonstrate my technical skills.

**Projects:**

* **Olympic_medalists_in_Athletics_(Women):** 
Web scraping project using Python's beautifulsoup and Pandas’ DataFrame. As an ex-athlete I found interesting to collect all Women Olympic medalists in Athletics from Wikipedia. Tricky part was that there was no date of birth information on the main webpage so the sub-webpage had to be open for each athlete and data had to be fetched. A lot of adjustments needed to be done because data structure on Wikipedia are not standardized. Once I got all these information I could create additional columns with the age when ladies achieved the medal. I exported data to csv, json and also stored in Posgtres. New analysis to come in Tableau/Matplotlib - I haven’t decided yet ;)

* **Home_Power_Plant:** 
The aim of the project is to fetch data about energy production from two sources: Tauron Elicznik and SMA inverter to present it further in Grafana dashboard. To achieve that I used two unofficial APIs elicznik and sma_sunnyboy. Data from both sources are then stored in Postgres (Elephant SQL) as two seperate tables. In Grafana I've prepared dahsboard presenting and comparing measurments from both.
