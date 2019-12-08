# Basic Brute Force Detection
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
### Description  																																					   | ### Data Availability
Uses a simple threshold for Windows Security Logs to alert if there are a large number of failed logins, and at least one successful login from the same source.	   | Bad
---------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------
### Category																							                                                               | ### MITRE ATT&CK Tactics (Click for Detail)
Account Compromise, Scanning																																		   | [<i class="icon-refresh"></i>Credential Access](#Credential-Access)
---------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------																																												   |
Discovering real credentials is a key component for any attacker. While there are many approaches for doing that, a time honored way is to find 					   | ### MITRE ATT&CK Techniques (Click for Detail)
weak passwords by just trying hundreds of common passwords. Particularly as most environments use Active Directory as their central storage 						   | [<i class="icon-refresh"></i>Brute Force](#Brute-Force)
respository for credentials, looking for brute force activity in Windows Security logs should be a component of any security strategy.								   |
---------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------			
### Alert Volume																																					   | ### MITRE ATT&CK Groups (Click for Detail)
Low 																																								   | [<i class="icon-refresh"></i>APT3](#APT3) [<i class="icon-refresh"></i>APT33](#APT33) [<i class="icon-refresh"></i>APT41](#APT41) [<i class="icon-refresh"></i>Dragonfly 2.0](#Dragonfly-2.0) [<i class="icon-refresh"></i>Lazarus Group](#Lazarus-Group) [<i class="icon-refresh"></i>Leafminer](#Leafminer) [<i class="icon-refresh"></i>OilRig](#OilRig) [<i class="icon-refresh"></i>Turla](#Turla) 
---------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------
### SPL Difficulty																																				       | ### Data Sources
Basic																																								   | Windows Security Logs Linux Auth Logs Cisco ISE Okta Duo
---------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------		
                                                                                                                                                                       |
Bad																																									   |
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|																																									

### MITRE ATT&CK Tactics
[<i class="icon-refresh"></i>Credential Access](#"Credential Access")
