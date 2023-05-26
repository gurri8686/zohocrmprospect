Given are the postman requests for both the APIs with test values. 

# Create Prospect API request

curl --location --request POST '(YOUR_DOMAIN_NAME)/api/prospects' \
--header 'Content-Type: application/json' \
--form 'First_Name=Test' \
--form 'Name=Test' \
--form 'Mobile=9876543210' \
--form 'Email=test@gmail.com' \
--form 'DOB=1984-12-23' \
--form 'Tax_File_Number=123456789' \
--form 'Agreed_Terms=No' \
--form 'Status=New Prospect'


# List recent 5 Prospect API request

curl --location --request GET '(YOUR_DOMAIN_NAME)/api/prospects' \
--header 'Content-Type: application/json' \

# Note
- To pass the URL in .env file constant name is ZOHO_CRM_API_URL 
- To pass the token in .env file constant name is ZOHO_CRM_TOKEN
