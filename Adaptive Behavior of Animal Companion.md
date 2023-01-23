# Adaptive Behavior of Animal Companion

Category: Internal R&D
PIC: Dhika
Research Periode: January 9, 2023 → January 27, 2023
Status: Ongoing

### Sources
https://www.notion.so/agategdd/Relation-between-Companionship-Player-Action-a1e9d2bd71ec4dfd8538af0ecbc26f79

# Table of Contents

# Background

## The Importance of Companions

A companion is an NPC who persistently accompanies the player as support. They can be controlled or not controlled by the player. For example, Ellie in The Last of Us is completely autonomous, whereas Dogmeat in Far Cry 5 is a semi-autonomous companion since it was independent but the player can give commands to it.
The companion’s goal is to help the player accomplish in-game goals. Since companions almost continuously appear throughout the game, they have the highest influence on the player’s experience in the game. They are an essential part of the player experience by ensuring that the player has fun and a sense of immersion in the game world. However, creating a companion that was not superficial is a challenge on its own, even in AAA games.
A companion that should intensify the player experience on a social and emotional level, should display believable behavior. Furthermore, the emotional bond between the player and the companion character affects the companion’s believability. Emotional attachment to digital characters can be as real and strong as to living beings.

## Animals as Companion

Considering games like the Fallout series, we reason that a companion does not necessarily have to be human. Animals are typically used in the game to give an emotional attachment to the player, creating a more immersive environment since people care a lot more about animals than humans. It is shown that people are more emotionally disturbed by reports of an animal than human suffering or abuse. One reason some people choose pets over people is that pets provide unconditional positive regard. This trait can be seen in the game Fallout 4 where Dogmeat, the dog companion, has a maximum affinity and won’t be affected by player action, unlike the other human companion who can be displeased by negative action.

The emergence of Twitter account Can You Pet the Dog, with more than half a million followers, and the Does the Dog Die website showed that people care so much about animals, especially dogs, in the game.

In terms of development, it’s relatively easier to create a believable animal companion than a human companion. Believability refers to “the size and nature of the cognitive gap between the player's experience and the character they expect”. When the players’ expectations match their experience, a character is fully believable. For a human companion, to be believable, they need to have a unique personality. Human companions need to have their own agenda and can’t be following the character blindly to be believable, unlike animal companions whose personality usually revolves around the player.

## Adaptive Behavior

Several design patterns for believable companions are directly related to behavior. Believable companions have to be aware of their surroundings and react to changes even if the player does not directly interact with the companion. These characteristics are important, as they correspond to the demand for being able to behave appropriately in various contexts.

Whereas the companion’s behavior has to match the player’s expectation, that does not necessarily mean that their behavior has to be the most effective or most realistic. It has to account for the situation and predict what the player desires. That implies that a companion who is an active part of the gameplay should be able to adapt to the player’s playing style (e.g., not attacking nearby enemies if the player sneaks past).

# Game Reference

## Companion Type

The type of companions seen in video games are as follows (Animals as main characters are not considered companions. Eg: STRAY):

