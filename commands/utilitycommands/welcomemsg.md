# /welcomemsg

### Description:

Setup a custom welcome message for the server<br>

### Usage:

Create a welcome message for the server:<br>
`/welcomemsg add channel:<Text-Channel> message:<String> user-role:<?Role> bot-role:<?Role>`<br>

> **Take Note**:<br>
>
> -   `user-role` and `bot-role` are optional, that when added will automatically assign respective role to user or bot when they join
> -   `${member}` and `${role}` can be added to the message to mention the new member and role in the message<br><br>
>
> Example to send "Welcome @member for joining! @role has been added" to `#welcome-channel`:
>
> ```
> /welcomemsg add channel:#welcome-channel message:Welcome ${member} for joining! ${role} has been added
> ```

Remove welcome message from server:<br>
`/welcomemsg remove`<br>

<a class="button prev" href="./#/commands/utilitycommands/embed" role="button">< Embed</a>
<a class="button next" href="./#/commands/utilitycommands/getwebhook" role="button">Get Webhook ></a>
