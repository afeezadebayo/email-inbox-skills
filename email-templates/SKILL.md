---
name: email-templates
description: "Build a small library of email templates from real repeated replies: finding repeats in sent mail, the top ten written answer-first in the user's voice, obvious placeholders with a pre-send check, searchable names, setup in Gmail, Outlook, text expanders or an AI agent, and quarterly reviews. Use whenever someone answers the same emails repeatedly, wants canned responses, Gmail templates, Outlook quick parts or snippets, needs consistent team replies or approved answers for an AI email agent."
license: CC-BY-4.0
metadata:
  author: Afeez Adebayo
  author_url: https://afeezadebayo.com
  author_linkedin: https://www.linkedin.com/in/afeez-adebayo/
  author_x: https://x.com/za_icon
  source: https://afeezadebayo.com/skills-md/productivity/email-inbox/email-templates/
  category: productivity
  subcategory: email-inbox
  version: "1.0.0"
  created: "2026-10-10"
  updated: "2026-10-13"
---

# Email Templates

The same questions arrive every week: pricing, availability, how to book, where to find a document, what happens next. Rewriting the answer each time wastes minutes and produces uneven quality. Templates (also called canned responses, snippets or quick parts) fix this, but badly built templates sound robotic, go out with the wrong name, and drift out of date.

This skill builds a small library of email templates from the user's own repeated replies: it finds the repeats, writes short answer-first templates in the user's voice, adds clear placeholders, organises them for fast use in Gmail, Outlook or an AI agent, and keeps them current.

## Operating principles
1. **Templates come from real repeats.** Build only for replies sent several times a month.
2. **Short and personal.** A template is a starting point; one personal line makes it feel human.
3. **Obvious placeholders.** `[name]`, `[date]`, `[link]` in a format that is impossible to send unnoticed.
4. **One owner, regular review.** Prices, links and policies change; templates must too.
5. **Answer first.** The same rules as any good reply.

## Common template types
| Type | Example |
|---|---|
| Information request | Pricing, services, availability |
| Scheduling | Offering times, sharing a booking link, rescheduling |
| Next steps | After a call, after a purchase, onboarding |
| Polite no | Declining requests, partnerships, unpaid work |
| Follow-up | Chasing replies, payments, documents |
| Thank you | After help, referrals, interviews |
| Handover | Introducing a colleague who will take over |
| Job search | Recruiter replies, interview confirmations, declining offers |

## When to use, and when not to
Use it when the user answers the same questions repeatedly, a team needs consistent replies, onboarding a new assistant, or setting up an AI email agent with approved answers.

Don't use it for sensitive one-off messages (`difficult-emails`) or marketing campaigns to lists (the CRM and Lifecycle skills).

## Inputs
- Sent mail from the last two to three months, or examples of repeated replies.
- Current prices, links, policies and booking tools.
- Tone notes and sign-off.
- The email client or agent that will hold the templates.

## Workflow

### Step 1. Find repeats
Scan sent mail for similar replies; group them by purpose and count how often each is sent.

### Step 2. Pick the top ten
Start with the replies sent most often or that take longest to write.

### Step 3. Write each template
Subject (if new email), answer-first body, placeholders, one optional personal line, sign-off.

### Step 4. Name and organise
Names that are easy to search, such as `price - standard`, `schedule - offer times`, `no - partnership`.

### Step 5. Load into the tool
Gmail templates, Outlook My Templates or Quick Parts, a text expander, or a templates file the agent reads.

### Step 6. Add a check
Before sending, search the draft for `[` to catch unfilled placeholders.

### Step 7. Review quarterly
Update prices, links and policies; delete templates not used in three months.

## Template format
```
Name: schedule - offer times
Use when: someone asks to meet
Subject: (reply)
Body:
Hi [name],
Happy to talk. Would any of these work?
- [day, date, time, time zone]
- [day, date, time, time zone]
Or pick a time here: [booking link]
[optional personal line]
Best,
[sign-off]
Last reviewed: [date]
```

