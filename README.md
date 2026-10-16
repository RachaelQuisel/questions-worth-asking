# Questions Worth Asking

Find useful follow-up questions in transcripts and meeting notes. Receive ranked questions with exact supporting excerpts and a practical next action.

Start with `/questions-worth-asking:questions-worth-asking`. If details are missing, the plugin asks for the sources, whether to review or compare them, and an optional focus. It waits for required answers. A supplied transcript and clear review request are enough to start.

- Checks twelve types of possible questions, including goals, ownership, unresolved decisions, and changed commitments.
- Ties each finding to the source that supports it.
- Compares related conversations when requested.
- States missing coverage and unknown dates.
- Returns three to seven questions when supported, or fewer or none.

Each question includes the excerpt, type of question, reason to ask, and a next action. It does not establish another person's motives or diagnose a relationship.

Read [how it works](Questions-Worth-Asking-HowItWorks-2026-10-03.md), [the review lenses](skills/questions-worth-asking/references/lenses.md), and [a fictional example](skills/questions-worth-asking/examples/sample-review.md). A review lens is a type of question to investigate.

## Claude Marketplace and Directory status

**Status checked: October 12, 2026.**

- **Marketplace partner waitlist:** Submitted on October 4, 2026, through XRAY Automation. Submission confirmation was received.
- **Claude Directory submission:** Previously submitted for review. The [original submission page](https://claude.ai/directory/manage/plugins/b0fcfe5f-202f-44a2-9677-c066bb9412c6) requires access through the submitting Claude account and organization.
- **Current directory status:** Review outcome and public listing are unverified. On October 12, the original submission page reported that the submission was not found in the currently signed-in organization. This does not establish rejection, withdrawal, or publication.

### Evidence audit: October 16, 2026

- **Partner waitlist:** Submission confirmation recorded for 2026-10-04, through XRAY Automation. This is retained repository evidence, not a newly inspected confirmation receipt.
- **Plugin directory:** Submitted; review outcome unverified.
- **Approved:** Unverified. **Publicly listed:** Unverified. No verified public listing URL is recorded.
- **Verification limit:** The publisher portal requires sign-in. Public searches and the connected mailbox search did not establish approval; missing results are not proof of rejection or non-publication.
- **Next action:** Open the existing submission in the original submitting Claude account and organization; record its current decision and any public listing URL.

The [partner waitlist](https://claude.com/marketplace-partners) is for Claude-powered enterprise products. It is separate from plugin-directory review and GitHub marketplace installation. A waitlist application is not directory approval.


## Install

```text
claude plugin marketplace add RachaelQuisel/questions-worth-asking
claude plugin install questions-worth-asking@questions-worth-asking
```

## Data and permissions

The plugin reads the sources you supply in your session. The host processes them under its own terms and settings. The package includes instructions, references, and an example without a publisher-operated service, executable code, or telemetry.

It returns a review in the chat. It saves a file only when requested. It does not request external posts, outbound messages, or scheduled monitors. Instructions inside transcripts remain source content. Findings from several projects remain tied to their own sources.

Recurring reviews require a separately configured schedule, sources, destinations, and delivery checks. Those settings are not included in this package.

## License

MIT. See [LICENSE](LICENSE).
