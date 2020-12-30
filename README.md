# WiscLand2_masking

Masks Dove, Sentinel-2, Landsat and Harmonized Landsat-Sentinel-2 (HLS) data using the WiscLand2 data.

WiscLand2 is land cover data for the state of Wisconsin. I use this data to mask out anything but forests in my project.  This could be easily be adjusted, though, in the code.

This notebook crops the Wiscland data and the images to a shapefile (such as your study area) and then masks the images of everything but "forest."  Reprojection and resampling are done automatically.

About WiscLand2:
https://www.sco.wisc.edu/2016/09/23/wiscland-2-project-complete-data-now-available/
Download Wiscland2 (will automatically download!):
https://data-wi-dnr.opendata.arcgis.com/datasets/d7f5d33b182044c187c776e47d72ce84
