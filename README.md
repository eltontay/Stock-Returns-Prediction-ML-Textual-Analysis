# Stock-Returns-Prediction-ML-Textual-Analysis

Applying machine learning and textual analysis on macro and micro determinants to predict stock returns

## Getting Started

1. Make sure your python is configured properly
   - In the .ipynb file, make sure the top right python library is the same as where you install your python libraries

There are 4 main folders : `Data` , `Data-Collection` , `Data-Model` and `Data-Report`

---

### 1. `Data`

Contains `Stock` and `Global` data. These unstructured data are extracted from investing.com and scraped using BeautifulSoup. Each csv file contains 3 columns : `Date`, `Title` and `Text`

### Stock

| Name  | Rows |
| ----- | ---- |
| Apple | 2289 |
| Meta  | 2465 |
| Tesla | 1776 |

### Global

| Name        | Rows |
| ----------- | ---- |
| World       |
| Politics    |
| Coronavirus |
