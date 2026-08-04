---
title: "Web of Science PostgreSQL Database"
layout: "home"
description: "This tutorial will help you get up and running querying the Web of Science PostgreSQL database. It will cover accessing the high performance computing environment, querying the database via SQL statements and from within a python script, and downloading the results of the query. You will need a Compute Canada account with the proper credentials to access this database. If you haven’t done so already, you should first follow the instructions to get your account set up."
staff:
    - name: Kara Handren
      link: https://library.utoronto.ca/staff/kara-handren
maintainer:
    - name: Leslie Barnes
      link: https://library.utoronto.ca/staff/leslie-barnes
created_date: 2022-02-07
permalink: "/"  #! Remove this if not the homepage
nav_order: 0
has_children: true
has_toc: false
---
# Web of Science PostgreSQL Database
The [Web of Science Raw Data (XML)](https://mdl.library.utoronto.ca/technology/text-data-mining-software/web-science-raw-data-xml) is a metadata extract of the Web of Science Database and includes over 12,500 journals from around the world in over 250 Science, Social Science and Humanities disciplines. Conference proceedings and book data are also included. Data are available from 1900 and currently include over 63 million article records and 1 billion cited references.

This XML has been converted into an object-relational database (updated periodically) and is available to UofT faculty, staff, and students for querying in a high performance computing environment offered by [SciNet](https://www.scinethpc.ca/). Currently the database contains data up to and including Dec. 31, 2024.

This is an excellent dataset for use in text and data mining research, particularly focusing on bibliometrics and citation analysis. It can be programmatically queried via SQL statements directly or through python scripts, with no limits on query results.

## Restrictions
The [Web of Science Raw Data (XML)](https://mdl.library.utoronto.ca/technology/text-data-mining-software/web-science-raw-data-xml) and this PostgreSQL database are intended for academic study, research, teaching and administrative use at the University of Toronto. The data is restricted to University of Toronto faculty, students, researchers and staff. It is strictly forbidden to use this dataset or derivatives for commercial or Non-University of Toronto specific use. Further distribution of this data or derivatives, is prohibited.

## Access
In order to access the database, you must first gain access to the high performance computing environment through a [multi-step process](https://mdlutoronto.github.io/postgresql-databases-access/) to create the appropriate account (may take a few days to create the account initially).

## Working with the Database
You query the database using SQL statements, and then can either continue to work with the results within this computing environment, or download the results as a CSV file.

For help with constructing your SQL queries:

* [This document](https://maps.library.utoronto.ca/docs/postgresql/WoS/db-structure.pdf) describes the various tables and their contents.
* This [Entity Relationship Diagram (ERD)](http://maps.library.utoronto.ca/docs/postgresql/WoS/WoS_ERD.pdf) provides a visual representation of all of the tables within the database and their relationships, including bridging tables. 

## Help
If working with object-relational databases, SQL, and/or high performance computing environments are new to you, check out the following tutorials to help you get started.

If you have any question, feel free to [contact us](https://mdl.library.utoronto.ca/about/contact-form).

**Technique:** [Searching for maps and data](https://mdlutoronto.github.io/tutorials-search/?technique=Searching+for+maps+and+data), [Text and Data Mining](https://mdlutoronto.github.io/tutorials-search/?technique=Text+and+Data+Mining) \| **Tools:** [Web of Science](https://mdlutoronto.github.io/tutorials-search/?tool=Web+of+Science)