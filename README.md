# API-PA-issue
My goal is to search for items using a specific keyword, retrieve the title, description, image, and affiliate link, and then store this information in a Google Sheet.


Hello GitHub Community,

I am a beginner trying to integrate Amazon's Product Advertising API (PA API) with Google Sheets to fetch product information. My goal is to search for items using a specific keyword, retrieve the title, description, image, and affiliate link, and then store this information in a Google Sheet. Despite following the documentation and making several attempts, I keep encountering issues and need your help to get this working correctly.

Requirements:

API Setup:

Amazon PA API (France)
Access Key
Secret Access Key
Associate Tag
AWS Account
Access Key
Secret Key
Google Sheets API:
Service account JSON file for authentication
Script Objective:

Use the Amazon PA API to search for items with the keyword "Bohemian Scandinave" in the "HomeAndKitchen" index.
Retrieve and store the following details in a Google Sheet:
Title
Description
Image
Affiliate Link
Steps Completed:

Installed necessary libraries (boto3, requests, gspread, google-auth).
Generated and downloaded the service account JSON file for Google Sheets API authentication.
Created a Google Sheet named "Make Pinterest" and shared it with the service account email.
Issues Encountered:

Internal Server Error:

When trying to make a request to the Amazon PA API, I consistently receive an "InternalFailure" error.
I have verified that the request parameters and headers are correctly formatted and that the request is properly signed.
Google Sheets Integration:

Successfully authenticated and accessed the Google Sheet.
Need to ensure that the data from the Amazon PA API is correctly inserted into the sheet.
Request for Assistance:

I need a complete and functional Python script that:

Authenticates with the Amazon PA API and makes a search request.
Retrieves the required product details.
Inserts this data into the specified Google Sheet.
Handles potential errors and edge cases.
Below is the partial code I've been working with (with personal information removed)

Despite following the documentation, I'm encountering persistent issues.
