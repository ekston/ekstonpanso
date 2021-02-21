# ekstonpanso

Espanso is a Privacy-first, Cross-platform Text Expander. 

Go check it out at [espanso.org](https://espanso.org/).

## Ekstonpanso modifications

I use espanso mostly in combination with [Obsidian](https://obsidian.md/), a markdown Notetaking and -organization tool. Let me explain some of my modifications to espanso's standard .yaml file

**Meetings**

During meetings I take my notes and I start them of with :meet which gives me the following header to all meeting notes:

```
2021-02-20_Meeting 
Attendees: 
Tasks: 
Notes: 
---------- end ---------- 
```

**Status Tracking**

The Tasks I keep in Obisidian, I track with the following information, that I get after I type :obs

```
**Current state**
*Status bar*

**Planned steps**

**Backlog**
```

The status bar I track with the following commands :0load :1load :3load :6load :9load or :loaded for completed tasks.

```
▒▒▒▒▒▒▒▒▒▒ 0%

█▒▒▒▒▒▒▒▒▒ 10%

███▒▒▒▒▒▒▒ 30%

██████▒▒▒▒ 60%

█████████▒ 90%

██████████ 100%
```

**Markdown Tables**

Tables in Markdown are not complicated but a bit cumbersome to start. Thats why I have a shortcut to create two kinds of tables. :mdtable or :2mdtable

```
|   |   |   |   |   |
|---|---|---|---|---|
|   |   |   |   |   |
|   |   |   |   |   |
|   |   |   |   |   |
```

```
|   |   |
|---|---|
|   |   |

```
