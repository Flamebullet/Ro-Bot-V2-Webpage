# /twitch

### Description:

Twitch going live notification integration to send a notification to a discord channel when a streamer is going live.<br>

### Usage:

Add a streamer to send notification when they go live:<br>
`/twitch follow twitchurl:<String> user:<User:optional> mention:<Role:optional>`<br>
Remove a user to send notification when they go live:<br>
`/twitch unfollow twitchurl:<String>`<br>
View all followed users in the server:<br>
`/twitch followings`<br>
Remove init settings:<br>
`/twitch uninit`<br>
Setup some settings for twitch going live notification integration:<br>
`/twitch init channel:<Channel> ispublic:<Boolean>`<br>

> **Important!**:<br>
>
> `/twitch init` should be used first to initialized the server before the rest of the command will work.<br>

<a class="button prev" href="./#/commands/utilitycommands/timeout" role="button">< Timeout</a>
<a class="button next" href="./#/commands/utilitycommands/welcomemsg" role="button">Welcome message ></a>
