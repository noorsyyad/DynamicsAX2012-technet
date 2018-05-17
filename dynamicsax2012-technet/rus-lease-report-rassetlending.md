﻿---
title: (RUS) Lease report (RAssetLending)
TOCTitle: (RUS) Lease report (RAssetLending)
ms:assetid: f45b043a-cc08-4ba3-a56c-00e152430356
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ992747(v=AX.60)
ms:contentKeyID: 51739434
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.RAssetLending
---

# (RUS) Lease report (RAssetLending) 


_**Applies To:** Microsoft Dynamics AX 2012 R2_

The Lease report displays a list of the fixed assets that are currently leased. The data on this report includes the date when a fixed asset is leased, the location and current lessee of the fixed asset, and the date when the fixed asset is returned to the legal entity. Accountants generate this report periodically to review information about leased fixed assets.

## How to filter the data on this report

When you generate this report, the following default parameters are displayed. You can use these parameters to filter the data that will be displayed on the report. For more information, see [Filter the data on a report](filter-the-data-on-a-report.md).

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Field</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>FA group</strong></p></td>
<td><p>The fixed asset group number of the fixed assets that are included on the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>FA inventory number</strong></p></td>
<td><p>The inventory number of each fixed asset that is included on the report.</p></td>
</tr>
</tbody>
</table>


## How to work with reports

The following topics explain how to print a report and how to filter and sort the data on a report.

  - [Print or email a report](print-or-email-a-report.md)

  - [Filter the data on a report](filter-the-data-on-a-report.md)

  - [Sort the data on a report](sort-the-data-on-a-report.md)

## Details of this report

The following table explains where to find the report in the Application Object Tree (AOT) and how to navigate to the report in the Microsoft Dynamics AX client.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Detail</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Name of report in the AOT</p></td>
<td><p>RAssetLending</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\RAssetLending</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>RAssetLending</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Fixed assets (Russia)</strong> &gt; <strong>Reports</strong> &gt; <strong>Lease (report)</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data on this report comes from

The data on this report comes from the following sources:

  - RAssetLendingView table

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

## See also

[(RUS) FA value models (form)](https://technet.microsoft.com/en-us/library/jj856113\(v=ax.60\))

[(RUS) FA on loan (form)](https://technet.microsoft.com/en-us/library/jj665390\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).
