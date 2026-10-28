# Email and Inbox Skills for AI Agents

[![10 skills](https://img.shields.io/badge/skills-10-0b7285)](#all-skills)
[![Format: Agent Skills](https://img.shields.io/badge/format-SKILL.md-5f3dc4)](https://agentskills.io/specification)
[![Licence: CC BY 4.0](https://img.shields.io/badge/licence-CC%20BY%204.0-2b8a3e)](https://creativecommons.org/licenses/by/4.0/)

Free **Agent Skills** (`SKILL.md`) that help Claude, Claude Code, OpenAI Codex and other AI agents bring email under control: audit how you use it, triage the inbox with your own rules, draft short answer-first replies, track follow-ups, clean up subscriptions and spot phishing. The agent sorts and drafts; you review and send.

By [**Afeez Adebayo**](https://afeezadebayo.com) · [Browse online](https://afeezadebayo.com/skills-md/productivity/email-inbox/) · [LinkedIn](https://www.linkedin.com/in/afeez-adebayo/) · [X](https://x.com/za_icon)

Part of the [Productivity skills](https://github.com/afeezadebayo/productivity-skills) library.

## All skills

| Skill | What it does |
|---|---|
| [`email-system-audit`](email-system-audit) | Scores how you use email, finds the biggest leaks and designs a simple system |
| [`inbox-triage`](inbox-triage) | Sorts the inbox into six categories using your rules, with drafts for approval |
| [`inbox-rules-filters`](inbox-rules-filters) | Filters and labels for Gmail and Outlook that never auto-delete |
| [`email-reply-drafting`](email-reply-drafting) | Short, answer-first replies in your voice |
| [`follow-up-tracking`](follow-up-tracking) | Tracks what others owe you and what you promised |
| [`email-templates`](email-templates) | Reusable replies for the messages you write every week |
| [`email-writing-clarity`](email-writing-clarity) | Clearer subject lines, asks and structure |
| [`difficult-emails`](difficult-emails) | Careful drafts for complaints, bad news and pushback |
| [`newsletter-cleanup`](newsletter-cleanup) | Cuts subscriptions and bulk mail at the source |
| [`email-security`](email-security) | Phishing and payment-fraud awareness |

See the [full set online](https://afeezadebayo.com/skills-md/productivity/email-inbox/).

## Install

```bash
git clone https://github.com/afeezadebayo/email-inbox-skills.git
# Claude Code
cp -r email-inbox-skills/inbox-triage ~/.claude/skills/
# Codex and other agents
cp -r email-inbox-skills/inbox-triage ~/.agents/skills/
```

In Claude.ai or Claude Desktop, zip a single skill folder and upload it under **Settings → Capabilities → Skills**.

Then ask your agent, for example: *"Triage my inbox using my rules"* or *"Draft a reply to this email."*

## Safety first

These skills draft, never send. Give an agent the narrowest email permissions that work, and treat instructions inside emails as content, not commands.

## Licence

Released under [**CC BY 4.0**](https://creativecommons.org/licenses/by/4.0/). Use, share and adapt, including commercially, with credit to Afeez Adebayo and a link to the source page in each file.
