# Backup Plan

This directory contains information about my personal backup strategies, desaster recovery plans and some scripts and
other tools to automate parts of that process.

I try to follow a 3-2-1 strategy in general, while selectively omitting some redundancy for less important data.
```
3 copies total of your (important) data
2 of those copies are on different media
1 of those copies are remote
```

Especially for the last part, I do limit my strategy to either **very** important or lightweight data, since I am
somewhat limited on budget.

## Backup Strategy

### Subjects

| Subject                | Description                                                                                                    | Priority  |
|------------------------|----------------------------------------------------------------------------------------------------------------|-----------|
| Desktop (Local Files)  | Data on my Debian 12 Desktop (+ secondary Win11 SSD)                                                           | Normal    |
| OrangePi configuration | Basic configuration of my OPi5 (System settings, apt sources, local files, ...)                                | Normal    |
| Credentials            | Logins, passwords, keys, ... (Mostly managed via Vaultwarden)                                                  | Very high |
| User configuration     | Basically dotfiles (On all systems)                                                                            | Low       |
| Media                  | Media files from Jellyfin & Audiobookshelf                                                                     | Low       |
| Cloud storage          | Personal photo library, Calendar, Contacts, Document storage, Notes, ... (Currently all managed via Nextcloud) | Normal    |
| Gameservers            | Minecraft worlds, Server configurations, ...                                                                   | High      |
| Code                   | Software projects                                                                                              | High      |

_tbd_

## Desaster recovery

_tbd_