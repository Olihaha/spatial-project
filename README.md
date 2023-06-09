# Spatial Analytics Project
this is my project for spatial analytics.

This repository is supposed to be used alongside the PDF file uploaded as a way to view the code.

## Contents 
- this repository contains an RMD file, a html file, a folder with data and a folder with images. 
To make use of the interactive maps the plots must be viewed in html, therefore the images folder is irrelevant. Instead they must be viewed with the following link utilizing github pages:  https://olihaha.github.io/spatial-project/index.html

- The images folder contains images of the graphs and maps drawn, these are only saved for my own usage. 

- In the src folder is a file.Rmd which contains all of the code for the project that was used. 

- The data folder contains the World_shape_file which is the country borders used for mapping and the dataset.csv. The dataset is the global terrorism database converted to a csv file.


## Libraries 
| Library         | Purpose                                             |
|-----------------|---------------------------------------------------|
| Tidyverse (v2.0) | Data manipulation, data visualization and everything pretty much |
| Data.table (v1.14.8) | When manipulating some data errors appeared that were fixed with this library |
| Magrittr (v2.0.3) | similar as above |
| Leaflet (v2.11.2) | Used for mapping |
| Maps (v3.4.1) | for geommapping |
| Maptools (v1.3.2) | same as above |
| Htmltools (v0.5.5) | used for html intergration, had errors when knitting to a HTML file which this library helped me fix |
| Rgdal (1.6-7) | used for READOGR command to read the spatial objects and import them into our "world map" |
| Ggthemes (v1.0.4) | Creates clean HTML output formats |
| Ggmap (v3.0.02) | used for ggplot mapping |
| Gganimate(v1.0.8) | used for gif generation |
| Mapview(v2.11.0)| to save images generated |

## How to reproduce
To reproduce the results found do the following : 
1. Clone the repository ```git clone https://github.com/Olihaha/spatial-project```
2. Install the libraries listed above
3. Run the code in the rmd file located in the src folder. 

Make sure that the libraries listed above are installed. 

The rest of the information is available in the pdf file