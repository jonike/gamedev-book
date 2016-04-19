# Game Development Concepts

This is the first chapter of the book, where the actual content begins. In this chapter, we'll discuss a few key ideas about what is game, what is game development, and what differentiates good games from bad games from great games. As usual in life, there is no golden hammer, or magical formulas, but we do hope some of these ideas will enlighten you a little bit.

In this chapter we will discuss a bit about the process of making a videogame, from a bird's eye view. Before being able to understand how to make a videogame, we need to discuss what exactly is a videogame. This will prove rather difficult, but enlightening.

## What makes a Great Game?

So, what makes a Great Game? The short answer: **nobody knows**. Yes, it is sad. Game development is still in its early beginnings, even though more than 50 years have passed by. That means there is no rock solid theory about what makes great games. There are no proven theorems, yet. Its is more of an art than a science.

However, there are a few key ideas that almost everybody agrees are very important components in most, if not all, successful video games:

**An engaging mechanic:** We'll discuss later exactly what _mechanics_ means but, for now, take it as the core functionality of the game. Its like the rules, the gameplay, what can the player do, and how the game reacts to him. Arguably, the single most important aspect of a game is its mechanics.

**A beautiful skin:** The name says it all. The skin is how the game looks, and many games have succeeded because, at first, they looked gorgeous. In the end, a beautiful skin can only get you so far, but without it, you cannot reach the top either.

**A tight learning curve:** Tight is key word here. Great games are neither too hard nor too easy. They are simply _challenging_. And that's extremely hard to achieve.

**A conscious marketing:** This part cannot be stressed enough, and yet many fail because after having a great product, they just couldn't sell it. It is not enough if your game is great. You still need to _convince_ people to play it anyway.

**A bit of luck:** And finally, yes, sometimes you just hit the right spot, publish your game at the exact moment, or get the right kind of media attention.

In this course, we'll try to provide as many hints as possible for the first four. The last one, well, it's all on you.

So, the ultimate question is: do you need to be a creative genius to make awesome games? Well, the only answer we can give is: **maybe, nobody knows**.

_However_, you just asked for awesome games. But what about **good** games? Not games that are a hit, top grossing, E3 Game of the Year, or anything like that. Just games that are good enough to pay their own cost, and then make profit. The kind of games that you can make a living on. Well, the whole premise of this course is: **no, you don't**. You don't need to be a creative genius to make a living out of videogames anymore than you need to be a creative genius to make a living out of any other kind of software application. Sure, creativity **is** involved, perhaps more than in any other kind of software, but, if there is one idea you need to take from this course, is this one:

>There is a fundamentally scientific path, not based on talent or luck, to develop and publish successful games.

It is a bold statement, we know, and the whole course is designed to convince you of that, and to show you how it works. Maybe I'm right and maybe I'm not. Tag along and find out. In the end, even if I'm wrong, you'll learn a couple of techniques that, if not enough to make you rich, at least are very fun to program.

### Skin versus Mechanics

So, let's begin with the main content. The first two things we told you were fundamental for making a good game are **skin** and **mechanics**. In this section we'll explain exactly what do we mean by that.
These two components are the very fabric of any game. The simplest explanation we can come up with is this: **skin** is the *look*, while **mechanics** are the *feel*.

When you think about the **skin** of your game, you're thinking about the genre (in a narrative sense: dark fantasy, steam punk), the topic (the battle between the good and evil, rescuing the princess, saving the world), the history and ambient of the world; but also about the graphics, sound, textures, characters that make up that world. On the other hand, when you think about the **mechanics**, you're thinking about the gameplay, the rules, the controls, the algorithms that decide how your game behaves and responds to the player.

One important difference between skin and mechanics is that almost everybody recognizes the skin right away, while most people will have a very hard time recognizing exactly what are the mechanics of a game. For this reason, mechanics are reusable to a great extent without almost anybody complaining, while new skins need to be invented all the time to get players satisfied.

There are many skins good enough to be reused all over again and again (dark fantasy themes, cartoonish graphics). However, most skins are fashion-driven, context-dependent and audience-specific. For instance, cartoon pixelized graphics are very common these days in mobile games, in a nostalgic-for-the-good-old-times style. That's fashion working. And stylized anime graphics are preferred in the eastern gaming cultures, while Marvel style graphics are preferred in western cultures (although globalization and a conscious marketing on both sides have smoothen the frontiers a lot). That's the audience preference. On the other hand, RPG games are popular everywhere, even if there is still some audience preference in mechanics too (westerns prefer less talking and more shooting while easterns seem to prefer strategic thinking).

Fortunately, making up new skins is relatively easy. Your average graphics designer can probably come up with a 100 completely different looks for your game, all equally pleasing. However, making up a good new mechanic is extremely hard, and almost invariable when a game invents a new mechanic, it immediately becomes an icon. Think about famous games, both old and new: Tetris, Pacman, Mario, Final Fantasy, Doom, StarCraft, Civilization, Diablo, The Elder Scrolls, Spore, SimCity, The Sims, Grand Theft Auto, Assassin's Creed, Angry Birds, Clash of Clans, and the thousand others missing in this list. Think about it, and you'll discover that:

