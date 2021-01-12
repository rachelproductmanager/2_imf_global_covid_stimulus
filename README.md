# 2. IMF global covid stimulus database

The data for this project was lifted from the International Monetary Fund's (IMF) Fiscal Monitor Database of Country Fiscal Measures in Response to the COVID-19 Pandemic which can be found here: https://www.imf.org/en/Topics/imf-and-covid19/Fiscal-Policies-Database-in-Response-to-COVID-19.

This database summarises key fiscal measures governments around the world have announced or taken in response to the COVID-19 pandemic as of September 11, 2020.

The database categorizes different types of fiscal support (for example, above-the-line and below-the-line measures, and contingent liabilities) that have different implications for public finances in the near term and beyond.

It focuses on government discretionary measures that supplement existing automatic stabilizers. These existing stabilizers differ across countries in their breadth and scope. In particular (and unsurprisingly), there are stark differences between G20 advanced economies and other countries in emerging markets and low income economies.

The dataset was quite challenging to work with as it's quite wide (contained 53 columns), had many headers, plenty of empty cells and unwanted rows. 

Once the dataset was clean and reshaped, it was interesting to create a few visualisations, in matplotlib and seaborn, which uncovered valuable insights from what was originally quite a messy and noisy dataset.
