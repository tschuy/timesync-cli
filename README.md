# TimeSync CLI

A simple Python CLI for TimeSync.

## Usage

Create a JSON file in ``$HOME/.timesync`` that looks something like this:

```
{
  "username": "tschuy",
  "password": "password",
  "server": "http://localhost:3000"
}
```

Add this repo to your ``$PATH``, or move ``timesync`` somewhere that's on your
path. Now, run ``timesync``, and you're good to go:

```
tschuy@aqua:(timesync-cli)(master) → timesync
Project: ts
Activity: dev
More activities? [y/n] n
Time worked in seconds: 120
Issue uri: https://github.com/osuosl/timesync-node/issues/123
Month worked: 08
Day worked: 20
Note: Audited js style according to AirBnB's JavaScript guide
Time successfully recorded!
```
