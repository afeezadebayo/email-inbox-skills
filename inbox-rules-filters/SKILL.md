---
name: inbox-rules-filters
description: "Design email filters and rules for Gmail, Outlook and other providers: top senders by volume, five to eight action-based labels or folders, sender, list and keyword rules, VIP highlighting, exception rules for important alerts, testing on recent mail, bulk clean-up and a monthly review, never auto-deleting. Use whenever someone wants Gmail filters or Outlook rules, a cleaner inbox, fewer notifications in the main inbox, labels or folders that work, or to set up email before giving an AI agent access."
license: CC-BY-4.0
metadata:
  author: Afeez Adebayo
  author_url: https://afeezadebayo.com
  author_linkedin: https://www.linkedin.com/in/afeez-adebayo/
  author_x: https://x.com/za_icon
  source: https://afeezadebayo.com/skills-md/productivity/email-inbox/inbox-rules-filters/
  category: productivity
  subcategory: email-inbox
  version: "1.0.0"
  created: "2026-10-10"
  updated: "2026-10-13"
---

# Inbox Rules and Filters

Most inboxes mix four very different kinds of mail: messages from people who need the user, automated notifications from tools, newsletters and promotions, and receipts or records. When all four land in one list, important messages get buried and the user must sort by hand every day. Filters and rules sort mail automatically as it arrives, so the main inbox shows mostly what needs a person.

This skill designs filters, labels or folders and rules for Gmail, Outlook and other providers: a small set of destinations, rules based on senders, lists and keywords, priority highlighting for key people, safe testing and a monthly review. It never deletes mail automatically.

## Operating principles
1. **Sort by what the user will do, not by topic.** Read later, receipts and notifications are actions; dozens of topic folders are not.
2. **Few destinations.** Five to eight labels or folders cover most needs.
3. **Never auto-delete.** Filters archive or label; deletion stays manual.
4. **Specific rules first.** Exact senders and list addresses beat broad keyword rules.
5. **Test, then trust.** Check each rule against recent mail before turning it on.

## Suggested destinations
| Label or folder | Holds | Seen when |
|---|---|---|
| Inbox | People who need the user | Each triage session |
| VIP (star or highlight) | Manager, key clients, family | Immediately or each session |
| Notifications | Tool alerts, system mail | Daily or weekly scan |
| Read later | Newsletters worth keeping | Weekly reading slot |
| Receipts | Orders, invoices, payments | Monthly bookkeeping |
| Calendar | Invites and updates | Handled by calendar |
| Archive | Everything else after triage | Search only |

## When to use, and when not to
Use it when the inbox is cluttered by automated mail, important emails get missed, setting up a new account, after an email audit or before giving an AI agent inbox access.

Don't use it for team shared inbox routing (`shared-inbox`) or for blocking malicious mail (`email-security` and the provider's spam controls).

## Inputs
- Email provider (Gmail, Outlook, Apple Mail, other).
- A sample of recent mail, or the top senders by volume.
- Priority people and topics.
- Existing labels, folders and rules.
- Bookkeeping or record-keeping needs.

## Workflow

### Step 1. Find the top senders
List senders and mailing lists by volume over the last 30 days, grouped into people, tools, newsletters, receipts and other.

### Step 2. Choose destinations
Start from the suggested set; add only what the user will check.

### Step 3. Write rules
For each high-volume sender or list: condition (from address, list header, subject words) and action (label, skip inbox, mark read, forward).

### Step 4. Highlight priority people
VIP lists, stars or importance markers for named senders so they stand out in every session.

### Step 5. Test
Run each rule's search on the last 30 days; check for false matches before applying.

### Step 6. Apply and clean
Apply to existing mail where useful; archive old notifications in bulk.

### Step 7. Review monthly
Check what still lands in the inbox, adjust rules and remove unused labels.

## Rule examples
| Condition | Action |
|---|---|
| From: notifications@tool.com | Label Notifications, skip inbox |
| List header contains: newsletter-name | Label Read later, skip inbox |
| Subject contains "receipt" OR "invoice" AND from: known vendors | Label Receipts, skip inbox |
| From: manager@company.com | Star, mark important |
| Has calendar invite | Label Calendar |
| To: user is in Cc only AND from: internal domain | Label Cc, keep in inbox but mark lower priority |

