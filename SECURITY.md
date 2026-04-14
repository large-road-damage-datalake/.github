# Security Policy

## Scope
This policy applies to GitHub repositories under the **`large-road-damage-datalake`** organization, including automation, repository configuration, and release assets that could affect the integrity of published dataset information.

## How to report a vulnerability
Please report security issues privately.

### Option A — GitHub (preferred)
1. Open the affected repository on GitHub.
2. Go to **Security**.
3. Use **Report a vulnerability** and follow the form.

### Option B — Email
Send an email to the security contact listed on the GitHub organization profile: contact@rauffatali.com.

Include:
- Summary of the issue and suspected impact
- Steps to reproduce or a proof-of-concept
- Affected repository name(s) and any specific workflow/file hints you can share

## Guidelines for researchers
- Do not publicly disclose the issue before coordination.
- Avoid privacy violations, data destruction, and service disruption.
- Do not access data beyond what is necessary to demonstrate the issue.

## Our response approach
- We will acknowledge receipt within **7 calendar days**.
- We may request additional details to reproduce and scope the issue.
- We will work toward a fix and coordinate disclosure when appropriate.

## Safe harbor
We consider good-faith security research that follows this policy to be authorized, within reasonable bounds and without harm to users, data, or service availability.

## Hardening expectations for maintainers and contributors
- Use least-privilege tokens and rotate any credential that may be exposed.
- Store secrets in GitHub Actions secrets, not in the repository.
- Pin third-party GitHub Actions to immutable references when practical.

## Non-goals
This channel is not for general dataset questions, website feature requests, or data licensing disputes—please use Discussions or Issues for those topics.
