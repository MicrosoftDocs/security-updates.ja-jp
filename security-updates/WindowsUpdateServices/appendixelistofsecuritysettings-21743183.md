---
TOCTitle: 'Appendix E: List of Security Settings'
Title: 'Appendix E: List of Security Settings'
ms:assetid: '0b284e97-679b-4d0f-83e5-99e68bce5fb9'
ms:contentKeyID: 21743183
ms:mtpsurl: 'https://technet.microsoft.com/ja-jp/library/Dd939800(v=WS.10)'
---

Appendix E: List of Security Settings
=====================================

This appendix lists the recommended security settings for WSUS. The recommendations are categorized into settings for Windows Server, IIS, and SQL Server.

Windows Server
--------------

The following are security recommendations for Windows Server with WSUS.

### Audit policy

Enable audit events to ensure that adequate logs are collected for system activities.

### Audit policy settings

<p> </p>
<table style="border:1px solid black;">
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th>Option</th>
<th>Security setting</th>
<th>Setting rationale</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><p>Audit account logon events</p></td>
<td style="border:1px solid black;"><p>Success, Failure</p></td>
<td style="border:1px solid black;"><p>Auditing for successful and failed logon events provides useful data regarding password brute-forcing attempts.</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p>Audit account management</p></td>
<td style="border:1px solid black;"><p>Success, Failure</p></td>
<td style="border:1px solid black;"><p>Auditing for successful and failed account management events tracks management activities.</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p>Audit directory service access</p></td>
<td style="border:1px solid black;"><p>No Auditing</p></td>
<td style="border:1px solid black;"><p>This is only important for domain controllers running the Active Directory Domain Services (AD DS).</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p>Audit logon events</p></td>
<td style="border:1px solid black;"><p>Success, Failure</p></td>
<td style="border:1px solid black;"><p>Auditing for successful and failed logon events provides useful data regarding password brute-forcing attempts.</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p>Audit object access</p></td>
<td style="border:1px solid black;"><p>No Auditing</p></td>
<td style="border:1px solid black;"><p>Auditing object access is unnecessary and creates many unnecessary logs for WSUS activity.</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p>Audit policy change</p></td>
<td style="border:1px solid black;"><p>Success, Failure</p></td>
<td style="border:1px solid black;"><p>Auditing for successful and failed policy changes tracks management activities.</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p>Audit privilege use</p></td>
<td style="border:1px solid black;"><p>Success, Failure</p></td>
<td style="border:1px solid black;"><p>Auditing for successful and failed privilege use tracks administrator activities.</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p>Audit process tracking</p></td>
<td style="border:1px solid black;"><p>No Auditing</p></td>
<td style="border:1px solid black;"><p>Process-tracking events are unnecessary for WSUS implementations.</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p>Audit system events</p></td>
<td style="border:1px solid black;"><p>Success, Failure</p></td>
<td style="border:1px solid black;"><p>Auditing for successful and failed system events tracks system activities.</p></td>
</tr>
</tbody>
</table>
  
### Security options
  
Configure Windows Server security settings to help ensure optional security and functionality.
  
### Security options settings

