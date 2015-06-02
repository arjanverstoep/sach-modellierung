* [02-06-2015] AV:
  * SpursignalisationType: Properties instead of Components.
* [26-05-2015] AR: 
  * Removed value "Unknown" from AccumStateStates 
  * Fixed a problem referencing NE object types in NT
  * Fixed a problem with CameraType/Status/Cameratype and CameraType/Status/IsRecording 
* [26-05-2015] AR: Updated to version 0.4 of the modelling spec of AS NT reflecting the changes in version 0.92 of 11601. Translated README to english in order to not to disadvantage non-german readers...
* [22-05-2015] AV: Removed events alltogether
* [21-05-2015] AV:
  * Removed DeviceType/GeoRef 
  * Added DeviceType/Configuration/TechnologicalType
  * Added ControllerType/Status/AccumState
  * Changed Events are now modeled by using HasEventSource and GeneratesEvent instead of OptionalPlaceholder-Objects

* [20-05-2015] JT: Added VTV namespace with AsVtvType, VideoDetectionSystemType, DecoderType, CameraType
* [20-05-2015] AV: ReflexSourceType and ReflexTargetType moved from S namespace to the base namespace
* [20-04-2015] AV: Modellierung Verkehrstypicals WtaType, AmpelType
* [20-04-2015] AV: Modellierung Verkehrstypicals VlType, BzType, WwwType, SpursignalisationType
