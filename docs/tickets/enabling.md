# Tickets Setup

In this guide, we will go over how to setup and basic configuration of the Wyvern ticket module.

!!! tip 
    To view information about all ticket settings, run:

    `!settings tickets`

    To view information about a specific ticket setting, run: (replace <setting> with the name of the setting)

    `!settings tickets <setting>` 

## Setting a Support Role
In order for your support team to respond to issues as soon as possible, we need to set a role that will ping them when
a ticket is created. Type in the following command:

`!settings tickets role <@role>` (make sure you mention the role)

**Example:**
`!settings tickets role @Support`

##Setting a Ticket Category
Next, we need to make a designated category for all the tickets to go to. You can do this by using the following command:

`!settings tickets category new`

Advanced users may already have a ticket category created, in which case you can use the ID in the following command:

`!settings tickets category <category id>`

##Enabling the Ticket Module
Now we have the category and support role set, we can go ahead and enable the module:

`!settings tickets module on`

##Creating the Ticket Panel
That's all the basic configuration done! Now, we need to make a 'panel' that users can click on to open a ticket. To do this,
navigate to your support channel and type the following command: 

`!panel create`

!!! warning
    Please note that your support channel should **not** have the SEND_MESSAGES permission enabled for everyone.


That's it! You now have a (basic) setup of the Wyvern Ticket system. Wyvern's ticket system is very powerful, and has plenty more 
features waiting. [Click here](additional.md) to continue the guide.