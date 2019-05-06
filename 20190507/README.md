## 2019-05-07. Python Performance Evaluation Tools to Prepare a Traditional Regional Seismic Network for Earthquake Early Warning

**[Jon Connolly](https://github.com/joncon), Pacific Northwest Seismic Network**


The [Pacific Northwest Seismic Network (PNSN)](https://pnsn.org/) is a Regional Seismic Network (RSN) responsible for monitoring 
all seismic activity in Washington and Oregon State. ShakeAlert Earthquake Early Warning (EEW) will provide end users and 
connected devices with seconds to minutes of warning before the strongest shaking starts. To accomplish this, the PNSN, 
together with the USGS and university partners at Caltech, Berkeley, and University of Oregon are adding and upgrading hundreds 
of stations along the west coast. This buildout is stretching the limits of traditional RSN State of Health (SOH) monitoring and 
requiring RSNs to move from a station-by-station analysis to a west coast wide, inter-RSN network performance assessment. 
I will demonstrate [magD](https://github.com/pnsn/magD), a Python package developed by the PNSN to analyze network noise, station density, warning times and station geometry, and give a sneak peak into a Django app called SQUAC, currently under development, which will allow an end user to define metrics, station groupings, thresholds and alerts.

Relevant resources:
- [magD GitHub repository](https://github.com/pnsn/magD)
- [https://github.com/pnsn/magd_client](https://github.com/pnsn/magd_client): A simple magD client with notebooks
