# Teacher: learn and teach

*[Leer en español](README.es.md)*

A skill for Claude that turns every conversation into language practice. Use Claude as usual (for code, studies, work or small talk), but in the language you're learning. Claude answers in that language and, when you make mistakes, corrects them at the end of its reply.

It works with any language: English, French, German, Italian, Portuguese, Japanese…

## What it does

- **Replies only in the language you're practicing**, at a level that fits yours (it estimates your level from how you write).
- **Corrects your mistakes at the end of each reply, only when there are any**: grammar, spelling, punctuation, unnatural phrasing and words from other languages. Each correction shows what you wrote, the corrected version and a one-line rule.
- **Refuses to answer messages in any other language.** It only replies with a short reminder to write in the language you're practicing. This forces you to practice, which is the whole point.
- **Warns you about false friends** (⚠️), words that look like your language but mean something else ("actually" ≠ "actualmente").
- **Points out repeated mistakes** (🔁) so you notice your patterns.
- **Tells you what you got right** (✓) when you fix an old mistake or use something above your level.
- **Practice modes on request**: mock job interviews, writing tasks, reading comprehension and vocabulary quizzes.
- **Helps with work and tech writing**: emails, cover letters, CVs, commit messages, pull request descriptions, standup updates.
- **Flags language that's too informal** if your goal is formal, like a job interview.
- **Gives vocabulary when you ask for it** ("teach me some words").

## How it works

1. **First time:** Claude asks three things: the language you want to practice, your native language and your goal (job interview, travel, exams…).
2. **Make it permanent:** Claude asks if you want to save your setup. Say yes, and practice mode is on in every new chat without calling the skill again. Without memory, Claude gives you one line to paste into your custom instructions (or `CLAUDE.md` in Claude Code).
3. **From then on:** just write in that language.
4. **Change language:** write "change language" whenever you want to switch.

Beginners (A1-A2) get the rule explanations in their native language. From B1 upward, everything is in the language you're practicing.

### Example

> **You:** Can you explain me how works a hashmap in java? i dont understand it very good
>
> **Claude:** *(explains HashMap in English)*
>
> **📝 Corrections**
> - ❌ "explain me how works a hashmap" → ✅ "explain to me how a HashMap works"
>   💡 "Explain" needs "to" before the person, and in indirect questions the subject comes before the verb.
> - ❌ "i dont" → ✅ "I don't"
>   💡 "I" is always capitalized, and "don't" needs an apostrophe.
> - ❌ "very good" → ✅ "very well"
>   💡 Use the adverb "well" to describe how you understand something.

More examples are in [examples/conversations.md](examples/conversations.md).

## Installation

### Claude (claude.ai and desktop app)

1. Download [`teacher-learn-and-teach.zip`](teacher-learn-and-teach.zip) from this repository.
2. Make sure code execution is turned on in Claude's settings (skills need it).
3. Go to **Customize → Skills**, click **+**, then **Create skill → Upload a skill**, and choose the ZIP file.
4. Start a chat and write something like: *"Use the teacher-learn-and-teach skill, I want to practice French."*

Menu names can change over time. If you can't find them, see Anthropic's guide: [Using Skills in Claude](https://support.claude.com/en/articles/12512180-using-skills-in-claude).

### Claude Code

Copy the `teacher-learn-and-teach/` folder into `~/.claude/skills/` (for all your projects) or `.claude/skills/` (for one project).

## Repository contents

| File | What it is |
|---|---|
| `teacher-learn-and-teach/SKILL.md` | The skill itself |
| `teacher-learn-and-teach.zip` | Ready-to-upload package for Claude |
| `teacher-learn-and-teach.skill` | The same package in `.skill` format |
| `examples/conversations.md` | Example conversations |
| `LICENSE` | MIT license |

## Tips

- Skills are loaded when Claude thinks they're relevant, so saving your setup (step 2) is what keeps practice mode on in new chats. If it still doesn't switch on, mention the skill once in that chat.
- Don't be afraid of mistakes: the more you write, the more you learn.

## License

[MIT](LICENSE) © 2026 Guillermo Navascués Martínez
