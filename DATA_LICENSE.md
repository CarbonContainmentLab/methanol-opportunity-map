# Data Licensing & Attribution

Each dataset in `01_Datasets/` carries its own license and citation.

------------------------------------------------------------------------

## Layer 1 — Methanol Infrastructure & Ports

### Methanol Bunkering Facilities (`Methanol_Bunkering_Facilities.gpkg`)

-   **Methanol Bunkering Facilities** — Carbon Containment Lab
    -   **Source:** Internal CC Lab Workbook: 'Methanol Bunkering Facility.xlsx'
    -   **License**: Creative Commons Attribution 4.0 (CC BY 4.0), applying to CC Lab's compilation, selection, arrangement, and attribute schema. The underlying legal instruments are public texts and the facts about them are not subject to copyright.
    -   **Attribution**: Carbon Containment Lab, Methanol Opportunity Map — Methanol Bunkering Facilities, 2026.

### Ports (`ports.gpkg)`

-   **NGA World Port Index (Pub 150)** — U.S. National Geospatial-Intelligence Agency
    -   **Source Link**: <https://msi.nga.mil/Publications/WPI>
    -   **License**: Public domain. As a work of the United States Government, Pub 150 is not subject to copyright protection in the United States (17 U.S.C. § 105). No license is required for reuse, redistribution, or derivative works.
    -   **Attribution**: National Geospatial-Intelligence Agency, World Port Index (Pub 150), accessed 2026-07-30.
-   **PortWatch**'s Port Databse— International Monetary Fund (IMF)
    -   **Source Link**: <https://portwatch.imf.org/pages/data-and-methodology>
    -   **License**: Not an open license. Use is governed by the IMF's Copyright and Usage terms ([https://www.imf.org/external/terms.htm).](https://www.imf.org/external/terms.htm).) The IMF's general terms permit personal, noncommercial use only; however, published IMF statistical data is subject to special terms that permit downloading, extraction, derivative works, publication, distribution, and commercial use, subject to attribution and integrity conditions. Redistribution here is made in reliance on those special terms.
    -   **Attribution**: International Monetary Fund, IMF PortWatch (portwatch.imf.org), accessed 2026-07-30
    -   *Transformation notice: Per the IMF's integrity condition, note that this material has been transformed. PortWatch port records were joined to NGA World Port Index records by UN/LOCODE with a spatial fallback. This transformation is of the Carbon Containment Lab's and not endorsed by or attributable to the IMF.*

------------------------------------------------------------------------

## Layer 2 — Relevant Regulations

### Emission Control Areas (`Emission_Control_Areas.gpkg`)

-   **\`eca_reg14_sox_pm\`,\`eca_reg13_nox\`, \`World_Seas_IHO_v3\`, \`World_EEZ_v12\`** — Marine Regions
    -   **Source link:** <https://www.marineregions.org/downloads.php>
    -   **License:** Creative Commons Attribution 4.0 (CC BY 4.0). Marine Regions products have been CC-BY licensed since Maritime Boundaries version 11 (2019). License and terms: <https://www.marineregions.org/disclaimer.php>
    -   **Attributions:**
        -   Flanders Marine Institute (VLIZ), Belgium; (2020). Emission Control Areas (ECAs) designated under regulation 13 of MARPOL Annex VI (NOx emission control). Available online at <https://www.marineregions.org/.> <https://doi.org/10.14284/396.> Consulted on 2026-07-30.
        -   Flanders Marine Institute (VLIZ), Belgium; (2020). Emission Control Areas (ECAs) designated under regulation 14 of MARPOL Annex VI (SOx and particulate matter emission control). Available online at <https://www.marineregions.org/.> <https://doi.org/10.14284/397.> Consulted on 2026-07-30.
        -   Flanders Marine Institute (2018). IHO Sea Areas, version 3. Available online at <https://www.marineregions.org/.> <https://doi.org/10.14284/323.> Consulted on 2026-07-30.
        -   Flanders Marine Institute (2023). Maritime Boundaries Geodatabase: Maritime Boundaries and Exclusive Economic Zones (200NM), version 12. Available online at <https://www.marineregions.org/.> <https://doi.org/10.14284/632.> Consulted on 2026-07-30.

### Green Shipping Corridors (`Green_Shipping_Corridors.gpkg`)

-   **Green Shipping Corridors** — Carbon Containment Lab
    -   **Source:** Internal CC Lab Workbook: 'Green Shipping Corridors.xlsx'
    -   **License**: Creative Commons Attribution 4.0 (CC BY 4.0), applying to CC Lab's compilation, selection, arrangement, and attribute schema. The underlying legal instruments are public texts and the facts about them are not subject to copyright.
    -   **Attribution**: Carbon Containment Lab, Methanol Opportunity Map — Green Shipping Corridors, 2026.

### Policy Instruments (`Policy_Instruments.gpkg`)

-   **Policy Instruments** — Carbon Containment Lab
    -   **Source:** Internal CC Lab Workbook: 'Policy Instruments.xlsx'
    -   **License**: Creative Commons Attribution 4.0 (CC BY 4.0), applying to CC Lab's compilation, selection, arrangement, and attribute schema. The underlying legal instruments are public texts and the facts about them are not subject to copyright.
    -   **Attribution**: Carbon Containment Lab, Methanol Opportunity Map — Policy Instruments, 2026

------------------------------------------------------------------------

## Layer 3 — Shipping Activity

### Shipping Routes (`Shipping_Routes.geojson`)

-   **Global Shipping Lanes** — Benden, P.
    -   **Source Link**: <https://doi.org/10.5281/zenodo.6361763>; <https://github.com/newzealandpaul/Shipping-Lanes>
    -   **License**: Creative Commons Attribution 4.0 International (CC BY 4.0). The author's license grant excludes Statista from permitted reuse; that exclusion does not affect use by other parties.
    -   **Attribution**: Benden, P. (2022). Global Shipping Lanes [Data set]. Zenodo. <https://doi.org/10.5281/zenodo.6361763>
    -   *Transformation notice: A clipping was made to remove a route going to the northern-end of Europe for clarity*

### Vessel-Density Rasters (`Global_Vessel_Density.tif`, `Commercial_Vessel_Density.tif`, `Passenger_Vessel_Density.tif`)

-   **Global Shipping Traffic Density** — World Bank Group/International Monetary Fund
    -   **Source Lin**k: <https://datacatalog.worldbank.org/search/dataset/0037580/global-shipping-traffic-density>
    -   **License**: Creative Commons Attribution 4.0 (CC BY 4.0). Classified Public under the World Bank's Access to Information Classification Policy. License terms: <https://datacatalog.worldbank.org/public-licenses?fragment=cc>
    -   **Attribution**: World Bank Group, *Global Shipping Traffic Density*. Obtained through a partnership with the International Monetary Fund as part of the IMF's World Seaborne Trade Monitoring System; analysis supported by the World Bank's ESMAP and PROBLUE programs. Accessed 2026-07-30.
