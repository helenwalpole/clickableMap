# clickableMap
Basic template for a user-updatable interactive map linked to a google sheet via google forms


First, create a new survey in google forms with at least the following compulsory fields: 
- Latitude [short text, compulsory]
- Longitude [short text, compulsory]
- Name [short text, compulsory]
- Description [long text, optional]
- Website [short text, optional]
- Category [enum, compulsory]
- DateFrom [date, compulsory]
- DateTo [date, optional]

Set the form sharing options to 'anyone with the link'. 
Set the form to save to a google sheet. Set the sharing options for the sheet to 'anyone with the link'. 
