![Working](https://img.shields.io/badge/Status-Working-brightgreen)

# Toggl Track Web Data Connector
This is a [Tableau Web Data Connector](https://tableau.github.io/webdataconnector/docs/wdc_use_in_tableau.html) that pulls in your task tracking data from the Detailed Report view on [Toggl Track](https://toggl.com/track/)

## How to Connect
To connect to your time tracking data create a new Web Data Connector data connection and enter the following url:

#### Tableau Desktop 2019.4+

```
https://keshiarose.github.io/Toggl-Web-Data-Connector/togglwdc_19.4.html
```
#### Older versions

```
https://keshiarose.github.io/Toggl-Web-Data-Connector/togglwdc.html
```

## Inputs Required
**Email:** Please enter your email to receive any errors from Toggl.

**Workspace ID:** Use the number shown in the url on the "[Reports](https://track.toggl.com/reports/detailed)" page

>For example: https:<span></span>//track.toggl.com/reports/detailed/**999999**

**API Token:** This can be found at the bottom of your "[My Profile](https://toggl.com/app/profile)" page

**Start & End Dates:** The time frame you would like to pull data for. Check **"Always today"** to always use the current day for refreshes.


_Note: The Toggl API has a maximum time frame of one year._
