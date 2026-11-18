# Lab 6 Questions to Explore

## 1. Choose two counties and inspect their trends. Does a high 2020 population necessarily imply a high percentage growth since 2000?

No. For example, King County has a much larger population than Franklin County, but total population and percentage growth measure different things. A smaller county can grow faster in percentage terms even if it gains fewer residents. 

## 2. How does a map help you form a question that the line chart can investigate?

The map reveals where counties with high or low populations are located. It can prompt questions such as whether a populous county has grown steadily or rapidly. Selecting that county links the map to the line chart, which shows how its population changed from 2000 to 2020.

## 3. What geographical context would be lost if non-matching counties disappeared completely?

We would lose the locations, shapes, and neighboring relationships of the other counties. Keeping them visible at low opacity helps us understand where the selected counties are within Washington and compare their geographic context.

## 4. Where does the code turn an interaction result into a new visualization input?

The `updateDashboard()` function converts the current pinned, hovered, or search-filtered counties into a shared `features` array. It then passes that array to `highlightCounties(features)` and `updateLinkedChart(features)`. The second call turns the interaction result into input for the D3 population trend chart.

# Independent Tasks

## 1. Population Growth Indicator

Added an interactive map indicator selector to compare total population in 2020 with population growth from 2000 to 2020. The growth rate is calculated using the POP2000 and POP2020 fields in the GeoJSON dataset.
Users can switch between the two choropleth maps, with the map colors and legend updating accordingly. 

## 2. Hover Popup

Implemented a hover popup using Mapbox GL JS to display each county's name, 2020 population, and population growth rate.The popup follows the mouse when hovering over a county and disappears when the mouse leaves the county layer or clicks the map. It also respects the search filter, preventing unrelated counties from displaying information.This feature provides precise numerical information alongside the map's visual patterns.