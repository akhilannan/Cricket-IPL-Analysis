# Introduction
This repo contains Databricks Notebook and Power BI report which helps to analyze the [Indian Premier League (IPL)](https://en.wikipedia.org/wiki/Indian_Premier_League) data. This data is based on the ball-by-ball IPL json data available in [Cricsheet.org](https://cricsheet.org/matches/).

# Cricket IPL ELT Databricks
The notebook does the ELT process in Databricks, which downloads the IPL data from Cricsheet.org and build the facts and dims, leveraging [Medallion Architecture](https://learn.microsoft.com/en-us/azure/databricks/lakehouse/medallion). It can be executed in [Databricks Community Edition](https://docs.databricks.com/getting-started/community-edition.html).

# Cricket IPL Analysis
This contains the pbit file with Power BI visualization based on the curated data build from Databricks. Pass the Databricks Cluster ID and Workspace ID (found in URL) as parameter values for refreshing the report, after the notebook is executed in Databricks. The final report is also available [here](https://app.powerbi.com/view?r=eyJrIjoiNzEwNTEzNzktNDVkZS00YmQ2LTlkYWEtNTE4ZmQ2ZWRmMDFkIiwidCI6IjgxNDQwMDExLTVhZTQtNDhmNy1hY2YwLTg2ZjBkNWQ2YTFlMiJ9).