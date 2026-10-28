---
name: email-reply-drafting
description: "Draft short, answer-first email replies in the user's voice: reading the whole thread, listing every ask, choosing one purpose, reply patterns for yes, no, not yet, scheduling, information requests, closing loops and chasing, tone matching, placeholders instead of guesses and two options when a decision is needed. Use whenever someone needs to reply to an email, draft a response, decline or accept politely, schedule a meeting by email, chase a reply or answer several questions in one thread."
license: CC-BY-4.0
metadata:
  author: Afeez Adebayo
  author_url: https://afeezadebayo.com
  author_linkedin: https://www.linkedin.com/in/afeez-adebayo/
  author_x: https://x.com/za_icon
  source: https://afeezadebayo.com/skills-md/productivity/email-inbox/email-reply-drafting/
  category: productivity
  subcategory: email-inbox
  version: "1.0.0"
  created: "2026-10-10"
  updated: "2026-10-13"
---

# Email Reply Drafting

Most slow email is not hard email. It is a short reply that takes twenty minutes because the writer re-reads the thread, worries about tone, adds three paragraphs of context and forgets to answer one of the questions. AI drafts can make this worse: long, over-polite replies that sound like a template and still miss the point. Readers skim, so the best replies are short, specific and easy to act on.

This skill drafts email replies in the user's own voice: it reads the whole thread, identifies every question and request, decides the reply's purpose, puts the answer first, keeps it brief, matches the relationship and tone, flags anything it cannot know, and offers alternatives when the user needs to say no, push back or negotiate. The user always reviews and sends.

## Operating principles
1. **Answer first.** Lead with the decision, answer or next step.
2. **Answer everything asked.** List the questions in the thread and make sure each is handled.
3. **Short by default.** Most replies need two to five sentences.
4. **Sound like the user.** Use their tone notes, sign-off and phrasing from past emails.
5. **Never invent facts.** Unknown dates, prices or commitments become clear placeholders.

## Inputs
- The full email thread.
- What the user wants to say, even in a few words ("yes but Thursday", "decline politely").
- Tone and style notes (`inbox-rules.md` or a short style file): English variant, formality, sign-off, phrases to avoid.
- Facts needed: calendar availability, prices, policies, attachments.

## When to use, and when not to
Use it for everyday replies, acknowledgements, scheduling, answering questions, declining requests, chasing, and replying in a second language.

Don't use it for very sensitive messages such as complaints, conflict, bad news or negotiations without the extra care in `difficult-emails`, and don't send anything without the user's review.

## Workflow

### Step 1. Read the thread
Identify the sender, relationship, history, the latest message and what changed since the last reply.

### Step 2. List the asks
Every question, request, deadline and implied expectation, including ones buried in long paragraphs.

### Step 3. Decide the purpose
Confirm, answer, decline, schedule, ask for information, push back or close the loop. One main purpose per reply.

### Step 4. Draft answer-first
```
Line 1: the answer or decision
Lines 2-4: the details needed to act (dates, links, next steps)
Last line: what happens next or what you need from them
Sign-off
```

### Step 5. Match tone
Mirror the sender's formality, adjusted to the relationship. Warm but brief for colleagues, polite and precise for clients, direct for suppliers.

### Step 6. Check facts and placeholders
Calendar times checked if available; anything unknown marked as `[confirm price]`, `[attach file]` or similar.

### Step 7. Offer options when useful
For yes, no or maybe decisions, give two short versions so the user can pick.

## Reply patterns
| Purpose | Pattern |
|---|---|
| Yes | "Yes, that works. I'll <action> by <date>." |
| No | "Thanks for thinking of me. I can't take this on before <date>. <Alternative or referral>." |
| Not yet | "Good question. I'll confirm by <date> once I've <reason>." |
| Scheduling | Offer two or three specific times with time zone, or a booking link |
| Need information | "To do this I need <items>. Could you send them by <date>?" |
| Closing a loop | "Done: <what>. Let me know if you need anything else." |
| Chasing | "Following up on <item> from <date>. Could you let me know by <date>?" |

