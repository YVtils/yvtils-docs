documentation: https://yvtils.net/yvtils-smp/docs
botToken: YOUR TOKEN HERE
mainGuild: Guild ID
botSettings:
  onlineStatus: online
  activity: none
  activityMessage: Minecraft
embedSettings:
  author: YVtils SMP
  authorIconURL: URL
whitelistFeature:
  channel: CHANNEL ID
  role: ROLE ID 1, ROLE ID 2, ROLE ID ...
serverInfoCommand:
  permission: PERMISSION
whitelistCommand:
  permission: PERMISSION
chatSync:
  enabled: true
  permission: PERMISSION
  channel: CHANNEL ID
consoleSync:
  enabled: true
  channel: CHANNEL ID
serverStats:
  enabled: true
  mode: both
  channel: CHANNEL ID
  layout:
    serverStatus:
      text: <emoji> | SERVER <status>
      emoji:
        online: 💚
        offline: ❤️
    serverVersion: 💻 | VERSION <version>
    lastPlayerCount: 🎮 | PLAYERS <count>
    lastRefreshed: ⌚ | <time>
logChannel: CHANNEL ID
