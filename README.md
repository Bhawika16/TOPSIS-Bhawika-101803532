# TOPSIS-Python

Submitted By: **BHAWIKA ARORA 101803532**

***
pypi: <https://pypi.org/project/TOPSIS-Bhawika-101803532>
<br>
git: <https://github.com/Bhawika16/TOPSIS-Bhawika-101803532>
***

## What is TOPSIS

**T**echnique for **O**rder **P**reference by **S**imilarity to **I**deal
**S**olution (TOPSIS) originated in the 1980s as a multi-criteria decision
making method. TOPSIS chooses the alternative of shortest Euclidean distance
from the ideal solution, and greatest distance from the negative-ideal
solution. More details at [wikipedia](https://en.wikipedia.org/wiki/TOPSIS).

<br>

## How to use this package:

TOPSIS-Bhawika-101803532  can be run as in the following example:



### In Command Prompt
```
>> topsis data.csv "1,1,1,1" "+,+,-,+" result.csv
```
<br>



## Sample dataset

The decision matrix (`a`) should be constructed with each row representing a Model alternative, and each column representing a criterion like Accuracy, R<sup>2</sup>, Root Mean Squared Error, Correlation, and many more.

Model | Correlation | R<sup>2</sup> | RMSE | Accuracy
------------ | ------------- | ------------ | ------------- | ------------
M1 |	0.79 | 0.62	| 1.25 | 60.89
M2 |  0.66 | 0.44	| 2.89 | 63.07
M3 |	0.56 | 0.31	| 1.57 | 62.87
M4 |	0.82 | 0.67	| 2.68 | 70.19
M5 |	0.75 | 0.56	| 1.3	 | 80.39

Weights (`w`) is not already normalised will be normalised later in the code.

Information of benefit positive(+) or negative(-) impact criteria should be provided in `I`.

<br>
