# Changelog
###### Last updated: 29/10/21

=== "Major Releases"
    ##v1.4.0
    ???+ note "Utility Update - 28/10/21"
        ###Auto Ticket Closing
        When you have a fantastic support team helping so many people at the same time, it's hard to keep track of all the tickets you have open. With Wyvern's ticket system, you can now specify how long a ticket should stay open for before it is closed automatically. The best part? It's absolutely free. You don't need to vote, nor do you need to subscribe to our patreon. 
    
        * Can be configured globally or on a per-ticket basis.
        * Automatically sends a message and DMs any users added to the ticket before the closure date.
        * Will DM any users added to the ticket when it is closed automatically.
        
        ###Improved Purge Command
        Our new purge command allows for all types of users. Whether you only need to purge a set amount of messages, or if you need to filter them from different users containing a certain string. 
        
        * Flags allow for as many filters to be applied as the user desires.
    
        ### Levelling Updates
        Thanks to community feedback, we've added more customisation options to the levelling module.
    
        * Redirect all levelling messages to a specific channel.
        * Change the level up message with placeholders.
        * XP Boost Roles allow you to tweak the amount of XP each role in your server gets.
    
        ### Quotes
        Have you ever seen a message from another server that you need to show your friend? Or maybe you have a quotebook channel and want to preserve the content of a message? Now you can!
    
        * Disabled by default, enable it in the settings command.
        * Simply send a message link and the bot will reply with the content.
        * Opt-out of other servers quoting your messages.
    
        _quoting only works cross-servers if the bot is in both servers and the target server has not opted-out of external quoting_ 
    
        ###Smaller Features
        * Settings & Help command now have menus attached to them to make navigation easier.
        * Ability to add people to tickets based on their username.
        * Activities command has been re-enabled after a complete redesign!
        * Settings command now has categories to easily navigate settings.
        * Added the ability to change the content of the ticket panel message.
        * Tip command - random tips about the bot you might not have known!
        * Ticket Closure Notifications when clicking the close button
        * Snowflake Command
        * Convert unix time command
        * Countless bug fixes

        Also this update, we've migrated our ticket system to a faster and more efficient database to manage growth better in the future. Whenever you read this, migration is already complete. If you notice any problems with old tickets, please open a ticket in this server.

        ###Premium Features
        As you may have noticed, everything in this update is completely free, and we want to keep it that way. However, we need your help. Whether you can support us financially or not, please consider subscribing to our [Patreon](https://www.patreon.com/wyvernbot) or simply voting for the bot for absolutely free (`!vote`). Wyvern is growing at an incredible rate, and that results in higher operating costs. To keep our features free, please consider subscribing.

        Ben:  All features + Bug fixes

        Wyvern Testers: Testing

    ##v1.3.1
    ??? note "Ticket Update (Week One Patch) - 01/10/21"
        Following feedback from **v1.3.0**, we have released a patch to fix some bugs that slipped under our radar, and a few small features.
    
        ###Features
        * There is now a button under missing permission warnings to disable future warnings if you are already aware of the problem and do not wish to fix it.
        * Unique error codes are now generated and sent with errors. If you encounter any problems using Wyvern, you can open a ticket and send us this error code for possible fixes.
        * Added vote cooldowns to the vote message (tells you when you can next vote on each platform)
        * Permission restrictions - we are committed to making Wyvern as easy as possible to use. Now, when you try to run a command that Wyvern does not have sufficient permissions to execute, the bot will provide you with the permissions it needs.
    
        ###Additions
        * Fixed vote messages showing times from the previous vote
        * The levelling module will remain on for new servers, however there is a new option called levellingMessages which will now be turned off by default
        * Added alias 'votes' to the vote command
        * Fixed punishment commands responding twice with different errors
        * Fixed the report command not sending reports properly
        * The bot must now have the `SEND_MESSAGES` and `READ_MESSAGE_HISTORY` permissions for any aspect of it to function in a channel. If you don't want levelling in that channel or the bot to be able to respond to commands, deny any of these permissions.
        * You can no longer set roles/channels in the settings command that the bot cannot access.


=== "Improvements"

    ##v1.4.0.2
    ??? note "Minor bug fixes"
        The changelog for this version is not available currently.

    ##v1.4.0.1
    ???+ note "Emergency Vote Patch - 29/10/21"
        This was a silent update that involved the fix of votes not being received. Votes did not expire during this time to allow people to keep their streaks. As of the release of this update, vote timers have been re-enabled.

        * Fixed votes not being received and processed
        * Unix command can identify which conversion you are using without a subcommand
        * Minor bug fixes
