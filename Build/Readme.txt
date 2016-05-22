- Build folder for native extension - 

!Notice!
Because Github does not allow files over 25MB, the EstimoteSDK file in the EstimoteSDK.Framework folder is zipped, 
and will have to be unzipped before building.

Build command:
adt -package -target ane LocationExtension.ane extension.xml -swc LocationExtension.swc -platform Android-ARM -C Android-ARM . -platform iPhone-ARM -platformoptions platform.xml EstimoteSDK.Framework -C iPhone-ARM .

Make sure to set the global path for adt to the adt executable in your Air SDK.
