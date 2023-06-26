# SQL-Weather-Observation-Station-3

# Challenge:
- Query a list of CITY names from STATION for cities that have an even ID number. Print the results in any order, but exclude duplicates from the answer.

- The STATION table is described as follows:

![n1e5uock jot](https://github.com/MarcvWaes/SQL-Weather-Observation-Station-3/assets/120553175/93033af8-77bd-460d-bf7b-fce39386b9e6)

- Where LAT_N is the northern latitude and LONG_W is the western longitude.

# Solution:
- SELECT DISTINCT CITY
- FROM STATION 
- WHERE ID%2=0;

# Output:
- Aguanga 
- Alba 
- Albany 
- Amo 
- Andersonville 
- Archie 
- Athens 
- Atlantic Mine 
- Bainbridge 
- Baker
- .....
