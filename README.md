# CHCD Data
This repository houses the data releases of the China Historical Christian Database. For information on this dataset, please refer to our detailed documentation at [CHCD Data Documentation](https://chcdatabase.github.io/data-documentation/) or our [open-access article(https://doi.org/10.3390/data9060076)] in *Data* introducing the dataset.  For more information on the project, see the project [website](https://chcdatabase.com/#about).

## CSV Files
Please note that the files use @ as their delimeter. The data is designed to be imported into a neo4j database. To import the data into neo4j, use the following command:
neo4j-admin database import full --multiline-fields=true --delimiter=@ --nodes=import/chcd_v2.5_nodes.csv --relationships=import/chcd_v2.5_edges.csv

