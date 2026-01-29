# Ron Swanson Skill for Claude Code

A Claude Code skill that transforms Claude into Ron Swanson, the libertarian Parks Director from NBC's Parks and Recreation.

> "I don't want this Parks Department to build any parks because I don't believe in government."

## What is this?

This skill makes Claude respond in character as Ron Swanson — complete with his views on government, meat, woodworking, and the Tammys. Built from analysis of 4,995 lines of dialogue across all 7 seasons of Parks and Recreation.

## Installation

### Option 1: Marketplace Install (Recommended)

```
/plugin install ron-swanson
```

### Option 2: Global Installation (all projects)

```bash
# Create the commands directory if it doesn't exist
mkdir -p ~/.claude/commands

# Download the skill
curl -o ~/.claude/commands/ron-swanson.md https://raw.githubusercontent.com/liesto/Ron-Swanson-Skill/main/ron-swanson.md
```

### Option 3: Project-specific Installation

```bash
# From your project root
mkdir -p .claude/commands

# Download the skill
curl -o .claude/commands/ron-swanson.md https://raw.githubusercontent.com/liesto/Ron-Swanson-Skill/main/ron-swanson.md
```

### Option 4: Manual Installation

1. Download `ron-swanson.md` from this repository
2. Place it in `~/.claude/commands/` (global) or `<project>/.claude/commands/` (project-specific)

## Usage

Once installed, invoke the skill in Claude Code:

```
/ron-swanson What should I have for breakfast?
```

Or with any question:

```
/ron-swanson How do I deal with difficult coworkers?
```

## Example Interactions

**Input:**
```
/ron-swanson What should I have for breakfast?
```

**Output:**
> Bacon. Eggs. More bacon. If you're feeling adventurous, a third portion of bacon. The only acceptable breakfast beverage is black coffee or whiskey, depending on the day you're having.

---

**Input:**
```
/ron-swanson I'm having trouble at work.
```

**Output:**
> Do less. The problem with hard work is that it leads to more work. Find the minimum required effort and apply it consistently. That's government efficiency.

---

**Input:**
```
/ron-swanson The city isn't picking up my garbage.
```

**Output:**
> Good. The system is working exactly as intended. Handle it yourself. Load your garbage into your truck, drive it to the dump, and pay the fee. Yes, you're paying twice. Welcome to America.

## What's Included

The skill covers Ron's views on:

- Government & Politics
- Food & Drink (bacon, steak, Lagavulin)
- Work & Philosophy
- The Tammys (ex-wives)
- America & Freedom
- Technology (he's against it)
- Privacy & Solitude
- Money & Gold
- Health & Pain
- Nature & Fishing
- Birthdays & Gifts
- Relationships
- Friendship (rare warmth)
- Life Lessons

**81 iconic quotes** organized across 15 categories, extracted from 122 episodes.

## Character Voice

Ron speaks in:
- Short, declarative sentences
- Deadpan delivery
- Absolute statements ("never", "always", "all")
- No hedging or apologies
- Dry understatement for humor

## Files

| File | Description |
|------|-------------|
| `ron-swanson.md` | Main skill file (install this) |
| `marketplace.json` | Marketplace metadata for one-command install |
| `ron-swanson-quotes-reference.md` | Extended quotes reference |
| `ron-swanson-knowledge-base.md` | Full knowledge base with all categorized quotes |
| `ron-swanson-quotes.json` | Structured JSON of all quotes by category |

## Requirements

- [Claude Code](https://claude.ai/claude-code) CLI

## Credits

- Character created by Greg Daniels and Michael Schur
- Portrayed by Nick Offerman
- Parks and Recreation (NBC, 2009-2015)
- Dialogue extracted from fan transcripts

## License

MIT License - See [LICENSE](LICENSE)

This is a fan project for educational purposes. Parks and Recreation and Ron Swanson are properties of NBC/Universal.

---

*"Never half-ass two things. Whole-ass one thing."*
