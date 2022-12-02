# Upgrade Log
## [v2.2.60] - 2022-11-09

## Fix
* Fix a problem where some pg syntax parsing fails.

## Update
* Add table file import function.
* Add database TDengine support.



## [v2.2.59] - 2022-09-28

## Fix
* Fix the bug that the execution of work order fails but the status is really successful.
* Fix the bug that adding comments in SQL statement causes parsing failure.
* Fix the problem that the return of specific fields may cause the program to crash.
* Fix the problem that mongoDB low version synchronization fails.



## Update
* Refine permission granularity, support finer granularity operation permission setting.
* Optimize table display, support detail view and one-click copy.
* Application Management-Functional Settings Support to enable "Disable page copy data".
* System Settings - Notification Add "SMS notification setting" function.
* Data source supports SSH connection.
* Audit log is added to audit management.
* Personal Center - Security Settings - Two-step Authentication Add SMS authentication method.
* Personal Center-Workspace, you can check personal execution/audit logs and work order records, and support downloading and exporting.


## [v2.0.18] - 2021-10-27

## Fix
* Fix the bug that Oracle blocks in certain cases.
* Fix the bug of special character escaping in MySQL.
* Fix a bug that some field length definitions are not valid for table structure synchronization.




## Update
* Add metadata node and detail display for data query.
* The data query interface supports theme setting.
* Add platform message module.
* Add user avatar setting.
* Add online remote upgrade function.
* Add LDAP login configuration to System Management -> Login Settings.
* The login page supports LDAP login.





## [v2.0.17] - 2021-08-19
## Fix
* Fix the bug that MySQL policy desensitization settings are not working.
* Change MyCat in-memory paging to paging with limit statement.
* MySQL DML update using auto transaction mode autocommit=1
* Upgrade Oracle table build statement to show full content.
* Optimize role setting permission color display.
* Fix the problem of database synchronization failure under some MongoDB authority scenarios.
* Repair the bug of unresponsive open file button in work order pop-up window.
* Fix the problem that asynchronous query results are not displayed.

## Update
* Add the function of turning on/off two-factor authentication for login.
* System-security settings support defining whitelist and blacklist network segments and ip addresses (CIDR).
* MySQL work order supports data backup function.
* Support opening work order approval policy on project work order, support query, export and asynchronous work order types. Support immediate empowerment requirements.
* Add the three authority mode and add the roles of system administrator, security administrator and audit administrator. The original administrator role is unchanged and upgraded to super administrator.
* Add "Test Connection" button for new data sources.
* Add system backup function, supporting local backup and remote backup and recovery.
* Add "Test Connection" button for new data source.





## [v2.0.16] - 2021-05-04

## FIx
* Fix the problem of MySQL work order execution failure.
* Fix the problem of primary key conflict in work order query log.
* Fix the bug of MySQL table structure display
* Fix the bug that policy desensitization fails in some cases.

## Update
* Add the security function of two-factor authentication.
* Add start-up banner
* Support webhook notification for project approval
* Support query and export through work order approval
