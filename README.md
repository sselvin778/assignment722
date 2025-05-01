# Analysing greenspace accessability of settlements to their nearest off-road greenspace trail through an interactive web based map
Programming Project for EGM722 - Programming for GIS and Remote Sensing

## Set-up and installation 
This README file contains all necessary instructions to set-up and install relevant softwares, prior to coding. 

### 1. How to get started 
Firstly, before installing `GitHub` to access relevant files, please ensure to create a __GitHub account__.  Next, ensure that `git` is installed onto your computer from [here](https://git-scm.com/downloads), followed by `GitHub Desktop` from [here](https://github.com/apps/desktop), to upload and download changes to/from remote repositories and finally, dont forget to install `conda` from [here](https://www.anaconda.com/docs/getting-started/anaconda/install).

### 2. Fork and clone the repository 
Using the __URL__ to the repository link, __fork__ the repository into your account and then by using `GitHub desktop`, ensure that you __clone__ the repository from `GitHub`, onto the local drive. 

### 3. Creating the conda environment 
To set up your `conda environment`, you first need to use the `environment.yml` provided in the repository and __import__ it into `Anaconda Navigator`. Also make sure to include the essential __dependenices__ needed to run the code which includes as follows:

1. `Python`
2. `Geopandas`
3. `Jupyter-lab`
4. `Folium`

### 4. Configuring Jupyter Lab
Before you begin to write your code, ensure that `jupyter-lab` has been __configured__ by changing the default launch directory to your project file location and by enabling the __terminal__ feature. 

### 5. External data sources and processing 
Once all software’s and packages have been installed, the final step is to download relevant data for the code. Data pertaining settlements can be __downloaded__ from `NISRA` as a shapefile from [here](https://www.nisra.gov.uk/publications/urban-rural-geography-documents-2015), which can be plugged straight into your project folder. 

By utilising `ArcGIS Online`, layers for Northern Ireland greenspaces can be accessed from [here](https://www.arcgis.com/home/item.html?id=c809afd275dd4dd4a519638978bd304a) and layers for the off-road greenspace trails can be accessed from [here](https://www.arcgis.com/home/item.html?id=0c9184ef90704ecf9871ccff622dc721). Both of these layers need to be opened in `ArcGIS Pro`, whereby they should be __exported__ as __features__ and put into your project file.  

### Last step
Please ensure you follow these steps in order to allow the formatting and processing functions to run smoothly. __Good luck!!!__
