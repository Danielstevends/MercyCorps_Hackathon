# MercyCorps_Hackathon
### Created by: Daniel Sitompul & Rashmi Varma
#### UC Berkeley - Disaster Lab Hackathon

HACIT - Humanitarian Aid Cost Integration Tool is a tool made by Daniel &amp; Rashmi, students from UC Berkeley, to help MercyCorps foundation to create a calculator. This tool will calculate transportation, baskets, and human resource to the total spending. We use APIs to get the current distance, price, and exchange rates to visualize.

The database of food that we use is based on internet scraping which we put in a google spreadsheet and connected through API. Please check this link to the database:
https://docs.google.com/spreadsheets/d/1CYUSuWbTvcINtHsDWTLdaKF7Isv9wKcyG_yYm1Ar52I/edit#gid=0

To fully use this code, you need 4 API keys:
1. GoogleMaps API
2. Forex API
3. Gas Price API
4. GoogleSheet API

The input fron the user are:
1. Location of transit
2. Emission per km (plane and truck)
3. Plane and truck distance per liter
4. Fuel price per liter
5. Output Forex
6. Aid Basket Ingredient
7. Employee salary

The output:
1. Map
2. Total price
3. Emission
