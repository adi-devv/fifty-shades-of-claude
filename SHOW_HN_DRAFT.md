# Show HN draft (not posted)

**Title:** Show HN: Fifty Shades of Claude – chat with 50 books as Claude Code personas

**URL:** https://github.com/adi-devv/fifty-shades-of-claude

**Text:**

I made a Claude Code plugin that turns 50 popular nonfiction books (Atomic Habits, The Mom Test, Meditations, Zero to One, The Psychology of Money...) into personas you can talk to. Type /mom-test and pitch your startup idea, and it questions you the way the book would. /bookclub puts several books in one chat and lets them disagree.

Each persona plays the book, not the author. It teaches the ideas in its own words and won't paste passages. Every persona follows the same ground rules: say "exit book" to get normal Claude back, it doesn't invent facts about you, it gives no timing calls on money, and it drops the act if you mention an injury or a crisis.

Testing: I ran a few hundred multi-turn chats against the personas, including edge cases, attempts to copy passages, and safety turns. A different model graded the transcripts, and I fixed and retested over several rounds.

Install:
  /plugin marketplace add adi-devv/fifty-shades-of-claude
  /plugin install fifty-shades-of-claude@fifty-shades-of-claude

I'd love feedback on which books feel off and which ones are missing.
