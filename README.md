# Global-Terrorsim-Dataset-GTD


Summary Content

- Project: Global Terrorism Trends :  Data Visualization Tool
- Geography: Worldwide
- Time period: 1970-2017, except 1993 (there were lots of missing data on year 1993 prior to the database compilation)
- Variables: DB contains 135 columns, but I only picked 14 variables containing dates, location, tactics, perpetrators, targets, and fatalities.


Steps to run on your local desktop: (using Bokeh Server)

- Download the GTD csv file at https://www.kaggle.com/START-UMD/gtd
- Download the GTD_tool.ipynb. Ensure the file and module are in the same base dir.
- Run the module via prompt, key in command: bokeh serve --show GTD_tool.ipynb
- An interactive dashboard hosted locally will be prompted.

References:

1.https://www.kaggle.com/START-UMD/gtd
2.https://www.start.umd.edu/gtd
3.https://start.umd.edu/gtd/downloads/Codebook.pdf
