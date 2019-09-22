---
description: Settings Commands
---

# Premium Commands

{% hint style="danger" %}
All settings commands require the `Manage Server` permission in Discord.
{% endhint %}

{% hint style="info" %}
All settings commands have aliases set to use the word `set` at the beginning of the command. For example, `adminclose` and `setadminclose` are identical.
{% endhint %}

| Command | Example | Description | Default |
| :--- | :--- | :--- | :--- |
| `adminclose <Boolean>` | `-adminclose true` | Disallow non **Ticketer Admins** from closing tickets | `false` |
| `cleanall <Boolean>` | `-cleanall true` | Deletes all invocation of commands other than the `new` command after 10 seconds of the command running. This includes any responses the command may trigger. | `false` |
| `cleannew <Boolean>` | `-cleannew true` | Deletes all invocation of the `new` command after 10 seconds of the command running. This includes any responses the command may trigger. | `false` |
| `cleanchannel <Channel>` | `-cleanchannel #channel` | Sets a channel to only allow `new` invocations and nothing else | `N/A` |
| `dmoncleanchannel <dmOnCleanChannel>` | `-dmoncleanchannel true` | When a channel is set to be a "clean channel", Ticketer will DM a user if they try to type in the channel | `false` |
| `inactivetime <Number>` | `-inactivetime 120` | Sets the time for a channel to be deleted after the use of the `inactive` command **in minutes**. For example, `inactive 60` would result in a channel being closed **1 hour** after being marked inactive | `120` |
| `joinwelcomemessage <String>` | `-joinwelcomemessage Hello and welcome!` | Sets the ticket welcome message to be displayed when a ticket is created on join. Must be less than **2000 characters** and must have `ticketonjoin` enabled | `N/A` |
| `maxtickets <Number>` | `-maxtickets 3` | Sets the maximum number of tickets a user may have open in a guild at any given time. A value of **-1** will allow for unlimited tickets | `-1` |
| `prefix <String>` | `-prefix !` | Sets the command prefix. In other words, using the example to the left, commands would be run as `!new` rather than `-new`. In the event you forget your prefix, `@Ticketer` will always be a default prefix | `-`**`||`**`@Ticketer` |
| `sendtouser <Boolean>` | `-sendtouser true` | Sets whether transcripts should be DM'd to a user on the closing of their ticket. Requires `transcripts` to be enabled | `false` |
| `ticketonjoin <Boolean>` | `-ticketonjoin true` | Sets whether a ticket should be created for a user when they join a guild | `false` |
| `ticketprefix <String>` | `-ticketprefix ticket` | Sets the prefix for tickets in the guild. In other words, this is the text that gets displayed in every ticket channel name other than the ticket number | `ticket` |
| `transcriptchannel <Channel||Boolean>` | `-transcriptchannel #channel` | Sets a channel for transcripts to be sent to rather than sending to the default log channel. Requires `transcripts` to be enabled | `false` |
| `transcripts <Boolean>` | `-transcripts true` | Sets whether transcripts should be generated on closing a ticket. Requires a `logchannel` or a `transcriptchannel` to be set | `false` |
| `welcomemessage <String>` | `-welcomemessage <String>` | Sets the ticket welcome message to be displayed when a ticket is created. Must be less than **2000 characters** | `N/A` |

