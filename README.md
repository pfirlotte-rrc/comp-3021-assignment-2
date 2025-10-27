# comp-3021-assignment-2

Unfortunately Only bandit appears to catch any errors, Super-Lint does not provide any feedback.
It also appears to only have caught issues with the python file and not the Typescript file.

## Do these results match what you found in your previous peer review?

The Bandit results match slightly, the services caught the same Injection vectors but differed in a URL issues.
It is also missing at least 2 other errors outside of the possible injection/permission issues. 

## Do you think they caught all the vulnerabilities present in the code?

They did not, they only caught 3 errors pertaining to the code.
This may ber due to some security methods being standards for how processes or information may be handled or
treated that are not directly a code structure issue. This could be how certain variables or data should be setup.

## Why is using multiple code scanners better than using one?

It allows for much greater coverage as not all scanners may be perfect. They may also serve different purposes such
as having a different focus on certain vulnerabilities. They also may be better among some languages rather than others.