1. Complementary
The companion doesn’t have any specific role in the game. They were just a part of the world or story. There are two types of complementary companions:
    - Interactable (Can interact on demand, story-based interaction does not count as interactable)E.g. A Space for the Unbound
        
        [https://lh6.googleusercontent.com/GmuwmRmIFtJSb3MUVceJ__AtCtp_hKa3fmIxznqW8GoXHB710HgUEbHD5mRoxGK25pVGeaiMvw_VeBJ01Qftv_vWlD9glh9cOxC5n1G2ouCBudG_sW32VUIyKsVbPJK_D8WdzOt53L7z3n6mNQfP61O8zfOz9LQhsUUCmWsieOE-fkm0l1iL7jcojYg6Zg](https://lh6.googleusercontent.com/GmuwmRmIFtJSb3MUVceJ__AtCtp_hKa3fmIxznqW8GoXHB710HgUEbHD5mRoxGK25pVGeaiMvw_VeBJ01Qftv_vWlD9glh9cOxC5n1G2ouCBudG_sW32VUIyKsVbPJK_D8WdzOt53L7z3n6mNQfP61O8zfOz9LQhsUUCmWsieOE-fkm0l1iL7jcojYg6Zg)
        
    - Non-interactable
    E.g. Dogs in Genshin Impact
        
        [https://lh5.googleusercontent.com/vpG9VfJwxwJqRlmXe7jRWcNX_r1oBRO2-AOyO6kIESeJpRQH7NTOn9QoUphrOwA2dhGOLJn7x_1EBUTtdyJZgeTxv0acft26L7hsSEYSZtfYkKJ_5HFOo1qv7q3mOPyCfCElPfcJq61VMT5vTwqIe8UNcfI9ZxWbzBa13dqW0s1hby-84aJt4heUTNm01A](https://lh5.googleusercontent.com/vpG9VfJwxwJqRlmXe7jRWcNX_r1oBRO2-AOyO6kIESeJpRQH7NTOn9QoUphrOwA2dhGOLJn7x_1EBUTtdyJZgeTxv0acft26L7hsSEYSZtfYkKJ_5HFOo1qv7q3mOPyCfCElPfcJq61VMT5vTwqIe8UNcfI9ZxWbzBa13dqW0s1hby-84aJt4heUTNm01A)
        
2. Playable
The companion can be recruited into one of the playable units, with equal ability as the other character.
E.g. Koromaru (Persona 3)
    
    [https://lh5.googleusercontent.com/PBEaiRbson79-SkXKrr3PFRIpL-IsT-mGGRgtJvGEi2hcBQ3OrcSxMmPW0oI1rnQ9qMbdZ08W7LptoSp_9XagotGjyAd9JDVUTCGa8JoHPFugZy22-hyY50yrbxugdQ68_fHawjdpjDOST_UkrF9NPaiDNISZ50oOVtNtGMdcSlRIb85aXcm3ZEvNs-Xlw](https://lh5.googleusercontent.com/PBEaiRbson79-SkXKrr3PFRIpL-IsT-mGGRgtJvGEi2hcBQ3OrcSxMmPW0oI1rnQ9qMbdZ08W7LptoSp_9XagotGjyAd9JDVUTCGa8JoHPFugZy22-hyY50yrbxugdQ68_fHawjdpjDOST_UkrF9NPaiDNISZ50oOVtNtGMdcSlRIb85aXcm3ZEvNs-Xlw)
    
3. Support
The companion can be recruited to help the main character finish a mission by providing special abilities.
E.g. Boomer (Far Cry)

## Animal Companion in Video Games

### Alice (The Last of Us 2)

Alice is part of the story, not many interactions that the player can do that are not part of the story. She died in the end, killed by the main character.

[https://lh6.googleusercontent.com/mVIf73SznqfIkrBHMnXMCrkFLke6nRV_S2aec4T8k64uJZoZVj04fYK7H3s7cOsUQ2uc0iUen-YNNBi0G25ETwTyoKbbOvapPRMZ6HP1fuq4kESD7_LXOd8hEF0TaQxQQ_N-e4MpOZLlaJ6Y1-3buYO5pC_9_CSGrgTmptikaYrtsZTJfVNae2KtVcr3UA](https://lh6.googleusercontent.com/mVIf73SznqfIkrBHMnXMCrkFLke6nRV_S2aec4T8k64uJZoZVj04fYK7H3s7cOsUQ2uc0iUen-YNNBi0G25ETwTyoKbbOvapPRMZ6HP1fuq4kESD7_LXOd8hEF0TaQxQQ_N-e4MpOZLlaJ6Y1-3buYO5pC_9_CSGrgTmptikaYrtsZTJfVNae2KtVcr3UA)

### Barbas (The Elder Scrolls)

Actually a shapeshifting Daedra. One of the bosses in The Elder Scrolls Online: Morrowind, but not in a dog form.

[https://lh4.googleusercontent.com/XXJCFyga5xUo96ykgngpValbFugCQZ--OceVkOOCCJ-rM8syY6NZdDHF9bdo65vkvKK_yd2tpCgEvuqpATmt2s7yY7eTRfkmUWAOoo0LE-_OBydwVDARiFadxAvfShfrRW6UkbKXziaiLskTBkVNaHuHDWpG6mW4CFpM63JNegVa4kuZMzHtils2-8h8_Q](https://lh4.googleusercontent.com/XXJCFyga5xUo96ykgngpValbFugCQZ--OceVkOOCCJ-rM8syY6NZdDHF9bdo65vkvKK_yd2tpCgEvuqpATmt2s7yY7eTRfkmUWAOoo0LE-_OBydwVDARiFadxAvfShfrRW6UkbKXziaiLskTBkVNaHuHDWpG6mW4CFpM63JNegVa4kuZMzHtils2-8h8_Q)

### Blade Wolf (Metal Gear Rising)

An AI Weapon in the shape of a robotic dog. Playable character on Bladewolf DLC.

[https://lh5.googleusercontent.com/YC5PIXPA0eG4aneEsNOyW0Nplopnynu38WVpm81HArQbWTUKG6YVcjM6tuvCv5z1YQc-s5qpFxlIF3uUijvro4u1X3E1Bmh79gaYRRBobPgNknzKs3qfvORZqHTMo5ksq8iEqfFZadMNyZXGgv32ww6KN4Ng6K46YFYjw0DpePWDgjjR2cXhxAblnJVazQ](https://lh5.googleusercontent.com/YC5PIXPA0eG4aneEsNOyW0Nplopnynu38WVpm81HArQbWTUKG6YVcjM6tuvCv5z1YQc-s5qpFxlIF3uUijvro4u1X3E1Bmh79gaYRRBobPgNknzKs3qfvORZqHTMo5ksq8iEqfFZadMNyZXGgv32ww6KN4Ng6K46YFYjw0DpePWDgjjR2cXhxAblnJVazQ)

### Koromaru (Persona 3)

Koromaru is a teammate that can be gained from the story. Players can control him in battle, they can also create a bond with him through social links. However, this bond will not change the relationship between the main character and the dog. Has similar power with the player (not a support).

[https://lh4.googleusercontent.com/SzfjoLZ5CGZzQAFC9nYPdJ5W-x7eiDujTd6Oy2K4HX6AsLB7xE5YY2gcoD_wB3zVJwkTG5smv9dm5ErPu0WPCIjTVs0UN4WOCu65mFXOuRNlwMBum7vy6UPcVML3Za_mRxDx4tWnii6rKHlzPcMg3R_UHbIq2c9QeSHT_j-3i_ek-ggOfsdXw2TWvZql5g](https://lh4.googleusercontent.com/SzfjoLZ5CGZzQAFC9nYPdJ5W-x7eiDujTd6Oy2K4HX6AsLB7xE5YY2gcoD_wB3zVJwkTG5smv9dm5ErPu0WPCIjTVs0UN4WOCu65mFXOuRNlwMBum7vy6UPcVML3Za_mRxDx4tWnii6rKHlzPcMg3R_UHbIq2c9QeSHT_j-3i_ek-ggOfsdXw2TWvZql5g)

### Boomer (Far Cry 5)

Players can rescue it in order to recruit him. Has special skills that can help players throughout the game. Better for scouting enemies.

- Pointer: tag all nearby enemies)
- Retriever (Fetch a weapon after an attack)

[https://lh3.googleusercontent.com/16OVVxOC-4B_XhKQL9o2ecl2qmU7Wx33_waXK2A1c_A6ZZQ2IIAP_frU-q7pJgtFZ93IZy31MF4XHypjctufFHacxvrbJFcF0rjIGVaAEk8SRj4Y8NrTL8zapdScOGh8vs537aSMVnJcLjQgwA4JPx-EI3s92NqoQ0Etcu0MHAFJgKgfNcjbhRgKFdZpcw](https://lh3.googleusercontent.com/16OVVxOC-4B_XhKQL9o2ecl2qmU7Wx33_waXK2A1c_A6ZZQ2IIAP_frU-q7pJgtFZ93IZy31MF4XHypjctufFHacxvrbJFcF0rjIGVaAEk8SRj4Y8NrTL8zapdScOGh8vs537aSMVnJcLjQgwA4JPx-EI3s92NqoQ0Etcu0MHAFJgKgfNcjbhRgKFdZpcw)

### Cheeseburger (Far Cry 5)

The player can rescue it in order to recruit him. Has special skills that can help players throughout the game. Better for defense.

- Bear Arms: Attack enemies.
- Cross to Bear: distract.

[https://lh6.googleusercontent.com/o0oawzpG4Zpm-fmoF5XG1fVnB1K4FzsspX8Jeg49pnoEypRLBRFiPX7ZYxrLFmvjodHbrnP_XrU0Hp6-Yyyx4fg5b5A95pFMGxxKP91Xnl9mroYe9sNc1WTUu_b7Yr9nZjm5_9xUAC5MpvjUlBGb9kbf5XK-I3svNPhw-bY7EoptqnlSBJTuvz3peZKpkw](https://lh6.googleusercontent.com/o0oawzpG4Zpm-fmoF5XG1fVnB1K4FzsspX8Jeg49pnoEypRLBRFiPX7ZYxrLFmvjodHbrnP_XrU0Hp6-Yyyx4fg5b5A95pFMGxxKP91Xnl9mroYe9sNc1WTUu_b7Yr9nZjm5_9xUAC5MpvjUlBGb9kbf5XK-I3svNPhw-bY7EoptqnlSBJTuvz3peZKpkw)

### Peaches (Far Cry 5)

Players can rescue it in order to recruit him. Has special skills that can help players throughout the game. Good at stealth.

- Pounch: Silently take down the enemy.
- Stalk: Stay hidden among the grass.

[https://lh3.googleusercontent.com/pvPRMxSulWsPPSct2sb8LiOczlCGaODf2jbALU4DXC4b2gL6MCNSuKsSMoEw1JzuvDissHiwUrGnqS0jpzvKMLwbZCovni7uuIyQ_yMVktXPmTe5gnJyvgK3P1eIAd2xvivM1wvy-qVvYvD-L8i_TNGpoXgjQNr8J1U92XhR4lOw_OJ4fT0_ByTwyi-d9w](https://lh3.googleusercontent.com/pvPRMxSulWsPPSct2sb8LiOczlCGaODf2jbALU4DXC4b2gL6MCNSuKsSMoEw1JzuvDissHiwUrGnqS0jpzvKMLwbZCovni7uuIyQ_yMVktXPmTe5gnJyvgK3P1eIAd2xvivM1wvy-qVvYvD-L8i_TNGpoXgjQNr8J1U92XhR4lOw_OJ4fT0_ByTwyi-d9w)

### Caesar (Wargroove)

Playable character (Commander) in the game. Has a similar ability as the player (not a support).

[https://lh3.googleusercontent.com/Ke5kTo-uZfXV_qcvj5qKuK5x6oCOLdmQpm1-T0EBgoA4wNutdRMphFysOwTN-ZnKXNbiCtutaCsHawMBhuWjZxmeUCT92kO6gfaAKjWP1Jl_m1fIlBRuQGA6RFyXLWbENYbju_oqzsZ_FobzWYXlUey5akJwGUvNjkkczn8RdxNb_n6X0tD1VJG_gUajEQ](https://lh3.googleusercontent.com/Ke5kTo-uZfXV_qcvj5qKuK5x6oCOLdmQpm1-T0EBgoA4wNutdRMphFysOwTN-ZnKXNbiCtutaCsHawMBhuWjZxmeUCT92kO6gfaAKjWP1Jl_m1fIlBRuQGA6RFyXLWbENYbju_oqzsZ_FobzWYXlUey5akJwGUvNjkkczn8RdxNb_n6X0tD1VJG_gUajEQ)

### Chop (Grand Theft Auto 5)

During some missions, the player is able to switch to Chop in order to find certain people or checkpoints. Chop can also aid the player in finding Hidden Packages. Players can walk the dog and play fetch with it. However, we can’t pet the dog.

[https://lh4.googleusercontent.com/qg70UUQk49VYyYSjqA9MbZl4TL-b018cVs_9nMn7n0F-Qqwp6I9Y9DKrMD5XnMyoDRojPIGH2fX5fJ6dB2zrAvFL9Si4EiNMHfDxwLOuwOPfO_9mLa8bgpaja2h5KCCPy3nSHeXsACpDwOYhRPg-qASdF9278rwFKoJCqk1N0USM-vKxWKpQFFiT3SL6pA](https://lh4.googleusercontent.com/qg70UUQk49VYyYSjqA9MbZl4TL-b018cVs_9nMn7n0F-Qqwp6I9Y9DKrMD5XnMyoDRojPIGH2fX5fJ6dB2zrAvFL9Si4EiNMHfDxwLOuwOPfO_9mLa8bgpaja2h5KCCPy3nSHeXsACpDwOYhRPg-qASdF9278rwFKoJCqk1N0USM-vKxWKpQFFiT3SL6pA)

### D-Dog (Metal Gear Solid V)

Players find DD as a puppy and they can save him by sending him to the base. Players have to visit the base often to create a bond with the dog, so when the dog get older they can help the player in a mission with his special skills.

- He will follow the player when out on a mission.
- If he’s too far, the player can call him.
- Stunt human/animal
- Attack enemy (to distract/wound/kill)
- Can bark for diversion.

[https://lh3.googleusercontent.com/s1cJpqCmpeeuarsT529j-LdIpdnUOlHBjWoREfXu51G8wHXykX-76WghLEnO0pxtEJ8cUu4SxgRo3vlkfm0vc6LjrcBkMY2OuRRLWeJl0IoApxD61v8HqbZmg6PCoJZrAqQsCcA7Y_C5LJawGQlDJ__E5M0HKA8qw7MmQs9vQzalm-yDRAhLBxrJLh3atw](https://lh3.googleusercontent.com/s1cJpqCmpeeuarsT529j-LdIpdnUOlHBjWoREfXu51G8wHXykX-76WghLEnO0pxtEJ8cUu4SxgRo3vlkfm0vc6LjrcBkMY2OuRRLWeJl0IoApxD61v8HqbZmg6PCoJZrAqQsCcA7Y_C5LJawGQlDJ__E5M0HKA8qw7MmQs9vQzalm-yDRAhLBxrJLh3atw)

### Dinki-Di (Mad Max)

Players can rescue DInki Di to get him as a companion by doing a special mission. The dog is able to sniff out mines and other things, such as ammo and upgrades.

[https://lh6.googleusercontent.com/D0c060GrQBtinau4DMrtN4DDLzFSrml4cTsbVZo-VT0ibWFlnxMGTcftLnE_a7tuJ4mXTNrW3tFEaTAEhnySeXuYgT3VBi-aagWwncBo6iOkcMvb8vbDHeVxT_cSSs3UjGWkOqwVxMBJsRyRpqHR6BCkI7P0n-hUNQzXLGcDzZh1zGCIwV34Ocg8_0gZ7g](https://lh6.googleusercontent.com/D0c060GrQBtinau4DMrtN4DDLzFSrml4cTsbVZo-VT0ibWFlnxMGTcftLnE_a7tuJ4mXTNrW3tFEaTAEhnySeXuYgT3VBi-aagWwncBo6iOkcMvb8vbDHeVxT_cSSs3UjGWkOqwVxMBJsRyRpqHR6BCkI7P0n-hUNQzXLGcDzZh1zGCIwV34Ocg8_0gZ7g)

### Dogmeat (Fallout series)

Companions in Fallout have an affinity that can be raised or decreased based on the player's action. However, dogmeat has maximum affinity from the start and doesn’t react to player actions. Dogmeat can be commanded to attack enemies. Players can also equip him with accessories, but these accessories are purely cosmetic with no effect.

[https://lh4.googleusercontent.com/k0FaL6ecWrjvB654FZG2x4hz78k3paEFncWuRXa3vvhCif2f5MJIEGvgnahkrNclDcWr_Doa_w9Y7Qim4r10nZKLEwgWxVnVdQ6COHfnSJpJtradBT_bJAFrPt4EMKIZhUGscfzbVGi-KorrUavhnl-xit_1ktIOSHQaPl_WnoyJccVxg3ZptVSzYE0kdA](https://lh4.googleusercontent.com/k0FaL6ecWrjvB654FZG2x4hz78k3paEFncWuRXa3vvhCif2f5MJIEGvgnahkrNclDcWr_Doa_w9Y7Qim4r10nZKLEwgWxVnVdQ6COHfnSJpJtradBT_bJAFrPt4EMKIZhUGscfzbVGi-KorrUavhnl-xit_1ktIOSHQaPl_WnoyJccVxg3ZptVSzYE0kdA)

# Development

## Goals

The goal is to create a highly flexible and adaptive companion by simulating different kinds of impulses around the companion. 

## Genre

Not every game is suitable for the integration of a companion. Most of the current games with companions belong to the role-playing or action-adventure genre. Hence, in this research, the development will be conducted with action games in mind to show its full potential.

## Companion Type

To exercise different impulses to the companion, the semi-autonomous companion will be implemented. The companion will act on its own but the player can give direction to it by giving commands.

## Impulse Type

The companion's behaviors are based on several different impulses:

### Player

The default setting for the companion is to follow the player everywhere and attack the enemies. The companion only attacks an enemy if the player is already engaged in battle, given a command to start attacking, or the enemy has attacked first.

### Enemy

1. The enemy was attacked by the player.
2. If the player does not attack any enemy, the companion will attack the closest enemy that can be seen by the companion.

### Command

The companion will act according to the given command. 

1. Follow
The companion will come to the player's side and forgo the previous action.
2. Search
The companion will scan the arena and search for the objective.
3. Halt
The companion will stop attacking.

## Priority

When facing different impulses at the same time. A priority needs to be set to determine which action will take place first.

## Level Design

The game jump right into action mode. Players will start the game in a designated arena along with their companions. 

### Mission Goal

The goal of the mission is to retrieve an item and left the arena.

### Enemy

Several enemies will be scattered around the arena.

### Map

-

---

# Reference

1. Exploring the Design of Companions in Video Games
[https://dl.acm.org/doi/fullHtml/10.1145/3464327.3464371](https://dl.acm.org/doi/fullHtml/10.1145/3464327.3464371)
2. I’m Glad You Are on My Side: How to Design Compelling Game Companions
[https://dl.acm.org/doi/10.1145/3242671.3242709](https://dl.acm.org/doi/10.1145/3242671.3242709)
3. Adaptive Companions in FPS Games
[http://gram.cs.mcgill.ca/papers/tremblay-13-adaptive.pdf](http://gram.cs.mcgill.ca/papers/tremblay-13-adaptive.pdf)
4. Exploring Emotional Attachment to Game Characters
[https://dl.acm.org/doi/10.1145/3311350.3347169](https://dl.acm.org/doi/10.1145/3311350.3347169)
5. Are People More Disturbed by Dog or Human Suffering?
[https://www.researchgate.net/publication/316478802_Are_People_More_Disturbed_by_Dog_or_Human_Suffering_Influence_of_Victim's_Species_and_Age](https://www.researchgate.net/publication/316478802_Are_People_More_Disturbed_by_Dog_or_Human_Suffering_Influence_of_Victim's_Species_and_Age)
6. Why Do Some People Love Animals More Than Humans?
[https://www.embracepetinsurance.com/waterbowl/article/why-do-some-people-love-animals-more-than-humans](https://www.google.com/url?q=https://www.embracepetinsurance.com/waterbowl/article/why-do-some-people-love-animals-more-than-humans&sa=D&source=docs&ust=1674005179511628&usg=AOvVaw3GCmDD_eXHLyXVhKkSRu7j)
7. Playing with Social and Emotional Game Companions
[https://www.researchgate.net/publication/309275458_Playing_with_Social_and_Emotional_Game_Companions](https://www.researchgate.net/publication/309275458_Playing_with_Social_and_Emotional_Game_Companions)
8. Opponent Modeling and Commercial Games
[https://www.researchgate.net/publication/228339723_Opponent_modelling_and_commercial_games](https://www.researchgate.net/publication/228339723_Opponent_modelling_and_commercial_games)
9. Intrinsically motivated general companion NPCs via Coupled Empowerment Maximisation
[https://www.researchgate.net/publication/313953076_Intrinsically_motivated_general_companion_NPCs_via_Coupled_Empowerment_Maximisation](https://www.researchgate.net/publication/313953076_Intrinsically_motivated_general_companion_NPCs_via_Coupled_Empowerment_Maximisation)