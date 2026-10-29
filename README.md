# Credit Union Marketing Skills for AI Agents

11 free, open-source AI skills for credit union marketers. They know that you have members, not customers, that every rate claim needs backup, and that every campaign goes through compliance.

They work in Claude and in any AI agent that supports Agent Skills. Adapted from Corey Haines' [marketingskills](https://github.com/coreyhaines31/marketingskills) library, which was built for SaaS, and rebuilt for credit unions and community financial institutions.

## The skills

### Start here

| Skill | What it does |
|---|---|
| **cu-marketing-context** | Builds the one document every other skill reads first: who you serve, field of membership, products, positioning, voice and approved claims. Run this first. |

### Plan and decide

| Skill | What it does |
|---|---|
| **cu-marketing-plan** | Builds a marketing plan tied to deposit and loan goals: current-state audit, member lifecycle strategy, budget, 90-day roadmap and 12-month outlook. |
| **cu-marketing-ideas** | Brainstorms and prioritizes from 116 credit union tactics (acquisition, deposits, lending, partners, community, retention, brand), tagged by goal, cost, effort and compliance risk. |
| **cu-marketing-council** | Pressure-tests a decision with a simulated council: well-known marketing thinkers plus a compliance officer, CFO, member experience lead, board member and fintech challenger. |

### Build campaigns

| Skill | What it does |
|---|---|
| **cu-lifecycle-emails** | Designs, writes or audits lifecycle emails: new member onboarding, product journeys, life events and partner programs, with compliance guardrails. |
| **cu-sms** | Plans and writes member texts: consent and opt-out, keeping marketing separate from fraud alerts, and designs that don't look like smishing. |
| **cu-member-referrals** | Designs member-get-member referral programs: eligibility, rewards and bonus disclosures, fraud controls, messaging and measurement. |
| **cu-member-retention** | Spots weakening relationships early (stopped direct deposit, maturing certificates, paid-off loans) and plans outreach, exit surveys and win-back. |
| **cu-partner-programs** | Plans, pitches, runs and measures partnerships: employer (SEG), association, school, dealer, community and fintech programs. |

### Review and measure

| Skill | What it does |
|---|---|
| **cu-compliance-review** | Pre-checks email, web, social, ads, SMS and print before it goes to compliance. Flags missing APY/APR, trigger terms, unsupported claims and phishing-like design, with fixes. |
| **cu-journey-measurement** | Proves what your programs changed: relationship-depth metrics, holdout tests, sample sizes, cohort reporting and a one-page results summary for leadership. |

## How to use them

**In the Claude app**
1. Download the `.zip` for the skill you want from this repo (click the file, then the download button).
2. In Claude, open **Settings**, find **Skills**, and upload the zip. Upload one skill at a time.
3. Start with `cu-marketing-context`, then ask Claude for what you need, such as "Build a 5-email onboarding journey for new members." Claude picks the right skill.

**In other AI agents**
Unzip each skill and put the folder wherever your agent loads skills (for example, `.claude/skills/` in Claude Code). The context skill can also save to `.agents/product-marketing.md` so skills from the original library still find it.

**A suggested order:** context → plan or ideas → build the campaign → compliance review → measurement.

## A note on compliance

`cu-compliance-review` is a pre-check, not a replacement for your compliance team. It catches common, fixable problems so your reviewer can focus on the judgment calls. Keep member data out of your prompts.

## Credits and license

Adapted from [coreyhaines31/marketingskills](https://github.com/coreyhaines31/marketingskills) (MIT). Credit union adaptation by Mark Nickerson. MIT licensed; see [LICENSE](LICENSE).

Questions, or want help setting these up at your credit union? [Connect with me on LinkedIn](https://www.linkedin.com/in/YOUR-PROFILE).
