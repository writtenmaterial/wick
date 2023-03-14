---
order: 900
icon: mortar-board
label: Setup
tags: [setup]
---
!!!success Fast & Smooth Setup
Sapphire's setup is fast and smooth, thanks to its easy-to-use dashboard interface. With just a few clicks, you can invite Sapphire to your Discord server, ensure it has the necessary permissions, and begin exploring all of its features. The dashboard allows for quick and efficient management of Sapphire, making setup a breeze.
!!!

## Manual Setup
If opting for manual setup, it is imperative to carefully follow each step to ensure that Wick is fully established and operational.

> Please note that the manual setup process may take some time. To assist you in this endeavor, we have divided the setup guide into two parts. The first part covers the key components that require modification prior to configuring the security features in the second part.

Furthermore, if you require additional guidance or have any queries, we recommend reaching out to our support team for further assistance.

---

## Rescue Key
!!!danger
Emphasizing the significance of this step cannot be overstated.
!!!

The utilization of the rescue key is an imperative step in confirming your identity as a physical owner of the server. Losing access to your owner account may lead to a loss of control over Wick, underscoring the criticality of this step.

To retrieve the rescue key, navigate to the servers page on the Wick dashboard and securely save the key or use the QR code for added convenience. For enhanced security, you may opt to utilize the two-factor authentication (2FA) or Auty feature by scanning the QR code. Additionally, it is recommended to explore content related to this topic for a deeper understanding of how to safeguard your Wick account.

---

## Wick's Role
!!!warning
Can cause malfunctions if done incorrectly
!!!

Firstly, make sure that you have granted Wick the necessary permissions. Once that is done, you will see a new Wick role added to your server. It is important to note that this role needs to be placed at the top of the role hierarchy in order for Wick to function properly.

---

## Automatic Setup
Now that we have covered the essential steps, it is time to initiate the automatic setup process. This feature allows Wick to generate a Quarantine role and apply it to all channels in your server. Additionally, Wick will create dedicated #logs and #modlogs channels, and these elements will be automatically set in your statics, providing you with a seamless experience.

To begin the automatic setup process, simply enter the command "w!setup" and observe a visually stunning live panel showcasing Wick's actions.

## Quarantine Role
In order to maintain the security of your server, it is essential to properly configure the Quarantine role in Wick. After the automated setup, a new role named Quarantine will be created, which should be positioned directly under the Wick role to prevent unauthorized access. It is important to note that Wick's functionality is dependent on the existence of the Quarantine role. 
!!!info
If you are unable to locate the Quarantine role after setup, please run "w!setup" to ensure proper configuration. 
!!!

## Wick's Statics
To gain a better understanding of Wick's functionalities, it is important to familiarize oneself with the Statics feature, which encompasses roles, channels, and users that Wick depends on. Please note that some Statics, such as the Quarantine role, #logs, and #modlogs, are automatically generated during setup.

If you are not the Physical Server Owner and wish to set up Wick, the server owner must add you as an Extra Owner using the command "w!statics USER ?add 11," where USER is replaced by your username, mention, or ID.

In terms of roles, Main Roles are crucial for Wick's functionality and are zero-permission roles that you give to all members in your server. To add a Main Role, use the command "w!statics role ?add 5," followed by the role's mention, name, or ID. It is important to note that Main Roles should not have any dangerous permissions.

Static Channels refer to channels that are set once and for all, such as the Logging, Mod-Logging, Partnering, and Main Channels. To set a partnering channel, use the command "w!statics CHANNEL ?set 8," where CHANNEL is replaced by the channel's mention, name, or ID. To set the Main Channel, use the command "w!statics CHANNEL ?set 9," again replacing CHANNEL with the appropriate mention, name, or ID.

Static Users consist of Trusted Admins and Extra Owners, who have immunity and will never be punished by Wick for their actions. To add a Trusted Admin, use the command "w!statics user ?add 10," followed by the user's mention, username, usertag, or ID. To add an Extra Owner, use the command "w!statics user ?add 11," again specifying the user's details. While it is not recommended to add Trusted Admins or Extra Owners, it is advisable to add your alternate account as an Extra Owner in case you lose access to your main account.

