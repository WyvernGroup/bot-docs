# Changelog
###### Last updated: 04/02/22
=== "Major Releases"
    ##v1.5.0
    ???+ note "Bot Rewrite - 04/02/22"
        We're so sorry for the lack of updates over the past 3 months, but this update alone is bigger than all our previous
        updates combined. Unfortunately, most of our changes happened behind the scenes in terms of our backend infrastructure,
        if we had time to add more to the frontend of the bot, this could easily have been 2.0.0.

        ###General Overhaul
        This update, we focused on polishing the bot and ensuring it was of the highest quality we could produce. Many bugs
        were squashed and the overall ease of use of the bot has hopefully improved. Additionally, you should notice much
        lower latency when using the bot, as we have drastically improved our backend infrastructure for handling commands.

        ###Documentation
        Having a fantastic bot packed with features is great, but we felt it was incredibly important to be more transparent
        with our users and provide easy access to official guides. We are still working on adding content to our documentation,
        and would grealty appreciate your help! If you have any suggestions, spot a mistake or wish to write a page, please
        make a pull request/issue on the <a href="https://github.com/WyvernGroup/bot-docs/" target="_blank">github repository</a>.

        ###Premium
        As our bot continues to grow, requiring more server resources and more development time, we decided to create an 
        option for people to support us. You can learn more <a href="https://patreon.com/wyvernbot" target="_blank">here</a>,
        or view the [documentation page](/support-us/premium).

        ###Giveaways
        Giveaways are back! Get started by running `!g help`

        ###Auto Ticket Closing when Member Leaves
        A great new addition to our ticket options, automatically closing a ticket if the member who opened it leaves the
        server. This is a fantastic way to prevent 'ghost tickets' from piling up. Our guide to this feature can be
        found [here](/tickets/advanced).

        ###Image Filter Command
        With this new command, you can pick from a range of filters to apply to your own and friends profile pictures! 

        ###Subscribe Command
        The best way to keep up to date with all things Wyvern! Simply run `!subscribe` in your own Discord server, and Wyvern
        will create a new channel where special notifications from developers will be sent.

        ###Purge using Message Link
        You can now supply a message link instead of the number of messages to purge. This will purge all messages **up to** the
        message you link to.

        ###Moderation Policy Setting
        You can now allow those with the appropriate permissions to disregard the role hierarchy when executing moderation
        commands. Don't worry, this feature is on strict by default (role hierarchy is taken into account).

        ###Vote Leaderboard
        A brand new, anonymous leaderboard displaying how many votes the person above and below you is away. You can view
        information about this feature and the entire voting system [here](/support-us/vote).

        **New:** The top few people will soon receive a prize at the end of every month! Get voting!

        ###Additional Features
        
        * Escape automatic quoting by putting an exclamation mark (!) infront of the message link
        * Updated the activities list (we recommend inviting our <a href="https://discord.com/api/oauth2/authorize?client_id=882163749077807125&permissions=2049&scope=bot%20applications.commands" target="_blank">brand new dedicated bot</a> for this, launching soon)
        * Added 2 new vote sites and overhauled voting sessions
        * We have changed how our analytics collection system works, you should take a look at the privacy policy below.
        * [Privacy Policy](/legal/privacy)
        * View server command now DMs the user to hide connection details (will be an ephemeral / cmd soon)
        * Link your Wyvern Hosting account to Discord

        Ben: All features, Bug fixes + Testing
        
        speaking of testing, did I mention we're [hiring them?](/jobs/tester)

    ##v1.4.0
    ??? note "Utility Update - 28/10/21"
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

    ##v1.3.0
    ??? note "Ticket Update - 26/09/21"
        ###Ticket Module
        Creating and managing tickets is easier than ever with Wyvern. You can create a panel with a simple one-click button, and even disable/enable it to control the flow of tickets. Features:

        * Adding/removing users from a ticket
        * Transcripts
        * Setting a category where closed tickets will be archived to
        * Claiming
        
        ###Hosting Module
        This module was created for customers of our sister server Wyvern Hosting to use. It allows you to control your server straight from the discord bot. Connecting your account is easy with the auth command. Features:

        * Backups
        * Stop/start/restart your server
        * View your server resources
        * Send a command directly to your server
        * View basic details, e.g. connection information
        
        ###Vote Rewards
        Wyvern now offers rewards if you vote for us. For more information, run the vote command. As of currently, the rewards for voting are the following:

        * 25% extra levelling XP in all servers
        * A voters role in the Wyvern Studios Discord.
        Each vote gives you an additional 6 hours of benefits. You can vote on each platform every 12 hours.
        
        ###Smaller Features:

        * Emoji Steal command
        * Information command
        * Nuke confirmation
        * Rewrite of Settings command (much more user friendly now!)
        * Missing Permissions Warning
        * Activities Rotation
        * Countless bug fixes

    ##v1.2.1
    ??? note "Configuration Update - 04/09/21"
        ###New Database
        Our new database and way of fetching data is much more efficient, allowing us to store more configuration options per server and fetch them easily. Migration is automatic and happens behind the scenes, but if you notice any problems, please contact our support team.
        
        ###Settings Command
        With this new settings command comes new configuration options and a much more straight forward way of configuring your server. View the syntax using !help settings. New options:

        * Blacklist commands (does not apply to users with the ADMINISTRATOR permission).
        * Disable levelling
        * Fixed countless typos and bugs
        * Improved backend data handling and analytics collection

    ##v1.2.0
    ??? note "General Overhaul - 24/08/21"
        ###Added
        * AFK System
        * Bug Utilities
        * Invitebot Command
        * Linkbuttons Command
        * Ping Command
        * Uptime Command
        * Userreport Command
        * Warnings Command
        
        ###Updated
        * Help Command (more user-friendly interface)
        * Levelling
        * Giveaways
        * Error messages rewritten to provide more useful responses
        * Every command was overhauled, but some changes were minor

        ###Temporarily Disabled
        - Music

    ##v1.1.1
    ??? note "Music Update - 25/05/21"
        Added music commands to the bot!

    ##v1.0.1
    ??? note "Purge Command - 21/05/21"
        Minimal bug fixes such as making `!purge` command more specifically delete messages.
        (Moderation is under development and will be pushed out ASAP)

    ##v1.0.0
    ??? note "Release - 19/05/21"
        Core bot features have been rolled out. Bot has successfully been hosted and is ready to be added to servers.
        ###Current Features
        
        * Giveaways
        * Purge/Nuke


=== "Improvements"

    ##v1.5.0-2
    ???+ note "Database Issues - 08/02/22"
        Fixed a few notable issues where a small group of users were unable to interact with the bot due to database issues.

    ##v1.5.0-1
    ??? note "Hotfix - 04/02/22"
        The changelog for this version is not available currently.

    ##v1.4.0-2
    ??? note "Minor bug fixes - 01/11/21"
        The changelog for this version is not available currently.

    ##v1.4.0-1
    ??? note "Emergency Vote Patch - 29/10/21"
        This was a silent update that involved the fix of votes not being received. Votes did not expire during this time to allow people to keep their streaks. As of the release of this update, vote timers have been re-enabled.

        * Fixed votes not being received and processed
        * Unix command can identify which conversion you are using without a subcommand
        * Minor bug fixes
