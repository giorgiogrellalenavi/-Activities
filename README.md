# Activities stored in TCX files

The root element is a **TrainingCenterDatabase** element, which contains an **Activities** element. 

That element has one or more **Activity** elements, each describing an activity.

As well as some metadata, the Activity element contains a number of **Lap** elements. 

Each Lap element contains some metadata about the relevant lap (or split), 

as well as a **Track** element which contains many **Trackpoint** elements, 

each representing a data point that was reported by the device, 

and which may (or may not) contain, among other things, **time**, **latitude** and **longitude**, **altitude**, **heart rate**, **cadence**, **distance** and **speed** data. 

![This is an image](https://github.com/giorgiogrellalenavi/Activities/blob/c82c15d02e62a893e4074f230caae70925b38ec6/Data/Images/hierarchy_TCX_files.JPG)
