#Auto Closing Tickets
Auto closing tickets is a great way to keep on top of old tickets and avoid clutter. There are two options for 
automatically closing tickets, both or just one can be enabled.

##Time-based
The time based option will close a ticket after a certain amount of time has elapsed since the last message. This can range
from 1 hour to 5 days. Set the default duration with the following command: (this will not affect tickets already opened)

`!settings tickets duration <number of hours (between 1 and 120)>`

Additionally, this can be modified (and disabled) on a per-ticket basis. You can use the button on a ticket embed
or the `acd` (auto close duration) command to be more specific.

##Member-based
Additionally, tickets can be closed as soon as the member who opened it leaves the server to avoid 'ghost tickets' from
building up. Enable it with the following command:

`!settings tickets memberLeave on`

Thanks for reading our ticket guide! We hope you found it useful.