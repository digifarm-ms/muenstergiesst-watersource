# Convert water source data to GeoJSON

Jupyter notebook for reading in water sources data (CSV) and convert it to a `pumps.json` file (GeoJSON), as used in the [Münster schenkt aus](https://github.com/digifarm-ms/giessdenkiez-de) web application.

## How to use this project:

1. Install dependencies

2. Run in a visual Jupyter environement, or execute on the command line:

```
jupyter nbconvert --execute --clear-output watersource-to-geojson.ipynb`
```

3. Place resulting output files in the web application's [public data folder](https://github.com/digifarm-ms/giessdenkiez-de/tree/muenster/public/data).
