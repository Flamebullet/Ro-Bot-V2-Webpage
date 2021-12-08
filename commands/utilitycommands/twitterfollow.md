# /twitterfollow

### Description:
Get tweets from a twitter user and forward them to discord<br>

### Usage:
> **Take Note**:<br>
> - 'screenname' is the twitter tag(@) of twitter user
> - 'webhookurl' the Discord server webhook's url, to create a webhook go to 'Server settings' > 'Integrations' > 'View webhooks' > 'New webhook'. After setting the channel for the webhook, click on 'Copy webhook URL'<br>

Get infomation of specified user:<br>
`/twitterfollow follow screenname:<String> webhookurl:<String> imageonly:<Boolean> sendretweet:<Boolean>`<br>
Get infomation of current server:<br>
`/twitterfollow unfollow screenname:<String> webhookurl:<String>`<br>
