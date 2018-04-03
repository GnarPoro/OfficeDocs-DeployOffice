---
title: "Telemetry Dashboard worksheet reference"
ms.author: danbrown
author: DHB-MSFT
manager: laurawi
ms.date: 12/20/2016
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Normal
ms.collection: Ent_O365
ms.custom: Ent_Office_Compat
ms.assetid: 7d48eddf-0ec6-4537-8595-88959eb253fa
description: "Find reference information about Telemetry Dashboard worksheets that helps you understand Office stability in your organization."
---

# Telemetry Dashboard worksheet reference

 **Summary:** Find reference information about Telemetry Dashboard worksheets that helps you understand Office stability in your organization. 
  
 **Audience:** IT Professionals 
  
As you use Telemetry Dashboard to investigate stability issues for Office documents and Office solutions, you might need more information about the data that is displayed in the worksheets. Use this article as a reference guide to help understand the data that is shown in Telemetry Dashboard. This data helps you identify stability issues for Office documents and solutions and helps you track Office deployments. You can also use this data to identify problems with the telemetry agents and processors.
  
     
<a name="bkmk_OverviewWorksheet"> </a>

## Overview worksheet

The **Overview** worksheet provides a big picture view of both the stability and deployment status of Office within your organization. By using this worksheet, you can quickly understand how your critical documents and solutions are behaving on users' computers. Instead of browsing the **Documents** and **Solutions** worksheets, which show you item-by-item status, you can open and refresh the **Overview** worksheet to see a high-level view of document and solution stability. The following screen shot shows the Overview worksheet: 
  
**Overview worksheet in Telemetry Dashboard**

![An screenshot of the main Overview worksheet view on the Office Telemetry dashboard.](../images/ORK_Telem_OverviewWSmain.png)
  
There are three primary tasks that you can perform on the **Overview** worksheet.
  
