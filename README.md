# I-320D---Coding-Assignment-2
  Description: This is an educational course project that aims to analyze the changes in reproductive health globally in the past two decades.

  Summary: The goal of this project is to analyze the changes in reproductive health globally in the past two decades, with a particular focus on two key indicators: the total fertility rate (TFR) and the lifetime risk of maternal mortality. To collect this data, I used web-scraping techniques using the BeautifulSoup and Requests packages in Python that allowed me to parse the HTML structure, identify the relevant table elements, and extract the data. The data was extracted from the World Bank's World Development Indicators (WDI) database, specifically from Table 2.14 on reproductive health, including country-level statistics on TFR, lifetime risk of maternal mortality, and other factors not featured in the final table itself (like contraceptive prevalence, adolescent fertility, and more). The World Bank collects and curates this data from various international sources such as national health surveys, censuses, and health reports from ministries of health. The key insights from this project reveal a global decline in total fertility rates from 1990 to 2022, with fewer women giving birth to large families. Simultaneously, the risk of maternal mortality has decreased, with the global average improving from 2000 to 2020. However, significant disparities still exist across countries, with some nations still facing alarmingly high risks. These trends indicate progress in reproductive health globally, though large outliers and regional inequalities remain major challenges. It is important to note that there are gaps in the data as not all countries report consistently, leading to missing entries. To combat this, the missing entries are filled with 0's that could slightly skew the analysis. Alongside this, external factors such as conflict or crises in countries may distort global trends. The findings from this project highlight the complex and varied progress in reproductive health, emphasizing the need for ongoing efforts to address disparities and improve maternal health outcomes worldwide.

# API Documentation:

BeautifulSoup Documentation:
https://www.crummy.com/software/BeautifulSoup/bs4/doc/

Requests Documentation:
https://readthedocs.org/projects/requests/downloads/pdf/latest/

License: Creative Commons Attribution 4.0 (CC BY 4.0)

Source: World Development Indicators, The World Bank; URL: https://wdi.worldbank.org/table/2.14#
