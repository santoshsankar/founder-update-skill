# Founder Monthly Update

A Claude Skill that helps you draft your monthly (or quarterly, post–Series A) investor update — pulling real context from your email, Slack, and CRM instead of starting from a blank page every month.

## Install

Click the **Save skill** button on the `.skill` file card. That's it, if your workspace allows skill installs. If it doesn't, ask whoever manages your Claude workspace to enable custom skills.

## What it needs to actually be useful

This skill works with whatever you already have connected in Claude — it doesn't require all three, and it won't break if you're only using one:

- **Email** (Gmail or similar) — for customer signal and any commitments made to investors last time
- **Slack** — for product launches, blockers, and hiring/team news
- **CRM** — for deal movement (works with Attio, HubSpot, Salesforce, Pipedrive, or whatever you use)

No connections set up? It still works — it'll just ask you directly for the handful of things it can't pull automatically (mainly revenue, burn, cash, and your Asks and Major Goals, which need your judgment anyway, not a tool's).

## How to use it

Just ask, in plain language, something like:

> "Draft my monthly investor update."

Or, if it's your first time and you want more control:

> "Help me put together this month's investor update. Last one went out four weeks ago."

The skill will check what's connected, pull what it can, ask you for what it can't, and hand you back a draft organized as: **Asks, KPIs, Customers, Product, People, Capital, Major Goals, Shoutouts.**

## What to expect from the draft

It's a first pass, not a final version. Plan to rewrite the Asks and Major Goals yourself — those sections are supposed to reflect your own read on the business, not an inference from your inbox. Everything else should be close, but check the Customers and Product sections in particular for anything it missed or got wrong.

## Why this order

Asks come first because they're the easiest thing for a reader to skip past if they're buried at the bottom. Everything else follows the shape of how the business actually runs: the numbers, then customers, product, and people, then capital, then where you're headed next, then who helped get you there.

## Notes

- Nothing here is tuned to a specific investor's preferences. If you know a particular investor wants something different, just say so and adjust the draft.
- This doesn't send anything on its own. It only drafts. You still decide when and to whom it goes out.
