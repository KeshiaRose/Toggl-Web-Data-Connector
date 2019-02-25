# Toggl Web Data Connector
This Tableau Web Data Connector pulls in your task tracking data from the Detail Reports view on toggl.com

# How to Connect
To connect to your time tracking data create a new **Web Data Connector** data connection and enter the following url:

**2019.1 and later**
```
https://keshiarose.github.io/Toggl-Web-Data-Connector/togglwdc_19.1.html
```
**2018.3 and earlier**
```
https://keshiarose.github.io/Toggl-Web-Data-Connector/togglwdc.html
```

## Inputs Required
**Email:** Please enter your email to receive any errors from Toggl.

**Workspace ID:** Use the number shown in the url on the "Workspace Settings" page

>For example: https:[]()//toggl.[]()com/app/workspaces/**999999**/settings

**API Token:** This can be found at the bottom of your "[My Profile](https://toggl.com/app/profile)" page

**Start & End Dates:** The time frame you would like to pull data for. Check **"Always today"** to always use the current day for refreshes.\
_Note: Toggl API has a maximum of a year time frame_