<p> </p>
<table style="border:1px solid black;">
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th>Option</th>
<th>Security setting</th>
<th>Setting rationale</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><p>Accounts: Administrator account status</p></td>
<td style="border:1px solid black;"><p>Enabled</p></td>
<td style="border:1px solid black;"><p>Because it is necessary to have an administrator, the administrator account should be enabled for authorized users.</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p>Accounts: Guest account Status</p></td>
<td style="border:1px solid black;"><p>Disabled</p></td>
<td style="border:1px solid black;"><p>Because it is risky to have guest accounts, the guest account should be disabled unless specifically required.</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p>Accounts: Limit local account use of blank passwords to console logon only</p></td>
<td style="border:1px solid black;"><p>Enabled</p></td>
<td style="border:1px solid black;"><p>Accounts with blank passwords significantly increase the likelihood of network-based attacks.</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p>Accounts: Rename administrator account</p></td>
<td style="border:1px solid black;"><p>Not Defined</p></td>
<td style="border:1px solid black;"><p>Renaming the administrator account forces a malicious individual to guess both the account name and password. Note that even though the account can be renamed, it still uses the same well known SID, and there are tools available to quickly identify this and provide the name.</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p>Accounts: Rename Guest account</p></td>
<td style="border:1px solid black;"><p>Not Defined</p></td>
<td style="border:1px solid black;"><p>Because the Guest account is disabled by default, and should never be enabled, renaming the account is not important. However, if an organization decides to enable the Guest account and use it, it should be renamed beforehand.</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p>Audit: Audit the access of global system objects</p></td>
<td style="border:1px solid black;"><p>Enabled</p></td>
<td style="border:1px solid black;"><p>This setting needs to be enabled for auditing to take place in the Event Viewer. The auditing setting can be set to Not Defined, Success or Failure in the Event View.</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p>Audit: Audit the use of backup and restore privilege</p></td>
<td style="border:1px solid black;"><p>Enabled</p></td>
<td style="border:1px solid black;"><p>For security reasons, this option should be enabled so that auditors will be aware of users creating backups of potentially sensitive data.</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p>Audit: Shut down system immediately if unable to log security audits</p></td>
<td style="border:1px solid black;"><p>Disabled</p></td>
<td style="border:1px solid black;"><p>Enabling this option shuts down the system if it is unable to log audits. This can help prevent missed audit events. Enabling very large log files on a separate partition helps mitigate this.</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p>Devices: Allow undock without having to log on</p></td>
<td style="border:1px solid black;"><p>Disabled</p></td>
<td style="border:1px solid black;"><p>Disabling this option ensures that only authenticated users can dock and undock computers.</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p>Devices: Allow to format and eject removable media</p></td>
<td style="border:1px solid black;"><p>Administrators</p></td>
<td style="border:1px solid black;"><p>This option is not typically useful for desktop images.</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p>Devices: Prevent users from installing printer drivers</p></td>
<td style="border:1px solid black;"><p>Enabled</p></td>
<td style="border:1px solid black;"><p>Because the Windows GDI system runs in kernel space, allowing a user to install a printer driver could lead to elevated privileges.</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p>Devices: Restrict CD-ROM access to locally logged-on user only</p></td>
<td style="border:1px solid black;"><p>Enabled</p></td>
<td style="border:1px solid black;"><p>Enabling this option prevents remote users from accessing the local CD-ROM, which may contain sensitive information.</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p>Devices: Restrict floppy access to locally logged-on user only</p></td>
<td style="border:1px solid black;"><p>Enabled</p></td>
<td style="border:1px solid black;"><p>In situations in which the server is physically secured and password authentication is required by the Recover Console, this option can be enabled to facilitate system recovery.</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p>Devices: Unsigned driver installation behavior</p></td>
<td style="border:1px solid black;"><p>Warn but allow installation</p></td>
<td style="border:1px solid black;"><p>Most driver software is signed. Administrators should not install unsigned drivers unless the origin and authenticity can be verified and the software has been thoroughly tested in a lab environment first. Because only senior administrators will be working on these systems, it is safe to leave this to their discretion.</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p>Domain controller: Allow server operators to schedule tasks</p></td>
<td style="border:1px solid black;"><p>Disabled</p></td>
<td style="border:1px solid black;"><p>The ability to schedule tasks should be limited to administrators only.</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p>Domain controller: LDAP server signing requirements</p></td>
<td style="border:1px solid black;"><p>Not Defined</p></td>
<td style="border:1px solid black;"><p>This option applies only to domain controllers.</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p>Domain controller: Refuse machine account password changes</p></td>
<td style="border:1px solid black;"><p>Disabled</p></td>
<td style="border:1px solid black;"><p>Enabling this option allows machine accounts to automatically change their passwords.</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p>Domain member: Digitally encrypt or sign secure channel data (always)</p></td>
<td style="border:1px solid black;"><p>Disabled</p></td>
<td style="border:1px solid black;"><p>If the domain controller is known to support encryption of the secure channel, this option can be enabled to protect against local network attacks.</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p>Domain member: Digitally encrypt secure channel data (when possible)</p></td>
<td style="border:1px solid black;"><p>Enabled</p></td>
<td style="border:1px solid black;"><p>Enabling this option provides the most flexibility while enabling the highest security when the server supports it.</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p>Domain member: Digitally sign secure channel data (when possible)</p></td>
<td style="border:1px solid black;"><p>Enabled</p></td>
<td style="border:1px solid black;"><p>Enabling this option provides the most flexibility while enabling the highest security when the server supports it.</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p>Domain member: Disable machine account password changes</p></td>
<td style="border:1px solid black;"><p>Disabled</p></td>
<td style="border:1px solid black;"><p>Disabling this option allows machine accounts to automatically change their passwords.</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p>Domain member: Maximum machine account password age</p></td>
<td style="border:1px solid black;"><p>30 days</p></td>
<td style="border:1px solid black;"><p>Less frequently changed passwords are easier to break than passwords that are changed more frequently.</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p>Domain member: Require strong (Windows 2000 or later) session key</p></td>
<td style="border:1px solid black;"><p>Enabled</p></td>
<td style="border:1px solid black;"><p>Enabling this option sets strong session keys for all computers running Windows 2000 or later.</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p>Interactive logon: Do not display last user name</p></td>
<td style="border:1px solid black;"><p>Enabled</p></td>
<td style="border:1px solid black;"><p>Hiding the last user name should be enabled, especially when the administrator user account is renamed. This helps prevent a passerby from determining account names.</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p>Interactive logon: Do not require CTRL+ALT+DEL</p></td>
<td style="border:1px solid black;"><p>Disabled</p></td>
<td style="border:1px solid black;"><p>The CTRL+ALT+DEL sequence is intercepted at a level lower than user mode programs are allowed to hook. Requiring this sequence at logon is a security feature designed to prevent a Trojan Horse program masquerading as the Windows logon from capturing users' passwords.</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p>Interactive logon: Message text for users attempting to log on</p></td>
<td style="border:1px solid black;"><p>[provide legal text]</p></td>
<td style="border:1px solid black;"><p>An appropriate legal and warning message should be displayed according to the Corporate Security Policy.</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p>Interactive logon: Message title for users attempting to log on</p></td>
<td style="border:1px solid black;"><p>[provide legal title text]</p></td>
<td style="border:1px solid black;"><p>An appropriate legal and warning message should be displayed according to the Corporate Security Policy.</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p>Interactive logon: Number of previous logons to cache (in case domain controller is not available)</p></td>
<td style="border:1px solid black;"><p>10 logons</p></td>
<td style="border:1px solid black;"><p>This option is usually appropriate only for laptops that might be disconnected from their domain. It also presents a security risk for some types of servers, such as application servers. If a server is compromised and domain logons are cached, the attacker may be able to use this locally stored information to gain domain-level credentials.</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p>Interactive logon: Prompt user to change password before expiration</p></td>
<td style="border:1px solid black;"><p>14 days</p></td>
<td style="border:1px solid black;"><p>Password prompts should be aligned according to the Corporate Security Policy.</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p>Interactive logon: Require Domain Controller authentication to unlock workstation</p></td>
<td style="border:1px solid black;"><p>Enabled</p></td>
<td style="border:1px solid black;"><p>Enabling this option allows a domain controller account to unlock any workstation. This should only be allowed for the local Administrator account on the computer.</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p>Interactive logon: Require smart card</p></td>
<td style="border:1px solid black;"><p>Not Defined</p></td>
<td style="border:1px solid black;"><p>If this system will not be using smart cards, this option is not necessary.</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p>Interactive logon: Smart card removal behavior</p></td>
<td style="border:1px solid black;"><p>Not Defined</p></td>
<td style="border:1px solid black;"><p>If this system will not be using smart cards, this option is not necessary.</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p>Microsoft network client: Digitally sign communications (always)</p></td>
<td style="border:1px solid black;"><p>Disabled</p></td>
<td style="border:1px solid black;"><p>For systems communicating to servers that do not support SMB signing, this option should be disabled. However, if packet authenticity is required, this can be enabled.</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p>Microsoft network client: Digitally sign communications (if server agrees)</p></td>
<td style="border:1px solid black;"><p>Enabled</p></td>
<td style="border:1px solid black;"><p>For systems communicating to servers that do support SMB signing, this option should be enabled.</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p>Microsoft network client: Send unencrypted password to third-party SMB servers</p></td>
<td style="border:1px solid black;"><p>Disabled</p></td>
<td style="border:1px solid black;"><p>If this option is enabled, then a third-party SMB server could negotiate a dialect that does not support cryptographic functions. Authentication would be performed using plain-text passwords.</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p>Microsoft network server: Amount of idle time required before suspending session</p></td>
<td style="border:1px solid black;"><p>15 minutes</p></td>
<td style="border:1px solid black;"><p>This should be set appropriately for the end-user system such that idle connections do not linger or consume resources.</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p>Microsoft network server: Digitally sign communications (always)</p></td>
<td style="border:1px solid black;"><p>Disabled</p></td>
<td style="border:1px solid black;"><p>For systems communicating to servers that do not support SMB signing, this option should be disabled. However, if packet authenticity is required, this can be enabled.</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p>Microsoft network server: Digitally sign communications (if client agrees)</p></td>
<td style="border:1px solid black;"><p>Enabled</p></td>
<td style="border:1px solid black;"><p>For systems communicating to servers that do not support SMB signing, this option should be disabled. However, if packet authenticity is required, this can be enabled.</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p>Microsoft network server: Disconnect clients when logon hours expire</p></td>
<td style="border:1px solid black;"><p>Enabled</p></td>
<td style="border:1px solid black;"><p>Enabling this option prevents users from logging on after authorized hours.</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p>Network access: Allow anonymous SID/Name translation</p></td>
<td style="border:1px solid black;"><p>Disabled</p></td>
<td style="border:1px solid black;"><p>This option is highly important for securing Windows networking. Disabling it severely restricts the abilities granted to a user connecting with a Null session.</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p>Network access: Do not allow anonymous enumeration of SAM accounts</p></td>
<td style="border:1px solid black;"><p>Enabled</p></td>
<td style="border:1px solid black;"><p>This option is highly important for securing Windows networking. Enabling this option severely restricts the abilities granted to a user connecting with a Null session. Because “Everyone” is no longer in the anonymous user’s token, access to IPC$ is disallowed. Pipes that are explicitly set to allow anonymous are inaccessible because the SMB tree connection to this share fails.</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p>Network access: Do not allow anonymous enumeration of SAM accounts and shares</p></td>
<td style="border:1px solid black;"><p>Enabled</p></td>
<td style="border:1px solid black;"><p>This option is highly important for securing Windows networking. Enabling this option severely restricts the abilities granted to a user connecting with a Null session. Because “Everyone” is no longer in the anonymous user’s token, access to IPC$ is disallowed. Pipes that are explicitly set to allow anonymous are inaccessible because the SMB tree connection to this share fails.</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p>Network access: Do not allow storage of credentials or .NET passports for network authentication</p></td>
<td style="border:1px solid black;"><p>Enabled</p></td>
<td style="border:1px solid black;"><p>Enabling this option prevents the storage of sensitive passwords in the computers’ cache.</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p>Network access: Let Everyone permissions apply to anonymous users</p></td>
<td style="border:1px solid black;"><p>Disabled</p></td>
<td style="border:1px solid black;"><p>Anonymous users should have no access to computers.</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p>Network access: Named Pipes that can be accessed anonymously</p></td>
<td style="border:1px solid black;"><p>Not Defined</p></td>
<td style="border:1px solid black;"><p>Named pipes should be restricted anonymously. Restricting named pipes breaks some intersystem processes, such as network printing.</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p>Network access: Remotely accessible registry paths</p></td>
<td style="border:1px solid black;"><p>Not Defined</p></td>
<td style="border:1px solid black;"><p>Registry paths should be restricted from remote access unless for monitoring circumstances.</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p>Network access: Shares that can be accessed anonymously</p></td>
<td style="border:1px solid black;"><p>None</p></td>
<td style="border:1px solid black;"><p>No shares should be accessed anonymously.</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p>Network access: Sharing and security model for local accounts</p></td>
<td style="border:1px solid black;"><p>Guest only—local users authenticate as Guest</p></td>
<td style="border:1px solid black;"><p>Limit all local accounts to Guest privileges.</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p>Network security: Do not store LAN Manager hash value on next password change</p></td>
<td style="border:1px solid black;"><p>Enabled</p></td>
<td style="border:1px solid black;"><p>Enabling this feature deletes the weaker LAN Manager hashes, reducing the likelihood of password attacks from sniffing the weak hash over the name or from the local SAM database file.</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p>Network security: Force logoff when logon hours expire</p></td>
<td style="border:1px solid black;"><p>Enabled</p></td>
<td style="border:1px solid black;"><p>This option should be enabled as part of the acceptable policy.</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p>Network security: LAN Manager authentication level</p></td>
<td style="border:1px solid black;"><p>Send NTLMv2 response only</p></td>
<td style="border:1px solid black;"><p>Sending LM is less secure than NTLM, and should only be enabled if the system will communicate with computers running Windows 98 or Windows 95. Additionally, use NTLMv2 only; however, computers running Windows 98, Windows 95, or unpatched Windows NT4.0 will not be able to communicate with servers running NTLMv2.</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p>Network security: LDAP client signing requirements</p></td>
<td style="border:1px solid black;"><p>Negotiate signing</p></td>
<td style="border:1px solid black;"><p>Require signing when authenticating to third party LDAP servers. This prevents attacks against rogue LDAP servers and clear-text submission of passwords over the network.</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p>Network security: Minimum session security for NTLM SSP-based (including secure RPC) clients</p></td>
<td style="border:1px solid black;"><p>Require NTLMv2 session security</p></td>
<td style="border:1px solid black;"><p>The NTLM hashes contain weaknesses that attacks may exploit. When enabled, these requirements strengthen the authentication algorithms for Windows.</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p>Network security: Minimum session security for NTLM SSP-based (including secure RPC) servers</p></td>
<td style="border:1px solid black;"><p>Require NTLMv2 session security</p></td>
<td style="border:1px solid black;"><p>The NTLM hashes contain weaknesses that attacks may exploit. When enabled, these requirements will strengthen the authentication algorithms for Windows.</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p>Recovery console: Allow automatic administrative logon</p></td>
<td style="border:1px solid black;"><p>Disabled</p></td>
<td style="border:1px solid black;"><p>If automatic administrative logon is enabled, then a malicious user that has console access could simply restart the computer and gain administrative privileges. However, an organization may enable this feature if the computer is a physically secure server, allowing access to the system if the administrator password is forgotten.</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p>Recovery console: Allow floppy copy and access to all drives and all folders</p></td>
<td style="border:1px solid black;"><p>Disabled</p></td>
<td style="border:1px solid black;"><p>The recovery console can be used as an attack method to gain access to SAM database files offline; therefore, this option should be enabled to prevent those files from being copied to a floppy disk.</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p>Shutdown: Allow system to be shut down without having to log on</p></td>
<td style="border:1px solid black;"><p>Disabled</p></td>
<td style="border:1px solid black;"><p>This option is used to prevent users without valid accounts from shutting down the system, and is a good precautionary measure.</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p>Shutdown: Clear virtual memory pagefile</p></td>
<td style="border:1px solid black;"><p>Disabled</p></td>
<td style="border:1px solid black;"><p>Clearing the memory pagefile at shutdown can help prevent offline analysis of the file, which might contain sensitive information from system memory, such as passwords. However, in situations in which the computer is physically secured, this can be enabled to reduce time required for system restarts.</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p>System cryptography: Force strong key protection for user keys stored on the computer</p></td>
<td style="border:1px solid black;"><p>User is prompted when the key is first used</p></td>
<td style="border:1px solid black;"><p>Protecting local cryptographic secrets helps prevent privilege escalation across the network, once access to one system is obtained.</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p>System cryptography: Use FIPS compliant algorithms for encryption, hashing, and signing</p></td>
<td style="border:1px solid black;"><p>Not Defined</p></td>
<td style="border:1px solid black;"><p>Require stronger, standard, and compliant algorithms for encryption, hashing, and signing.</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p>System Objects: Default owner for objects created by members of the Administrators group</p></td>
<td style="border:1px solid black;"><p>Administrators group</p></td>
<td style="border:1px solid black;"><p>Administrators should only have access to the created file.</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p>System objects: Require case insensitivity for non-Windows subsystems</p></td>
<td style="border:1px solid black;"><p>Disabled</p></td>
<td style="border:1px solid black;"><p>Require case-sensitivity for non-Windows subsystems, such as UNIX passwords.</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p>System settings: Optional subsystems</p></td>
<td style="border:1px solid black;"><p>Enter POSIX here only if expressly required</p></td>
<td style="border:1px solid black;"><p>The POSIX execution layer has had multiple local exploits in the past, and should be disabled unless required by third-party software. It is extremely rare for POSIX to be required by commercial software packages.</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p>System settings: Use Certificate Rules on Windows executables for Software Restriction policies</p></td>
<td style="border:1px solid black;"><p>Not Defined</p></td>
<td style="border:1px solid black;"><p>When certificate rules are created, enabling this option enforces software restriction policies that check a Certificate Revocation List (CRL) to make sure the software's certificate and signature are valid.</p></td>
</tr>
</tbody>
</table>

