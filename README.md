# Methanol Opportunity Map, GitHub

This following GitHub repository contains the datasets, scope and definitions, field keys, and methodology for the Carbon Containment Lab's **Methanol Opportunity Map** (MOM). MOM is an interactive dashboard built on ArcGIS Experience Builder that can help one idenitfy where methanol supply, demand, and policy align to enable low-carbon marine fuel deployment.

------------------------------------------------------------------------

## Layers

| Layer | Contents |
|----|----|
| **1. Methanol Infrastructure & Ports** | Marine methanol bunkering facilities; global ports |
| **2. Relevant Regulations** | Emission control areas; green shipping corridors; country-level policy instrument summaries |
| **3. Shipping Activity** | Global shipping routes; AIS-derived global vessel-density raster; AIS-derived commercial vessel-density raster; AIS-derived passenger vessel-density raster; |

------------------------------------------------------------------------

## Repository Structure

```         
Methanol-Opportunity-Map/
├── README.md
├── DATA_LICENSE.md
├── 01_Datasets/                  
│   ├── Layer_1_Methanol_Infrastructure_and_Ports/
│   │   ├── Methanol_Bunkering_Facilities.gpkg
│   │   └── Ports.gpkg
│   ├── Layer_2_Relevant_Regulations/
│   │   ├── Emission_Control_Areas.gpkg
│   │   ├── Green_Shipping_Corridors.gpkg
│   │   └── Policy_Instruments.gpkg
│   └── Layer_3_Shipping_Activity/
│       ├── Shipping_Routes.gpkg
│       ├── Global_Vessel_Density.tif      
│       ├── Commercial_Vessel_Density.tif   
│       └── Passenger_Vessel_Density.tif    
├── 02_Scope_and_Definitions/     
└── 03_Keys/                      
```

------------------------------------------------------------------------

## Citation

If you're planning to use this data in a publication, cite the sources listed in [`DATA_LICENSE.md`](DATA_LICENSE.md) alongside this repository (see `CITATION.cff`)..

If you use this repository, please cite it as described in [`CITATION.cff`](CITATION.cff). GitHub renders a "Cite this repository" button in the sidebar that generates BibTeX / APA / other formats automatically once the file is present.

------------------------------------------------------------------------

## Contact

For issues, comments, additions, or questions about the data, please contact Nicole Gotthardt at nicole.gotthardt\@cclab.org.
