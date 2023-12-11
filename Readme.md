<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/128571617/22.2.2%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/T200978)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
<!-- default badges end -->

# Map for WPF - How to Implement Custom Map Projection


This example describes how to implement custom map projection (the [Hammer-Aitoff])(http://paulbourke.net/geometry/transformationprojection/) projection). 

[Map](./image/Map.png)

To create a custom projection, inherit the [ProjectionBase](https://docs.devexpress.com/WPF/DevExpress.Xpf.Map.ProjectionBase) class and override the following methods of the base class:

* [GeoPointToMapUnit](https://docs.devexpress.com/WPF/DevExpress.Xpf.Map.ProjectionBase.GeoPointToMapUnit(DevExpress.Xpf.Map.GeoPoint))
* [MapUnitToGeoPoint](https://docs.devexpress.com/WPF/DevExpress.Xpf.Map.ProjectionBase.MapUnitToGeoPoint(DevExpress.Xpf.Map.MapUnit))
* [GeoToKilometersSize](https://docs.devexpress.com/WPF/DevExpress.Xpf.Map.ProjectionBase.GeoToKilometersSize(DevExpress.Xpf.Map.GeoPoint-System.Windows.Size))
* [KilometersToGeoSize](https://docs.devexpress.com/WPF/DevExpress.Xpf.Map.ProjectionBase.KilometersToGeoSize(DevExpress.Xpf.Map.GeoPoint-System.Windows.Size))

## Files to Review

* [HammerAitoffProjection.cs](./CS/CustomProjection/HammerAitoffProjection.cs) (VB: [HammerAitoffProjection.vb](./VB/CustomProjection/HammerAitoffProjection.vb))
* [MainWindow.xaml](./CS/CustomProjection/MainWindow.xaml) (VB: [MainWindow.xaml](./VB/CustomProjection/MainWindow.xaml))

## Documentation

* [Geographical Projections](https://docs.devexpress.com/WPF/14750/controls-and-libraries/map-control/coordinate-systems/geographical-projections)