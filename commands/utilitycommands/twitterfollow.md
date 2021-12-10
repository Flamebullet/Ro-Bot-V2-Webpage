# /twitterfollow

### Description:
Get tweets from a twitter user and forward them to discord<br>

### Usage:
> **Take Note**:<br>
> - 'screenname' is the twitter tag(@) of twitter user
> - 'webhookurl' is the Discord server webhook's url, to find the Webhook URL, go to 'Server settings' > 'Integrations' > 'View webhooks' > 'New webhook' , then choose existing webhook or create a new one and click on 'Copy webhook URL'
>> **\*\*Important!**: When creating new webhook remember to set channel to the channel you wish to send the twitter updates in.<br>

> (Hover mouse over image to zoom)<br>
> <img class='docimages left' src="./images/server_settings.png" alt="Server Settings" style="height:320px; vertical-align:middle;"> > <img class='docimages' src="./images/integrations.png" alt="Integrations" style="height:320px; vertical-align:middle;"> > <img class='docimages right' src="./images/webhook.png" alt="Webhook" style="height:320px; vertical-align:middle;">

Follow Twitter user's tweets:<br>
`/twitterfollow follow screenname:<String> webhookurl:<String> imageonly:<Boolean> sendretweet:<Boolean>`<br>
Stop following Twitter user's tweets:<br>
`/twitterfollow unfollow screenname:<String> webhookurl:<String>`<br>

<a class="button prev" href="./#/commands/utilitycommands/reactrole" role="button">< Reaction Role</a>
<a class="button next" href="./#/commands/utilitycommands/embed" role="button">Embed ></a>