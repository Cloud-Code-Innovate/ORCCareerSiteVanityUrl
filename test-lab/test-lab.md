# Test the Vanity URL

## Introduction

- This lab will guide you to test the Setup for the HCM Vanity.

Estimated Time: 5 minutes

### Objectives

- Test the setup that was done for the vanity URL

## **Step 1:** Test the Vanity URL in the browser

1. On your desktop, navigate to the browser of your choice.

2. Enter the vanity URL in the browser address bar. (ex: https://yourvanityurl.com)

3. The page should load the HCM Job Page with the hostname being the vanity url.

 ![](images/VanityURLLandingPage.png " ")

## **Step 2:** Verify the loaded HCM site

1. Move around the site by clicking the buttons to load popups, navigate to links and try searching for jobs. If all of that works then the setup is succesful.

 ![](images/VanityURLOtherPages1.png " ")
  ![](images/VanityURLOtherPages2.png " ")
   ![](images/VanityURLOtherPages3.png " ")

2. Another way to verify is via the source code of the index.html file that gets displayed when you hit the url. If you see the following variables in the source code then the setup is done right.

```
vanityBaseUrl="yourvanityurl" 
window.VanityUrlEnabled=true
window.VanityUrlUseReverseProxy=true
``` 
   ![](images/VanityURLCodeValidation.png " ")
   
## **Summary**

Congratulations, You have successfully setup the Vanity URL solution for your HCM instance.

## Acknowledgements
 - **Author** -  Saipriya Thirvakadu | Cloud Engineer 
 - **Contributors** - Aditya Trivedi | Cloud Engineer
 - **Last Updated By/Date** - Saipriya Thirvakadu, Cloud Engineer, June 2024
