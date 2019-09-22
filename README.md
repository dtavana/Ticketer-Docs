---
description: General information about the Ticketer Bot
---

# General Information

## Command Arguments

{% hint style="warning" %}
`<>` and `[]` are arguments to a command. They are required and optional arguments respectively.
{% endhint %}

{% hint style="warning" %}
`||` denotes OR and `&&` denotes AND.
{% endhint %}

{% hint style="danger" %}
**DO NOT** type these out in your command. For example, `-new [help me]` is not correct. The correct command would be `-new help me` in this case.
{% endhint %}

* A command name is signified by \[commandName, commandAlias\]. This denotes that all command names in the `[]` server as the same command. In other words, `commandName` and `commandAlias` are the exact same command. Settings commands due to include their aliases that are started by `set` in the documentation, however, they do exist.
* As mentioned above, `<>` denotes a **required** argument and `[]` denotes an **optional** argument. A default argument may be passed to an optional argument. This is denoted like so: `[foo="bar"]` where the argument would be **foo** and if nothing is supplied to the argument, foo is assigned a value of **"bar"**.
* The current version of the bot allows for flexible command arguments when specifying discord based argument \(channels, users, roles, etc\). This means that if you wanted to pass `@twist` as an argument, you could pass one of the following: `[@twist, twist, twist#7777, 542709669211275296]`

### Command Argument Types

{% hint style="warning" %}
The allowed value examples are simply **examples**. In other words, a String argument can be something other than `text`.
{% endhint %}

| Argument Name | Allowed Values Examples |
| :--- | :--- |
| Boolean | `true`**\|\|**`false` |
| String | `text` |
| Number | `123` |
| Channel | `#channel` |
| User | `@twist` |
| Role | `@Ticketer Admin` |

## Free vs. Premium

{% hint style="info" %}
All free features are included in premium
{% endhint %}

| Feature | Free/Premium | Description |
| :---: | :---: | :---: |
| HTML Transcripts | Premium | Allows a complete transcript of a ticket to be exported into a HTML file for record keeping |
| Command Prefix | Premium | Change the default `-` prefix |
| Ticket Prefix | Premium | Change the default ticket text before a ticket channel |
| Max Tickets | Premium | Change the maximum tickets a user may have open at one time per guild |
| Custom Welcome Message | Premium | Change the welcome message that is displayed in tickets at the time of creation. Allows for :server: and :user: in the message to be replaced with the server name or user that created the ticket |
| Ticket On Join | Premium | Allow for a ticket to be created when a user joins a guild |
| Log Ticket Actions | Free | Log Ticket actions such as opening, closing, and more |
| Blacklist Users | Free | Disallow users from creating tickets |
| Enforce Subject | Free | Disallow ticket creation without a subject |
| Inactive Tickets | Free | Deletes a ticket after a default of 120 minutes \(can be changed with premium\) once marked inactive |

