# Training Exercise GQI Ad Hoc Data Source Service Alarms

## Description

The goal of this exercise is to create a GQI (Generic Query Interface) ad hoc data source which can be used to show the real-time alarm state of services, filterable by view ID.

The ad hoc data source must:
* Read info from DMS
* Support real-time updates
* Have caching
* Have sort optimization

The ad hoc data source must have these input arguments:
* View ID (integer, default: 0)

The ad hoc data source returns a list of services with these fields:
* Name
* Alarm State

![demo](https://github.com/user-attachments/assets/669b2533-0b92-42ad-80d0-e916755621db)
