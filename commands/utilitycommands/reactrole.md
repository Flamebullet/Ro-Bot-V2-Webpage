# /reactrole

### Description:

Get Discord information of specified user/server<br>

### Usage:

Add reaction role to message in current channel:<br>
`/reactrole add messageid:<String> role:<Role> emoji:<String> action:add/remove/kick`<br>
Add reaction role to message in specified channel:<br>
`/reactrole add messageid:<String> role:<Role> emoji:<String> action:add/remove/kick channel:<Text Channel>`<br>

> **Take Note**:<br>
>
> -   Action can only be add/remove/kick
> -   add assigns role to user, remove take the role away, kick kicks member from server when reacted
> -   When adding action of kick you can set the role to any role, perferably the role @everyone<br>

Remove reaction role with selected emoji from message:<br>
`/reactrole removeemoji messageid:<String> emoji:<String> `<br>
Remove reaction role that assigns selected role from message:<br>
`/reactrole removeroleid messageid:<String> role:<Role> `<br>

<a class="button prev" href="./#/commands/utilitycommands/report" role="button">< Report</a>
<a class="button next" href="./#/commands/utilitycommands/reactroledd" role="button">Reaction Role Dropdown ></a>
