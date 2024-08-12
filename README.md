# World-Factbook-JSON
This repository contains World Factbook archives in raw JSON data from 2000 to 2024. Each year is found in an individual JSON file "(year).json".

## The JSON File Structure
Each JSON file is structured to include the complete set of data on every country. The data types include text values, lists, numeric values, and dictionaries. Some numeric values are stored as dictionaries with additional fields such as text, suffix and distribution, where the suffix often represents the unit, and the text contains the full text value from the World Factbook. 

## Example
```json
{
  "Afghanistan": {
    "background": "Afghanistan was invaded and occupied by the Soviet Union in 1979...",
    "location": ["Southern Asia", "north and west of Pakistan", "east of Iran"],
    "geographic_coordinates": ["33 00 N", "65 00 E"],
    "map_references": "Asia",
    "area": {
      "total": {"value": 652000.0, "suffix": " sq km"},
      "comparative": "slightly smaller than Texas"
    },
    "land_boundaries": {
      "total": {"value": 5529.0, "suffix": " km"}
    },
    "climate": ["arid to semiarid", "cold winters and hot summers"],
    "terrain": ["mostly rugged mountains", "plains in north and southwest"],
    "elevation_extremes": {
      "lowest_point": {"text": "Amu Darya 258 m", "value": 258.0, "suffix": " m"}
    },
    "natural_resources": ["natural gas", "petroleum", "coal"],
    "land_use": {
      "arable_land": {"value": 12.0, "suffix": "%"}
    },
    "population": {
      "text": "25,838,797 (July 2000 est.)",
      "value": 25838797.0,
      "suffix": " (July 2000 est.)"
    }
  }
}
```

## Usage 
To work with it, download any of the JSON files provided that interests you and parse it. _The data should be seen as a basis for further refinement._ You could therefore use the data for analysis, visualization, or to be plugged into another application.
