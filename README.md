# alfred

[![.NET](https://github.com/jbies121/alfred/actions/workflows/dotnet.yml/badge.svg?branch=develop)](https://github.com/jbies121/alfred/actions/workflows/dotnet.yml)

The Ghost of Michael Masi Discord Bot, a fork of Alfred. He's here to help.

# Requirements
You will need a bot token to be the face of your discord bot: https://discord.com/developers/docs/topics/oauth2

## Build
Create a file named config.yml

```yaml
testguild: <guild Id>
tokens:
  discord: <OAuth token>
```

Run build from within the project directory:
```bash
dotnet build
```

Run compiled dll (default output path example)
```bash
dotnet run ./bin/Debug/net6.0/aflred.dll
```