## Example templates
**Pricing enquiry**
```
Hi [name], thanks for asking. [Service] starts at [price] for
[scope]. Most clients choose [option] because [reason].
The next step is a 20-minute call: [booking link].
```
**Polite no**
```
Hi [name], thank you for thinking of me. I can't take this on
right now because [brief reason]. [Alternative: person, resource
or a later date].
```
**After a call**
```
Hi [name], thanks for today. As agreed: [action 1, owner, date];
[action 2, owner, date]. I'll [next step] by [date].
```

## Templates for AI agents
An agent can use the same library: keep templates in `email-templates.md`, tell the agent when each applies, and require it to fill placeholders only from known facts, leaving the rest visible. The agent drafts; the user sends.

## Output format
```
1. Repeated replies found (counts)
2. Top ten templates, ready to paste
3. Names and folder structure
4. Setup steps for the user's email tool or agent
5. Placeholder check and review schedule
```

## More example templates
**Invoice reminder**
```
Hi [name], a friendly reminder that invoice [number] for [amount]
was due on [date]. You can pay here: [link]. If it's already in
process, please ignore this note.
```
**Introducing a colleague**
```
Hi [name], I'd like to introduce [colleague], who will lead
[project] from [date]. [Colleague] knows the background and will
be in touch this week. I'm copied for continuity.
```
**Recruiter reply (interested)**
```
Hi [name], thanks for reaching out. The [role] sounds interesting,
particularly [one detail]. Could you share the salary range and
location rules? I'm free for a call on [times].
```

## Personalising quickly
Each template has one line marked `[optional personal line]`: a reference to the person's last message, their company or a shared context. Filling it takes ten seconds and is the difference between a reply that feels handled and one that feels processed.

## Measuring value
Track how often each template is used and the time saved per use. Templates used rarely are deleted; templates edited heavily every time are rewritten to match how the user actually replies.

## Where templates live
| Tool | Where | Notes |
|---|---|---|
| Gmail | Templates (enable in settings) | Insert from the compose menu |
| Outlook | My Templates or Quick Parts | Available on desktop and web |
| Text expander apps | Short codes such as ;price | Work in any app, including chat |
| AI agent | `email-templates.md` | Agent picks and fills; user approves |
Keep one master copy, usually the Markdown file, and update the others from it so wording stays consistent.

## Writing in the user's voice
Base each template on the user's best real reply, not a generic version. Keep their greeting, sign-off and typical phrases, and remove anything that only made sense for one recipient.

Review the library each quarter.

## Edge cases and judgement calls
| Situation | What to do |
|---|---|
| Team shared templates | One owner; changes logged; version date in each |
| Different regions or languages | One template per language; local prices and time zones |
| Legal or pricing wording must be exact | Lock the wording; mark editable parts clearly |
| Template feels cold | Add one personal sentence each time |
| Too many templates | Merge similar ones; delete the unused |

## Handoffs to related skills
- Writing individual replies: `email-reply-drafting`
- Hard messages: `difficult-emails`
- Clear structure: `email-writing-clarity`
- Follow-up templates in use: `follow-up-tracking`
- Team inboxes: `shared-inbox`

## Worked example
A small agency owner found 11 reply types sent at least four times a month, including pricing, scheduling, project kickoff, invoice reminders and declining unpaid pitches. The agent wrote ten templates in the owner's voice, each under 80 words, with bracketed placeholders and a last-reviewed date, loaded them as Gmail templates and as a file for the AI agent, and added a final search for `[` before sending. Replies that took 10 minutes now take two, and a quarterly review caught an old price in the pricing template.

## Common mistakes
- Long templates that read like policy documents.
- Placeholders that are easy to miss.
- Out-of-date prices and links.
- No personal line, so replies feel automated.
- Hundreds of templates nobody can find.

## Self-check before you answer
- Is each template based on a real repeated reply?
- Is the answer in the first line?
- Are placeholders obvious and checked before sending?
- Is there an owner and a review date?

---
Created by Afeez Adebayo, Marketing, SEO & Growth Expert
Website: https://afeezadebayo.com
LinkedIn: https://www.linkedin.com/in/afeez-adebayo/
X: https://x.com/za_icon
Source: https://afeezadebayo.com/skills-md/productivity/email-inbox/email-templates/

Licence: CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/). You may copy, share and adapt this skill, including for commercial use, as long as you credit Afeez Adebayo and link to the source URL above. Keep this notice in any copy or adapted version.
