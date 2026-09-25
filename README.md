# Cumberland County Public Safety Map

A static GitHub Pages dashboard for Cumberland County, Pennsylvania’s publicly released active incident feed. Enable GitHub Pages on the repository root.

The map queries the county’s Active_Incidents_Public ArcGIS FeatureServer at runtime. Counts represent returned public calls only, not verified crimes, full police activity, historical trends, or crime rates. Cumberland County says most law enforcement incidents are withheld. Use the PA UCR and PSP CAID links for broader crime research. No incident data is stored by this site.

Filters include service, municipality and text; the filtered public records can be exported to CSV. Leaflet and OpenStreetMap tiles require internet access. Feed availability and browser cross-origin access depend on the county service. This is not a dispatch system. Call 911 for emergencies.

Optional overlay: 2023 mapped fatal or suspected serious injury crashes from the HATS ArcGIS layer, filtered to PennDOT county code 21. Historical road safety context only; not a crime signal. CRIMEWATCH links to participating agency reports, not a complete countywide data feed.

**Data freshness:** During publication on September 25, 2026, the county ArcGIS endpoint returned four incidents dated November 29, 2023. The site flags the newest event date, marks stale records as an archive, and defaults to the dated 2023 crash layer when the incident feed is old. Use official WebCAD for current calls.

## 2026 mapped reports

`reported-2026.json` is a curated, non-exhaustive set of 2026 reports from participating departments on CRIMEWATCH. Every record includes a source URL, date, agency, disposition, reference where available, and an approximate mapped point. The source reports determine the incident label; an arrest, charge, report, or open case is not a conviction. Street-block locations are geocoded to a representative address within the named block, not a verified incident point. The public geocoding service is ArcGIS World Geocoding Service. No private-residence locations or victim-sensitive offenses were selected. This snapshot was assembled September 25, 2026; it does not update automatically. Additional reports may exist in covered areas, and other municipalities may have no entries because their data was not curated here. Do not interpret marker density as crime risk or compare counts between municipalities.
