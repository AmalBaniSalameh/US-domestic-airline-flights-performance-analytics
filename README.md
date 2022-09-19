# US-domestic-airline-flights-performance-analytics
This is the project of course "Data Visualization with Python" issued by IBM, which is course #8 in the "IBM Data Science Professional Certificate"
I have been given a task to monitor and report US domestic airline flights performance. Goal is to analyze the performance of the reporting airline to improve flight reliability thereby improving customer reliability.
Below are the key report items:
  - Yearly airline performance report
  - Yearly average flight delay statistics
NOTE: Year range is between 2005 and 2020.


Components of the report items:
  - Yearly airline performance report

For the chosen year provide:

* Number of flights under different cancellation categories using bar chart.
* Average flight time by reporting airline using line chart.
* Percentage of diverted airport landings per reporting airline using pie chart.
* Number of flights flying from each state using choropleth map.
* Number of flights flying to each state from each reporting airline using treemap chart.


  - Yearly average flight delay statistics

For the chosen year provide:

* Monthly average carrier delay by reporting airline for the given year.
* Monthly average weather delay by reporting airline for the given year.
* Monthly average national air system delay by reporting airline for the given year.
* Monthly average security delay by reporting airline for the given year.
* Monthly average late aircraft delay by reporting airline for the given year.


Requirements to create the expected Dashboard:
1)  Two dropdown menus: For choosing report type and year
2)  Each dropdown will be designed as follows:
An outer division with two inner divisions(One of the inner divisions will have information about the dropdown and the other one is dropdown.)
3)  Layout for adding graphs (we must have five graphs for each report type).
4)  Callback function to compute data, create graph and return to the layout.
