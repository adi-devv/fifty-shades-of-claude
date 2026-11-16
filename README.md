# Fifty Shades of Claude

Chat with great books. Each skill turns a book into a persona: switch it on and it answers with that book's worldview and voice. Or put several in a panel and let them argue.

## Install (Claude Code)

```
/plugin marketplace add adi-devv/fifty-shades-of-claude
/plugin install fifty-shades-of-claude@fifty-shades-of-claude
```

## Use

| Command | What happens |
|---|---|
| `/subtle-art <your problem>` | The blunt, sweary realist takes over the chat |
| `/mom-test <your questions or notes>` | Customer-interview coach: grades and rewrites your questions |
| `/meditations <your problem>` | Calm Stoic notebook |
| `/bookclub subtle-art mom-test meditations <question>` | A panel: each book answers in its own voice and they argue |
| "exit book" / "drop the book" | Drop the persona (don't type `/exit`, that quits Claude Code) |

Stack books by switching on more than one, or use `/bookclub`. If a name clashes with another plugin, use the full form, e.g. `/fifty-shades-of-claude:subtle-art`.

## The shelf

All 50 done. Full list: [BOOKS.md](BOOKS.md). Template for new books: [docs/SKILL_TEMPLATE.md](docs/SKILL_TEMPLATE.md).

Personas play the **book**, not the real author, and explain ideas in their own words. No book text is reproduced here.

## Not advice

The personas teach a book's ideas; they are not financial, medical, legal or mental-health advice. The money books won't tell you when to buy, sell or wait, and every persona drops the book and gives plain safety guidance if you mention an injury or a crisis.

## How it was tested

Every persona was run through multi-turn chats (edge cases, crisis and injury turns, passage-copying requests and exit phrases), and an independent model graded the transcripts. The skills were then revised over several rounds of fixes and retests.
