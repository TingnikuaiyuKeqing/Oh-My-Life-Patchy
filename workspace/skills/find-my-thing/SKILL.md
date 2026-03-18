---
name: find-my-thing
description: Help users locate missing everyday items by narrowing the highest-probability locations and giving an efficient search path. Use when the user cannot find keys, earbuds, chargers, cards, documents, or similar small items and wants a calm, ordered search instead of random panic-searching.
---

# Find My Thing

Search smarter, not wider.

## Goal

Shrink the search path. Do not just comfort the user—help them check the most likely places first.

## Use this for

- Missing earbuds, keys, cards, chargers, or small daily objects
- Feeling sure the item is nearby but not remembering where
- Panic-searching before going out
- Wanting a more efficient search order

## Do not use this for

- Theft or security investigations
- Formal response to high-value loss
- Cases needing trackers, surveillance, or police involvement

## Expected input

The user may provide:
- what is missing
- when it was last seen
- where they recently went
- where it is usually placed
- any unusual actions today
- how urgent the situation is

If details are missing, still start from the most likely path first.

## Output

Default structure:
1. One-line judgment: what kind of life-friction search this is
2. Ranked likely locations
3. Memory-trigger questions
4. Fastest search order

Useful outputs:
- where to check first
- where to check next
- which places are not worth searching yet
- whether to reconstruct the timeline

## Writing rules

- Keep it short
- Stay calm
- Sound like practical troubleshooting
- Do not increase panic
- Do not encourage random repeated searching

## Priorities

1. Check high-probability locations first
2. Reconstruct from the last-use path
3. If urgent, prioritize the fastest route
4. If not urgent, include memory-trigger questions
5. Keep the list to about 3 to 5 steps

## Response pattern

Prefer this order:
- 识别：这是什么类型的生活摩擦
- 高概率位置：先查哪几个地方
- 补丁：最省时间的查找顺序
- 回忆触发：如果还没找到，再问哪几个问题

## Success standard

Success means:
- the search area narrows quickly
- the order is clearly more efficient
- the user stays calmer
- random chaotic searching is reduced
