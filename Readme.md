<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/128571617/21.1.5%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/T200978)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
[![](https://img.shields.io/badge/💬_Leave_Feedback-feecdd?style=flat-square)](#does-this-example-address-your-development-requirementsobjectives)
<!-- default badges end -->
<!-- default file list -->
*Files to look at*:

* [HammerAitoffProjection.cs](./CS/CustomProjection/HammerAitoffProjection.cs) (VB: [HammerAitoffProjection.vb](./VB/CustomProjection/HammerAitoffProjection.vb))
* [MainWindow.xaml](./CS/CustomProjection/MainWindow.xaml) (VB: [MainWindow.xaml](./VB/CustomProjection/MainWindow.xaml))
<!-- default file list end -->
# How to implement custom map projection


This example describes how to implement custom map projection. In this example the <a href="http://paulbourke.net/geometry/transformationprojection/">Hammer-Aitoff</a> projection was implemented.


<h3>Description</h3>

To&nbsp;create a custom projection, inherit the&nbsp;<strong>ProjectionBase</strong>&nbsp;class and override the following methods of the base class.<br />- <strong>GeoPointToMapUnit</strong>&nbsp;- converts geographic points to internal map units.<br />-&nbsp;<strong>MapUnitToGeoPoint</strong> - converts internal map units to geographic points.<br />- <strong>GeoToKilometersSize</strong>&nbsp;- converts sizes in geographic units into the corresponding size&nbsp;in kilometers.<br />- <strong>KilometersToGeoSize</strong>&nbsp;- converts sizes in kilometers into the corresponding size&nbsp;in geographical units.

<br/>


<!-- feedback -->
## Does this example address your development requirements/objectives?

[<img src="https://www.devexpress.com/support/examples/i/yes-button.svg"/>](https://www.devexpress.com/support/examples/survey.xml?utm_source=github&utm_campaign=wpf-map_implement-custom-map-projection&~~~was_helpful=yes) [<img src="https://www.devexpress.com/support/examples/i/no-button.svg"/>](https://www.devexpress.com/support/examples/survey.xml?utm_source=github&utm_campaign=wpf-map_implement-custom-map-projection&~~~was_helpful=no)

(you will be redirected to DevExpress.com to submit your response)
<!-- feedback end -->
