---
name: follow-up-tracking
description: "Track open loops in email: things others owe the user and promises the user made, captured from sent and received mail, logged with dates and thread links, checked daily, chased with short nudge templates, escalated after one nudge and reviewed weekly, with default chase intervals by relationship. Use whenever someone needs to track email replies, chase clients, suppliers or colleagues, manage promises made by email, follow up on job applications or stop things slipping through the cracks."
license: CC-BY-4.0
metadata:
  author: Afeez Adebayo
  author_url: https://afeezadebayo.com
  author_linkedin: https://www.linkedin.com/in/afeez-adebayo/
  author_x: https://x.com/za_icon
  source: https://afeezadebayo.com/skills-md/productivity/email-inbox/follow-up-tracking/
  category: productivity
  subcategory: email-inbox
  version: "1.0.0"
  created: "2026-10-10"
  updated: "2026-10-13"
---

# Follow-Up Tracking

Many costly email failures are silent: a client never replied and nobody chased, a promised document was never sent, a supplier quote expired, a candidate waited a week for an answer. People rely on memory or starred messages, and both fail as volume grows. A simple waiting-for list, checked on a rhythm, prevents most of these misses.

This skill tracks two kinds of open loops in email: things others owe the user (waiting for) and things the user promised (commitments). It captures them as emails are sent and received, sets chase dates, drafts polite nudges and reminds the user before their own promises are due.

## Operating principles
1. **Capture when the loop opens.** Log the item when the email is sent or the promise is made.
2. **Every item has a date.** A chase date for others, a due date for the user's promises.
3. **One list.** Waiting-for and commitments live in the task system, not scattered stars and flags.
4. **Chase politely, then escalate.** One nudge, then a different channel or person.
5. **Close loops visibly.** Mark items done and thank people who delivered.

## Two lists
| List | Holds | Example |
|---|---|---|
| Waiting for | Replies, approvals, files or payments owed to the user | "Contract signature from Acme, asked 3 Oct, chase 8 Oct" |
| Commitments | Things the user promised in email | "Send revised quote to Lena by Thu 10 Oct" |

## When to use, and when not to
Use it for tracking replies, chasing clients, suppliers and colleagues, managing promises made by email, job applications awaiting response and sales follow-ups.

Don't use it for automated sales sequences to many contacts (the CRM and Lifecycle skills) or for repeated nagging that damages relationships.

## Inputs
- Access to sent and received mail, or a list of open items.
- The task file or tool where waiting items should live.
- Default chase intervals by relationship.
- Tone and sign-off notes.

## Workflow

### Step 1. Detect open loops
In sent mail, find questions and requests the user made ("could you", "please send", "let me know", "by Friday"). In received mail and the user's replies, find promises ("I'll send", "I will confirm", "by Monday").

### Step 2. Log each item
```
| Type | Item | Person | Asked or promised | Due or chase | Thread link | Status |
| Waiting | Signed contract | Acme legal | 3 Oct | 8 Oct | link | Open |
| Commitment | Revised quote | Lena | 7 Oct | 10 Oct | link | Open |
```

### Step 3. Set dates
Use a stated deadline if one exists; otherwise defaults such as two working days for internal requests, three to five for external, and one day before any deadline the user promised.

### Step 4. Check daily
During triage: replies received close items automatically; overdue waiting items get a nudge draft; commitments due tomorrow appear in the morning plan.

### Step 5. Draft nudges
Short, friendly and specific, replying in the original thread so context is visible.

### Step 6. Escalate when needed
After one unanswered nudge: try another channel (call or chat), another person, or decide the item no longer matters.

### Step 7. Review weekly
In the weekly review, scan both lists, close stale items and spot people or suppliers who often run late.

## Nudge templates
**First nudge**
```
Hi <name>, a quick follow-up on <item> from <date>. Could you let
me know by <date>? If anything is blocking it, I'm happy to help.
```
**Second nudge (different angle)**
```
Hi <name>, I need <item> to <reason, e.g. confirm the start date>.
If it's easier, I can call for five minutes today or tomorrow.
```
**Closing the loop**
```
Thanks, <name>, received. I'll <next step> by <date>.
```
**Own promise running late**
```
Hi <name>, the <item> I promised for <date> needs one more day
because <reason>. You'll have it by <new date>.
```

