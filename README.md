# CPD_incident
Chattanooga Police Incident Analysis

The data in the CPD_incident jupyter notebook comes from the City of Chattanooga's Open Data portal.
https://data.chattlibrary.org/Public-Safety/Police-Incident-Data/jstk-5mri

The data comes from police incidents throughout the City of Chattanooga, TN and follows (not strickly) the TIBRS (Tennessee Incident Based Reporting System). 

Certian Crimes like those involving domestic violence or juveniles were removed by CPD prior to posting this public data.
form. The incidents started in 2015 and run to 2018. The City updates the data frequently but at this time only the information through the end of 2018 is in our project.

The data, as stated above, is not complete and some incident information was redacted or not present.  This is not a total representation of all incidents.

#### Columns:
- Address

- City
- State                      
- Zip                        
- Date_Incident              
- Jurisdiction               
- Incident_Tract           
- UCR_Incident_Code          
- Incident_Description
- Incident_Type
- Case_Number
- Case_Status   
- Case_Status_Description   
- Latitude               
- Longitude     
- Location   

*** A note about UCR_Incident_Code.  FBI set up the UCR codes (uniform crime reporting) and NIBRS (National Incident Based Reporting System) to make local crime incident reporting as uniform as possible.  Not all states conform to this, for example, Alabama doesn't report these stats to the FBI.

UCR & NIBRS Manual: https://ucr.fbi.gov/nibrs/nibrs-user-manual
