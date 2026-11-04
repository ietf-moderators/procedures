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

# Responsibilities

## Moderator team

The moderator team can be contacted at ietf-moderators@ietf.org. Participants may use this address
to report disruption, to ask for an incident to be rescinded or a sanction reduced, or to ask any
question about these procedures. Administrators use it to notify the moderator team of reports and
actions taken.

* Define these proposed procedures, with community input, for approval by IESG
* Act as administrators of plenary lists
	- ietf@ietf.org
	- last-call@ietf.org
	- Plenary session Zulip chat
* Act as administrator of last resort
	- If there is no defined administrator
	- If administrators are unresponsive
	- In cases of disruption across multiple lists
* Provide training and guidance to administrators
* Maintain the incident register
* Respond to requests and perform actions in a timely manner (defined as "SHOULD be within 48 hours, MUST be within one week").
* Revise these procedures based on experience, following the same community input and approval process.
* Extend sanctions to multiple lists where appropriate

## Administrators

* Implement the approved procedures
* Record incidents, and the sanctions applied, in the incident register
* Notify moderator team of reports and actions taken
* May rescind their own incidents, and reduce the sanctions on them.

# Administrator procedures

## Incidents

An **incident** is a single occasion on which an administrator finds that a participant's
conduct in an IETF forum was disruptive. The participant whose conduct it was is the **respondent**
of that incident.

### What counts as disruption

Disruption can take any of these forms.