<p> </p>
<table style="border:1px solid black;">
<colgroup>
<col width="100%" />
</colgroup>
<thead>
<tr class="header">
<th><img src="images/Dd939800.Important(WS.10).gif" />重要</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">The WSUS subdirectories UpdateServicesPackages, WsusContent, and WsusTemp created as shared directories (for WSUS Administrators and the Network Service account) as part of WSUS setup. These directories can be found by default under the WSUS directory at the root of the largest partition on the WSUS server. Sharing of these directories may be disabled if you are not using local publishing.
<p></p></td>
</tr>
</tbody>
</table>
<p> </p>

### Event log settings

Configure Event Log settings to help ensure an adequate level of activity monitoring.

### Event log settings

<p> </p>
<table style="border:1px solid black;">
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th>Option</th>
<th>Security setting</th>
<th>Setting rationale</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><p>Maximum application log size</p></td>
<td style="border:1px solid black;"><p>100489 kilobytes</p></td>
<td style="border:1px solid black;"><p>A large event log allows administrators to store and search for problematic and suspicious events.</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p>Maximum security log size</p></td>
<td style="border:1px solid black;"><p>100489 kilobytes</p></td>
<td style="border:1px solid black;"><p>A large event log allows administrators to store and search for problematic and suspicious events.</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p>Maximum system log size</p></td>
<td style="border:1px solid black;"><p>100489 kilobytes</p></td>
<td style="border:1px solid black;"><p>A large event log allows administrators to store and search for problematic and suspicious events.</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p>Prevent local guests group from accessing application log</p></td>
<td style="border:1px solid black;"><p>Enabled</p></td>
<td style="border:1px solid black;"><p>Guest accounts should not be able to access sensitive information in the event log.</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p>Prevent local guests group from accessing security log</p></td>
<td style="border:1px solid black;"><p>Enabled</p></td>
<td style="border:1px solid black;"><p>Guest accounts should not be able to access sensitive information in the event log.</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p>Prevent local guests group from accessing system log</p></td>
<td style="border:1px solid black;"><p>Enabled</p></td>
<td style="border:1px solid black;"><p>Guest accounts should not be able to access sensitive information in the event log.</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p>Retain application log</p></td>
<td style="border:1px solid black;"><p>7 Days</p></td>
<td style="border:1px solid black;"><p>After a week, logs should be stored on a centralized log server.</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p>Retain security log</p></td>
<td style="border:1px solid black;"><p>7 Days</p></td>
<td style="border:1px solid black;"><p>After a week, logs should be stored on a centralized log server.</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p>Retain system log</p></td>
<td style="border:1px solid black;"><p>7 Days</p></td>
<td style="border:1px solid black;"><p>After a week, logs should be stored on a centralized log server.</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p>Retention method for application log</p></td>
<td style="border:1px solid black;"><p>As Needed</p></td>
<td style="border:1px solid black;"><p>Overwrite audit logs as needed when log files have filled up.</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p>Retention method for security log</p></td>
<td style="border:1px solid black;"><p>As Needed</p></td>
<td style="border:1px solid black;"><p>Overwrite audit logs as needed when log files have filled up.</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p>Retention method for system log</p></td>
<td style="border:1px solid black;"><p>As Needed</p></td>
<td style="border:1px solid black;"><p>Overwrite audit logs as needed when log files have filled up.</p></td>
</tr>
</tbody>
</table>
  
