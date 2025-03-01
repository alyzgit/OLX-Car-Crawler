Database Project Milestone 3 submission
CarCity Release V1

This is a web crawler tailored specifically for OLX Cars.
The Web crawler gathers all car data based on search preferences.
The cars found in the search are then parsed into a mysql Database.

The database parses info such as 
'carId' : carIDS,
    'brand' : carBrands,
    'model' : carModels,
    'adType': carAdTypes,
    'fuelType': carFuelTypes,
    'price': carPrices,
    'priceType': carPriceType,
    'paymentOption': carPaymentOptions,
    'year': carYear,
    'kmLower': carKMLower,
    'kmUpper': carKMUpper,
    'transmitionType': carTT,
    'condition': carCondition,
    'color': carColor,
    'bodyType': carBodyType,
    'engCapLower': carEngCapLower,
    'engCapUpper': carEngCapUpper,
    'virtualTour': carVT,
    'transmissionType': carTT,
    'description': carDescriptions,
The Web Crawler itself is built using Python, and is contained in the file : Milestone2-copy2
Backend Files are all contained in a Folder titled DBwebapp
Frontend Files are all contained in a folder titled client

Backend development was using node JS
Frontend development was using React Js


Top run project 
Open 2 terminals
Run the react app in one terminal by:
- navigating to folder using ‘cd client’
- typing npm start App.js

Run the Node backend in the other terminal by:
- navigating to folder using ‘cd DBwebapp’
- typing nodemon index.js or node index.js

Navigate to LocalHost 4000 and happy searching :)
