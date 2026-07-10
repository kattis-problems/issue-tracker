# Kattis problem tracker

Issue tracker for the problems on Kattis. Each problem lives in its own
(private) repository in this organization — all bug reports and discussion
about problems happen here instead.

## Filing an issue

- Start the title with the problem's short name (the id in the problem URL):
  `different: time limit too tight for Python`
- If an issue spans a few problems, list the short names in the title:
  `different, otherproblem: inconsistent output format`. If they are too
  many, use a descriptive title without the prefix and list the affected
  short names (or describe the set) in the body.
- Search existing issues first.
- Everything is fair game: broken test data, unclear statements, too-tight
  limits, judging oddities, typos.

## What not to post

This tracker is public, but problem packages (secret test data, judge
solutions) are not — and other people still want to solve the problems.

- No secret test data, no judge solutions, no full solutions.
- Describe the failure without spoiling more than necessary: "my solution
  passes samples but gets WA on a case in the second secret group" is
  exactly enough.
- If your report can't avoid spoilers, say so in the issue and we'll
  handle the details privately.

## Want to fix it yourself?

Reports are welcome as-is. If you're also willing to implement the fix in
the problem package, say so in the issue and we'll follow up about next
steps.

## What happens next

We triage, the fix lands in the problem's repository, and the issue closes
when the fix merges.