## Whitelist Stuff
To ensure optimal service with minimal risk of false positives, whitelisting is a crucial step. The table below outlines the objects that can be whitelisted based on their respective commands and types:

!!!success Objects Command Type
- Member w!whitelist @member
- Role w!whitelist @role
- Channel w!whitelist #channel
- Category w!whitelist category-id
- Webhook w!whitelist webhook-id
!!!

In addition to the above, you have the option to whitelist permit roles (i.e., staff roles you have designated within Wick) from Antinuke limitations and blacklist words. This can be done on a case-by-case basis or through a total whitelist, which exempts objects from the entirety of Automod. By taking advantage of these features, you can customize your experience with Wick to suit your needs.

## Automated Moderation
It is strongly advised to review the Whitelist section before attempting to set up the Auto Mod in order to avoid complications. Wick utilizes an adaptive algorithm known as Heat, which sets it apart from other moderation bots, and utilizes public and hidden filters to analyze messages and behavior in channels. These factors contribute to the total heat generated by a user, which diminishes over time to prevent wrongful timing out of regular users.

===- Example
To provide an example, if a message contains both regular content and an advertisement, Wick will calculate the heat generated by the message based on various factors, such as the type of message and the presence of emojis. The Auto Mod will then be triggered if the heat generated exceeds a certain threshold.
===

In the General Settings section, users can adjust various elements of the heat system, such as enabling or disabling the anti-spam filters and adjusting the maximum heat percentage at which Wick will take action. Premium users can access additional features such as the Heat Panic Mode and Auto Server Lockdown.

It is important to note that while the default filters are effective, users should customize them according to their needs, particularly by using the dashboard to access the Whitelist section. With its unique Heat algorithm, Wick's Auto Mod is a highly efficient and reliable tool for moderating Discord channels.

## Panick Mode
Wick's Anti Nuke system is a highly sought-after and crucial feature for any Discord user. It is important to note that Wick's Anti Nuke is enabled by default and can be turned off by using the command "w!antinuke 1 ?off". Additionally, Wick's Anti Nuke system has both minute and hour limits in place, which will result in the quarantine of any Admin who exceeds them. It is recommended that users familiarize themselves with the limits by reviewing them through the dashboard.

One of Wick's Anti Nuke filters is designed to detect malicious activities related to pruning. If users do not wish to utilize this filter, they can turn it off by using the command "w!an 4a ?off".

Furthermore, Wick's Quarantine Hold feature is enabled by default and will monitor any individual who is quarantined, punishing anyone who attempts to interfere with them or bypass the Anti Nuke system. If users do not wish to utilize this feature, they can turn it off.

Wick's Panic Mode system, which is only available with the Premium subscription, is designed to help users manage their server during an emergency situation. To configure this system, users can refer to the short guide provided. Additionally, Wick's Premium subscription also includes a Backups feature, which takes a complete snapshot of the server every three hours and loads the last backup if Panic Mode is triggered.

## Join Gate
Wick offers a highly effective join gate for new members joining your Discord server, which complements the verification system. This join gate has been proven to be an efficient system for blocking out raids and unwanted accounts. In addition, it provides several filters that can be customized according to your preferences.

One of the filters available is the No PfP Filter, which identifies accounts without profile pictures. While not all accounts without profile pictures are raiding accounts, this filter can still be used to eliminate such accounts if desired. To enable or disable this filter, use the command w!jg 2a ?on or ?off, respectively. You can also choose whether Wick timeouts, kicks, bans, or logs the accounts caught by following the format w!jg ACTION ?set 2b.

Another filter is the Account Age Filter, which allows you to accept accounts that are older than a specific number of days. To enable or disable this filter, use the command w!jg 3a ?on or ?off, respectively. You can also use the same format as above to change the action: w!jg ACTION ?set 3b.