## Default chase intervals
| Relationship | First nudge | Second nudge |
|---|---|---|
| Close colleague | 1 to 2 working days | Chat or call |
| Client | 3 working days | 3 more days, or a call |
| Supplier | 2 to 3 working days | Call or account manager |
| Senior stakeholder | 3 to 5 working days | Through their assistant or a meeting |
| Job application | 7 to 10 working days | One more, then move on |

## Tools
Any tool works: a Waiting for section in `TASKS.md`, a label such as "Waiting" with dated notes, follow-up flags or reminders in the email client, or a CRM for sales. The agent keeps the list current and links each item to its thread.

## Output format
```
1. New open loops found (waiting and commitments)
2. Updated lists with dates
3. Overdue items with nudge drafts
4. Commitments due in the next 48 hours
5. Items to close or escalate
```

## Making commitments realistic
Many missed promises start with an over-quick reply such as "I'll send it today". Before promising, check the calendar and task list; promise a date with a small buffer; and if a promise becomes unrealistic, update the person before the date passes rather than after. People forgive a moved date far more readily than silence.

## Sales and job search follow-ups
For prospects and job applications, keep the cadence short and respectful: one follow-up adding something useful, such as a relevant example or a brief update, then a final note that closes the loop politely. Log outcomes so future follow-ups learn from what worked.

## Daily check script
```
Overdue waiting (3): drafts ready
Due from you in 48 hours (2): quote to Lena (Thu), slides to Sam (Fri)
Closed today (4): replies received
```

## Privacy
Waiting lists can include client names and money owed. Keep them in private files, and avoid copying sensitive details into shared task tools or summaries sent to others.

## Measuring reliability
Count missed follow-ups and late promises each month. A falling number shows the system works; a rising one usually means items are not being captured when emails are sent.

## Edge cases and judgement calls
| Situation | What to do |
|---|---|
| Vague request ("let's catch up") | Ask the user whether it needs tracking |
| Several people owe parts | One line per person |
| Recipient on leave (auto-reply) | Move chase date to their return or contact the named cover |
| Sensitive relationship | Softer wording, longer interval; user decides |
| Payment owed | Follow the user's invoicing process; escalate formally if needed |
| User missed own deadline | Draft an honest update with a new date immediately |

## Handoffs to related skills
- Daily triage that feeds the lists: `inbox-triage`
- Writing nudges and updates: `email-reply-drafting`
- Task list structure: the Planning and Task Management `task-system-setup` skill
- Weekly review: the Planning and Task Management `weekly-review` skill

## Worked example
A freelance designer sends proposals, invoices and file requests to a dozen clients a month. The agent finds 14 open loops in sent mail and 5 promises in replies. It logs them with dates, drafts three nudges for overdue items, reminds the designer that two promised drafts are due tomorrow, and after a week closes nine items as replies arrive. An overdue invoice gets a second nudge and then a call, and is paid within three days.

## Common mistakes
- Starring emails as a tracking system.
- No dates on waiting items.
- Nudging too often or too soon.
- Forgetting the user's own promises.
- Not closing items when replies arrive.

## Self-check before you answer
- Were both waiting items and commitments captured?
- Does every item have a date and a thread link?
- Are nudges short, specific and in the original thread?
- Are overdue own promises updated openly?

---
Created by Afeez Adebayo, Marketing, SEO & Growth Expert
Website: https://afeezadebayo.com
LinkedIn: https://www.linkedin.com/in/afeez-adebayo/
X: https://x.com/za_icon
Source: https://afeezadebayo.com/skills-md/productivity/email-inbox/follow-up-tracking/

Licence: CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/). You may copy, share and adapt this skill, including for commercial use, as long as you credit Afeez Adebayo and link to the source URL above. Keep this notice in any copy or adapted version.
