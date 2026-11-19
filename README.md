# Built Young Skills

Open-source [Claude Skills](https://docs.claude.com/en/docs/agents-and-tools/agent-skills/overview) for young builders.

Built Young teaches teenagers aged 10–18 to find a problem worth solving and ship a real product. These are the tools we use with our own students, released free for anyone to use.

---

## Skills

### `first-users`

Gets a new product its first 10 to 100 users by hand: the list of people to reach, warm, community and cold messages, follow-ups, hands-on onboarding, and a tracker of who replied and signed up.

**How it works**

1. **Ask first.** The product, the first user you picture, and who you already know.
2. **Build the list** in three rings: people you know, one introduction away, and strangers. You fill in the names.
3. **Write the messages** for each ring, plus a 30-second in-person version.
4. **Follow up once**, then stop.
5. **Onboard the first five by hand** and write down their exact words.
6. **Track it**: asked, replied, signed up, used it.

For founders under 18, an adult sends every message to someone they don't know, including other schools.

It is one stage of [gtm-pipeline](https://github.com/BuiltYoung/gtm-pipeline), the GTM super agent, and also works on its own.

---

## Installing

**Claude Code**

```bash
mkdir -p ~/.claude/skills
git clone https://github.com/BuiltYoung/first-users.git ~/.claude/skills/first-users
```

Restart Claude Code. The skill loads automatically when your request matches it.

**Claude.ai**

Settings → Capabilities → Skills → Upload, then select the `first-users` folder.

---

## Using it

Describe what you need. No command needed:

> *"We need our first 20 users for a homework planner. Who do we ask and what do we say?"*

---

## Contributing

Issues and pull requests welcome. If you used this with students and something didn't land, we especially want to hear about it.

## Licence

MIT. See [LICENSE](LICENSE). Use it, fork it, teach with it.

---

**[Built Young](https://builtyoung.org)** · Build before everyone else.
