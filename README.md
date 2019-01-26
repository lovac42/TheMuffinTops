# TheMuffinTops: Learning Stages

<i>Top of the Muffin to You!</i>

## About:
If you're familiar with learning stages in Supermemo, this is exactly what it is, a set of tools emulating SM's learning stages. This is especially useful for passive review (IR cards) where learning steps are not necessary.


### The first stage: Review cards (Rocks)
When your mind is fresh, when time is limited, or when you are overwhelmed by overdues, review cards should be your primary focus. The idea is that review cards have a higher priority than learning cards, so they should be reviewed with lapses filtered out first. Whereas learning cards can be postponed for later review. This ensures that all due reviews get at least one exposure based on the algorithm. Review cards are the rocks you should put in to your learning jar first, they are the tops of the muffin.

In this addon, review cards and day-learning cards are treated the same by default. This can be changed by editing the configs with the addon manager.


### The second stage: New cards (Pebbles)
New materials add dynamics to your study. They make learning fun and interesting. These are the pebbles that goes in to your jar.

Is the jar full?  


### Final Drill: Learning cards (Sands)
Learning would be greatly enhanced if you go through final drill, you may even like doing them, but they are not as important. Learning cards are the sands in your learning jar.


### Cram Mode: Filtered Decks (Water)
Some versions of the "Rock, pebble, and sand" story incorporates water as the fourth element. These would be the filtered decks in Anki, though it is not used here.


## Another side of the story
The problem with focusing only on the high priority items is that we tend to neglect the low priority stuff and they start to mount up over time. This is the reason Anki mix learning cards with review cards. Here, a set of tools is provided to deal with the learning cards that remains after your study.

<img src="https://github.com/lovac42/TheMuffinTops/blob/master/screenshots/menuitem.png?raw=true">


### Skip final drill
This option is in the preference menu. It is used to automatically skip all learning material at the end of each session. Learning cards are converted to day-learning cards with the due set to 1 day for new card and 2-4 days for review cards load balanced base on the ease factor. You should only turn this on in extreme cases such as during vacation. This ensures that all lapsed cards get at least one exposure a day.

<img src="https://github.com/lovac42/TheMuffinTops/blob/master/screenshots/prefmenu.png?raw=true">


### Cut Drills
Learning cards are converted to day-learning cards on the selected deck and subdecks. They will be postponed and load balanced across several days based on the user's choice. Any learning steps remain will resume when the card is due again. This is useful for leech cards at the end of your study.


### Drop Drills
Lapsed cards are converted to review cards, and new-learning cards are converted back to new cards. The behavior is similar to burying or suspending learning cards on the V1 scheduler. All learning steps will be discarded.


### Randomize Drills
All due learning cards are converted to day-learning cards due today. Because the learning queue is time sensitive, it can not be randomized. By converting learning cards to day-learning cards, we gain the benefit of shuffling the queue during review.

This option is based on your "learn ahead limit", if you set this to 999, all learning cards will be affected.
