#### Commands

##### Add a new saved message
msg = text to be used for retrieval  
`/add msg < saved message text >`  

##### Show a list of saved messages
`/saved`  


##### Display group rules
`/rules`  


##### Set the rules for the chat
Single space after command is must  
`/setrules <rules text>`


##### Change Chat Title/Name
`/title`  


##### Pin a message
`/pin` 
Reply to a message with this command to pin this message.  
Works only in supergroups. 


##### Unpin a message
`/unpin` 
To unpin a pinned message.  
Works only in supergroups.


##### Kick a user  
`/kick`  
Reply to a person's message with this command to warn him


##### Warn a user,user auto-kicked on 3 warns
`/warn`  
Reply to a person's message with this command to warn him


##### Retrieve a saved message  
`#saved`  
Retrieve a saved message , saved with shortcut 'saved'


##### Sticker Control
On - No more stickers  
Off - Stickers allowed  
`/sticker on/off`


##### Voice Control
On - No more voice messages  
Off - Voice messages allowed  
`/voice on/off`


##### Video Control
On - No more videos  
Off - Videos allowed  
`/video on/off`


##### Photo Control
On - No more photos  
Off - Photos allowed  
`/photos on/off`


##### Report a message
`/report`  
Reply to message with this command to report it.
Bot PMs the admins with the message.
The PMed message has a link to the message if the grp is
a supergroup with defines username.


##### Admin Only Mode
Allows only admins to send messsages, all messages by non  
admins are auto-deleted.
This does not prevent any bot from sending messages as 
Telegram API does not allow any interaction with other bots. Hence
I do not have any clue as to what other bots are sending/receiving.
Highly useful for spam control !!!
`/adminmmode on/off`

##### Refresh Administrators List
Use this command to refresh the list of administrators for a group.
The bot will do this periodically(WIP),but currently requires users to use this command.