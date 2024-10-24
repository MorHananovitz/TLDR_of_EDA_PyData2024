# The TL;DR of EDA

Notebook attached to the talk given in PyData TLV 2024

<u> Full Conference Agenda: </u>
https://pydata.org/telaviv2024


<u> UCI Wine dataset: </u>
https://archive.ics.uci.edu/dataset/109/wine

`ucimlrepo` package full documentation:
https://github.com/uci-ml-repo/ucimlrepo?tab=readme-ov-file


## Installation
In a Jupyter notebook, install with the command 
```
!pip install -U ucimlrepo 
!pip install -U ydata-profiling
```
Restart the kernel and import the modules.

## Dependencies
```
pandas = '2.2.2'
seaborn = '0.13.2' 
numpy = '1.26.4'
matplotlib = '3.7.1'
sklearn = '1.5.2'
```
## Data Set:

* **Alcohol:** The alcohol content of the wine, usually measured as a percentage of volume.
* **Malic acid:** The concentration of malic acid, a type of organic acid found in wine that affects its tartness and taste.
* **Ash:** The total ash content in wine, a measure of the mineral content after complete combustion of the wine sample.
* **Alcalinity of ash:** The measure of alkalinity in the ash content of the wine, indicating the balance of acids and bases in the sample.
* **Magnesium:** The amount of magnesium present in the wine, an essential mineral that can influence fermentation and the overall taste.
* **Total phenols:** The total amount of phenolic compounds in wine, which contribute to the wine's flavor, color, and mouthfeel.
* **Flavanoids:** A specific group of phenolic compounds that contribute to the wine’s bitterness, astringency, and antioxidant properties.
* **Nonflavanoid phenols:** Phenolic compounds in wine that are not flavanoids, influencing color and aging properties but less on taste.
* **Proanthocyanins:** Tannins that influence the astringency, color, and mouthfeel of the wine, playing a role in its bitterness.
* **Color intensity:** The depth or intensity of the color of the wine, often indicative of grape variety and wine age.
* **Hue:** The hue or tint of the wine's color, which can indicate its age (with red wines, it tends to become more orange with age).
* **OD280/OD315 of diluted wines:** The ratio of optical densities measured at wavelengths 280 nm and 315 nm, used to estimate the concentration of phenolic compounds, especially tannins.
* **Proline:** An amino acid found in wine that can be an indicator of the grape variety and the fermentation process.
