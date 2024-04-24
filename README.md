# Lockleys Pilon Change Detection 2019 to 2023
How has the land cover change at Lockley's Pilon, Blue Mountains, NSW, following the 2019 busfires?

## Method
* Use the [DEA Maps](https://maps.dea.ga.gov.au/#share=s-02TACjEp7EBe0FBXTOYPXvGts7f) to choose two dates prior to the bushfires in November 2019 and two similar dates in late 2023. All dates should be as cloud-free as possible.
* Resample using the mean to one dataset per year.
* Classify land cover for the two dates using NDVI thresholds.
* Calculate class change statistics and plot a class change map.
