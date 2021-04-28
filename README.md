# dpy-utils
Some extra discord.py utilities

# Features:
* Duration parsers: from `1y1w1d1h1m1s` format to seconds, and from seconds or timedelta to a namedtuple with each unit in it individually
* Context editor: Allows users to edit their message, which will edit the command response.
* Extra converters: Member, User, Role, TextChannel, VoiceChannel, StageChannel, CategoryChannel
* Tasks system: A cog for a to-do list

# Usage:
* Tasks: Add `bot.load_extension("tasks")` to your main.py file.
* Context Editor: Add `bot.load_extension("ContextEditor")` to your main.py file.
* Extra Converters: Just `import converters` and use `converters.Member` etc.
* Duration Parsers: Just `import duration` and use `duration.DurationParser` or `duration.parse()`