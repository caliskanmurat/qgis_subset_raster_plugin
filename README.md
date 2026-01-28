# QGIS Raster Divider Plugin

This plugin allows user to create subset of a raster quickly and easily. Two types of output formats are available (GeoTiff, VRT).
<br/><br/>

<img width="800" src="./images/image.png">
<br/>
<i>Generate Footprints</i> section is first part of the analysis. In this section a <i><b>Geopackage (GPKG)</b></i> file is created. This file contains informations about the tiles to be generated such as "<i>col_id, row_id, overlap_col, overlap_row, etc.</i>". Tiles that are not desired should be deleted from the attribute table of the GPKG file. The original raster file is splitted based on this file.
<br/>

<br/>
<b>Input  Raster Data:</b> Image to be splitted is specified here.
<br/>

<br/>
<b>Chunk Size:</b> Width, Height sizes of each tile are specified here.
<br/>

<br/>
<b>Overlap:</b> Overlap sizes of each tile are specified here.
<br/>

<br/>
<b>Overlap Strategy:</b> There are two options for overlapping.<br/>

- <b><i>Auto</i></b> : In this method an auto overlapping is applied to tiles to make the subraster completely align with the original raster. For instance; if raster size is 1000 px and desired tile size is 150 px than 6 subraster would be generated with <b>100px residual</b>. In order to prevent this residual, subrasters are overlapped automatically even if the overlapping value is 0. If the overlapping value is set as a number greater than 0, subrasters are overlapped automatically <b>taking this value into account</b>.
<br/><br/>
