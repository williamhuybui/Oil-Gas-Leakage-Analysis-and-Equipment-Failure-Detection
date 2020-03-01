# Rolling in the Deep

Description: A journey from oil leakage to applying AI to predict equipment failure

** Project status: ** Completed

## Dataset

[Oil Pipeline Accidents, 2010-Present](https://www.kaggle.com/usdot/pipeline-accidents)
**Location:** `database.csv`
**Description:** This database includes a record for each oil pipeline leak or spills reported to the Pipeline and Hazardous Materials Safety Administration since 2010. These records include the incident date and time, operator and pipeline, cause of the incident, type of hazardous liquid and quantity lost, injuries and fatalities, and associated costs.

[Predictive Equipment Failures](https://www.kaggle.com/c/equipfails/data)
**Location:** `equipfails`
**Description:** Predict downhole equipment failures using sensor data!

**Features summary**: There are two types of sensor columns in these data sets :

* `measure columns` - These columns are a single measurement for the sensor.

* `histogram bin columns` - These columns are set of 10 columns that are different bins of a sensor that show its distribution over time.

## Technologies:

`python`, `pandas`, `matplotlib`, `plotly`, `scikit-learn`

## Result

All of the results can be found in the medium post! However, the visualizations are all static. For interactive graphs, go to `Accident_visulization.ipynb` and execute the file.

