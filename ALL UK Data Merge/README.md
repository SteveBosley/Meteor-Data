Hampshire Astronomical Group are active members of both the UK Meteor networks : UKMON and NEMETODE
As such they have access to and can analyse the data captured by both networks.

So, the scripts in this folder were produced to gather and merge this data so that UFO Orbit can be
run for All the UK - taking advantage of the considerable overlap of coverage to improve the quality of observations.
There is another neighbour network - BOAM in France - from which data is available intermittently. Scripts will be 
written to handle this when access is regularised.

In addition, to the merge process, there are scripts to interrogate each network by station so that we can understand
how up-to-date the data is and whether or not we should proceed with orbit analysis.

The Read_NEMETODE, Read_UKMON_Old and Read_UKMON_AWS scripts can be run in any order, but must be run before 
Deduplicate_ALL_UK AND on the same day. The submissions scripts should be run afterwards as they report on the number of 
clips available per month per station.

Note. Once Read_UKMON_Old.R has been run once, there is no need to rerun it as that data is dormant.
