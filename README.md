# kumar-molecular-mechanism

## This is the code used to analyze the data presented in S. Kumar, A. K. Sharma, and A. M. Leifer, titled "An inhibitory acetylcholine receptor gates context dependent mechanosensory processing in *C. elegans*". 

This study uses a targeted optogenetic delivery system published previously. More details can be found at the following publications:
1) Liu et al., *PLoS Biology* 2022 (https://doi.org/10.1371/journal.pbio.3001524).
2) Kumar et al., *PLoS Biology* 2023 (https://doi.org/10.1371/journal.pbio.3002280).

### Code for LabVIEW 
Requirements:
 - LabVIEW 2019 64-bit Windows
 - LabVIEW package manager
 - LabVIEW OpenG add-on
 - HDF5 v1.8.18+ (latest v1.8 but not v1.10)
 - h5labview

To run the real-time LabVIEW code, open the LabVIEW project at `\LabviewVIs\ProjectAPI.lvproj` and then select the appropriate experimental protocol vi. For example, open loop stimulation is done using `RunFullWormRails.vi`, closed-loop stimulation on turns was done using `RunRailsTriggeredByTurning.vi`. 