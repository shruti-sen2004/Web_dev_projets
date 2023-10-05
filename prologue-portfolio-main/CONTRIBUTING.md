# PULL/MERGE REQUEST DETAILS
# HERE’S HOW WE VALIDATE CONTRIBUTOR PULL/MERGE REQUESTS (“PR/MRS”) FOR HACKTOBERFEST

## [ OUT-OF-BOUNDS ]

YOUR PR/MRS MUST BE WITHIN THE BOUNDS OF HACKTOBERFEST.
Your PR/MRs must be created between October 1 and October 31 (in any time zone, UTC-12 thru UTC+14).

Your PR/MRs must be made to a public, unarchived repository.

## [ EXCLUDED ]

REPOS THAT GO AGAINST HACKTOBERFEST’S VALUES WILL BE EXCLUDED FROM QUALIFICATION AND PR/MRS MADE TO THOSE REPOS WON’T COUNT.
Found a repository that goes against the values of Hacktoberfest? LET US KNOW AND WE’LL TAKE A LOOK.

## [ SPAM ]

YOUR PR/MRS MUST NOT BE SPAMMY.
PR/MRs that are labeled with a label containing the word “spam” by maintainers will not be counted.

We use the Node.js 16 RegEx engine with /\bspam\b/i to look for spam labels.

PR/MRs that also have the “hacktoberfest-accepted” label cannot be marked as spammy via a label.

PR/MRs that have been merged and do not have a label containing the word “invalid” cannot be marked as spammy via a label.

PR/MRs that our system detects as spammy will also not be counted.

Any user with two or more spammy PR/MRs will be disqualified.

## [ PARTICIPATING ]

YOUR PR/MRS MUST BE IN A REPO TAGGED WITH THE “HACKTOBERFEST” TOPIC, OR BE LABELED “HACKTOBERFEST-ACCEPTED.”
Hacktoberfest is now opt-in for maintainers, so only contribute to projects that indicate they’re looking for Hacktoberfest PR/MRs.

Once your PR/MR has passed this check, we won’t check this again (unless your PR/MR fails a check before this, such as it being marked as spammy).

## [ INVALID ]

YOUR PR/MRS MUST NOT BE LABELED AS “INVALID”.
PR/MRs that have a label containing the word “invalid” won’t be counted, unless they also have the “hacktoberfest-accepted” label.

Specifically, we use the Node.js 16 RegEx engine with /\binvalid\b/i to look for invalid labels.

## [ ACCEPTED ]

YOUR PR/MRS MUST BE MERGED, HAVE THE “HACKTOBERFEST-ACCEPTED” LABEL, OR HAVE AN OVERALL APPROVING REVIEW.
Your PR/MR must not be a draft to be considered accepted.

If your PR/MR is being accepted for Hacktoberfest via an overall approving review it must also not be closed.

ONCE YOUR PR/MRS PASS ALL THE CHECKS ABOVE, IT WILL BE ACCEPTED FOR HACKTOBERFEST AFTER THE 7-DAY REVIEW PERIOD.
We continually evaluate all of the checks except the [PARTICIPATING] check. If it fails any of these checks during this time, the 7-day timer will reset.
