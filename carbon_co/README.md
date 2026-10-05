# carbon_co widgets

Carbon County, UT versions of the client-specific FWFS widgets.
Live at `https://consor-dev.github.io/fwfs-widgets/carbon_co/<file>`.

Generic widgets stay at the repo root and are shared by every client:
day_1_0to6, day_1_html, day_2_html, day_3_html, nowcast(.html), ndfd-qpf-6hr,
mrms-product-guide (and mt-clock in its own repo).

## Still to fill in (search for `TBD` and `TODO(carbon_co)`)
- how_this_works / representative_storm: Carbon storm count, storm positions, rep-storm depths, Atlas 14 point, return periods (DRAFT banner on representative_storm until done)
- FWFS_Threshold_Table: Carbon basin area; re-check thresholds, NDFD point count, gauge count
- fwfs_radar_tutorial: Carbon basin names; KMTX vs KGJX in WeatherWise links; coverage notes
- storm_motion_panel: BASIN_CENTRE (currently AOI centre) and EDGE_FROM_CENTRE_KM (Moab values)
- FWFS_Legal_Disclaimer: adopted date
- flash_risk_panel: reads ./flash_risk_latest.json and ./flash_risk_*_latest.png from THIS folder;
  shows "feed error" until the Carbon nowcast job publishes there
