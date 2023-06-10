# ADA: Python & GBQ with Dram Shop, Part 1

This assignment is the first of two uploading Dram Shop data to GBQ. In this assignment we'll read in
a single file into a Pandas dataframe, make some modifications to it, upload it to your GBQ instance, 
and query it. 

In the second part of the assignment we'll perform some more complicated manipulations and uploads. 

# ADA: Python & GBQ with Dram Shop, Part 2

This assignment continues the work from Part 1. In that part we read in
a single file into a Pandas dataframe, made some modifications to it, uploaded it to your GBQ instance, 
and queried it. 

In this assignment we go a bit further. Here we will process all of the items files from the zip `dram-items.zip`. Unzip these into a folder in your repo. Open them one at a time and make the same changes to some of the columns as you made in part 1. Then you'll upload the data, one month's worth of data at a time, to tables in your personal project and dataset. The tables will have the form `dram_items_YYYYMM01` to take advantage of GBQ's "sharding" of the data. 
