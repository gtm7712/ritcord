# Dyno Commands

**You can use the plaintext user nickname, ping the user, or take the user ID using developer mode. We prefer the user ID since its guaranteed to target the proper account.**

[Dyno Documentation](https://docs.dyno.gg/en/commands/)

All these commands have slash versions too, just make sure to use the proper variables for them, and *make sure you use the Dyno commands*.

## Punishments

### Bans

Bans a user from a server for a period of time. (saves messages)

```
;ban save <userid> <time> <reason>
```

Bans a user from the server indefinitely.
```
;ban <userid> <reason>
```

Unbans a user from the server.
```
;unban <userid>
```

### Kicks

Kicks a user from a server.
```
;kick <userid> <reason>
```

### Mutes

Mutes a user from speaking in a server for a period of time.
```
;mute <userid> <time> <reason>
```

Mutes a user from speaking in a server indefinitely.
```
;mute <userid> <reason>
```

Unmutes a user from a server.
```
;unmute <userid>
```

### Warns

Warns a user
```
;warn <userid> <reason>
```

### Updating punishment duration

1. Get the punishment ID number using `modlogs`
2. `;duration <punishmentid> <newtime>`

## Punishment Details

### Search a user for punishments

Also gets punishment IDs
```
;modlogs <userid>
```

## Punishment Information

Gives info about a punishment that a user received (who did it, when, etc)
```
;case <punishmentid>
```

### Update reason

```
;reason <punishmentid> <reason>
```

## Warning Information

**Warnings are separate from punishments, so they have their own commands**

### List Warnings

```
;warnings <userid>
```

### Delete Warning

```
;delwarn <punishmentid>
```

### Update Reason

```
;reason <punishmentid> <reason>
```

