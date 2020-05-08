# Daily Work Log
## Goals
* I want to track my efforts at building my own business, Space Monkeys Down, LLC.
* I want to start my life as a game designer and developer.
* I want to publish 3 games by the end of 2020.
  * 1 to Steam
  * 1 to mobile
  * all to [WeirdBeardDev's itch.io](https://weirdbearddev.itch.io/)

**Log Template:** [Improvement Challenge](https://github.com/WeirdBeardDev/Improvement-Challenge) on GitHub

---

## Day 38 - 7 May 2020
**Work streak:** 6 days
**Time (planned/actual):** 5h / 
* SMD - reviewed weekly quest template, made updates to reflect reality
* WBD - posted [A Banner and Research](http://weirdbearddev.com/2020/05/07/a-banner-and-research/) blog and shared out
* WBD - updated VS Code to April 2020 (v1.45); read about update
* TH - 2 commits
  * commit `1f3eaf2` - Add IsObtainable to ResearchManager 
  * commit `45f75d0` - Add SelectedLocation property to GameManager
* Personal note - I spent about 2 hours messing around with my new binoculars and cellphone adapter mount, I need a tripod 😄

## Day 37 - 6 May 2020
**Work streak:** 5 days
**Time (planned/actual):** 5h / 4.8h
* SMD - reviewed my progress for week
* WBD - engaged community on PFD, HRUUG, and a few reddit communities
* WBD - wrote a devlog about Treasure Hunter
* WBD - troubleshot an error in Unity where I couldn't select anything in my scene - somehow the UI layer got locked WTF??!!

## Day 36 - 5 May 2020
**Work streak:** 4 days
**Time (planned/actual):** 2h / 1.5h
* TH - 2 commits
  * commit `9d63472` - Add new research - ignore encounter cost 
    - added FreeAmount to track free buildings
    - HACK changed ComputeCost() to a public method
    - moved ResearchEffect enum to ResearchManager file
  * commit `ba4482f` - Add encounter cost formula

## Day 35 - 4 May 2020
**Work streak:** 3 days
**Time (planned/actual):** 5.5h / 4.1h
* SMD - added Unity Connect to my sales funnel
* SMD - created game page for Treasure Hunter: Quixxen's Suit
* WBD - code formatting, added FORMULA tag for VS Code extension Todo Tree, now I can find all my formulas through out the code
* TH - finalized banner for TH
* TH - 3 commits
  * commit `6fe7661` - Refactor UpdateResearchEffect to ImproveLocations 
    - moved code to ResearchManager
    - refactored ExplorationZone to work with new code
    - found a BUG in Location, created a hack to make this work
  * commit `23b7461` - Add new research item for reducing cost of all encounters
    - fixed encounter cost
    - created new class ReduceAllEncounterCostResearch
    - updated enum ResearchEffect
    - added new effect to UpdateResearchEffect
    - add new research to Tree
  * commit `5a220d7` - Update encounter base cost formula

## Day 34 - 3 May 2020
**Work streak:** 2 days
**Time (planned/actual):** 4h / 2.6h
* SMD - participated in Unity's Your First Game Jam
* SMD - performed weekly cleanup, bookkeeping, and goal review

## Day 33 - 2 May 2020
**Work streak:** 1 day
**Time (planned/actual):** 10h / 10.1h
* SMD - created plan for next week
* WBD - posted to PFD and created Meetup event about Unity's Your First Game Jam
* TH - 9 commits
  * commit `952f583` - Refactor Encounter class for research 
    - converted BaseCost and CurrentCost into a Stat type
    - updated code in Quest and DisplayEncounter for new Cost member
    - created a formula for calculating base cost for all encounters
  * commit `75dc46e` - Cleanup Stat class
  * commit `4c3b116` - Implement new research - Increase Research Point Award
    - created new research class
    - updated ResearchManager to know what zone it's in
    - moved the research item creation into ResearchManager ctor
    - coded a test method for rewarding research points
  * commit `b4ef0a0` - Update research benefits
    - changed zone max locations to Stat class
    - moved updating benefit modifier to ResearchManager class
    - cleaned up research item game object class
  * commit `41af2c7` - Fix bug with research
    - fixed research benefits were applied to every quest in every zone
    - updated ResearchManager to reward points instead of ExplorationZone
  * commit `075e90b` - Implement research effects for new locations
  * commit `5dfa1d4` - Implement StartingIncomeRsearch for existing quests
    - added BenefitModifier to ResearchItem
    - implemented BenefitModifier in ConcurrentQuest* and StartingIncomeResearch
    - implemented StartingIncomeResearch in ExplorationZone, currently this only works for existing quests
  * commit `2538333` - Simplify StatModifier class
    - updated ModifierValue to have a public setter
    - changed to auto properties
  * commit `1dc288d` - Update ResearchEffect enum
    - rename enum
    - added prefix to enum options

## Day 32 - 21 Apr 2020
**Time (planned/actual):** 2h / 2.21h
* SMD - weekly review of master plan, annual goals, and sales funnel
* TH - commit `ac4971b` - Refactor ResearchItem text displays for cost/benefit
* TH - commit `d22bd86` - Implement research item for increasing concurrent quests in Plains zone

## Day 31 - 18 Apr 2020
**Time (planned/actual):** 10h / 0.8h
* SMD - planning meeting

## Day 30 - 17 Apr 2020
**Time (planned/actual):** 2h / 2h
* TH - commit `e0620fe` - Implement basic research item displays and leveling
  - created a second research item - ConcurrentQuestsResearch to use for testing
  - research panel now updates based upon the contents of the ResearchManager
  - updated ResearchItem event, ResearchCompleted, to be static
  - enabled clicking on a research item to increase its level, cost, and benefit
* TH - commit `c52e62e` - Enable display of research items
* TH - commit `de3fe69` - Update research panel to display active research tree items

## Day 29 - 11 Apr 2020
**Time (planned/actual):** 11h / 
* SMD - planned my quests for next week
* SMD - reviewed quarterly goals; updated my weekly quests
* SMD - helped my wife setup her [Comfort Creatives Patreon](https://www.patreon.com/ComfortCreatives/posts)/Discord connection
* TH - commit `50399e3` - Display ResearchPanel and improve internal naming 
  - refactored Point Display prefab to display/hide Research panel except for the ones on the panel which currently do nothing
  - renamed folder Quest Display to Location Display
  - renamed folder Quest Zone to Exploration Zone
  - should have renamed the folders as separate commits

## Day 28 - 10 Apr 2020
**Time (planned/actual):** 1h / 0.4h
* SMD - did some bookkeeping

## Day 27 - 7 Apr 2020
I don't count the missing days as I did nothing work related.
**Time (planned/actual):** 1h / 0.4h
* WBD - took Unity's [Editor Scripting](https://learn.unity.com/tutorial/editor-scripting#5c7f8528edbc2a002053b5f6) tutorial

## Day 26 - 2 Apr 2020
**Time (planned/actual):** 2h / 1.1h
I shook off my funk enough to get some work done.

* WBD - edited and posted [Treasure Hunter Devlog 7 - Draggable Windows](http://weirdbearddev.com/2020/04/02/treasure-hunter-devlog-7-draggable-windows/)


## Day 25 - 1 Apr 2020
**Time (planned/actual):** 5h / 0h
My funk continued.

## Day 24 - 31 Mar 2020
**Time (planned/actual):** 2h / 0h
I was in a funk were I felt nervous about releasing my Draggable Windows code and didn't want to write new code.


## Day 23 - 30 Mar 2020
**Time (planned/actual):** 5h / 5.11h
* SMD - did weekly quest and time tracking
* WBD - worked on Draggable Window code for blog
* WBD - wrote TH Devlog 7 - Draggable Windows

## Day 22 - 29 Mar 2020
**Time (planned/actual):** 3h / 0
I had the best intentions to work today and then I ate some peanut butter brownies and sat on the counch watching TV and playing [Idlescape](https://www.idlescape.com/game) and [Melvor Idle](https://melvoridle.com/).

## Day 21 - 28 Mar 2020
**Time (planned/actual):** 10h / 6.8h
* SMD - planned my day to maximize my time
* WBD - researched drag window for next post, having problems with clamping to windows while scaling

## Day 20 - 27 Mar 2020
**Time (planned/actual):** 2h / 1.3h
* WBD - created a [Tumblr account](https://www.tumblr.com/blog/weirdbearddev) and linked it to WordPress

## Day 19 - 26 Mar 2020
**Time (planned/actual):** 5h / 0h
Kerbal Space Program was on sale and had a free trial for the next 3 days.  I've had it on my wishlist for quite some time and decided now was a good time to test it out.  I found the game well made, however, I don't have the time to invent in learning how to play.  Before I could even do basic items I had to take two training courses and even then I consulted the Internet to figure out how to complete two contracts.  If I had a dozen or so free hours a week I could invest in learning the game I would have bought it.  Alas, that's not what I want to focus on.  As it is I spent my time testing the game instead of working on my game.

## Day 18 - 25 Mar 2020
**Time (planned/actual):** 5h / 6.2h
* WBD - edited blog and posted [Planning For More Adventures](http://weirdbearddev.com/2020/03/25/planning-for-more-adventures/)
* SMD - performed mid-week review
* TH - reviewed banner sketch
* WBD - updated MailChimp for WBD branding
* WBD - created MC pop-up (non-modal) and added as WBD widget
* WBD - configed auth WBD domain for MailChimp
* FAFF - organized my Dev Notes Trello board

## Day 17 - 24 Mar 2020
**Time (planned/actual):** 1.5h / 2h
* SMD - weekly review of my Master Plan - including goals and sales funnel
  * Game dev goal: publish at least 3 games this year
    * created itch.io profile - WeirdBeardDev
  * Teaching goal: create a beginner's and intermediate series for C#
    * joined r/csharp and r/learncsharp so I can engage in the communities before I start posting
* WBD - wrote draft blog 'Planning For More Adventures'

## Day 16 - 23 Mar 2020
**Time (planned/actual):** 4h / 4.15h
* General I almost let the night slip away, however, I got off the couch and went to my office and sat down to work.
* WBD - created aliases for my git logs
  * log1 "log --pretty=' commit %x60%h%x60 - %s %n%b' -1"
  * logtoday "log --pretty=' commit %x60%h%x60 - %s %n%b' --since='yesterday'"
* TH - started coding my research tree
  * commit `47df235` - Move ResearchItem to Classes folder 
  * commit `78702aa` - Merge branch origin 'Research' into local Research
  * commit `e2e4376` - Refactor LeveledFloat 
    - streamlined the member variables
    - streamlined the properties
    - refactored CalculateLevel(...)
  * commit `07b2b76` - Refactor LeveledFloat
    - streamlined the member variables
    - streamlined the properties
    - refactored CalculateLevel(...)
  * commit `657b6e2` - Refactor ResearchItem
    - changed ResearchCompleted event to a EventHandler, removing the specialized EventArgs class
    - changed all the setters to protected
    - made several methods virtual so I could override them later
    - added base IncreaseCost() and IncreaseBenefit() methods
  * commit `b185cfa` - Create StartingIncomeResearch class 
    - need a research item for testing
  * commit `e89ee92` - Create basic Research Item game object for testing
  * commit `0f1a39f` - Update Quest Location prefab button to cover progress bar
  * commit `2327193` - Create baseline to start implementing Research


## Day 15 - 22 Mar 2020
**Time (planned/actual):** 2.5h / 2.7h
* SMD - planned my week
* NU - put Etsy store in vacation mode due to COVID-19

## Day 14 - 21 Mar 2020
**Time (planned/actual):** 11h / 0h
* Insomnia the night before messed up my entire day

## Day 13 - 20 Mar 2020
**Time (planned/actual):** 0h / 0.89h 
* TH - creating a LeveledFloat struct (it's a horrible name)

## Day 12 - 19 Mar 2020
**Time (planned/actual):** 3h / 3.2h
* WBD - wrote and published [Implementing IEquatable and IComparable](http://weirdbearddev.com/2020/03/19/implementing-iequatable-and-icomparable/)
* WBD - decided on what I'm posting about next week

## Day 11 - 18 Mar 2020
**Time (planned/actual):** 5h / 0h
* I allowed a long day at my day-job to sucker me into couching it for the night.

## Day 10 - 17 Mar 2020
**Time (planned/actual):** 1h / 0h
* Tuesday night = board game night

## Day 9 - 16 Mar 2020
**Time (planned/actual):** 4h / 5.8h
* WBD - wrote and published [Improving My Coding Practice](http://weirdbearddev.com/2020/03/16/improving-my-coding-practice/)
* TH - fix research window so it stays within the screen
  * commit `f3ce21f` - Fix DragWindow for multiple screen sizes 
    - refactored the IsWindowFullyOnScreen to use world coordinates
    - refactored the ClampToScreen to account for multipile screen sizes by using lossyScale
  * commit `cfdd968` - Fix ResearchPanel blocking GameManager
    - calling the GameManager during OnEnable blocks the static Instance of GameManager

## Day 8 - 15 Mar 2020
**Time (planned/actual):** 6h / 4.3h
* SMD - recorded hours for last week; planned work and time for this week
* SMD - reviewed my master plan for the year; update my sales funnel
* SMD - refined 2020Q2 checklist into real goals and grouped them into months
* TH - hid the Adventurer's and Game Currency sections
* TH - removed the temp sounds from the game
* TH - added resolutions to Game view; researched clamping research panel to screen window
* TH - commits
  * commit `3aed3c6` - Save MainGame file 
  * commit `d21282b` - Remove temp sounds and unneeded areas
    - hid the adventurer's and game currency section
    - turned off the sounds for all encounters

## Day 7 - 14 Mar 2020
**Time (planned/actual):** 6h / 2.7h
* NU - created agenda for tomorrow's meeting
* NU - completed updating hot pad listing; created coaster listing as draft
* TH - reviewed new art work, provided feedback, then incorporated into the game
* TH - created prefab variants for research point displays
* TH - commit `cc7f6bd` - Update research points 
  - added new art work for Caves, Forest, Hills, Lakes, Plains, River, & Swamp
  - created Research Point Display prefab variants
  - added them to the Research window

## Day 6 - 13 Mar 2020
**Time (planned/actual):** 0h / 1.1h
* SMD - committed log for Day 4 & 5
* SMD - created repo for my WBD personal Improvement Challenge and linked it to the template repo
* WBD - updated PFD and HRUUG events for 16 Mar

## Day 5 - 12 Mar 2020
**Time (planned/actual):** 3h / 0h
* Day off

## Day 4 - 11 Mar 2020
**Time (planned/actual):** 5.5h / 6.75h
* TH - reviewed TH banner plan
* WBD - went to test Starship Horizons

## Day 3 - 10 Mar 2020
**Time (planned/actual):** 1h / 1.9h
* WBD - worked on my outline for a series of C# tutorials
* SMD - troubleshot and fixed Wacom issue my wife had

## Day 2 - 9 Mar 2020
**Time (planned/actual):** 1.5h / 2.3h
* NU - added mom's bio to site
* NU - organized local inventory
* TH - commit `74d10e4` - Update ResearchPanel to correctly display available zones 
  - added ResearchPanel to turn on each zone point totals OnEnable and Update
  - added script to the Research Panel gameObject

## Day 1 - 8 Mar 2020
**Time (planned/actual):** 5h / 5.13h
* NU - ran a meeting focused on opening up our Etsy store
* SMD - blocked out my time for the week, and updated my schedule
* SMD - created [Improvement Challenge](https://github.com/WeirdBeardDev/Improvement-Challenge) on GitHub
* WBD - updated [Configuring Git LFS To Use Dropbox](http://weirdbearddev.com/resources/learning/configuring-git-lfs-to-use-dropbox/)
* WBD - reconnected to my MailChimp account
  * cleaned up old SMD audiences
  * converted a few items to WBD
  * started making a list of tasks to fully convert so I can start using MailChimp