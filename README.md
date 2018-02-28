## Data repository for the paper: [Seasonal shoreline variability induced by subtidal water level fluctuations at reef-fringed beaches](http://onlinelibrary.wiley.com/doi/10.1002/2017JF004385/full) by Laura Elena Segura, Jeff Hansen and Ryan Lowe. Journal of Geophysical Research: Earth Surface (2018)

In this repository you can find the dataset with the shorelines extracted from 44 high-resolution images ([Nearmap.com.au](http://nearmap.com.au)) and 19 topographic surveys.
The data is in MATLAB files (.mat). If you need the data in another format please let me know.

* Shorelines from images: shorelines_nearmap.mat
   `date_nearmap`: year, month and day when the image was taken of the corresponding shorelien was taken.
   `dateser_nearmap`: serial date (Number of days from 1/1/1970)
   `yy_nearmap`: a matrix of 1300 rows and 49 columns. The rows represent the cross-shore shoreline position recorded each meter starting    at 1352 m (row 1) and finishing in 53 m. If you want to plot the shorelines as in the paper, just plot them againts a  vector y =   
   53:1:1352 that represents the alongshore position.

* Shoreline from topographic surveys: Contours_MO.map 
  `dates_MO`: serial date, year, month and day for each topographic survey where the shoreline contour was extracted.
  `swell_MO`: Mean swell wave height for the day that each topographic survey was collected.
  `days`: a list with the dates as Mmm dd.
  `height`: elevation of the shoreline contours. It has seven elevations. The resuts from the paper were calculated using the contours from the elevation 2 (yy2).
  `yy00, yy1, yy2, ...`: Contours corresponding to each elevation.
