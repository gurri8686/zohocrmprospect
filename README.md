Given are the postman requests for both the APIs with test values. Passed URL is localhost URL(http://localhost:8000) and can be replaced with assigned domain.

# Create Prospect API request

curl --location --request POST 'http://localhost:8000/api/prospects' \
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

curl --location --request GET 'http://localhost:8000/api/prospects' \
--header 'Content-Type: application/json' \
