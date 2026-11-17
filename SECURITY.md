# Security policy

**Don't open a public issue for a security vulnerability.** Report it privately so I can fix it before anyone can exploit it.

## Supported versions

Security fixes ship in the latest release. Update to the newest version before you report, and check whether the problem still happens there.

## Report a vulnerability

Use GitHub's private vulnerability reporting:

1. Open the repository's **Security** tab.
2. Select **Report a vulnerability**.
3. Fill in the form. Only you and I can see the report and the discussion that follows.

For a plugin listed on WordPress.org, you can also use the [WordPress plugin security reporting process](https://developer.wordpress.org/plugins/wordpress-org/plugin-security/).

Include:

- what the vulnerability is and what an attacker could do with it;
- the steps to reproduce it;
- the affected versions;
- whether an attacker needs to be logged in, and with which role.

## Response times

- Acknowledgement within 48 hours.
- First assessment within 1 week.
- A fix as soon as practical, usually within 2 weeks for critical issues.

## Disclosure

I follow coordinated disclosure. Please give me time to ship a fix before you publish: 90 days for medium-severity issues, less for issues already being exploited. I'll credit you in the release notes unless you'd rather I didn't.

## Out of scope

- Problems in WordPress core, other plugins, or themes. Report those to their own maintainers.
- Attacks that require administrator access.
- Self-XSS, where a victim must paste attacker code into their own browser console.

A repository's own `SECURITY.md` may list more surfaces that are in or out of scope.
