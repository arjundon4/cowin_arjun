# Cowin monitor for BBMP and Trivandrum
Auto refresh every 60 seconds and fires API call to check availability for next 7 days based on district id. Shows a pop up if 18+ slot available.\
https://apisetu.gov.in/public/marketplace/api/cowin \

The API call being done is hardcoded in each html having fixed center id. \
district_id=294 is for BBMP \
You can get the district_id from the metadata APIs in the API marketplace. Then replace in the fetch call to get availability for your district.\
There are more APIs available to fetch for a specific pincode. Do explore.\
\
Lot of room for improvement. Feel free to contribute :)
