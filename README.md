# Overview
This repository contains two datasets providing information about Halal grocery stores and mosques in the City of Toronto. These datasets are intended for use in mapping, spatial analysis, community resource planning, and more.

## Files

### 1. `TorontoHalalStores.csv`
Contains details of Halal grocery stores, butcher shops, and supermarkets.

**Columns:**
- **Store Name**: Name of the store  
- **Address**: Full address including street, city, and postal code  
- **Maps Coordinates**: Combined latitude and longitude in a single string  
- **Notes**: Additional details (e.g., cultural focus like Afghan, Desi, Turkish)  
- **Latitude**: Decimal latitude for mapping  
- **Longitude**: Decimal longitude for mapping  

**Example Row:**
Petra Ave Market, "150 Dundas St W Unit: 102, Toronto, ON M5G 1C6", "43.655562481204285, -79.3853714460048", Not a full butcher, 43.655562481204285, -79.385371446004

---

### 2. `TorontoMosques.csv`
Contains details of mosques and Islamic centres in Toronto.

**Columns:**
- **Mosque Name**: Name of the mosque or Islamic centre  
- **Address**: Full address including street, city, and postal code  
- **Maps Coordinates**: Combined latitude and longitude in a single string  
- **Notes**: Additional details (e.g., size, cultural affiliation like Bosnian, Turkish)  
- **Latitude**: Decimal latitude for mapping  
- **Longitude**: Decimal longitude for mapping  

**Example Row:**
ISNA Jami Mosque, "56 Boustead Ave, Toronto, ON M6R 1Y9", "43.65347142007285, -79.45457397677004", Larger mosque, 43.65347142007285, -79.45457398

---

## Usage
- **Mapping**: Use latitude and longitude columns for plotting on maps.  
- **Filtering**: Filter by cultural notes or neighborhood for targeted analysis.  
- **Integration**: Combine with other datasets for demographic or accessibility studies.

---

## Notes
- Data is based on publicly available addresses and community resources.  
- Some entries include cultural or size notes for context.  
- Coordinates are in **WGS84** format (decimal degrees).
