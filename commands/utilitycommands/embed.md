# /embed

### Description:
Sends or edit an embed message<br>

### Usage:
**Options**:<br>
- title : Sets embed title
- description : Sets embed description
- field : Add fields
> - Format: `title | description | inline(true/false) || ...` <br>
> - Each field is seperated by `||`, up to 25 fields can be created <br>
> - To create blank field type this `\u200b|\u200b|true/false`<br>

- colour : Set colour of embed
- author : Set author name
- author icon : Set icon image
- author url : Link author name field
- url : Link title field
- image : Attach image to embed
- thumbnail : Add thumbnail image to embed
- time : Add current time to embed
- footer : Set footer
- footer-icon : Set footer image
> `author icon, image, thumbnail, footer icon` takes in image url<br>
> Profile picture can be added to `author icon, image, thumbnail, footer icon` by typing `-pfp` to add your profile picture and `-server` to add server icon<br><br>

Add reaction role to message in current channel:<br>
`/embed add [options]`<br>
Add reaction role to message in specified channel:<br>
`/embed edit messageid:<String> [options]`<br>

<a class="button prev" href="/#/commands/utilitycommands/twitterfollow" role="button">< Twitter</a>
<a class="button next" href="/#/commands/utilitycommands/welcomemsg" role="button">Welcome Message ></a>