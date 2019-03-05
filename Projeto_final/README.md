## Input data

One of the data is too big so i was having problem to upload it here, so it follow the link were i downloaded:
https://www.kaggle.com/ramirobentes/flights-in-brazil/home  
The other data are in the folder "Dados"


Final column after the preprocess:
Codigo.Justificativa  -> Target (If the flight is going to be on-time, delayed or canceled)

tmpf: Air Temperature in Fahrenheit, typically @ 2 meters

dwpf: Dew Point Temperature in Fahrenheit, typically @ 2 meters

relh: Relative Humidity in %

drct: Wind Direction in degrees from north

sknt: Wind Speed in knots

alti: Pressure altimeter in inches

mslp: Sea Level Pressure in millibar

vsby: Visibility in miles

gust: Wind Gust in knots

skyc1, skyc2, skyc3, skyc4 -> sky coverage, related with visibility

skyl1, skyl2, skyl3, skyl4 -> sky level, related with visibility

## Instalation

### Install imbalanced-learn library


conda install -c conda-forge imbalanced-learn 

### Instal scikit learn
conda install -c anaconda scikit-learn

Executed on Ubuntu (i had a few problem on Windows because of DLL)

## Report
The work that was made is described in Capstone_report.
