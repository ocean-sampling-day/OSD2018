# Ocean Sampling Day 2018 space

These are the (meta)data and documentation files for Ocean Sampling Day 2018. The metadata record for this event is published in the IMIS datasets catalogue (https://www.vliz.be/en/imis?module=dataset&dasid=7916). The same data can be obtained as a direct download from that IMIS record, but a more annotated set of data (in particular the machine/developer-readable versions) are provided here. Also provided via this Github space are the OSD2014 (https://github.com/ocean-sampling-day/ToPublish/tree/main/IMIS/OSD2014) and OSD2019 data (https://github.com/ocean-sampling-day/ToPublish/tree/main/IMIS/OSD2019).   


The documentation provided here includes:

* The OSD Handbook (from 2016 still applies in 2018)
* The two sampling protocols used by OSD
* Instructions that were provided to the sampling scientists for filling in their logsheets


The data files provided here are:
* CSV files with the collected environmental, event, and omics data (being [ENA accession numbers](https://www.ebi.ac.uk/ena/browser/home)):  
    * version 1 - published on 29/11/2021: [OSD18Data_version1.csv](https://github.com/ocean-sampling-day/ToPublish/blob/main/IMIS/OSD2018/OSD18Data_version1.csv)
    * version 2 - published in April 2022:  
    Data flags were added to mitigate confusion about the units and character malformations were corrected. This version is provided in two forms:
        - [OSD18Data_HumanReadable_version2.csv](https://github.com/ocean-sampling-day/ToPublish/blob/main/IMIS/OSD2018/OSD18Data_HumanReadable_version2.csv) which is a version that humans will find more comfortable to read
        - [OSD18Data_MachineReadable_version2.csv](https://github.com/ocean-sampling-day/ToPublish/blob/main/IMIS/OSD2018/OSD18Data_MachineReadable_version2.csv) which is a version being necessary to generate the turtle file;  
    
* CSV files with the metadata to accompany these data files
    * [OSD18Metadata_version1.csv](https://github.com/ocean-sampling-day/ToPublish/blob/main/IMIS/OSD2018/OSD18Metadata_version1.csv) 
    * [OSD18Metadata_HumanReadable_version2.csv](https://github.com/ocean-sampling-day/ToPublish/blob/main/IMIS/OSD2018/OSD18Metadata_HumanReadable_version2.csv) 
    * [OSD18Metadata_MachineReadable_version2.csv](https://github.com/ocean-sampling-day/ToPublish/blob/main/IMIS/OSD2018/OSD18Metadata_MachineReadable_version2.csv), with the latter being necessary to generate the turtle file.
* A turtle file with the collected environmental, event and omics data described in RDF triples: [OSD18Data_MachineReadable_version2.ttl](https://github.com/ocean-sampling-day/ToPublish/blob/main/IMIS/OSD2018/OSD18Data_MachineReadable_version2.ttl).  
This file was generated using [this template](https://github.com/ocean-sampling-day/ToPublish/blob/main/IMIS/OSD2018/OSD18Data_MachineReadable_version2.ldt) with [PySUByT](https://github.com/vliz-be-opsci/pysubyt).
* The station information spreadsheet

All of the data collected in the Data sheets are taken from the logsheets that were provided by each sampling station. A certain amount of QC was performed on the values in the logsheets: where stations returned values in units that were not as requested in the SOPs and the OSD Handbook, we added a comment in the flag columns of the data spreadsheets to highlight this fact. The units themselves are included as separate columns along with each measured parameter in the data spreadsheets and are also explained in the metadata spreadsheets. Note that we did not perform any unit conversions, nor did we do any checking for potentially suspect values: the values here are exactly as provided on the logsheets from each station.

Scans of the original logsheets can be downloaded from the Marine Data Archive: 	https://mda.vliz.be/directlink.php?fid=VLIZ_00000615_625ebb1f06a6d729944697
