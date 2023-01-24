# dcs_missions
Collection of missions for DCS

# How to contribute
DCS stores its missions in .miz files which are zip files containing all the mission data (lua scripts, images, sound files, kneeboards,...).


To upload the missions here in this repository do the following steps:
* make sure you know either git or just install the github application and clone this repository
* edit your mission in DCS as usual
* locate the mission .miz file: ..\Saved Games\DCS.openbeta\Missions
* use 7zip or equivalent to unzip the miz file into the git repository which you cloned previously (follow the existing naming schema)

If you want to edit an existing mission:
* locate the mission directory and zip the contents of the directory (not the directory) to a file.
* make sure the file extention is .miz
* load this mission file in the mission editor of DCS
* if it doesn't load make sure you didn't pack the directory!

To upload changes follow the same steps by unpacking the content into the repository and then do a new commit.
t