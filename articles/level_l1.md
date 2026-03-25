# Level 1 Support Knowledge Manual for MS Outlook

This guide provides step-by-step instructions for resolving common Level 1 support issues in MS Outlook, helping users troubleshoot and resolve basic problems efficiently.

## Table of Contents
1. [Introduction to MS Outlook](#1-introduction-to-ms-outlook)
2. [Common Level 1 Support Issues](#2-common-level-1-support-issues)
   - [Outlook Not Responding](#21-outlook-not-responding)
   - [Login Issues](#22-login-issues)
   - [Email Not Sending or Receiving](#23-email-not-sending-or-receiving)
   - [PST/OST File Issues](#24-pstost-file-issues)
   - [Attachment Problems](#25-attachment-problems)
3. [Basic Troubleshooting Steps](#3-basic-troubleshooting-steps)
   - [Restart Outlook](#31-restart-outlook)
   - [Check Internet Connection](#32-check-internet-connection)
   - [Run Outlook in Safe Mode](#33-run-outlook-in-safe-mode)
   - [Check for Updates](#34-check-for-updates)
   - [Quick Repair](#35-quick-repair)
4. [Performance Troubleshooting](#4-performance-troubleshooting)
   - [Clear Cache](#41-clear-cache)
   - [Clear Temporary Files](#42-clear-temporary-files)
5. [Escalation Guidelines](#5-escalation-guidelines)
6. [Conclusion](#6-conclusion)

## 1. Introduction to MS Outlook

Microsoft Outlook is an email client and personal information manager. It includes tools for managing email, calendar appointments, tasks, contacts, and notes. Outlook is widely used in business environments for handling email and scheduling tasks.

## 2. Common Level 1 Support Issues

### 2.1 Outlook Not Responding
**Description:** Outlook may freeze or become unresponsive. This issue usually occurs due to memory overload, conflicting applications, or corrupted files.

![Image 1](https://raw.githubusercontent.com/Lalith-Adithya-k/AdithyaTechWorks/main/Outlook%20doc%20final/1.png)

**Troubleshooting Steps:**
1. Select Windows icon (A) in the task bar.

![Image 17](https://raw.githubusercontent.com/Lalith-Adithya-k/AdithyaTechWorks/main/Outlook%20doc%20final/14.png)

2. Search `Task Manager` and click open (A).

![Image 2](https://raw.githubusercontent.com/Lalith-Adithya-k/AdithyaTechWorks/main/Screenshot%202024-09-30%20163224.png)

3. Find `Outlook` (A) in the list of applications and select `End Task` (B) to close the program.

![Image 3](https://raw.githubusercontent.com/Lalith-Adithya-k/AdithyaTechWorks/main/Outlook%20doc%20final/3.png)

4. Restart Outlook to see if the problem persists.

### 2.2 Login Issues
**Description:** Users may be unable to log in due to incorrect credentials or server connection issues.

![Image 4](https://raw.githubusercontent.com/Lalith-Adithya-k/AdithyaTechWorks/main/Outlook%20doc%20final/5.png)

**Troubleshooting Steps:**
1. Confirm the username and password are correct.
2. If you forget the password, select `Forget Password` (A) to set a new one.

![Image 5](https://raw.githubusercontent.com/Lalith-Adithya-k/AdithyaTechWorks/main/Outlook%20doc%20final/6.png)

3. Verify that the email server is reachable:
   - Open a browser and try accessing the email server’s web portal.
4. If issues persist, contact the system administrator to reset the login.

### 2.3 Email Not Sending or Receiving
**Description:** Emails may fail to send or receive due to server connection issues, incorrect settings, or full mailbox storage.

![Image 6](https://raw.githubusercontent.com/Lalith-Adithya-k/AdithyaTechWorks/main/Outlook%20doc%20final/7.png)


**Troubleshooting Steps:**
1. Verify that the internet connection is stable.
2. Ensure the mailbox has not exceeded the storage limit:
   - Go to `File` > `Info` (A) > `Mailbox Settings` (B).

![Image 7](https://raw.githubusercontent.com/Lalith-Adithya-k/AdithyaTechWorks/main/Outlook%20doc%20final/8.png)

3. Try sending a test email and confirm it is received.

### 2.4 PST/OST File Issues
**Description:** PST and OST files can become corrupted, causing Outlook to malfunction or fail to open.

**Troubleshooting Steps:**
1. Close Outlook.
2. Find the location (A) of `ScanPST.exe` (B).

![Image 8](https://raw.githubusercontent.com/Lalith-Adithya-k/AdithyaTechWorks/main/Outlook%20doc%20final/20.png)

3. Double click `ScanPST.exe` to open.
4. Enter the name of the corrupted PST or OST file to scan.

![Image 9](https://raw.githubusercontent.com/Lalith-Adithya-k/AdithyaTechWorks/main/Outlook%20doc%20final/21.png)

5. Click `Start` (A) to begin the repair process.

![Image 10](https://raw.githubusercontent.com/Lalith-Adithya-k/AdithyaTechWorks/main/Outlook%20doc%20final/22.png)

6. Once completed, open Outlook and check if the issue is resolved.

### 2.5 Attachment Problems
**Description:** Attachments may not open or upload due to file size limitations or compatibility issues.![Image 11](https://raw.githubusercontent.com/Lalith-Adithya-k/AdithyaTechWorks/main/Outlook%20doc%20final/9.png)

**Troubleshooting Steps:**
1. Make sure that the attachment size is within the allowable limit.
   - **Note:** Allowable limit of attachment size is **20 MB**.
2. If the file is too large, compress it to make it less than **20 MB**.
   - Right-click on the file.
   - Select `Compress to` (A) > Desired compression tool (B).

![Image 12](https://raw.githubusercontent.com/Lalith-Adithya-k/AdithyaTechWorks/main/Outlook%20doc%20final/10.png)

3. Confirm the file format is supported by the recipient’s email client.

## 3. Basic Troubleshooting Steps

### 3.1 Restart Outlook
**Description:** Restarting the application can resolve most minor issues.

**Steps:**
1. Close Outlook completely.
2. Wait for a few seconds, then reopen the application.
3. Check if the issue persists.

### 3.2 Check Internet Connection
**Description:** Email delivery often fails due to network connectivity issues.

**Steps:**
1. Make sure that the computer is connected to the internet.
   - Check the Wi-Fi or Ethernet connection status in the task bar.
2. Open a web browser to verify that websites load correctly.
3. If the connection is unstable, reset the modem/router.

### 3.3 Run Outlook in Safe Mode
**Description:** Safe Mode starts Outlook without add-ins, which can help identify if an add-in is causing the issue.

**Steps:**
1. Press **Windows + R** to open the `Run` dialog box.
2. Type `outlook.exe /safe` and press **Enter**.

![Image 13](https://raw.githubusercontent.com/Lalith-Adithya-k/AdithyaTechWorks/main/Screenshot%202024-09-30%20164037.png)

3. Outlook will open in Safe Mode. Test if the issue is resolved.
4. Go to `File` > `Options` > `Add-ins` (A) > `Go` (B)

![Image 14](https://raw.githubusercontent.com/Lalith-Adithya-k/AdithyaTechWorks/main/outlook%20addon%201.png)

5. Remove one add-in.
 
![Image 15](https://raw.githubusercontent.com/Lalith-Adithya-k/AdithyaTechWorks/main/safe%203.png)

6. Restart Outlook to find which add-in causes the problem.


### 3.4 Check for Updates
**Description:** Outdated versions of Outlook may cause performance or compatibility problems.

**Steps:**
1. Open Outlook and go to `File` > `Office Account` (A).

![Image 16](https://raw.githubusercontent.com/Lalith-Adithya-k/AdithyaTechWorks/main/Outlook%20doc%20final/12.png)

2. Select `Update Options` (A) and click `Update Now` (B).

![Image 16](https://raw.githubusercontent.com/Lalith-Adithya-k/AdithyaTechWorks/main/Outlook%20doc%20final/13.png)

3. Wait for the update process to complete.
4. Restart Outlook after updating.

### 3.5 Quick Repair
**Description:** Quick repair fixes most of the issues without the need for an internet connection.

1. Select Windows icon (A) in the task bar.

![Image 17](https://raw.githubusercontent.com/Lalith-Adithya-k/AdithyaTechWorks/main/Outlook%20doc%20final/14.png)

2. Search **Control Panel**.
3. Double click to open the `Control Panel` (A).

![Image 18](https://raw.githubusercontent.com/Lalith-Adithya-k/AdithyaTechWorks/main/Outlook%20doc%20final/15.png)

4. Go to `Control Panel > Programs > Programs and Features`

![Image 19](https://raw.githubusercontent.com/Lalith-Adithya-k/AdithyaTechWorks/main/Outlook%20doc%20final/16.png)

5. Select `Microsoft Office` (A) and click `Change` (B).

![Image 20](https://raw.githubusercontent.com/Lalith-Adithya-k/AdithyaTechWorks/main/Outlook%20doc%20final/17.png)


6. Select `Quick Repair` and click `Repair` (A).

![Image 21](https://raw.githubusercontent.com/Lalith-Adithya-k/AdithyaTechWorks/main/Outlook%20doc%20final/18.png)

7. Select 'Close' when the repair is complete.

![Image 22](https://raw.githubusercontent.com/Lalith-Adithya-k/AdithyaTechWorks/main/Outlook%20doc%20final/19.png)


## 4. Performance Troubleshooting

### 4.1 Clear Cache 
**Description:** Clearing the cache in Outlook refreshes stored data, resolving synchronization issues and improving performance.

1. Press the **Windows + R** keys to open the `Run` dialog box.
2. Type `appdata` in the `Run box` and press **Enter**.

![Image 23](https://raw.githubusercontent.com/Lalith-Adithya-k/AdithyaTechWorks/main/cache%201.png)

3. Go to `AppData > Local > Microsoft > Outlook > RoamCache' folder.

![Image 24](https://raw.githubusercontent.com/Lalith-Adithya-k/AdithyaTechWorks/main/Screenshot%202024-09-30%20154120.png)


4. Press **Ctrl + A** to select all files in the folder.
5. Press **Delete** to delete all the cache files.

### 4.2 Clear Temporary Files

**Description:** Clearing temporary files frees up disk space and enhances system performance by removing unnecessary data accumulated over time.

1. Press the **Windows + R** keys to open the Run dialog box.
2. Type `temp` in the `Run` box and press **Enter**.

![Image 25](https://raw.githubusercontent.com/Lalith-Adithya-k/AdithyaTechWorks/main/Screenshot%202024-09-30%20161113.png)

3. Press **Ctrl + A** to select all files.
4. Press **Delete** to delete all the temp files.

## 5. Escalation Guidelines
1. If the issue remains unresolved after performing basic troubleshooting, escalate the case to Level 2 support.
2. Provide detailed notes on the steps taken and any error messages encountered.

## 6. Conclusion
This manual provides solutions to common Level 1 support issues in Microsoft Outlook. Always attempt these basic troubleshooting steps before escalating the problem to higher support levels.
