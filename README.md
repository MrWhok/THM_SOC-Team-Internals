## Table of Contents
1. [SOC L1 Alert Triage](#soc-l1-alert-triage)
2. [SOC L1 Alert Reporting](#soc-l1-alert-reporting)
3. [SOC Workbooks and Lookups](#soc-workbooks-and-lookups)

## SOC L1 Alert Triage
### Event and Alerts
1. What is the number of alerts you see in the SOC dashboard (opens in new tab)?

    The answer is `5`.

2. What is the name of the most recent alert you see?

    The answer is `Double-Extension File Creation`.

### Alert Properties
1. What was the verdict for the "Unusual VPN Login Location" alert?

    The answer is `False Positive`.

2. What user was mentioned in the "Unusual VPN Login Location" alert?

    The answer is `M.Clark`.

### Alert Prioritisation
1. Should you first prioritise medium over low severity alerts? (Yea/Nay)

    The answer is `Yea`.

2. Should you first take the newest alerts and then the older ones? (Yea/Nay)

    The answer is `Nay`.

3. Assign yourself to the first-priority alert and change its status to In Progress.
The name of your selected alert will be the answer to the question.

    The answer is `Potential Data Exfiltration`.

### Alert Triage
1. Which flag did you receive after you correctly triaged the first-priority alert?

    The answer is `THM{looks_like_lots_of_zoom_meetings}`.

2. Which flag did you receive after you correctly triaged the second-priority alert?

    The answer is `THM{how_could_this_user_fall_for_it?}`.

3. Which flag did you receive after you correctly triaged the third-priority alert?

    The answer is `THM{should_we_allow_github_for_devs?}`.

## SOC L1 Alert Reporting
### Alert Funnel
1. What is the process of passing suspicious alerts to an L2 analyst for review?

    The answer is `Alert Escalation`.

2. What is the process of formally describing alert details and findings?

    The answer is `Alert Reporting`.

### Reporting Guide
1. According to the SOC dashboard (opens in new tab), which user email leaked the sensitive document?

    The answer is `m.boslan@tryhackme.thm`.

2. Looking at the new alerts, who is the "sender" of the suspicious, likely phishing email?

    The answer is `support@microsoft.com`.

3. Open the phishing alert, read its details, and try to understand the activity.
Using the Five Ws template, what flag did you receive after writing a good report?
Note: Do not change the status yet, fill in the Analyst Comment and click Save.

    The answer is `THM{nice_attempt_faking_microsoft_support}`.

### Escalation Guide
1. Who is your current L2 in the SOC dashboard (opens in new tab) that you can assign (escalate) the alerts to?

    The answer is `E.Fleming`.

2. What flag did you receive after correctly escalating the alert from the previous task to L2? Note: If you correctly escalated the alert earlier, just edit the alert and click "Save" again.

    The answer is `THM{good_job_escalating_your_first_alert}`.

3. Now, investigate the second new alert in the queue and provide a detailed alert comment.
Then, decide if you need to escalate this alert and move on according to the process.
After you finish your triage, you should receive a flag, which is your answer!

    The answer is `THM{looks_like_webshell_via_old_exchange}`.

### SOC Communication
1. Should you first try to contact your manager in case of a critical threat (Yea/Nay)?

    The answer is `Nay`.

2. Should you immediately contact your L2 if you think you missed the attack (Yea/Nay)?

    The answer is `Yea`.


## SOC Workbooks and Lookups
### Assets and Identities
1. Looking at the identity inventory, what is the role of R.Lund at the company?

    The answer is `US Financial Adviser`.

2. Checking the asset inventory, what data does the HQ-FINFS-02 server store?

    The answer is `Financial records`.

3. Finally, does the file sharing from the scenario look legitimate and expected? (Yea/Nay)

    The answer is `Yea`.

### Network Diagrams
1. According to the network diagram, which service is exposed on the TCP/10443 port?

    The answer is `VPN`.

2. Now, which subnet would the server behind 172.16.15.99 IP belong to?

    The answer is `Database Subnet`.

3. Finally, does the scenario look like a True Positive (TP) or False Positive (FP)?

    The answer is `TP`.

### Workbooks Theory
1. Which SOC role would use workbooks the most (e.g. SOC Manager)?

    The answer is `SOC L1 Analyst`.

2. What is the process of gathering user, host, or IP context using TI and lookups?

    The answer is `Enrichment`.

3. Looking at the workbook example, what platform is used as an identity inventory source?

    The answer is `BambooHR`.

### Workbook Practice
1. What flag did you receive after completing the first workbook?

    The answer is `THM{the_most_common_soc_workbook}`.

2. What flag did you receive after completing the second workbook?

    The answer is `THM{be_vigilant_with_powershell}`.

3. What flag did you receive after completing the third workbook?

    The answer is `THM{asset_inventory_is_essential}`.