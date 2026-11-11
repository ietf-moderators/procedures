# Introduction

[RFC9945](https://www.rfc-editor.org/rfc/rfc9945.html) says that the IETF community will treat people with kindness and grace, but not endless patience. It sets up a policy for the moderation of disruptive participation across the IETF's various public contribution channels and discussion forums. It establishes guardrails for moderation and a moderator team. This team is required to develop a set of moderation procedures and facilitate their consistent implementation with chairs and administrators. This document defines those moderation procedures.

## Scope

These procedures apply to all public online IETF forums, as described in Section 3 of RFC9945:
mailing lists, chat groups, and other systems that the IETF or its working groups have chosen to
use, such as GitHub repositories, wikis, and issue trackers.

They do not apply to the forums of the IRTF, the IAB, the RSWG, the RSAB, or the Independent
Submission Stream, unless that body explicitly agrees. Some of those forums are hosted on IETF
infrastructure, so the address of a list is not always a reliable guide. The moderator team
maintains the current list of forums in and out of scope in [scope.md](scope.md), and updates it as
other bodies opt in.

These procedures cover the conduct of individual participants and the remedies applied to them.
They do not restrict the controls administrators already have over a forum as a whole, such as
filtering messages by header, holding all messages to a forum for moderation, or closing a thread.
Those controls are not remedies and are not recorded as incidents. A control aimed at a particular
participant is a remedy, and follows these procedures.

## Terminology

A **forum** is any public IETF participation channel: a mailing list, a chat group, or discussion in
a collaborative tool such as GitHub.

An **administrator** is someone assigned to manage a forum
([RFC9945 Section 1.1](https://www.rfc-editor.org/rfc/rfc9945.html#section-1.1)). Working group
chairs are by default the administrators of every forum their working group uses, and may delegate
that role ([RFC2418 Section 6.4](https://www.rfc-editor.org/rfc/rfc2418.html#section-6.4)). The
owners of non-WG lists are also administrators. The moderator team administers the plenary forums,
and any forum that has no other administrator. Where a forum has more than one administrator, they
are each other's **co-administrators**.

## Principles

Applying these procedures requires judgment both in deciding whether conduct is an incident and in
choosing a remedy. Decision-makers are expected to follow the principles in
[principles.md](principles.md), and reviewers consider them. A respondent who believes a principle
was not followed may raise that when asking for review, but it does not by itself overturn a
decision.

# Responsibilities

## Moderator team

The moderator team can be contacted at ietf-moderators@ietf.org. Participants may use this address
to report disruption, to ask for an incident to be rescinded or a remedy reduced, or to ask any
question about these procedures. Administrators use it to notify the moderator team of incidents
recorded.

The moderator team's responsibilities are to:

* Define these proposed procedures, with community input, for approval by IESG
* Act as administrators of plenary forums
	- ietf@ietf.org
	- last-call@ietf.org
	- Plenary session Zulip chat
* Act as administrator of last resort
	- If there is no defined administrator
	- If administrators are unresponsive
	- In cases of disruption across multiple forums
* Provide training and guidance to administrators
* Maintain the incident register
* Respond to requests and perform actions in a timely manner (defined as "SHOULD be within 48 hours, MUST be within one week"),
  unless the requests are themselves found to be disruptive or abusive (a respondent's first request
  to review an incident never is). This does not apply to
  reviewing held messages; see "Handling messages held for moderation".
* Revise these procedures based on experience, following the same community input and approval process.
* Extend remedies to multiple forums where appropriate

## Administrators

* Accept, acknowledge, and keep track of reports of disruption in their forums
* Implement these procedures
* Record incidents, and the remedies applied, in the incident register
* Send the respondent a private notice for every incident
* Notify co-administrators of reports and actions taken, and the moderator team of incidents recorded
* Review held messages, on a best-effort basis
* Remove each remedy at the end of its period
* Respond to a respondent's requests about their own incidents within one week, or, if unavailable,
  pass the request to the moderator team, which responds instead
* May rescind their own incidents, and reduce the remedies on them.
* May rescind any incident in their forums, or reduce its remedy, after consulting the moderator
  team. This includes incidents recorded by an administrator they have replaced.

## Participants

Participants who see disruption should report it to the forum's administrators or to the moderator
team, rather than replying to it in the forum. Replying on the forum usually adds to the disruption.
Reporting early, before a thread escalates, is better than waiting.

## Respondents

A participant asked to stop disrupting a forum must do so immediately
([RFC9945 Section 4](https://www.rfc-editor.org/rfc/rfc9945.html#section-4)).

A respondent can:

* Expect a private notice for every incident, saying why the conduct fell short, what remedy was
  applied and why, and how to ask for review
* See the history of incidents recorded against them, the maximum remedy available against them,
  and any remedy in force
* Ask the action-taker, an administrator of the forum, the moderator team, or the IESG to rescind an
  incident or reduce a remedy, and get a response. Don't ask them all at once; wait a reasonable time
  for an answer before asking another
* Ask for their remedy to be mentioned in a public statement, and ask that no correction be sent if
  an incident is rescinded
* Take a disagreement with a decision to the responsible Area Director, or to the IETF Chair if
  there is none, and then appeal to the IESG and the IAB
  ([RFC9945 Section 4.1](https://www.rfc-editor.org/rfc/rfc9945.html#section-4.1))

A first request to review each incident, and any appeal, is never treated as disruption or counted
against the respondent. Repeating a request that has already been answered, without new
information, may be disruption. Escalating it to another of those listed above is not repetition.

## Oversight

The moderator team watches how these procedures are used, to catch misuse and uneven impact:

* It reviews every remedy longer than 28 days, after it is applied.
* It looks for patterns in the register: by action-taker, by forum, by the respondent's region where
  known, and by whether the respondent is new to the IETF. This includes looking for any
  administrator who applies remedies much more readily than others.

A respondent is counted as **new to the IETF** if their earliest recorded participation - their
Datatracker account, their first message to an IETF list, or their first meeting registration - was
less than two years before the incident.

If the moderator team thinks an administrator is going too far, it tells them. If they disagree, the
moderator team raises it with the responsible Area Director, or with the IETF Chair where there is
none.
The moderator team does not manage administrators. It reports what it finds to the responsible Area Director.

# Administrator procedures

## Incidents

An **incident** is a single occasion on which an administrator finds that a participant's
conduct in an IETF forum was disruptive. The participant whose conduct it was is the **respondent**
of that incident.

### What counts as disruption

The forms of disruption below are examples. The list is not exhaustive: whether conduct is
disruptive is a matter for the administrator's judgment, guided by the [principles](principles.md).

- [Uncivil commentary](#handling-uncivil-commentary)
	- Attacking people
	- Attacking groups of people
	- Attacking an idea in an insulting or excessively hostile manner
	- Clearly lacking in respect and courtesy (the expectations of [RFC7154](https://datatracker.ietf.org/doc/html/rfc7154))
	- Inciting hate
- [Messages unrelated to the forum's purpose](#handling-messages-unrelated-to-the-forums-purpose)
- [Behavior that hinders the work of the group](#handling-behavior-that-hinders-the-work-of-the-group)
- Sealioning (arguing ad nauseam): incessant requests for evidence or data, even while remaining superficially polite
  ([RFC9945 Appendix B](https://www.rfc-editor.org/rfc/rfc9945.html#appendix-B)). It is judged by
  its effect, not by guessing at intent: the requests continue after reasonable answers have been
  given, and degrade the progress of technical debate. See also the descriptions from
  [Merriam-Webster](https://www.merriam-webster.com/wordplay/sealioning-internet-trolling) and
  [Wikipedia](https://en.wikipedia.org/wiki/Sealioning).
- [Astroturfing](#handling-astroturfing) (an orchestrated campaign): a campaign to make a position appear to have wider
  support than is the case. See also the descriptions from
  [Merriam-Webster](https://www.merriam-webster.com/dictionary/astroturfing) and
  [Wikipedia](https://en.wikipedia.org/wiki/Astroturfing).
- [Messages containing confidential information](#handling-messages-containing-confidential-information)
- [Repeated inclusion of derivative rights notices](#handling-repeated-inclusion-of-derivative-rights-notices)
	- As per the [IESG statement](https://datatracker.ietf.org/doc/statement-iesg-statement-on-clarifying-derivative-works-rights/)
- [Messages containing slop](#handling-slop)
- [Debating specific moderation actions](#handling-debate-about-moderation-actions) outside
  mod-discuss@ietf.org

As [RFC9945 Appendix B](https://www.rfc-editor.org/rfc/rfc9945.html#appendix-B) says:

> These items are examples. Moderators and administrators may take moderation actions for many
> other cases.
>
> The moderator team's task consists of subjective judgment calls. Behaviors not listed here might
> require moderation, and it is not possible to write a complete list of all such behaviors.

The same is true of administrators acting under these procedures.

### Counting incidents

Incidents are counted as follows:

- A connected series of messages - one thread, or several messages over a short period making
  the same disruption - is **one** incident, not one per message. The series ends when the
  respondent is asked to stop or notified of an incident; conduct that continues after that is a
  new incident.
- Incidents are counted per participant across the whole IETF, not per forum. An incident recorded
  by the administrator of one forum counts when the administrator of another forum acts later.
- An **eligible incident** is one that has not been rescinded and whose date of the incident is
  within the past five years. Only eligible incidents are counted. Older incidents stay in the register; they
  just stop counting. RFC9945 does not set the five-year window: it is a starting point, and will be
  reviewed in the light of experience along with the rest of these procedures.
- The count includes every eligible incident, regardless of its form.

Every incident MUST be recorded in the incident register and notified to the respondent, to
co-administrators, and to the moderator team.

## Incident register

Incidents are recorded in the **incident register**, maintained by the moderator team.

### What the register records

For each incident:

- An identifier
- The date of the incident (when the conduct occurred), and the date it was recorded
- The forum(s) in which it occurred
- The form of disruption
- The respondent
- The action-taker
- The remedy applied, if any: whether hold or ban, its duration, and when it ends
- Whether it has been rescinded, by whom, when, and why
- Whether a remedy has been reduced, by whom, when, and why
- The private detail: links to the messages concerned, the private notice sent to the respondent,
  and any further correspondence with them

Although the register is not public, write everything in it as if it were. Record which content the
remedy was applied for, by linking to it rather than copying it, and which form of disruption it
is. Do not record personal assessments of the respondent, opinions about them, or speculation about
their motives.

One human always takes the action, and is recorded as the **action-taker**. Where administrators
decided jointly, one of them still takes the action and is the action-taker for that incident. They
may name the others in the private detail, but that grants no additional access.

### Datatracker accounts

Incidents are recorded against the respondent's Datatracker account, not against an email address,
so every address on that account shares a single incident count.

If the respondent does not already have a Datatracker account, the moderator team creates one,
linked to the email address from which the disruption came.

If credible evidence shows that disruption from another address or Datatracker account came from
the same person, the moderator team records the incident against that person's existing account.
The other address is not added to the account. A person does not avoid the incident count by using
multiple addresses or accounts. If the identification turns out to be wrong, the fix is to rescind
the incident.

### Who sees what

| Who | Sees |
|---|---|
| The action-taker, at the point of recording an incident | the maximum remedy available against the respondent based on the remedy ladder |
| The action-taker, the respondent, the moderator team, the IESG, and legal counsel | the full detail of that incident |
| Any respondent | the history of incidents recorded against them, the maximum remedy available against them, and any current remedy in force |
| The moderator team, the IESG, and legal counsel | every incident, and every participant's incident count and history |

Once a year the moderator team publishes a report on the use of these procedures in that year, so
that the community can hold the moderator team and administrators to account. It gives:

- the number of incidents recorded, by form of disruption and by forum
- the number of remedies applied, by type and duration
- the number of individuals with each type and duration of remedy against them
- the number of incidents rescinded and remedies reduced
- how many respondents were new to the IETF

and whatever commentary the team wishes to add, including on any patterns found under
"Oversight". The report does not identify respondents or action-takers.

### Rescinding an incident

Rescinding an incident withdraws the finding: the incident is treated as never having been recorded.
Any of the following may rescind an incident, acting alone and recording a reason:

- The action-taker, for their own incidents
- Any current administrator of the forum, including one who has since replaced the action-taker,
  after consulting the moderator team
  ([RFC9945 Section 3](https://www.rfc-editor.org/rfc/rfc9945.html#section-3))
- The moderator team
- The IESG

Administrators of other forums may not rescind an incident. They ask the moderator team or the IESG
instead.

The respondent may ask any of them to rescind an incident.

It is appropriate to rescind an incident when it is found that the determination of disruption was
made in error. If the incident did occur but the respondent is determined to be willing to improve
their behavior, then reducing the remedy (see below) is a better choice.

A finding may also be in error because the respondent's account was compromised and the messages
were not theirs. A hold may still be appropriate until the account is secured, and repeated
compromises are a reason to keep it.

A rescinded incident is no longer eligible: it is removed from the count and from the calculation of
remedies available against this respondent. It remains visible in full (marked rescinded) to the
action-taker, the respondent, the moderator team, the IESG, and legal counsel.

When an incident is rescinded, any remedies currently in effect on the respondent are reviewed to
see if they should be reduced or removed.

If a public statement was made about the incident, whoever rescinds it sends a correction to the
same forums, saying that the finding has been withdrawn, unless the respondent asks that none be sent.

When an incident is rescinded because the finding was made in error, the action-taker should
apologise to the respondent, privately, and also publicly if a public statement was made.

### Reducing a remedy

Reducing a remedy lifts it, or brings its end date forward. It changes the remedy, not the
finding: the incident stays in the register and stays eligible, and the remedy ladder is unaffected.

Any of the following may reduce a remedy, acting alone and recording a reason:

- The action-taker, for their own incidents
- Any current administrator of the forum, after consulting the moderator team
- The moderator team
- The IESG

As with rescinding, administrators of other forums may not reduce a remedy.

The respondent may ask any of them to reduce a remedy, for example by undertaking to change their
behavior. Reduction is a grace and not a right.

Whoever reduces a remedy notifies the respondent and the administrators of the affected forums. If
the remedy is lifted immediately, follow "Removal of a remedy" below now; if its end date is
brought forward, follow it on or before the new end date.

### Until the register exists

The register has yet to be built. Until it is, the moderator team maintains the record, and an
administrator handling an incident asks the moderator team what remedies are available.

### Existing posting rights actions

RFC9945 obsoletes the posting rights (PR) actions of [RFC3683](https://www.rfc-editor.org/rfc/rfc3683.html).
When these procedures take effect, the moderator team handles each PR action listed on the
[IESG's PR actions page](https://www.ietf.org/about/groups/iesg/posting-rights-actions/) as follows:

- If the PR action was approved or last updated within the past five years, record three incidents
  against its respondent in the register, each dated on the date of that approval or update. A PR
  action always follows several incidents of disruption, so the respondent does not start from
  zero; their next incident is their fourth.
- If it was approved or last updated more than five years ago, record nothing, as any incidents
  it represented would no longer be eligible.

In either case, remove the restrictions the PR action imposed by setting the list default action
for the respondent on every affected list, and send them a private message saying so and linking to
these procedures.

### Requirements for the tools team

The register must:

- Record each incident with the fields listed above.
- Provide a method for administrators, the moderator team, and the IESG to create entries in
  the register, displaying the maximum remedy available in days, and allowing entry of any
  number of days equal to or less than the maximum allowed.
- Either apply the recorded remedy automatically or provide instructions on how to apply it, and
  remind the action-taker and the administrators of the affected forums when it is due to expire.
- Notify the moderator team of each incident recorded.
- Record incidents against the respondent's Datatracker account, so that counts are collected
  across all addresses on that account.
- Allow the moderator team to create a Datatracker account for a respondent who has none, linked
  to the address from which the disruption came.
- Allow the moderator team to record an incident from any address against an existing account,
  without adding that address to the account.
- Allow an incident to be recorded against an account on another tool, such as a GitHub account,
  where no Datatracker account can be identified, and move its incidents to a Datatracker account
  if one is identified later.
- Record exactly one action-taker per incident, and restrict the private detail of an incident to
  the action-taker, the respondent, the moderator team, the IESG, and legal counsel. Anyone named in
  the private detail gains no additional access by being named.
- Allow the action-taker, any current administrator of the forum, the moderator team and the IESG
  to rescind an incident, recording who rescinded it, when, and why.
- Allow the action-taker, any current administrator of the forum, the moderator team and the IESG
  to reduce a remedy, recording who reduced it, when, and why, and notify the respondent and the administrators of the affected forums.
- Compute each participant's count from eligible incidents only, so that an incident leaves the
  count when it is rescinded or five years after the date of the incident, while the record is
  retained.
- Offer a five-year maximum for any incident occurring within one year after the end of a
  previous five-year remedy, whatever the respondent's count.
- When an incident is rescinded, remove it from every view except those of the parties who see
  its full detail, recalculate affected counts, reduce any remedy still in force to the
  recalculated maximum (or provide instructions for same), notify the respondent and the
  administrators of the affected forums, and remind whoever rescinded it to send a correction if
  a public statement was made.
- Display to the moderator team aggregate counts of incidents and remedies, by form of
  disruption, type and duration of remedy, forum, action-taker, the respondent's region where
  known, and whether the respondent is new to the IETF, and flag each remedy longer than 28 days
  for review.

## Remedies

### The remedy ladder

The number of eligible incidents, **including the one being handled**, sets the maximum remedy
available. The incident register computes this and tells the acting administrator
the maximum. Any remedy up to and including that maximum may be applied - or none at all. In
general, the minimal action necessary should be taken.

| Eligible incidents (including this one) | Maximum remedy |
|---|---|
| 1 | 3 days |
| 2 | 7 days |
| 3 | 28 days (1 month) |
| 4 | 90 days (3 months) |
| 5 | 365 days (one year) |
| 6 or more | 1825 days (5 years) |

A remedy is a **hold for moderation** or a **ban**, of any duration up to the maximum. No remedy
may exceed five years. A respondent is immediately eligible for another five-year remedy if an
incident occurs within one year after the end of a previous five-year remedy, whatever their
incident count at that time.

A single incident, however serious, unlocks nothing beyond a 3-day remedy. Where conduct is serious
enough that the ladder is plainly an inadequate response, refer the matter to the Ombudsteam (if it may be
[harassment](https://datatracker.ietf.org/doc/statement-iesg-ietf-anti-harassment-policy-20131103/))
or raise it with the IESG. These procedures do not give administrators a route around the ladder.

### Choosing between a hold and a ban

A hold for moderation is the default: the respondent's messages are reviewed before delivery, so
non-disruptive messages still reach the forum.

A ban stops messages reaching the forum at all. Prefer a ban only where a hold will not work:

- the volume of held messages is unmanageable for the administrators, or
- the respondent is using the moderation queue itself disruptively.

A hold already in force may be converted to a ban for the remainder of its duration, and MUST be
notified as such. Converting a hold does not extend it; a longer remedy requires a new incident.

### Actions not gated by the incident count

**Private notice to the respondent.** Mandatory for every incident. See "Handling disruption" below.

**Public statement.** At the administrator's judgment, for any incident. Send it to all IETF forums
that the original message was sent to.

- Advise why the message falls short of our standards
- Include links to [RFC7154](https://datatracker.ietf.org/doc/html/rfc7154) and these procedures
- If a remedy has been applied, consider whether to mention it
	- If longer than 14 days, it MUST be mentioned
	- If 14 days or less, it MAY be
	- If the respondent requests, it MUST be
- If the incident is later rescinded, a correction follows (see "Rescinding an incident")

**Central address block** and **hiding a message from the mail archive** are not remedies on the
ladder. They are anti-spam and confidentiality measures, covered in the relevant subsections below.

## Handling disruption

If the disruption may also be [harassment](https://datatracker.ietf.org/doc/statement-iesg-ietf-anti-harassment-policy-20131103/),
report it to the Ombudsteam. Their work is strictly confidential and takes time. Do not assume they will take action, so in all cases
these procedures should still be followed. Any actions they take will be in addition to these procedures.

Otherwise, follow these steps for every incident:

1. Discuss the message(s) with your co-administrators and decide whether the conduct was disruptive.

2. Decide whether to ask the participant to stop before recording an incident. For judgement-based
   forms of disruption, you SHOULD follow the "Warning first" principle in [principles.md](principles.md)
   unless they have already been asked to stop the same or similar conduct. If you ask and
   the conduct stops, there is no incident. If the conduct is egregious, it might be necessary to block
   traffic immediately.

3. Otherwise, this is an incident. Record it in the register. It will tell you the maximum remedy
   available against the respondent.

4. Choose a remedy, up to that maximum, or none, and record it, following "Choosing a remedy" in
   [principles.md](principles.md#choosing-a-remedy).

5. Send a private notice to the respondent:
   - Advising why the conduct falls short of our standards
   - Noting that prior incidents were taken into account, if the maximum remedy shows there were any
   - Including a link to these procedures
   - Advising the remedy applied, if any, and its duration
   - Saying briefly why that remedy and duration were chosen (see "Reasons" in
     [principles.md](principles.md#fairness-and-oversight))
   - Saying how to ask for the incident to be rescinded or the remedy reduced, and how to appeal
     (see "Respondents")
   - If a hold is applied, saying that non-disruptive messages will be allowed through to the forum
     on a best-effort basis
   - Adding anything the relevant subsection below requires

6. Notify your co-administrators and the moderator team.

7. Consider whether to send a public statement.

In examining email threads for disruptions, administrators should judge disruptions on qualitative (quality of technical content) and
quantitative (number of times a mail message post causes a problem).  An administrator is uniquely qualified to judge the technical content on
whether the information provides a substantive additions to the discussion whether the discussions agrees with or disagrees with the
draft or issue the Working Group is discussing.  Quantitative counts can be generated by hand or by IETF tools.

If the disruption is occurring in multiple forums, the moderator team has the ability to extend remedies across all IETF forums.

### Handling uncivil commentary

Include links to [RFC7154](https://datatracker.ietf.org/doc/html/rfc7154) in the private notice.

### Handling messages unrelated to the forum's purpose

Consider if the message(s) would fit the purpose of another IETF forum.

If so, reply in this forum only, saying where the discussion belongs and asking participants to
start a new thread there, linking to this one if useful. Do not copy the other forum, as replies
would then go to both.

For messages outside the remit of the IETF, treat as spam.

### Handling debate about moderation actions

A debate about whether a specific moderation action was right can take over a forum. The place for
it is mod-discuss@ietf.org, the public list for discussing IETF moderation policies and practices,
including specific actions.

If a debate about a moderation action starts in another forum, handle it as a message unrelated to
the forum's purpose: reply in this forum only, asking participants to continue on
mod-discuss@ietf.org. Continuing the debate in the forum after that is disruption.

This does not apply to:

- A public statement about an incident, or a correction when one is rescinded
- A respondent asking for review or appealing through the routes in "Respondents"
- Discussion on mod-discuss@ietf.org itself

### Handling astroturfing

Astroturfing is a campaign to make a position appear to have wider support than is the case. There are three types for
the purposes of these procedures:

1. A participant pretends to be multiple people in order to simulate a larger faction. If an administrator comes across
credible evidence of this behavior, it is an incident.

2. A group of participants uses false associations to appear that a point of view comes from more than one
employer. For example, three employees of example.com pretend to be from abc.com, def.com, and ghi.com to suggest there
is broad industry support for a position. If the administrator finds evidence the stated affiliation is false and
deceitful, it is an incident.

3. A stated affiliation is true but omits important disclosures. For example, a professor uses their university
affiliation while also under contract to a corporation with a financial interest in the question. The administrator
SHOULD remind the participant of the interest. If the participant does not then disclose, the administrator SHOULD
directly announce it to the forum. If the administrator believes the lack of disclosure is a deliberate attempt to
deceive, it is an incident.

Nothing in this section should be construed as a requirement for administrators to launch extensive investigations
into the true identities and/or affiliations of participants.

### Handling spam

Spam is not handled as an incident. It is dealt with as below, unless the sender is believed to be
a genuine participant, in which case it is treated as disruption under "Handling disruption".
If a genuine participant's account appears to have been compromised, record the incident as usual;
see "Rescinding an incident" for how to withdraw it once that is established.

#### Spam definition

[Disruptive posting](https://chairs.ietf.org/mailing-lists/disruptive-posting) identifies two types:

- Messages unrelated to the IETF
- Advertising

It notes this is a non-exhaustive list. These procedures add:

- Messages with no indication that the sender is a real person
- Messages with no indication that the sender has an understanding of how the IETF works

Mentioning an event or activity that is likely to interest participants is not by itself
disruptive, whether or not the IETF sponsors it. Use reasonable judgment: it becomes a problem
only when it gets in the way of the forum's work.

#### Spam procedure

If the sender has been automatically held for moderation because they are not a subscriber to any IETF list:

- Decide if they are likely to be a genuine newcomer
  - If yes, reject with [newcomer-rejection-message.txt](newcomer-rejection-message.txt)
  - If no, discard

If it has been held for another reason:

- Reject or discard as needed

Otherwise, the spam has already been delivered to subscribers.

- Consider whether it should remain in the mail archive
  - If appropriate, ask support@ietf.org to hide it
- If the sender address may have been spoofed:
  - Does the tools team need to tighten controls?
  - Does the sender need to tighten DMARC?
- If the sender is believed to be genuine:
  - Treat as disruption

#### Dealing with repeated spam

As per the advice in [Spam control](https://chairs.ietf.org/mailing-lists):

- Ask support@ietf.org to block the address centrally
- For immediate results, ban this sender from the affected list (optional)

### Handling behavior that hinders the work of the group

This is conduct that may be civil and on topic but obstructs progress: for example, repeatedly
arguing against an approved charter, reopening a consensus call without new information, continuing
to debate a point after the chairs have clearly closed that debate, or making the same point in reply
after reply so that other voices are drowned out.

Disagreement, however persistent, is not disruption. The test is whether the conduct adds to the
discussion, not whether the administrator agrees with it. Asking the chairs to revisit a decision
with new information, or appealing under [RFC2026](https://www.rfc-editor.org/rfc/rfc2026.html#section-6.5),
is never disruption.

In the private notice, additionally identify the specific conduct, and say that it is the conduct
being addressed, not their technical position.

### Handling messages containing confidential information

Report the message to support@ietf.org.

A participant who shares confidential information by mistake, and has not done so before, is
reminded privately rather than recorded as an incident. It is an incident if they knew the
information was confidential, or if it happens again; this is in addition to, not instead of,
reporting it.

### Handling repeated inclusion of derivative rights notices

Outside of an internet-draft, [IESG Statement on Clarifying Derivative Works Rights](https://datatracker.ietf.org/doc/statement-iesg-statement-on-clarifying-derivative-works-rights/)
says that notices that claim that derivative rights are being withheld for a Contribution are not conformant to IETF policies.
Repeated inclusion of such notices is a disruption.

In the private notice, additionally:
- Refer to the [IESG Statement on Clarifying Derivative Works Rights](https://datatracker.ietf.org/doc/statement-iesg-statement-on-clarifying-derivative-works-rights/)
- Advise why this notice is not conformant to IETF policies
- Say that messages without the notice will be allowed through to the forum on a best-effort basis

### Handling slop

"Slop" is voluminous content that is devoid of technical substance: hundreds of words that make a
simple point, or no point at all. Slop is often the product of AI, though administrators are not
expected to determine whether the content was written by a human. Slop can also be uncivil, spam, or
unrelated to the forum's purpose, in which case it can be handled in accordance with the procedures
above.

## Handling messages held for moderation

Assess held messages on a best-effort basis, as administrators are reasonably able to. There is no
committed response time.

- If it is spam, follow the [spam procedure](#spam-procedure)
- If it is non-disruptive, allow it through
- If disruptive, reject with a reason as to why

Rejecting a held message is not by itself a new incident. If the held messages amount to a fresh
occasion of disruption, handle it under "Handling disruption" above.

If the volume of held messages is unmanageable, the hold may be converted to a ban for its remaining
duration - see "Choosing between a hold and a ban".

If the respondent is only sending non-disruptive messages:

- You have the option to temporarily remove hold for moderation.
- If disruption recurs, the hold may be reinstated without notice for the remainder of the remedy period.

## Removal of a remedy

On or before the end of the remedy period:

1. Remove the hold or ban (for a mailing list, by setting the list default action for the respondent)
2. Send a private message to the respondent confirming the remedy is no longer in place, and referring to what these procedures, as currently approved, say will happen if there is a further incident

Removing a remedy does not remove the incident from the count. It continues to count for five
years from the date of the incident.

# Repositories and other tools

These procedures apply to GitHub repositories, wikis, issue trackers, shared notes and similar tools
that the IETF owns, such as a repository in an IETF GitHub organization. Disruption there is
an incident like any other, and the remedy ladder applies.

The administrators of such a tool are the people who control it. For a working group repository,
these are normally the working group chairs.

A tool owned by an individual, such as a repository in a draft author's, editor's or chair's own
account, is not an IETF forum, even when the IETF links to it. Its owners are not administrators
under these procedures and do not record incidents. They may restrict participation as they see
fit.

Most of these tools have no hold for moderation, so a remedy is usually applied as a ban: for
example, blocking the respondent from the repository's GitHub organization until the remedy ends.
Disruptive comments may also be hidden, and a disruptive discussion locked. Like hiding a message
from the mail archive, these are not remedies on the ladder.

The administrator records the respondent's account name on the tool, and the moderator team
identifies the person's Datatracker account, as for any other address (see "Datatracker accounts").
If the person cannot be identified, the incident is recorded against the account on the tool, which
has its own incident count. If that account is later linked to a person, its incidents are moved to
that person's Datatracker account.

# Chat moderation during sessions

Moderation of chat during a meeting session has a different procedure, reflecting the synchronous
nature of the discussion. Other chat forums follow the procedures above. A chat message is
disruptive if it would be disruptive as a message to a mailing list, and vice versa.

When an administrator sees a disruptive chat message during a session, they delete it immediately
if it is spam or contains confidential information. Otherwise, they post a public message to the
participant saying that further disruption will be moderated.

If the same participant disrupts the chat again in the same session, the administrator deletes the
message and blocks the participant from the chat for the rest of the session.

These actions are independent of the remedy ladder. If the conduct warrants it, the administrator may
also record it as an incident under "Handling disruption".

# Open questions

1. How do chairs delegate administration responsibility, and how do we track that?
2. How do we identify the administrators of [non-WG lists](https://datatracker.ietf.org/list/nonwg)?
