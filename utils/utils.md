## Continent-Region Merging

This worklow merges **continents** (global base layer) with detailed administrative regions like **USA states** or **NUTS regions** into unified GeoJSON files.

## Generated Files

|                       **Input**                       |               **Output**              |                  **Description**                 |
|:-----------------------------------------------------:|:-------------------------------------:|:------------------------------------------------:|
|        continents.geojson + USA_states.geojson        |       States_of_the_USA.geojson       | USA states nested within North America continent |
| continents.geojson + nuts1_updated_uk_regions.geojson | NUTS1_regions_(2024 edition).geojson |       NUTS1 regions within Europe continent      |
| continents.geojson + nuts2_updated_uk_regions.geojson | NUTS2_regions_(2024 edition).geojson |       NUTS2 regions within Europe continent      |
| continents.geojson + nuts3_updated_uk_regions.geojson | NUTS3_regions_(2024 edition).geojson |       NUTS3 regions within Europe continent      |