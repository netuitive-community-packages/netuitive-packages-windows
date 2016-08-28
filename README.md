#netuitive.packages.windows 1.6.2

For detailed information on this package, please refer to the [online documentation](https://help.app.netuitive.com/Content/Misc/Datasources/Windows/new_windows_datasource.htm).

##Release History

###Version 1.6.2

* Updated package compatibilities.

###Version 1.6.1

* Don't baseline or correlate disk space metrics; these are slow-changing metrics that don't lend themselves well to such.

###Version 1.6.0

* Fixed bug where only CPU Utilization was showing up on the Utilization Reports.
* Added new computed metrics for max network utilization, max network error rate, and physical disk busy time.
* Cleaned up utilization metric tagging; all Windows elements will now have exactly 5 utilization metrics: CPU, Logical Disk (which is space used from _Total), Physical Disk (which is percent busy time from _Total), Network (which is the max utilization across all the network interfaces), and Memory.

###Version 1.5.1

* Fixed bug with the Events widget on the Element Detail Page.

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