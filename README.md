# Western Province Paddy Productivity Explorer

An interactive web map developed to support agricultural planning and paddy productivity assessment in the Western Province of Sri Lanka.

## Study Area
Western Province, Sri Lanka:
- Colombo District
- Gampaha District
- Kalutara District

## Purpose

The web map provides a planning-level estimate of paddy productivity by integrating environmental, irrigation and historical productivity information.

Users can explore individual paddy fields, understand the factors contributing to the estimated productivity level, and anonymously report actual paddy-field conditions and yield information.

## Productivity Estimation Model

The final productivity score was developed using four factors:

| Factor | Weight |
|---|---:|
| Rainfall | 35% |
| Soil conditions | 30% |
| Irrigation accessibility | 20% |
| Historical paddy productivity | 15% |

The final score is used to classify paddy lands into:

- High productivity
- Moderate productivity
- Low productivity

An approximate planning-level yield estimate in tonnes per hectare is also provided.

## Web Map Features

The interactive web map includes:

- Active paddy lands
- Estimated paddy productivity
- Estimated yield and production
- Average annual rainfall
- Topsoil pH
- Topsoil clay content
- Potential irrigation sources
- Historical productivity information
- Multiple basemap options
- Field-level information popups
- Farmer reporting function
- Automatic latitude and longitude entry for farmer reports

### Map Interaction

**Hover over a paddy field**  
Shows a quick productivity summary.

**Click a paddy field**  
Shows detailed information including rainfall, soil pH, clay content, irrigation accessibility, historical productivity, estimated yield and final productivity score.

**Report actual paddy yield**  
Allows farmers or community members to select a field location and submit actual field and harvest information through a linked Google Form.

## Main Data Sources

- Sri Lanka NSDI – mapped paddy lands
- WorldClim – precipitation data
- ISRIC SoilGrids – soil pH and clay content
- OpenStreetMap – potential irrigation and water-source information
- Department of Census and Statistics, Sri Lanka – historical paddy productivity data
- GADM – administrative boundaries
- Ground observations - from the studio field visits

## Important Note

The estimated productivity and yield values are intended for planning and educational purposes.

They should not be interpreted as precise field-level agricultural yield forecasts.

Rainfall, soil, irrigation accessibility and historical productivity datasets have different spatial and temporal resolutions, and farmer-reported information may require validation before use in formal planning decisions.

## Technologies Used

- Python
- Google Colab
- GeoPandas
- Rasterio
- Folium / Leaflet
- Google Forms
- GitHub Pages

## Live Web Map

The public web map will be available through GitHub Pages after deployment.