- [Determine the overall stability of Office 2016 documents and solutions throughout your organization](monitor-office-compatibility-and-deployments-by-using-telemetry-dashboard.md#stability)
    
- [Drill down to investigate unstable documents or solutions that require your attention](monitor-office-compatibility-and-deployments-by-using-telemetry-dashboard.md#investigate)
    
- [View the progress of Office 2016 deployments in your organization](monitor-office-compatibility-and-deployments-by-using-telemetry-dashboard.md#deploystatus)
    
<a name="bkmk_DocumentsWorksheet"> </a>

## Documents worksheet

The **Documents** worksheet in Telemetry Dashboard displays the list of documents that was collected by telemetry logging and by Telemetry Agent scans. In this worksheet, you can find frequently used documents and telemetry data about them. 
  
The following screen shot shows the **Documents** worksheet. 
  
**Documents worksheet in Telemetry Dashboard**

![A screenshot of the main Document worksheet view in the Office Telemetry dashboard.](../images/ORK_Telem_DocumentWorksheet1.png)
  
There are two main sections on the Documents worksheet:
  
- **Office usage**
    
- **Office 2016 telemetry data**
    
The columns under the **Office usage** section display usage data that is collected by the Telemetry Agent. You can select the link for the number of users of a document to see who is using the document. This information is displayed in the **Document details** worksheet. 
  
The columns under the **Office 2016 telemetry data** section display telemetry data that is collected by telemetry logging. You can select the link for the number of users who hit critical or informative issues to see more details. This information is displayed in the **Document issues** worksheet. 
  
The following table describes each column in the **Documents** worksheet. 
  
> [!NOTE]
> By default, some columns are collapsed and not visible. Select the [+] symbols on the top row to expand the columns. 
  
**Column descriptions for the Documents worksheet in Telemetry Dashboard**

|**Section**|**Column**|**Description**|
|:-----|:-----|:-----|
|Office usage  <br/> |File name  <br/> |Shows the file name of each document.  <br/> |
||Total users  <br/> |Shows the number of users who opened each document by using Office 2003, Office 2007, Office 2010, Office 2013, and Office 2016  <br/> |
||Office 2003  <br/> |Shows the number of users who opened each document by using Office 2003.  <br/> |
||Office 2007  <br/> |Shows the number of users who opened each document by using Office 2007.  <br/> |
||Office 2010  <br/> |Shows the number of users who opened each document by using Office 2010.  <br/> |
||Office 2013  <br/> |Shows the number of users who opened each document by using Office 2013.  <br/> |
||Office 2016  <br/> |Shows the number of users who opened each document by using Office 2016.  <br/> |
||Office 2003 (computers)  <br/> |Shows the number of computers on which users opened each document by using Office 2003  <br/> |
||Office 2007 (computers)  <br/> |Shows the number of computers on which users opened each document by using Office 2007.  <br/> |
||Office 2010 (computers)  <br/> |Shows the number of computers on which users opened each document by using Office 2010.  <br/> |
||Office 2013 (computers)  <br/> |Shows the number of computers on which users opened each document by using Office 2013.  <br/> |
||Office 2016 (computers)  <br/> |Shows the number of computers on which users opened each document by using Office 2016.  <br/> |
|Office 2016 telemetry data  <br/> |Success (%)  <br/> |Shows the percentage of successfully opened documents (no critical errors occurred) out of the total number of sessions.  <br/> |
||Sessions  <br/> |Shows the total number of sessions. A session refers to all selected file open events.  <br/> |
||Trend  <br/> |Shows the trend of changes that occurred between the current week and a week within the selected period. You can change the period by using the **Date range** filter in the navigation pane. For example, if you select **1 year** from the **Date range**, the column shows a trend that compares the current week to a week from one year prior.  <br/> |
||Critical  <br/> |Shows the number of users who encountered critical issues.  <br/> |
||Critical issues  <br/> |Shows the number of unique critical issues.  <br/> |
||Informative  <br/> |Shows the number of users who encountered informative issues.  <br/> |
||Informative issues  <br/> |Shows the number of unique informative issues.  <br/> |
||Application  <br/> |Shows the name of the application that was used to open each document.  <br/> |
||Extension  <br/> |Shows the file name extensions that were used to open each document.  <br/> |
||Built-in  <br/> |Indicates whether each document is included with Office or has a default file name that is used for Office documents. You can use the filter for this column to hide built-in documents so that you can see the unique documents in your organization.  <br/> |
   
The following sections describe worksheets that help you drill down into specific issues. These worksheets appear after you select links within the **Documents** worksheet. 
  
<a name="document_details"> </a>

## Document details worksheet

The **Document details** worksheet appears after you select a link under **Office usage** on the **Documents** worksheet. The **Document details** worksheet helps you see which users are frequently using a document. 
  
The following screen shot shows the **Documents details** worksheet. 
  
**Document details worksheet in Telemetry Dashboard**

![A screenshot of the Document details worksheet in the Office Telemetry dashboard.](../images/ORK_Telem_DocumentWorksheet2.png)
  
The following table describes each column in the **Document details** worksheet. 
  
**Column descriptions for the Documents details worksheet in Telemetry Dashboard**

|**Column**|**Description**|
|:-----|:-----|
|User name  <br/> |Displays the name of the user who used the document.  <br/> |
|User domain  <br/> |Displays the domain name for this user.  <br/> |
|Computer name  <br/> |Displays the computer name that was used to open the document.  <br/> |
|Computer domain  <br/> |Shows the computer's domain name.  <br/> |
|Location  <br/> |Shows the file path of the document.  <br/><br/>  Only one file path is kept per user and computer. If the same user opens the document from a different file path on the same computer, Office Telemetry keeps only the most recent file path.  <br/> |
|Size (KB)  <br/> |Shows the file size of the document.  <br/> |
|Author  <br/> |Shows the author name of the document.  <br/> |
|VBA  <br/> |Indicates whether the document contains VBA code.  <br/> |
|OLE  <br/> |Indicates whether the document contains OLE objects.  <br/> |
|External data connection  <br/> |Indicates whether the document has an external data connection.  <br/> |
|ActiveX control  <br/> |Indicates whether the document contains ActiveX controls.  <br/> |
|Assembly reference  <br/> |Indicates whether the document contains VSTO document-level customizations.  <br/> |
|Last loaded  <br/> |Indicates when the document was most recently loaded.  <br/> |
|Title  <br/> |Shows the title of the document.  <br/> |
|Office version  <br/> |Shows the version of Office that was used to open the document.  <br/> |
   
<a name="document_issues"> </a>

## Document issues worksheet

The **Document issues** worksheet appears after you select a link under **Office 2016 telemetry data** on the **Documents** worksheet. The **Document issues** worksheet helps you find details about unique events that were found for a document. 
  
The following screen shot shows the **Document issues** worksheet. 
  
**Document issues worksheet in Telemetry Dashboard**

![A screenshot of the Document issues worksheet from the Office Telemetry dashboard.](../images/ORK_Telem_DocumentWorksheet3.png)
  
The following table describes each column in the **Document issues** worksheet. 
  
**Column descriptions for the Documents issues worksheet in Telemetry Dashboard**

|**Column**|**Description**|
|:-----|:-----|
|Event ID  <br/> |Displays the Event ID. For more information about the event IDs, see "Table 2. Types of events displayed in the Telemetry Log" in [Troubleshooting Office files and custom solutions with the Office Telemetry Log](https://go.microsoft.com/fwlink/p/?LinkId=260532).  <br/> |
|Title  <br/> |Shows the title of the issue.  <br/> |
|Explanation  <br/> |Describes the issue.  <br/> |
|More info  <br/> |Provides a link to more information.  <br/> |
|Users  <br/> |Shows total number of users who encountered the issue.  <br/> |
|Sessions  <br/> |Shows total number of sessions that encountered the issue.  <br/> |
   
<a name="document_sessions"> </a>

## Document sessions worksheet

The **Document sessions** worksheet shows the sessions during which an issue occurred. You can open this worksheet by selecting a link in the **Sessions** column of the **Document issues** worksheet. 
  
The following screen shot shows the **Documents sessions** worksheet. 
  
**Document sessions worksheet in Telemetry Dashboard**

![A screenshot of the Document sessions worksheet from the Office Telemetry dashboard.](../images/ORK_Telem_DocumentWorksheet4.png)
  
The following table describes each column in the **Document sessions** worksheet. 
  
**Column descriptions for the Documents sessions worksheet in Telemetry Dashboard**

|**Column**|**Description**|
|:-----|:-----|
|Event ID  <br/> |Displays the Event ID. For more information about the event IDs, see "Table 2. Types of events displayed in the Telemetry Log" in [Troubleshooting Office files and custom solutions with the Office Telemetry Log](https://go.microsoft.com/fwlink/p/?LinkId=260532).  <br/> |
|Event date  <br/> |Shows the date and time when the issue occurred.  <br/> |
|User name  <br/> |Shows the names of users who were using the document that encountered the issue.  <br/> |
|User domain  <br/> |Shows the domain name for the user.  <br/> |
|Computer name  <br/> |Shows the name of the computer where the document encountered the issue.  <br/> |
|Computer domain  <br/> |Shows the computer's domain name.  <br/> |
|Location  <br/> |Shows the file path where the selected document was opened.  <br/><br/>  Only one file path is kept per user and computer. If the same user opens the document from a different file path on the same computer, Office Telemetry keeps only the most recent file path.  <br/> |
|Office version  <br/> |Shows the version of Office that was used to open this document.  <br/> |
|Documents loaded  <br/> |Shows the list of documents that were being used when the issue occurred.  <br/> |
|Size (KB)  <br/> |Shows the size of the document.  <br/> |
|Author  <br/> |Shows the name of the author of the document.  <br/> |
|VBA  <br/> |Indicates whether the document contains VBA code.  <br/> |
|OLE  <br/> |Indicates whether the document contains OLE objects.  <br/> |
|External data connection  <br/> |Indicates whether the document has an external data connection.  <br/> |
|ActiveX control  <br/> |Indicates whether the document contains ActiveX controls.  <br/> |
|Assembly reference  <br/> |Indicate whether the document contains VSTO document-level customization.  <br/> |
|Title  <br/> |Shows the title of the document.  <br/> |
   
<a name="bkmk_SolutionsWorksheet"> </a>

## Solutions worksheet

The **Solutions** worksheet displays the list of solutions that was collected by telemetry logging and telemetry agent scans. In this worksheet, you can find frequently used solutions and telemetry data about them. The kinds of solutions that are shown include COM add-ins, application-specific add-ins, and apps for Office. 
  
The following screen shot shows the **Solutions** worksheet. 
  
**Solutions worksheet in Telemetry Dashboard**

![A screenshot of the main Solutions worksheet from the Office Telemetry dashboard.](../images/ORK_Telem_SolutionWorksheet1.png)
  
After telemetry data is collected, you can manage Office add-ins by using the **Add-in management mode** link on the **Solutions** worksheet. For more information, see [Let's manage add-ins using Telemetry Dashboard](https://go.microsoft.com/fwlink/p/?LinkId=271236).
  
There are two main sections on the **Solutions** worksheet: 
  
- **Office usage**
    
- **Office 2016 telemetry data**
    
The columns under the **Office usage** section display the usage data that is collected by the telemetry agent. You can select the link for the number of users of a solution to see who is using the solution. This information is displayed on the **Solution details** worksheet. 
  
The columns under the **Office 2016 telemetry data** section display telemetry data that is collected by telemetry logging. You can select the link for the number of users who hit critical or informative issues to see more details. This information is displayed on the **Solution issues** worksheet. 
  
The following table describes each column in the **Solutions** worksheet. 
  
> [!NOTE]
> By default, some columns are collapsed and not visible. Select the [+] symbols on the top row to expand the columns. 
  
**Column descriptions for the Solutions worksheet in Telemetry Dashboard**

|**Section**|**Column**|**Description**|
|:-----|:-----|:-----|
|Office usage  <br/> |Total users  <br/> |Shows the number of users who use the solution in Office 2003, Office 2007, Office 2010, Office 2013, and Office 2016.  <br/> |
||Office 2003  <br/> |Shows the number of users who use the solution in Office 2003.  <br/> |
||Office 2007  <br/> |Shows the number of users who use the solution in Office 2007.  <br/> |
||Office 2010  <br/> |Shows the number of users who use the solution in Office 2010.  <br/> |
||Office 2013  <br/> |Shows the number of users who use the solution in Office 2013.  <br/> |
||Office 2016  <br/> |Shows the number of users who use the solution in Office 2016.  <br/> |
||Total computers  <br/> |Shows the number of computers where the solution was opened by using Office 2003, Office 2007, Office 2010, Office 2013, and Office 2016.  <br/> |
||Office 2003 (computers)  <br/> |Shows the number of computers where the solution was opened by using Office 2003.  <br/> |
||Office 2007 (computers)  <br/> |Shows the number of computers where the solution was opened by using Office 2007.  <br/> |
||Office 2010 (computers)  <br/> |Shows the number of computers where the solution was opened by using Office 2010.  <br/> |
||Office 2013 (computers)  <br/> |Shows the number of computers where the solution was opened by using Office 2013.  <br/> |
||Office 2016 (computers)  <br/> |Shows the number of computers where the solution was opened by using Office 2016.  <br/> |
|Office 2016 telemetry data  <br/> |Success (%)  <br/> |Shows the percentage of successfully opened solutions (no critical error occurred) out of total sessions.  <br/> |
||Sessions  <br/> |Shows the total number of sessions. A session refers to all selected file open events.  <br/> |
||Trend  <br/> |Shows the trend of changes that occurred between this week and a week within the selected period. You can change the period by using the **Date range** filter in the navigation pane. For example, if you select **1 year** from the **Date range**, the column shows a trend that compares this week to a week from one year prior.  <br/> |
||Critical  <br/> |Shows the number of users who encountered critical issues  <br/> |
||Critical issues  <br/> |Shows the number of unique critical issues.  <br/> |
||Informative  <br/> |Shows the number of users who encountered informative issues.  <br/> |
||Informative issues  <br/> |Shows the number of unique informative issues.  <br/> |
||Load time  <br/> |Shows the average load time of the solution.  <br/> |
||Application  <br/> |Shows the application name that was used to open the selected solution.  <br/> |
||Type  <br/> |Shows the solution type.  <br/> |
||File  <br/> |Shows the file name of the solution.  <br/> |
||Extension  <br/> |Shows the file name extensions of the solution.  <br/> |
||Publisher  <br/> |Shows the publisher of the solution.  <br/> |
||Built-in  <br/> |Indicates whether this solution is included with Office. You can use the filter for this column to hide built-in solutions so that you can see the unique solutions in your organization.  <br/> |
   
The following sections describe worksheets that help you drill down into specific issues. These worksheets appear after you select links within the **Solutions** worksheet. 
  
<a name="solution_details"> </a>

## Solution details worksheet

The **Solution details** worksheet appears after you select a link under **Office usage** on the **Solutions** worksheet. The **Solution details** worksheet helps you see which users are frequently using a solution. 
  
The following screen shot shows the **Solution details** worksheet. 
  
**Solution details worksheet in Telemetry Dashboard**

![A screenshot of the Document details worksheet in the Office Telemetry dashboard.](../images/ORK_Telem_DocumentWorksheet2.png)
  
The following table describes each column in the **Solution details** worksheet. 
  
**Column description for the Solution details worksheet**

|**Column**|**Description**|
|:-----|:-----|
|User name  <br/> |Shows the name of user who used the solution.  <br/> |
|User domain  <br/> |Shows the domain name for this user.  <br/> |
|Computer name  <br/> |Shows the name of the computer where the solution was opened.  <br/> |
|Computer domain  <br/> |Shows the computer's domain name.  <br/> |
|Solution version  <br/> |Shows the version of the solution.  <br/> |
|Architecture  <br/> |Shows the architecture of the solution.  <br/> |
|Load time  <br/> |Shows how long the solution took to load.  <br/> |
|Last loaded  <br/> |Shows the last time that the solution was loaded.  <br/> |
|Load behavior  <br/> | Shows the load behavior of COM add-ins as follows:  <br/> <br/> **0** - Do not load automatically (Unloaded)  <br/> **1** - Do not load automatically (Loaded)  <br/> **2** - Load at startup (Unloaded)  <br/> **3** - Load at startup (Loaded)  <br/> **8** - Load on demand (Unloaded)  <br/> **9** - Load on demand (Loaded)  <br/> **16** - Load first time, then load on demand (Loaded)  <br/> <br/>  For more information, see [Load behavior values](https://go.microsoft.com/fwlink/p/?LinkId=272180).  <br/> |
|Policy setting  <br/> |Shows the policy setting.  <br/> |
|Office version  <br/> |Shows the Office version that was used to open the solution.  <br/> |
|Publisher  <br/> |Shows the publisher of the solution.  <br/> |
|Author  <br/> |Shows the author name of the solution.  <br/> |
|Friendly name  <br/> |Shows the friendly name of the solution.  <br/> |
|Description  <br/> |Shows the description of the solution.  <br/> |
|Size (KB)  <br/> |Shows the size of the solution.  <br/> |
|Location  <br/> |Shows the file path of the solution.Only one file path is kept per user and computer. If the same user opens the solution from different file path on the same computer, Office Telemetry keeps only the most recent file path.  <br/> |
   
<a name="solution_issues"> </a>

## Solution issues worksheet

The **Solution issues** worksheet appears after you select a link under **Office 2016 telemetry data** on the **Solutions** worksheet. The **Solution issues** worksheet helps you find details about the unique events that were found for a solution. 
  
The following screen shot shows the **Solution issues** worksheet. 
  
**Solution issues worksheet in Telemetry Dashboard**

![A screenshot of the Solutions issues worksheet from the Office Telemetry dashboard.](../images/ORK_Telem_SolutionWorksheet3.png)
  
The following table describes each column in the **Solution issues** worksheet. 
  
**Column descriptions for the Solution issues worksheet in Telemetry Dashboard**

|**Column**|**Description**|
|:-----|:-----|
|Event ID  <br/> |Displays the Event ID. For more information about the event IDs, see "Table 2. Types of events displayed in the Telemetry Log" in [Troubleshooting Office files and custom solutions with the Office Telemetry Log](https://go.microsoft.com/fwlink/p/?LinkId=260532).  <br/> |
|Title  <br/> |Shows the title of the issue.  <br/> |
|Explanation  <br/> |Describes the issue.  <br/> |
|More info  <br/> |Provides a link to more information.  <br/> |
|Users  <br/> |Shows the number of users who encountered the issue.  <br/> |
|Sessions  <br/> |Shows the number of sessions that encountered the issue.  <br/> |
   
<a name="solution_sessions"> </a>

## Solution sessions worksheet

The **Solution sessions** worksheet shows the sessions during which the issue occurred. You can open this worksheet by selecting a link in the **Sessions** column of the **Solution issues** worksheet. 
  
The following screen shot shows the **Solution sessions** worksheet. 
  
**Solution sessions worksheet in Telemetry Dashboard**

![A screenshot of the Solutions sessions worksheet from the Office Telemetry dashboard.](../images/ORK_Telem_SolutionWorksheet4.png)
  
The following table describes each column in the **Solution sessions** worksheet. 
  
**Column descriptions for the Solution sessions worksheet in Telemetry Dashboard**

|**Column**|**Description**|
|:-----|:-----|
|Event ID  <br/> |Displays the Event ID. For more information about the event IDs, see "Table 2. Types of events displayed in the Telemetry Log" in [Troubleshooting Office files and custom solutions with the Office Telemetry Log](https://go.microsoft.com/fwlink/p/?LinkId=260532).  <br/> |
|Event date  <br/> |Shows the date and time when the issue occurred.  <br/> |
|User name  <br/> |Shows the names of users who were using the solution that encountered the issue.  <br/> |
|User domain  <br/> |Shows the domain name for the user.  <br/> |
|Computer name  <br/> |Shows the name of the computer where the solution encountered the issue.  <br/> |
|Computer domain  <br/> |Shows the computer's domain name.  <br/> |
|Solution version  <br/> |Shows the version of the solution.  <br/> |
|Architecture  <br/> |Shows the architecture of the solution.  <br/> |
|Office version  <br/> |Shows the Office version with build numbers that used this solution.  <br/> |
|Load time  <br/> |Shows how long the solution took to load.  <br/> |
|Load behavior  <br/> | Shows the load behavior of COM add-ins as follows:<br/>   <br/> **0** - Do not load automatically (Unloaded)  <br/> **1** - Do not load automatically (Loaded)  <br/> **2** - Load at startup (Unloaded)  <br/> **3** - Load at startup (Loaded)  <br/> **8** - Load on demand (Unloaded)  <br/> **9** - Load on demand (Loaded)  <br/> **16** - Load first time, then load on demand (Loaded)  <br/> <br/>  For more information, see [Load behavior values](https://go.microsoft.com/fwlink/p/?LinkId=272180).  <br/> |
|Policy setting  <br/> |Shows the policy setting.  <br/> |
|Document loaded  <br/> |Shows the documents that were open when the issue occurred.  <br/> |
|Publisher  <br/> |Shows the publisher of the solution.  <br/> |
|Author  <br/> |Shows the author name of the solution.  <br/> |
|Friendly name  <br/> |Shows the friendly name of the solution.  <br/> |
|Description  <br/> |Shows the description of the solution.  <br/> |
|Size (KB)  <br/> |Shows the size of the solution.  <br/> |
|Location  <br/> |Shows the file path of the solution.  <br/> <br/> Only one file path is kept per user and computer. If the same user opens the solution from a different file path on the same computer, Office Telemetry keeps only the most recent file path.  <br/> |
   
<a name="bkmk_TelemetryProcessorWorksheet"> </a>

## Telemetry Processor worksheet

The **Telemetry Processor** worksheet displays information about the health of the Office Telemetry infrastructure. You can monitor whether Telemetry Processors are running correctly, and you can check whether users' computers are sending telemetry data correctly. 
  
The following screen shot shows the **Telemetry Processor** worksheet: 
  
**Telemetry Processor worksheet in Telemetry Dashboard**

![A screenshot of the main Telemetry Processor worksheet from the Office Telemetry dashboard.](../images/ORK_Telem_TelemetryProcessor.png)
  
The following table describes each column in the **Telemetry Processor** worksheet. 
  
**Column descriptions for the Telemetry Processor worksheet in Telemetry Dashboard**

|**Column**|**Description**|
|:-----|:-----|
|Computer name  <br/> |Lists the names of computers that are running Telemetry Processor. You can select the computer name to see the users whose computers are sending telemetry data to each Telemetry Processor. For more information about this feature, see the **Agents** worksheet later in this article.  <br/> |
|Level  <br/> |Shows the status of the Telemetry Processor. Depending on the status, you might want to investigate if the Telemetry Processor is running correctly or if the agents on users' computers are configured correctly and uploading data.  <br/><br/>  The levels are described in the next table.  <br/> |
|Users  <br/> |Shows the number of users whose computers are connected to each Telemetry Processor.  <br/> |
|Computers  <br/> |Shows the number of computers that connected to each Telemetry Processor.  <br/> |
|Last updated  <br/> |Shows the last date and time when the Telemetry Processor inserted data into the database.  <br/> |
   
The following table describes the status that is represented by the symbols that are displayed in the **Level** column. 
  
**Icon descriptions for the Level column in the Telemetry Processor worksheet**

|**Symbol**|**Status description**|
|:-----|:-----|
|![An image of the status icon indicating that the last update date/time for the Telemetry Processor is less than a day ago.](../images/ORK_Telem_Icon_Green.png)|The last updated date and time for the Telemetry Processor is less than a day ago.  <br/> |
|![An image of the status icon indicating that 5% or more of the users for this Telemetry Processor are not uploading data for the last 14 days.](../images/ORK_Telem_Icon_Yellow.png)|5% or more of the users for this Telemetry Processor have not uploaded data for the last 14 days. Select the Telemetry Processor name to open the **Agents** worksheet so that you can view which users' computers are not sending telemetry data.  <br/> |
|![An image of the status icon indicating that the last updated date/time for the Telemetry Processor is older than a day.](../images/ORK_Telem_Icon_Red.png)|The last updated date and time for the Telemetry Processor is older than a day. When you see this status, you should investigate whether the Telemetry Processor is running correctly on the computer. <br/> <br/> You find information about how to troubleshoot Telemetry Processor in [Troubleshooting Telemetry Dashboard deployments](deploy-telemetry-dashboard.md#tshooting).  <br/> |
|(No symbol)  <br/> |The last updated date and time for the Telemetry Processor was more than 14 days ago.  <br/> |
   
> [!NOTE]
> A Telemetry Processor is deleted from the **Telemetry Processors** worksheet if the **Last updated** value for the Telemetry Processor is 90 or more days ago. 
  
<a name="agents"> </a>

## Agents worksheet

The **Agents** worksheet displays information about the users whose computers who are uploading data to each Telemetry Processor. You can open the **Agents** worksheet by selecting a link for a computer name on the **Telemetry Processor** worksheet. Use this worksheet to monitor the upload status of each computer. 
  
The following screen shot shows the **Agents** worksheet. 
  
**Agents worksheet in Telemetry Dashboard**

![A screenshot of the Agents worksheet which is a drill down worksheet from the Telemetry Processor page on the Office Telemetry dashboard.](../images/ORK_Telem_Agents.png)
  
The following table describes each column in the **Agents** worksheet. 
  
**Column descriptions for the Agents worksheet in Telemetry Dashboard**

|**Column name**|**Description**|
|:-----|:-----|
|User name  <br/> |Lists the names of users whose computers upload telemetry data to the Telemetry Processor.  <br/> |
|Level  <br/> |Indicates how recently the agent uploaded data. The levels are described in the next table.  <br/> |
|Computer  <br/> |Lists the names of the computers that upload telemetry data.  <br/> |
|Last updated  <br/> |Shows the last date and time when the user's computer uploaded data.  <br/> |
|Label 1 - 4  <br/> |Shows the tag values that are assigned to each user.  <br/> |
|Version  <br/> |Shows the major and minor version of Telemetry Agent that runs on the user's computer.  <br/> |
   
The following table describes the status that is represented by the symbols that are displayed in the **Level** column. 
  
|**Symbol**|**Status description**|
|:-----|:-----|
|![An image of the status icon indicating that the last update date/time for the Telemetry Processor is less than a day ago.](../images/ORK_Telem_Icon_Green.png)|The last updated date and time for the user is less than a day ago.  <br/> |
|![An image of the status icon indicating that 5% or more of the users for this Telemetry Processor are not uploading data for the last 14 days.](../images/ORK_Telem_Icon_Yellow.png)|The last updated date and time for the user is between 2 and 14 days ago. Occasionally, you will see this icon when the user's computer has not uploaded data for more than a day (for example, Monday morning after the weekend).  <br/> |
|![An image of the status icon indicating that the last updated date/time for the Telemetry Processor is older than a day.](../images/ORK_Telem_Icon_Red.png)|The last updated date and time for the user is between 15 and 30 days ago. When you see this status, you should investigate whether the Telemetry Agent on this user's computer is configured correctly.  <br/><br/>  You find information about how to troubleshoot Telemetry Agents in [Troubleshooting Telemetry Dashboard deployments](deploy-telemetry-dashboard.md#tshooting).  <br/> |
|(No symbol)  <br/> |The last updated date and time for the Telemetry Processor was 31 or more days ago.  <br/> |
   
> [!NOTE]
> A user is deleted from the **Agents** worksheet if the **Last updated** value for the user was 90 or more days ago. 
  
<a name="bkmk_DeploymentsWorksheet"> </a>

## Deployments worksheet

The **Deployments** worksheet provides a tabular view of the number of Office clients that are deployed in your organization. This worksheet provides additional information for the deployment trend chart that is shown in the **Overview** worksheet. This information can help you plan for future Office deployments. 
  
In the following screen shot of the **Deployments** worksheet, you can see how many Office clients are deployed. The list is organized by Office version and CPU architecture. For example, you can see how many users are running 32-bit versions of Office. 
  
**Deployments worksheet in Telemetry Dashboard**

![A screenshot of the main Deployments worksheet from the Office Telemetry dashboard.](../images/ORK_Telem_Deployment.png)
  
You can see that there are still 32-bit computers that are running Office 2003. You may want to contact these users to understand if they have any concerns about how to upgrade. You can also create a custom report to show more information about these users, such as their computer hardware.
  
Also, you should be aware that Windows 8 is now supported on ARM-based architectures. If your organization has users who have Office on these computers, you can now keep track of that information in the **Deployments** worksheet. You can create custom reports to obtain richer information about who is using these computers, what issues they may be experiencing, and so on. 
  
<a name="custom_report"> </a>

## Custom report worksheet

When you select the **Create custom report** button on the **Custom report** worksheet, Telemetry Dashboard connects to multiple tables and creates relationships for you to use in a PivotTable. If you have never used a PivotTable before, you can learn more in [Tutorial: PivotTable data analysis using a Data Model in Excel](https://go.microsoft.com/fwlink/?LinkID=279531). 
  
## Related topics
[Compatibility and telemetry in Office](compatibility-and-telemetry-in-office.md)
  
[Deploy Telemetry Dashboard](deploy-telemetry-dashboard.md)
