These are the second version of the OSD 2018 data, on which a slightly more extended QC has been performed on the digitised logsheeets: where stations returned values in units that were not as requested in the SOPs and the OSD Handbook, if it was possible a conversion to the requested unit was carried out, and if not the value was discarded. An indicator of the type of conversion done is contained in a flag column in the data spreadsheet with more information provided in the metadata spreadsheet, and details of the conversions are provided as an additional document.

* CSV files with the collected environmental, event, and omics data (being [ENA accession numbers](https://www.ebi.ac.uk/ena/browser/home)) - where data flags were added to mitigate confusion about the units, and character malformations were corrected. This version is provided in two forms: 
    * [OSD18Data_HumanReadable_version2.csv](https://raw.githubusercontent.com/ocean-sampling-day/OSD2018/main/QualityControlledData/version2/OSD18Data_HumanReadable_version2.csv) which is a version that humans will find more comfortable to read
    * [OSD18Data_MachineReadable_version2.csv](https://raw.githubusercontent.com/ocean-sampling-day/OSD2018/main/QualityControlledData/version2/OSD18Data_MachineReadable_version2.csv) which is a version being necessary to generate the turtle file
* CSV files with the metadata to accompany these data files:
    * [OSD18Metadata_HumanReadable_version2.csv](https://raw.githubusercontent.com/ocean-sampling-day/OSD2018/main/QualityControlledData/version2/OSD18Metadata_HumanReadable_version2.csv) to accompany the equivalently-named Data file
    * [OSD18Metadata_MachineReadable_version2.csv](https://raw.githubusercontent.com/ocean-sampling-day/OSD2018/main/QualityControlledData/version2/OSD18Metadata_MachineReadable_version2.csv), to accompany the equivalently-named Data file
* A turtle file with the collected environmental, event and omics data described in RDF triples: [OSD19Data_MachineReadable_version2.ttl](https://raw.githubusercontent.com/ocean-sampling-day/OSD2018/main/QualityControlledData/version2/OSD18Data_MachineReadable_version2.ttl).  
This file was generated using [this template](https://raw.githubusercontent.com/ocean-sampling-day/OSD2018/main/QualityControlledData/version2/OSD18Data_MachineReadable_version2.ldt) with [PySUByT](https://github.com/vliz-be-opsci/pysubyt).
* An explanation of the conversions [UnitConversions.pdf](https://raw.githubusercontent.com/ocean-sampling-day/OSD2018/main/QualityControlledData/version2/UnitConversions.pdf)


