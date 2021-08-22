# Training Resources for Geospatial Computing

This is a curated list of training resources for popular packages that are used in geospatial computing. The current list primarily includes Python packages, but it will be updated to include packages from other languages, e.g. R. If you need resources for any particular package, please [contact us](https://crib.utwente.nl/support/open.php) so we can update the list accordingly. 

Please feel free to contribute the adding resources you find useful for geospatial research, education, and training purposes.

## Outline 

- [Common Resources for Geospatial Computing and Earth Observation](#common-resources-for-geospatial-computing-and-earth-observation)
- [Dask](#dask)
- [Xarray](#xarray)
- [GeoPandas](#geopandas)
- [RasterIO](#rasterio)
- [Plotly](#plotly)
- [NumPy](#numpy)
- [Matplotlib](#matplotlib)
- [Pandas](#pandas)
- [Scikit-Learn](#scikit-learn)
- [Seaborn](#seaborn)
- [Cartopy](#cartopy)
- [PySAL](#pysal)
- [SpatioTemporal Asset Catalogs](#spatiotemporal-asset-catalogs)
- [geemap](#geemap)
- [PyTorch](#pytorch)
- [TensorFlow](#tensorflow)
- [JAX](#jax)
- [Miscellaneous Libraries](#miscellaneous-libraries)
	- [Fiona](#fiona)
	- [Xarray-spatial](#xarray-spatial)
	- [Rio-xarray](#rio-xarray)
	- [Regionmask](#regionmask)
	- [Geocube](#geocube)
	- [Salem](#salem)

### Common Resources for Geospatial Computing and Earth Observation

These are links to resources that have useful information and tutorials on geospatial computing and Earth observation. 

- [Awesome Geospatial](https://github.com/sacridini/Awesome-Geospatial) - Long list of geospatial analysis tools
- [GeoHackWeek 2017 Materials](https://github.com/geohackweek/tutorial_contents) - Materials from GeohackWeek which happened in University of Washington in 2017.
- [Python Geospatial Analysis Cookbook](https://github.com/mdiener21/python-geospatial-analysis-cookbook) - Over 60 python recipes to perform spatial operations and build an indoor routing Django web application 
- [Intro to Geospatial Data using Python](https://developer.ibm.com/learningpaths/data-analysis-using-python/introduction-to-geospatial-data-using-python/) - Introduction to geospatial data and its types, vector and raster, and work with geospatial data using Python.
- [Automating GIS Processes](https://automating-gis-processes.github.io/site/index.html) - A course on how to do different GIS-related tasks in Python programming language. Has lessons with tutorials on specific topic(s) where the aim is to learn how to solve common GIS-related problems and tasks using Python tools.
- [Geo Python](https://geo-python-site.readthedocs.io/en/latest/) - The Geo-Python course contains basic concepts of programming and scientific data analysis using the Python. Targeted at beginners with no previous programming experience needed.
- [Parallel Python - Analyzing large Datasets](https://github.com/pydata/parallel-tutorial) - Parallel computing in Python tutorial materials.
- [Course Materials of Fabien Maussion](https://fabienmaussion.info/teaching/) - Includes various courses such as Scientific Programming, Climate Systems, etc
- [Digital Earth Africa Training Course](https://training.digitalearthafrica.org/en/latest/session_1/index.html#) - Sandbox data analysis platform.
- [Digital Earth Australia Notebooks](https://training.digitalearthafrica.org/en/latest/session_1/index.html#) -  Jupyter Notebooks, Python scripts and workflows for analysing Digital Earth Australia (DEA) satellite data and derived products. 
- [Free Earth Data Science Courses and Textbooks (Earth Lab CU Boulder)](https://www.earthdatascience.org/courses/) - Free and open earth data science textbooks and courses as open education resources.
- [Intro to Earth Data Science (Earth Lab CU Boulder)](https://www.earthdatascience.org/courses/intro-to-earth-data-science/) - Analyze and visualize earth and environmental science data using the Python. No prior programming knowledge assumed.
- [Intermediate Earth Data Science (Earth Lab CU Boulder)](https://www.earthdatascience.org/courses/use-data-open-source-python/) - Use Data for Earth and Environmental Science in Open Source Python
- [Open Source Geoprocessing Tutorial](https://github.com/patrickcgray/open-geo-tutorial) - Tutorial of basic remote sensing and GIS methodologies using modern open source software in Python (rasterio, shapely, geopandas, folium, etc).
- [GDAL](https://gdal.org/index.html) - GDAL is a translator library for raster and vector geospatial data formats. 
- [GDAL Tutorials](https://gdal.org/tutorials/index.html) - Tutorials for using GDAL.
- [GIS in Python](https://www.earthdatascience.org/workshops/gis-open-source-python/) - Learn how to use geopandas, rasterio and matplotlib to plot and manipulate spatial data in Python.
- [Awesome-EarthObservation-Code](https://github.com/acgeospatial/awesome-earthobservation-code) - A curated list of awesome tools, tutorials, code, helpful projects, links, stuff about Earth Observation and Geospatial stuff.
- [Python for Atmosphere and Ocean Scientists](https://github.com/carpentries-lab/python-aos-lesson) - Repository containing the Data Carpentry lesson materials for a single day workshop on using python (and git) in the atmosphere and ocean sciences: [Python AOS Lesson](https://carpentrieslab.github.io/python-aos-lesson/).
- [Open Geospatial Datasets for GIS Education](https://github.com/andrea-ballatore/open-geo-data-education) - Repository of open geospatial datasets to be used in an educational context.
- [Awesome GIS](https://github.com/sshuair/awesome-gis) -  Collection of geospatial related sources, including cartographic tools, geoanalysis tools, developer tools, data, conference & communities, news, massive open online course, some amazing map sites, and more.
- [Awesome GeoSpatial List](https://github.com/jerr0328/awesome-geospatial-list) - A curated list of geospatial tools, data, tutorials, information, and more.
- [Open Geospatial Data Download Catalog](https://github.com/iamtekson/geospatial-data-download-sites) - Major sources of open geospatial data download sites.
- [Python for Geospatial Analysis](https://www.tomasbeuzen.com/python-for-geospatial-analysis/README.html) / [Code Repository](https://github.com/TomasBeuzen/python-for-geospatial-analysis) - Crashcourse introduction to using Python to wrangle, plot, and model geospatial data.
- [Geospatial Analyses in Python](https://github.com/makerportal/geospatial-analyses) - Python-based geospatial analysis codes related to: GOES-16 satellite data, national land cover database (NLCD), elevation maps, building footprints, city mapping across the Continental USA.
- [Geospatial Mapping in Python](https://github.com/SirRacha/Geospatial_Mapping_In_Python) - An exploration into working with geospatial data, transforming data types, and visualizing geospatial data in a multitude of ways.
- [Google Earth Engine Python Notebooks](https://github.com/giswqs/earthengine-py-notebooks) - A collection of 360+ Jupyter Python notebook examples for using Google Earth Engine with interactive mapping.
- [Google Earth Engine Examples](https://github.com/giswqs/qgis-earthengine-examples) - A collection of 290+ Python examples for using Google Earth Engine in QGIS.
- [Awesome Earth Engine](https://github.com/giswqs/Awesome-GEE) - A curated list of Google Earth Engine resources.
- [Python From Space](https://github.com/kscottz/PythonFromSpace) - Analyzing Open Satellite Imagery Using the Python Ecosystem. Contains slides and Jupyter notebooks for the "Python from Space" talk at Pycon 2017 in Portland, Oregon.
- [Geospatial Machine Learning](https://github.com/deepVector/geospatial-machine-learning) - A curated list of resources focused on Machine Learning in Geospatial Data Science.
- [Python Geospatial](https://github.com/giswqs/python-geospatial) - A collection of Python packages for geospatial analysis with binder-ready notebook examples.
- [Google Earth Engine with Python](https://github.com/csaybar/EEwPython) -  Series of Jupyter notebook (colabs) to learn Google Earth Engine with python.
- [Kepler.gl](https://github.com/keplergl/kepler.gl) - Data-agnostic, high-performance web-based application for visual exploration of large-scale geolocation data sets. Built on top of Mapbox GL and deck.gl.
- [R GeoNotebooks](https://github.com/mhermans/rgeonotebooks) - RMarkdown notebooks documenting maps & GIS howto's in R.
- [ETL Python Tools for Geospatial Data](https://github.com/jmcarrillog/geospatial-etl) - Multiple tools to perform Extract-Transform-Load (ETL) operations on Geospatial data.
- [Plotting Geospatial Data](https://github.com/Develop-Packt/Plotting-Geospatial-Data) - Utilize Geoplotlib to create geographical visualizations, identify the different types of geospatial charts, and create complex visualizations using tile providers and custom layers.
- [NDVI Stats](https://github.com/bjornjorgensen/ndvistats) - Jupyter Notebook with flow calculation of zonal statistics for selected polygons using geopandas, google earth engine api, rasterio, rasterstats and folium.
- [Lectures on scientific computing with Python](https://github.com/jrjohansson/scientific-python-lectures) - A set of lectures on scientific computing with Python, using IPython notebooks.
- [Practical Data Science](https://www.practicaldatascience.org/html/index.html#) - Course site for Duke Practical Data Science.
- [LearnEO](https://www.learn-eo.org/index.php) - Learn Earth Observation with ESA.
- [EOPortal Directory](https://earth.esa.int/web/eoportal/home) - Earth Observation resources by ESA.
- [Cate](https://climate.esa.int/en/explore/analyse-climate-data/) - The CCI Climate Analysis Toolbox (Cate) is a cloud-enabled computing environment for analysing, processing and visualising all ESA Climate Change Initiative datasets. Cate works by mashing ECV data and other data sources into a common data model. Users operate on this model, then analyse, process, and visualise the results.
- [Intro to Geospatial Data Analysis](https://www.youtube.com/watch?v=kJXUUO5M4ok) - SciPy 2018 Video Tutorial.
- [Spatial Data Analysis with PySAL](https://www.youtube.com/watch?v=i9TRi7r3NxM) - SciPy 2020 Video Tutorial.
- [Data Science Hacks](https://github.com/kunalj101/Data-Science-Hacks) - Data Science Hacks consists of tips, tricks to help you become a better data scientist. Consists of python, jupyter notebook, pandas hacks and so on.
- [Python Data Science Handbook](https://jakevdp.github.io/PythonDataScienceHandbook/) -  Contains the full text of the Python Data Science Handbook by Jake VanderPlas
- [Python Data Science Handbook Code Materials](https://github.com/jakevdp/PythonDataScienceHandbook) - This repository contains the entire Python Data Science Handbook, in the form of Jupyter notebooks.
- [Python Essentials for GIS Learners](https://tu-delft-dcc.github.io/Intro-to-Python-for-GIS) - Materials, exercises and lessons for a 3-day course on Python Essentials for GIS Learners offered to the BK Faculty at TU Delft ([Github Repository](https://github.com/TU-Delft-DCC/Intro-to-Python-for-GIS)).

### Dask

Dask is a flexible library for parallel computing in Python.

Dask is composed of two parts:

1. Dynamic task scheduling optimized for computation. This is similar to Airflow, Luigi, Celery, or Make, but optimized for interactive computational workloads.

2. “Big Data” collections like parallel arrays, dataframes, and lists that extend common interfaces like NumPy, Pandas, or Python iterators to larger-than-memory or distributed environments. These parallel collections run on top of dynamic task schedulers.

- [Dask Documentation](https://docs.dask.org/en/latest/) - Official Dask Documentation
- [Dask Examples](https://examples.dask.org/) / [Code Repository](https://github.com/dask/dask-examples) - Examples show how to use Dask in a variety of situations.
- [Dask Tutorial](https://tutorial.dask.org/) / [Code Repository](https://github.com/dask/dask-tutorial) - Dask Tutorial that was last presented at SciPy 2020. 
- [Dask Tutorial - Nvidia Blog](https://developer.nvidia.com/blog/dask-tutorial-beginners-guide-to-distributed-computing-with-gpus-in-python/) - Beginner’s Guide to Distributed Computing with GPUs in Python.
- [Dask Tutorial with Jupyter Notebooks](https://github.com/adbreind/dask-mini-2019) - A collection of notebooks that have Dask tutorials.
- [Official Dask Youtube Channel](https://www.youtube.com/c/Dask-dev) - Link to the official Dask youtube channel that has videos on how to use Dask.
- [Parallel and Distributed Computing in Python with Dask](https://www.youtube.com/watch?v=EybGGLbLipI) - SciPy 2020 Conference.
- [Scalable Data Analysis in Python with Dask](https://www.youtube.com/playlist?list=PLTgRMOcmRb3OlkfAdqJWyGGrQM7eU-mi7) - Playlist that contains videos on data analysis with Dask.

### Xarray

xarray is an open source project and Python package that makes working with labelled multi-dimensional arrays simple, efficient, and fun!

- [Xarray Tutorial](https://xarray-contrib.github.io/xarray-tutorial/index.html) - Official Xarray Tutorials
- [Xarray Documentation](https://xarray.pydata.org/en/latest/) - Official Xarray documentation
- [Xarray Video Tutorials](https://xarray.pydata.org/en/latest/tutorials-and-videos.html) - Official video tutorials for Xarray
- [GeoHackWeek Xarray Tutorial](https://geohackweek.github.io/nDarrays/) - Series of tutorials by GeoHackWeek
- [Digital Earth Africa Xarray Tutorial](https://training.digitalearthafrica.org/en/latest/python_basics/05_xarray.html) - Specific lesson on Xarrays as a part of Digital Earth Africa training.
- [Xarray with Dask](https://examples.dask.org/xarray.html) - Xarray with Dask arrays
- [EGU2017 Xarray Tutorial and Answers](https://github.com/iiasa/xarray_tutorial) - Contains the EGU2017 tutorial with answers. 
- [Exploring netCDF Datasets using Xarray](https://notebook.community/alaindomissy/xarray_example/Exploring%20netCDF%20Datasets%20Using%20xarray) - A notebook provides discussion, examples, and best practices for working with netCDF datasets in Python using the xarray package.
- [Xarray tutorial for Rossbypalooza](https://gist.github.com/shoyer/d462cc3b2aeb87bbb78cc6f8207851c6) - This notebook introduces xarray for new users in the geophysical sciences.
- [Climate Data Analysis with Xarray](https://ep2021.europython.eu/talks/BhhAcSi-climate-data-analysis-with-xarray-and-cartopy/) - EuroPython talk on climate analysis with Xarray and Cartopy.
- [Weather Data Analysis with Python](https://spire.com/tutorial/spire-weather-tutorial-intro-to-processing-grib2-data-with-python/) - Spire Weather’s global forecast data in GRIB2 format using Python
- [Xarray Introduction and Tutorial](https://boisestate.hosted.panopto.com/Panopto/Pages/Embed.aspx?id=a38a2efc-1ac6-4c02-af0f-acfc015e9444) - Research Computing Days 2021 Xarray Video Tutorial

### GeoPandas

GeoPandas is an open source project to make working with geospatial data in python easier. GeoPandas extends the datatypes used by pandas to allow spatial operations on geometric types

- [GeoPandas Documentation](https://geopandas.org/docs.html) - Official Documentatiom
- [GeoPandas Examples](https://geopandas.org/gallery/index.html) / [Code Repository](https://github.com/geopandas/geopandas/tree/master/doc/source/gallery) - Official GeoPandas collection of examples.
- [GeoPandas Repository](https://github.com/geopandas/geopandas) - Official GitHub repo of GeoPandas
- [Geospatial Fundamentals in Python](https://github.com/dlab-berkeley/Geospatial-Fundamentals-in-Python) - DLab workshop materials on Geospatial analysis using GeoPandas
- [Intro To GeoPandas](https://automating-gis-processes.github.io/CSC18/lessons/L2/geopandas-basics.html) - Course materials of CSC Finland Intro to Python GIS
- [GeoPandas Tutorial (focus on tabular vector data)](https://github.com/jorisvandenbossche/geopandas-tutorial) -  Introduction to geospatial data analysis in Python, with a focus on tabular vector data using GeoPandas.
- [Intro to GeoPandas (Intro to GIS course)](https://autogis-site.readthedocs.io/en/latest/notebooks/L2/01-geopandas-basics.html) - Course materials of Intro to GIS course, University of Helsinki
- [GeoPandas Tutorial by J Cutrer](https://github.com/joncutrer/geopandas-tutorial) - Ingest and plot shapefiles using the geopandas library in python.
- [Exploring GeoPandas](https://nbviewer.jupyter.org/github/RagingTiger/explore-geopandas/blob/master/naturalearth_lowres_data.ipynb) - JupyterLab notebook for exploring GeoPandas using the builtin Natural Earth Low Res dataset.
- [GIS Analysis with GeoPandas](https://github.com/Paritoshyadav/GIS-Analysis-with-GeoPandas-using-Python) -  Basic GIS Analysis with Geo pandas 

### RasterIO

Geographic information systems use GeoTIFF and other formats to organize and store gridded raster datasets such as satellite imagery and terrain models. Rasterio reads and writes these formats and provides a Python API based on Numpy N-dimensional arrays and GeoJSON.

- [RasterIO Repo](https://github.com/mapbox/rasterio) - Official GitHub repository for RasterIO.
- [RasterIO Documentation](https://rasterio.readthedocs.io/en/latest/) - Official Documentation for RasterIO.
- [RasterIO QuickStart](https://rasterio.readthedocs.io/en/latest/quickstart.html) - Short examples of RasterIO in Python.
- [Raster Processing using Python](https://geohackweek.github.io/raster/01-introduction/) - GeoHackWeek materials for Raster. 
- [GeoHackWeek Raster Tutorials](https://github.com/geohackweek/raster-2019) - Contents for GeoHacWeek 2019 raster tutorial.
- [Exploring RasterIO](http://patrickgray.me/open-geo-tutorial/chapter_1_rasterio.html) - Tutorial series by Patrick Grey from Duke.
- [Reading Raster Files](https://automating-gis-processes.github.io/CSC18/lessons/L6/reading-raster.html) - RasterIO materials as part of course Intro to Python GIS.
- [GDAL Raster Tutorials](https://github.com/neerubhai/GDAL-rasterio-tutorials) - Tutorials on how to use GDAL Python API and rasterio for raster data management, transformation, analysis and visualization tasks.
- [Intermediate Earth Data Science (Earth Lab CU Boulder) Raster Tutorial](https://www.earthdatascience.org/courses/use-data-open-source-python/intro-raster-data-python/fundamentals-raster-data/) -  Fundamental concepts related to working with raster data in Python, including understanding the spatial attributes of raster data, how to open raster data and access its metadata, and how to explore the distribution of values in a raster dataset.
- [Open, Plot, and Explore Raster Data in Python](https://www.earthdatascience.org/courses/use-data-open-source-python/intro-raster-data-python/fundamentals-raster-data/open-lidar-raster-python/) - Working with lidar derived raster data that represents both terrain / elevation data, and surface elevation.
- [Create Geospatial Raster from XY Data](https://hatarilabs.com/ih-en/how-to-create-a-geospatial-raster-from-xy-data-with-python-pandas-and-rasterio-tutorial) - Tutorial shows the procedure to run a Scipy interpolation over a Pandas dataframe of point related data having a 2D Numpy array as an output.
- [Advanced Features in RaSterIO](https://gist.github.com/sgillies/7e5cd548110a5b4d45ac1a1d93cb17a3) - Notebook that demonstrates advanced RasterIO concepts useful for developing cloud-native applications.

### Plotly

Plotly's Python graphing library makes interactive, publication-quality graphs.

- [Getting Started with Plotly Python](https://plotly.com/python/)
- [Plotly Fundamentals](https://plotly.com/python/plotly-fundamentals/) - Plotly Python Open Source Graphing Library Fundamentals.
- [Plotly Maps](https://plotly.com/python/maps/) - Plotly Python Open Source Graphing Library Maps.
- [Awesome Dash](https://github.com/ucg8j/awesome-dash) - A curated list of awesome Dash (plotly) resources.
-[Plotly Tutorial for Beginners](https://www.kaggle.com/kanncaa1/plotly-tutorial-for-beginners/notebook#INTRODUCTION) - Learn to use Plotly library.
- [Plotly Tutorial](https://github.com/derekbanas/plotly-tutorial) - Jupyter Notebook that condenses the Plotly API into one easy to use document with examples.
- [Plotly Tutorial](https://www.journaldev.com/19692/python-plotly-tutorial) - Extensive Plotly Tutorial.
- [Series of Plotly Tuturials](https://github.com/achourasia/plotly-tutorial) - Covers Basic, Scientific, Statistic, Financial, Maps, and 3D Plots.
- [Plotly Tutorial for Energy System Modifiers](https://github.com/brynpickering/plotly-tutorial) -  Tutorial on using the Python package Plotly to build plots for energy system related data, as given in openmod Zurich workshop, June 2018.
- [IPython Notebooks for Plotly](https://plotly.com/python/v3/ipython-notebooks/) - Gallery of IPython Notebooks in Python/v3.
- [Graphs and Plots Using Plotly](https://sites.pitt.edu/~naraehan/presentation/Graphs_and_Plots_using_Plotly.html) - Plotly Tutorial on graphs and plotting.

### NumPy

NumPy is the fundamental package for scientific computing in Python. It is a Python library that provides a multidimensional array object, various derived objects (such as masked arrays and matrices), and an assortment of routines for fast operations on arrays, including mathematical, logical, shape manipulation, sorting, selecting, I/O, discrete Fourier transforms, basic linear algebra, basic statistical operations, random simulation and much more.

- [NumPy Quickstart](https://numpy.org/doc/stable/user/quickstart.html) - Quick overview of arrays in NumPy.
- [NumPy Tutorials](https://github.com/numpy/numpy-tutorials) - NumPy tutorials & educational content in notebook format.
- [Creating and Manipulating Numerical Data](https://scipy-lectures.org/intro/numpy/index.html) - SciPy lectures that gives an overview of NumPy.
- [Python NumPy Tutorials](https://cs231n.github.io/python-numpy-tutorial/) - Tutorial by Justin Johnson of University of Michigan.
- [Data Visualization with Python](https://github.com/TrainingByPackt/Data-Visualization-with-Python) - Shows you how to use Python with NumPy, Pandas, Matplotlib, and Seaborn to create impactful data visualizations with real world, public data.
- [Applied Intro To Beginners](https://www.learndatasci.com/tutorials/applied-introduction-to-numpy-python-tutorial/) - Python NumPy tutorial for beginners.
- [NumPy Tutorial for Beginners](https://github.com/eric496/numpy-tutorial) - A Numpy Tutorial for Beginners covering Data Types, Array, Sampling Methods, Maths functions, Slicing and Indexing, Set operations, Linear Algebra.
- [NumPy Beginner Tutorials](https://github.com/rougier/numpy-tutorial) - Tutorial for beginners by Nicolas P. Rougier.
- [First Steps into Data Science in Python](https://realpython.com/numpy-tutorial/) - RealPython guide to NumPy.
- [NumPy Essentials](https://nbviewer.jupyter.org/github/mdkearns/scientific-computing-libraries/blob/master/NumPy-Library-Essentials.ipynb) - NumPy tutorial by Matthew Kearns covering essential concepts.
- [EuroSciPy 2018 NumPy tutorial](https://nbviewer.jupyter.org/github/gertingold/euroscipy-numpy-tutorial/blob/master/numpy-tutorial-solved.ipynb) - NumPy tutorial covered in EuroSciPy 2018.
- [Advanced NumPy](https://scipy-lectures.org/advanced/advanced_numpy/index.html) - SciPy lecture on Advanced NumPy functionality.
- [NumPy Cheat Sheet](https://github.com/derekbanas/NumPy-Tutorial) - Cheat Sheet for NumPy.
- [Python NumPy Beginner Video Tutorial](https://www.youtube.com/watch?v=QUT1VHiLmmI) - Basics of the NumPy library provided by freeCodeCamp.
- [NumPy Video Tutorial by Derek Banas](https://www.youtube.com/watch?v=8Y0qQEh7dJg) - Updated Video tutorial for NumPy.

### Matplotlib

Matplotlib is a comprehensive library for creating static, animated, and interactive visualizations in Python.

- [Matplotlib Documentation](https://matplotlib.org/stable/users/index.html) - Official Matplotlib documentation.
- [Matplotlib Tutorials](https://matplotlib.org/stable/tutorials/index.html) - Official tutorials for Matplotlib covering concepts frmo beginner to advanced.
- [Anatomy of Matplotlib](https://github.com/matplotlib/AnatomyOfMatplotlib) - Tutorial developed for the SciPy conference
- [Beginner Matplotlib Tutorials](https://github.com/rougier/matplotlib-tutorial) - Tutorials for beginner provided by Nicolas P. Rougier.
- [Getting Started with Matplotlib](https://github.com/matplotlib/GettingStarted) - SciPy 2019 Tutorial.
- [Plotting with Matplotlib](https://realpython.com/python-matplotlib-guide/) - RealPython guide to Matplotlib.
- [SciPy Matplotlib Tutorial](https://scipy-lectures.org/intro/matplotlib/index.html) - Explore matplotlib in interactive mode covering most common cases.
- [Time Series Exploration with Matplotlib](https://github.com/matplotlib/interactive_tutorial) - Interactive Matplotlib tutorial.
- [Matplotlib Tutorial Notebooks](https://github.com/veb-101/Numpy-Pandas-Matplotlib-Tutorial) - Tutorial notebooks on numpy, pandas and matplotlib.
- [Data Visualization with Python](https://github.com/TirendazAcademy/DATA-VISUALIZATION-WITH-PYTHON) - Data Visualization tutorials with Jupyter Notebooks.
- [Maptplotlib Video Tutorial Series](https://www.youtube.com/playlist?list=PL-osiE80TeTvipOqomVEeZ1HRrcEvtZB_) / [Code Respository](https://github.com/manjusv/Matplotlib_tutorial) - Video Tutorial series by Corey Schafer.
- [Matplotlib Video Tutorial](https://www.youtube.com/watch?v=wB9C0Mz9gSo) - Video tutorial by Derek Banas.

### Pandas

pandas is an open source, BSD-licensed library providing high-performance, easy-to-use data structures and data analysis tools for the Python programming language.

- [Pandas](https://github.com/pandas-dev/pandas) - Official GitHub repository of Pandas.
- [Pandas Documentation](https://pandas.pydata.org/pandas-docs/stable/user_guide/index.html#user-guide) - Official Pandas Documentation. Has interactive Notebooks at the end.
- [Intro Tutorials](https://pandas.pydata.org/pandas-docs/stable/getting_started/intro_tutorials/index.html) - Official intro to Pandas
- [Community Tutorials](https://pandas.pydata.org/pandas-docs/stable/getting_started/tutorials.html) - Pandas Community tutorials geared for new users. Has excellent resources (Notebooks and video).
- [Pandas Tutorial](https://www.dataquest.io/blog/pandas-python-tutorial/) - Analyzing Video Game Data with Python and Pandas.
- [Pandas Exercises](https://github.com/guipsamora/pandas_exercises) - Repository just with exercises to practice pandas. 
- [Series of Pandas Tutorial](https://github.com/TirendazAcademy/PANDAS-TUTORIAL) - Jupyter Notebooks and Data Sets for Pandas Library.
- [Scikit-Learn and Pandas](https://github.com/luciasantamaria/pandas-tutorial) - Teaching materials for pandas and scikit-learn.
- [Pandas Scipy Conference Tutorials](https://github.com/jorisvandenbossche/pandas-tutorial) - Material for the pandas tutorial at EuroScipy 2016.
- [100 Pandas Puzzles](https://github.com/ajcr/100-pandas-puzzles) - 100 data puzzles for pandas, ranging from short and simple to super tricky.
- [PyCon 2019 Presentation on Pandas](https://github.com/justmarkham/pycon-2019-tutorial) - Data Science Best Practices with pandas.
- [Python Pandas Tutorial](https://www.learndatasci.com/tutorials/python-pandas-tutorial-complete-introduction-for-beginners/) - A Complete Introduction for Beginners.
- [PyData Book Materials](https://github.com/wesm/pydata-book) - Materials and IPython notebooks for "Python for Data Analysis" by Wes McKinney, published by O'Reilly Media.
- [Dataframes in Python](https://www.datacamp.com/community/tutorials/pandas-tutorial-dataframe-python) - Datacamp tutorial on exploring data analysis with Python.
- [Pandas Video Tutorial](https://www.youtube.com/playlist?list=PL-osiE80TeTsWmV9i9c58mdDCSskIFdDS) - Video Tutorial series by Corey Schafer.
- [Pandas Extensive Video series](https://github.com/justmarkham/pandas-videos) - Jupyter notebook and datasets from the pandas Q&A video series from Data School.

### Scikit-Learn

- [Scikit-Learn Tutorials](https://scikit-learn.org/stable/tutorial/index.html) - Official scikit-kearn tutorials.
- [Machine Learning with scikit-learn](https://scikit-learn.org/stable/tutorial/basic/tutorial.html) - An introduction to machine learning with scikit-learn.
- [Scikit-Learn Tutorial (ML)](https://www.datacamp.com/community/tutorials/machine-learning-python) - An easy-to-follow scikit-learn tutorial that will help you get started with Python machine learning provided by Datacamp.
- [Sckit-Learn Extensive tutorial](https://github.com/jakevdp/sklearn_tutorial) - Materials for Scikit-Learn tutorial.
- [Scikit-Learn Videos](https://github.com/justmarkham/scikit-learn-videos) - Jupyter notebooks from the scikit-learn video series by Data School.
- [Scikit-Learn and Pandas](https://github.com/luciasantamaria/pandas-tutorial) - Teaching materials for pandas and scikit-learn.
- [Scikit-Learn Video Course](https://www.youtube.com/watch?v=pqNCD_5r0IU) - Scikit-Learn video course provided by freeCodeCamp.

### Seaborn

Seaborn is a Python visualization library based on matplotlib. It provides a high-level interface for drawing attractive statistical graphics.

- [Seaborn](https://github.com/mwaskom/seaborn) - Statistical data visualization in Python. Official Github Repo.
- [Seaborn User Guide Tutorials](https://seaborn.pydata.org/tutorial.html) - Official user guide and tutorials.
- [Ultimate Python Seaborn Tutorial](https://elitedatascience.com/python-seaborn-tutorial) - Step-by-step Seaborn tutorial
- [Visualization with Seaborn](https://jakevdp.github.io/PythonDataScienceHandbook/04.14-visualization-with-seaborn.html) - Excerpt from the Python Data Science Handbook by Jake VanderPlas
- [Seaborn Tutorial](https://github.com/clair513/Seaborn-Tutorial) - Includes all the types of plot offered by Seaborn, applied on random datasets.
- [Series of Seaborn Notebooks](https://github.com/corazzon/seaborn-tutorial) - Training notebooks in Seaborn.
- [Matplotlib and Seaborn Tutorial](https://github.com/roguexray007/Matplotlib-and-Seaborn-Tutorial) - Tutorials for easy understanding of matplotlib and seaborn commands for graph plotting.
- [Plotting with Seaborn and Matplotlib](https://github.com/mohdsanadzakirizvi/Matplotlib-Seaborn-Tutorial) - Basic to advanced visualization techniques and some basic Exploratory Data Analysis on a dataset.
- [Practical Data Visualization](https://github.com/pmaji/practical-python-data-viz-guide) - Resources for teaching & learning practical data visualization with python.
- [Data Visualization](https://github.com/DataForScience/DataViz) - Data Visualization With Matplotlib and Seaborn.
- [Cheat Sheet](https://github.com/derekbanas/seaborn) - Seaborn Cheat Sheet provided by Derek Banas.
- [Seaborn Video Tutorial](https://www.youtube.com/watch?v=6GUZXDef2U0) - Video Tutorial provided by Derek Banas

### Cartopy

Cartopy is a python package which provides a set of tools for creating projection-aware geospatial plots using python’s standard plotting package, matplotlib. Cartopy also has a robust set of tools for defining projections and reprojecting data.

- [Cartopy Documentation](https://scitools.org.uk/cartopy/docs/latest/) - Official cartopy documentation.
- [Cartopy SciPy 2018](https://github.com/SciTools/cartopy-tutorial) - Cartopy tutorial: Around the world in 80 ways.
- [Basic Cartopy Tutorial](https://github.com/nawendt/cartopy-tutorial) - Basic tutorial for cartopy map plotting Python package.
-  [Maps with Cartopy](https://rabernat.github.io/research_computing_2018/maps-with-cartopy.html) - Tutorial on building maps with Cartopy.
- [Simple Maps with Cartopy](https://geohackweek.github.io/visualization/03-cartopy/) - Basic and quick intro to Cartopy.

### PySAL

The python spatial analysis library for Geospatial Data Science

- [PySAL Documentation](https://pysal.org/docs/users/) - Official documentation, contains a list of courses, workshops, tutorials, and presentations. 
- [PySAL Notebooks Project](https://pysal.org/notebooks/intro) - This is a compilation of official notebooks demonstrating the functionality of PySAL, the Python Spatial Analysis library.
- [Intermediate Methods for Geospatial Data Analysis](https://github.com/pysal/scipy2019-intermediate-gds) - SciPy 2019 tutorial. 
- [Geographic Data Science with PySAL and the pydata stack](https://darribas.org/gds_scipy16/) - SciPy 16 tutorials.

### SpatioTemporal Asset Catalogs

The SpatioTemporal Asset Catalog (STAC) specification provides a common language to describe a range of geospatial information, so it can more easily be indexed and discovered. A 'spatiotemporal asset' is any file that represents information about the earth captured in a certain space and time.

- [STAC](https://github.com/radiantearth/stac-spec) - Official Github repository containing the core object type specifications, examples, validation schemas, and documentation about the context and plans for the evolution of the specification.
- [STAC openAPI](https://stacspec.org/STAC-api.html) - The openAPI of STAC.
- [Introduction to SpatioTemporal Asset Catalogs](https://www.youtube.com/watch?v=qGRrDPTwpmk) - Video tutorial.
- [STAC utilities](https://github.com/orgs/stac-utils/repositories) - Official Github repository for STAC utilities like integrations with various databases, clients and programming languages.
- [PySTAC Documentation](https://pystac.readthedocs.io/en/latest/) - The official documentation of PySTAC, a python library for working with STAC.
- [PySTAC Tutorial](https://www.youtube.com/watch?v=5Q_v_qRpST8) - Video tutorial for the PySTAC library.
- [PySTAC Tutorial Jupyter Notebooks](https://github.com/stac-utils/pystac/tree/main/docs/tutorials) - Interactive notebooks with PySTAC examples.

### geemap

geemap is a Python package for interactive mapping with [Google Earth Engine (GEE)](https://earthengine.google.com/), which is a cloud computing platform with a multi-petabyte catalog of satellite imagery and geospatial datasets.

- [geemap Documentation](https://geemap.org/) - geemap official documentation.
- [geemap Jupyter Notebooks](https://github.com/giswqs/earthengine-py-notebooks) - Collection of examples as interactive notebooks for geemap.
- [geemap Tutorial Series](https://youtube.com/playlist?list=PLAxJ4-o7ZoPccOFv1dCwvGI6TYnirRTg3) - Official video tutorials created by geemap author.
- [geemap list of tutorials](https://github.com/giswqs/geemap/tree/master/examples) - List of official geemap tutorials and examples with links to the resources used in the tutorial.

### PyTorch

PyTorch is an optimized tensor library for deep learning using GPUs and CPUs.

- [PyTorch Documentation](https://pytorch.org/docs/stable/index.html) - Official PyTorch documentation.
- [PyTorch](https://github.com/pytorch/pytorch) - Official PyTorch Github repository.
- [PyTorch Examples](https://github.com/pytorch/examples) - Official Github repository containing PyTorch examples. 
- [PyTorch tutorials](https://pytorch.org/tutorials/) - Official tutorials for the whole PyTorch ecosystem.
- [PyTorch video tutorials](https://youtube.com/playlist?list=PLQVvvaa0QuDdeMyHEYc0gxFpYwHY2Qfdh) - PyTorch video tutorial series made by Harrison Kinsley.
- [PyTorch video tutorials](https://youtube.com/playlist?list=PLZbbT5o_s2xrfNyHZsM6ufI0iZENK9xgG) - PyTorch video tutorial series made by deeplizard.

### TensorFlow
TensorFlow is an end-to-end open source platform for machine learning. It has a comprehensive, flexible ecosystem of tools, libraries and community resources that lets researchers push the state-of-the-art in ML and developers easily build and deploy ML powered applications.

- [TensorFlow Python Documentation](https://www.tensorflow.org/api_docs/python/tf) - TensorFlow official documentation for Python.
- [TensorFlow](https://github.com/tensorflow/tensorflow) - Official TensorFlow Github repository.
- [TensorFlow Tutorials](https://www.tensorflow.org/tutorials) - Official tutorials for the whole TensorFlow ecosystem.
- [TensorFlow Guides As Interactive Notebooks](https://www.tensorflow.org/guide) - Official interactive notebook guides for TensorFlow.
- [TensorFlow Video Tutorials](https://www.youtube.com/playlist?list=PLhhyoLH6IjfxVOdVC1P1L5z5azs0XjMsb) - TensorFlow beginner video tutorial series made by Aladdin Persson.
- [TensorFlow Tutorial For Beginners](https://www.datacamp.com/community/tutorials/tensorflow-tutorial) - A tutorial aimed at beginners, includes interactive code examples.
- [TensorFlow Curated Resource List](https://github.com/jtoy/awesome-tensorflow) - An extensive list of TensorFlow tutorials, videos, tools, etc.
- [TensorFlow Tutorials](https://github.com/Hvass-Labs/TensorFlow-Tutorials) - TensorFlow tutorials that include a detailed interactive notebook and accompanying video lecture.


### JAX
JAX is [Autograd](https://github.com/hips/autograd) and [XLA](https://www.tensorflow.org/xla), brought together for high-performance numerical computing and machine learning research.

- [JAX](https://github.com/google/jax) - Official Github repository.
- [JAX Documentation](https://jax.readthedocs.io/en/latest/) - Official documentation.
- [JAX tutorials](https://jax.readthedocs.io/en/latest/jax-101/index.html) - Official JAX tutorials.
- [Getting Started With JAX](https://roberttlange.github.io/posts/2020/03/blog-post-10/) - A blog post introducing JAX concepts.
- [JAX: Accelerated Machine Learning Research](https://www.youtube.com/watch?v=z-WSrQDXkuM) - SciPy 2020 video tutorial.
- [JAX Ecosystem Meetup](https://www.youtube.com/watch?v=iDxJxIyzSiM) - NeurIPS 2020 video  tutorial.
- [Introduction To JAX](https://www.youtube.com/watch?v=0mVmRHMaOJ4) - Google Cloud Tech video.
- [JAX Curated Resource List](https://github.com/n2cholas/awesome-jax) - An extensive list of JAX tutorials, videos, tools, etc.


## Miscellaneous Libraries

### Fiona

Fiona reads and writes geographic data files and thereby helps Python programmers integrate geographic information systems with other computer systems. Fiona contains extension modules that link the Geospatial Data Abstraction Library (GDAL).

- [Fiona](https://github.com/Toblerity/Fiona) - Official GitHub repository.
- [Fiona Documentation](https://fiona.readthedocs.io/en/latest/) - Fiona Documentation
- [Examples](https://github.com/Toblerity/Fiona/tree/master/examples) - Fiona Examples

### Xarray-spatial

Xarray-Spatial implements common raster analysis functions using Numba and provides an easy-to-install, easy-to-extend codebase for raster analysis.

- [Xarray-spatial](https://github.com/makepath/xarray-spatial) - Official GitHub repository.
- [Xarray-spatial Documentation](https://xarray-spatial.org/index.html) - Official Documentation for Xarray-spatial.
- [Examples](https://github.com/makepath/xarray-spatial/tree/master/examples) - Official examples for using Xarray-spatial.

### Rio-xarray

Geospatial xarray extension powered by rasterio

- [Rio-xarray Documentation](https://corteva.github.io/rioxarray/stable/) - Official documentation for Rio-xarray.
- [Rio-xarray](https://github.com/corteva/rioxarray) - Official GitHub repository.
- [Examples](https://corteva.github.io/rioxarray/stable/examples/examples.html) - Official exmaples for Rio-xarray.

### Regionmask

regionmask is a Python module that:

Contains a number of defined regions, including: countries (from Natural Earth), a landmask and regions used in the scientific literature (the Giorgi regions 1 and the SREX regions 2). Can plot figures of these regions with matplotlib and cartopy. Can be used to create masks of the regions for arbitrary longitude and latitude grids (2D integer masks and 3D boolean masks). Support for shapefiles is provided via geopandas. Arbitrary regions can be defined easily.

- [RegionMask](https://github.com/regionmask/regionmask) - Official Github Repository.
- [RegionMask Documentation](https://regionmask.readthedocs.io/en/stable/) - Official documentation for Regionmask.
- [RegionMask Tutorial Notebooks](https://github.com/regionmask/regionmask/tree/master/docs/notebooks) - Official tutorials with Jupyter Notebooks.

### Geocube

Tool to convert geopandas vector data into rasterized xarray data.

- [Geocube](https://github.com/corteva/geocube) - Official GitHub repository.
- [Geocube documentation](https://corteva.github.io/geocube/stable/) - Official Geocube documentation.
- [Examples](https://corteva.github.io/geocube/stable/examples/examples.html) - Official examples for using Geocube.

### Salem

Salem is a small library to do geoscientific data processing and plotting. It extends xarray to add geolocalised subsetting, masking, and plotting operations to xarray’s DataArray and DataSet structures.

- [Salem](https://github.com/fmaussion/salem) - GitHub repository for Salem.
- [Salem Documentation](https://salem.readthedocs.io/en/stable/) - Official documentation for Salem.
- [Examples](https://github.com/fmaussion/salem/tree/master/docs/examples) - Examples for using Salem.
