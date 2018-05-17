﻿---
title: (RUS) Calculate the accounts receivable bad debts reserve register
TOCTitle: (RUS) Calculate the accounts receivable bad debts reserve register
ms:assetid: 17c15c23-0cfb-4828-89e8-51c30ece7de6
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ711433(v=AX.60)
ms:contentKeyID: 49387251
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (RUS) Calculate the accounts receivable bad debts reserve register 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You must set up the **Accounts receivable - bad debts reserve** register in the **Tax registers** form and create a tax register journal before calculating the register.


> [!NOTE]
> <P>For more information, see <A href="rus-set-up-a-register-for-the-accounts-receivable-bad-debts-reserve.md">(RUS) Set up a register for the accounts receivable bad debts reserve</A>.</P>




> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **General ledger** \> **Journals** \> **Tax register journal**.

2.  Press CTRL+N to create a new register journal and enter the required details. You can create a new journal only if all the previous journals are approved.
    

    > [!NOTE]
    > <P>For more information see <A href="rus-create-a-tax-register-journal.md">(RUS) Create a tax register journal</A> and <A href="rus-approve-the-register.md">(RUS) Approve the register</A>.</P>



3.  Click **Lines** to open the **Register journal lines** form. Register journal lines are created with the status as **Not calculated**.

4.  Select the **Accounts receivable - bad debts reserve** journal line.

5.  Click **Register calculation** \> **Calculate current** to calculate the register.

6.  Click **OK** to confirm the calculation. After calculation, the status of the register is displayed as **Calculated** in the **Status** field.
    

    > [!NOTE]
    > <P>To view the details in the register lines after calculation, click <STRONG>Register lines</STRONG> to open the <STRONG>Register lines</STRONG> form.</P>



7.  Select the **Approved** check box to approve the register.

8.  In the **Worker** field, view or modify the code of the employee who approved the register.

9.  Press CTRL+S or close the form.

## See also

[(RUS) Tax register journal (form)](https://technet.microsoft.com/en-us/library/jj856114\(v=ax.60\))

[(RUS) Register journal lines (form)](https://technet.microsoft.com/en-us/library/jj839663\(v=ax.60\))

[(RUS) Recalculate registers](rus-recalculate-registers.md)

[(RUS) Tax registers (form)](https://technet.microsoft.com/en-us/library/jj853195\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).
