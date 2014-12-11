Depositing Data on the NSRR
===========================


Purpose
-------
To describe the process of taking a dataset, stripping it of missing and identifiable data, and publishing the data on [sleepdata.org](https://sleepdata.org).

Scope
-----
This SOP is intended for use by any clinical research staff who maybe involved in the collection, cleaning, or curation of any dataset that is to be hosted by the NSRR.

Responsibilities
----------------
#### Research Assistant
- To generate JSON data dictionary files for each variable in the dataset
- To create an automated process to deidentify and clean any PHI in the dataset
- To identify and verify or note any outliers or implausible data in the dataset

#### Data Manager
- To liaise with other data coordinating centers (DCC) for clarification of undefined variables
- To provide guidance to Research Assistant(s) working on a dataset
- To adjudicate any potential outliers or implausible data that are found in a dataset

#### System Administrator
- To assist with the publication of datasets on [sleepdata.org](https://sleepdata.org)
- To provide guidance, where necessary, in the utilization of tools developed by the NSRR

Procedure
---------
1. Formation of a GitHub repository

  1.1 Research Assistant will initialize a version-controlled GitHub repository specific to the dataset

  1.2 GitHub repository should contain folders to house variables, domains, forms, Ruby tests, and data cleaning scripts, along with any other files necessary to maintain version control

    1.2.1  Examples can be found [here](https://github.com/sleepepi/shhs-data-dictionary)

  1.3 Repository version should be initialized to `v0.1.0.pre` and a CHANGELOG should be created

2. Receipt of the source data

  2.1 Data Manager or Research Assistant will receive the source data in an easily accessible format (CSV, SAS, etc.)


  2.2 Source data should be imported into a combined SAS dataset, separated by visit (where appropriate), without any formats applied

  2.3 Newly created source dataset(s) should be stored on a network location accessible to any relevant research staff

3. Cleaning and deidentification of the source data

  3.1 Research Assistant will work with the Data Manager to identify variables that contain PHI or might otherwise be unnecessary to include in the dataset

  3.2 Research Assistant will use the newly created source dataset(s) as the basis for the creation of a data cleaning script

    3.2.1 Script should be written either in SAS or R and hosted publicly with the data dictionary

    3.2.2 Script should facilitate the importation of source data, scrubbing of missing data, deidentification of PHI, and exportation of finalized, version-controlled datasets

4. Creation of a JSON data dictionary

  4.1 Research Assistant will use the "clean" dataset to create a JSON data dictionary in conjunction with the formatting guidelines available on [Spout](https://www.github.com/sleepepi/spout)

  4.2 Research Assistant will use Spout to test (spout t) the structure of the data dictionary and the degree to which it covers (spout c) the variables found in the dataset

    4.2.1 Research Assistant or Data Manager will write additional Ruby tests for Spout, when necessary, to better check the integrity of the data dictionary

5. Publication of the dataset

  5.1 Research Assistant or Data Manager will use Spout to deploy (spout d) the completed dataset to a staging server [staging sleepdata.org](https://sleepepi.partners.org/edge/sleepdata)

    5.1.1 System Administrator will facilitate access to research staff deploying the dataset

  5.2 The dataset will be verified by Research Assistant(s) to ensure proper formating of JSON files

  5.3 After the dataset has been fully reviewed, Research Assistant or Data Manager will deploy (spout d) the dataset to [sleepdata.org](https://sleepdata.org)

    5.3.1 System Administrator will facilitate access to research staff deploying the dataset

  5.4 System Administrator or Data Manager will notify the NSRR community of the availability of the new dataset via a forum post on Sleepdata.org

References
----------
1. Spout Style Guide (https://www.github.com/sleepepi/spout)
