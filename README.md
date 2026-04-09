<p align="center">
  <img width="512" height="512" alt="pirate-ship" src="https://github.com/user-attachments/assets/bec7b7dc-67f2-4e3c-81da-7cb4fdbad8b6" />
</p>

<h1 align="center">Pirate Speakin'</h1>

<p align="center">
  <strong>Ahoy! Have ye e'er wanted Claude t' sound like a Corsair? And hoist the mainsail! </strong>
</p>

<p align="center">
  <a href="https://github.com/aetomack/pirate/stargazers"><img src="https://img.shields.io/github/stars/aetomack/pirate?style=flat&color=yellow" alt="Stars"></a>
  <a href="https://github.com/aetomack/pirate/commits/main"><img src="https://img.shields.io/github/last-commit/aetomack/pirate?style=flat" alt="Last Commit"></a>
  <a href="LICENSE"><img src="https://img.shields.io/github/license/aetomack/pirate?style=flat" alt="License"></a>
</p>
---

A [Claude Code](https://docs.anthropic.com/en/docs/claude-code) skill that makes Claude sound like a Corsair.

## Before / After

<table>
<tr>
<td width="50%">

### Landlubber Claude ❌

> "The reason your React component is re-rendering is likely because you're creating a new object reference on each render cycle. When you pass an inline object as a prop, React's shallow comparison sees it as a different object every time, which triggers a re-render. I'd recommend using useMemo to memoize the object."

</td>
<td width="50%">

### Real Swashbucklin' Buccanneer Claude ✅ 

> "Yer component be re-render'n because ye made a new object refer 'ta each render. Skewer't in `useMemo`."

</td>
</tr>
<tr>
<td>

### Mad Dog Land Lover Claude ❌

> "Explain database connection pooling"

</td>
<td>

### High Seas Caesar Claude ✅ 

> Ah, so ye want t' understand database connection poolin'. Splice the mainbrace! I see. Well, listen up! Yo-ho-ho! Connection poolin' reuses open connections instead o' creatin' new ones per request. Ya see, ye scallywag, it avoids repeat'd handshake over'ead."

</td>
</tr>
</table>


**:**

<table>
<tr>
<td width="25%">

#### Power Monkey (Lite)

> "Yer component re-rendered because ye made a new object refer 'ta each render. Put ye component in a useMemo."

</td>
<td width="25%">

#### Scallywag (Normal)

> "Yer component be re-render'n because ye made a new object refer 'ta each render. Skewer't in useMemo."

</td>
<td width="25%">

#### Blackbeard (Max)

> "Avast, ye! Yer component be re-render'n, ya simpleton, because ye made a new object refer 'ta each render. Yaaarr! Skewer't in `useMemo'. Savvy?"

</td>
<td width="25%">


</tr>
</table>

- **Slower, but more thoughtful response** — Pirates be known fer their big hearts.  Shiver me timbers!  They love t' talk as much as they love t' plunder!
- **Simulate a voyage** — Well, if ye have e'er dreamed o' th' rockin' o' a ship at night and th' sounds o' th' waves, this be th' plugin fer ye.
- **Fun** — As pirates, we understand seafarin' can shiver yer timbers.  Aarrr!  Aarrr! Krakens, mermaids, sirens and th' like.  Sometimes what ye need be yer Cap'n t' batton down th' hatches and talk ye through a problem.

## Usage

Trigger with:
- `/pirate` 
- "pirate mode"
- "talk like a pirate"
- "use pirate"
- "embark"
- "begin voyage"
- "set sail"

Stop with: "stop pirate" or "normal mode"

### Levels

| Level | Trigger | Effect |
|-------|---------|------------|
| **Powder Monkey** | `/caveman lite` | Drop filler, keep grammar. Professional but no fluff |
| **Scallywag** | `/caveman full` | Default caveman. Drop articles, fragments, full grunt |
| **Blackbeard** | `/caveman ultra` | Maximum compression. Telegraphic. Abbreviate everything |

> [!IMPORTANT]
> Pirate speech makes responses more verbose. Will increase token usage. Only for fun!

## License

MIT — free like mass mammoth on open plain.
