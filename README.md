# Richmond Environmental Justice Project: Green Space Accessibility
# By Nayhb Oseguera
![RichmondEnvironmentalJusticeProject_v1](https://user-images.githubusercontent.com/107137280/177134105-eb03f11f-22b3-471f-9991-4fe4d054c4b8.jpg)
## Introduction
### Social Justice Mission
This mapping project hopes to be a local level intervention on environmental justice for the East Bay city of Richmond, CA. When crafting this map, I was interested in the First Law of Geographical Information which states that where the need for geographical information is the greatest the amount of it available is the least (Taylor Overton 1991). Additionally, I believe as scholars or active community members it is our duty in relation to justice to produce knowledge for often overlooked communities as our role in reducing social inequality (Rawls 1999). Moreover, I was inspired by our class reading discussing environmental justice and wanted to apply the idea to a local community (Anguelovski 2013). As such, the project’s scope is limited to Richmond to provide a historically underserved community with detailed cartography that has the potential to improve the city’s environment.
### Key Concepts
The project I am presenting today is the first map of a series of maps each with the common theme of representing one of three defined indicator factors of environmental violence in order to convey a plan of environmental justice. The project defines Environmental Violence as any spatial characteristic of a city’s urban area as a man-made ecosystem that contributes to increased mental and physical health risks in its citizens. Conversely Environmental Justice refers to policy and infrastructure decisions made with the expressed goal to improve citizen health by altering the urban environment.
### Project Goal
The project aims to provide a visually informative graphic that allows community leaders, activists, and policy makers to identify the physical urban areas in Richmond that suffer the most from environmental conflict. These maps could then be compiled into one summarizing and relating the interactions of all Environmental Violence factors in one visual graphic. By doing so, the series of maps would specify, akin to a diagnosis, the multimodal cocktail of environmental concerns for each neighborhood to help the city of Richmond define redevelopment priority neighborhoods to begin taking active steps to ameliorate environmental conflicts in these disadvantaged communities.
### Green Space Accessibility Map Intro 
This first map represents Green Space Accessibility, meaning that it is mapping the areas of the City of Richmond that are walking distance from at least one public park or protected outdoor space. More importantly, the map conversely also indicates which areas are lacking access to substantial green space and may need to use a car to do so. I define lack of green space access as a form of environmental violence because it is a preventable urban planning problem with adverse health effects described by governmental institutions. Organizations such as the California Department of Public Health (CDPH) hold park, beach, open space, and coastline access are “critical to human quality of life and wellness activities” and are indicators of health equity (CHHS 2010). In terms of how to describe walking distance or walkability, I used the definition held by the National Center for Biotechnology Information (NCBI): 0.25 miles (NCBI 2013). 
In the next section, I will describe the original procedure of the map. The plan is still an outline for future developments of the project, in the discussion section I will address any significant changes to the planned procedure.
## Original Procedure
### Factors and Metrics to Measure Environmental Violence
Time permitting, the project will focus its description of environmental violence via 3 factors ideally: Heavy Industry, Greenspace, and Transportation Infrastructure. Each factor will ideally be measured with 2 metrics for a total of 6 indicators of environmental violence. Heavy Industry is defined as any industrial activity that either negatively affects local AQI daily/during emergencies or causes health problems due to air pollution like lung cancer or asthma. Green space is defined as how accessible via walking are spaces with vegetation and how much tree cover exists in the city’s streets itself. Transportation Infrastructure is defined by the city’s street grid accessibility for active modes of transport (walking, biking, and public transit) to nodes of activity throughout the city and the noise pollution caused by traffic along such infrastructure. The plan is to implement each factor into the map one by one starting with Greenspace, Transportation Infrastructure, and then Heavy Industry because of the limited time available to construct the map.
### Data Collection 
The factors are ordered based on ease of data access. Park accessibility is measured with centroids defining a walkability radius around them based on walk score project precedents. There is local government data on Richmond Street coverage that can easily be inputted into the map. Transportation Infrastructure will be deemed to hinder active transport modes based on the number of street connections made impossible by the space it occupies. For instance, metro stations themselves are considered to increase accessibility in the adjacent neighborhood whereas elevated tracks between each can reduce ground transport accessibility. Noise pollution would simply be measured as any area that exceeds decibel levels typical of a residential area (>60dB) considering levels become hazardous at about 80dB. Noise pollution data would likely be kept in City website records or sources related to interstate highway system for freeway data. AQI information is a popular publicly available data set especially due to recent California wildfires. The city also has area data on the risks of chemical leaks in the event of a refinery emergency. Finally, the most difficult piece of information would be to find the distribution of cancer and asthma related health problems in Richmond as it would rely on the existence of a study or data collection tracking both variables (disease and address). This information is made further difficult to obtain because the private nature of this data reduces the likelihood and frequency it would be released.
### Differences From Similar Precedent Studies
This project in contrast to the Environmental Justice Atlas will plot area instead of points as its spatial data representation to better convey what geographical areas of the city are impacted by various forms of environmental violence (Ejolt 2022). Each shading of area will be cumulative with different overlapping areas being shaded in progressively darker tones to indicate spaces suffering multiple forms of environmental violence. Moreover, the data has been reduced to variables that specifically impact space and historical data is not the priority, this project’s priority is instead to identify current issues in efforts to enact future environmental justice. The data is also local specific so environmental justice issues such as water cleanliness that are of concern say in Flint, Michigan will not be mapped in this project. I also plan to make the map graphically appealing to read using a pink based color scheme to elicit empathy from readers rather than the realistic color scheme in the Environmental Justice Atlas.
### Proposal Conclusion
At minimum this project will achieve a map with the potential to guide development on expanding Richmond’s parks and urban forest as green space environmental justice, ideally it will be a multidimensional graphic indicating neighborhoods that should be the city’s priority for redevelopment. If successful, this mapping project could serve as a simple model and starting point for more multidimensional graphic approaches of environmental justice cartography for cities throughout the country.
The original story map proposal can be read in the following link: https://nayhb-oseguera.github.io/Social-Justice-Blog/
## Discussion 
Procedure Addendum
As mentioned in the proposal conclusion, due to time constraints I had to focus on only one factor and set of metrics. I followed the plan and mapped out the green space factor first. I also discarded Richmond Street Tree coverage as a metric as there weren’t available open data sets with such information.
### Data 
Park area data was provided by the California Protected Areas Database (CPAD 2021) and San Francisco Bay Protected Areas data (Bay Area Open Space Council 2010). The CPAD data represents areas throughout California that are protected as public open space by various public agencies and other organizations. This includes parks and public wilderness/coast. The Bay Area Protected Areas data are also area and polygonal data with largely the same information as CPAD, but specific to the Bay Area not California as a whole. I compared both data sets to identify if there were any gaps and if needed to supplement one over the other, but that did not end up being the case. Due to some clerical errors, I actually was not able to use either data set, however I will touch on later how I remedied this issue for making the map.
Contra Costa County City Boundary Data was also used and obtained through Berkeley Geodata (Contra Costa County 2012). I needed this data because Richmond has a very irregular shape and is intermeshed with other cities, it literally engulfs the City of San Pablo, and census designated communities. The city limit data helped clean up the map and convey the actual areas I am studying for this project. The data set consists of longitude and latitude coordinates that are connected to form a series of lines to represent the cities’ boundaries. Again, I was not able to use that data in the final map! But I managed and I will now discuss these problems and solutions related to the data collection.
### Problems
I faced many challenges using the data because I could not get the Carto and Github Student’s Developer Pack. I made about 6 attempts ranging from my student ID to even ordering an online official transcript! Nothing worked nor did emailing them. Regardless I was able to use a 1-day free trial of Carto, but the trial was very lackluster in comparison to the developer pack. It was very difficult to upload any data and it did not resemble the way demoed in class. I couldn’t even upload or make excel sheets how I had previously planned in case some data I needed did not exist. The only data set that was successfully uploaded in this trial version was the city limits set. After much trial and error, I decided that maybe I should try Map Box instead since it is free by default.
Map Box proved to be the right way forward despite not being able to upload data there either. However, the saving grace lied in its own built-in data. I learned how to add new layers, and  edit existing data sets to extract the information I needed. Specifically, Map Box had land-use data with a park class category. I was also able to directly control the style of my map and opted for a pink monochrome tone as I had planned. Map Box also has various default data such as freeways, street names, city and neighborhood labels, etc that was crucial in providing necessary contextual information for my map’s readers. However, as I mentioned I was not able to implement any city limit data. As such, given the luck I had with the land-use data I decided I just had to push forward and work with what I had.
All the data and the absent analysis functions from Carto had to be drawn and performed manually. I moved to Illustrator and began my work. I verified from my Carto attempt that the google maps city limit data was consistent with the Berkeley sourced data, I also checked if green spaces in the Map Box land-use data matched Google’s and the Bay Area Protected Areas Data set. Finally, I essentially traced the city boundaries by hand on my computer, but that does not compare to the work I put in to make the analysis possible. 
### Data Analysis
Another hurdle I had to overcome was the lack of location point data for Richmond parks. My goal was to conduct a centroid analysis denoting the walkable area surrounding the city’s parks. I used Google maps’ distance tool to measure centroid radii for each park. I used some data observations from the walk score project to ease my centroid analysis (Walkscore 2022). Namely, I used walkability shorthand based on street grids. Orthogonal grids resemble the ideal centroid being a circle; the grids truly form a diamond centroid shape with corners at the maximum radius distance, but I kept it simple by representing it as a circle for timeliness and aesthetic considerations. In contrast, organic curved street grids designed for car-centric mobility make irregular branched shape centroids and required measuring every single street adjacent to the park.
 I adjusted centroid geometry based on four limits besides the 0.25 mi distance: freeway or exceptionally large arterial road, railroad, city boundaries, and mixed street grid patterns. Walkers tend to be uncomfortable walking across freeways and large arterials so instead of connectors these roads act as barriers for pedestrians, because of this I would reduce the centroid areas if they crossed one of these roads. Railroads are also physical barriers that pedestrians tend to not cross and thus reduce walkability. The study is only considering parks and public open space funded by the city of Richmond and for its citizens, as such centroid area was reduced at any city limit encounter. Finally, at mixed city grid patterns I implemented hybrid strategies, orthogonal portions were drawn more circularly whereas curved grid branches were measured and reduced like branches. Other things I looked out for in mixed grids was pedestrian only walkways and restricted entrances to certain green spaces. 
Some adjustments were made to what was considered green space area. I removed three green spaces: portions of the Bay Trail, the Richmond Greeneway, and the entire Richmond Country club. In general, I excluded trails as green spaces. While they are mobility corridors with vegetation, they do not offer the same leisure amenities of a park or serve as destinations. This destination distinction is the critical difference I held on to a case-by-case basis; as such, I did include a portion of the Richmond Greeneway near downtown that expands into a community space with gardens, benches, and a jungle gym for the kids. The Richmond Country Club was simply removed because it is not a public space, they are privately-owned, and a membership is required to reliably enter the green space. I also added 2 green spaces: the Civic Center and Alvarado/Wildcat Canyon Creek Regional Park. Both are vegetated destinations and public spaces of significant local and historical notoriety, as such their omission is unjustifiable on all accounts.
An interesting feature of the map’s analysis is the overlapping centroids cumulatively darken intersecting areas in a gradient pattern. This behavior creates another source of information, namely the darker the pink an area is the more parks residents have available at a less than 0.25 mi walking radius.
## Results and Observations
### Defining a Green Space
This project is meant to be a tool for the Richmonder community’s scholars, activists, policymakers, and families invested in Richmond’s development. The map only includes the City of Richmond to ensure the study is focused providing quality local data instead of overextended designs for larger audiences. Green spaces in this study are specifically defined as publicly owned vegetated destinations for leisure. Under this definition golf courses, trails, and private green spaces are excluded. That includes other parks such as HOA funded ones. The reasoning for ignoring their contributions is that private parks are not guaranteed to be permanent/stable land use as the owners can always repurpose them unlike public parks.
### Raw Results
The green space map has produced a plethora of interesting insights ranging from what neighborhoods should be given priority status for new park developments to reaffirming the efficiency benefits in park service area for grids that prioritize accessibility vs mobility-based transportation grids (surface rail, freeways, large arterials, and curved limited-access street grids).

![image](https://user-images.githubusercontent.com/107137280/177137097-97220411-c7c7-4e10-ac5c-c4af9f76e3e1.png)
_Green Space Accessibilty Map: Marina Bay Close-Up_

![image](https://user-images.githubusercontent.com/107137280/177137309-395cf63d-5ed6-4be8-9668-0a741c984443.png)
_Marina Bay Park is a well maintained park in a high-income neighborhood. Source: Google maps_

The results as to what neighborhoods should be prioritized are nuanced but clear with some discussion. At face value the priority neighborhoods would be Point Molate, Point Richmond, portions of Marina Bay, Easter Hill Village, Pullman, Belding Woods, Metro Village, North & East, East Richmond, portions of Richmond Annex, Parchester Village, portions of the Hilltop District, and the majority of May Valley. However, on closer inspection it is noticeable that higher income neighborhoods like the Marina Bay and Point Richmond do lack park accessibility. More importantly, the parks they do have are very inefficient service area wise due to their curved street grids. The case of the Marina Bay neighborhood is extreme with some houses being adjacent to a park, but they are more than 0.25 mi from them in walking distance simply because of how their streets are organized. In fact, the Marina Bay would not be considered a priority neighborhood for park development whatsoever if its street grid was orthogonal to maximize walkability.
### 2 Types of Priority Neighborhoods
In a way this conundrum actually yields more information than I had previously envisioned for the project. The map is showing us priority neighborhoods for both poor walkability and park development. So, if we remove these affluent low park accessible neighborhoods from the park priority list, we get the following priority areas for better walkability: Point Richmond, Marina Bay, the Hilltop District, and May Valley. Finally, I’d highlight Belding Woods Easter Hill Village, and the North & East neighborhoods as the most notable priority neighborhoods for park development as they are the largest and most isolated of all priority neighborhoods from green space. The ultimate solution I propose is that the city build more green spaces in these neighborhoods to ameliorate green space access inequality. 
### Iron Triangle Parks

![image](https://user-images.githubusercontent.com/107137280/177139831-a629314d-dcd4-481c-9673-868c47bbae10.png)
_Green Space Accessibilty Map: Iron Triangle Close-Up_

![image](https://user-images.githubusercontent.com/107137280/177139104-e8add0db-5477-43d8-b2ab-b8f99eae9058.png)
_Lucas Park is a large park located next to the arterial road Pennsylvannia Ave. Source: Google Maps_

One finding was very surprising, the infamous Iron Triangle has the highest park accessibility according to the map. This is surprising because the neighborhood has a history of being underfunded, destitute, and rampant in crime. In fact, there are current community projects with the expressed goal of increasing the neighborhood’s green space. This observation raised by the Richmond Environmental Justice Project raises a couple questions that we can address in future projects. 
### Hilltop District Parks

![image](https://user-images.githubusercontent.com/107137280/177139974-0d371fbc-1091-431a-b601-130733ad594b.png)
_Green Space Accessibilty Map: Hilltop District Close-Up_

![image](https://user-images.githubusercontent.com/107137280/177140291-65b0b5b7-e8d7-4053-a41d-170d6b057cb8.png)
_Hilltop Park is a good example of good urban design in organic grids. Source: Google maps_

Another noteworthy insight can be found analyzing the results of the Hilltop District. Looking at the Hilltop district the role of restricted access and park size to improve their service area efficiency in organic street grids is critical. Point Pinole despite being Richmond’s second largest park has a smaller walkable footprint than Hilltop Park. Moreover, Fairmead Park has a smaller footprint as well despite being the same size as Hilltop Park. Hilltop Park has a larger walkable footprint/service area because in difference to the other two parks Hilltop has more than two entrances. It is also worth mentioning that both Fairmead and Hilltop Park are larger than Wendell Park to the south, yet Wendell’s walkable footprint is larger and thus the land use per square foot is more efficient for providing park services. In sum, the Hilltop District shows that in order for parks to be viable and walkable in an organic grid they need to be larger and have many access points in comparison to their smaller counterparts on orthogonal grids. In other words, Parks and Recreation services are more expensive to provide effectively in organic grids or hilly landscapes.
## Conclusion
### 1st Map Overview
The Green Space Accessibility map has been a huge step to kickstart the Richmond Environmental Project, regardless there are many aspects in which we can improve piece of cartography. For one there are many avenues to explore on the findings regarding the Iron Triangle neighborhood. I recommend that the paradox of a low-income neighborhood despite having high green space accessibility be resolved. One possible explanation is that parks do greatly vary in maintenance and quality between Richmond neighborhoods. So, even though a neighborhood has a park in every corner, it will do little to improve land value if not properly maintained. I propose this oversight can be solved by factoring in park maintenance in the project’s service coverage schema. Poorly maintained parks likely also have lower walkability footprints as they attract less visitors. As such, this added park maintenance variable can factored in as either a smaller walkability radius, a lighter shading value than well-maintained parks or both. With these new adjustments I’m confident the project would provide an even more nuanced perspective on the green space needs of Richmond. 
### Recommendations for New Iterations
Another avenue of exploration could be considering different versions of the Green Space Accessibility map that convey variances in walkability. For instance, I could make a map that decreases walkability footprints based on neighborhood crime levels. It could be a useful exercise to make versions representing proposed green space solutions to compare with the original. Such an activity would serve as a good learning tool as to the impacts even small infrastructure changes like new park entrances can have on the community’s welfare. In a sense these exercises would be tantamount to practicing environmental justice rather than pointing out violence as I did. 
Other map versions could also be more selective as to what green spaces should be included. Not only could this new version exclude poorly maintained parks, but it could also decide to remove any parks smaller an acre per se under the premise that small parks are not good enough green spaces. Even though there were few parks outside Richmond’s city limits that affected it, a new map could include all these communities I ignored and make a regional map. A map like this would be most useful in cities that surround each other like Los Angeles in Southern California.
### Project’s Future Objectives
Now that the pilot or first version of Green Space Accessibility is complete, the project can continue to complete the remaining two maps to eventually complete its objective of creating a multimodal map compiling all these environmental violence factors. I chose to make separate versions of these maps instead of only one combined one because after making this one only representing parks, I realized that many unique insights can be found in unimodal data too before making it multimodal. 
The next map should be Infrastructure Barriers. The map would represent how freeways and surface rail disrupt city grids by reducing walkability and increasing noise. Both effects qualify these “Infrastructure Barriers” as a form of environmental violence as low walkability is related to increased levels of obesity, heart disease, air pollution (more people would drive), and noise pollution contributing to hearing loss. A more restrictive version could include arterials as well, there is definitely a good case for the faux freeway that is Richmond Parkway. Overall the most impacted areas are likely the Richmond Annex, South Richmond, Point Richmond, and the Iron Triangle as these neighborhoods have many railroad, metro, freeway, and parkway infrastructure lassoing and splitting them.
The penultimate map would be Industrial Pollution. This map areas of the city in which industrial air pollution is unhealthy. The map’s subject would mainly be targeting the adverse health effects caused by the Chevron Refinery. It is fair to assume the more western neighborhoods of the city would be most affected by these industrial activities. 
The final map will be a culmination of all previous maps as had been originally intended for this project. All these different complex pieces of data would come together to help policymakers decide what neighborhoods need the city council’s attention and investment. More importantly the final map would provide accurate insight as to what strategies of environmental justice the city should perform to improve these neighborhoods. 
If successful, the goal would be to expand this project across multiple cities throughout the country. By doing so it could establish cartography as a powerful local skill to resolve “urban ailments” in a calculated and informed manner. In a sense, environmental cartography following the ideas of this project would consist diagnosing and prescribing solutions to improve the urban environment of our communities.
### Final Remarks
Green Space Accessibility was only the beginning of the Richmond Environmental Justice Project. The map showed us how in a journey to obtain multivariable observations and phenomena, there is much to learn focusing one variable at a time. In fact, serendipity is the name of the game. There was an intended type of analysis I expected to obtain and while I did still receive those results, the bonus insights were the fascinating lessons. Had I not made an individual map for greens space I would not have identified that area data can reveal the walkability of a street grid by through the latter’s very distortions on the data. I also through unexpected results in the Iron triangle found that the design I had conceived was not full proof. Spatial data by virtue of being tied to the physical world is anything but objective and I found the unpredictable to be rewarding.
## Sources
1.	https://bcourses.berkeley.edu/files/83431594/download?download_frd=1
2.	https://bcourses.berkeley.edu/files/83445379/download?download_frd=1
3.	https://bcourses.berkeley.edu/files/83438821/download?download_frd=1
4.	https://data.chhs.ca.gov/dataset/park-beach-open-space-or-coastline-access
5.	https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3377942/#:~:text=Walking%20distance%20is%20an%20important,distance%20in%20U.S.%20research%20studies.
6.	http://www.ejolt.org/maps/
7.	https://data.cnra.ca.gov/dataset/california-protected-areas-database
8.	https://geodata.lib.berkeley.edu/catalog/stanford-ww607xn1686
9.	https://geodata.lib.berkeley.edu/catalog/berkeley-s7hm3f
10.	https://www.walkscore.com/walkable-neighborhoods.shtml
11.	Images from Google Street View: https://www.google.com/maps/place/Richmond,+CA/@37.9532942,-122.3647424,12.71z/data=!4m5!3m4!1s0x808565e0f15c8c29:0xb3101633da15bff4!8m2!3d37.9357576!4d-122.3477486

