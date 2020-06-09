# Tags

{% hint style="info" %}
This documentation applies only for the British English translation of Cascade. To find information for your language, run the `;usage tags` command or [join our Discord server](https://discord.cascadebot.org)
{% endhint %}

Placeholders can be used within tags to produce custom output based on the user, arguments or channel the command is run in.

#### Server

`{server}` - Displays information about the server. Without arguments, `{server}` returns the server's name

* `{server:id}` - The numeric ID of the server e.g. 488394590458478602
* `{server:region}` - The name of the region e.g. EU Central
* `{server:owner}` - The full name for the server's owner e.g. Cascade\#3186
* `{server:member_count}` - The count of members in the server. 

#### Sender

`{sender}` - Displays information about the user who has run the tag. Without arguments, `{sender}` returns the sender's full name e.g. Cascade\#3186

* `{sender:id}` - The numeric ID of the sender e.g. 135081860790222848
* `{sender:nickname}` - The nickname of the sender e.g. weeryan17.java
* `{sender:name}` - The name of the sender e.g. weeryan17
* `{sender:full_name}` - The full name of the sender e.g. weeryan17\#1258
* `{sender:mention}` - Mentions the sender e.g. @weeryan17

#### Channel

`{channel}` - Display information about the text channel the tag has been run in. Without arguments, `{channel}` returns the channel's name e.g. info

* `{channel:id}` - The numeric ID of the text channel e.g. 548975880924561409
* `{channel:mention}` - Mentions the text  channel e.g. \#support
* `{channel:topic}` - The topic of the text channel
* `{channel:creation}` - The creation date of the text channel
* `{channel:parent}` - The name of the channel's category if there is one

#### Miscellaneous

`{time}` - The current time when the tag is run

`{args:index}` - The argument at the 0-based index that is passed to the tag

> Example: ;tag arguments hi hello  
> `{args:0}` = hi  
> `{args:1}` = hello



