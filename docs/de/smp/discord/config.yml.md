# Discord Module Configuration

```yaml
botToken: YOUR TOKEN HERE
```

```yaml
mainGuild: Guild ID
```

```yaml
botSettings:
  onlineStatus: online
  activity: none
  activityMessage: Minecraft
```

```yaml
embedSettings:
  author: YVtils SMP
  authorIconURL: URL
```

```yaml
whitelistFeature:
  channel: CHANNEL ID
  role: ROLE ID 1, ROLE ID 2, ROLE ID ...
```

```yaml
serverInfoCommand:
  permission: PERMISSION
```

```yaml
whitelistCommand:
  permission: PERMISSION
```

```yaml
chatSync:
  enabled: true
  permission: PERMISSION
  channel: CHANNEL ID
```

```yaml
consoleSync:
  enabled: true
  channel: CHANNEL ID
```

```yaml
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
```

```yaml
logChannel: CHANNEL ID
```
