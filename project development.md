ServiceNow Setup – Open ServiceNow and access Flow Designer under Process Automation.
Flow Creation – Create a new Flow and name it “Standard Laptop Task.” Set the application as Global and select System User as the Run As user.
Trigger Configuration – Add a Service Catalog trigger so the workflow can respond to the standard laptop request process.
Catalog Task Creation – Add the Create Catalog Task action to automatically generate a task for the requested laptop.
Task Configuration – Map the Requested Item Record to the Request Item field and configure the Catalog Task details.
Task Description – Set the short description and description to “Laptop need to Configured.”
Assignment Group – Set the Assignment group field to Hardware so the configuration task reaches the appropriate team.
Approval Condition – Set the Approval field to Approved so the task is processed after approval.
Save and Activate – Save the Flow and activate it so it becomes available for the Standard Laptop request process.
Flow Assignment – Open Maintain Items, select Standard Laptop, remove the remaining automations if required, and associate the newly created Flow.
Testing – Place a Standard Laptop order through the Service Catalog, approve the request, and check the Requested Item and Catalog Tasks sections.
Verification – Verify that the Catalog Task is created with the correct description and assigned to the Hardware group.
