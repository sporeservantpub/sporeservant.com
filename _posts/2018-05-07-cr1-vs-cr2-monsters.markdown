---
layout: post
pretitle: Spore Servant Happy Fun Hour
title: What is the difference between a CR1 and a CR2 monster?
date: 2018-05-07 9:30:00
categories: happy-fun-hour
# excerpt: Hero be warned - here lies maths. Just a little maths, though, so don't run.
# hero-image: "/images/.png"
# hero-text: ""
---

> Hero be warned - here lies maths. Just a little maths, though, so don't run. Saddle up for our Happy Fun Hour!

Note: this post was inspired by [@mikemearls](https://twitter.com/mikemearls) [Happy Fun Hour Series](https://www.youtube.com/watch?v=-552hVebgPk&list=PLfS8QgUdeGYqNneY16sB2RFfWI40jlgIy), which I <3 a lot!

I want to take some time to break down the magic of D&D monster creation, and maybe together we can gain some insight into the "how" and "why" of the D&D 5th Edition Challenge Rating system. I also want to preemptively apologize for the mathiness of this post. I don't particularly love doing all the math, and I think the sooner you are comfortable with the rules that you don't even need to think about this, the more fun you will have with the game. However, I think it is *incredibly* value to dive in to the math and understand the mechanics and engineering behind the game.

We will learn that buried deep in the calculations of a creature's challenge rating are revelations about its probable tactics, and that most combat-focused foes are capable of taking out a single player character of the same level as their challenge rating in one round of combat.

The 5th edition challenge rating system gets a lot of criticism. I think much of it is justifiable - especially on the surface, in regard to immediate usage by a DM creating monsters or encounters - but some of it is still a mystery and warrants further analysis before table-flipping in-game or burning your Dungeon Master's Guide.

In this post, I will discuss:
  - what philosophies present from the data?
  - what are the mechanical differences and what do they actually mean?
  - is challenge rating a linear scale?
  - what is a creature's challenge rating really trying to tell us?

### CR1 Creatures: Bugbear and Young Faerie Dragon

In order to really understand the mechanical differences between a CR1 and a CR2 creature, let's first analyze a CR1 monster - in fact, let's analyze two CR1 monsters, side by side, so we have a slightly wider berth of data. Let's take a look at a Bugbear as our more brutish type, and a spellcaster like the Faerie Dragon (young: red, orange, or yellow). We'll look at the stats that are used in calculating offensive and defensive challenge ratings, and then finally their average.

|----------------------------------------------------------|
|                    | Bugbear     | Faerie Dragon (young) |
|----------------------------------------------------------|
| **Defensive**                                            |
|----------------------------------------------------------|
| Armor Class        | 16    | 19 (base 15, + 2 for Magic Resistance, +2 for Superior invisibility |
| Hit Points         | 27    | 14                          |
|----------------------------------------------------------|
| **Total Defensive CR** | 1/4   | 1                       |
|----------------------------------------------------------|
| **Offensive**                                            |
|----------------------------------------------------------|
| Attack Bonus       | +4    | +7                          |
| Damage per Round   | 11    | 1                           |
| Save DC            | n/a   | 13                          |
|----------------------------------------------------------|
| **Total Offensive CR** | 1     | 1/4                     |
|----------------------------------------------------------|
| **Average CR**         | .625  | .625                    |
|----------------------------------------------------------|

The Bugbear's *brute* feature causes its effective per-round damage to be 2d8+2 rather than 1d8+2, and this is already accounted for in its stat block (Attack Bonus).

> 8 out of 12 classes have hit dice of 1d8 or lower

For the Faerie Dragon, its HP is 14 and its AC is 15, so it would have a challenge rating of 1/4. However, because of its *magic resistance*, its Effective AC is increased by 2 to 17. Then, in addition, because of *superior invisibility*, the Faerie Dragon adds an additional 2 to its effective AC, making it 19. See page 280-281 of the [Dungeon Master's Guide](https://www.amazon.com/Dungeon-Masters-Guide-Core-Rulebook/dp/0786965622/ref=as_sl_pc_tf_til?tag=sporeservant-20&linkCode=w00&linkId=f6cec78426cdc4722361f7837ad8f11d&creativeASIN=0786965622) for more information on Monster Features and how it affects their final (or average) challenge rating.

Now, **let's be real**: in a combat situation against 1st-level character, the bugbear can dish it out. There is a high likelihood that it could kill any level 1 player character with 1 hit. If its damage is 2d8+2, that means average damage is 11 - the maximum Constitution bonus a PC can have at level 1 is +3, and a rare +4. That means that any player character whose class Hit Dice is d8 or less can likely be taken out in 1 hit (8 out of 12 classes have hit dice of 1d8 or lower).

On the other hand, the Faerie Dragon is a good-aligned creature, and likely if the players are to encounter one, it will not be a combat situation. On a social encounter level, a mischievous Faerie Dragon acting on the *chaotic* part of its nature is virtually out of the realm of possibilities for a first level party to successfully contend with.

For example: a red faerie dragon can invisibly follow the party to a treasure, appear in the room but attempt to hide with its Stealth, then cast *mage hand* to steal the treasure they were after, and disappear, never to be seen again. Very useful for a villain with a pet faerie dragon! But how can the party really deal with superior invisibility at level 1?

#### But what does it all *mean*?

> CR1 creatures are designed to be challenging/deadly/impossible for a level 1 party without the dice on their side.

By looking at just two CR1 monsters side-by-side who have very different monster makeup, my first thought is that the challenge rating system is pretty wildly flexible in how drastically different variables return the same ultimate result. An argument could be made that it would be more valuable to present both offensive and defensive challenge rating in the monster's statistics, because these two have very different implications for the encounter. Not saying they should, but an argument could be made in favor of it!

For example, if you just look at the challenge rating by itself, you will have no idea that a Faerie Dragon with challenge rating 1 is not capable of dishing out the kind of combat damage it would need to be a threat to the party. But, from a defensive perspective, the combat may go on a long time as the Faerie Dragon is a (sometimes) invisible creature with **magic resistance** - they will rarely hit it.

The party will be able to bash on the Bugbear with relative ease, but, in the short time it is alive, it will likely drop 1 or 2 party members to 0 hit points, depending on the number of actions the party has and whether or not the monster has allies.

Additionally, I would posit that CR1 creatures are designed to be challenging/deadly/impossible for a level 1 party without the dice on their side.

I think the takeaway here is that in general, and in my observations of analyzing monsters in 5th Edition, the challenge rating really takes into account specifically: if it comes down to combat, how likely is the party to die? It does not take into account as obviously how badly can something annoy the players, foil their plans, spy on them, learn their tactics and report to their superiors, etc. This is why tactics are so essential to think about! (If you're looking for tactics advice, I cannot recommend enough [The Monsters Know](http://themonstersknow.com/) by [@geeniusatwrok](https://twitter.com/geeniusatwrok)).

### CR2 Creatures: Quaggoth and Lizardfolk Shaman

Now let's take a look at two CR2 monsters now and see what we can learn. I will choose again a more melee monster - the Quaggoth - and a spellcaster - let's use Lizardfolk shaman!

If you're savvy, you will notice that at first glance the Lizardfolk Shaman seems to have a wildly inappropriate challenge rating. Its features - **Hold Breath** and **Change Shape** give it no bonuses to its offensive or defensive challenge rating, and none of its spells do more damage than its multi-attack, so it won't get a save DC to add to its offensive challenge rating.

So how in the world did WotC come up with this challenge rating? Well, I don't know for sure, but I imagine it is because of the way they determine Effective Hit Points. The Lizardfolk Shaman can cast *conjure animals* (twice, but challenge rating only accounts for once), with the rule "reptiles only". The highest HP creature of type "beast" is a **giant constrictor snake**, which happens to be a reptile with a whopping 60 hit points!

Additionally, the Shaman has a Change Shape ability which is essentially a polymorph. So when the party gets the shaman down to near-death, he or she can polymorph into a crocodile with 19 hit points (who technically has a lower per-round damage output), from which they will revert back to their natural form when the crocodile's hit points reach 0. So technically the shaman's effective HP is 106!

|----------------------------------------------------------|
|                        | Lizardfolk Shaman | Quaggoth    |
|----------------------------------------------------------|
| **Defensive**                                            |
|----------------------------------------------------------|
| Armor Class            | 13                | 13          |
| Hit Points             | 106 (base 27, +19 in crocodile form, +60 from *conjure animals* highest HP creature **giant constrictor snake**) | 45 |
|----------------------------------------------------------|
| **Total Defensive CR** | 3   | 1/4                       |
|----------------------------------------------------------|
| **Offensive**                                            |
|----------------------------------------------------------|
| Attack Bonus           | +4    | +5                      |
| Damage per Round       | 9     | 26 (base 12 + 14 for **wounded fury**) |
| Save DC                | 12    | n/a                     |
|----------------------------------------------------------|
| **Total Offensive CR** | 1     | 3                       |
|----------------------------------------------------------|
| **Average CR**         | 2  | 1.625                      |
|----------------------------------------------------------|

Once again, our challenge rating 2 melee combatant the Quaggoth deals a per-round damage amount that has the potential to take out any level 2 player character in just one round. Even a fighter with 2d10 hit points and the *Second Wind* class feature - with an effective HP of 22 (10 + 6 (1d10 average) + 6 (Second Wind 1d10 average)) - is well within the means of the Quaggoth dropping it to 0 HP in one round (even if you give the fighter a con modifier, it still looks bad for them).

#### A Minor in CR2 Creature Design Philosophy

I'm not 100% sure what WotC's intentions were here in their design, but my bet is that they want a high likelihood of the player characters to have at least 1 party member drop to 0 in combat, allowing for party members who want to take on the healer role to be able to do so.

Additionally, I think designers of 5th Edition are well aware that if they want the monsters to gain an advantage in combat, they need to reduce the number of actions the party takes in comparison to the number of actions the monster takes (known as Action Economy). Once the fighter is down, the Quaggoth, in round 2, could theoretically take down 2 more squishy characters and leave room for that moment where the rogue, monk, ranger, or cleric ends up the hero of the battle.

### Conclusion

In [this article from Sage Advice](https://www.sageadvice.eu/2016/10/05/im-having-difficulty-with-my-players-being-stronger-than-their-challenge-rating-advice/), the following [Twitter conversation](https://twitter.com/matthewmercer/status/777551213269164032) is shown:

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">Adjust monsters to have a slightly higher Hp, AC, damage, or ability DC. Mix and match the above to test out a balance</p>&mdash; Matthew Mercer (@matthewmercer) <a href="https://twitter.com/matthewmercer/status/777551213269164032?ref_src=twsrc%5Etfw">September 18, 2016</a></blockquote>
<script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

Matt Mercer gives a valid response here - these are all of the variables of the offensive and defensive challenge rating - but some of the above analysis reminds us that we can also:
- add or remove an ability that affects the monster's challenge rating (page 281 of the [Dungeon Master's Guide](https://www.amazon.com/Dungeon-Masters-Guide-Core-Rulebook/dp/0786965622/ref=as_sl_pc_tf_til?tag=sporeservant-20&linkCode=w00&linkId=f6cec78426cdc4722361f7837ad8f11d&creativeASIN=0786965622))
- use features that increase the creature's effective hit points (polymorph, change shape)
- give the monster/npc/villain a magic item that let's the cast a spell that does more damage than their normal attack (increase damage/round)

So, what are the differences between a CR1 and CR2 creature? Well, it's just the levers Matt states above (and in the tables above), combined with some of the features and abilities I just mentioned. I think the fact that both CR1 and CR2 combat-focused creatures are capable of doing enough damage on average to take out a party member in a single round shows that the challenge rating is pretty linear, at least in the early levels. The offensive and defensive challenge ratings tell wildly different stories about the kinds of tactics a monster will use, which may be of even more value than simply knowing "is this thing going to kill my PCs?" We also learned that in order to actually learn how WotC designers came up with the challenge rating for monsters, you may need to dig deeper to understand the CR value of certain abilities, particularly in regards to effective HP. And finally, we leveled up our understanding of monster building so that hopefully we can adjust our monsters with confidence in the future without having to think about all this math! Cheers ;) ::beers-clinking::
