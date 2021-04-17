# golden-hour-state
California solar irradiance analysis using meteorological data from 1998-2019. Developed as final project for the course Environmental Data Analysis &amp; Modeling at Columbia University and partially rehashed for a project paper in Alternative Energy Resources.

Dataset is from The National Renewable Energy Laboratory, a national laboratory of the U.S. Department of Energy.

While their database is vast, covering much of the United States, we selected 11 cities and 4 locations in California. The sites are relatively equally dispersed around California, considering latitude, longitude, and space from bodies of water.

The NSRDB deploys geostationary satellites that collect raw data in the form of aerosol properties, surface albedo, snow albedo, atmospheric profiles, and cloud properties. These measured values are plugged into a physics-based model to infer other features, such as GHI, DNI, and DHI.

Direct Normal Irradiance (`DNI`) is the key variable here, as it is directly proportional to solar power potential (Schlecht & Meyer, 2012)

I know what you're thinking, how did he miss the golden opportunity to name this repo *Let the Sunshine In*, referencing the third best musical in history, after of course Jesus Christ Superstar (all hail ALW) and Grease (don't even try to tell me you don't get giddy when Frankie Vallie gets going). However, I'm saving that one in for a similar analysis on Florida, duh. 
