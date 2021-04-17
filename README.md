# golden-hour-state
California solar irradiance analysis using meteorological data from 1998-2019. Developed as final project for the course Environmental Data Analysis &amp; Modeling at Columbia University and partially rehashed for a project paper in Alternative Energy Resources.

Dataset is from The National Renewable Energy Laboratory, a national laboratory of the U.S. Department of Energy.

While their database is vast, covering much of the United States, we selected 11 cities and 4 locations in California. The sites are relatively equally dispersed around California, considering latitude, longitude, and space from bodies of water.

The NSRDB deploys geostationary satellites that collect raw data in the form of aerosol properties, surface albedo, snow albedo, atmospheric profiles, and cloud properties. These measured values are plugged into a physics-based model to infer other features, such as GHI, DNI, and DHI.

The data we examine spans 1998 through 2019. Variables provided for each location are listed in the next cell.

We are going to model Direct Normal Irradiance (`DNI`) based on these variables as it is the most important predictor when assessing solar power potential (Schlecht & Meyer, 2012). We will use `DNI` and Irradiance interchangeably throughout this project. 
