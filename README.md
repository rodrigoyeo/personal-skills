# Personal Skills

Five Claude Code skills that make you sharper at the work every founder, operator, and employee does: think clearly, learn fast, build offers that sell, close deals, and understand customers.

Drop them into Claude Code (or any agent that reads SKILL.md files) and they trigger automatically when the moment fits.

## The five skills

| Skill | What it does | Say something like |
|-------|--------------|--------------------|
| **grill-me** | A sceptical interviewer that pokes holes in your plan before you commit. Surfaces hidden assumptions, unowned tradeoffs, and failure modes. | "grill this plan", "poke holes in this", "stress test this design" |
| **teach** | Turns the current folder into a personal course. Builds short, beautiful lessons and reference docs over multiple sessions, tuned for long-term retention. | "teach me X", "I want to learn", "continue my learning" |
| **offer-strategist** | A direct business-strategy advisor. Runs your offer and pricing through the Value Equation, finds the one constraint, and gives you one move. | "stress test this offer", "is this priced right", "make this offer better" |
| **negotiation** | Close on value without discounting your way to a yes. Anchor with options, trade concessions, know your walk-away, and close clean. | "they want a discount", "competitor is cheaper", "how do I close this" |
| **customer-research** | Turn transcripts, reviews, and your own sales calls into themes, voice-of-customer quote banks, jobs-to-be-done maps, and real personas. | "voice of customer", "analyze these transcripts", "build personas" |
| **objection-handler** | Handle any sales objection with LAER (Listen, Acknowledge, Explore, Respond). Ready-to-fill scripts for price, timing, authority, competitor, trust. | "they said it's too expensive", "how do I respond to this objection" |
| **follow-up** | The next touch on a quiet deal: one message with a real purpose, owner, and date, plus the call on when a deal is dead. | "they went quiet", "no reply on the proposal", "next touch" |
| **positioning** | The one message your whole company writes from: positioning statement, value prop, the wedge, messaging pillars, message map. | "positioning", "what makes us different", "value proposition" |

## Install

Each skill is a folder under `skills/` with a single `SKILL.md`.

**Claude Code (personal, all projects):**
```bash
git clone https://github.com/<your-username>/personal-skills.git
cp -r personal-skills/skills/* ~/.claude/skills/
```

**One project only:**
```bash
cp -r personal-skills/skills/* /path/to/project/.claude/skills/
```

Restart Claude Code (or start a new session) and the skills are live. Trigger one by name ("grill this plan") or just describe the task and let it fire.

Works with any agent harness that loads `SKILL.md` files. No setup, no API keys, no tools beyond reading files (customer-research can also use web search).

## How a skill works

A skill is a Markdown file with a short frontmatter block (name + description with trigger phrases) and a body that tells the agent how to do the job well. When your request matches the triggers, the agent loads the skill and follows it. That is the whole mechanism.

## Credits

- `grill-me`, `teach`: adapted from [Matt Pocock's skills](https://github.com/mattpocock/skills) (MIT).
- `customer-research`: adapted from [Corey Haines's marketing skills](https://github.com/coreyhaines31/marketingskills) (MIT).
- `offer-strategist`: an independent advisor persona built around well-known value-based offer and pricing frameworks. Not affiliated with or endorsed by any individual.
- `negotiation`: a generic value-based closing method.

## License

MIT. See [LICENSE](LICENSE).
