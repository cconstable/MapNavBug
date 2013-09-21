MapNavBug
=========

> Potential iOS 7 Bug

It seems that when a `MKMapView` is added to a view anywhere inside a `UINavigationController` the nav bar will lose it's `barTintColor` and it will never be able to be set again.

This happens on devices running iOS 7.0 and does not happen in the simulator. The project was built with Xcode 5 GM seed.

Run the Xcode project and follow the instructions in the app.


