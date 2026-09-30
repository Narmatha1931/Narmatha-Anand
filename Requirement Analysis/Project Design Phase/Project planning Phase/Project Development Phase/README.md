# Project Development Phase

## Salesforce Development

The Student Enrollment & Course Management System was developed using Salesforce.

## 1. Student Object

The Student object is used to store student information.

Key fields:
- Student Name
- Register Number
- Email
- Phone

## 2. Course Object

The Course object is used to store course information.

Key fields:
- Course Name
- Course Code
- Instructor
- Duration

## 3. Enrollment Object

The Enrollment object connects students with courses.

Key fields:
- Student
- Course
- Enrollment Date
- Status

## 4. Relationships

Student and Course information are connected through the Enrollment object.

Student → Enrollment → Course

## 5. Automation

Salesforce Flow is used to automate enrollment-related processes and update required information.

## 6. Security Setup

Profiles and object permissions are configured for different users.

- Admin – Full access
- Enrollment Officer – Create and Update Enrollment records
- Instructor – Read-only access to assigned Enrollment records

## 7. Reports and Dashboards

Reports and dashboards are used to monitor student enrollment and course information.

## Development Evidence

Screenshots of Salesforce configuration, objects, fields, flows, security settings, reports, and dashboards will be added to this folder.
