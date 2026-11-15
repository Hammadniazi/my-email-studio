# Skills I chose

Searched skills.sh on 15 Nov 2026 with: "email marketing", "email sequence", "campaign plan", "resend". Nothing installed yet.

## Use these

**1. For writing campaigns: `anthropics/knowledge-work-plugins`**
- Publisher: Anthropic, the company that makes Claude (official).
- GitHub stars: about 36,000. Apache-2.0 license. Updated this week.
- Skills to use: `campaign-plan` and `email-sequence` (both in the `marketing` folder).
- Why: it's an official publisher, lots of people have checked it, and it has both of the writing skills I need.
- Install later with: `npx skills add anthropics/knowledge-work-plugins@campaign-plan` (and `@email-sequence`)

**2. For sending email: `resend/resend-skills`**
- Publisher: Resend, the email sending service (official).
- GitHub stars: about 210. MIT license. Updated last week.
- Skills to use: `resend` (send email through the API). Optional: `email-best-practices` for deliverability rules.
- Why: the company behind the service wrote it, so it should match their real API. The star count is low because the repo is new and small. Their main `react-email` repo has about 20,000 stars, which shows Resend is an established company.
- Install later with: `npx skills add resend/resend-skills@resend`

Worth a look, but not first choice: `coreyhaines31/marketingskills` (about 60,000 stars, very popular). It's run by one person, not a company, so read the skill files before installing.

## Avoid these

**1. `mbfinotti/sales-skills` (for example `cold-email-deliverability`, `sales-outbound-sequence`)**
- Says about 33,000 installs, but the GitHub repo has only **3 stars** and was created in September 2026.
- That many installs with almost no stars doesn't add up. It suggests the install count has been inflated. The same publisher's `advertising-skills` repo shows the same pattern (about 26,000 installs, 2 stars).
- It's also aimed at cold outreach, which is a different job from marketing to people who signed up.

**2. `caffeinelabs/skills` (`extension-email-marketing`, `extension-email`)**
- Says about 31,700 installs, but the GitHub repo has only **2 stars** and 2 contributors.
- The same mismatch. Nobody has really reviewed it, and the publisher isn't someone I know.

## How I decided

Check these three things before installing any skill:

1. **Who publishes it?** Look for the official company (anthropics, resend) or a well-known maintainer. Click through to the GitHub owner. Don't trust the name alone, since anyone can call a repo "email-marketing".
2. **Do the numbers match?** Compare installs on skills.sh with GitHub stars, and check when the repo was created and last updated. A large install count with almost no stars, or a brand-new repo, is a red flag.
3. **What does it actually do?** Open the `SKILL.md` and any scripts on GitHub and read them. Look for commands it runs, places it sends data, and requests for API keys. Make sure it only does what it says, and check the license (MIT or Apache-2.0 is fine).
