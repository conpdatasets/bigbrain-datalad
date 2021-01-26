# BigBrain dataset

## BigBrain

The BigBrain is the brain of a 65 years old man with no neurological or psychiatric
diseases in clinical records at time of death. The brain was embedded in parafin and
sectioned in 7404 coronal histological sections (20 microns), stained for cell bodies.
The BigBrain is the digitized reconstruction of the hi-res histological sections 
(20 microns isotropic).

## Dataset content

This dataset contains the 3D blocks and 3D volumes of the BigBrain release 2015
published in the [BigBrain Project website](https://bigbrainproject.org).

The 3D 40 um blocks of the BigBrain are 5x5x5 blocks for a total of 125 blocks
representing the BigBrain with small overlap at block boundaries.

The 3D histological volumes (Merker stain) are also available at different 
isotropic resolutions (100, 200, 300, 400 microns) in MNI space and 
histological space, with and without optical balancing. The MNI ICBM152 
2009b symmetric model used for the stereotaxic registration of the BigBrain 
can be found at http://www.bic.mni.mcgill.ca/ServicesAtlases/ICBM152NLin2009.


All files are available in MINC and NIfTI formats except for the 100um volumes 
since they are too large to convert to NIfTI using the current version of our
converter.

## Reference and more information

The BigBrain dataset is the result of a collaborative effort between the
teams of Dr. Katrin Amunts and Dr. Karl Zilles (Forschungszentrum Jülich)
and Dr. Alan Evans (Montreal Neurological Institute).

Amunts, K. et al.: "BigBrain: An Ultrahigh-Resolution 3D Human
Brain Model", Science (2013) 340 no. 6139 1472-1475, June 2013
[https://www.sciencemag.org/content/340/6139/1472.abstract](https://www.sciencemag.org/content/340/6139/1472.abstract)

For more information please visit the [BigBrain Project website](https://bigbrainproject.org).