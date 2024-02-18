# COVID-19 Effect on Housing Market in Canada

**Overview**

A comparative analysis of key indicators before and after the pandemic. Our research project aims to perform an extensive analysis of what are the key differences in the Canadian housing market dynamics before and after the COVID-19 pandemic, and how factors such as housing prices, demand-supply dynamics, mortgage rates, and consumer behavior contributed to these changes.

**Research Question**: Has the COVID-19 pandemic significantly impacted the housing market in Canada? Which Provinces in Canada have been affected the most? 

The slide deck of our presentation can be found as a PDF, titled: Presentation - Analysis of the housing market in Canada before and after the pandemic.PDF.

**Data Sets**: Data sets were obtained from the following website:

- (n.d.). Canadian Housing Market Stats. CREA. https://stats.crea.ca/en-CA/

- https://www.bankofcanada.ca/rates/interest-rates/canadian-interest-rates/?lookupPage=lookup_canadian_interest.php&startRange=2014-02-08&rangeType=dates&dFrom=2020-01-01&dTo=2024-02-08&rangeValue=1&rangeWeeklyValue=1&rangeMonthlyValue=1&ByDate_frequency=daily&submit_button=Submit

The data sets included the following information:
- COVID-19 Infection rates
- Mortgage rates
- Housing demand-supply dynamics
- Real Estate Trends

**Data Cleaning**

Data cleaning can primarily be found in Jupyter's notebooks "Outlier_analysis.ipynb". The data cleaning process included the following steps:

Years: 2000 to 2024.
- Covid-19 infection data Analysis from 2020 to the present(2024).
- 


**Data Analysis**

This analysis aims to investigate and comprehend the real estate trends in Canada before and after the onset of the COVID-19 pandemic, with a specific focus on understanding the effects of COVID-19 on these trends.

**COVID Cases in Canada**

**Affect of COVID 19 on Mortgage rate (Interest)**

**Affect of COVID 19 on Housing prices**

**Hypothesis**

**Conclusion**

**Sources used for covid19 dataframe creation:**
https://pandas.pydata.org/docs/reference/api/pandas.Series.dt.month_name.html #used by Graham
https://www.skytowner.com/explore/combining_columns_of_years_months_and_days_in_pandas #used by Graham
https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.set_index.html #used by Graham
https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.shapiro.html #used by Graham
https://matplotlib.org/stable/api/_as_gen/matplotlib.pyplot.vlines.html #used by Graham
https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.shift.html #used by Graham

Site for CSV File #Used by Edward
https://www.bankofcanada.ca/rates/interest-rates/canadian-interest-rates/?lookupPage=lookup_canadian_interest.php&startRange=2014-02-08&rangeType=dates&dFrom=2020-01-01&dTo=2024-02-08&rangeValue=1&rangeWeeklyValue=1&rangeMonthlyValue=1&ByDate_frequency=daily&submit_button=Submit

Definitions for the different types of interest displayed in the dataset #Used by Edward
https://www.bankofcanada.ca/rates/interest-rates/canadian-interest-rates/notes-on-canadian-interest-rates/

Pandas Merging dataframes #Used by Edward
https://pandas.pydata.org/docs/user_guide/merging.html

Converting to percentage #Used by Edward
https://levelup.gitconnected.com/convert-percentage-string-to-numeric-and-vice-versa-in-pandas-18a3d66e2853

Assist with plotting #Used by Edward
https://www.datacamp.com/tutorial/line-plots-in-matplotlib-with-python

Scatterplot reference: https://matplotlib.org/stable/api/_as_gen/matplotlib.pyplot.scatter.html #Used by Edward

Lineplot references: https://matplotlib.org/stable/api/_as_gen/matplotlib.pyplot.plot.html #Used by Edward

Look over what is involved in matplotlib: https://matplotlib.org/2.0.2/index.html #Used by Edward

Github functions: making branch, changing branch, merge main to branch #Used by Edward
https://chat.openai.com/

Bar graph average home prices reference  : https://stackoverflow.com/questions/22508590/enumerate-plots-in-matplotlib-figure

