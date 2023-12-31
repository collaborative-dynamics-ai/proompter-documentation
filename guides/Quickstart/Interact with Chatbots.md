# Chatbots

## How to talk to the chatbots?
> You can either mention a chatbot or reply to one of it's messages
> Editing the message by including the mention afterwards doesn't work. If you forgot to mention the bot, either send a message that only contains the mention, or delete and resend your message with the mention

> On mobile the role suggestions don't work at all, and on Desktop it often happens that it will not show the desired roles when entering the `@` sign into the chat. In those cases you can copy & paste the raw [role IDs](../Good%20to%20Know/Get%20IDs%20of%20Roles-Users-Channels). Those are available in the <#1137217914802548796> post of each bot (`Role ID`) and also in the results of the [/find chatbot](../../slash-command/find####/find%20chatbot%20by-name) command. They look like this: `<@&1234567890>`. Copy the whole thing and paste it into the chat, if done correctly, it will turn into the blue role mentioned


---


## How to talk to the chatbots privately?
> **Note:** In the scope of this Discord Server, the term `conversation` is used interchangeably with `text-channel`/`thread`, unless otherwise mentioned. Check [this](../../reference/Conversation) for more details

> Direct messages are not supported, due to how the chatbots work. You can create a private thread on this Discord Server to have conversations with all the different chatbots

### Method 1
- Go to any of the text channels you can write in
- Execute the [/conversation start](../../slash-command/conversation####/conversation%20start) command
  - Provide a `name`
  - Press Enter



### Method 2
- Go to any of the text-channels you can write in
- Click on the `#` at the top right next to the search bar
![[thread-list.png]]


- Click on `Create`
![[new-thread.png]]


- Give it any title and enable `Only people you invite and moderators can see` to make it a private thread. Or leave it unticked to make it a public thread
![[set-private.png]]


---

## Context Management
> If you delete or edit a message, it will do so in the context too. You can get more details about the loaded context be using the [**/context**](proompter-documentation/slash-command/context.md####/context%20details) command



# What are inactive bots? How to deal with them?
> Discord has a role limit of 250 per server. Our chatbots get called by roles, so each bot needs it's own role. Due to the huge amount of personas, we needed a workaround to be able to have more bots than role. Thats why bots can be inactive. An inactive bot cannot be called, as it doesn't have a role associated
> When a bot is inactive, it has an "Activate Chatbot" button in it's [chatbot library](<https://discord.com/channels/1100933695986208849/1137217914802548796>) post. Simply click on it, wait a quick moment until the bot is ready, and then interact with it by mentioning the role