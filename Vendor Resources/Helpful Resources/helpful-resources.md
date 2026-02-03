# Helpful Resources

`@@LastModified` ||

---

## Background and Training Materials

Background and more detailed training information can be found here: 
- Data handling guidelines: [Program Updated Guidance (PUG)](https://microsoft.sharepoint.com/:b:/r/teams/CST_NationalSecurity/Shared%20Documents/National%20Security%20Data%20Governance/Program%20Updated%20Guidance.pdf?csf=1&web=1&e=fpeVa3)
- ACK’D App: https://aka.ms/ACKD 
- Training slide decks: 
    - [Service Notification (SN) Introduction](https://microsoft.sharepoint.com/:p:/r/teams/AzureCXPAirGapJEDICXPTeam/Team%20Documents/Service%20Notification%20Training/BasicsOfSNs.pptx?d=w7de7f3a1e7024999a1e55e3d2260f680&csf=1&web=1&e=S7Gs1L) (slides) 
    - [SNs Beyond the Basics](https://microsoft.sharepoint.com/:p:/r/teams/AzureCXPAirGapJEDICXPTeam/Team%20Documents/Service%20Notification%20Training/SN_BeyondTheBasics.pptx?d=w868ef84ee7e6492fab7dd5c609ca49e6&csf=1&web=1&e=jvgGvY) (slides) 
    - [SNs Beyond the Basics 2](https://microsoft.sharepoint.com/:p:/r/teams/AzureCXPAirGapJEDICXPTeam/Team%20Documents/Service%20Notification%20Training/SN_BeyondTheBasics2.pptx?d=w4ead1e8f76264816b0887a25d9ef3d4e&csf=1&web=1&e=McT2DQ) (slides) 
    - [Service Notification Updates & Reminders](https://microsoft-my.sharepoint.com/:p:/g/personal/jedav_microsoft_com1/ERlUMT6GcClDu7XYikzqOG4Bo_kQWYw2IRk2ZhJilg6sRA?e=QLBEJs) (slides)
    - [Service Notification Training: ADO & Automation](https://microsoft-my.sharepoint.com/:p:/g/personal/jedav_microsoft_com1/EaF7Fw8SoudEvWE7IJfKxnIBnUO-fHtBzkJX3LVUuBCYFg?e=evxQra) (slides)
    - [Emergency Service Notifications](https://microsoft-my.sharepoint.com/:p:/g/personal/jedav_microsoft_com1/EValYJNDUMFFutyDOrJHPy8B9gCp6eF-1y0wHw8DVfspVQ?e=FwccG2) (slides)
    - [Training video recordings](https://microsoft.sharepoint.com/:f:/r/teams/AzureCXPAirGapJEDICXPTeam/Team%20Documents/Service%20Notification%20Training?csf=1&web=1&e=2Chuw0)

## Tools Needed

To send a SN you will need access to both low and High Side (HS) resources.

### On the High Side (HS): 
- Azure Communications Manager (ACM): To post communications to external customers.
- Cloud Transfer Service Portal (CTS Portal): To copy/paste information gathered from various sources across the networks.
- HS IcM: To obtain impacted external customer details. 

### On the Low Side (LS): 
- **Microsoft Teams**: Service Notification requests are posted in the shared Teams channel [SN and Publish IcMs (Sev 3, 4)](https://teams.microsoft.com/l/channel/19%3Af5333433a4b94a149009bfd95438a73b%40thread.tacv2/SN%20and%20Publish%20IcMs%20(Sev%203%2C%204)?groupId=297fb1a7-1622-4824-8fe4-f461fb04b98b&tenantId=72f988bf-86f1-41af-91ab-2d7cd011db47), and much of the communication with the engineering team occurs in Teams. 
- **LS IcM**: Service Notification tickets are created and tracked on this [IcM Board](https://portal.microsofticm.com/imp/v3/incidents/search/advanced). 
- **Azure DevOps (ADO)**: An ADO card is created for each IcM SN ticket on this [ADO Service Notifications Team Board](https://dev.azure.com/AzureCRE-AGC/Service%20Notifications/_boards/board/t/Service%20Notifications%20Team/Service%20Notifications), and the AzComms work is documented in those cards.
- **AGC Lookup Tool**: Use the PowerBI [AGC Lookup Tool](https://msit.powerbi.com/groups/me/reports/ba9f535e-36b4-420c-bc7c-55b5ff34e20d/ReportSectionaed44c157e7ed32d6336?ctid=72f988bf-86f1-41af-91ab-2d7cd011db47&experience=power-bi) verify if a requestor is tented. 
- **Service Tree**: Use the [Service Tree tool](https://microsoftservicetree.com/home#) to look up the ownership of Azure services and products in order to complete the SN.
- **Cloud Transfer Service Portal (CTS Portal)**: Use the [CTS Portal](https://ctsportal.trafficmanager.net/pastes) to copy/paste information gathered from various sources across the networks. 
- **Microsoft Word**: While creating early drafts of communications, operators should use MS Word’s editing tools - including Copilot and the Read Aloud feature - to confirm proper spelling, grammar, and punctuation.

## About Time

All times in ADO should be recorded in EST. However, all times in ACM are saved in UTC format. 

The operator will have to do the conversion when moving between the LS ADO card and the HS ACM. Copilot can be used for this. 