- Uncivil commentary
	- Attacking people
	- Attacking groups of people
	- Attacking an idea in an insulting or excessively hostile manner
	- Clearly lacking in respect and courtesy (the expectations of [RFC7154](https://datatracker.ietf.org/doc/html/rfc7154))
	- Inciting hate
- Messages unrelated to the list's purpose
- Behavior that hinders the work of the group
- Sealioning: the disingenuous action by a commenter of making an ostensible effort to engage in
  sincere and serious civil debate, usually by asking persistent questions of the other commenter.
  The questions appear as an effort to learn, but degrade the progress of technical debate and the
  goodwill of the list participants. See the descriptions from
  [Merriam-Webster](https://www.merriam-webster.com/wordplay/sealioning-internet-trolling) and
  [Wikipedia](https://en.wikipedia.org/wiki/Sealioning).
- Astroturfing
- Messages containing confidential information
- Repeated inclusion of derivative rights notices
	- As per the [IESG statement](https://datatracker.ietf.org/doc/statement-iesg-statement-on-clarifying-derivative-works-rights/)
- Messages containing slop
- Debating specific moderation actions on any list other than the list(s) designated for that purpose.

### Counting incidents

- A connected series of messages - one thread, or several messages over a short period making
  the same disruption - is **one** incident, not one per message.
- Incidents are counted per participant across the whole IETF, not per list. An incident recorded
  by the administrator of one list counts when the administrator of another list acts later.
- An **eligible incident** is one that has not been rescinded and whose conduct occurred within the
  past five years. Only eligible incidents are counted.
- All forms of disruption share a single count. It does not matter whether the earlier incidents
  were of the same kind as the one being handled now.
- Every incident MUST be recorded in the incident register, and notified to the respondent and to
  co-administrators.

## Incident register

Incidents are recorded in the **incident register**, maintained by the moderator team.

### What the register records

For each incident:

- An identifier
- The date of the conduct, and the date it was recorded
- The forum(s) in which it occurred
- The form of disruption
- The respondent
- The action-taker
- The sanction applied, if any: whether hold or ban, its duration, and when it ends
- Whether it has been rescinded, by whom, when, and why
- Whether a sanction has been reduced, by whom, when, and why
- The private detail: the messages, the reasoning, and correspondence with the respondent

One human always takes the action, and is recorded as the **action-taker**. Where administrators
decided jointly, one of them still takes the action and is the action-taker for that incident. They
may name the others in the private detail, but that grants no additional access.

### Datatracker accounts

Incidents are recorded against the respondent's Datatracker account, not against an email address,
so every address on that account shares a single incident count.

If the respondent does not already have a Datatracker account, the moderator team creates one,
linked to the email address from which the disruption came.

If disruption from another address is identified as coming from the same person, the moderator team
identifies their existing account and records the incident against it. The other address is not
added to the account. If the identification turns out to be wrong, the remedy is to rescind the
incident.

### Who sees what

| Who | Sees |
|---|---|
| The action-taker, at the point of recording an incident | the maximum sanction available for the respondent based on the sanction ladder |
| The action-taker, the respondent, the moderator team, the IESG, and legal counsel | the full detail of that incident |
| Any respondent | the history of incidents recorded against them, the maximum sanction available against them, and any current sanction in force |
| The moderator team, the IESG, and legal counsel | every incident, and every participant's incident count and history |

Once a year the moderator team publishes a report giving the number of incidents recorded in that
year, with a count of each type and severity of sanction applied and whatever commentary the team
wishes to add.

### Rescinding an incident

Rescinding an incident withdraws the finding: the incident is treated as never having been recorded.
Any of the following may rescind an incident, acting alone and recording a reason:

- The action-taker, for their own incidents
- The moderator team
- The IESG

No other administrator may rescind an incident, even a co-administrator of the same forum who took
part in the decision. They ask the moderator team or the IESG instead.

The respondent may ask any of them to rescind an incident.

A rescinded incident is no longer eligible: it is removed from the count and from the calculation of
sanctions available against this respondent. It remains visible in full (marked rescinded) to the
action-taker, the respondent, the moderator team, the IESG, and legal counsel.

When an incident is rescinded, any sanctions currently in effect on the respondent are reviewed to
see if they should be reduced or removed.

If a public statement was made about the incident, whoever rescinds it sends a correction to the
same forums, saying that the finding has been withdrawn, unless the respondent asks that none be sent.

It is appropriate to rescind an incident when it is found that the determination of disruption was made
in error.  If the incident did occur but the respondent is determined to be willing to improve their
behavior, then reducing the sanction (see below) is a better choice.

A finding may also be in error because the respondent's account was compromised and the messages
were not theirs. A hold may still be appropriate until the account is secured, and repeated
compromises are a reason to keep it.

### Reducing a sanction

Reducing a sanction lifts it, or brings its end date forward. It changes the sanction, not the
finding: the incident stays in the register and stays eligible, and the sanction ladder is unaffected.

Any of the following may reduce a sanction, acting alone and recording a reason:

- The action-taker, for their own incidents
- The moderator team
- The IESG

As with rescinding, no other administrator may reduce a sanction; co-administrators ask the moderator
team or the IESG.

The respondent may ask any of them to reduce a sanction, for example by undertaking to change their
behavior. Reduction is a grace and not a right.

Whoever reduces a sanction notifies the respondent and the administrators of the affected forums. If
the sanction is lifted immediately, follow "Removal of a sanction" below now; if its end date is
brought forward, follow it on or before the new end date.

### Until the register exists

The register has yet to be built. Until it is, the moderator team maintains the record, and an
administrator handling an incident asks the moderator team what sanctions are available.

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
this procedure.

### Requirements for the tools team

The register must:

- Record each incident with the fields listed above.
- Provide a method for administrators, the moderator team, and the IESG to create entries in
  the register, displaying the maximum sanction available in days, and allowing entry of any
  number of days equal to or less than the maximum allowed.
- Either apply the recorded sanction automatically or provide instructions on how to apply it, and
  remind the action-taker and the administrators of the affected forums when it is due to expire.
- Record incidents against the respondent's Datatracker account, so that counts are collected
  across all addresses on that account.
- Allow the moderator team to create a Datatracker account for a respondent who has none, linked
  to the address from which the disruption came.
- Allow the moderator team to record an incident from any address against an existing account,
  without adding that address to the account.
- Record exactly one action-taker per incident, and restrict the private detail of an incident to
  the action-taker, the respondent, the moderator team, the IESG, and legal counsel. Anyone named in
  the private detail gains no additional access by being named.
- Allow the action-taker, the moderator team and the IESG to rescind an incident, recording who
  rescinded it, when, and why.
- Allow the action-taker, the moderator team and the IESG to reduce a sanction, recording who
  reduced it, when, and why, and notify the respondent and the administrators of the affected forums.
- Compute each participant's count from eligible incidents only, so that an incident leaves the
  count when it is rescinded or five years after the date of the conduct, while the record is
  retained.
- Offer a five-year maximum for any incident occurring within one year after the end of a
  previous five-year sanction, whatever the respondent's count.
- When an incident is rescinded, remove it from every view except those of the parties who see
  its full detail, recalculate affected counts, reduce any sanction still in force to the
  recalculated maximum (or provide instructions for same), notify the respondent and the
  administrators of the affected forums, and remind whoever rescinded it to send a correction if
  a public statement was made.
- Display to the moderator team an aggregate count of incidents recorded each year, by type
  and severity of sanction applied.

## Sanctions

### The sanction ladder

The number of eligible incidents, **including the one being handled**, sets the maximum sanction
available. The incident register computes this and tells the acting administrator
the maximum. Any sanction up to and including that maximum may be applied - or none at all. In
general, the minimal action necessary should be taken.

| Eligible incidents (including this one) | Maximum sanction |
|---|---|
| 1 | notice only |
| 2 | 7 days |
| 3 | 28 days (1 month) |
| 4 | 90 days (3 months) |
| 5 | 365 days (one year) |
| 6 or more | 1825 days (5 years) |

A sanction is a **hold for moderation** or a **ban**, of any duration up to the maximum. No sanction
may exceed five years. A respondent is immediately eligible for another five-year sanction if an
incident occurs within one year after the end of a previous five-year sanction, whatever their
incident count at that time.

A single incident, however serious, unlocks nothing beyond a notice. Where conduct is serious enough
that the ladder is plainly an inadequate response, refer the matter to the Ombudsteam (if it may be
[harassment](https://datatracker.ietf.org/doc/statement-iesg-ietf-anti-harassment-policy-20131103/))
or raise it with the IESG. These procedures do not give administrators a route around the ladder.

### Choosing between a hold and a ban

A hold for moderation is the default: the respondent's messages are reviewed before delivery, so
non-disruptive messages still reach the list.

A ban stops messages reaching the list at all. Prefer a ban only where a hold will not work:

- the volume of held messages is unmanageable for the administrators, or
- the respondent is using the moderation queue itself disruptively.

A hold already in force may be converted to a ban for the remainder of its duration, and MUST be
notified as such. Converting a hold does not extend it; a longer sanction requires a new incident.

### Actions not gated by the incident count

**Private notice to the respondent.** Mandatory for every incident. See "Handling disruption" below.

**Public statement.** At the administrator's judgment, for any incident. Send it to all IETF forums
that the original message was sent to.

- Advise why the message falls short of our standards
- Include links to [RFC7154](https://datatracker.ietf.org/doc/html/rfc7154) and this procedure
- If a sanction has been applied, consider whether to mention it
	- If longer than 14 days, it MUST be mentioned
	- If 14 days or less, it MAY be
	- If the respondent requests, it MUST be
- If the incident is later rescinded, a correction follows (see "Rescinding an incident")

**Central address block** and **hiding a message from the mail archive** are not sanctions on the
ladder. They are anti-spam and confidentiality measures, covered in the relevant subsections below.

## Handling disruption

If the disruption may also be [harassment](https://datatracker.ietf.org/doc/statement-iesg-ietf-anti-harassment-policy-20131103/),
report it to the Ombudsteam. Their work is strictly confidential and takes time. Do not assume they will take action, so in all cases
the procedures in this document should still be followed. Any actions they take will be in addition to these procedures.

Otherwise, follow this procedure for every incident:

1. Discuss the message(s) with your co-administrators and decide whether the conduct was disruptive.
   If it was, this is an incident.

2. Record the incident in the register. It will tell you the maximum sanction available for the
   respondent.

3. Choose a sanction, up to that maximum, or none, and record it.

4. Send a private message to the respondent:
   - Advising why the conduct falls short of our standards
   - Noting that prior incidents were taken into account, if the maximum sanction shows there were any
   - Including a link to this procedure
   - Advising the sanction applied, if any, and its duration
   - If a hold is applied, saying that non-disruptive messages will be allowed through to the list
     in a timely manner
   - Adding anything the relevant subsection below requires

5. Notify your co-administrators.

6. Consider whether to send a public statement.

In examining email threads for disruptions, administrators should judge disruptions on qualitative (quality of technical content) and
quantitative (number of times a mail message post causes a problem).  An administrator is uniquely qualified to judge the technical content on
whether the information provides a substantive additions to the discussion whether the discussions agrees with or disagrees with the
draft or issue the Working Group is discussing.  Quantitative counts can be generated by hand or by IETF tools.

If the disruption is occurring in multiple forums, the moderation team have the ability to extend sanctions across all IETF forums.

### Handling uncivil commentary

Include links to [RFC7154](https://datatracker.ietf.org/doc/html/rfc7154) in the private message.

### Handling messages unrelated to the list's purpose

Consider if the message(s) would fit the purpose of another IETF list.

If so, send a reply to the list, requesting that further discussion occurs on that list and not this one.
[Add best practice with respect to cc/bcc/reply-to]

For messages outside the remit of the IETF, treat as spam.

### Handling astroturfing

Astroturfing is a campaign to make a position appear to have wider support than is the case. There are three types for
the purposes of this document:

1. A participant pretends to be multiple people in order to simulate a larger faction. If an administrator comes across
credible evidence of this behavior, it is an incident.

2. A group of participants uses false associations to appear that a point of view comes from more than one
employer. For example, three employees of example.com pretend to be from abc.com, def.com, and ghi.com to suggest there
is broad industry support for a position. If the administrator finds evidence the stated affiliation is false and
deceitful, it is an incident.

3. A stated affiliation is true but omits important disclosures. For example, a professor uses their university
affiliation while also under contract to a corporation with a financial interest in the question. The administrator
SHOULD remind the participant of the interest. If the participant does not then disclose, the administrator SHOULD
directly announce it to the list. If the administrator believes the lack of disclosure is a deliberate attempt to
deceive, it is an incident.

Nothing in this section should be construed as a requirement for administrators to launch extensive investigations
into the true identities and/or affiliations of participants.

### Handling spam

Spam is not handled as an incident. It is dealt with as below, unless the sender is believed to be
a genuine participant, in which case it is treated as disruption and the procedure above applies.
If a genuine participant's account appears to have been compromised, record the incident as usual;
see "Rescinding an incident" for how to withdraw it once that is established.

#### Spam definition

[Disruptive posting](https://chairs.ietf.org/mailing-lists/disruptive-posting) identifies two types:

- Messages unrelated to the IETF
- Advertising

It notes this is a non-exhaustive list. These procedures add:

- Messages with no indication that the sender is a real person
- Messages with no indication that the sender has an understanding of how the IETF works

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
arguing against an approved charter, reopening a consensus call without new information, or making
the same point in reply after reply so that other voices are drowned out.

Disagreement, however persistent, is not disruption. The test is whether the conduct adds to the
discussion, not whether the administrator agrees with it. Asking the chairs to revisit a decision
with new information, or appealing under [RFC2026](https://www.rfc-editor.org/rfc/rfc2026.html#section-6.5),
is never disruption.

Unless the conduct is egregious, first ask the participant to stop; it is an incident if it continues.

In the private message, additionally identify the specific conduct, and say that it is the conduct
being addressed, not their technical position.

### Handling messages containing confidential information

Report the message to support@ietf.org.

This is in addition to, not instead of, handling the incident under the procedure above.

### Handling repeated inclusion of derivative rights notices

Outside of an internet-draft, [IESG Statement on Clarifying Derivative Works Rights](https://datatracker.ietf.org/doc/statement-iesg-statement-on-clarifying-derivative-works-rights/)
says that notices that claim that derivative rights are being withheld for a Contribution are not conformant to IETF policies.
Repeated inclusion of such notices is a disruption.

In the private message, additionally:
- Refer to the [IESG Statement on Clarifying Derivative Works Rights](https://datatracker.ietf.org/doc/statement-iesg-statement-on-clarifying-derivative-works-rights/)
- Advise why this notice is not conformant to IETF policies
- Say that messages without the notice will be allowed through to the list in a timely manner

### Handling slop

"Slop" is voluminous, low-quality content that does not appear to have been checked by someone knowledgeable in the field. Slop can be uncivil, spam, or unrelated to the list's
purpose, in which case it can be handled in accordance with the procedures above. Slop is often the product of AI, though administrators are not expected to determine if the content
was written by a human. There might be a nugget of a good point in hundreds of words, or it could be complete nonsense.

Administrators should assess if a message is slop:
- Does it use hundreds of words to make a simple point, or no point at all?
- Is no one engaging meaningfully with the technical content of the message?

If an administrator judges that a message is slop, it counts as an incident.

## Handling messages held for moderation

Assess the message in a timely manner.

- If it is spam, follow the [spam procedure](#spam-procedure)
- If it is non-disruptive, allow it through
- If disruptive, reject with a reason as to why

Rejecting a held message is not by itself a new incident. If the held messages amount to a fresh
occasion of disruption, handle it under "Handling disruption" above.

If the volume of held messages is unmanageable, the hold may be converted to a ban for its remaining
duration - see "Choosing between a hold and a ban".

If the respondent is only sending non-disruptive messages:

- You have the option to temporarily remove hold for moderation.
- If disruption recurs, the hold may be reinstated without notice for the remainder of the sanction period.

## Removal of a sanction

On or before the end of the sanction period:

1. Remove the hold or ban by setting the list default action for the respondent
2. Send a private message to the respondent confirming the sanction is no longer in place, and referring to what the currently-approved procedure says will happen if there is a further incident

Removing a sanction does not remove the incident from the count. It continues to count for five
years from the date of the incident.

# Chat moderation

Moderation of Zulip chat has different procedures reflecting the synchronous nature of discussion.
However, a chat message violates policy if it would violate policy as an email to the list, and
vice versa.

The Sanctions Ladder does not apply to chat moderation.

An Administrator detects a message that violates policy. Spam and messages containing confidential
information should immediately be deleted. Otherwise, the Administrator sends a public message to the
offender indicating that further lapses will be moderated.

On a second offense in the same session, the message is deleted and the user is blocked from
participation it the chat for the remainder of the session.

# Open questions

1. How do chairs delegate administration responsibility, and how do we track that?
2. How do we identify the administrators of [non-WG lists](https://datatracker.ietf.org/list/nonwg)?