The Bot Addition Filter is also available, which must be enabled if you don't want anyone unauthorized adding bots to your server. To enable or disable this filter, use the command w!jg 4a ?on or ?off, respectively. You can also use the same format as above to change the action: w!jg ACTION ?set 4b.

The Advertising Names filter is ideal for blocking new members that have invite links as usernames. To enable or disable this filter, use the command w!jg 5a ?on or ?off, respectively. You can also use the same format as above to change the action: w!jg ACTION ?set 5b.

The Unverified Bots filter is highly recommended as it eliminates bots that are unverified by Discord. To enable or disable this filter, use the command w!jg 6a ?on or ?off, respectively. You can also use the same format as above to change the action: w!jg ACTION ?set 6b.

If you want to eliminate accounts that Wick finds suspicious, the Suspicious Accounts filter is the one to use. To enable or disable this filter, use the command w!jg 7a ?on or ?off, respectively. You can also use the same format as above to change the action: w!jg ACTION ?set 7b.

Lastly, the Username Filter allows you to detect any member that has one of your strict or wildcard words. This feature sanitizes all usernames before checking, making it almost impossible to bypass the filter. To enable or disable this filter, use the same format as above: w!jg 8a ?on or ?off, respectively.

It is important to note that once an account has been flagged and punished, Wick will not lift the punishment if the account later adds a profile picture or has enough days to join. You can have the Unverified Bots filter enabled alongside the Bot Additions Filter with no issues.

## Join Raid
The Join Raid feature offered by Wick is a premium service that allows server owners to monitor and track joins, as well as detect and block malicious raid attacks. This feature is particularly useful for large servers that are at a higher risk of being targeted.

To use Join Raid, it is recommended to review the General Settings, which include Static Flags such as Status, Action, and Warned Roles. By default, the system triggers a flag when 10 accounts join within 10 minutes, but this can be adjusted to suit specific server needs.

In addition to these Static Flags, Join Raid also includes two algorithms, String Flag and Age Flag, which help to detect potential threats. The String Flag algorithm allows for the addition of specific strings using special syntax operators, while the Age Flag algorithm flags any account that is too young. Join Raid also includes a NoPfP Flag, which targets accounts without profile pictures, and an ID Flag, which efficiently targets automated raids.

Overall, the Join Raid system is an effective tool for preventing malicious raids and protecting server communities.

## Verification
To ensure a secure and streamlined process for your server, Wick provides a verification system that utilizes a designated channel featuring a Verify button for users to initiate the verification process. By utilizing the command "w!verification 1", you can enable or disable this feature and specify actions such as Quarantine, Kick, Ban, or None. Additionally, you can set the target audience to Everyone or Suspicious Accounts using the command "w!v X ?set 3" where "X" represents "all" or "suspicious". To adjust the verification duration, use "w!v X ?set 5" with "X" representing the desired duration time.

Moreover, Wick offers different Modes to allow you to customize the verification process, including the Premium-only "Regeneration" mode which generates a new Captcha every specified interval. To adjust the regeneration time, utilize "w!v TIME ?set 12" with "TIME" being the desired interval time. Additionally, the verification process includes Notes sent to the user, which can be disabled using "w!v 13 ?off".

Please note that quarantining bots on join is deprecated, and if the verification mode is set to None and you have Premium, the JoinRaid will enable the Captchas and DM Verification once triggered. The None mode, on the other hand, simply means that Wick will not add the member to Quarantine on join. After the initial setup, Wick will automatically create a verification channel and add it to your server's statistics, though you can manually do so using "w!s #channel ?set 12".

## Miscellaneous
If you desire to customize certain behaviors or set a unique prefix, Wick's Miscellaneous feature is ideal for you. To quickly adjust these settings, please refer to the instructions below.

---

!!!success Completing Your Wick Setup: A Congratulatory Note
Congratulations on successfully completing all the necessary steps to set up Wick! Your dedication and attention to detail have resulted in a fully functional Wick environment. As you continue to explore Wick's capabilities, consider diving deeper into related topics such as customization options and advanced features.
!!!
