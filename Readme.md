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


