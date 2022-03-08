# ReadMe
This dataset was made for a Data Curation course at the University of Washington in March 2022. It contains information on public library data related to digital book and physical book collections, expenditures, and circulation from 2008, 2017, 2018, and 2019. This data is freely available to the public, although the primary intended audiences are public library researchers and advocates. 
The data is available in .xlsx and .csv formats and includes three tables. 
## Table of Contents
- [Naming](#naming)
- [Data Dictionary](#datadictionary)
- [Metadata](#metadata)
- [Contact](#contact)
## Naming
The naming convention for these files is as follows:
      
      year-DataTableName
_Year_ is the most recent year reflected in the data table, and 

_DataTableName_ indicates what type of public library data is collected in each table.

## Data Dictionary
| **Variable** | **Variable Name** | **Measurement Unit** | **Allowed Values** | **Definition** |
| --- | --- | --- | --- | --- |
| **Location** | Location | String | WA or National | Where the public library data was taken from, either Washington State (WA) or national public library data (National) |
| **rcbooks2008** | Rural collection of books in 2008 | Numerical | Integers greater than 0 | The total collection of print books, in the thousands, held by rural libraries in 2008|
| **rcbooks2017** | Rural collection of books in 2017 | Numerical | Integers greater than 0 | The total collection of print books, in the thousands, held by rural libraries in 2017 |
| **prate_rcbooks** | Percent change rate in rural collections of books | Numerical | Any number | The percent change in rural collections of books between 2008 and 2017, expressed in positive or negative form |
| **rcebooks2008** | Rural collection of eBooks in 2008 | Numerical | Integers greater than 0 | The total collection of ebooks, in the thousands, held by rural libraries in 2008 - audiobooks are excluded |
| **rcebooks2017** | Rural collection of eBooks in 2017 | Numerical | Integers greater than 0 | The total collection of ebooks, in the thousands, held by rural libraries in 2017 - audiobooks are excluded. |
| **prate_rcebooks** | Percent change rate in rural collections of ebooks | Numerical | Any number |The percent change in rural collections of ebooks between 2008 and 2017, expressed in positive or negative form |
| **tc_exp_2018** |Total collection expenditures in 2018 | Numerical | Integers greater than 0 | The total expenditures, in the thousands, that public libraries from the designated location have spent on all print, electronic, and other materials, in 2018  |
| **tc_exp_2019** | Total collection expenditures in 2019 | Numerical | Integers greater than 0 | The total expenditures, in the thousands, that public libraries from the designated location have spent on all print, electronic, and other materials, in 2019 |
| **pchange_tc_exp** | Percent change in total expenditures | Numerical | Any number | The percent change in total expenditures that public libraries have spent on all collections between 2018 and 2019  |
| **pp_tc_exp2018** | Percent print of total collection expenditures in 2018 | Numerical | Integers greater than 0| The percent of total collection expenditures that public libraries spent on print materials in 2018 |
| **pp_tc_exp2019** | Percent print of total collection expenditures in 2019 | Numerical | Integers greater than 0 | The percent of total collection expenditures that public libraries spent on print materials in 2019 |
| **ppchange_tc_exp** | Percent change in print expenditures  | Numerical | Any number |The percent change in total collection expenditures in public libraries that is spend on print materials between 2018 and 2019 |
| **pe_tc_exp2018** | Percent eBook of total collection expenditures in 2018| Numerical | Integers greater than 0 | The percent of total collection expenditures that public libraries spent on electronic materials in 2018. Electronic materials include eBooks, e-serials, government documents, databases, electronic files, reference tools, scores, maps, or pictures in digital format |
| **pe_tc_exp2019** | Percent eBook of total collection expenditures in 2019| Numerical | Integers greater than 0 | The percent of total collection expenditures that public libraries spent on electronic materials in 2019. Electronic materials include eBooks, e-serials, government documents, databases, electronic files, reference tools, scores, maps, or pictures in digital format  |
| **pechange_tc_exp** | Percent change in eBook expenditures | Numerical | Any number| The percent change in total collection expenditures in public libraries that is spend on electronic materials between 2018 and 2019, expressed in positive or negative form |
| **pmaterials2018** | Print materials 2018 | Numerical | Integeres greater than 0 |The number of print materials, in the thousands, that are held by the public libraries in the given location, in 2018 |
| **pmaterials2019** |Print materials 2019 | Numerical | Integers greater than 0 | The number of print materials, in the thousands, that are held by the public libraries in the given location, in 2019 |
| **pchange_pmaterials** | Percent change in print materials| Numerical | Any number| The percent change in print material collections held by public libraries in the given location between 2018 and 2019, expressed in positive or negative form |
| **pmaterials_pcapita2018** | Print materials per capita in 2018| Numerical | Integers greater than 0 | The number of print materials per capita held by public libraries at a given location in 2018 |
| **pmaterials_pcapita2019** | Print materials per capita in 2019 | Numerical | Integers greater than 0| The number of print materials per capita held by public libraries at a given location in 2019|
| **pchange_pmaterialspcapita** | Percent change in print materials per capita | Numerical | Any number | The percent change in print materials per capita between 2018 and 2019, expressed in positive or negative form |
| **eBooks2018** |  eBooks in 2019 | Numerical | Integers greater than 0 |The number of eBooks, in thousands, held by public libraries at a given location in 2018 |
| **eBooks2019** | eBooks in 2019 | Numerical | Integers greater than 0 | The number of eBooks, in thousands, held by public libraries at a given location in 2019|
| **pchange_eBooks** | Percent change in eBooks  | Numerical | Any number | The percent change in the number of eBooks held by public libraries between 2018 and 2019, expressed in positive or negative form|
| **eBooks_pcapita2018** | eBooks materials per capita in 2018 | Numerical | Integers greater than 0 | The number of eBooks per capita held by public libraries at a given location in 2018 |
| **eBooks_pcapita2019** | eBooks per capita in 2019  | Numerical | Integers greater than 0 |The number of eBooks per capita held by public libraries at a given location in 2019 |
| **pchange_eBookspcapita** | Percent change in eBooks per capita| Numerical | Any number | The percent change in the number of eBooks per capita held by public libraries between 2018 and 2019, expressed in positive or negative form | 

## Metadata
Schema Used: Project Open Data

| **Attribute** | **Value** |
| --- | --- |
| title | eBook and Print Book Public Library Data |
| description| This dataset contains information on public library data related to eBook and physical book collections, expenditures, and circulation from 2008, 2017, 2018, and 2019 in Washington State and the entire United States. This dataset was curated by a student at the University of Washington in 2022.|
| keyword| “public library”, “washington”, “eBook”, “book”,|
| modified | 2022-03-07 |
| publisher | Erin Andreassi |
| contactPoint | Erin Andreassi at erinandreassi@gmail.com |
| accessLevel | public |
| accessURL | https://github.com/eandre2019/PublicLibraryData_2008-2019  |
| rights|This data is freely available to everyone, no permission is required to use or share this data |

## Contact
Erin Andreassi
erinandreassi@gmail.com

