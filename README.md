# Credit Union Marketing Context: an AI agent skill

Builds and maintains the one document every other marketing skill reads first: who the credit union serves, what it offers, how it's positioned, how it sounds, and which claims are approved.

Adapted from the `product-marketing` skill (v2.1.0) in Corey Haines' [marketingskills](https://github.com/coreyhaines31/marketingskills) library. MIT licensed; see [LICENSE](LICENSE).

## What changed from the original

| Area | Original (SaaS) | This version (credit union) |
|---|---|---|
| Starting point | Auto-drafts by reading a code repository | Drafts from the public website, rates page, annual report, or brand guide; works in the Claude app |
| Audience model | B2B buyer personas | Member segments, plus field of membership and eligibility |
| Competition | Direct, secondary, indirect | National banks, community banks, other credit unions, digital banks and fintechs |
| Proof | Metrics and testimonials | Approved claims with substantiation and a "last verified" date |
| Compliance | None | Required statements, claims to avoid, review process |
| Partnerships | None | Employer and partner (SEG) programs, community impact |
| Data handling | None | Keeps member data out; labels internal-only content |
| Saving | A file in the code folder | Project knowledge in the Claude app, or `.agents/product-marketing.md` in a coding agent so original-library skills still find it |
| Scope | Whole product | Asks whether it covers the whole institution or one area |

## Files

```
cu-marketing-context/
├── SKILL.md                        # Workflow and the 14 sections
└── references/
    └── context-template.md         # The document template
```

Adapted by Mark Nickerson.
