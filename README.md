# Earthquake Data Visualization Project (Geospatial Mapping of Earthquake Events)


This project is focused on creating an interactive geospatial map to visualize earthquake events around the world. The inspiration for this project came after I experienced my first earthquake in Los Angeles, which sparked my interest in understanding seismic activities through data.

[Check out the interactive map here:-)](https://annalzrv.github.io/earthquake_map.html)

## Project Overview

The primary goal of this project is to visualize global earthquake data on an interactive map. By leveraging the power of geospatial analysis, this map provides insights into where and when earthquakes occur, as well as their magnitude and depth. The project serves as a starting point for further exploration into seismic patterns and trends.

## Data Source

The dataset used in this project is obtained from the [USGS Earthquake Database](https://www.kaggle.com/datasets/usgs/earthquake-database/data) available on Kaggle. The dataset is comprehensive, covering earthquake events worldwide from the year 1965 to 2016.

### Key Features of the Dataset:
- **Time Span:** The dataset includes earthquake records from 1965 to 2016, allowing for long-term analysis of seismic activity.
- **Attributes:**
  - **Date and Time:** When the earthquake occurred.
  - **Location:** Latitude and longitude coordinates, along with specific details about the location.
  - **Magnitude:** The magnitude of the earthquake, which indicates the energy released during the event.
  - **Depth:** The depth at which the earthquake occurred beneath the Earth's surface.
  - **Intensity:** Where available, the dataset also includes intensity measures like CDI (Community Determined Intensity) and MMI (Modified Mercalli Intensity).
  - **Tsunami Information:** Indicators of whether the earthquake was followed by a tsunami.
  - **Additional Metadata:** Includes details such as the type of magnitude, the seismic network that recorded the event, and the event status.

### Data Quality:
- The dataset contains some missing values, particularly in fields such as intensity and depth errors, which may be due to the limitations of recording equipment or the inaccessibility of certain regions.
- Despite these gaps, the dataset remains one of the most detailed and reliable sources of earthquake information available to the public.

## Project Features

- **Interactive Geospatial Map**: A dynamic map that visualizes earthquake locations worldwide, with markers representing the magnitude and depth of each event.
- **Pop-up Details**: Each marker on the map includes a pop-up with detailed information about the earthquake, such as its magnitude, depth, and the date it occurred.
- **Visual Insights**: The map provides an intuitive way to explore seismic activity, helping users understand the distribution and frequency of earthquakes across different regions.

## Next Steps

This project is part of an ongoing exploration into earthquake data. In the next phase, I will be conducting a time series analysis to identify patterns and trends in seismic activity over time. This analysis will help in understanding whether there are cyclical patterns or other temporal trends that could provide further insights into earthquake behavior.

## Contributing

Contributions to this project are welcome! If you have any ideas, suggestions, or improvements, feel free to open an issue or submit a pull request.
