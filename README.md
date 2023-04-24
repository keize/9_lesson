
# Diamonds dataset analysis
Studing project with tasks:

1. What is the average price of all diamonds in the dataset?
2. What is the average number of carats in diamonds of each quality of cut?
3. What is the most common diamond color in the dataset?
4. What is the distribution of the number of diamonds in each color? Use the graph to explain
5. What percentage of diamonds in the dataset have a cut quality of "Fair"?
6. What percentage of diamonds in the dataset are perfectly cut?
7. What is the average number of diamonds in the "Premium" category in each color?


## Imports

```
import pandas as pd 
import numpy as np 
import seaborn as sns
import matplotlib.pyplot as plt
%matplotlib inline

```
## Data set
```
df = pd.read_csv('diamonds.csv')

```