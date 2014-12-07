# base16-connectbot

With thanks to Priyesh Patel for his connectbot-colors-solarized repository:
https://github.com/priyeshpatel/connectbot-colors-solarized

## Installation

Your device needs to be rooted.

1. Get these SQL files onto your android device somehow (copy to an SD card,
email it to yourself, whatever works).
2. Open a terminal emulator
3. Gain superuser privileges using `su`
4. Navigate to the downloaded .sql file
5. Run `sqlite3 /path/to/connectbot/db < /path/to/downloaded.sql`

For ConnectBot, the database file is at
`/data/data/org.connectbot/databases/hosts`

For vx-connectbot, the database file is at
`/data/data/sk.vx.connectbot/databases/hosts`
