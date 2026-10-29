# FIH-Text-Chat

| Keybind | Feature |
| --- | --- |
| `T` | Open chat |
| `/` | Open a command |
| `Enter` | Send a message |
| `Esc` | Cancel/close chat |
| `Tab` | Complete a command or player name |
| `Up` / `Down` | Move through autocomplete suggestions |
| `Up` / `Down` while the input is empty | Recall sent messages and commands |
| `Ctrl+C` after selecting text | Copy selected chat text |

## Features
- Multiplayer chat.
- Commands: commands for help, history clearing, muting, action messages, configuration, and version checks.
- Autocomplete: press Tab to complete commands and player names; type @ followed by a name to get mention suggestions. Use Up/Down to navigate suggestions or recall messages and commands when the input box is empty.
- Mentions: highlight messages that mention your name and optionally play a ping sound.
- Chat history and timestamps: adjustable history length, message fade duration, timestamps, and 12-/24-hour formatting.
- Link controls: block links and received messages, or click a link while chat is open and confirm before opening it.
- Profanity filtering: masks detected words with # characters. The filter includes multiple languages and supports a custom word list.
- Persistent mutes: muted players remain muted after restarting the game.
- In-game configuration: view, change, and reset settings with /config; changes are validated before they are applied.
- Text selection: drag across chat text and press Ctrl+C to copy it.

Multiplayer Note: Players need Text Chat installed to see messages sent through this mod. Players without it can still appear in join/leave notifications.

## Settings overview
All settings can be viewed and changed with '/config'. Use '/config reset <setting>' to restore one default, or '/config reset all' to restore every default.
| Setting | Default | Purpose |
| --- | --- | --- |
| `MessageVisibleSeconds` | `10` | How long messages remain visible while chat is closed (2–120 seconds). |
| `FilterProfanity` | `true` | Mask detected profanity. |
| `BlockLinks` | `false` | Remove web links from sent and received messages instead of making them clickable. |
| `LinkWarning` | `true` | Ask for confirmation before opening a clicked link. |
| `MaxHistory` | `300` | Maximum number of chat lines in scroll-back history (50–1000). |
| `Timestamps` | `true` | Show timestamps on messages. |
| `Timestamp24Hour` | `true` | Use 24-hour timestamps instead of 12-hour AM/PM. |
| `MentionHighlight` | `true` | Highlight messages that mention you. |
| `MentionPlainName` | `true` | Treat your plain name as a mention as well as `@name`. |
| `MentionSound` | `true` | Play a sound when you are mentioned. |
| `PingVolume` | `0.5` | Mention-ping volume (0–1). |
| `OffsetX` | `4` | Horizontal chat offset from the right edge (−600–1700). |
| `OffsetY` | `0` | Vertical chat offset from screen center (−480–480). |
| `OpenKey` | `T` | Key that opens chat. |
| `SendKey` | `Enter` | Key that sends a message. |
| `SlashOpensCommand` | `true` | Open chat with `/` already entered when the slash key is pressed. |
| `DebugLog` | `false` | Write chat network and internal debug information to the BepInEx log. |
| `LinkWarning ` | `true` | Ask for confirmation before opening a link you clicked in chat |
