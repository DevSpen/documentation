---
description: 'Returns the amount of members, in the current Guild.'
---

# $membersCount

This function returns the amount of members in the current guild

```javascript
$membersCount[guildID (optional);status (optional)]
```

```javascript
bot.command({
name: "info",
code: `Members: $membersCount`
})
```

{% hint style="danger" %}
This only works in Guilds, otherwise will return an error.  
Prototype: $allMembersCount
{% endhint %}

### Member Count of a certain status

* $membersCount\[$guildID;online\] - returns the amount of online people in the guild.
* $membersCount\[$guildID;Idle\] - returns the amount of idle people in the guild.
* $membersCount\[$guildID;dnd\] - returns the amount of  people in the guild.
* $membersCount\[$guildID;invisible\] - returns the amount of offline people in the guild.
