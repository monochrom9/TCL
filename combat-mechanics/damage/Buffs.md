---
Description: >-
  A look into how buffing effects that are dependent on a character stats work in contrast to flat bonuses.

---

# Buffs

## Introduction

There are two main types of buffs - ones that scale off a character's stats and ones that grant a buff of constant strength, regardless of the buffing character's stats. 

For example, Kazuha's Ascension 4 Passive grants his teammates an Elemental DMG% buff, and the amount of Elemental DMG% he grants is dependent on Kazuha's Elemental Mastery - as such, Kazuha's A4 buff counts as a scaling buff. 

On the other hand, Sucrose's Ascension 1 Passive grants 50 EM to any party members matching the element that Sucrose Swirls, regardless of her personal stats, so it counts as a constant buff.
## Buff Stacking

Scaling buffs cannot stack with each other. For example, Sucrose's Ascension 4 Passive, which grants 20% of her personal Elemental Mastery to any teammates when her Elemental Skill or Elemental Burst hits an opponent, cannot stack with Kazuha's Ascension 4 Passive - Kazuha's buff will be calculated using the EM he had without Sucrose's Ascension 4 buff. 

For example, if both Sucrose and Kazuha have 1000 EM and Sucrose buffs Kazuha's EM to 1200 with her Ascension 4 Passive, Kazuha's buff strength will remain at 1000*0.04% = 40% Elemental DMG%, not 1200*0.04% = 48% Elemental DMG%.

However, constant buffs can stack with scaling buffs. For example, the Instructor's set provides 120 EM to any party members when the holder triggers an Elemental reaction. If one of Kazuha's teammates holds the set and triggers an Elemental Reaction, Kazuha's buff strength will take into account the 120 EM from the Instructor's set.

For example, if Kazuha starts with 1000 EM, and a teammate buffs his EM to 1120 with the Instructor's set, then Kazuha will provide 1120*0.04% = 44.8% Elemental DMG%. 

