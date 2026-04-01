## Table of Contents
1. [SOC L1 Alert Triage](#soc-l1-alert-triage)
2. [SOC L1 Alert Reporting](#soc-l1-alert-reporting)

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