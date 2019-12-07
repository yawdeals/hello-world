# Basic Brute Force Detection

|### Description
|Uses a simple threshold for Windows Security Logs to alert if there are a large number of failed logins, and at least one successful login from the same source.
| :---
|### Category
|Account Compromise, Scanning
| :---
|### Security Impact
|Discovering real credentials is a key component for any attacker. While there are many approaches for doing that, a time honored way is to find weak passwords by just trying hundreds of common passwords. 
|Particularly as most environments use Active Directory as their central storage respository for credentials, looking for brute force activity in Windows Security logs should be a component of any 
|security strategy.
| :---
|### Alert Volume
|Low
| :---
|###SPL Difficulty
|Basic
|
