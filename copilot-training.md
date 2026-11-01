---
title: "Does GitHub Copilot train on your code? Free, Pro, Pro+ and Max may, unless you opt out; Business and Enterprise don't"
description: "GitHub's docs say Copilot Free, Pro, Pro+ and Max interaction data may be used to train AI models unless you opt out, and Business and Enterprise customer data is not used. The pages do not all name Max. Checked 2 November 2026."
date: 2026-10-04
last_modified_at: 2026-11-02
seo:
  type: Article
---

# Does GitHub Copilot train on your code? Free, Pro, Pro+ and Max may, unless you opt out; Business and Enterprise don't

GitHub's docs say that starting 24 April 2026, Copilot Free, Pro, Pro+ and Max interaction data may be used to train AI models, and that you can opt out. They say "GitHub does not use Copilot Business or Copilot Enterprise customer data to train AI models." The pages do not all name Max, so this note still does not state one training rule for every plan.

Last checked: 2 November 2026. Every page below was re-read that day except [GitHub's generative AI services terms](https://github.com/customer-terms/github-generative-ai-services-terms), which did not load (HTTP 500).

Updated 2 November 2026: rewritten to lead with the answer, with the docs quoted word for word. The github.com/features/copilot and /plans FAQs no longer carry the answer "No. GitHub does not use either Copilot Business or Enterprise data to train its models." (present on 14 October 2026). They now describe Business and Enterprise data use under GitHub's Data Protection Agreement. This note now says so.

## Short answer

- **Free, Pro, Pro+, Max:** "Starting on April 24, 2026, if you have a Copilot Free, Copilot Pro, Copilot Pro+, or Copilot Max plan, GitHub may use your interactions with GitHub features and services—including inputs, outputs, code snippets, and associated context—to train and improve AI models." and "You can opt-out from allowing your data to be used for training in your personal settings for GitHub Copilot." ([Managing Copilot policies](https://docs.github.com/en/copilot/how-tos/manage-your-account/manage-policies))
- **Business, Enterprise:** "GitHub does not use Copilot Business or Copilot Enterprise customer data to train AI models. Copilot Business and Copilot Enterprise customers' data is protected under GitHub's Data Protection Agreement, which prohibits such use without customer authorization." (same page)
- **Where to opt out:** the same page names the setting "Allow GitHub to use my data for AI model training", and says it is not displayed for Business or Enterprise licenses.

## What the pages agree on, still not as one rule for every plan

[https://docs.github.com/en/copilot/how-tos/manage-your-account/manage-policies](https://docs.github.com/en/copilot/how-tos/manage-your-account/manage-policies) says that starting 24 April 2026, Free, Pro, Pro+, and Max may have inputs, outputs, code snippets, and context used to train, with an opt-out. It also says GitHub does not use Business or Enterprise customer data to train, because the Data Protection Agreement prohibits that without customer authorization. The opt-out control is not shown for Business or Enterprise.

[https://docs.github.com/en/copilot/reference/ai-models/model-hosting](https://docs.github.com/en/copilot/reference/ai-models/model-hosting) (also [https://docs.github.com/en/enterprise-cloud@latest/copilot/reference/ai-models/model-hosting](https://docs.github.com/en/enterprise-cloud@latest/copilot/reference/ai-models/model-hosting)) says GitHub may use individual subscribers' prompts, suggestions, and code snippets to train, with an opt-out, and does not use Business or Enterprise customer data to train. That sentence is printed under Microsoft models and again under Moonshot, not as a page-wide header.

## Open conflicts

Max is named in those two docs sentences. Max is not named in the 24 April 2026 change on these pages:

- [https://github.com/features/copilot](https://github.com/features/copilot) is a product FAQ, not docs.github.com.
- [https://github.com/features/copilot/plans](https://github.com/features/copilot/plans) is a product FAQ, not docs.github.com.
- [https://github.blog/news-insights/company-news/updates-to-github-copilot-interaction-data-usage-policy/](https://github.blog/news-insights/company-news/updates-to-github-copilot-interaction-data-usage-policy/) is dated 25 March 2026 and names Free, Pro, and Pro+ only.
- [https://github.blog/changelog/2026-03-25-updates-to-our-privacy-statement-and-terms-of-service-how-we-use-your-data/](https://github.blog/changelog/2026-03-25-updates-to-our-privacy-statement-and-terms-of-service-how-we-use-your-data/) applies to Free, Pro, and Pro+, and says the list may expand, but does not say Max has been added.

For Business and Enterprise, the product FAQ on [https://github.com/features/copilot](https://github.com/features/copilot) and [https://github.com/features/copilot/plans](https://github.com/features/copilot/plans) answered "No. GitHub does not use either Copilot Business or Enterprise data to train its models." when read on 14 October 2026. That answer is gone as of 2 November 2026. The FAQ now asks "How does GitHub use the Copilot data from Business and Enterprise Subscribers?" and lists operational uses under GitHub's Data Protection Agreement. Its training sentence is under "Individual (Free/Pro/Pro+) Subscribers" only, and that heading does not name Max. Those pages are a product FAQ, not docs.github.com. The docs say "without customer authorization." [https://github.com/customer-terms/github-generative-ai-services-terms](https://github.com/customer-terms/github-generative-ai-services-terms) (March 2026) says GitHub will not use Inputs or Outputs to train generative AI models unless given documented instructions, but section 1.A limits that document to volume-licensing purchases and does not name Copilot Business or Enterprise.

The hosting page does not say GitHub's training use of individual subscribers' prompts is separate from a provider's do-not-train promise. This note does not infer that. Provider lines on that page (OpenAI, Amazon Bedrock, Anthropic, Google, Gemini, xAI, Fireworks) stay labeled as provider commitments, and they are silent on which Copilot plan.

This note does not recommend a plan.

## Related notes

- [What do the listed AI plans cost?](prices.md)
- [Does ChatGPT train on your chats? On by default for Free, Plus and Pro; off by default for Business](chatgpt-training-default.md)
- [Cursor Privacy Mode: what it does, how to turn it on, and the default by plan](cursor-privacy-mode.md)
