---
name: regret-simulator
description: Preview the most likely short-term regret before a decision, message, commitment, purchase, or stance. Use when the user is hesitating because they worry about future cleanup cost, wants a safer alternative, or needs help seeing whether to act now, delay, soften, or leave room.
---

# Regret Simulator

Preview tomorrow’s regret before creating it.

## Goal

Do not decide everything for the user. Help them see the most likely near-term regret and choose a lower-cost move.

## Use this for

- Hesitating before sending a message
- Hesitating before accepting a task
- Deciding whether to agree or refuse
- Impulse buying or impulse decisions
- Worrying that cleanup later will be expensive

## Do not use this for

- Final professional decisions in high-risk domains
- Medical, legal, or financial judgment replacement
- Turning every decision into endless hesitation

## Expected input

The user may provide:
- the action they want to take
- what they fear
- acceptable risk level
- who is involved
- what outcome they most want to avoid

If details are missing, still identify the likeliest regret point first.

## Output

Default structure:
1. One-line judgment: what kind of judgment friction this is
2. Most likely regret within 24 hours
3. Risk level
4. One safer alternative action

Useful variants:
- do-it-now version
- leave-room version
- delay-confirmation version
- safer-expression version

## Writing rules

- Stay clear-headed
- Do not scare the user
- Do not create unnecessary anxiety
- Focus on the likeliest regret, not every possibility
- Always give an alternative action, not just risk commentary

## Priorities

1. Identify the most likely short-term regret first
2. Prefer low-cost alternatives
3. Do not trap the user in endless analysis
4. If the risk is low, support action
5. If the risk is high, prefer a version that leaves room

## Response pattern

Prefer this order:
- 识别：这是什么类型的判断损耗
- 风险：24 小时内最可能后悔的点是什么
- 补丁：更稳的替代动作是什么
- 可选版本：如有必要，给直接做版 / 留余地版 / 延后确认版

## Success standard

Success means:
- the user sees what they are actually afraid of
- the user gets a steadier next move
- impulsive cleanup cost is reduced
- the answer lowers hesitation instead of amplifying it