>Almost every great game ever made either created or popularized new mechanics.

Just keep this in mind: **skin** is *why they come*, but **mechanics** is *why they stay*.

### Achieving the Right Balance

It should be clear by now that skin and mechanics are two very important concepts from where to view the design of a video game. You have to nail them both to make a successful game. So, the interesting question is: how to distribute your energy between these two tasks? Should you invent your own skin, your own mechanics, or reuse some?

The key point here is to be **efficient**. If you are going for the E3 Best Game of the Year, then by all means, you need both an awesome skin and a mind-blowing mechanic. However, if you want to publish a lot of small games, fast enough to keep the pace, and your main purpose is to make a living, not a piece of art, then remember what We just told you:

>Almost everybody can recognize a similar skin, but hardly anyone can distinguish a cloned mechanic.

So, the easy path would be to reuse some proven mechanics, and try to come up with a suitable skin for it. There is another argument in favour of reusing mechanics and investing on skins, and is this: *Skin is content*, so it is fairly easy to keep making more and more, because **content complexity scales linearly**. This means that if you want twice the number of suits, you need twice the resources (designer hours, for instance). Also, it can be argued that more content is always better. More swords, more levels, more enemies. On the other hand, *mechanics are features*, and adding a new feature is a tricky thing, because you need to make it work right with the rest of the features. For this reason, we can argue that **feature complexity scales quadratic**, because, in the general sense, every new piece of behaviour needs to get along with all the others.

This is the reason why the difference between casual and AAA games is mostly about how many different mechanics they have, and not primarily about content. Yes, there is more content in AAA games, but not much more content, comparatively. However, casual games usually have **one single mechanic**, while AAA games are full of mini-games and different mechanics.

Another key point here is deciding to go in a **skin-first** approach or in a **mechanics-first** approach. The former involves deciding a *skin* that is  currently hot. For instance, during the FIFA World Cup, almost every single mini-game related to football (soccer) will have a unfair advantage. You can also exploit some news topic, like some celebrity gossip, or the presidential campaign, etc. The trick is in finding a skin that will have an unfair advantage during the current timespan, and ride the wave. Then you just select a simple mechanic that fits (i.e., tap to bite your fellow soccer player) and ship. Of course, for this strategy to succeed you need a very good timing, you need to develop fast, so, take the *simplest possible mechanic* that fits, and you need to **target your audience**. It makes no sense to sell a soccer-based game to middle-age housekeep women, even if its the hottest topic around.

The later approach involves picking an interesting mechanic that is popular at the time being. Good examples now are infinite runners, physic puzzles and tower defence/attack. Then, select a skin that has something new to offer. Maybe nobody has done a tower defence that features zombies versus plants? Or maybe a physics puzzle involving little angry birds and piggies could be the next hit? Deciding a basic mechanic to build your game around is also dependant on the audience, although mechanics are much more broad in terms of audience than skins. But a few noteworthy examples are *fast-paced* mechanics versus *strategic-mechanics*. The young and violent prefer fast action,and are more inclined towards enjoying angry little birds destroying structures. The elder and cult prefer strategic puzzles that provide an intellectual challenge.
Of course, in the end, there are both action players and strategic players of all ages, races and gender. You just have to decide if your game will please one or the other.

### Targeting Your Audience

In the end, it doesn't matter if you pick a skin-first or a mechanics-first approach. It all comes down to selecting your audience, and building a game for them. Always think first about your audience, who they are, what are their tastes, which kind of games they play. But most important, find some of them, make them play your prototypes, and **watch, don't talk**. Never explain to a player testing your game what she should do. Let her find it out. If there is no immediate connection, no ah-ha moment when she discovers the inner workings of your game, then either your mechanic is too complex, or your audience is ill-defined. This is a good thing too, because you'll find out pretty soon what's working and what's not.

One interesting way to look at players, is the *hunter/gatherer* dichotomy. Like most things in life, is not 100% accurate, but nevertheless, interesting enough. It states that any gamer is either a **hunter** or a **gatherer**. The hunters enjoy the thrill of the chase, the need to make fast decisions, and the
inherent pleasure of non-determinism. They are willing to make a lot of mistakes, if they can recover from those mistakes fast enough. They need a chance to visualize the prey, to decide and perform, and then a small but extremely exciting moment of await, before the definitive outcome. A classic example of a hunter game is Angry Birds: you visualize the prey, make a decision, let the bird go, and then you have a few seconds of expectation before the bird actually lands and the outcome is decided. Another classic example is Candy Crush, for the matter. One very important thing is that hunters don't plan too much, they only visualize the immediate reward, and they need **a lot** of chances to fail and retry.

