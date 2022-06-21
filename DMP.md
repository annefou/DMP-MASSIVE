# Data Management Plan


## General information

### Administrative information

- Project principle investigator: Thomas Schellenberger
- Data Officer: 
    - Thomas Schellenberger, Researcher/PI, UiO; 
    - Anne Fouilloux, Researcher, UiO

### Resources for the management of the data

Funds for person effort, hardware, software and data management activities will be provided by NRC.
Archiving data in the NIRD archive, NVE's glacier database and the world glacier monitoring service, NSIDC.
In addition, research objects will be created and referenced in https://reliance.rohub.org/ for all published research 
products to increase the FAIRness of our results.

## Data 

### Input data

Data in Use: Freely available satellite data (optical, SAR) and value added products from satellite data (e.g. elevation models, snow cover maps, albedo).
In most cases, this input data will need to be downloaded and pre-process to facilitate our data analysis. To facilitate future research, we may keep a copy of this input data and not only the derived and final products.


### Output data


The final products will be open and use standard formats with additional metadata for provenance.


**Software**: Matlab, Python, ArcGIS, Gamma Remote Sensing, 
**Data Format**: Tiff, GeoTiff, Shapefile,

## Documentation and metadata

### Metadata

- Use standard metadata schemes in use for the NVE's glacier database, the World Glacier Monitoring Service (WGMS) and the National Snow and Ice Data Center (NSIDC).
- Additional metadata for data lineage (using s-ProvFlow Provenance framework for storage and access of data-intensive streaming lineage (https://gitlab.com/project-dare/s-ProvFlow).

### Quality measures

Same quality standards than used when publishing data in the NVE's glacier database, the World Glacier Monitoring Service (WGMS) and the National Snow and Ice Data Center (NSIDC). This would ensure our data is consistent and following international standards.

## Storage

- Data will be stored on NIRD 
- NIRD project ID: NS1000K

### NIRD services

- Advanced User Support
- Computing resources
- Data storage
- EasyDMP - Data Planning
- NIRD Toolkit
- Research Data Archive

#### More information

Advanced User support would be helpful for the deployment of the data cube and optimizing the resources. This would also ensure the sustainability of our project and long-term and easy access to the products produced after then end of the project.

### Data storage plan to store each year from 2020-2024

- 2022: 10 TiB Up to 50% backup
- 2023: 10 TiB Up to 50% backup
- 2024: 15 TiB Up to 25% backup
- 2025: 15 TiB Up to 25% backup
- 2026: 15 TiB Up to 25% backup

**Remark**: These numbers are maximum amount per year but we will monitor closely and optimize the data storage (remove unused data regularly).

### Primary usage of the storage

- computing (including HPC) input and output
- sharing data
- backup

**Remark**:
- Sharing input and output data within all the project participants
- Sharing output data to everyone once published.

### Data transfer

Not sure how much we would need to transfer yet.

**Remark**: This will depend on the ability of the NIRD toolkit to accomodate our computing needs. Our main objective would be to use the NIRD toolkit only to directly access our data from the NIRD project (NS1000K). However, for some computing heavy processing, we may need to stage data to the HPC storage (between 1 to 10 TB).

### Data Safety

- Most data will be open access. 
- from the NIRD toolkit service, we would have a specific "public" folder and we will set up a jupyterhub using the NIRD toolkit service.
- Anyone having access to this jupyterhub (access is controlled by the project coordinator and/or data manager) will be able to access public data.  Restricted data (to project partners only) will be controlled using classical UNIX permissions on the NIRD project area (only those having access to NS1000K) will be able to access the data.

### Data availability

All data will be made available to others.


