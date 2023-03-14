---
label: "FAQs"
icon: unverified
order: 550
author:
  name: Robbe
  avatar: https://cdn.discordapp.com/attachments/1034201179716079777/1084940308686589992/Robbe.png
tags: [faqs]
---
## Installation
Setting up Wick can be a sensitive and advanced process, which may take several minutes to complete. Depending on your level of proficiency with the bot, it may seem easy or difficult. Fortunately, there is a setup guide and a wizard available to guide you through the process and ensure a smooth setup experience.

It is important to treat Wick with the same level of caution as you would an antivirus program. Always exercise caution when making decisions in your server, just as you would with your computer.

If you are unable to find a new role named Wick in your server, it is likely because you did not grant the bot the necessary permissions during the setup process.

Please note that only individuals with permit 4/5 (Trusted Admins/Extra Owners) have the authority to set up Wick. It is important to exercise caution when granting these permits and only give them to individuals you trust.

In the event that Wick displays the message "Wick lacks certain permissions to function properly" during setup, this indicates that the bot does not have the necessary permissions to operate effectively in your server. To resolve this issue, grant Wick ADMIN permissions.

---

## Wick Control
When it comes to managing Wick, it's important to have a plan in place in case of unexpected circumstances. One scenario that may arise is losing access to the owner account. In such a case, it is recommended to utilize the Rescue key step in the wizard, which provides a QR code for two-factor authentication or Auty, as well as a key to copy and save for future use. It is also wise to add an alternative owner to your account, should the need arise for additional access.

As for who can access the Dashboard and manage Wick's features, there are two user types to consider: Extra Owners and Trusted Admins. Extra Owners have full access and control over the account, with the exception of adding more Extra Owners. They are completely immune to Wick. Trusted Admins can access the Dashboard but are limited in their ability to manage the Miscellaneous and Anti-Nuke settings. They too are completely immune to Wick. By understanding these user types and their respective levels of access, you can ensure that your Wick account is secure and properly managed.

---

## General Questions
Inquiries Regarding Wick's Security Features

For those seeking to enhance their knowledge of Wick's security measures, the following topics may be of interest:

- How does Wick identify suspicious accounts?
- What permissions are classified as dangerous?
- Is there a means to evaluate the level of security of one's server?
Regarding the identification of suspicious accounts, Wick considers various factors such as default profile pictures, account age, and username filters, which may be tailored to one's specific settings.

In terms of dangerous permissions, the following actions are generally deemed high risk: managing channels, roles, webhooks, messages, server (administrator), and moderating or kicking/banning members.

To determine the security status of a server, navigate to the Dashboard, select the desired server, and view the Overview page. Here, Wick provides a summary of any issues that require attention, an overview of system functionality, and other pertinent information. While it is impossible to guarantee complete immunity to attacks, a server that adheres to recommended security practices will be substantially more secure.

---

## Punishments
When encountering issues related to punishments in Wick, it is important to approach the situation in a methodical manner. If Wick failed to punish a user, there could be several reasons why this occurred. One possible explanation could be a faulty setup. Please ensure that the Quarantine role is correctly placed and located in the appropriate position within the statistics. Additionally, it is possible that the user has been whitelisted from punishment for a particular filter. You can verify whether or not a user is whitelisted by running the command "w!info USER".

If you are experiencing issues with Wick punishing your ticket bot, this is likely due to Wick's antinuke system. Wick will react to any attempts to destroy your server, including those made by the ticket bot. However, you can whitelist the category where the ticket bot operates by running the command "w!anp CATEGORY-ID ?add 6".

In the event that Wick is deleting your webhooks, it is recommended that you ensure that the webhooks are not performing any suspicious or harmful actions. If the webhooks are harmless, you can whitelist them to prevent Wick from deleting them.

Lastly, if you are encountering issues with Wick punishing your auto roles bot, it is likely due to the bot attempting to assign roles to Quarantined members. To resolve this issue, you can add the bot to the Quarantine whitelist or disable its auto role feature and use Wick's instead. With Wick's verification system, users who pass the verification process will automatically receive the main roles that you have designated in the statistics.

---

## Response
In the event that you encounter any issues with Wick, we encourage you to refer to the following information.

If Wick is not responding, it may be due to permissions. Ensure that Wick has been granted ADMIN permissions. Additionally, check your prefix to ensure that it has not been changed. If you have been quarantined, Wick may not be able to respond to your commands. Lastly, if Wick is experiencing technical difficulties, please check Wick's Status.

In the event that Wick is slow to respond, please report any delays longer than 5 seconds.

If Wick is not performing any actions, it may be due to an improper setup. Ensure that your setup has been configured correctly. If the issue persists, please run w!tshoot in your server. If the problem continues, please join our Discord server for further assistance.

---

## Fake Wick

!!!danger Important
!!!

It has come to our attention that there are several imposter accounts posing as Wick and soliciting individuals to scan a QR code or engage in unsolicited direct messages. It is imperative that these instances are reported to Discord immediately.

If you happen to encounter a fraudulent Wick account that has been verified by Discord, we kindly request that you join our support server to aid us in taking swift action against such activity. Additionally, please be advised to exercise caution and verify the authenticity of any communication from Wick to avoid falling victim to these scams.