# Nexus Red-discord Bot Cogs

**Role Reminder** • Notifies & messages users when they lose their Top Donator, VIP or VIP+ role 

  - `[p]settopdonorole <Role>` - Sets the Top Donator role to be listened to
  - `[p]setviprole <Role>` - Sets the VIP role to be listened to
  - `[p]setvipplusrole <Role>` - Sets the VIP+ role to be listened to

**Custom Roles** • Allows nitro boosters to create a custom role

  - `[p]role <hexcode> [RoleName]` - Creates a custom role and assigns it to the command author
  - `[p]disallowrolename [RoleName]` - Adds the specified role name to the list of disallowed role names
  - `[p]allowrolename [RoleName]` - Removes the specified role name from the list of disallowed role names
  - `[p]removememberrole <Member>` - Removes the specified members custom role

**Custom Channels** • Allows nitro boosters to create custom text and voice channels

  - `[p]ns category` - Creates the category that custom channels will be created in
  - `[p]ns wipe` - Removes all related channels and categories from the discord server
  - `[p]privatechannel create <text>` - Creates a private text channel
  - `[p]privatechannel create <voice>` - Creates a private voice channel
  - `[p]privatechannel add <Member> <text/voice>` - Give a member access to a private channel
  - `[p]privatechannel remove <Member> <text/voice>` - Revoke a members access to a private channel
  - `[p]privatechannel rename <text/voice> [name]` - Change the name of a pricate channel
  - `[p]privatechannel delete <text/voice>` - Delete a custom channel

**Claim** • Lets nitro boosters claim 50 tokens/week on the NexusNation store and reminds them 

  - `[p]linksteam <SteamID 64>` - Link your steam account to the bot
  - `[p]claim` - Claim 50 tokens once a week

**TNN Tips** • Responds to keywords/phrases in the NexusNation discord server

  - `[p]missing` - Shows the map missing help message
  - `[p]differs` - Shows the map differs help message
  - `[p]appeal` - Shows the punishment appeal help message
  - `[p]apply` - Shows the staff application help message
  - `[p]report` - Shows the player report help message
  - `[p]bugreport` - Shows the bug report help message
  - `[p]calladmin` - Shows the calladmin help message
  - `[p]vip` - Shows information about VIP and VIP+
  - `[p]setlogschannel` - Sets the text channel that logs for the tips cog will be sent to
  - `[p]tblacklist <Member>` - Prevents a user from triggering help messages
  - `[p]tblacklist <Category>` - Prevents help messages from being triggered within certain categories
