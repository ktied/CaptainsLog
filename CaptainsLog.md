Captain's Log


# Feb 10 2021, Wednesday

Captains Log,perfect enemy of good etc etc 

## met with Shauhin
we discussed classifications using Planet, drone, sentinel, and Hyperion imagery 
Costs and Benes of doing the weighted means instead of centroids for extracting data for dipteryx points. 
- we would need to either download data or find a work around for the sampleRegions code: https://developers.google.com/earth-engine/apidocs/ee-image-sampleregions
- Previously looked at cloud cover problems and masking: https://pdfs.semanticscholar.org/aff3/3f1e89db7e4fb7297b1719c9daeb3fb33731.pdf
https://ntrs.nasa.gov/api/citations/20040031747/downloads/20040031747.pdf
https://eo-learn.readthedocs.io/en/latest/eolearn.mask.cloud_mask.html
https://github.com/ianeece/hyperion_preproc_gee_code/blob/master/atm_corr_and_cloud_masking.txt

Overall we can make a mask for BCI and I probably should 
Shauhin is going to look at the planet bands w the hyperion - and I made a list of the Hyperion bands within the ranges of the planet bands 


## met w Kristen at 4pm
We discussed the conflict paper and agreed to work on it for 3 days next week
uncertain if we will include the vervets - they're interesting from a perspective of the psychological disconnect of feeling vervets are a huge problem. OR the distance/nuisance 
Overreporting vervets since no other problems 

We discussed her graduate student (Michael) and using the biomass surveys and ndvi.


I would like to rerun my GSM classification for Nathan et al. SO I will view and open what he sent

## To Do: 
Otherwise - I emailed the ForestGeo people for seedling data access after receiving email from stri
Rerun GSM at least one of those suckers 

# February 11, 2021 Thursday

Cold today. figured out how to move this to git hopefully? Personal note: learned about a dragon audiobook the kids love here

To Do (end of week, let's be real)
1. clean files nathan sent to add to earth engine
2. write to Daisy et al? 
3. Get the Hyperion in the classifications
4. 

learned something: about saving your R studio session info like the packages etc. 


Save the session as a txt file (readable outside R)
sessioninfo::session_info() in the terminal
Save the output to a session_info_date.txt file in your github repository
Reinstall the versions you need at a later date
pander::pander(session_info_date)

Save the session as an R specific format
'> sessioninfo::save.session(file="session_info.RSession", ...)
> sessioninfo::restore.session(file="session_info.RSession", ...)'


With the Kristen: I looked at a few pappers on the biomass ~ NDVI (or any remote sensing index) 
Papers reveal this: 
[Liu (2017)](https://www.nature.com/articles/s41598-017-04038-4)
 Used MODIS NVDI to estimate aboveground biomass (AGB). They also used field spec and it did pretty well (0.63 R^2) for the steppe (less well for a meadow). Used max NDVI for the year
Serengeti Specific: [Anderson 2010](https://esajournals.onlinelibrary.wiley.com/doi/full/10.1890/09-0739.1) Additionally, because we hypothesized that vegetation biomass and greenness would be relatively stable in hotspots over different seasons, we included the ratio of wet‐season : dry‐season NDVI. Mean annual rainfall was included as a predictor to understand the influence of climate on the presence of hotspots across Serengeti (Appendix A). 