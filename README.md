This is the repository for Team 9 (Ctrl+Alt+Elite) @ Esri's Intern Hackathon 2022. 

You can run our website locally on your machine by navigating to the web-app folder.

Our inspiration for our project came after the Supreme Court’s decision to overturn the Roe v. Wade case. 
This went into effect immediately by some states and became a problem for women accessing reproductive healthcare facilities. 
We decided to do research and find a solution to help inform users about the latest updates on abortion in their state.
We also wanted users to have different types of resources and options on their decision.

This prompted us to build a web application that helps individuals access abortion clinics, planned parenthood offices, mental health facilities, 
and adoption clinics. It has information about the route, distance metrics, and estimated time to travel as well as directions, up-to-date abortion laws, 
and funding information for each state.

We started with looking for good, reliable and recent sources of data. Given the dynamic and sensitive nature of the project, we wanted to be sure 
that we would present the most authentic source of information to our users. Datasets were finally obtained by scraping (using python scripting) needed information
from credible websites. Once we had the data, we used ArcGIS Pro to build layers (using several geoprocessing tools) and publish a feature layer on ArcGIS online. 
Data visualization and carthography were done in ArcGIS Online. Feature layers were used in building web maps and web apps which were then consumed by the web application using JavaScript API for ArcGIS online.
To find the nearest facility to the user's address, we used the Closest Facility service and routing services. 
Popups were built to present a user-friendly and intuitive information about the facility and route.
We used both custom CSS as well as the Bootstrap library, HTML, and JS. To generate the live US focused newsfeed we used an API from the GDELT project. 
The GDELT monitors the world's broadcast, print, and web news. We queried data on abortion related topics local to the United States and embedded the result into our website. 

Check out our [devpost](https://devpost.com/software/forward-mj3z8s) for more!
