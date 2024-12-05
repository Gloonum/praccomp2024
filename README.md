# Grace's Praccomp 2024 GitHub Repo
## Fall Semester 2024
### Markdown Basics


- Bulletpoint
	- Subbulletpoint


1. Numerical list 1
2. Numerical list 2


[ ] Open Check
[x] Checked


Unformatted text


- Text formatting
	- _Spider_ -> italics
	- __Spider__ -> bold
	- __*Spider*__ -> bold and italics
	- ~Spider~ -> strikethrough



| Obs | Value |
| --- | ----- |
| A   | 0.5   |
| B   | 0.7   |


## Carrot Island Restoration Project
### __*Grace Loonam, Master's Thesis*__
### Practical Computing, Fall 2024


#### Project Background
Oyster reefs at Carrot Island in the Rachel Carson Reserve, Beaufort, North 
Carolina, were restored in 2018 with multiple restoration approaches in order to test 
various substrates and their capacity to restore oyster reef habitat compared to 
nearby natural reefs in the area. Former members of the Blakeslee and Gittman labs 
(Christopher Moore and Emory Wellman) conducted a variety of biodiversity and habitat 
surveys and analyses to quantify the immediate changes that developed at these sites 
for up to two years post-restoration by comparing the conditions at these later time 
points to what they measured prior to the implementation of the restoration plots. 

With my master's work, I am following up on their projects now that it has been five 
years since the reefs were restored, as we are interested in seeing how these 
conditions may have changed even further with additional time post restoration. For the purposes of this project, I was specifically interested in looking at two particular response variables that they also evaluated: trematode diversity in the Eastern mudsnail, (_Ilyanassa obsoleta_) and oyster density by restoration treatment. I hypothesized that trematode diversity would be higher five years post restoration at the restored sites than at their unrestored counterparts, and that oyster densities would be higher than they were at the last time they were measured (2020). In terms of restoration treatment, I predicted that the novel breakwater substrate (OysterCatcherTM, or OC) would possess greater oyster densities than the more traditional restoration approach (shell bags, or SB) as the latter technique has had mixed results in previous applications. 

The purpose of this research is to evaluate the effectiveness of these two restoration treatments in comparison to one another as well as relative to unrestored plots using multiple evaluation metrics in order to get a clear idea of how well this restoration is doing five years post restoration (additionally relative to early monitoring results). This can help inform what restoration approaches should be implemented in the future as well as where these approaches should be put in place, based off of the results of my work. I am also interested in seeing how longer term monitoring compares to initial monitoring to help guide future restoration initiatives in their implementation/follow through, as these long term results are critical to consider for the effective restoration of this vitally imporatant organism and the habitat they provide. 


#### Methods
All sites are located at Carrot Island in the Rachel Carson Reserve, Beaufort, NC. Data accessed from previous work (completed by Christopher Moore and Emory Wellman) was collected between 2017-2020, with the same methods outlined below. 
- Trematode diversity in _I. obsoleta_
    - Following up on Christopher Moore's biodiversity work, I collected 100 snails per region across seven regions of the study area (four loose cultch/unrestored reefs, three restored regions in which there are both OC and SB reefs). Snails were not always present at the study regions, but 100 snails were collected each time they were available. My sampling took place in April, June, September, and October of 2023, and June and August of 2024. 
    - The process of dissecting snails for parasites begins by measuring the length of the snail (from the bottom of the aperture to the tip of their shell). The shell is then broken with a hammer and the gonad region (located in the tip of the shell) is removed and broken up with forceps and placed under a light microscope to look for infection. If infected, the parasite species is identified and recorded, and a sample is taken to preserve for potential further use in the future.
- Oyster densities at OC and SB sites
    - As done in Emory Wellman's Master's project, to determine the average oyster density by reef type, I removed a subset from each reef and brought it back to the lab to enumerate the number of oysters on it. The removal process differed by reef type due to their different structures. For the SB reefs, one entire bag (and all attached growth) was removed from the site. For the OC reefs, a 10cm section of the reef was cut off with a hacksaw and all material attached to that section was brought back to the lab. The dimensions of each sample were recorded to obtain a volume by which the number of oysters could be divided to obtain the density values. The individual oysters on each sample type were checked to see if they were alive or dead and then measured to determine if they should be classified as an adult or juvenile.

#### Preparing the data to be put in R
- Trematode diversity data
    - To prepare the trematode diversity data for analysis and visualization as rank abundance curves, I created two data sheets for each time chunk of data (pre-restoration, 1 year post-restoration, and 5 years post-restoration): an abundance data sheet (with the parasite species abbreviations across the first row, and the numbers associated with each site in the subsequent rows, with one site per row) and an environmental data sheet (with site names in the first column to help recall the organization of the abundance data sheet, and a second column with the site type -- loose cultch or restored -- noted). 
- Oyster density data
    - To prepare the oyster density data for analysis, 
 
