# Adding to the roadmap

We submit roadmap proposals in the form of [Amazon-style PR-FAQs](https://coda.io/@colin-bryar/working-backwards-how-write-an-amazon-pr-faq). Anybody can submit a PR-FAQ. PR-FAQ can come from the exec team, or from any teammate. PR-FAQ are reviewed and prioritised by the VPEng/Prod with input from the exec team. PMs help build, refine and evaluate the impact of PR-FAQs.

## How to submit a PR-FAQ

Full details on how to write a PRFAQ can be found [here](prfaq-process.md).

1. **Write a PR-FAQ to describe your proposal**.

- PR-FAQ are a recommended format, but you should feel free to use the most appropriate format for the project as long as it's concise and has a [Success Criteria](#success-criteria)
- You can use this [template](https://docs.google.com/document/d/1Stwe26NWoh0r_LOeA3sUqwDZlrmZ2qBEcdV0Sd1KP1o/edit#).
- All PR-FAQs are stored in the [PR-FAQ folder](https://drive.google.com/drive/folders/1cOXPKDIQ3O3ZEq9oP6WZBTizgwnoZI9l).
- If you need help putting your PR-FAQ together, post in #product to request help from a PM.

2. **Get a PM review**. Raise a [PR-FAQ issue](https://github.com/sourcegraph/pr-faqs/issues/new/choose), linking to your proposal. This will trigger an [alert](https://zapier.com/editor/175816594/published/175816595/sample) in #product and #engineering. Steve will assign a PM (or self-assign for non-customer facing/platform proposals) the issue to:
   1. Give a pre-read to the PR-FAQ and give (non-blocking) feedback
   2. Determine the impact of the proposal (no more than 2 weeks of early validation)
   3. Set a Success Criteria for the project
3. **Steve will prioritise proposals.** Quarterly, Steve and the exec team will review proposals, with input from PMs (for features) and EMs(for tech-only) to decide what to move to the roadmap.
4. **Job fair.** Once a project is moved to the roadmap, Steve will add them to the [job fair](./job-fair.md)

## Success Criteria

A good success criteria should include:

- a leading indicator of success that can be measured in less than 3 months
- lagging indicators of success, such as customer adoption that typically takes longer to see

## PM review

PMs (or Steve for non-customer facing/platform proposals) are in charge of reviewing PR-FAQs. This is non-blocking and just a way to ensure there's a high standard for PR-FAQ and that the exec team can focus on reviewing the most impactful proposals first in case there are too many of them.

We don't use a formal/complicated framework for evaluating impact for now, in order to keep things lightweight. We might someday introduce a more complicated [opportunity canvas](https://docs.google.com/document/d/1pTEMcwH10xWilQEnVc65oC6PdC3VMjn2XoARfNTaHkc/edit#) later on.

That said, here’s a rough guideline for evaluating impact of customer-facing features:

- **High**: Large ARR (>$5M ARR) or DAU (> 500 DAUs) impact, in the next 12 months. Fit with strategy. Well validated. Differentiated feature. Eg. a project like Batch Changes, Insights, Own, or adding support for a broadly-used codehost.
- **Medium**: Large ARR (>$1M ARR) or DAU (> 100 DAUs) impact, in the next 12 months. Fit with strategy. Elements of validation.
- **Low**: Unknown or unvalidated impact. No clear fit with strategy.
