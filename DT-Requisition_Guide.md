---
layout: default
title: DT Requisition Guide
permalink: /dtreqguide/
---

# CREATING DT REQUISITIONS IN PEOPLESOFT
April 4, 2018

## Introduction
After years of preparation, months of training, and even more months of delay, the City and County of San Francisco has taken the plunge: goodbye to the decrepit, mainframe world of FAMIS, and hello to the modern, web-based world of PeopleSoft to manage every transaction in the City’s $10 billion budget!

The [SF Employee Portal](https://sfemployeeportalsupport.sfgov.org/support/home) contains a wealth of training and job aides designed for the citywide audience of budget, accounting, and procurement teams. We have tested the [eProcurement: Create a Requisition job aide](https://sfemployeeportalsupport.sfgov.org/support/solutions/articles/22000209326-create-a-requisition), and it is technically accurate. It contains 97% of what you need to know to successfully create a requisition for the Department of Technology. This document will fill in that missing 3%, warn you of potential pitfalls, and stiffen your spine to jump into the future.

## Pep Talk and a Word of Caution
We all know that the PeopleSoft rollout remains a work in progress: errors in contract conversion are still being uncovered, most vendors still lack access, many budget codes are confusing or incorrect, individual role-mapping appears to be . . . creative? 
BUT, the PeopleSoft system is live, FAMIS is now frozen, and our ability to keep the lights and Internet on for the City depends on our ability to start flying this plane while the support team finishes building it.

![caution](/images/exclamation.png) The City made the decision to make this an open system. This essentially means that “trust is given, not earned.” We have visibility and access to budgets outside of DT’s. This, combined with the bugs in the system, mean it can be easy to accidentally misroute our requisitions, purchase orders, and contracts. **It’s not the end of the world if-and-when mistakes happen!** This guide will help you avoid some pitfalls, but there will undoubtedly be more pitfalls. That’s okay! If we can’t correct an errant requisition, we can always delete it and start over. Take a deep breath, pour another cup of coffee, and we’ll begin. 

## What You Need and Where to Get It
Before you login to the PeopleSoft system, we suggest you first take a few minutes to gather all of the information you will need. If your requisition has missing budget codes, you want to find out now before you invest the time to start entering all the information. Here is what you need to create a DT requisition:
*	[eProcurement: Create a Requisition job aide](https://sfemployeeportalsupport.sfgov.org/support/solutions/articles/22000209326-create-a-requisition)
*	This DT-specific supplemental guide
*	PeopleSoft budget codes for your requisition 

![caution](/images/exclamation.png) The PeopleSoft budget codes provide the key information to ensure that your requisition is attached to the correct portion of the budget and routed to the correct approval path.

### Determining PeopleSoft Budget Codes
There are two main sources for determining the new PeopleSoft budget codes for your requisition:
*	[ServiceNow Procurement Ticket](#sn-ticket)
*	[DT FY17-18 Budget Spreadsheet](docs/dtreqguide#spreadsheet)

(#sn-ticket)#### ServiceNow Procurement Ticket
To locate the PeopleSoft budget codes in a ServiceNow procurement ticket:
1.	Navigate to the ServiceNow procurement ticket for your requisition.
2.	Scroll down to **Procurement Information** section. By default, the **Budget Section** tab is displayed.
3.	Click on the **Funding Information** tab. There you will (hopefully) see the six PeopleSoft (PS) codes needed to define the requisition!
![SN funding information](/images/SN-funding.png)

#### [DT FY17-18 Budget Spreadsheet](#spreadsheet)
But what if you are working off an old ServiceNow procurement ticket (created before 6/1/17)? DT Budget staff are in the process of mapping PeopleSoft codes to DT Budget Line Items in the spreadsheet, [FY17-18_DT_Budget-ACTIVE.xls](https://sfgov1.sharepoint.com/sites/TIS/Finance/BudgetFinancial/SitePages/Home.aspx), which is posted on DT Budget’s SharePoint home page:
![SN funding information](/images/SP-budget-page.png)

In the spreadsheet, simply search for the DT Budget Line Item for your requisition and then scroll over to locate the PeopleSoft codes.
![SN funding information](/images/DT-budget-spreadsheet.png)

## DT-Specific Guidance for Creating Requisitions
The following sections provide additional information that is not covered by the [eProcurement: Create a Requisition job aid](https://sfemployeeportalsupport.sfgov.org/support/solutions/articles/22000209326-create-a-requisition):
•	Entering the Requisition Name
•	Entering Bulk Budget Codes
•	Adding new Items to PeopleSoft
•	Confirming and Troubleshooting the Approval Path
•	Troubleshooting Incorrect Approval Paths

### Entering the Requisition Name
DT has adopted the following naming convention for requisitions to ensure consistency and make the best use of the 30-character limit:
> **DT** *ServiceNow-ticket-number brief-description*
The following screenshot shows the requisition name for ServiceNow ticket 0102084, which is for the renewal of LinkedIn corporate recruiting seats. 
 ![SN funding information](/images/PS-RQ-name.png)
 
We know the 30-character limit for names is arbitrary and annoying. Until this is fixed, we will just need to get creative with our abbreviations.  ¯\_(ツ)_/¯
