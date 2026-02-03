# Different Tools Explained

Last Modified: `@@LastModified`

---

## Which Tool to Use and When?  

The AGC AzComms team uses a collection of tools to complete the SN process. Each tool has a specific purpose, based on its functionality and the access that different teams have to it. 

Operators working on SNs should follow these guidelines in order to ensure the right people have the right information available to them when they need it: 

### IcM 

Incident Management System (IcM) is Microsoft's internal ticketing system for managing Live Site incidents and on-call rotations for Microsoft Services.

AGC AzComms teams receive SN requests (aka "tickets") in IcM from the Service Teams (STs). 
Automation in IcM creates an ADO card for every LS IcM ticket that is assigned to the AGC AzComms team. 

**IcM is Used for**: 

STs primarily work on SNs through IcM and Teams, so the communications between the AGC AzComms team and the STs mostly occur in those tools. Use it for: 

- Documenting decisions between the AGC AzComms team and the ST members
- Saving a copy of the final - approved - draft of the SN customer message prior to being published 
- Documenting issues and escalations

### Teams 

Teams is a Microsoft application that creates a shared workspace that includes chat, meetings, calling, video conferencing, file sharing and storage, and collaboration. The AGC AzComms team uses Teams for all real-time communications between SN stakeholders - mostly using the Chat functionality. 

**Teams is Used for**: 

Teams is the best way to get quick answers to urgent questions. Use it for: 

- Asking questions of the ST PM related to the scope of the SN 
- Coordinating approvals with the ST PM and the CSM 
- Updating stakeholders of status issues 
- Handling escalations 

### ADO 

Azure DevOps is a collection of Microsoft services and technologies for agile planning, continuous integration, continuous delivery, and monitoring of applications.

AGC AzComms teams use ADO for their _internal_ work / task management and tracking. Data in ADO is used verify our SLA metrics and for quality assurance purposes. 

The ADO SN Board allows us to visualize the status of the various SN requests that have been received as they move through the SN process.

ADO cards are automatically created for every IcM ticket that is assigned to the AGC AzComms team. The automation copies all relevant info from IcM to ADO at the time the card is created. 

**ADO is Used for**: 

ADO is mostly for the AGC AzComms team's internal use. Use it for: 

- Collecting all the information related to the SN request 
- Creating the SN draft
- Documenting the approvals (date/time requested, date/time approved)
- Tracking the request's progress from start to finish 

**If the automation is down**: 

- The operator should notify the CSM in Teams, so they can get the automation back up and re-run the failed ADO card creation. 
- If the automation can't be restarted right away, the operator may need to manually create the ADO card based on the data in the IcM ticket. 

>[!NOTE]
>The automation does not "dynamically" sync updates between the ADO card and the original LS IcM ticket. 
