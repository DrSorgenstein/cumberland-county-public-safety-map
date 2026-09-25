# Cumberland County Public Safety Map

A static GitHub Pages dashboard for Cumberland County, Pennsylvania’s publicly released active incident feed. Enable GitHub Pages on the repository root.

The map queries the county’s Active_Incidents_Public ArcGIS FeatureServer at runtime. Counts represent returned public calls only, not verified crimes, full police activity, historical trends, or crime rates. Cumberland County says most law enforcement incidents are withheld. Use the PA UCR and PSP CAID links for broader crime research. No incident data is stored by this site.

Filters include service, municipality and text; the filtered public records can be exported to CSV. Leaflet and OpenStreetMap tiles require internet access. Feed availability and browser cross-origin access depend on the county service. This is not a dispatch system. Call 911 for emergencies.

Optional overlay: 2023 mapped fatal or suspected serious injury crashes from the HATS ArcGIS layer, filtered to PennDOT county code 21. Historical road safety context only; not a crime signal. CRIMEWATCH links to participating agency reports, not a complete countywide data feed.

**Data freshness:** During publication on September 25, 2026, the county ArcGIS endpoint returned four incidents dated November 29, 2023. The site flags the newest event date, marks stale records as an archive, and defaults to the dated 2023 crash layer when the incident feed is old. Use official WebCAD for current calls.
