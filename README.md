# XGBoost-Ontario-Road-Pavement-Quality
This notebook used eXtreme Gradient Boosting (XGBoost) on the *Pavement condition for provincial highways* dataset from the government of Canada (available here: https://open.canada.ca/data/en/dataset/01dfc06c-6ef0-4fd0-a010-8ba20e3c9d10). 

The dataset contains the readings from an Automatic Road Analyzer (ARAN) that was used on various sections of road in Ontario (e.g., freeway, local road, arterial). Each section of road pavement was automatically evaluated by the ARAN based on its distress (Distress Manifestation Index, DMI), wheel
track rutting (in mm), and roughness (International Roughness Index, IRI). These indices were then combined into a Pavement Condition
Index (PCI) for an overall rating of road pavement condition.

The goal of this notebook was to determine what features might predict for good or bad quality roads in Ontario.
