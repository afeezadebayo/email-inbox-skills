---
name: newsletter-cleanup
description: "Clean up email subscriptions safely: find bulk senders with counts and last-opened dates, group them, decide keep, read later, reduce, unsubscribe or report as spam, act in approved batches using one-click unsubscribe, bulk archive, filter what stays and set a prevention habit with a two-week check. Use whenever someone wants to unsubscribe from newsletters, reduce promotional email, clean up bulk mail, stop marketing emails or prepare an inbox for an AI email assistant."
license: CC-BY-4.0
metadata:
  author: Afeez Adebayo
  author_url: https://afeezadebayo.com
  author_linkedin: https://www.linkedin.com/in/afeez-adebayo/
  author_x: https://x.com/za_icon
  source: https://afeezadebayo.com/skills-md/productivity/email-inbox/newsletter-cleanup/
  category: productivity
  subcategory: email-inbox
  version: "1.0.0"
  created: "2026-10-10"
  updated: "2026-10-13"
---

# Newsletter and Subscription Clean-Up

For many people, half or more of daily email is bulk mail: newsletters they once wanted, promotions from every shop they bought from, product updates, event invitations and social notifications. Each one takes seconds, but together they bury real messages and pull attention dozens of times a day. Large mailbox providers have pushed senders to make leaving easier: since 2024, Gmail and Yahoo have required bulk senders to support one-click unsubscribe. [Confirmed, Gmail and Yahoo sender requirements 2024]

This skill cleans up subscriptions safely: it finds every bulk sender, groups them, helps the user keep, digest or leave each one, unsubscribes only from legitimate senders, marks spam instead of unsubscribing from suspicious ones, filters what stays and sets a habit that stops the pile returning.

## Operating principles
1. **Keep what is read.** If the user has not opened a sender in months, it goes.
2. **Unsubscribe from legitimate senders only.** For spam, report it rather than clicking unsubscribe links, which can confirm the address is active.
3. **Approval before action.** The agent proposes; the user confirms each batch.
4. **Digest what stays.** Wanted newsletters go to a Read later label, not the main inbox.
5. **Prevent the return.** New sign-ups use a rule, a separate address or a quick decision at arrival.

## Decisions for each sender
| Decision | When | Action |
|---|---|---|
| Keep in inbox | Rare, essential (bank statements, school notices) | No change |
| Keep, read later | Valued newsletters read weekly | Filter to Read later |
| Reduce | Useful but too frequent | Change frequency in sender's preferences |
| Unsubscribe | Not read or not wanted | Use the sender's unsubscribe option |
| Report as spam | Never subscribed, suspicious or ignores unsubscribes | Mark as spam; do not click links |

## When to use, and when not to
Use it when bulk mail floods the inbox, after an email audit, at the start of a year, before connecting an AI agent to email, or when moving to a new address.

Don't use it to judge whether a specific message is a phishing attempt (`email-security`) or to manage work notifications from tools (`inbox-rules-filters`).

## Inputs
- Access to the mailbox, or a list of bulk senders.
- Senders the user definitely wants to keep.
- Whether the user prefers a separate address for shopping and sign-ups.
- Any receipts or records that must still arrive.

## Workflow

### Step 1. Find bulk senders
Search the last 60 to 90 days for messages with an unsubscribe link or List-Unsubscribe header, grouped by sender, with counts and the last date the user opened one.

### Step 2. Group
Newsletters, shops and promotions, product updates, social notifications, events, unknown senders.

### Step 3. Propose decisions
Default: unsubscribe from senders not opened in 90 days; keep and filter senders opened regularly; report unknown or suspicious senders as spam.

### Step 4. Confirm in batches
Show batches of 10 to 20 senders with the proposed action; the user ticks or changes each.

### Step 5. Act
Use one-click unsubscribe where the mail client offers it; otherwise the sender's own preference page. Never enter passwords on unsubscribe pages. Apply spam reports and filters.

### Step 6. Bulk archive
Archive old messages from removed senders in one action.

### Step 7. Set the prevention habit
Decide at arrival for any new bulk sender: keep, filter or leave. Consider a separate address for shopping and sign-ups.

### Step 8. Check after two weeks
Senders that keep mailing after unsubscribing get a filter to archive or are reported as spam.

