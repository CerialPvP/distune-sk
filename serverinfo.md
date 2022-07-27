## Server Info - Role method

**Last updated at 27/7/22, 16:52 GMT+3**

Because DiSky's `if member is a bot` condition is not working, we are resorting to work with roles. If you don't know, when a bot joins a server it makes a role
with all its permissions defined in the invite page of the bot.

For the bot to give you the true count of the members, put the DisTune role above all of the bot roles (not your custom "bot" role, the role which comes with bots you invite), otherwise DisTune will fail to detect all of your roles.

