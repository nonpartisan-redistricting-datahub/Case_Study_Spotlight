# Case Study Spotlight 

This is the code that accompanies the Case Study of our aggregation data work with Spotlight PA on the [Pennsylvania District Look Up Tool](https://www.spotlightpa.org/news/2021/12/pennsylvania-redistricting-house-senate-districts-lookup-tool/). 

You can find a write up of that Case Study on our website [redistrictingdatahub.org](https://redistrictingdatahub.org/). (Note: As of 04/28 it has not yet been posted).

## Getting Started

### Data
These datasets are necessary in order to provide both census and voter file data for state legislative and congressional districts. They are available for all 50 states.

Pennsylvania data is used in the code: 

* [Pennsylvania block PL 94-171 2020](https://redistrictingdatahub.org/dataset/pennsylvania-block-pl-94171-2020/)
* * [Pennsylvania block PL 94-171 2020](https://redistrictingdatahub.org/dataset/pennsylvania-block-pl-94171-2020/)
* [Pennsylvania Block PL 94-171 2020 Official (Prison Adjusted)](https://redistrictingdatahub.org/dataset/pennsylvania-block-pl-94-171-2020-official-prison-adjusted/)
* [2021 Pennsylvania L2 Voter File Aggregated to 2020 Census Blocks](https://redistrictingdatahub.org/dataset/2021-pennsylvania-l2-voter-file-aggregated-to-2020-census-blocks/)
* [Pennsylvania Current Maps 2022](https://davesredistricting.org/maps#state::PA)


#### PL 94-171
The PL 94-171 data at the “uncorrected” 2020 census block level in csv format. This contains data on the total population, as well as the population by race and ethnicity (used for congressional redistricting). It also contains block assignments to the “old” districts in effect in 2020.

To download the data, [create a free account](https://redistrictingdatahub.org/my-account/register/), go to [download data](https://redistrictingdatahub.org/data/download-data/#state-menu), select a state and filter by type of data: *PL 94-171*

#### Offical adjusted data
Shapefiles of the official adjusted PL 94-171 dataset at the 2020 census block level. This contains data on the total adjusted population, as well as the adjusted population by race and ethnicity. 

To find out if your state uses adjusted data reference [State and Adjustment Wording](https://redistrictingdatahub.org/data/about-our-data/pl-94171-dataset/states-and-modification-wording/) and [States that Adjust the Census Data for Redistricting](https://redistrictingdatahub.org/data/ongoing-data-projects/states-that-adjust-the-census-data-for-redistricting/)

To download the data, [create a free account](https://redistrictingdatahub.org/my-account/register/), go to [download data](https://redistrictingdatahub.org/data/download-data/#state-menu), select a state and type name: Official

#### Voter File
2021 L2 voter file data aggregated to the 2020 census block level in csv format. This contains data on voter registration totals by party. 

To download the data, [create a free account](https://redistrictingdatahub.org/my-account/register/), go to [download data](https://redistrictingdatahub.org/data/download-data/#state-menu), select a state and filter by source: *L2*

#### Current Maps 2022
Block assignment files for the new House, Senate, and US Congressional districts. 
Navigate to the current maps for the state on [DRA](https://davesredistricting.org/maps#), and open up each of the three official maps. On each map, click the arrow pointing to the upper-right, check "Export alternate census blocks" and export the block assignment files.

#### Folder Structure
After making the name changes to the block-assignment files (being sure to rename the right files), you should have a "raw-from-source" folder with the following files / folders:

raw-from-source/
* block-assignments-pa-cong.csv
* block-assignments-pa-sldl.csv
* block-assignments-pa-sldu.csv
* PA_L2_2020BlockAgg
* pa_pl2020_b
* pa_pl2020_b_csv
* pa_pl2020_block_noreallocation
* pa_pl2020_official_blocks

## Questions

Send a message to the Redistricting Data Hub [Help Desk](https://redistrictingdatahub.org/tools/support/) at help@redistrictingdatahub.org with questions about this code, data and the redistricting process!

## Built With

We are used Python and Jupyter Notebook to show how we processed the data. We like Jupyter Notebook because it provides a very easy way to visualize the data as you are working. 

* [Python](https://www.python.org/)
* [Jupyter Notebook](https://jupyter.org/)

## Read More
For more information about how our Help Desk used this code to create a tool that compares Pennsylvania's new and old districts, read the case study. (Note: As of 04/28 it has not yet been posted).

To learn more about our data, read articles available about [each dataset](https://redistrictingdatahub.org/data/about-our-data/) and [frequently asked questions](https://redistrictingdatahub.org/tools/support/data-faq/) about our data  



