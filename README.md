# Initial page

## General Information

### Command Arguments

{% hint style="warning" %}
`<>` and `[]` are arguments to a command. They are required and optional arguments respectively.
{% endhint %}

{% hint style="danger" %}
**DO NOT** type these out in your command. For example, `-new [help me]` is not correct. The correct command would be `-new help me` in this case.
{% endhint %}

* A command name is signified by \[commandName, commandAlias\]. This denotes that all command names in the `[]` server as the same command. In other words, `commandName` and `commandAlias` are the exact same command.
* As mentioned above, `<>` denotes a **required** argument and `[]` denotes an **optional** argument. A default argument may be passed to an optional argument. This is denoted like so: `[foo="bar"]` where the argument would be **foo** and if nothing is supplied to the argument, foo is assigned a value of **"bar"**.
* The current version of the bot allows for flexible command arguments when specifying discord based argument \(channels, users, roles, etc\). This means that if you wanted to pass `@twist` as an argument, you could pass one of the following: `[@twist, twist, twist#7777, 542709669211275296]`

\`\`

