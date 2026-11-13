# TSAF-Ex-1-Plot-a-Time-Series-Data
# TSAF-Ex-1-Plot-a-Time-Series-Data

## AIM:
To develop a Python program to plot and visualize time series data such as population,
commodity market price, or temperature.

## ALGORITHM:
1. Start the program.
2. Import Pandas and Matplotlib libraries.
3. Create the time-series data using Year or Month and its corresponding values.
4. Create a DataFrame using the time and value data.
5. Display the DataFrame.
6. Plot the time-series data using a line graph.
7. Add a suitable title and labels for the X-axis and Y-axis.
8. Display the graph.
9. Observe the graph and identify the trend as increasing, decreasing, approximately
constant, or seasonal.
10. Stop the program.

## PROGRAM:

### Annual Population — 2015–2025
```
import pandas as pd
import matplotlib.pyplot as plt
year = [2015, 2016, 2017, 2018, 2019, 2020, 2021, 2022, 2023, 2024, 2025]
population = [90, 93, 96, 98, 100, 103, 106, 110, 114, 118, 123]
data = pd.DataFrame({
 "Year": year,
 "Population": population
})
print(data)
plt.plot(data["Year"], data["Population"])
plt.title("Annual Population")
plt.xlabel("Year")
plt.ylabel("Population (Millions)")
plt.show()
```

## OUTPUT:
<img width="652" height="687" alt="image" src="https://github.com/user-attachments/assets/10ef1d36-4216-4406-8f86-e69bb3203165" />

## RESULT:
Thus, the given time-series data were successfully stored using Pandas and visualized using
Matplotlib. The trends in population, temperature, and commodity price were identified from
the plotted graphs
