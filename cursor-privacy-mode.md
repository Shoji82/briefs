---
title: "Cursor Privacy Mode: what it does, how to turn it on, and the default by plan"
description: "Cursor says Privacy Mode means your code is never used for training. Its help page says it is on by default for teams and for Enterprise teams, and other Cursor pages do not say the Teams plan starts on. Steps and sources, checked 2 November 2026."
date: 2026-10-04
last_modified_at: 2026-11-02
seo:
  type: Article
---

# Cursor Privacy Mode: what it does, how to turn it on, and the default by plan

Cursor says "Privacy Mode ensures your code is never used for training by Cursor or other AI model providers." You turn it on in Cursor Settings, under General. Cursor's help page says "For teams, Privacy Mode is enabled by default for all team members," and also that it "is on by default for Enterprise teams." Cursor's other pages do not say the Teams plan starts on, so this note does not state one default for Teams.

Last checked: 2 November 2026. Every Cursor page below was re-read that day.

Updated 2 November 2026: rewritten to lead with the answer. Added a short answer, a plan-by-plan table, Cursor's steps to turn Privacy Mode on, and an exceptions list. Cursor's pricing now names Free, Plus, Premium, Super and Ultra (was Hobby, Pro, Pro+ and Ultra). Its privacy policy now shows "Last updated October 11, 2026" (was 29 September 2026). cursor.com/terms now shows Cursor's "404: This page could not be found." page, served with HTTP status 200. The default findings are unchanged.

## Short answer

- **What it does:** "Privacy Mode ensures your code is never used for training by Cursor or other AI model providers." ([Cursor help: Privacy and data](https://cursor.com/help/security-and-privacy/privacy))
- **Teams:** "For teams, Privacy Mode is enabled by default for all team members." (same page)
- **Enterprise:** "Privacy Mode is on by default for Enterprise teams." (same page)
- **Individual plans:** no Cursor page we read says whether it starts on or off. [cursor.com/docs/enterprise](https://cursor.com/docs/enterprise) labels it "User choice" for individual plans.

## Plan by plan

| Plan | What the page says | Page (date it shows) | Checked |
|---|---|---|---|
| Individual plans | "User choice" | [cursor.com/docs/enterprise](https://cursor.com/docs/enterprise) (no date shown) | 2 November 2026 |
| Anyone | "Privacy Mode is available to anyone (free or Pro)." | [cursor.com/security](https://cursor.com/security) (Last updated August 25, 2026) | 2 November 2026 |
| Teams | "For teams, Privacy Mode is enabled by default for all team members." | [Cursor help: Privacy and data](https://cursor.com/help/security-and-privacy/privacy) (no date shown) | 2 November 2026 |
| Teams | "Enforce org-wide" | [cursor.com/docs/enterprise](https://cursor.com/docs/enterprise) (no date shown) | 2 November 2026 |
| Teams | "New team members inherit the team's Privacy Mode settings." | [cursor.com/security](https://cursor.com/security) (Last updated August 25, 2026) | 2 November 2026 |
| Enterprise | "Privacy Mode is on by default for Enterprise teams." | [Cursor help: Privacy and data](https://cursor.com/help/security-and-privacy/privacy) and [privacy and data governance](https://cursor.com/docs/enterprise/privacy-and-data-governance) (no dates shown) | 2 November 2026 |
| Enterprise | "on by default for Enterprise" | [security hardening](https://cursor.com/docs/enterprise/security-hardening) (no date shown) | 2 November 2026 |

## How to turn it on

Cursor's steps, from [Cursor help: Privacy and data](https://cursor.com/help/security-and-privacy/privacy):

1. Open Cursor Settings: Cmd + Shift + J on Mac, or Ctrl + Shift + J on Windows and Linux.
2. "Click General in the sidebar"
3. "Toggle Privacy Mode on"

The same page says: "Admins can enforce it organization-wide via cursor.com/dashboard so members cannot disable it."

## When Privacy Mode is off

[cursor.com/data-use](https://cursor.com/data-use) (Last updated September 3, 2026): "If you choose to turn off "Privacy Mode": we may use and store codebase data, prompts, editor actions, code snippets, and other code data and actions to improve our AI features and train our models." That page does not say whether it starts on, and it does not name a plan.

## Exceptions

- **Your own API keys:** "ZDR doesn't apply when you use your own API keys. In that case, your data handling follows your provider's privacy policy." ([Cursor help](https://cursor.com/help/security-and-privacy/privacy))
- **Models with provider retention:** "Some models also require data retention with their provider and fall outside Cursor's ZDR agreements. These models are off by default and require admin approval before use." (same page) Cursor's [privacy and data governance](https://cursor.com/docs/enterprise/privacy-and-data-governance) page names Claude Fable 5 and Claude Fable 5.1, and says "Anthropic stores their inputs and outputs to run automatic and human harm-prevention reviews. This data is not used for training or product improvement."
- **Prompts still go to providers:** "When you use AI features, Cursor sends prompts and code context to model providers like OpenAI, Anthropic, and Google. With Privacy Mode enabled, your code is not used for training." ([Cursor help](https://cursor.com/help/security-and-privacy/privacy))

A personal account might not have Privacy Mode enabled. That is not a sentence that individual plans are off by default.

## Open conflicts

On [Cursor help: Privacy and data](https://cursor.com/help/security-and-privacy/privacy), one sentence says: "For teams, Privacy Mode is enabled by default for all team members." Later on the same page it says "Privacy Mode is on by default for Enterprise teams. Teams and Enterprise admins can enforce it organization-wide so members cannot disable it." That second passage does not say the Teams plan is on by default. This note does not pick a winner.

These pages say Privacy Mode can be enabled or enforced, and they are silent on the Teams default: [cursor.com/security](https://cursor.com/security), [cursor.com/pricing](https://cursor.com/pricing), [cursor.com/docs/account/teams/pricing](https://cursor.com/docs/account/teams/pricing), and [cursor.com/docs/account/teams/dashboard](https://cursor.com/docs/account/teams/dashboard). Pricing names Free, Plus, Premium, Super, and Ultra, but it does not say whether Privacy Mode is on for them.

## Policy pages

- [cursor.com/privacy](https://cursor.com/privacy) (Last updated October 11, 2026): "We do not use Inputs or Suggestions to train our models, or permit third parties to use them for training, unless: (1) they are flagged for security review ..., (2) you explicitly report them to us (for example, as Feedback), or (3) you've explicitly agreed to their use for such training purposes." It does not apply where Cursor processes data for a commercial customer, "for example, if your employer has provisioned a Cursor account for you to use at work." The page does not name Privacy Mode or a plan.
- [cursor.com/terms-of-service](https://cursor.com/terms-of-service) (Last updated September 3, 2026): "ANYSPHERE WILL NOT USE CONTENT TO TRAIN, OR ALLOW ANY THIRD PARTY TO TRAIN, ANY AI MODELS, UNLESS YOU'VE EXPLICITLY AGREED TO THE USE OF CONTENT FOR TRAINING." It does not mention Privacy Mode.
- [cursor.com/terms](https://cursor.com/terms) shows Cursor's "404: This page could not be found." page.

This note does not recommend a plan.

## Related notes

- [What do the listed AI plans cost?](prices.md)
- [Does GitHub Copilot train on your code? Free, Pro, Pro+ and Max may, unless you opt out; Business and Enterprise don't](copilot-training.md)
- [Does Claude Pro or Max train on your chats? Yes, if the setting is on](claude-pro-max-training.md)
