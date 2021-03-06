# OpticalRS Modules

OpticalRS methods are organized into various modules. When appropriate, modules are named after the journal paper from which they were derived. The following details were autogenerated from the first paragraph of the module docstrings. For full details, look at the docstrings on [GitHub](https://github.com/jkibele/OpticalRS/) or the the installed code.

Module | Description
--|--
AlbedoIndex | <sup>Code for generating a water column corrected image from multispectral imagery. This is a method of water column correction for habitat mapping. It is based on Maritorena et al. 1994 and is described in detail in Chapters 4 and 5 of my PhD thesis (Kibele, In Review). </sup> 
ArrayUtils | <sup>This module contains functions that are applied to numpy array representations of images. Unless stated otherwise, image arrays are expected to be of shape (RowsxColumnsxN) where N is the number of bands. </sup> 
DepthEstimator | <sup>Code for handling required data and producing depth estimates from multispectral satellite imagery. KNN (Kibele and Shears, In Review) and linear methods (Lyzenga et al., 2006) are currently supported. </sup> 
KNNDepth | <sup>Code for the empirical regression of depth from multispectral imagery using the k nearest neighbors technique (Kibele and Shears, In Review). This method should typically be accessed throught the OpticalRS.DepthEstimator module. </sup> 
LandMasking | <sup>This module contains methods for masking land in multispectral satellite imagery based on thresholding the NIR band and filtering the result for mask connectivity. This code also shows up in the [Multispectral Land Masker QGIS plugin](https://github.com/jkibele/LandMasker). </sup> 
Lyzenga1978 | <sup>This module implements some of the methods described in Lyzenga 1978. These methods are used in depth estimation from multispectral imagery and in water column correction for bottom type classification. </sup> 
Lyzenga1981 | <sup>This file will implement methods from Lyzenga 1981 for producing a depth invariant index from multispectral satellite imagery. Unless otherwise stated methods will expect image arrays in the shape of (Rows,Columns,Bands). </sup> 
Lyzenga2006 | <sup>This module implements methods described in Lyzenga et al. 2006. The methods implemented so far are mostly the image preprocessing steps. </sup> 
MSDisplay | <sup>Methods for displaying multispectral images and information about them. I've found these methods useful when exploring images. </sup> 
MSExposure | <sup>This module contains **POORLY TESTED** methods for adjusting the exposure of multispectral images. Unless otherwise stated methods will expect image arrays in the shape of (Rows,Columns,Bands). These methods should be considered expirimental at this point. </sup> 
RasterDS | <sup>The RasterDS object will provide some utilities for getting raster data sets into and out of numpy array formats. The main feature is the simplification of reading and writing to GeoTiffs from numpy.array format. </sup> 
RasterSubset | <sup>These are methods for subsetting a raster to get just the cells within a vector geometry. Much of this code is derived from the python [rasterstats package](https://github.com/perrygeo/python-raster-stats) and is dependent on some utilities from that package. I think this code could be rewritten to remove the dependency on having rasterstats installed but I'm not sure when I'll get around to that. </sup> 
Sagawa2010 | <sup>In Sagawa et al. 2010 [1]\_, an alternative to Lyzenga's depth invariant index is proposed. Sagawa's reflectance index incorporates depth measurements in an attempt to correct for water column attenuation. This code is my attempt at implementing this method. </sup> 
WV2RadiometricCorrection | <sup>This module reads parameters from a DigitalGlobe supplied xml file and applies radiometric correction to WorldView-2 imagery according to the instructions found here: </sup> 
