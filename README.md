# Vision Zero Dashboard

last updated: 11/17/2019 2:33 PM CST

## About the Meetup

https://www.meetup.com/Chicago-R-User-Group/

Do you love Chicago and want to help make our great city safer? Then this hacking session is for you!

CRUG is working together with the City of Chicago to host a hackathon to develop a prototype dashboard using R and Shiny. We want to understand where, when, and why traffic crashes are happening, and what is effective for preventing crashes.

We are looking for help in developing concepts, graphical components, and / or prototype dashboards using R and Shiny. We are looking for contributions from people with different skill sets. You don’t necessarily have to be “technical” so long as you are interested in the problem and committed to contribute.

Through your participation you will have the opportunity to work directly on a City of Chicago project on our official GitHub repository!

https://github.com/Chicago/vision-zero-dashboard

### VISION ZERO CHICAGO

Vision Zero Chicago (VZC) is a commitment and approach to eliminating fatalities and serious injuries from traffic crashes. Vision Zero is an international movement that is changing the way we look at traffic safety.

The Vision Zero philosophy is that even a single life lost due to a traffic crash is unacceptable, and that everyone has a right to walk, bike, take transit, and drive safely. It’s a whole new approach that treats fatalities and serious injuries as preventable.

Please take a moment to read the introductory material on Chicago Vision Zero: https://www.chicago.gov/city/en/depts/cdot/supp_info/vision-zero-chicago.html

### DETAILS

Did you know that the City’s open data portal publishes detailed traffic crash information? As of September 2017, Chicago implemented an electronic crash reporting system that is operated by Chicago Police Department, and that crash data is published on a nightly basis on the open data portal.

We would like to use this data, along with historical crash data to track our progress on Vision Zero goals and find actionable and useful insights about crashes.

We will manage the work through the City of Chicago’s GitHub account and site. Users will be given write access to the dashboard repository for the duration of the weekend. We will ask that each team (or individual) work in their own branch.

This is not a competition, and we do not expect to have a final working prototype at the end of the session. We expect to consider and incorporate elements from the branches.

Depending on the level of interest, we may have an ongoing effort through the Chi Hack Night Meetup! More about this at the event.

Ultimately you have a real opportunity to help impact our City and your community, and drive real decision making through your insight and analysis.

Finally, although the primary data set is the crash data, there are many other data sets which can be brought into the analysis!

### AGENDA

We are offering two sessions. Sign up for either session, or both sessions.

## Session 1
10:00 – 10:30 Presentation and orientation
10:30 – 2:00 Hacking in teams, or individually
12:00 – Lunch is delivered (pizza!)

### Session 2
2:00 – 2:30 Presentation and orientation
2:30 – 6:00 Hacking in teams, or individually
5:00 – Dinner is delivered (pizza!)

Please plan to attend the introduction presentation for your session. This will contain important information about the goals, procedures, and resources.

At the conclusion of the presentation we will divide into teams and facilitate the process. Feel free to work independently, or to come as a team. We will be available during the hacking session to help with questions.

### REQUIREMENTS

Please bring a laptop, and if you plan to participate in development efforts please bring a laptop with R and R Studio installed.


## Background on Vision Zero

Vision Zero Chicago (VZC) is the commitment and approach to eliminating fatalities and serious injuries from traffic crashes.

Much more information is available in the Action Plan, and the City’s website:
https://www.chicago.gov/city/en/depts/cdot/supp_info/vision-zero-chicago.html

The plan emphasizes reporting and accountability in an transparent manner. To this end, the VZ committee has requested a public facing dashboard that communicates our progress toward Vision Zero goals, which can be referenced internally and externally.

## The Vision Zero Dashboard

The purpose of the proposed dashboard is to help Vision Zero Chicago achieve its mission, and increase transparency and accountability.

There are a wide variety of ways this information could be communicated, and technologies that could be used.  We feel that it would be best to begin with open source software and open data. The most relevant data that we would want to communicate is already publicly available on the open data portal: https://data.cityofchicago.org/Transportation/Traffic-Crashes-Crashes/85ca-t3if

The data sets include crash, vehicle, and person information reported into our eCrash system.  These data sets are updated daily.

We are also working with IDOT to determine how we can incorporate data for prior years so that we can accurately measure progress toward goals, and identify trends.

### Elements of the dashboard:

- Progress toward Vision Zero goals
- Cause of crash
- Was the crash in a High Crash Corridor
- Demographics impacted by crashes
- Summaries by time of day, day of week, season
- Anything that would provide insight to help prevent crashes

Examples of dashboards from other cities, and Illinois:

- [Illinois IDOT](http://apps.dot.illinois.gov/fatalcrash/snapshot.html)
- [Seattle](https://sdotblog.seattle.gov/2016/06/10/new-vision-zero-dashboard-now-online/)
- [Denver](https://public.tableau.com/profile/kmay#!/vizhome/DenverVisionZeroDashboard/OverviewofDenverCrashes)
- Portland (offline was [this](https://pdx.maps.arcgis.com/sharing/rest/oauth2/authorize?client_id=arcgisonline&display=default&response_type=token&state=%7B%22returnUrl%22%3A%22https%3A%2F%2Fpdx.maps.arcgis.com%2Fapps%2FMapSeries%2Findex.html%3Fappid%3D47c2153a3fa84636bb63e25b451372d0%22%2C%22useLandingPage%22%3Afalse%7D&expiration=20160&locale=en-us&redirect_uri=https%3A%2F%2Fpdx.maps.arcgis.com%2Fhome%2Faccountswitcher-callback.html&force_login=false&hideCancel=true&showSignupOption=true&signuptype=esri))
- [Washington DC](https://www.dcvisionzero.com/maps-data)
- [San Francisco](https://www.visionzerosf.org/maps-data/)
- [Los Angeles](http://visionzero.geohub.lacity.org/)
- [New York (citizen created)](http://crashmapper.org/#/?cfat=true&cinj=true&endDate=2019-02&geo=citywide&identifier=&lat=40.696518118094616&lng=-73.91738891601562&lngLats=%255B%255D&mfat=true&minj=true&noInjFat=false&pfat=true&pinj=true&startDate=2019-02&zoom=11)
- [New York (official)](http://www.nycvzv.info/)
- [Toronto](https://www.toronto.ca/services-payments/streets-parking-transportation/road-safety/vision-zero/safety-measures-and-mapping/)

## Technical Details

Please fork, clone, push, and then issue pull requests to the Chicago repository. Please use the issues in Chicago for general discussion, unless you have topics specific to your group.  The `discussion` tag indicates discussion areas.

To install `geneorama` please use devtools, `devtools::install_github("geneorama/geneorama")`

Please use the metadata for the crash data in `data-idot` to understand the nuance of the crash data.

Generally speaking, reference data can be found in the `resources\` folder, including a Word Document with dashboard examples. The final example in that document is a template created by CDOT which represents a great starting point.  From a technical perspective, check out the `example-shiny-crashes\` app.  

** Please use issues!  Let us know what you're thinking. 


## About the Chicago R User Group and Shiny

The CRUG Organization is focused on R, which is an open source language with broad application and compatibility with other technology. The open source software company R Studio has developed a library that works with R to create modern, secure, websites.

You can learn more about the web development software, and view examples here:
https://shiny.rstudio.com
https://shiny.rstudio.com/gallery/
 

<img src="https://design.chicago.gov/assets/img/seals/1990-blue.png" width="400" alt="City Seal of Chicago"/>
