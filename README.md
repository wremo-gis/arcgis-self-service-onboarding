# ArcGIS Self-Service Onboarding

# Overview

This repository supports a **Azure Static Web App** that provides a **self-service interface** for users to onboard themselves into **ArcGIS Online** groups.

The app helps reduce reliance on **ArcGIS Administrators** and **Group Managers** in time-critical situations. By automating user onboarding, administrators can focus on higher-value activities instead of manually creating users and managing group memberships.

The app allows users to:

1. **Scan a QR code** or navigate to a predefined URL  
2. **Sign in** with their own ArcGIS credentials or create a new account in the deploying organisation
3. **Be automatically added** to a specified group, granting them the required permissions  
4. **Be redirected** to a predefined app or URL upon completion

Multiple QR codes can be active at once, allowing the app owner to distribute different URLs or QR codes to different user groups, based on their access needs.

The sign-in process works whether the user belongs to:
- The **same ArcGIS Online organisation** as the deployed app, or  
- A **different ArcGIS Online organisation**

### For setting up your own repository and app, please see the hansonwj's [arcgis-self-service-onboarding](https://github.com/hansonwj/arcgis-self-service-onboarding) repository for instructions.
