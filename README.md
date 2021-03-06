# econsult-api
The Bridge between Google Sheets and the eConsult Platform (econsult-website and econsult-prescribe)
                    
### API Implementation

Hosted in express, Fetched from local storage JSON(s) which are updated by Google Sheets API fetch and cron job using `pushthejson` for every 10 minutes

### Tables
                    
Api  | URL
------------- | -------------
links  | https://econsult-api-lovat.now.sh/links
faq  | https://econsult-api-lovat.now.sh/faq
doctors  | https://econsult-api-lovat.now.sh/doctors 
doctorsbyId  | https://econsult-api-lovat.now.sh/doctorsbyId?emailId=<email-id>
tnc  | https://econsult-api-lovat.now.sh/tnc
  
#### Note: doctors and doctorsbyId JSON will not be updated for this project as personal contacts of Doctors are not recommended to be published. Using a Secure DB and/or an easily editable sheets based interface such as [Airtable](https://airtable.com/invite/r/R3jkS9nc) is recommended.
  
