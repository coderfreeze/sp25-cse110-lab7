# Vijay Sinha  

1) We would put our automated tests within a Github action that runs whenever code is pushed.  
Since a Github action is automatic, this ensures that we cannot push buggy code to the repo and it gets fixed as we develop the software.  
It also helps in maintaining big projects easier because it checks the code on every push automatically.   

2) No. Jest-Pupeteer is used for front-end testing.  

3) Navigation does a full page load. Lighthouse will navigate to the URL, collects performance data, and then runs the full tests on a fresh reload.  
Snapshot mode does not reload or navigate. It tests the page in its current state.  
Since there is no reload, performance metrics like FCP or LCP are not tested.  

4) To improve the CSE 110 shop site there are three things we can do:
1. Properly size images (Potential savings of 798 KiB). 
2. Reduce unused JavaScript (Potential savings of 206 KiB).
3. Preload Largest Contentful Paint image.

