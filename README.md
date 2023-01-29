# dcs_missions
Collection of missions for DCS

# How to contribute
DCS stores its missions in .miz files which are zip files containing all the mission data (lua scripts, images, sound files, kneeboards,...).


## Add a new mission to the repository
To upload the missions here in this repository do the following steps:
* make sure you know either git or just install the github application and clone this repository
* edit your mission in DCS as usual
* locate the mission .miz file: ..\Saved Games\DCS.openbeta\Missions
* use 7zip or equivalent to unzip the miz file into the git repository which you cloned previously (follow the existing naming schema)

## Editing or Updating a mission
To edit an existing mission there are two ways:
1. Download the latest release and then edit the miz file in DCS.
2. Manual zip the mission in the repository to a miz file (e.g. with 7Zip). Take care to only zip the contents inside a mission folder and not the folder itself otherwise it will not load in DCS

After editing follow the steps in _Add a new mission to the repository_
