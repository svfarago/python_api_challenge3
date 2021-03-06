# python_api_challenge
This is my first Pandas project using APIs and mapping within a Jupyter Notebook.

================
ReadMe File
================

Updated: Jan 25, 2021 | Created: Jan 20, 2021
Copyright: open source

== License ===========================
None. See Installation instructions below for a list of applications.


== Configuration Instructions ========
None. See Installation instructions below for a list of applications.


== Installation Instructions ==========
Applications used for the python_api_challenge:
- Jupyter Notebook
- GitBash terminal
- Visual Studio Code for the Readme.md
- Git Hub (to save versions and share code while in development)
- Image viewer such as Microsoft Photos or Microsoft Paint
- Various dependencies and setups were required as part of pip, Jupyter Notebook. See "Dependencies and Setup" at the top of each Jupyter Notebook for a list of dependencies.

Similar applications may also work.


== Operating Instructions =============
Open either the WeatherPy or VacationPy file in Jupyter Notebook.
Review Analysis at the top of the notebook.
Play/run all rows in order from top to bottom to review code output and data analysis.

ATTENTION: IF you want to run this script, register to the API resources listed below and name the file api_key.py in the either the WeatherPy or VacationPy folder.

== List of Files ====================
\python_api_challenge
    \output_data  (all image files auto-generated from WeatherPy script)
        weather_globalcities.csv
        Latitude_cloudiness.png
        Latitude_humidity.png
        Latitude_temperature.png
        Latitude_windspeed.png
        Linreg_north_cloud.png
        Linreg_north_humid.png
        Linreg_north_temp.png
        Linreg_north_wind.png
        Linreg_south_cloud.png
        Linreg_south_humid.png
        Linreg_south_temp.png
        Linreg_south_wind.png
    \VacationPy
        .ipynb_checkpoints
        --pycache--
        api_keys
        VacationPy.ipynb
        VacationPy_Heatmap.png
        VacationPy_Hotelmap.png
    \WeatherPy
        .ipynb_checkpoints
        --pycache--
        api_keys
        WeatherPy.ipynb
    README.md


== Data Set(s) =======================
Data pulled from APIs. See API Resources below.


== API Resources =======================
https://openweathermap.org/appid
https://developers.google.com/maps/apis-by-platform 
Monitor Google API usage at: https://developers.google.com/maps/reporting/gmp-reporting

Registration is required to obtain personal APIs. Follow respective documentation at each website for more information.
APIs registered on: January 22, 2021


== Data Alterations =======================
None.

Analysis Impact: None.


== Known Bugs =====================
None.


== Troubleshooting ===============
#print hashtags are used liberally throughout the code to run individual lines of code for additional testing/troubleshooting, and general comment hashtags are used for code notes/additional information.

Heatmaps
I was unable to initially print heatmaps. From command line I ran these two lines:
$  pip install gmaps
$  jupyter nbextension enable --py --sys-prefix gmaps
Then I completely shut down Jupyter Notebook and restarted it.


Resources used to build and troubleshoot this code are listed below, in addition to help and code peer review from students, instructor, and TA's.


Web URLs:
https://ohshitgit.com/
https://github.com/mwaskom/seaborn/issues/375
https://www.geographyrealm.com/latitude-longitude/
https://www.w3schools.com/python/python_try_except.asp
https://jupyter-gmaps.readthedocs.io/en/v0.3.3/gmaps.html
https://jupyter-gmaps.readthedocs.io/en/latest/tutorial.html
https://www.geeksforgeeks.org/python-pandas-dataframe-dropna/
https://stackoverflow.com/questions/47536735/my-google-heat-map-wont-appear-in-jupyter-notebook
https://www.geeksforgeeks.org/drop-rows-from-the-dataframe-based-on-certain-condition-applied-on-a-column/
https://stackoverflow.com/questions/11854847/how-can-i-display-an-image-from-a-file-in-jupyter-notebook


URLs last used: January 25, 2021



== Contact Information ===============
Colorado   United States



== Random Notes ===============
This is my first Pandas project using APIs and mapping within a Jupyter Notebook.
Time to complete: approximately 22 hours
