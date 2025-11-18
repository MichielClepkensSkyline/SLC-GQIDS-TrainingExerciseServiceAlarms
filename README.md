# Training Exercise GQI Ad Hoc Data Source Service Alarms

## Description

The goal of this exercise is to create a GQI (Generic Query Interface) ad hoc data source which can be used to show the real-time alarm state of services, filterable by view ID.

The ad hoc data source must contain the following features. Please add them in this order:

1. Read info from a DMS.
2. Maintain a cache of server alarm states that is continuously kept up-to-date via events. This way, the service alarm states can be used by multiple queries without needing to retrieve the initial data multiple times.

Based on the input argument View ID (integer, default: 0), the ad hoc data source should return a list of available services with the fields:
* Name
* Alarm State

![demo](https://github.com/user-attachments/assets/669b2533-0b92-42ad-80d0-e916755621db)
