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

## Overview

- **More thoughtful response** — Pirates be known fer their big hearts.  Shiver me timbers!  They love t' talk as much as they love t' plunder!
- **Simulate a voyage** — Well, if ye have e'er dreamed o' th' rockin' o' a ship at night and th' sounds o' th' waves, this be th' plugin fer ye.
- **Fun** — As pirates, we understand seafarin' can shiver yer timbers.  Aarrr!  Aarrr! Krakens, mermaids, sirens and th' like.  Sometimes what ye need be yer Cap'n t' batton down th' hatches and talk ye through a problem.

## Before / After

<table>
<tr>
<td width="50%">

### Landlubber Claude ❌

> "The reason your React component is re-rendering is likely because you're creating a new object reference on each render cycle. When you pass an inline object as a prop, React's shallow comparison sees it as a different object every time, which triggers a re-render. I'd recommend using useMemo to memoize the object."

</td>
<td width="50%">

### Real Swashbucklin' Buccanneer ✅ 

> "Yer React component be re-render'n because ye be creatin' a new object refer 'ta each render cycle, we'll keel-haul ye! When ye pass an inline object as a prop, React's shallow comparison sees it as a different object every time — firin' the cannons o' re-renders! Skewer't in useMemo t' memoize the object. Savvy?"

</td>
</tr>
<tr>
<td>

### Mad Dog Land Lover Claude ❌

>  Recursion is when a function solves a problem by calling itself on a smaller version of the same problem, until it hits a base case that returns directly.  

</td>
<td>

### High Seas Caesar ✅ 

> Aye, matey! Recursion be a function callin' itself, we'll keel-haul ye! Break a big problem into smaller versions o' the same problem. Each call works on a smaller chunk til ye hit the base case. Then it all unwinds back up the stack.                                  
         

</td>
</tr>
</table>


## Intensity Levels:

<table>
<tr>
<td width="25%">

#### Powder Monkey (Lite)

> "Yer component re-rendered because ye made a new object refer 'ta each render. Put ye component in a useMemo."
> use with /pirate lite

</td>
<td width="25%">

#### Scallywag (Full) -- Default

> "Yer component be re-render'n because ye made a new object refer 'ta each render. Skewer't in useMemo."
> use with /pirate full

</td>
<td width="25%">

#### Blackbeard (Ultra)

> "Yer component be re-render'n, ya scallywag, because ye made a new object refer t' each and every render upon these cursed seas! Yaaarr! Skewer't in useMemo, and batten down the hatches it don't happen again! Savvy?"
> use with /pirate ultra

</td>
</tr>
</table>

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

> [!IMPORTANT]
> Pirate speech makes responses more verbose. Will increase token usage. Only for fun!
> inspired by [caveman](https://github.com/JuliusBrussee/caveman)

## Install
npx skills add aetomack/pirate
npx skills supports 40+ agents — Claude, Copilot, Cursor, etx.
For specific agents:

npx skills add aetomack/pirate -a cursor
npx skills add aetomack/pirate -a github-copilot
npx skills add aetomack/pirate -a cline
npx skills add aetomack/pirate -a windsurf
npx skills add aetomack/pirate -a codex

Claude Code plugin system:
claude plugin marketplace add aetomack/pirate
claude plugin install pirate@pirate

## License

MIT 
