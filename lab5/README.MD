GEOG 458 Lab 5 — Vessel Traffic Through the Golden Gate Strait

1. Study Area and Dates
For this project, I selected the Golden Gate Strait in the San Francisco Bay Area, California, as my study area. The selected region includes the Golden Gate Bridge, the western entrance to San Francisco Bay, and nearby shipping routes. This area is an important connection between the Pacific Ocean and San Francisco Bay, where different types of vessels travel through a relatively narrow waterway.

I chose this location because I was interested in how different vessels use the relatively narrow geographic area. The narrow strait also provides a manageable study area for visualizing vessel movements and comparing different traffic patterns.

The vessel data was obtained from NOAA's AccessAIS, which provides Automatic Identification System (AIS) observations.

Date Range: from 2023-02-03 to 2023-02-06
Time zone: Pacific Standard Time (PST)

2. Interpretation
The animated map reveals clear differences in the spatial and temporal patterns of vessel traffic around the Golden Gate Strait.

Passenger vessels appear more frequently and tend to travel along repeated routes connecting four major locations: Sausalito, Fort McDowell, Alcatraz Island, and Fisherman's Wharf. Their movements are concentrated during daytime hours, suggesting that passenger traffic follows relatively regular schedules and established routes.

In contrast, cargo ships and tankers are less common within the study area. They generally travel through the strait rather than making frequent stops within the selected region. Their movements are also distributed more evenly between daytime and nighttime, unlike passenger vessels, which show a stronger daytime concentration.

These observations suggest that different vessel types use the Golden Gate Strait for different purposes. Passenger vessels primarily serve regular transportation routes between local destinations, while cargo ships and tankers are more associated with continuous maritime transportation through the region.

3. User-Focused Feature Proposal

One potential user of this map is a maritime traffic analyst who wants to understand vessel movements and traffic patterns in the Golden Gate Strait.

I would propose adding an interactive popup that displays detailed information when users click on a vessel's trajectory. The popup could include the vessel's name, type, speed, and identification number (MMSI). This would allow users to examine individual vessels rather than only observing general traffic patterns.

For example, the map shows that passenger vessels frequently travel between Sausalito, Fort McDowell, Alcatraz Island, and Fisherman's Wharf, while cargo ships and tankers tend to pass through the study area. With the proposed popup, analysts could identify specific vessels and investigate how their movements differ.

This feature is inspired by the deck.gl Interactivity Guide, which demonstrates how tooltips and object selection can provide additional information in interactive visualizations.

By combining vessel information with the existing type filter and time slider, the map would become more useful for analyzing maritime traffic patterns and understanding how different vessels use the Golden Gate Strait.