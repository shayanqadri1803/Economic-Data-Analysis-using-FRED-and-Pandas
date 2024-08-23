# Economic Data Analysis with FRED and pandas

The code provided is a comprehensive economic data analysis project that leverages the Federal Reserve Economic Data (FRED) API to retrieve, analyze, and visualize key economic indicators, specifically focusing on the S&P 500 index, unemployment rates, and labor force participation rates across various U.S. states. The project utilizes Python libraries such as `pandas`, `numpy`, `matplotlib`, `plotly`, and `fredapi` for data manipulation, visualization, and interaction with the FRED API.

#### **Setting Up the Environment**
The project begins by setting up the necessary environment, including installing required packages such as `fredapi`, which allows for seamless interaction with the FRED database. The script imports essential libraries for data handling (`pandas`, `numpy`), plotting (`matplotlib`, `plotly`), and configuring the plotting style to maintain consistency across visualizations.

#### **Accessing and Analyzing Economic Data**
The next step involves creating an object to interact with the FRED API using the provided API key. The code demonstrates how to search for specific economic data within the FRED database. For instance, it searches for S&P 500 data and retrieves the corresponding time series, which is then plotted to show the historical performance of the S&P 500 index. This section also introduces basic visualization using `matplotlib`, where the S&P 500 data is plotted over time to observe trends.

#### **Unemployment Rate Data**
The project proceeds to focus on unemployment data by searching for unemployment rates across different U.S. states. It filters the search results to obtain monthly data that is seasonally adjusted and expressed as a percentage. The code retrieves unemployment rate data for each state, consolidating it into a single DataFrame. This allows for comprehensive state-level analysis and comparison. The unemployment rates are then visualized using `plotly`, which provides interactive and dynamic visualizations.

#### **May 2020 Unemployment Rate Analysis**
A specific analysis is conducted for the unemployment rates as of May 2020, where the code selects data from this period and plots it to compare unemployment rates across states. The data is further processed to replace state IDs with their corresponding names for better readability. The unemployment rates for May 2020 are visualized using a horizontal bar plot, allowing for a clear comparison of the economic impact of the COVID-19 pandemic on different states.

#### **Labor Force Participation Rate Data**
Similar to the unemployment data, the code retrieves and analyzes the labor force participation rates for various states. This data is also filtered, processed, and visualized to observe trends and differences in labor force participation across states. The project utilizes fuzzy matching techniques to align state names between unemployment and participation datasets, ensuring accurate comparisons and analyses.

#### **Comparison of Unemployment and Participation Rates**
The final section of the code involves comparing unemployment rates with labor force participation rates for specific states, such as New York, over a defined time period. This comparison is visualized using a dual-axis plot, where unemployment rates are plotted on one axis and participation rates on the other. This allows for a nuanced understanding of the relationship between these two economic indicators.