## Subject lines and structure
- Keep the subject when replying; change it only if the topic has changed, noting "(was: old subject)".
- Use short paragraphs or a few bullets for several items.
- Put dates in an unambiguous format, such as 14 October, with time zones for cross-border emails.
- Move long discussions to a call and say so in one line.

## Before and after
**Before (AI-generic):**
"Thank you so much for reaching out! I hope this email finds you well. I wanted to take a moment to let you know that I have reviewed your request and I would be more than happy to assist..."

**After:**
"Yes, I can send the revised quote by Thursday. One question first: should it include the two extra workshops you mentioned?"

## Phrases to avoid unless the user uses them
`I hope this email finds you well`, `I wanted to reach out`, `Please do not hesitate to contact me`, `Per my last email`, `Just checking in`, `Thanks in advance`, long apologies for short delays.

## Output format
```
1. Asks found in the thread (checklist)
2. Draft reply (and a second option if a decision is needed)
3. Placeholders to fill or facts to confirm
4. Suggested follow-up date, if any
```

## Learning the user's voice
Ask for five to ten sent emails the user is happy with. Note greeting and sign-off habits, sentence length, formality, phrases they repeat and phrases they never use. Save these as tone notes so every draft sounds familiar. When the user edits a draft, record the change if it reflects a preference.

## Time zones and dates
For cross-border emails, write times with the time zone and, where helpful, the recipient's local time: "Tuesday 14 October, 3pm WAT (2pm London)". Avoid formats such as 10/11, which mean different dates in different countries.

## Replying faster
- Reply within the user's response-time targets; a short holding reply beats a perfect late one.
- Batch similar replies, such as scheduling or acknowledgements, in one session.
- Save good replies as templates when the same question comes up repeatedly.
- If a thread passes three rounds without progress, suggest a short call.

## Attachments and links
Mention every attachment in the text ("I've attached the revised quote"), check it is actually attached before sending, and prefer links to shared documents for large or frequently updated files, with access settings confirmed.

## Final read before sending
Read the draft once as the recipient: is the answer clear in the first line, is every question handled, and is the next step obvious? If any answer is no, fix it before sending.

## Edge cases and judgement calls
| Situation | What to do |
|---|---|
| Angry sender | Switch to `difficult-emails` |
| Many people in the thread | Reply all only if everyone needs the answer; otherwise reply to the sender |
| Request outside the user's role | Redirect to the right person with an introduction |
| Second-language reply | Draft in the sender's language, with an English translation for the user |
| Reply needs approval from someone else | Draft a holding reply with a date |
| Legal, HR or financial commitments | Flag; suggest checking before sending |

## Handoffs to related skills
- Sorting the inbox: `inbox-triage`
- Hard messages: `difficult-emails`
- Reusable answers: `email-templates`
- Tracking promised replies: `follow-up-tracking`
- Clear longer emails: `email-writing-clarity`

## Worked example
A client sends a four-paragraph email asking for a revised quote, a call next week, an update on a delayed deliverable and whether invoices can go to a new address. The agent lists the four asks, drafts a reply that confirms the quote by Thursday, offers two call times with time zones, gives a one-line update on the deliverable with a new date, and marks the invoice address change as `[confirm with finance]`. The reply is six lines. The user fills the placeholder and sends it in two minutes.

## Common mistakes
- Missing one of several questions.
- Burying the answer in the third paragraph.
- Over-polite filler that hides the point.
- Guessing dates or prices.
- Replying all by default.

## Self-check before you answer
- Is every ask in the thread answered or acknowledged?
- Is the answer in the first line?
- Does the tone match the relationship and the user's voice?
- Are unknowns marked rather than guessed?

---
Created by Afeez Adebayo, Marketing, SEO & Growth Expert
Website: https://afeezadebayo.com
LinkedIn: https://www.linkedin.com/in/afeez-adebayo/
X: https://x.com/za_icon
Source: https://afeezadebayo.com/skills-md/productivity/email-inbox/email-reply-drafting/

Licence: CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/). You may copy, share and adapt this skill, including for commercial use, as long as you credit Afeez Adebayo and link to the source URL above. Keep this notice in any copy or adapted version.
