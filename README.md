mobile-dashboard-dreamforce-2013
================================

Repo for Mobile Dasbhboard using D3, Google Charts and JQuery Mobile Talk

Steps to Deploy this app in your salesforce org:
************************************************

1. Deploy the Report Metadata first. My org namespace "testram" might be present in some report metadata, please remove it before deploying it. If you have namespace in your org, you have to include it in this report metadata.

2. Deploy the static resources - both JQuery Mobile and D3.js

3. I have hard coded the report id in Document.ready method line #993, change it with your actual org report id

4. Deploy visual force page and access it at your_org_instance/apex/df2013


Enjoy!