### System services
  
Enable only services that are required for WSUS.
  
### Enabled operating system services

<p> </p>
<table style="border:1px solid black;">
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th>Option</th>
<th>Security setting</th>
<th>Setting rationale</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><p>Alerter</p></td>
<td style="border:1px solid black;"><p>Disabled</p></td>
<td style="border:1px solid black;"><p>The alerter service is of most use when an administrator is logged into the network and wants to be notified of events. For computers running WSUS, the service is not necessary.</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p>Application Management</p></td>
<td style="border:1px solid black;"><p>Manual</p></td>
<td style="border:1px solid black;"><p>This service is only necessary when installing new applications to the environment with Active Directory.</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p>Automatic Updates</p></td>
<td style="border:1px solid black;"><p>Automatic</p></td>
<td style="border:1px solid black;"><p>This service is required in order to support a fully patched operating environment.</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p>Clipbook</p></td>
<td style="border:1px solid black;"><p>Disabled</p></td>
<td style="border:1px solid black;"><p>This service is unnecessary to the WSUS environment.</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p>COM+ Event System</p></td>
<td style="border:1px solid black;"><p>Manual</p></td>
<td style="border:1px solid black;"><p>The COM+ event system might be used in the Web-based application.</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p>Computer Browser</p></td>
<td style="border:1px solid black;"><p>Automatic</p></td>
<td style="border:1px solid black;"><p>The computer browser service is required on interactive workstations.</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p>DHCP Client</p></td>
<td style="border:1px solid black;"><p>Automatic</p></td>
<td style="border:1px solid black;"><p>DHCP is necessary to have an IP address on the WSUS server.</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p>Distributed File System</p></td>
<td style="border:1px solid black;"><p>Disabled</p></td>
<td style="border:1px solid black;"><p>DFS is used for file sharing across multiple servers, which is not needed for WSUS.</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p>Distributed Link Tracking Client</p></td>
<td style="border:1px solid black;"><p>Disabled</p></td>
<td style="border:1px solid black;"><p>This service is appropriate only if a domain has distributed link tracking configured.</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p>Distributed Link Tracking Server</p></td>
<td style="border:1px solid black;"><p>Disabled</p></td>
<td style="border:1px solid black;"><p>This service is appropriate only if a domain has distributed link tracking configured.</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p>Distributed Transaction Coordinator</p></td>
<td style="border:1px solid black;"><p>Disabled</p></td>
<td style="border:1px solid black;"><p>This service is appropriate only if a domain uses distributed transactions, which are not needed for WSUS.</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p>DNS Client</p></td>
<td style="border:1px solid black;"><p>Automatic</p></td>
<td style="border:1px solid black;"><p>DNS is necessary for IP-address-to-name resolution.</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p>Event Log</p></td>
<td style="border:1px solid black;"><p>Automatic</p></td>
<td style="border:1px solid black;"><p>The Event Log service is important for logging events on the system and provides critical auditing information.</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p>File Replication</p></td>
<td style="border:1px solid black;"><p>Disabled</p></td>
<td style="border:1px solid black;"><p>This service is used for file replication and synchronization, which is not necessary for WSUS.</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p>IIS ADMIN Service</p></td>
<td style="border:1px solid black;"><p>Automatic</p></td>
<td style="border:1px solid black;"><p>This service is required for WSUS administration.</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p>Indexing Service</p></td>
<td style="border:1px solid black;"><p>Manual</p></td>
<td style="border:1px solid black;"><p>This service is used by IIS.</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p>Intersite Messaging</p></td>
<td style="border:1px solid black;"><p>Disabled</p></td>
<td style="border:1px solid black;"><p>This service needs to be enabled only on domain controllers.</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p>Internet Connection Firewall/Internet Connection Sharing</p></td>
<td style="border:1px solid black;"><p>Manual</p></td>
<td style="border:1px solid black;"><p>This service is required if the local ICF firewall is being used.</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p>IPsec Services</p></td>
<td style="border:1px solid black;"><p>Automatic</p></td>
<td style="border:1px solid black;"><p>This service is required if IPsec has been utilized.</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p>Kerberos Key Distribution Center</p></td>
<td style="border:1px solid black;"><p>Disabled unless functioning as a domain controller</p></td>
<td style="border:1px solid black;"><p>This service is enabled by default in order to join and authenticate to Windows Server domain controllers.</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p>License Logging Service</p></td>
<td style="border:1px solid black;"><p>Disabled</p></td>
<td style="border:1px solid black;"><p>This service is used on systems on which application licensing must be tracked.</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p>Logical Disk Manager</p></td>
<td style="border:1px solid black;"><p>Automatic</p></td>
<td style="border:1px solid black;"><p>This service is used in logical disk management.</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p>Logical Disk Manager Administrative Service</p></td>
<td style="border:1px solid black;"><p>Manual</p></td>
<td style="border:1px solid black;"><p>This service is used in logical disk management.</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p>Messenger</p></td>
<td style="border:1px solid black;"><p>Disabled</p></td>
<td style="border:1px solid black;"><p>This service is only necessary if NetBIOS messaging is being used.</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p>Net Logon</p></td>
<td style="border:1px solid black;"><p>Automatic</p></td>
<td style="border:1px solid black;"><p>This service is necessary to belong to a domain.</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p>NetMeeting Remote Desktop Sharing</p></td>
<td style="border:1px solid black;"><p>Disabled</p></td>
<td style="border:1px solid black;"><p>NetMeeting is an application that allows collaboration over a network. It is used on interactive workstations, and should be disabled for servers as it presents a security risk.</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p>Network Connections</p></td>
<td style="border:1px solid black;"><p>Manual</p></td>
<td style="border:1px solid black;"><p>This service allows network connections to be managed centrally.</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p>Network DDE</p></td>
<td style="border:1px solid black;"><p>Disabled</p></td>
<td style="border:1px solid black;"><p>Network DDE is a form of interprocess communication (IPC) across networks. Because it opens network shares and allows remote access to local resources, it should be disabled unless explicitly needed.</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p>Network DDE DSDM</p></td>
<td style="border:1px solid black;"><p>Disabled</p></td>
<td style="border:1px solid black;"><p>Network DDE is a form of interprocess communication (IPC) across networks. Because it opens network shares and allows remote access to local resources, it should be disabled unless explicitly needed.</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p>NTLM Security Support Provider</p></td>
<td style="border:1px solid black;"><p>Manual</p></td>
<td style="border:1px solid black;"><p>The NTLM Security Support Provider is necessary to authenticate users of remote procedure call (RPC) services that use transports such as TCP and UDP.</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p>Performance Logs and Alerts</p></td>
<td style="border:1px solid black;"><p>Manual</p></td>
<td style="border:1px solid black;"><p>This service is only necessary when logs and alerts are used.</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p>Plug and Play</p></td>
<td style="border:1px solid black;"><p>Automatic</p></td>
<td style="border:1px solid black;"><p>Plug and Play is needed if the system uses Plug and Play hardware devices.</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p>Print Spooler</p></td>
<td style="border:1px solid black;"><p>Disabled</p></td>
<td style="border:1px solid black;"><p>This service is necessary if the system is used for printing.</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p>Protected Storage</p></td>
<td style="border:1px solid black;"><p>Automatic</p></td>
<td style="border:1px solid black;"><p>This service must be enabled because the IIS Admin service depends on it.</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p>Remote Access Auto Connection Manager</p></td>
<td style="border:1px solid black;"><p>Disabled</p></td>
<td style="border:1px solid black;"><p>Enable this service only for RAS servers.</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p>Remote Access Connection Manager</p></td>
<td style="border:1px solid black;"><p>Disabled</p></td>
<td style="border:1px solid black;"><p>Enable this service only for RAS servers.</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p>Remote Procedure Call (RPC)</p></td>
<td style="border:1px solid black;"><p>Automatic</p></td>
<td style="border:1px solid black;"><p>This service is required for RPC communications.</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p>Remote Procedure Call (RPC) Locator</p></td>
<td style="border:1px solid black;"><p>Manual</p></td>
<td style="border:1px solid black;"><p>This service is required for RPC communications.</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p>Remote Registry</p></td>
<td style="border:1px solid black;"><p>Manual</p></td>
<td style="border:1px solid black;"><p>Remote Registry is a key target for attackers, viruses, and worms, and should be set to manual unless otherwise needed, where the server can enable it.</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p>Removable Storage</p></td>
<td style="border:1px solid black;"><p>Manual</p></td>
<td style="border:1px solid black;"><p>For a dynamic server, this service is necessary.</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p>Routing and Remote Access</p></td>
<td style="border:1px solid black;"><p>Disabled</p></td>
<td style="border:1px solid black;"><p>Enable this service only for RAS servers.</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p>Security Accounts Manager</p></td>
<td style="border:1px solid black;"><p>Automatic</p></td>
<td style="border:1px solid black;"><p>This service should be enabled, as it manages local accounts.</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p>Server</p></td>
<td style="border:1px solid black;"><p>Automatic</p></td>
<td style="border:1px solid black;"><p>This service should be enabled or disabled as necessary. The service supports file, print, and named-pipe sharing over the network for this computer.</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p>Smart Card</p></td>
<td style="border:1px solid black;"><p>Manual</p></td>
<td style="border:1px solid black;"><p>Because users will not be using smart cards for two-factor logon authentication, this service is unnecessary and should be disabled or set to manual.</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p>System Event Notification</p></td>
<td style="border:1px solid black;"><p>Automatic</p></td>
<td style="border:1px solid black;"><p>This service is needed for COM+ events.</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p>Task Scheduler</p></td>
<td style="border:1px solid black;"><p>Manual</p></td>
<td style="border:1px solid black;"><p>This service should be enabled or disabled as necessary. The service enables a user to configure and schedule automated tasks on this computer.</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p>TCP/IP NetBIOS Helper</p></td>
<td style="border:1px solid black;"><p>Automatic</p></td>
<td style="border:1px solid black;"><p>This service is used in Windows networking for computers running an operating system earlier than Windows Server 2003.</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p>Telephony</p></td>
<td style="border:1px solid black;"><p>Disabled</p></td>
<td style="border:1px solid black;"><p>This service is not necessary in this environment because telephony devices are not used.</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p>Telnet</p></td>
<td style="border:1px solid black;"><p>Disabled</p></td>
<td style="border:1px solid black;"><p>The telnet service should be disabled and its use strongly discouraged.</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p>Terminal Services</p></td>
<td style="border:1px solid black;"><p>Manual</p></td>
<td style="border:1px solid black;"><p>Terminal services should be enabled or disabled as necessary.</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p>Uninterruptible Power Supply</p></td>
<td style="border:1px solid black;"><p>Manual</p></td>
<td style="border:1px solid black;"><p>This service is necessary if a Uninterruptible Power Supply is used.</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p>Windows Installer</p></td>
<td style="border:1px solid black;"><p>Manual</p></td>
<td style="border:1px solid black;"><p>Users may choose to use Windows Installer to install .msi packages on the system; therefore, this service should be set to manual.</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p>Windows Management Instrumentation</p></td>
<td style="border:1px solid black;"><p>Manual</p></td>
<td style="border:1px solid black;"><p>WMI provides extended management capabilities.</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p>Windows Management Instrumentation Driver Extensions</p></td>
<td style="border:1px solid black;"><p>Manual</p></td>
<td style="border:1px solid black;"><p>WMI Driver Extensions allow monitoring of network card connection state in the taskbar.</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p>Windows Time</p></td>
<td style="border:1px solid black;"><p>Automatic</p></td>
<td style="border:1px solid black;"><p>External time synchronization is required for Kerberos key exchange in Active Directory environments.</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p>Workstation</p></td>
<td style="border:1px solid black;"><p>Automatic</p></td>
<td style="border:1px solid black;"><p>The workstation service is necessary for Windows networking.</p></td>
</tr>
</tbody>
</table>
  
