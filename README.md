# TS-Exp-1-Plot-a-Time-Series-dafa
# AIM:
To develop a Python program to plot and visualize time series data such as population, commodity market price, or temperature.

# PROGRAM:
## Annual Population — 2015–2025
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
<img width="797" height="823" alt="image" src="https://github.com/user-attachments/assets/64ae87f8-b1ed-4c73-979c-114da936081f" />

# RESULT:
Thus, the given time-series data were successfully stored using Pandas and visualized using Matplotlib. The trends in population, temperature, and commodity price were identified from the plotted graphs
