The group is progressing smoothly. In the [NGC6819 repository](https://github.com/GosnellResearchGroupSummer2018/NGC6819), Thom and Rory have made source detection codes that are fairly good at detecting the stars in an image. They each detect more sources than are there, but it's easy to tell which sources are fakes and throw those out. Moreover, we have functional aperture photometry codes as well for removing background noise. Finally, Thom has successfully been able to estimate the Poisson uncertainty of our photon count. Marta has also made great progress with astrometry. She is able to find the WCS coordinates of an image using index files to within 5-10 milliarcseconds, which is just the accuracy we're looking for. 

We are starting to get close to the point in this project where we begin bringing the two halves of the project together. All three members are independently able to detect sources in an image, and the photometry team can take that data and estimate the sources total flux and associated Poisson uncertainty, while the astrometry specialist can accurately places those sources in the sky. Both departments have one more task before the group can come together to make conclusions. In the astrometry department, we need to overlay the fields that contain the x-ray sources we're studying so we can determine which sources in different bands are actually the same source. The photometry department will then need to use that information to generate color magnitude diagrams. We will likely end up comparing the difference in magnitude of different bands using almost every combination of two bands we have. We have data from HST in UVBRI bands, from Diafi in RGBHα bands, and from Chandra in x-ray. 

## Selected Results
[Thom's source detection code:] (https://github.com/GosnellResearchGroupSummer2018/NGC6819/blob/master/photometry%20codes/aperture_photometry.py)   
Outputs:  
![sources]({{ https://gosnellresearchgroupsummer2018.github.io }}/images/sources.png)
![sources_2]({{ https://gosnellresearchgroupsummer2018.github.io }}/images/sources_2.png)


Rory's Codes:  
- [Background Detection](https://github.com/GosnellResearchGroupSummer2018/NGC6819/blob/master/Rory's%20Codes/sambd.py)   
- [Source Detection](https://github.com/GosnellResearchGroupSummer2018/NGC6819/blob/master/Rory's%20Codes/samsd.py)   
Outputs:    
![sourcefigf4t200v10]({{ https://gosnellresearchgroupsummer2018.github.io }}/images/sourcefigf4t200v10.png)

# Conclusion
We have made very nice progress this week, and it seems like we are getting close to finishing the preparation part of this endeavor.
