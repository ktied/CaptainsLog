Captain's Log


# February 10 2021, Wednesday

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
2. ~~write to Daisy et al?~~
3. Get the Hyperion in the classifications
4. https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet

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


https://link.springer.com/article/10.1007/s00300-014-1472-3 MODIS NDVI grazing 

links: https://serengetidata.weebly.com/vegetation.html

Simple dee dimple: [Schucknecht 2017](https://www.mdpi.com/2072-4292/9/5/463/htm) The phenology-based seasonal cumulative Normalised Difference Vegetation Index (cNDVI), computed from 10-day image composites of the Moderate-resolution Imaging Spectroradiometer (MODIS) NDVI data, was used as proxy for biomass production. A linear regression model was fitted with multi-annual field measurements of herbaceous biomass at the end of the growing season.
- ed. note: this is v similar to crop stuff 

- moved this to a google doc bc I think it better fits the format: [Biomass ndvi](https://docs.google.com/spreadsheets/d/10Ho6c1rY-XsFrJW0IkglQLQB5aOJko5kxVEMVrpXAL8/edit#gid=0)

# February 12, 2021 Friday
CL: cold again today. Kinderhaus drop off was a beast on the fingers 

Morning spent doing what I don't know. Got an email 

## Goals/ To Do: 
1. clean files nathan sent to add to earth engine
2. ~~Forward email from ForestGeo to Chase~~
3. ~~Email Jordan back~~
4. After ee running bb lookover the doc then either send it to Jordan again ORRRRRR set up the meeting with him 


## Meeting with Shauhin and Andreas 
hopefully will say - hyperion added 
we should try an all the stuff allll the time thing aka for future me reading this, make a classification using bands from multiple satellites 
the spreadsheet I'm using: https://docs.google.com/spreadsheets/d/1EeocgJVlpney-lPe7Kvb2k_CQ2UTCXWxkKGaVKaOM4U/edit#gid=1745530911

# February 15, 2021 Monday

okay this is a day later but here's what I did! 

- struggled with the landcover type designations for the Mara survey 
- conversed via email with Nathan about the LC type 
- emailed w Jordan and Robert
- R says ok to the denominator thing 
- harassed S over whatsapp about plotting vs bayes 

# February 16, 2021 Tuesday

Captain Log: I definitely worked yesterday 

Today is a different day bc its Tuesday, Here we go 

## To Do 
1. Prep for Thurs meeting 

 + Replace figures 
 + just make some judgement calls on the costs - whatever 
 + clean up text for readability 
 + clean text for changes from rmse to accuracy and gain - this is a big ass project 
 + tackle that soil moisture paragraph that you hate
 + decide on a comprehensive name for the transect measures - is it cob weight? idk lol (who am i)
 + add the figure comparing all 8 measures
 + add the table that R is always mad about the big one for the SI
2. ~~Rerun cloud mask and mosaic for the planet images for S full scape hyperion comparison~~
3. emails that have come to me. 
4. email Nathan et al. re GSM - I don't think we need to redo everything due to the grass/herbaceous cover situation. that shit is ridic/ 
5. order laptop w Instin

## this week in general 

I'm sure I said I would look at the drone imagery by Andreas so I should do that - plan to on Fri maybe or move meeting to diff day 

Talking to Daisy at some point I don't remember when

I feel like we are generally always a heartbeat away from Tobi illness so get on shit 

B laptop just died, so I should really get my shit together in getting a work one too