### TCP/IP hardening
  
Microsoft recommends that you harden the TCP/IP interface for WSUS servers.
  
### TCP/IP registry key settings

<p> </p>
<table style="border:1px solid black;">
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th>Registry key</th>
<th>Security setting</th>
<th>Setting rationale</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><p>HKLM\SYSTEM\CurrentControlSet\Services\Tcpip\Parameters\SynAttackProtect</p></td>
<td style="border:1px solid black;"><p>REG_DWORD = 1</p></td>
<td style="border:1px solid black;"><p>Causes TCP to adjust retransmission of SYN-ACKS.</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p>HKLM\SYSTEM\CurrentControlSet\Services\Tcpip\Parameters\TcpMaxHalfOpen</p></td>
<td style="border:1px solid black;"><p>REG_DWORD = 500</p></td>
<td style="border:1px solid black;"><p>Helps protect against SYN attacks.</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p>HKLM\SYSTEM\CurrentControlSet\Services\Tcpip\Parameters\TcpMaxHalfOpenRetried</p></td>
<td style="border:1px solid black;"><p>REG_DWORD = 400</p></td>
<td style="border:1px solid black;"><p>Helps protect against SYN attacks.</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p>HKLM\SYSTEM\CurrentControlSet\Services\Tcpip\Parameters\EnableICMPredirect</p></td>
<td style="border:1px solid black;"><p>REG_DWORD = 0</p></td>
<td style="border:1px solid black;"><p>Prevents the creation of expensive host routes when an ICMP redirect packet is received.</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p>HKLM\SYSTEM\CurrentControlSet\Services\Tcpip\Parameters\DeadGWDetectDefault</p></td>
<td style="border:1px solid black;"><p>REG_DWORD = 1</p></td>
<td style="border:1px solid black;"><p>Allows Transmission Control Protocol to detect failure of the default gateway and to adjust the IP routing table to use another default gateway.</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p>HKLM\SYSTEM\CurrentControlSet\Services\Tcpip\Parameters\DisableIPSourceRouting</p></td>
<td style="border:1px solid black;"><p>REG_DWORD = 1</p></td>
<td style="border:1px solid black;"><p>Disables IP source routing.</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p>HKLM\SYSTEM\CurrentControlSet\Services\Tcpip\Parameters\IPEnableRouter</p></td>
<td style="border:1px solid black;"><p>REG_DWORD = 0</p></td>
<td style="border:1px solid black;"><p>Disables forwarding of packets between network interfaces.</p></td>
</tr>
</tbody>
</table>
  
