
# Lightcurve Hunter

This project analyzes real Lightcurve data from NASA's Kepler mission to detect the presence of exoplanets using time-series analysis.

## Sample Data

A sample dataset containing 100 Kepler targets is included in this directory (`filtered_kepler_targets_confirmed_candidate.csv`).  
This sample is composed of:

- 50 confirmed exoplanets  
- 50 candidate exoplanets  

We recommend using only this 100-record dataset for testing, as it already takes several hours to process.  
If you prefer to run with more samples, download the full dataset directly from NASA's Kepler data archive at:

[https://exoplanetarchive.ipac.caltech.edu/cgi-bin/TblView/nph-tblView?app=ExoTbls&config=cumulative](https://exoplanetarchive.ipac.caltech.edu/cgi-bin/TblView/nph-tblView?app=ExoTbls&config=cumulative)

## Instructions for Google Colab

To execute the code in Google Colab, upload the `.csv` test file to your Google Drive and mount the drive with:

```python
from google.colab import drive
drive.mount('/content/drive')
```

Then, update the path in the notebook to point to the correct location of the uploaded file.
