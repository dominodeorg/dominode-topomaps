# DomiNode topomaps

Development of DomiNode topomaps

This repository holds the QGIS project and related files for the development
of national topo maps for the Government of Commonwealth of Dominica. These
have been developed in scope of the DomiNode project.

## How to use it

The `qgis-projects` subdir contains the relevant QGIS projects and their
related resources, as stipulated in Kartoza's [QGIS Project synchronization SOP]

## Projects

- dominode-topomaps.qgs
  - Custodian: charles@kartoza.com
  - Description: Primary map project for toposheet production

## Data

- `qgis-proojects/data/data.gpkg`

  - Custodian: charles@kartoza.com
  - Description: Local copy of utilised data copied from remote staging 
    database as well as additional features sourced from public internet 
    sources.
  - Source: [Download from google drive]

Note that the *data* directory will be ignored by git and users will be 
required to download data sources independently and place them within the 
`qgis-projects/data` directory manually.

[QGIS Project synchronization SOP]: https://docs.google.com/document/d/1JkBSQfYDSvlybmNpwsK2DS0egbIRjkiApVBE2B1cGIA
[Download from google drive]: https://drive.google.com/file/d/1B3o7bPx1iQH5qMXUGWQO-BwLkeJYlYP7/view?usp=sharing