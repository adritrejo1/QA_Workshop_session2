# QA_Workshop_session2
this is the challenge #2 for Wizeline Certification

*Description: 

Author: Adriana Trejo Diaz

Challenge Execises-BackEnd-Postman session 2- Thursday May 27th 2021



-Currently the project contains a folder with 6 folders inside: Payments_Negative, Payments_All, Payments_Cancel, Payments_Complete and Payments_Refund

-The only folder that will bring errors is Payments_All, as it coontains the whole requests that were created and some of the flows that should follow are not going to passed due they contain Cancel, Complete, Refund at same level.

-that is why I separate in different folders to vizualize the correct flow for each one of the request.



*Intructions:

1.- 

	Create new Folder: SESSION2_ADRITREJO->ADRIANA_SQUARE_PAYMENTS->API->COLLECTION

    Create new Folder: SESSION2_ADRITREJO->ADRIANA_SQUARE_PAYMENTS->API->envVariables

	Create new Folder: SESSION2_ADRITREJO->ADRIANA_SQUARE_PAYMENTS->API->reports
    
	
2.- 

	npm install --save-dev newman


3.- 

	npm install --save-dev newman-reporter-htmlextra


4.- 

	npx newman run <'Collection_Path'> -e <'Environment_Path'> -r htmlextra --reporter-htmlextra-export <'Report_path'> --env-var token=<'Auth_token'>



