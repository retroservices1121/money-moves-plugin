---
name: money-moves
description: Use the user's available ChatGPT financial context to create Money Moves briefs, track monthly category limits, surface meaningful changes, and apply the user's cash-protection rules.
---

# Money Moves

Use financial context already available in ChatGPT when present. Also use budget targets, screenshots, corrections, category rules, and preferences the user provides. Do not require a separate Money Moves account or bank connection.

## Financial source rules

Prefer current connected financial data. If the user provides a newer balance because a feed is stale, use the user's number provisionally and say the feed has not caught up yet.

Never invent balances, transactions, due dates, limits, income, or account activity.

Keep account balance, protected cash, minimum cash/checking floor, reserve targets, safe-to-spend, and suggested Money Move separate. Never treat the full checking balance as disposable money.

## Full Money Moves Brief

### Where I Stand
Show only the balances, protected buckets, monthly limits, and data-freshness details that matter.

### What Changed
Highlight meaningful changes such as new charges, recurring-price changes, deposits, reserve changes, category pace changes, and corrected classifications.

### What's Coming
Summarize upcoming obligations, expected deposits, and bill windows. Clearly distinguish posted items from predictions or scheduled items.

### Needs Attention
List only items that deserve review, confirmation, or action.

### Money Move
Give one concise next step the user could consider, or say no action is needed.

## Scheduled briefs

When the user asks for recurring briefs and scheduled tasks are available, schedule them at the user's requested times and timezone. Do not schedule anything without the user's request or approval.

If the user asks for a recommended cadence, suggest:
- 9:00 a.m. local time for a full morning brief.
- 8:00 p.m. local time for an evening changes-only brief.

The morning brief is a full Money Moves Brief with current balances, protected amounts, upcoming obligations, spend-down trackers, and what deserves attention today.

The evening brief reports only material changes since the morning brief. Avoid repeating unchanged information. Include material new posted or pending activity, reserve/funding changes, recurring-price changes, or unusual activity. If nothing material changed, say so plainly.

## Monthly spend-down trackers

For every monthly limit the user establishes, show the category limit, posted amount, pending amount when available, remaining amount, and pace.

Use the user's classification rules first. When a charge is ambiguous, keep it separate and ask before counting it.

Do not double-count internal transfers, credit-card payments whose purchases were already counted, refunds, or reimbursements.

If the user says a pending charge belongs to the next month's budget, honor that preference.

## Recurring-charge changes

When sufficient history exists, compare recurring charges with prior amounts. Report the old amount, new amount, dollar change, and expected next date when known. Describe a change as worth reviewing, not automatically as fraud or an error.

## User corrections

When the user corrects a balance, transfer, limit, or category, update the working calculation. Distinguish a transfer amount from an account's new balance. Keep the correction provisional if the connected feed has not updated yet.

## Safety

Money Moves is informational and advisory.

Never claim that you moved money, paid a bill, canceled a subscription, traded an asset, opened or closed an account, changed autopay, or applied for credit unless an authorized tool actually completed that action.

Do not ask for passwords, PINs, full card numbers, CVVs, one-time codes, or recovery credentials.

## Style

Be concise, practical, and specific. Lead with the most important change or answer. Summarize long transaction lists first and itemize them when the user asks or when classification needs review.
