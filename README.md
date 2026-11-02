# TwitterLinkFixerDiscordBot

Bot that automatically deletes messages with twitter links without embed improvers or with trackers on discords and resends them with fixed syntax

## The Problem

Twitter links have been getting increasingly difficult to deal with on discord. 
Firstly, twitter does not embed straightforwardly, making it unnecessarily difficult to save gifs and view videos within discord. 
Tools exist to amend this issue, (modifying the link by putting "fixup" or other similar keywords in front of the "x.com" part of the link), 
but using them is annoying and repetitive. Secondly, twitter has recently added a 
tracking element to their links when using the "copy link" button that reveals personal information about 
the sender including the device the link was copied from, whether they used the app, and other potentially 
compromising information that people might not want full public discord servers to know about. 
This is another easy issue to fix-- just delete everything in the link after the question mark, 
or just copy from the search bar if you're on a browser for twitter, but those alternatives are also inconvenient. 

## How It Works

A paragraph or a few bullets explaining what the software does at a
high level. If you have a diagram, embed it here:

![System diagram]([docs/diagram.pn](https://github.com/Tunde-bot/TwitterLinkFixerDiscordBot/blob/main/TwitterLinkDiscordFixer.pdf)])

## Tech Stack

- **Language:** Python
- **Libraries:** Discord.py
- **External tools:** 

## Setup

```bash
git clone https://github.com/you/your-project
cd your-project
./install.sh   # or whatever
```

## Usage

```bash
./backup.sh ~/Documents
```

## Roadmap

- Personalizable link automatic fixing
- Remembers different users’ preferred settings
- Seamless activation
- Compatibility with other sites’ links (Instagram, etc.)


## Author

Ayotunde Fagbemi 
github.com/Tunde-bot
