# Environmental-Inequality-in-Europe
pollution levels green space access income vs environment
scatter plot (income vs pollution)
map of environmental inequality
sustainability transitions
EU Green Deal
import seaborn as sns
import pandas as pd

data = {
    "country": ["Germany", "France", "Poland", "Italy"],
    "gdp": [45000, 42000, 18000, 35000],
    "pollution": [12, 10, 25, 18]
}

df = pd.DataFrame(data)

sns.scatterplot(data=df, x="gdp", y="pollution")
