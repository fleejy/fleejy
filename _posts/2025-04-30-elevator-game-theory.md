---
title: "Elevator Game Theory"
date: 2025-04-30
categories:
  - blog
tags:
  - randomthoughts
classes: wide
excerpt: For Those Who Press "Up" When Bound for Down
mermaid: true
---

## Background
I've lived in high-rise buildings for most of my life. I've noticed that the residents of the buildings would often press the "up" button to intercept the elevator(s) when they intended to go down. This would create awkward encounters where their button to go to the ground floor gets cancelled as they arrived at the floors above them.

This reminded me of game theory and the prisoner's dilemma so I wanted to explore how it would work.

## Elevator as a Prisoner's Dilemma
- `Goal of each resident`: Get on the elevator as fast as possible to go down.

## Choices
Each person waiting on a high floor has two options:
- `Cooperate`: Press only the down button (intended choice)
- `Defect`: Also press the up button (trying to "hijack" the elevator earlier in its cycle)

## Payoff Matrix:

| | Others Cooperate (press only ↓) | Others Defect (press ↑ too) |
| --- | --- | --- |
| You Cooperate (press ↓) | 🚀 Best collective result<br>(efficient elevator cycle)<br>but you may wait longer if elevators skip you. | 🕗 You miss the elevator<br>that got hijacked going up;<br>longer wait. | 
| You Defect (press ↑) | ⏱ You intercept the elevator early,<br>possibly getting it to stop for<br>you on the way down. | 🔄 Everyone presses ↑,<br>elevator goes all the way up first,<br>then down — worse for all. |

## Why it's a Prisoner's Dilemma
- Rational self-interest encourages people to press both ↑ and ↓ to maximize chances of boarding.

- But when everyone defects, the system breaks: elevators go inefficient routes, increasing wait times for everyone.

- If everyone cooperated, elevators would follow efficient paths, but the fear of missing the elevator leads people to defect.

## Possible Solutions (implemented already in many commercial buildings)
1. **Better interface design**: Only allow destination floor button and show the true elevator direction.

2. **Behavioural Nudges**: Using signage to explain that pressing both up and down causes inefficiencies and may cause social embarrassement when you inevitably end up on a floor that shows that you pressed the opposite direction to intercept.

### Side brain inspiration on a story

![Awkward Eleavtor Situation](/assets/img/awkward-elevator.png){: width="400" }
*Figure 1. Image generated using OpenAI from the prompt awkward situation in the elevator.*

## Canto XXVII½ — The Vestibule of Vertical Offenders
(For Those Who Press "Up" When Bound for Down)

And lo, we came upon a shaft of steel and glass,
Encased in mirrored guilt, within the Tower of Delay.
A place not Heaven, nor yet quite Hell,
But Purgatory's hold for the selfish and the sly.

Here dwell the Button-Betrayers,
Souls who in life,
Pressed the upward arrow while longing to descend,
Disturbing the sacred rhythm of the lift.

They stand in endless queue upon high floors,
Each hopeful for descent, yet cursed by their own hand.
For every elevator that arrives doth rise instead,
Mocking their impatience with upward sighs.

A spectral voice echoes from the panel:

> "You wished to rise, and rise you shall,
> Through every floor, through every stall.
> And only when the tower's crown you see,
> Shall you descend — and endlessly repeat."

And I, the pilgrim, turned to my guide and asked:
“Is there no mercy for these misguided few?”
To which he spoke, without pity:

> “They knew the code, yet broke the rite.
> Let them taste the looping flight.”

---

## Disclosure

All opinions are my own.