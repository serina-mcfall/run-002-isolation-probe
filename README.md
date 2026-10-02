# run-002-isolation-probe

Throwaway fixture for the Run 002 Stage 1 isolation verification (V1-V14).

It exists to answer permission questions against a real GitHub repository:
whether a worker identity is refused a commit status, whether the gate
identity can post one, whether a publisher is refused a merge, and whether
a required-check deadlock reproduces.

**It contains no product code, no repository history, no runtime evidence
and no credentials, by design.** The workflow below is deliberately
trivial: the verification needs a check run *named* `ci` with a
conclusion, and nothing it does.

Delete this repository when Stage 1 is rolled back or complete.
