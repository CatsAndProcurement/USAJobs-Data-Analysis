# USAJobs-Data-Analysis
Demonstration of how to use Python to pull job posting data off the USAJobs.gov web API

The purpose of this script is to show people how to use Python to access data on jobs posted to USAJobs.gov, the U.S. government's central hiring website for most non-political positions.

USAJobs.gov is run by the Office of Personnel Management (OPM), which is basically the U.S. government's HR department.

To use this script (or to extract bulk data from USAJobs.gov in general) you will need an application program interface (API) key. You can request an API key from OPM via the following link:
https://developer.usajobs.gov/APIRequest/Index

After you have your API key, to run this script you'll need to enter it (along with the email you used to obtain it) in the sections below with the variables labeled 'API_email' and 'API_key'.

This script has a few lines of code that create the URL for an API call requesting data on contracting jobs (USAJobs occupational code '1102') posted by the General Services Administration (GSA, USAJobs organization code 'GS'). You can replace these occupational and organization codes with any others that you prefer. See links below for raw data with occupation and organization codes:
https://data.usajobs.gov/api/codelist/occupationalseries
https://data.usajobs.gov/api/codelist/agencysubelements
