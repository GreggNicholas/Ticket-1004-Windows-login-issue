# Ticket-1004-Windows-login-issue

# Introduction
This activity simulates an IT Support ticket submitted by a user. Your task is to resolve the issue and document the process, as you would using a ticketing system.  
To troubleshoot this ticket, you will need to import and launch a Virtual Machine named Ticket #1004 using VirtualBox.

# Objectives
Resolve ticket #1004 and document the process.
Equipment/Requirements
Computer with internet connection and VirtualBox installed.
The Ticket #1004 VM (Open Virtual Appliance (OVA) file).


Ticket ID #
1004
User Name
Learner01
User’s email
learner01@TechSolutions.com
Priority
 High
Category
 Operating System
Status
 Open
Subject
Windows login issue
Asset
capstone120
Assigned to
[Enter your name here]
Description
Hey IT Team,

Learner01 here. I changed my password recently, and now I'm totally locked out of Windows. Can't get in at all, and I don’t remember my password.

If you could help me out with this pronto, that would be awesome.

Thank you,
Learner01


# Tasks
I first tried to “forget password” to which I windows stated I need a USB. I looked over the virtual USB under devices in the upper right tool bar but that was of no help. I logged in as admin. Right clicked Start on lower left taskbar and left clicked computer management. Left clicked users and clicked on actions. Set password. Which it gave me a warning message about some data possible being lost but the user wants his password pronto. So I clicked proceed. 
# Resolution (Internal-facing)
To resolve the lockout issue faced by Learner01, I logged into the system using an administrator account. Right click Start menu in the lower left  taskbar and clicking computer management. I navigated to “Local Users and Groups” and selected “Users”. I then located Learner01’s account, right-clicked it, and chose “Set Password”. A warning message appeared, notifying me that some encrypted data, such as EFS-encrypted files and saved passwords, might be lost if the password was reset. However, given the urgency of the situation and Learner01’s immediate need to regain access, I proceeded with the password reset.
After setting a new password, I logged out of the administrator account and successfully logged in as Learner01 using the new password. This allowed access to the user’s desktop, resolving the issue effectively. I then took a screenshot of Learner01’s desktop to confirm and document that the issue had been fully resolved.
The root of the problem was that Learner01 had forgotten the recently changed password, and the Forgot Password feature required a recovery USB that was unavailable. By directly resetting the password through Computer Management, I was able to bypass the need for external recovery media and restore access promptly.
# Resolution (Client-facing)

Hello Learner01,
Your access issue has been successfully resolved. I was able to reset your password. You should be able to access your desktop with this password ********** now without any problems. If you encounter any other issues, feel free to reach out.

Best,
Gregg Nicholas

IT Support Specialist







