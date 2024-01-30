# (Optional) Hands-on Lab: Committing and Rolling back a Transaction

A transaction is simply a sequence of operations performed using one or more SQL statements as a single logical unit of work. A database transaction must be ACID (Atomic, Consistent, Isolated and Durable). The effects of all the SQL statements in a transaction can either be applied to the database using the COMMIT command or undone from the database using the ROLLBACK command.

In this lab, you will learn some commonly used TCL (Transaction Control Language) commands of SQL through the creation of a stored procedure routine. You will learn about COMMIT, which is used to permanently save the changes done in the transactions in a table, and about ROLLBACK, which is used to undo the transactions that have not been saved in a table. ROLLBACK can only be used to undo the changes in the current unit of work.

To launch the lab, check the box below indicating "I agree to use this app responsibly.",  and then click on the "Launch App" button. This will open up the lab environment in a new browser tab.

This lab uses IBM Skills Network Labs (SN Labs), which is a virtual lab environment used in this course. Upon clicking "Launch App" your Username and Email will be passed to Skills Network Labs and will only be used for communicating important information to enhance your learning experience, in accordance with IBM Skills Network Privacy policy.

To view the lab instructions in a different browser tab, [click here](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-DB0201EN-SkillsNetwork/labs/v8/mod6_acid_trans_rollback.md.html). 