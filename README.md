# Eloqua_Activities_Reports
1) Visit https://web.postman.co and create a workspace
   
   <img width="960" alt="image" src="https://github.com/Eucloid-Data-Solutions/Eloqua_Activities_Reports/assets/147633066/35ef74f8-b584-4922-a34e-9205b888c6ee">

2) Click on the Authorisation tab from the drop-down list, click on authentication type.
   In our case we use basic auth:

   User name: <company_name> \ <your_user_name>
   
   Password: <Your_password>

   <img width="960" alt="image" src="https://github.com/Eucloid-Data-Solutions/Eloqua_Activities_Reports/assets/147633066/7978e20d-5693-42b4-b7fd-85467b7ba496">

   On the URL text box, enter "https://login.eloqua.com/id".

4) Click on the headers tab and add the following header with the given key:

   <img width="960" alt="image" src="https://github.com/Eucloid-Data-Solutions/Eloqua_Activities_Reports/assets/147633066/8ad57398-d451-4715-a79a-1ac4d9ed3762">

5) Click on the code snippet icon to fetch the auth key.

   <img width="960" alt="image" src="https://github.com/Eucloid-Data-Solutions/Eloqua_Activities_Reports/assets/147633066/a93a0aad-88ea-4cfd-8dcc-db230461fbb0">



Run your desired code from the given choices:
1. Specific Campaign metrics : CRM_analysis.ipynb
2. PII level information : email_openers.ipynb
3. Date level activities : CRM_analysis.ipynb - Add the date filters as used in 2. in function: api()

Visit for additional information:
https://docs.oracle.com/en/cloud/saas/marketing/eloqua-rest-api/
