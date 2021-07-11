# netsuite-sql-queries

This folder of SQL views displays my work in creating usable data queries from Riverside's instance of Oracle's Netsuite system. 
This transactional database ERP was ingested into Snowflake; previously, many stakeholders across the organization created individualized "saved searches" within the Netsuite UI.
This was not sustainable, as it created many sources of truth with minor differences. Developing these views aided in establishing a core source of truth within the Snowflake data lake.
All code has been made to be generic from source company to maintain proprietary integrity.
