---
title: Release Notes for 2020.11.0
seo-title: AEM Cloud Manager Release Notes for 2020.11.0
description: Follow this page to get information for Cloud Manager Release 2020.11.0
seo-description: Follow this page to get information for AEM Cloud Manager Release 2020.11.0
---
# Release Notes for 2020.11.0 {#release-notes-for}

The following section outlines the general Release Notes for [!UICONTROL Cloud Manager] Release 2020.11.0.

## Release Date {#release-date}

The Release Date for [!UICONTROL Cloud Manager] Version 2020.11.0 is November 12, 2020.

## What's New {#whats-new}

* The **Learn** tab in Cloud Manager is refreshed with new images in the UI.

## Bug Fixes {#bug-fixes}

* Certain customer-caused deployment errors will now be surfaced explicitly in the deployment logs.

* The loading of dependencies done prior to build execution required downloading a Maven plugin. 

* The link from the Cloud Manager footer to select a language will now navigate to the correct location.

* Sometimes during the code scanning, the SonarQube process would not start. This will now be auto-detected and a restart attempted.

* During the site crawling process used in performance testing, requests which time out in the first three levels of depth traversal will be automatically retried.