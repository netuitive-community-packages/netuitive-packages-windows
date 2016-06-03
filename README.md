#netuitive.packages.windows 1.5.0

For detailed information on this package, please refer to the [online documentation](https://help.app.netuitive.com/Content/Misc/Datasources/Windows/new_windows_datasource.htm).

##Release History

###Version 1.5.0

* Fixed bug with the Events widget on the Element Detail Page.
* Added new computed metric for normalizing run queue size (aka processor queue length) across CPUs.
* Adjusted the Heavy CPU Usage policy to look at the normalized run queue size.
* Added computed metrics for disk utilization on individual logical disks.

###Version 1.4.1

* Fixed bug with "Windows - Elevated Event Count"; need to look only for upper deviations.

###Version 1.4.0

* Added configuration for new metric windows_events.
* Added new policy "Windows - Elevated Event Count".

###Version 1.3.0

* Added metric units.
* Added memory and disk utilization metrics.

###Version 1.2.0

* Added Windows-specific element detail page.

###Version 1.1.0

* Added summary dashboard.
* Bug fix: the wrong configuration for computed metrics had been included in v1.0

###Version 1.0.0

* Initial production release of the package for monitoring Windows OS resources.