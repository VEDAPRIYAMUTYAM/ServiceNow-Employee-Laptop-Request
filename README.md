# ServiceNow-Based Employee Laptop Request Application

A ServiceNow application that automates the employee laptop request process from submission to manager approval.

## 🚀 Features

* Employee laptop request submission
* Basic and Advance request types
* Duplicate request prevention
* Manager approval workflow
* Automated email notifications
* Approved/Rejected request status
* Role-based access using ACLs
* Service Catalog integration
* Update Set-based deployment

## 🛠️ Technologies

* ServiceNow
* Service Catalog
* Record Producer
* Flow Designer
* Business Rules
* JavaScript / GlideRecord
* ACLs
* Roles & Groups
* Update Sets

## 🔄 Workflow

```text
Employee
   ↓
Laptop Request
   ↓
Validation
   ↓
Pending Approval
   ↓
Manager Approval
   ├── Approved → Status: Approved
   └── Rejected → Status: Rejected
```

## 🔐 Security

The application uses role-based access control with:

* `it_employee`
* `it_manager`

ACLs control employee and manager access to laptop request records.

## 📦 Deployment

The complete application configuration was captured in the **HR Onboarding Application** Update Set.

* Update Set Preview: ✅ Successful
* Updates: **83**
* Collisions: **0**
* Commit: ✅ Successful
* XML export: ✅ Completed

## 🧪 Testing

The application was tested for:

* Request creation ✅
* Duplicate request prevention ✅
* Manager approval ✅
* Request rejection ✅
* Employee access control ✅
* Manager access restrictions ✅
* Email notifications ✅

## 📌 Project Status

**Completed ✅**

## 👩‍💻 Author

**Veda Priya Mutyam**
B.Tech CSE – Artificial Intelligence & Machine Learning
VR Siddhartha Engineering College, Vijayawada