### IIS security configuration
  
Consider enabling the following three security settings on the IIS Web server to help ensure secure WSUS administration.
  
#### Enable general IIS error messages
  
By default, IIS gives detailed error messages to remote Web clients. We recommend enabling IIS general, less-detailed error messages. This prevents an unauthorized user from probing the IIS environment with IIS error messages.
  
**To enable general IIS error messages**  
1.  On the **Start** menu, point to **Programs**, point to **Administrator Tools**, and then click **Internet Information Services Manager**.
  
2.  Expand the local computer node.
  
3.  Right-click **Web Sites**, and then click **Properties**.
  
4.  On the **Home Directory** tab, click **Configuration**.
  
5.  On the **Debugging** tab, under **Error messages for script errors**, click **Send the following text error message to client**, where the error message reads "An error occurred on the server when processing the URL. Please contact the system administrator."
  
#### Enable additional IIS logging options
  
By default, IIS enables logging for a number of options. However, we recommend logging several additional key options.
  
**To enable additional IIS logging options**  
1.  On the **Start** menu, point to **Programs**, point to **Administrator Tools**, and then click **Internet Information Services Manager**.
  
2.  Expand the local computer node.
  
3.  Right-click **Web Sites**, and then click **Properties**.
  
4.  On the **Web Site** tab, under the **Active log format** box, click **Properties**.
  
