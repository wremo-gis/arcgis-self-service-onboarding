# ArcGIS Self-Service Onboarding

### Overview

This repository hosts the Wellington Region Emergency Management Office (WREMO) deployment of the ArcGIS Self-Service Onboarding app. It supports an **Azure Static Web App** that provides a **self-service
interface** for users to onboard themselves into **ArcGIS Online** groups, and is a fork of [hansonwj/arcgis-self-service-onboarding](https://github.com/hansonwj/arcgis-self-service-onboarding).

The app reduces reliance on ArcGIS Administrators and Group Managers in time-critical situations, such as emergency responses. By automating user onboarding, administrators can focus on higher-value tasks instead of manually creating users and managing group memberships.

Users can:
 
1. **Scan a QR code** or follow a predefined link
2. **Sign in** with their existing ArcGIS account, or create a new account in the WREMO organisation (if enabled)
3. **Be added automatically** to a specified group, giving them the access they need
4. **Be redirected** to a predefined app or page once complete
 
Multiple QR codes can be active at once, so different groups of users can be given different access. Sign-in works for users from the WREMO ArcGIS Online organisation and from other ArcGIS Online organisations.

The sign-in process works whether the user belongs to:
- The **same ArcGIS Online organisation** as the deployed app, or  
- A **different ArcGIS Online organisation**


### Setting up your own deployment

This fork contains WREMO-specific changes and isn't intended as a template. To deploy the app for your own organisation, please follow the setup instructions in the **[original repository](https://github.com/hansonwj/arcgis-self-service-onboarding)**.


### Changes in this fork

- WREMO and Civil Defence Emergency Management branding
- Updated page titles, wording and sign-up page styling
- Deployment workflow updated for WREMO's Azure Static Web App


### Security
 
This repository is public because it is a fork of a public repository. No credentials, passwords or deployment tokens are stored in this repository. Sensitive configuration is held in Azure environment variables and GitHub Actions secrets. Onboarding links and QR codes are distributed separately and are not published here.


### Support
 
This repository is maintained by WREMO for our own use, and we're unable to provide support for other deployments. For questions about the app itself, please raise an issue on the [original repository](https://github.com/hansonwj/arcgis-self-service-onboarding).


### Acknowledgements
 
Ngā mihi nui to [hansonwjithub.com/hansonwj for building and sharing the original app.
 
### Licence
 
MIT – see LICENSE. The original copyright notice is retained.