## Provider notes
- **Gmail:** create filters from a search (from:, to:, list:, subject:, has:attachment), with actions such as skip inbox, apply label, star, mark important, forward. Labels can be nested.
- **Outlook:** rules with conditions and actions (move to folder, categorise, flag); Focused Inbox separates likely-important mail.
- **Other providers:** most support sender and subject rules; check the help pages for list or header conditions.

## Search operators worth knowing
| Need | Gmail example |
|---|---|
| Bulk mail from one list | list:updates.example.com |
| Old notifications | from:alerts@tool.com older_than:30d |
| Large attachments | larger:10M |
| Unread from a person | from:name@company.com is:unread |

## Output format
```
1. Top senders by volume and type
2. Destinations (labels or folders) with purpose
3. Rules table: condition, action, expected volume
4. VIP list
5. Test results and false matches found
6. Clean-up actions for existing mail
7. Monthly review checklist
```

## Notification digests
Many tools let users choose daily or weekly digests instead of an email per event. Changing these settings at the source is often better than filtering: fewer messages arrive at all. List each noisy tool, check its notification settings, keep only alerts that need action and switch the rest to digests or in-app only.

## Rules for AI agents
Before giving an AI agent access, filters make its work safer and cheaper: notifications and newsletters are already labelled, so triage focuses on people. Keep a label such as "Agent drafted" for drafts the agent creates, so the user can review them in one place.

## Monthly review checklist
- What still reaches the inbox that could be filtered?
- Did any rule hide something important?
- Which labels were never opened? Remove them.
- Are new tools sending mail without a rule?
- Is the VIP list current?

## Keeping it simple
If the user needs a diagram to understand their own rules, there are too many. Merge similar labels, delete rules that move fewer than a few messages a month, and rely on search for the rest. Search is fast enough that most mail never needs a folder.

## Mobile considerations
On phones, show only the main inbox and VIP notifications. Labels such as Notifications and Read later can stay off the phone entirely, which removes much of the temptation to check email between tasks.

## Backing up rules
Export or note every rule in a simple table (condition, action, reason, date added). If an account is moved, rebuilt or shared, the table makes the setup quick to recreate and easy for an agent to audit.

Keep the table with the task files.

## Edge cases and judgement calls
| Situation | What to do |
|---|---|
| Important mail from a noisy tool | Exception rule for alerts with key words (e.g. "failed", "payment") |
| Shared or delegated mailbox | Agree rules with the other users first |
| Records must be kept | Archive and label; never delete |
| Several accounts | Same structure in each, or forward to one |
| Rule catches a real person | Narrow the condition to the exact address |

## Handoffs to related skills
- Find what to filter: `email-system-audit`
- Reduce bulk mail at the source: `newsletter-cleanup`
- Daily sorting of what remains: `inbox-triage`
- Suspicious mail: `email-security`

## Worked example
A product manager received 140 emails a day. The top-sender list showed 52 tool notifications, 31 newsletters, 9 receipts and 48 from people. Seven rules moved notifications to a Notifications label (with an exception for "incident" and "failed"), newsletters to Read later and receipts to Receipts, all skipping the inbox, while the manager and two key stakeholders were starred. Testing found one rule catching a colleague's emails, which was narrowed. The main inbox dropped to about 50 messages a day, almost all from people.

## Common mistakes
- Dozens of topic folders nobody checks.
- Rules that delete mail.
- Broad keyword rules that catch real people.
- No exception for important alerts from noisy tools.
- Never reviewing rules.

## Self-check before you answer
- Do destinations match actions the user will take?
- Was every rule tested on recent mail?
- Are priority people highlighted?
- Does nothing get deleted automatically?

---
Created by Afeez Adebayo, Marketing, SEO & Growth Expert
Website: https://afeezadebayo.com
LinkedIn: https://www.linkedin.com/in/afeez-adebayo/
X: https://x.com/za_icon
Source: https://afeezadebayo.com/skills-md/productivity/email-inbox/inbox-rules-filters/

Licence: CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/). You may copy, share and adapt this skill, including for commercial use, as long as you credit Afeez Adebayo and link to the source URL above. Keep this notice in any copy or adapted version.
