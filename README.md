# Adobe Campaign Web Tracking
Tracking a recipients clicks within the web page of a webapp and write to a table.

## Summary

Due to some issues with Adobe Campaigns out-of-the box Web Tracking. This project has been created to track a single recipients journey through the Adobe Campaign web application, based on their encrypted Recipient ID. It makes the following assumptions:

- There will be no anonymous users coming through. This script will only track users that have received emails via Adobe Campaign, and all data is maintained within the Adobe Campaign ecosystem.
- The user has javascript enabled
- All data handling will be done on the Adobe Campaign database via built in Adobe Campaign data handling.

## Initial Build

The initial build will be done via node.js on my local machine to handle tracking and session cookies, and will later be updated to reflect Adobe Campaign's functionality.