5.  In **Logging Properties** go to the **Advanced** tab, and select the check boxes for the following logging options:
  
    -   **Server Name**  
    -   **Time taken**  
    -   **Host**  
    -   **Cookie**  
    -   **Referer**
  
#### Remove header extensions
  
By default, IIS enables header extensions for HTTP requests. We recommend removing any header extensions for IIS.
  
**To remove header extensions for HTTP requests**  
1.  On the **Start** menu, point to **Programs**, point to **Administrator Tools**, and then click **Internet Information Services Manager**.
  
2.  Expand the local computer node.
  
3.  Right-click **Web Sites**, and then click **Properties**.
  
4.  On the **HTTP Headers** tab, select the **X-Powered-By: ASP.NET** check box, and then click **Remove**.
  
SQL Server  
----------
  
The following are security recommendations for SQL Server with WSUS.
  
### SQL registry permissions
  
Use access control permissions to secure the SQL Server registry keys.
  
**HKLM\\SOFTWARE\\MICROSOFT\\MSSQLSERVER**
  
###  

<p> </p>
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th>ISEC setting</th>
<th>Rationale</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><p>Administrators: Full Control</p>
<p>SQL Service Account: Full Control</p>
<p>System: Full Control</p></td>
<td style="border:1px solid black;"><p>These settings help ensure limited access to the application’s registry key to authorized administrators or system accounts.</p></td>
</tr>
</tbody>
</table>
  
