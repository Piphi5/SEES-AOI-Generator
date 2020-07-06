# Usage

The script above creates a CSV file (to be imported into Google My Maps or ArcGIS) containing a 36 point grid spaced out by 500m from the Latitude, Longitude coordinates of a centerpoint. The center point can be found through google maps or other GIS services.

## Example Run:
(Quick Example using Google Maps and Google My Maps)

Go onto Google Maps, and click on your desired centerpoint.
![](https://github.com/Piphi5/Mapper-Automation-Notebook/blob/master/tutorial_images/MM_SampleCenter.PNG)
Then get the coordinates of the centerpoint.
![](https://github.com/Piphi5/Mapper-Automation-Notebook/blob/master/tutorial_images/MM_SampleCenterCoords.PNG)

Now, run the script with the latitude and longitudes of this center point. The program will generate a CSV called "AOI_Points.csv".


With the CSV file, we can import it into Google MyMaps. 
![](https://github.com/Piphi5/Mapper-Automation-Notebook/blob/master/tutorial_images/MM_Add.PNG)
![](https://github.com/Piphi5/Mapper-Automation-Notebook/blob/master/tutorial_images/MM_import.PNG)
Select these settings to help my maps setup:
![](https://github.com/Piphi5/Mapper-Automation-Notebook/blob/master/tutorial_images/MM_setupColumns.PNG)
![](https://github.com/Piphi5/Mapper-Automation-Notebook/blob/master/tutorial_images/MM_title.PNG)

From here, you can move around any points that might be unaccessible (e.g ontop of a house, lake, etc.) and then you can generate directions to collect your points.

![](https://github.com/Piphi5/Mapper-Automation-Notebook/blob/master/tutorial_images/MM_finalproduct.PNG)
![](https://github.com/Piphi5/Mapper-Automation-Notebook/blob/master/tutorial_images/MM_SampleDirection.PNG)

