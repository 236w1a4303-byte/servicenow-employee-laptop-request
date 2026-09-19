# ServiceNow-Based Employee Laptop Request Application

## 1. Project Overview

This project is developed using **ServiceNow** to automate and manage employee laptop requests through a centralized request management system.

The application provides a structured process where employees can submit laptop requests, managers can review and approve them, and the IT team can process and fulfill the approved requests.

The system helps reduce manual email-based requests and provides better visibility, tracking, validation, and notification throughout the request lifecycle.

---

## 2. Business Objective

The main objectives of this project are:

* Centralize all employee laptop requests in ServiceNow.
* Provide **Basic** and **Advanced** laptop request types.
* Implement a **manager approval process**.
* Prevent duplicate laptop requests from the same employee within the same year.
* Track the request status from submission to fulfillment.
* Automate notifications for important request activities.
* Provide better visibility to employees, managers, and the IT team.

---

## 3. Request Lifecycle

The laptop request follows a structured lifecycle:

**Requested → Pending Approval → Approved → In Progress → Fulfilled → Closed**

If the manager does not approve the request, the request follows the rejection process instead of moving to the approved stage.

---

## 4. Technologies Used

* **ServiceNow**
* **Service Catalog**
* **Record Producer**
* **Flow Designer**
* **Business Rules**
* **ACL (Access Control Lists)**
* **Approval Management**
* **Notifications**
* **Update Sets**

---

## 5. Key Features

### 5.1 Laptop Request Form

Employees can submit a laptop request by providing the required employee, laptop, and business-related information.

### 5.2 Basic / Advanced Request Type

The application provides two laptop usage types:

* **Basic**
* **Advanced**

This helps the IT team understand the employee's laptop requirement.

### 5.3 Manager Approval

After an employee submits a request, it is sent to the respective manager for approval.

The manager can review the request and approve or reject it.

### 5.4 Approval Status Tracking

The system tracks the approval and processing status of each laptop request.

This provides visibility into the current stage of the request.

### 5.5 Duplicate Request Validation

The application validates whether the employee has already submitted a laptop request within the same year.

This helps prevent duplicate laptop requests.

### 5.6 Automated Email Notifications

Notifications are automatically sent to the relevant users during important stages of the request process, such as request submission, approval, rejection, and fulfillment.

### 5.7 Update Set Deployment

App

