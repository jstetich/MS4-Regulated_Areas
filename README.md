# MS4 Regulated Areas 2019-2020

<img
    src="https://www.cascobayestuary.org/wp-content/uploads/2014/04/logo_sm.jpg"
    style="position:absolute;top:10px;right:50px;" />


GIS data showing MS4 regulated Areas in the Casco Bay Region

# Introduction
This archive includes geospatial data and a simple map showing the location
of MS4 regulated areas in the Casco Bay region, in Maine.

Curiously, areas regulated under the U.S. Clean Water Act's "Municipal 
Separate Storm Sewer System" program (known as the "MS4" program) are not 
based on municipal boundaries or even on local land use, but on whether the 
areas are designated by the U.S. Census as part of an "urbanized area". These
maps show how those designated areas have been interpreted by Maine DEP 
to identify areas in the MS4 program.

# Statement of Purpose
CBEP is committed to the ideal of open science.  Our State of the Bay data
archives ensure the science underlying the 2020 State of the Bay report is
documented and reproducible by others. The purpose of these archives is to
release raw data and data analysis code whenever possible to allow others to
review, critique, learn from, and build upon CBEP science.

# Archive Structure
CBEP 2020 State of the Bay data analysis repositories are divided into from two
to four sub-folders.  All archives contain at least an "Original_Data" and a
"Graphics" folder.  The other two folders are included if necessary.

- Original Data.  Original data, with a "DATA_SOURCES.md" or "READ ME.txt" file 
that documents data sources.
**DATA IN THIS FOLDER IS AS ORIGINALLY PROVIDED OR ACCESSED.** 

- Derived Data.  Data derived from the original raw data.  Includes
documentation of data reorganization steps, either in the form of files (R
notebooks, Excel files, etc.) that embody data transformations, or via README.md
or DATA_NOTES.md files.

- Analysis.  Contains one or more R Notebooks proceeding through the data
analysis steps. This often includes both preliminary data analysis --
principally graphical -- and detailed statistical modeling where necessary.

- Graphics.  Contains R Notebooks stepping through development of graphics, and
also copies of resulting graphics, usually in \*.png and \*.pdf formats.  These
graphics may differ from graphics as they appear in final State of the Bay
graphical layouts.

# Summary of Data Sources
All data included here are derived from public data released by Maine's Department
of Environmental Protection:

GIS data delineating current MS4 areas is available from Maine DEP
[website](https://www.maine.gov/dep/gis/datamaps/). 

The specific data shown here is titled "Municipal Separated Storm Sewer Systems 
Regulated Areas (5/27/2014)"
A link is provided for downloading a zipped shapefile here:
(https://www.maine.gov/dep/gis/datamaps/lawb_municipal_separate_stormwater_sewer_systems/municipal_separate_stormwater_sewer_systems_regulated_area_shapes.zip)
