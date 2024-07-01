# RAI-DONUTSMP-UPDATES

RAI DONUTSMP UPDATES is a versatile plugin designed to keep your players informed about the latest changes and updates on your server. With a user-friendly configuration, customizable messages, and easy-to-use commands, this plugin ensures that your community stays up-to-date effortlessly.

Features:

Customizable Update Book:

Title: Update Book
Author: Configurable author name
Content: Easily editable content with support for colors, formatting, and hex color gradients
Page Size: Adjustable page size to fit your needs
Sound: Custom sound effect when the book is opened
World Whitelisting:

Only allow the update book to be opened in specified worlds (e.g., spawn)
Messages:

Configurable messages for reloading, permission errors, opening the book, and world restrictions
Hex Color Gradients:

Supports vibrant hex color gradients for text, enhancing the visual appeal of your update book
Commands:

/rai-updates [reload]: Manage RAI updates with the option to reload the configuration.
/updates: Open the update book with aliases for convenience (e.g., /server-updates).
Permissions:

rai-updates.reload: Allows reloading of the plugin configuration. (Default: OP)
rai-updates.open: Allows opening of the update book. (Default: OP)
Configuration Example:

``
book:
  title: Update Book
  author: YourAuthor
  enabled: true
  size: 256 # Shows up how many Characters are allowed in one Page
  content:
  - '#00bfff&l YOUR SERVER NAME'
  - ''
  - '&8Things we added:'
  - ''
  - '#00BFFF- &8add your text'
  - '#00BFFF- &8Badd your text'
  - '#00BFFF- &8add your text'
  - '#00BFFF- &8add your text'
  - '#00BFFF- &8add your text'
  - '#00BFFF- &8add your text'
  - '#00BFFF- &8add your text'
  
  openSound: ENTITY_PLAYER_LEVELUP

whitelist-world:
- spawn

messages:
  reloaded: '&aYou successfully reloaded the config!'
  permission: '&cYou dont have permission to use this command!'
  opened: '&a&lYou successfully opened the Book!'
  onlyInWhitelistWorld: '&cʏᴏᴜ ᴄᴀɴ ᴏɴʟʏ ᴛʜɪѕ ᴄᴏᴍᴍᴀɴᴅ ɪɴ ѕᴘᴀᴡɴ'``
Get Started:
Simply download and install the RAI DONUTSMP UPDATES plugin, configure it to suit your server's needs, and keep your players informed with ease!

Keep your server community engaged and informed with RAI DONUTSMP UPDATES! Download now and start updating your players in style.





