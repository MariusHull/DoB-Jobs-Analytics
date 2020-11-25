# DoB Jobs Analytics Project
## NY Buildings and infrastructure cost evaluation

### Goal :
Real estate assets acquisition takes into account many parameters, among others is the cost of the maintenance that will be necessary to keep the building or apartment in a good condition. The goal of this project is to predict when and which type of maintenance jobs will need to be done, and give estimations of the cost of these jobs.
	The business value we will try to create during this project might interest two types of people: building owners, to help planning their budget, and contractors or real estate agencies, in order to better target advertising campaigns and give their potential customers more insights on what they have to offer.
 	If we can complete these tasks, another goal will be to identify areas within the city that have a homogeneous job type and frequency distribution. Identifying such areas could give insights about old and high-maintenance costs infrastructures that would need to be replaced either by city services or other service providers.

Project roadmap :
- An important part of the project will be data visualization, both to extract insights from the data and to present the results, as we have many data points and a lot of features.
- For each job type, clustering (which scale will we use? How many clusters?)
- For each job type, for each cluster, predict the average duration between each job at the same address
- For each job type, predict cost and confidence intervals
- Try to create an index to evaluate a building's maintenance costs, and compute it from any new building based on its geographical and physical characteristics.

### Sources of Data : 
We will be working on the NYC DoB job filing dataset, updated daily : https://data.cityofnewyork.us/Housing-Development/DOB-Job-Application-Filings/ic3t-wcy2. We can divide the features of interest into 3 categories :
Localisation / Geographical features : Borough, Street name,  Block, Lot, Zip, Latitude, Longitude
Building characteristics : Building class, City owned
Job characteristics : Job type (Plumbing,….Curb cut), Pre-filing date, Paid, Approved, Fully permitted, Estimated cost of job,  Estimated fee of job

### Notes : 
Might want to think about cost of the building
Consider weather events VS random failures in systems

