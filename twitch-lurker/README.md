# Twitch Lurker Bot

Python bot that rotates through a configurable list of Twitch channels on a timed interval, building views and minutes-watched for streamers. Built by reverse-engineering the Twitch algorithm to understand how watch-time and concurrent viewer metrics are weighted.

## Overview

`TWITCH_LURKER.ipynb` connects to Twitch via IRC, cycles through a list of channel URLs at a set interval, and maintains an active presence on each. Demonstrates IRC socket programming, session management, and timed automation logic.

## How to Run

```bash
pip install socket
jupyter notebook TWITCH_LURKER.ipynb
```

Add target channel URLs to the channels list in the config cell before running.

## Tech Stack
- Python 3
- `socket` — raw IRC connection to Twitch chat servers
- `time` — rotation interval control
- Twitch IRC API
