# After the Emergency Maintenance is Complete 

Last Modified: `@@LastModified`

---

## When the ST Confirms Mitigation

After the work is complete, the AGC AzComms operator will need to do a few housekeeping tasks to close out the Emergency Maintenance request. 

After the ST updates the status of IcM ticket #3 to "Mitigated" and it is Resolved, the operator will then need to wrap up the comms:

1. **HS IcM**: The HS SN IcM request (ticket #1) needs to be mitigated and resolved. 
2. **ACM**: Close the Event used for the customer communications. 
3. **ADO**: Both the original SN ADO card and the Reconvene/Outage ADO card need to be moved to the Closed status column. 
4. **LS IcM**: Both the LS SN IcM ticket (ticket #2) and the LS IcM ticket for the Reconvene (ticket #3) need to be mitigated and resolved. 

>[!NOTE]
>If additional impacts occurred during the Emergency Maintenance, then a customer-facing Post Incident Response (PIR) is also required (see the "[Post Incident Response](https://eng.ms/docs/cloud-ai-platform/azure-edge-platform-aep/cai-silver/experience-silver-/silver-problem-management/azure-outage-communications/frontlinelivesite/sendingthepir/sending-post-incident-review)" page on the EngHub for the requirements and timelines for customer-facing PIRs).
