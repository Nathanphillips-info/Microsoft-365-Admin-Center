# Microsoft-365-Admin-Center
Microsoft 365 Admin  Set up and Configuration

This page is for documentation of basic Microsoft 365 Admin Center functionality. How to add users and groups, reset passwords and assign licenses for your hybrid or cloud enviornment. 

## Creating Users and Groups

- Once in the Admin center you can click users/active_users to open up the active users. At the top of this screen you can create a new user. You can create and email address connected to your domain and asign licenses and put them in a certain department. That is the basic way to add a user in the cloud enviornment one person at a time.You should always select have user create new password on first login. The user, if given an email and a license should be able to login and access microsoft 365 apps like outlook or word or excel.
- As an example I created a user named Robert Smith, I am going to login and create a document and send an email from his outlook account.

![Alt text](path/to/image.jpg "Optional Title")

  As I am testing this out at home and signed in to two different 365 accounts on the same device, sometimes a cached login can cause issues trying to access and app. I was signed into Robert Smith, but my Admin accouant logged in when opening the document because the credentials were cached. I had to delete browsing history to access the app with the correct account. Otherwise it logged in with the admin while it was loading to Robert Smiths document and said I didn't have access.
- To add teams and groups, go to teams and groups/active teams and groups. Then in the menu you can create a new team or microsoft 365 group. A group includes a group email for contacting everyone and a sharpoint site to collaborate. A team provides a teams group to message and edit files together through teams. Each team and group can have owners and members.
- Under teams and groups you can also add security groups which can give or limit access to certain resources on SharePoint sites. These might be best configured in the Entra ID portal. There you can configure the group further and add users giving them special privelages or restrictions.
- Under Shared mailboxes, you can also create a shared mailbox for users or groups that you have created for them to recieve emails together.
- You can access deleted users or groups data for 30 days.
- I created several users, assigned them licenses, and made groups for them, such as accounting, help desk, and system administrators. 


# Microsoft Exchange Admin Portal 
In the exchange admin portal you can assign roles for data protection, trace mail routes, create rules for messages. You can manage sharing policies for mailboxes and calanders and you can look at mailflow reports. If you find any suspicious emails you can also report them in exchange, taking you to the security and compliance page. 

- I created a rule that all email must use TLS encryption.
- I created a web app policy where people could only open attachtments on private devices and it would not sync with mobile devices.
- You can also use message trace to see lost emails. I searched for emails sent from the primary domain in the last day. 
