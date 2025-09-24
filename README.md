# irp-wildfire-data
A repository with resources for accessing and generating data from ELMFIRE for the IRP wildfire projects

## Datasets

This repository provides access to three wildfire simulation datasets generated using ELMFIRE:

### Dataset 1: Single Fuel Type
**Link:** [Dataset 1 - Single Fuel Type](link-to-dataset-1)

This dataset contains wildfire simulations using a single fuel type configuration. Each simulation runs for 259200 seconds (72 hours). The zip file includes:
- A `cases` folder containing output rasters for each simulation case
- A tracking file with run numbers and input parameters for each case in the directory

### Dataset 2: Multiple Fuel Types  
**Link:** [Dataset 2 - Multiple Fuel Types](link-to-dataset-2)

This dataset features wildfire simulations using multiple fuel types within the simulation set. Each simulation runs for 259200 seconds (72 hours). The zip file includes:
- A `cases` folder containing output rasters for each simulation case
- A tracking file with run numbers and input parameters for each case in the directory

### Dataset 3: Real World Fuel Raster
**Link:** [Dataset 3 - Real World Fuel Raster](link-to-dataset-3)

This dataset contains wildfire simulations using real-world fuel raster data. Each simulation runs for 42000 seconds (11.67 hours). The zip file includes:
- A `cases` folder containing output rasters for each simulation case
- An `inputs` folder containing input rasters (note: lhc and lwc values are included in the tracking file rather than as separate input rasters)
- A tracking file with run numbers and input parameters for each case in the directory

## File Structure

All zip files follow a consistent structure:
- **cases/**: Contains output rasters from the wildfire simulations
- **inputs/**: Contains input rasters (only in Dataset 3, excluding lhc and lwc values)
- **tracking file**: Contains run numbers and input parameters for each simulation case

## Simulation Duration
- Datasets 1 & 2: 259200 seconds (72 hours) per simulation
- Dataset 3: 42000 seconds (11.67 hours) per simulation
