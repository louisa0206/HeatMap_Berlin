# HeatMap_Berlin
***

### Getting Started
#### Installing Geopandas 
Install Geopandas in an IDE (PyCharm was used here).
[Installation Guide for Geopandas for Jupyter Notebook](https://medium.com/@sourav_raj/ultimate-easiest-way-to-install-geopandas-on-windows-add-to-jupyter-notebook-which-will-a4b11223f4f2)






#### Starting a project
Start a Scrapy Porject.
```
scrapy startproject Glascontainer
```
`cd` into the project folder.
```
cd Glascontainer
```
#### Creating a Spider
Create a Spider.
```
scrapy genspider GlascontainerSpider berlin.de/ba-charlottenburg-wilmersdorf/verwaltung/aemter/umwelt-und-naturschutzamt/umweltschutz/altglascontainer
```
#### Installing Packages
Install packages for the pipeline.
```
pip install requests
pip install geopy
pip install google_trans_new
```
#### Copying the code
Open the *GlascontainerSpider.py* and copy the code into the created Spider in your IDE.\
Open the *pipelines.py* file and copy the code into the pre-created pipelines.py in your IDE.\
Open the *settings.py* file and copy the code into the pre-created settings.py in your IDE.

#### Running the Spider
Run the Spider in Scrapy.
```
scrapy crawl GlascontainerSpider
```
#### Done!
The Code need some time to run.\
The CSV-File is available.
