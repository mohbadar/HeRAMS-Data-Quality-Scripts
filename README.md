# HeRAMS-Scripts

- Data Timeliness and Completeness: This script identifies health facilities that have not been updated, completed, or synced since a configurable date. 
- Duplicate: Focuses on identifying duplicate health facilities using matching based on a combination of different criteria. Currently, we use five approaches to identify duplicates. 
- GPS Boundaries: Checks if provided GPS coordinates are within the country’s boundary. It can also identify the state, province, and city, but requires separate configuration for each country based on availability of the data. 
- Catchment Population Outlier Check: Identifies health facilities with outlier catchment population figures. 
- HF Status vs Functionality: Verifies various scenarios such as facilities that are existing but not functioning, planned but labeled as functioning, etc. 
- Building Type and Building Damage: Ensures that for mobile teams, the building type is set correctly, and checks if building damage is set for physical health facilities correctly. The script detects if the building damage or type for physical health facilities is inaccurately marked as “Not relevant.” 
- Health Service Availability: Currently, the admin dashboard serves as a good tool for this purpose. However, we can develop additional scripts if needed.

- VV File Preparation: this script is to prepare data to import into LimeSurvey