### Stored procedures
  
Remove all stored procedures that are unnecessary and that have the ability to control the database server remotely.
  
### Unnecessary SQL Server 2005 stored procedures

<p> </p>
<table style="border:1px solid black;">
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th>Description</th>
<th>Stored procedures</th>
<th>Rationale</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><p>Delete stored procedures by using the following command:</p>
<p><strong>use master exec sp_dropextendedproc</strong> <em>stored procedure</em></p>
<p>where <em>stored procedure</em> is the name of the stored procedure to be deleted.</p></td>
<td style="border:1px solid black;"><ul>
<li>Sp_OACreate<br />
<br />
</li>
<li>Sp_OADestroy<br />
<br />
</li>
<li>Sp_OAGetErrorInfo<br />
<br />
</li>
<li>Sp_OAGetProperty<br />
<br />
</li>
<li>Sp_OAMethod<br />
<br />
</li>
<li>Sp_OASetProperty<br />
<br />
</li>
<li>SP_OAStop<br />
<br />
</li>
<li>Xp_regaddmultistring<br />
<br />
</li>
<li>Xp_regdeletekey<br />
<br />
</li>
<li>Xp_regdeletevalue<br />
<br />
</li>
<li>Xp_regenumvalues<br />
<br />
</li>
<li>Xp_regread<br />
<br />
</li>
<li>Xp_regremovemultistring<br />
<br />
</li>
<li>Xp_regwrite<br />
<br />
</li>
<li>sp_sdidebug<br />
<br />
</li>
<li>xp_availablemedia<br />
<br />
</li>
<li>xp_cmdshell<br />
<br />
</li>
<li>xp_deletemail<br />
<br />
</li>
<li>xp_dirtree<br />
<br />
</li>
<li>xp_dropwebtask<br />
<br />
</li>
<li>xp_dsninfo<br />
<br />
</li>
<li>xp_enumdsn<br />
<br />
</li>
</ul></td>
<td style="border:1px solid black;"><p>Remove all stored procedures that are not necessary for WSUS and could possibly give unauthorized users the ability to perform command-line actions on the database.</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p> </p></td>
<td style="border:1px solid black;"><ul>
<li>xp_enumerrorlogs<br />
<br />
</li>
<li>xp_enumgroups<br />
<br />
</li>
<li>xp_eventlog<br />
<br />
</li>
<li>xp_findnextmsg<br />
<br />
</li>
<li>xp_fixeddrives<br />
<br />
</li>
<li>xp_getfiledetails<br />
<br />
</li>
<li>xp_getnetname<br />
<br />
</li>
<li>xp_logevent<br />
<br />
</li>
<li>xp_loginconfig<br />
<br />
</li>
<li>xp_makewebtask<br />
<br />
</li>
<li>xp_msver<br />
<br />
</li>
<li>xp_readerrorlog<br />
<br />
</li>
<li>xp_readmail<br />
<br />
</li>
<li>xp_runwebtask<br />
<br />
</li>
<li>xp_sendmail<br />
<br />
</li>
<li>xp_sprintf<br />
<br />
</li>
<li>xp_sscanf<br />
<br />
</li>
<li>xp_startmail<br />
<br />
</li>
<li>xp_stopmail<br />
<br />
</li>
<li>xp_subdirs<br />
<br />
</li>
<li>xp_unc_to_drive<br />
<br />
</li>
</ul></td>
<td style="border:1px solid black;"><p> </p></td>
</tr>
</tbody>
</table>
