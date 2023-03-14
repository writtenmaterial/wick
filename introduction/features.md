---
order: 100
icon: dot-fill
author:
  name: Robbe
  avatar: https://cdn.discordapp.com/attachments/1034201179716079777/1084940308686589992/Robbe.png
tags: [intro]
---
# Wick's Features
Wick's Anti-Nuke system sets it apart from other Discord Bots with its ability to monitor and detect any changes, planned or spontaneous, that occur within a server. This system is designed to safeguard against actions that can potentially harm your server, such as creation or deletion of channels/roles, bans/kicks, and creation or deletion of webhooks.

To maintain the integrity of this system, Wick also notes any attempts to bypass it and takes appropriate measures, such as stripping off the power of rogue admins or members and quarantining them. The panic mode feature is a complex and efficient system that allows Wick to effectively fend off rapid mass nukes that may be initiated through scripts or specialized bots.

During a lockdown, Wick simultaneously deploys a miniWick that retrieves server information before the nuke trigger, separate from the Wick bot to avoid overburdening its resources. Once the causes are identified and fixed, Wick will load the latest snippet of the server saved through its Restore System, which operates in two scenarios.

If Imaging (Backups) is enabled, Wick will save a backup of the server at regular intervals and load the latest backup when a nuke occurs. Anything that does not match the image will be removed and all deletions that occurred during that short span of time will be reverted back to normal. If Imaging is disabled, Wick will use its memory and Discord to restore the server, although this process may be finicky and may not result in complete restoration.

Discover the full capabilities of Wick's Anti-Nuke system and its panic mode feature, and protect your server against rogue admins and other members who may attempt to cause harm.

---

The Heat System is a crucial tool in managing raids and spam in Wick. It employs an adaptive algorithm known as Heat that adjusts to user actions and scales appropriately with an increase in member activity. Wick also utilizes hidden filters to analyze messages and user behavior, contributing to the total heat which diminishes over time to prevent regular members from being wrongfully silenced. The Heat System factors in a range of message elements, including message repetition, suspicion, advertisement, NSFW and malicious websites, emojis, characters, new lines, mentions, attachments, and blacklist words and links. The system also includes Auto Timeouts and a Panic Mode for targeting raiders, as well as an Auto Lockdown feature to prevent damage from ping raids. Each Heat Filter has its own percentage and action set if triggered, making it a versatile tool for maintaining server security.

---

Discord servers often face the challenge of raiding, which has resulted in the adoption of temporary solutions such as kicking new accounts that join the server. However, such a practice can lead to the loss of genuine new members, which is contrary to the recommended approach by Discord.

To address this issue, Wick offers an advanced verification system with multiple modes that can be customized to suit different types of servers, including big servers, NFT/Crypto servers, among others. The verification system is highly configurable and can target everyone or just suspicious accounts, using options such as Captcha, web verification, or instant verification.

The verification system can be personalized by configuring the various settings according to the server's needs and the preferences of its admins. The system scales to the user's input settings to ensure optimal performance.

By using Wick's verification system, raid accounts can be eliminated, while allowing genuine new members to join with ease. 

!!!danger A Significant Threat to Personal Safety
Wick will never ask users to scan a QR code to access a specific server.
!!!

---

To ensure the security of your community, Wick offers an on-join security system that utilizes multiple filters to identify potential security threats. Acting as a firewall, this system enables administrators to establish their own preferences for what actions should be taken in response to specific triggers.

For instance, Wick can detect accounts without avatars, which are often associated with raiding bots and spammers. In addition, administrators can establish age requirements for new accounts and even take action against unauthorized bot additions.

To further safeguard your community, Wick can also filter out unverified bots and accounts that contain discord invites. Moreover, you can now use Wick's username filter to target accounts with specific usernames that fall under your requirements.

We highly recommend enabling the Bot Addition Filter for all server owners. With customizable filters and actions, Wick's JoinGate system provides a powerful tool for ensuring the security and integrity of your community.

---

To address the issue of potential server raids, we suggest utilizing JoinRaid, a tool designed to monitor the influx of account joins over a specified time period and detect any suspicious activity. JoinRaid employs a range of algorithms to flag potentially problematic accounts and trigger immediate action, such as issuing warnings to designated roles or taking punitive measures against flagged accounts and their associated contributors. JoinRaid runs continuously and is not limited by any joingate constraints.

Moreover, admins can access a comprehensive log of all activity captured by JoinRaid, including a link to Wick's website that provides a complete list of identified accounts. We encourage you to consider implementing JoinRaid as part of your server management strategy to proactively address potential security threats.