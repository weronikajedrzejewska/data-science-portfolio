# data-science-portfolio

This repository collects data science projects I’ve prepared to demonstrate my technical skills.

**Projects:**

* **Olympic_medalists_in_Athletics_(Women):** 

Web scraping project using Python's beautifulsoup and Pandas’ DataFrame. As an ex-athlete I found interesting to collect all Women Olympic medalists in Athletics from Wikipedia. Tricky part was that there was no date of birth information on the main webpage so the sub-webpage had to be open for each athlete and data had to be fetched. A lot of adjustments needed to be done because data structure on Wikipedia are not standardized. Once I got all the information I could create additional columns with the age when ladies achieved the medal. I exported data to csv, json and also stored in Posgtres. New analysis to come in Tableau/Matplotlib - I haven’t decided yet ;)


* **Home_Power_Plant:** 

After installing photovoltaic power plant in May'22 I was wondering how well production measurments from Tauron are aligned with inverter performance. Unfortunately Tauron does not provide any API, so the only source of data was website for customers. After quick search on github I found repo that is transforming response JSON from user request, into unnofficial API. Simillar story was with SMA inverter and again github was very helpful cause after few tweaks I was able to store desired data into two seperate tables in Postgres. For presenting these kind of data Grafana seemed to be well suited because rows will be updated every day and Grafana is designed for dynamically changing data. I've prepared dashboard comparing data from two different sources, iverter itself and Tauron. Now I can monitor everything and setup alerts for any possible anomallies in the installation.
