# Geospatial learning resources for biomedical applications
Resources related to geospatial analysis in (mostly) R

## R package resources

- [CRAN Task View: Analysis of Spatial Data • Roger Bivand & Jakub Nowosad](https://cran.r-project.org/web/views/Spatial.html)
- [r-spatial.org • Edzer Pebesma, Marius Appel & Daniel Nüst](https://r-spatial.org/): Website and blog for those interested in using R to analyse spatial or spatio-temporal data
- [rspatial.org - Spatial Data Science with R — R Spatial](https://rspatial.org/): Materials that teach spatial data analysis and modeling with R using the `raster` and `terra` packages
 
## Spatial data visualization

- Workshop (R/Medicine 2022): Using Public Data and Maps for Powerful Data Visualizations • Joy Payton
  - [Video](https://www.youtube.com/watch?v=iU1h5b3qp_Y)
  - [Slides](https://rpubs.com/pm0kjp/r_medicine_2022)
  - [Repo](https://github.com/pm0kjp/r-medicine-2022)
- Talk (RStudio Conf 2022): Accelerating geospatial computing using Apache Arrow • Dewey Dunnington: 
  - [Video](https://www.rstudio.com/conference/2022/talks/accelerating-geospatial-computing-using-apache/)
  - [Slides](https://github.com/rstudio/rstudio-conf/blob/master/2022/deweydunnington/Accelerating%20geospatial%20computing%20using%20Apache%20Arrow%20-%20Dewey%20Dunnington.pdf)
  - [Package (`geoarrow`)](https://paleolimbot.github.io/geoarrow/)
- Course: Geospatial Workshop • The Carpentries
  - [Introduction to Geospatial Concepts](https://datacarpentry.org/organization-geospatial/)
  - [Introduction to Geospatial Raster and Vector Data with R](https://datacarpentry.org/r-raster-vector-geospatial/)
- Course: GIS in R • Earth Lab
  - [Shapefile Structure](https://www.earthdatascience.org/courses/earth-analytics/spatial-data-r/shapefile-structure/)
  - [Coordinate Reference System (CRS) and Spatial Projection](https://www.earthdatascience.org/courses/earth-analytics/spatial-data-r/intro-to-coordinate-reference-systems/)
  - [Projected vs Geographic Coordinate Reference Systems](https://www.earthdatascience.org/courses/earth-analytics/spatial-data-r/geographic-vs-projected-coordinate-reference-systems-UTM/)
  - [Understand EPSG, WKT and other CRS definition styles](https://www.earthdatascience.org/courses/earth-analytics/spatial-data-r/understand-epsg-wkt-and-other-crs-definition-file-types/)
  - [How to Reproject Vector Data in Different CRS](https://www.earthdatascience.org/courses/earth-analytics/spatial-data-r/reproject-vector-data/)
  - [Making Interactive Maps with Leaflet Earth Lab • Earth Lab](https://www.earthdatascience.org/courses/earth-analytics/spatial-data-r/make-interactive-maps-with-leaflet-r/)
- Course: Introduction to Spatial Data Science • Luc Anselin & Grant Morrison
  - [Spatial Data Handling](https://spatialanalysis.github.io/lab_tutorials/1_R_Spatial_Data_Handling.html)
  - [Basic Mapping](https://spatialanalysis.github.io/lab_tutorials/4_R_Mapping.html)
- Tutorial: [Space - Data Visualization • Andrew Wheiss](https://datavizm20.classes.andrewheiss.com/example/12-example/)
- Tutorial: [Mapping Environmental Exposures • CHOP Arcus Education](https://education.arcus.chop.edu/mapping-environmental-exposures/)
- Tutorial: [How to use open vector file formats in R: GeoPackage & GeoJSON • Floris Vanderhaeghe](https://inbo.github.io/tutorials/tutorials/spatial_standards_vector/)
- Workshop notes: R Spatial Workshop - Center for Spatial Data Science • Angela Li
  - [Book of notes](https://spatialanalysis.github.io/workshop-notes/)
- Book: Spatial Data Science • R Spatial
  - [Spatial data with terra](https://www.rspatial.org/terra/spatial/index.html)
- Book: Spatial Analysis with R • Chia Jung, Yeh
  - [Shapefile](https://chiajung-yeh.github.io/Spatial-Analysis/basic-knowledge-on-gis.html#shapefile)
- Book: Geospatial Health Data • Paula Moraga
  - [Coordinate reference systems](https://www.paulamoraga.com/book-geospatial/sec-intro.html)
  - [Shapefiles](https://www.paulamoraga.com/book-geospatial/sec-spatialdataandCRS.html#shapefiles)
  - [Making maps with ](https://www.paulamoraga.com/book-geospatial/sec-spatialdataandCRS.html#making-maps-with-r)
- Book: Introduction to Spatial Data Programming with R • Michael Dorman
  - [Vector layers](https://geobgu.xyz/r/vector-layers.html)
- Workshop (useR!2020): First steps in spatial handling and visualization • Sébastien Rochette, Dorris Scott & Jakub Nowosad
  - [Repo](https://github.com/statnmap/user2020_rspatial_tutorial)
  - [Video](https://www.youtube.com/watch?v=1Hp8MO82t4g)
- Workshop: Creating maps in R (sp package) • Robin Lovelace
  - [Repo](https://github.com/Robinlovelace/Creating-maps-in-R)
- Site: Designing accessible maps
  - [Maps & Geospatial: Accessibility Resources • Library Guides at Penn State University](https://guides.libraries.psu.edu/c.php?g=1246608&p=9122546)

## Geocoding (offline)
- Residential mobility[^1]
- R programming language
  - Decentralized and reproducible geocoding and characterization of community and environmental exposures for multisite studies[^2]
    - [Video](https://www.cctst.org/news/2019/04/decentralized-and-reproducible-geocoding_11.html)
  - DeGAUSS: Decentralized Geomarker Assessment for Multi-Site Studies[^3]
    - Tool & instructions: https://degauss.org/ 
  - [Challenges and solutions for private and reproducible environmental exposure assessment at scale](https://www.niehs.nih.gov/news/events/pastmtg/2022/elsi/challenges_and_solutions_for_private_and_reproducible_environmental_exposure_assessment_at_scale_508.pdf)
  - OpenStreetMap data to PostgreSQL converter: [openstreetmap/osm2pgsql](https://github.com/openstreetmap/osm2pgsql)
- [Geocoding Made Easy • tidygeocoder](https://jessecambon.github.io/tidygeocoder/index.html)
  - [Geocoding Services - Data Privacy • tidygeocoder](https://jessecambon.github.io/tidygeocoder/articles/geocoder_services.html#data-privacy) 
- ArcGIS software
  - [What is geocoding?—ArcMap | Documentation](https://desktop.arcgis.com/en/arcmap/latest/manage-data/geocoding/what-is-geocoding.htm)
  - [Geocode Addresses (Geocoding)—ArcGIS Pro | Documentation](https://pro.arcgis.com/en/pro-app/latest/tool-reference/geocoding/geocode-addresses.htm)
  - R + ArcGIS
    - [Leveraging ArcGIS World Geocoding Service in R](https://www.esri.com/arcgis-blog/products/arcgis-pro/analytics/leveraging-arcgis-world-geocoding-service-in-r/)
    - [R-ArcGIS/r-bridge: Bridge library to connect ArcGIS and R, including arcgisbinding R library.](https://github.com/R-ArcGIS/r-bridge)
    - [R-ArcGIS Bridge | Spatial Analysis in R & GIS for Spatiotemporal Data](https://www.esri.com/en-us/arcgis/products/r-arcgis-bridge/overview)
    - [R Notebooks in ArcGIS Pro for Spatial Data Science](https://www.esri.com/arcgis-blog/products/arcgis-pro/analytics/r-notebooks-in-arcgis-pro-for-spatial-data-science/)

## Spatial analysis

- Workshop (R/Medicine 2022): Analyzing Geospatial Data in R • Sherrie Xie
  - [Video](https://www.youtube.com/watch?v=DD7bXonh-_E)
  - [Slides (pptx)](https://github.com/sherriexie/SpatialAnalysisinR/raw/main/Analyzing%20geospatial%20data%20in%20R.pptx)
  - [Repo](https://github.com/sherriexie/SpatialAnalysisinR)
- Talk: Geocomputation with R’s guide to reproducible spatial data analysis • Jakub Nowosad
  - [Slides](https://jakubnowosad.com/ogh2022)
- Talk (RStudio Conf 2018): Tidy spatial data analysis • Edzer Pebezma
  - [Video](https://www.rstudio.com/resources/rstudioconf-2018/tidy-spatial-data-analysis/)
  - [Slides](https://edzer.github.io/rstudio_conf/#1)
- Webinar: [Introduction to Geospatial Analysis in R - ORNL DAAC • Alison Boyer & Jessica Welch](https://daac.ornl.gov/resources/tutorials/r-geospatial-webinar/)
  - [Video](https://www.youtube.com/watch?v=Ul5Ly0266fU)
  - [Slides](https://daac.ornl.gov/resources/tutorials/r-geospatial-webinar/Earthdata_R_Geospatial_webinar_Mar2019_v20190312.pdf)
  - [Repo](https://github.com/ornldaac/r-geospatial-webinar)
- Workshop (RStudio Conf 2020): Modern Geospatial Data Analysis • Zev Ross
  - [Repo](https://github.com/rstudio-conf-2020/geospatial)
- Book: Spatial data analysis • R Spatial
  - [Spatial autocorrelation](https://www.rspatial.org/terra/analysis/3-spauto.html)
  - [Spatial interpolation techniques](https://www.rspatial.org/terra/analysis/4-interpolation.html)
  - [Spatial distribution models](https://www.rspatial.org/terra/analysis/5-global_regression.html)
  - [Spatial regression models](https://www.rspatial.org/terra/analysis/7-spregression.html)
- Book: Geospatial Health Data • Paula Moraga
  - [Spatial modeling of areal data](https://www.paulamoraga.com/book-geospatial/sec-arealdataexamplespatial.html)
  - [Spatio-temporal modeling of areal data](https://www.paulamoraga.com/book-geospatial/sec-arealdataexamplest.html)
  - [Geostatistical data](https://www.paulamoraga.com/book-geospatial/sec-geostatisticaldatatheory.html)
- Book: Intro to GIS and Spatial Analysis • Manuel Gimond
  - [Point pattern analysis](https://mgimond.github.io/Spatial/chp11_0.html)
  - [Hypothesis testing](https://mgimond.github.io/Spatial/hypothesis-testing.html)
- Course: [Applied Spatial Statistics in R • Yuri Zhukov](https://scholar.harvard.edu/zhukov/classes/applied-spatial-statistics-r)
- Course: GIS in R • Earth Lab
  - [Shapefile Structure](https://www.earthdatascience.org/courses/earth-analytics/spatial-data-r/shapefile-structure/)
- Tutorials: The Center for Spatial Data Science
  - [Univariate and bivariate analysis](https://spatialanalysis.github.io/lab_tutorials/2_R_EDA_1.html)
  - [Multivariate exploration](https://spatialanalysis.github.io/lab_tutorials/3_R_EDA_2.html)
  - [Rate mapping](https://spatialanalysis.github.io/lab_tutorials/Rate_mapping.html)
  - [Applications of spatial weights](https://spatialanalysis.github.io/lab_tutorials/Applications_of_Spatial_Weights.html)
  - [Dimension reduction methods](https://geodacenter.github.io/tutorials/pca_mds/pca_mds.html)
  - [Classic clustering methods](https://geodacenter.github.io/tutorials/classic_cluster/classic_cluster.html)
- Workshop notes: R Spatial Workshop - Center for Spatial Data Science • Angela Li
  - [Book of notes](https://spatialanalysis.github.io/workshop-notes/)


[^1]: J.R. Meeker, H. Burris, M.R. Boland, An algorithm to identify residential mobility from electronic health-record data, International Journal of Epidemiology. 50 (2021) 2048–2057. https://doi.org/10.1093/ije/dyab064.

[^2]: C. Brokamp, C. Wolfe, T. Lingren, J. Harley, P. Ryan, Decentralized and reproducible geocoding and characterization of community and environmental exposures for multisite studies, J Am Med Inform Assoc. 25 (2018) 309–314. https://doi.org/10.1093/jamia/ocx128.

[^3]: C. Brokamp, DeGAUSS: Decentralized Geomarker Assessment for Multi-Site Studies, JOSS. 3 (2018) 812. https://doi.org/10.21105/joss.00812.
