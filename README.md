# SpamAssassinRules
SpamAssassin rules to be implemented to help reduce SPAM on VestaCP servers.

## Credits
Credits: http://www.pettingers.org/annoyances/sa-rules.html

## How to install these rules on a VestaCP Server
Create a new file `custom_SA-rules.cf` in the directory `/etc/mail/spamassassin/` with the content from `custom_SA-rules.cf`

Now restart SpamAssassin with
```
service spamassassin restart
```