Gatherers are the exact opposite  They are long time planners, and they enjoy concocting complicated strategies for a final outcome. They enjoy the planning and are fans of deterministic, foreseeable albeit intricate decisions. They will not forgive you if after so much planning, things don't turn out as expected because of hidden traps or unclear rules. So you need to make sure that every time they fail, is clearly their fault. Classic gatherer games are Farmville and the like. It might seem that hunter games are more effective, but don't underestimate your gatherer users. They will probably stay a much longer time playing your game.

Now, you might be thinking, what if We want to please both? Well, you certainly can, and actually most bigger games try to do exactly that, and include mechanics that are pleasant for hunters, and mechanics that are pleasant for gatherers. However, in small, casual games, it is very hard to do. As an example, after the initial success, Don't Touch the Spikes, a classic hunter game, included an alternative gatherer gameplay, where players could recollect gems while watching (and tapping on) little flying birds. It is possible, sure, but keep in mind the following:

>Great games polarize players.

You can either love or hate Civilization, but once you play it you have to have an opinion. You can either love or hate Grand Theft Auto, and The Sims, and StarCraft, and all the others. I'm not saying you should intentionally piss people off, but don´t be afraid to polarize players. Pick your audience, and build a game **for them**. The more defined your audience is, the more loyal they will be. They'll feel identified with your game, they'll love you for understanding them. And the worst you could do is adding some dumb new game mechanic to please the rest of the world; all those other players that **are actually not** playing your game. So instead of asking "How might we have *more* players?" ask yourself "How might we have *more loyal* players?". Invest in getting all the nerds that love to build spaceships with complicated physic simulations, instead of getting a few of them, and a few of the ones who like shooting at people, and then a few of the ones who like race cars. Take Watchdogs as an example. Not fast enough for GTA, and not smooth enough for Assassin's Creed, and then the hacking part just sucks. If you try to please everyone, you'll please none.

### Finding Interesting Mechanics

To finish with this first post of the series, We want to share a few tips about how to find and recognize interesting mechanics. This strategy is something We call **deconstructing mechanics**. Its a thought experiment that works more or less like this: you pick a successful game, remove all content, and reformulate its mechanic in terms of abstract elements. In the end, you want to have a sentence in the form: the player *interacts* with *some element* to achieve *some goal*. To find out the mechanic of the game, fill in the *italics* with the most abstract concept you can that still refers to that game.
To recognize if you still need to delete something, ask yourself if you still recognize the game. If you do, then there is skin left. Pick something else and ask if by removing that, the fun is lost. If it does, then you are touching an element of the core mechanics.

Let's go through an example, let say, Angry Birds. To begin with, do we need the piggies at all? Surely not; if you remove the piggies, nothing changes, it is still as fun as before. So, remove that. Next, does it matter if the projectiles are birds? Suppose you throw a rock at the boxes. It seems to still be fun enough, so, let's change the birds for abstract projectiles. Now lets tackle the boxes. What if we remove them altogether? Well, in this case the game just looses its sense. So no, the boxes stay. There needs to be a structure, it needs to be breakable, and it needs to be physically simulated. There you have it, Angry Birds mechanics is this: the player *launches* a *physically simulated projectile* at *some carefully positioned structures* to *create havoc*. This is what makes Angry Birds fun. The rest is just skin. Sure, there are tiny bits of secondary mechanics, like activating power-ups in the air and bombs. But the core, what makes the game great, is just that.

One you have identified a good mechanic, and stripped all the skinny parts, you just need to invent (or copy) a new skin, and dress up your game. Lets say you are mad scientist in control of a volcano, and you can throw boulders of fire to destroy the houses of fearful villagers. There you go, you just invented a new game. Add all the skin you want: villagers running in fire, different types of buildings, some harder than others, different maps, different sizes of rocks, with different physical properties. All that is skin, even if it involves changing a few parameters, because it adds no behaviour. Bigger rocks are just different sprites with different mass for the physics engine.

What about if the fire spreads to adjacent buildings and then some firemen try to put it out? Well, careful, now you are talking of a new mechanic, you just invented a new adversary, and a new gameplay. Now we are not just fighting against the level designer who layout the structures. Now we are also fighting against some AI (as dumb as it might be) who is trying to delay our progress. And also, new rules come into play: how does the fire spreads, how long, to which structures? Remember, adding new types of boulders and houses is easy, adding a new behaviour is hard.

## Discussion

So, to sum it up, here is what we have so far:

* **Skin** and **Mechanics** are the core elements that make up your game.
* **Mechanics** are hard, while a good **skin** is almost always easy to make.
* The easiest (and safest) approach is to **invent skins** but **reuse mechanics**.
* Be **loose** when adding more skin, but **careful** when adding mechanics.
* Always **define your audience** first, and make a game for them.
* Don't be afraid to **polarize players**.

In the next chapter we'll discuss about the phases of game development, and how to tackle you first few projects in a way that doesn't destroy your ego.