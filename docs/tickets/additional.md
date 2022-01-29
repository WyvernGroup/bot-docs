# Additional Ticket Features

???+ info "Ticket Log"
    A ticket log is a great place to monitor ticket statuses in your server. Set it up with:
    
    `!settings tickets log <#channel>`

???+ info "Closed Ticket Category"
    Want to keep your tickets as a channel, even after they're closed? A closed ticket category is for you! When this option is set,
    closed tickets will be moved to a new category, but the original ticket member will lose access to the channel. Create a new
    category with this command:
    
    `!settings tickets closedcategory new`
    
    Or for advanced users with an existing category:
    
    `!settings tickets closedcategory <category id>`

???+ info "Ticket Claiming"
    Members with the support role will be able to 'claim' tickets, meaning other support representatives will not be able to talk in the ticket.
    This is a great way to stop multiple support members from possibly confusing customers or potentially interrupting each other.

    `!settings tickets claim on`

That's not all! Wyvern's Ticket System has more great features! If you're looking to get more technical, [click here](advanced.md)