# QGIS Raster Divider Plugin

This plugin helps users create raster subsets quickly and easily. Details are provided below:
<br/><br/>

<img width="800" src="./images/image_1.png">
<br/>
<b>Extent of Subset:</b> Specifies the extent of the subset area. <i>Layer Extent</i>, <i>Canvas Extent</i>, and <i>Manual Draw</i> options are available, and the extent coordinates can also be entered manually. The coordinate reference system (CRS) of the subset extent is displayed in the lower-right corner. <img width="15" src="./images/image_2.png"> button can be used to change the CRS of extent.
<br/>

<br/>
<b>Output  Type:</b> Output type and compression method is specified here. Two types of output formats are available (GeoTiff, VRT).
<br/>

<br/>
<b>Extra Creation Options:</b> This section is optional. Creation options, other than compression method, can be specified here. (e.g. TFW=YES, BIGTIFF=YES)
<br/>

<br/>
<b>Output Folder Path:</b> The path of the folder where the output files are saved is specified here. If no path is specified, output files are saved to the QGIS default temporary folder.
<br/>

<br/>
<b>Add Alpha Band:</b> If this option is checked, an alpha band is added to the output raster files.
<br/>

<br/>
<b>Get Raster Layers From Canvas:</b> Available raster layers are added to the raster list to be used for clipping.<br/>
<b>Browse:</b> Rasters outside the canvas can be selected and added to the raster list to be used for clipping.<br/>
<b>Remove Selected:</b> Rasters that are not intended to be used for clipping can be selected and removed from the raster list.<br/>
<b>Clear:</b> This option is used to clear the raster list.
<br/>

<br/>
<b>Raster List:</b> The rasters to be clipped are listed here. Users can manage the rasters. If the path of a raster is shown in red, it indicates a conflict between the raster CRS and the extent CRS. <b>The plugin automatically handles CRS conflicts; however, matching the SRS before clipping is recommended.</b>
<br/>
