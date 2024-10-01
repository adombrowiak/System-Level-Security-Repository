<h1>System Level Security</h1>

[Project 4: System Level Security](https://github.com/user-attachments/files/17102215/dombrowiak_CST620_Project4.pdf)

<h2>Description</h2>
Configuring users and groups for both Windows and Linux environments.


<h2>Tools Utilized</h2>

- <b>Computer Management</b> 
- <b>Mate Terminal</b>

<h2>Environments Used </h2>

- <b>Windows 10</b>
- <b>Kali Linux</b>

<h2>Project Documentation</h2>
<h3>Windows Local Account and Group Security Best Practices</h3>
To ensure robust security for Windows local accounts, it is essential to follow several best practices. First, enforce the use of strong, unique passwords for all accounts. This can be achieved by implementing password policies that mandate complexity, length, and regular changes (Microsoft, 2023). Second, disable or rename the default Administrator account to make it harder for attackers to guess. Additionally, enable account lockout policies to prevent brute force attacks and regularly audit account activity to detect and respond to suspicious behavior promptly. Utilizing multi-factor authentication (MFA) where possible adds an extra layer of security, making unauthorized access more difficult even if passwords are compromised (Soni, n.d.).</br>
When it comes to group security, limiting the use of administrative privileges is crucial. Only grant admin rights to accounts and groups that need them and consider using the principle of least privilege. Regularly review and update group memberships to ensure only necessary users can access sensitive resources. Implement role-based access control (RBAC) to manage permissions efficiently (Tremblay, 2024). Also, segment network resources using groups to ensure sensitive data is accessible only to authorized users. Lastly, ensure that group policies are configured and applied consistently across the network to maintain a secure and compliant environment.</br>

<h3>Linux Local Account and Group Security Best Practices</h3>
To secure Linux local accounts, start by enforcing the use of strong, unique passwords for all users. Implement password policies that require complexity, length, and regular updates. Utilize tools like ‘pam_pwquality’ to enforce these policies system-wide. Disable or lock the root account where possible and encourage the use of ‘sudo’ for administrative tasks to minimize risk. Regularly review user accounts and remove any that are no longer needed. Additionally, employ multi-factor authentication (MFA) for added security, reducing the likelihood of unauthorized access even if a password is compromised (Soni, n.d.).</br>
For group security, adhere to the principle of least privilege by only assigning users to groups that are necessary for their roles. Regularly audit group memberships to ensure that only authorized personnel have access to critical systems and data. Use Access Control Lists (ACLs) to fine-tune permissions beyond the basic user/group/others model, providing more granular control. Implement role-based access control (RBAC) to manage permissions effectively and ensure that security policies are consistently applied (Tremblay, 2024). Keep system and software updated to protect against vulnerabilities and monitor logs for any unusual activity to identify and mitigate potential security threats quickly.</br>

<h3>Windows Local Account and Group Security Best Practices Implementation and Testing</h3>

I have created users for Cindy, Dale, Jeda, and Steve. Including the proper description for each user.
![image](https://github.com/user-attachments/assets/1ec854f1-99ec-4a56-a02e-84eb2e6b75cc)

Created three groups better to distinguish the level of access to the computers.
![image](https://github.com/user-attachments/assets/1c35cb5e-5982-41f7-8f0b-3536323e80e6)

I have added all the users to the proper groups.
![image](https://github.com/user-attachments/assets/026a0dff-0e7c-463c-bf48-d989a467d2c8)
![image](https://github.com/user-attachments/assets/5d0d2a0f-5de5-417c-8873-2eef2e5e86b9)
![image](https://github.com/user-attachments/assets/1d1a8471-6a46-497b-b94a-9694aceff799)
![image](https://github.com/user-attachments/assets/044000f2-3010-40ca-a403-1051fe39d243)
![image](https://github.com/user-attachments/assets/31d51d1c-db66-4d92-9386-1ff8465f3e08)
![image](https://github.com/user-attachments/assets/296b9dcf-7ec5-4cf2-88e7-7774a8d4f849)

I have added all the users to the proper groups.
![image](https://github.com/user-attachments/assets/1c39a726-2b4b-4acb-9498-3787bb2a82c1)
![image](https://github.com/user-attachments/assets/25284628-a9e7-465a-9b97-9d92e7bf0e9b)

I’ve added Help Desk to all the required ‘rights.’ Two examples are listed above.
![image](https://github.com/user-attachments/assets/b1b84266-33ea-437b-9042-57c3c5be78bd)
![image](https://github.com/user-attachments/assets/fe90767e-a365-478d-bbf0-e56f8dc99a23)

Added System Engineering to the required accesses, above are two examples of the group being added.
![image](https://github.com/user-attachments/assets/7018e90a-2a68-4711-9e1d-927f353c3445)
![image](https://github.com/user-attachments/assets/9ebcb856-8e04-451a-956b-613af3789d6e)

<h3>Linux Local Account and Group Security Best Practices Implementation and Testing</h3>

Created all the users needed.
![image](https://github.com/user-attachments/assets/6e8686dd-59c4-4d22-a09a-5382e88828bd)

Added the users into /etc/ssh/ssh_config
![image](https://github.com/user-attachments/assets/9630a7c4-a1a4-43eb-810e-ea5de4b5a2ef)

Added the required groups along with showing that I reset the sshd.
![image](https://github.com/user-attachments/assets/6bf08d2e-0863-4697-a5c7-57753ba07e60)

Updated each of the users to their respective group.
![image](https://github.com/user-attachments/assets/afbb7f31-e160-4b67-93e5-bbb613aad2a7)

Gave Cindy and Jeda full access to the computer.
![image](https://github.com/user-attachments/assets/80d4b496-828d-4bd0-ab29-00085ccb82a4)

<h3>References</h3>

Microsoft. (2023, June 7). Password must meet complexity requirements - Windows 10. Learn.microsoft.com. https://learn.microsoft.com/en-us/previous-versions/windows/it-pro/windows-10/security/threat-protection/security-policy-settings/password-must-meet-complexity-requirements</br>
Soni, R. (n.d.). 7 Benefits of Using Multi-Factor Authentication ( MFA). Www.loginradius.com. https://www.loginradius.com/blog/identity/benefits-of-mfa/#:~:text=Increased%20Security%3A%20With%20MFA%2C%20even</br>
Tremblay, T. (2024, January 11). How to Implement Role-Based Access Control in Your Organization. Kohezion. https://www.kohezion.com/blog/role-based-access-control</br>