## Batch review template
```
| Sender | Type | Emails (90 days) | Last opened | Proposed | Your decision |
| Shop A promotions | Shop | 64 | Never | Unsubscribe | |
| Industry weekly | Newsletter | 12 | Last week | Read later | |
| Unknown deals | Unknown | 30 | Never | Report spam | |
```

## Safe unsubscribe rules
- Prefer the mail client's built-in unsubscribe button, which uses the sender's list header.
- Use links only from known, legitimate senders.
- Never log in, enter card details or download anything to unsubscribe.
- For unknown or suspicious senders, report as spam instead.
- Some legal and account messages cannot be unsubscribed; filter them instead.

## Output format
```
1. Bulk senders found (count, types, volume)
2. Batches with proposed decisions
3. Actions taken after approval
4. Filters created for kept senders
5. Prevention plan
6. Two-week check date
```

## A separate address for sign-ups
Many people use a second address, or an alias such as name+shops@ where the provider supports it, for shopping, trials and event sign-ups. Mail to that address can be filtered away from the main inbox automatically, and if one service leaks or sells the address, it is easy to see which and stop it.

## Weekly reading slot
Newsletters that stay are read in one weekly slot, for example Friday lunchtime, from the Read later label. Anything unread for a month is a signal to unsubscribe. An agent can also summarise the week's newsletters into a short digest with links.

## Measuring the result
| Measure | Before | After |
|---|---|---|
| Bulk emails a day in the main inbox | | |
| Bulk senders | | |
| Time spent on bulk mail a day | | |
Record the numbers before starting and two weeks later; the difference usually makes the habit easy to keep.

## Privacy and data
Unsubscribing stops marketing but may not delete the data a company holds. Where privacy law gives the user rights, such as under UK or EU data protection rules, they can ask a company to delete their data; the agent can draft that request for the user to send. Keep any such requests and replies in a folder in case follow-up is needed.

## Agent permissions
The agent needs read access to find bulk senders and the ability to apply labels or filters. Unsubscribing and spam reports happen only after the user approves each batch, and the agent never visits unsubscribe pages that ask for a login or payment details.

## Repeat yearly
Run the full clean-up once a year, because new subscriptions creep back in through purchases, events and trials.

## Edge cases and judgement calls
| Situation | What to do |
|---|---|
| Thousands of senders | Start with the top 50 by volume |
| Work newsletters the user must receive | Filter to Read later instead of leaving |
| Account emails mixed with marketing | Change marketing preferences in the account; keep service mail |
| Shared family or team address | Agree decisions with the other users |
| Sender ignores unsubscribe | Filter to archive or report as spam |

## Handoffs to related skills
- Find the volume first: `email-system-audit`
- Filters for what stays: `inbox-rules-filters`
- Suspicious senders: `email-security`
- Daily triage after clean-up: `inbox-triage`

## Worked example
A teacher's inbox received about 90 bulk emails a day. The scan found 212 bulk senders in 90 days. In four batches, the teacher kept 9 newsletters (filtered to Read later), reduced 6 shops to monthly emails, unsubscribed from 151 senders and reported 18 unknown senders as spam. Old messages from removed senders were archived in one action. Two weeks later, 4 senders were still emailing and got archive filters. Daily bulk mail fell to about 15 messages.

## Common mistakes
- Clicking unsubscribe links in spam.
- Unsubscribing from everything, then missing important service mail.
- Leaving wanted newsletters in the main inbox.
- No prevention habit, so the pile returns.
- Acting without the user's approval.

## Self-check before you answer
- Was each batch approved before action?
- Were suspicious senders reported rather than unsubscribed?
- Do kept newsletters skip the main inbox?
- Is there a prevention habit and a two-week check?

---
Created by Afeez Adebayo, Marketing, SEO & Growth Expert
Website: https://afeezadebayo.com
LinkedIn: https://www.linkedin.com/in/afeez-adebayo/
X: https://x.com/za_icon
Source: https://afeezadebayo.com/skills-md/productivity/email-inbox/newsletter-cleanup/

Licence: CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/). You may copy, share and adapt this skill, including for commercial use, as long as you credit Afeez Adebayo and link to the source URL above. Keep this notice in any copy or adapted version.
