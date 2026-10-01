# Streamlining IT Procurement: Automating Standard Laptop Orders with Flow Designer

## Project Overview

This project focuses on automating the procurement and configuration process for standard laptop orders using **ServiceNow Flow Designer**. The main purpose is to reduce manual work, improve task assignment, and ensure that laptop configuration begins promptly after request approval.

## Problem Statement

The existing IT procurement process involves manual activities that can cause delays in handling standard laptop requests. Laptop configuration may be overlooked or delayed, resulting in longer user waiting times and inefficient use of IT resources.

## Objective

The main objectives of this project are:

* Automate the standard laptop procurement workflow.
* Automatically create configuration tasks after approval.
* Assign tasks to the **Hardware** group.
* Reduce manual intervention and errors.
* Improve IT resource utilization.
* Provide a faster and smoother user experience.

## Technologies Used

* **ServiceNow**
* **Flow Designer**
* **Service Catalog**
* **Catalog Task**
* **Maintain Items**
* **Approval Workflow**
* **Assignment Group**

## Project Workflow

The project follows this process:

**User Requests Laptop → Approval → Flow Designer Trigger → Catalog Task Created → Hardware Assignment → Laptop Configuration**

## Main Modules

### 1. Flow Designer

A flow named **"Standard Laptop Task"** is created to automate the process.

### 2. Service Catalog

The **Standard Laptop** catalog item allows users to place laptop requests.

### 3. Approval

The request goes through the approval process before the configuration task is generated.

### 4. Catalog Task

After approval, the system automatically creates a Catalog Task with the required details.

### 5. Hardware Assignment

The generated task is automatically assigned to the **Hardware** assignment group.

## Task Configuration

The automated task contains:

* **Short Description:** Laptop need to Configured
* **Description:** Laptop need to Configured
* **Assignment Group:** Hardware
* **Approval:** Approved

## Project Demonstration

The demonstration starts by placing a Standard Laptop order through the Service Catalog. The request is then approved. After approval, Flow Designer automatically creates a Catalog Task. The task can be viewed under the Requested Item and verified for its description and Hardware assignment.

## Benefits

* Reduces manual intervention.
* Minimizes errors.
* Speeds up laptop configuration.
* Improves task allocation.
* Reduces user waiting time.
* Improves IT procurement efficiency.

## Future Enhancements

Possible future improvements include:

* Email and system notifications.
* SLA tracking.
* IT procurement dashboards.
* Approval escalation.
* Automation for other hardware such as monitors and accessories.

## Conclusion

The project demonstrates how ServiceNow Flow Designer can automate the standard laptop procurement process. By automatically creating and assigning configuration tasks after approval, the system reduces manual effort, improves resource utilization, and provides a more efficient procurement experience.
