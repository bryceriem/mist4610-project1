# Group-4-MIST-4610-Group-Project-2
# Team Name: 
61608 Group 4
# Team Members:
1. Jacob Witucki [@JacobWitucki](https://github.com/JacobWitucki)
2. Ashleigh Serrafin [@AshleighSerafin](https://github.com/AshleighSerafin)
3. Bryce Riemersma [@Bryceriem](https://github.com/Bryceriem)
4. Lily Shaw  [@Lilyshaw714](https://github.com/Lilyshaw714)
5. Matt Miller  [@matthewroanmiller](https://github.com/matthewroanmiller)
6. Shruti Alladi  [@salladi13](https://github.com/salladi13)
# Dataset and Questions
Description of Data Model: 
The **USDOT dataset** available through Snowflake’s Data Foundations is a structured, aviation-focused dataset that provides detailed information on airline operations within the United States. It is designed to support analysis of air travel activity, carrier performance, and transportation trends.  

At a high level, the dataset contains **monthly records of domestic, non-stop flight segments** reported by both U.S. and international air carriers. These records capture operational details such as routes, carriers, and activity levels, making it useful for analyzing airline networks, traffic patterns, and industry performance over time.  

The dataset is organized using Snowflake’s standardized schema, which separates data into **entities and time series**. Entity tables provide reference information about core components of the aviation system—such as airlines, aircraft, and airports—while time series tables store measurable activity (e.g., flight volumes) across time periods.  

Tables included in the USDOT dataset are: 

(Database: SNOWFLAKE_PUBLIC_DATA_FREE Schema: PUBLIC_DATA_FREE)  

(EX: SNOWFLAKE_PUBLIC_DATA_FREE.PUBLIC_DATA_FREE.AIRCRAFT_CARRIER_INDEX)  

1. AIRCRAFT_CARRIER_INDEX (955 Rows)
 
<img width="849" height="591" alt="Screenshot 2026-04-15 at 12 39 11 PM" src="https://github.com/user-attachments/assets/2d92ee06-1e53-445f-b8c8-b1a8b2f58e3b" />
 
2. AIRCRAFT_INDEX (697 Rows)

<img width="847" height="325" alt="Screenshot 2026-04-15 at 12 40 08 PM" src="https://github.com/user-attachments/assets/980af716-8de8-41f8-a056-9bb8ae099619" />  

3. AIRPORT_INDEX (5,107 Rows)  

<img width="765" height="644" alt="Screenshot 2026-04-15 at 12 40 57 PM" src="https://github.com/user-attachments/assets/8d20b697-736b-4fe7-945f-6e228fc5753c" />  

4. US_DEPARTENT_OF_TRANSPORTATION_ATTRIBUTES (10 Rows) 

<img width="764" height="287" alt="Screenshot 2026-04-15 at 12 42 13 PM" src="https://github.com/user-attachments/assets/1dd3477f-c93a-4d31-bf31-c474e49d9b54" />  

5. US_DEPARTENT_OF_TRANSPORTATION_ATTRIBUTES_PIT (10 Rows)

<img width="765" height="446" alt="Screenshot 2026-04-15 at 12 44 28 PM" src="https://github.com/user-attachments/assets/56173aea-a4dc-4346-88f0-f74a53b12f27" />

6. US_DEPARTENT_OF_TRANSPORTATION_TIMESERIES (123,250,510 Rows)

<img width="680" height="700" alt="Screenshot 2026-04-15 at 12 45 16 PM" src="https://github.com/user-attachments/assets/bce1d72c-41fa-4fc3-971d-38b8feaa5860" />

7. US_DEPARTENT_OF_TRANSPORTATION_TIMESERIES_PIT (336,370,033 Rows)

<img width="567" height="709" alt="Screenshot 2026-04-15 at 12 45 50 PM" src="https://github.com/user-attachments/assets/d22511cd-3576-452d-9390-a3bf83a8119e" />

Overall, this dataset is structured to enable **consistent, time-based analysis of U.S. air transportation**, supporting use cases such as trend analysis, route optimization, and performance benchmarking. It is particularly valuable for analysts, data scientists, and businesses interested in aviation, logistics, and transportation economics because it combines standardized reference data with regularly updated operational metrics.

Analytical Questions:  



