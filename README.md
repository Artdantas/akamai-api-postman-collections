# akamai-api-postman-collections
This repository contains Akamai API Postman Collections and Environments.

You can download both the Postman Collection and Envrionment and import these directly into Postman. Currently contains Akamai Application Security including the Application Security API, Network Lists API and SiteShield API to manage your Akamai Security solutions.

Video Tutorial:
https://www.youtube.com/watch?v=NtJ_ZdN0T7I
Note: uses an older version of Postman, minor UI changes in the latest 8.5.0 release.

Instructions to setup:

1) Install Postman
2) Download the Postman Collection and Postman Environment files for your use-case (2 available right now, Application Security and Live Video Workflow)
3) Launch Postman
4) Click on File > Import (or the Import button) and add your Postman Collection and Environment files.
5) Click Import
6) Select your Akamai Environment (top-right)
7) Add your Akamai API EdgeGrid credentials as the right Variable Values (host, client token, client secret and access token). 
8) Run your first Akamai API request. Recommended is to run List Contracts and Groups in the AppSec > Security Configurations folder. This should return a 200 OK with your Contract ID and Group IDs. If you receive a 401 Error, your Akamai EdgeGrid credentials are not working properly or misconfigured. If you receive a 403 Error, your Akamai API client requires read-write on the AppSec API.

Video Tutorial on how to create an Akamai API client:
https://www.youtube.com/watch?v=qT0QK3nnMPM&ab_channel=AkamaiDeveloper

For questions, please contact me.
