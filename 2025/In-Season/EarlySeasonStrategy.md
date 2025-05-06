<div>
<div align="center">
<h1><span style="color:#bf5700">Early Season Strat</span></h1>
</div>

This post outlines our early season thoughts on what robots will do, potential robot archetypes, and what our robot will do

<div>
<div align="left">
<h2><span style="color:#bf5700">What robots will do</span></h2>
</div>

Purpose: List things that we think that robots will do
- Score coral
    - L1
    - L2/L3
    - L4
- Scoring coral and removing algae
- Using reef to align to score coral
- Climb on deep cage
- Climb on shallow cage
- Causing penalty driving through barge area
- Acquire coral from the ground
- Acquire algae from the ground
- Acquire coral from the coral station
- Acquire pre-staged algae / coral
    - Also acquire opponent’s pre-staged algae / coral
- Score algae into alliance processor
- Score algae into opponent processor
- Score algae into barge net
    - From our zone
    - From opponent zone
- Buddy climb on cages?
- Stabilize cages
- ~~Destabilize cages?~~  (probably not)
- Swing cage into another robot to gain Barge RP
- Transporting coral for alliance partners
- Remove algae from reef
    - In control
    - Free
        - Shoot coral to remove algae?
- Remove algae from opponent's reef (carefully!)
- Pushing algae or coral
- Receive coral from an alliance partner
- Launch algae across field
- Defense
    - Preventing general opponent movement
    - Prevent acquiring coral from coral station
    - Be a wall – prevent shooting algae
    - Prevent access to our side of field without a penalty
    - Prevent access to opponent processor
- Draw a penalty by touching a robot while in barge zone
- Draw a penalty by touching a robot in our reef zone
- Climb on reef on to score coral higher?
- Not move
- Die in or near protected zones
- Pushing an alliance partner
    - To park in barge zone
    - To move off of starting zone
    - Out of the way
- ~~Disruptive auto~~ – major foul for touching robots
- Disrupt in early teleop
- Use LEDs to communicate with drive team
- Use cameras and AprilTags for localization/alignment
- Bulldoze through dropped Coral
- Get hit with a swinging deep cage
- Get hit with a missed Algae shot
- Leave starting line during Auto
- Hold Algae externally while transporting it

<hr>

<div>
<div align="left">
<h2><span style="color:#bf5700">Potential Robot Archetypes</span></h2>
</div>

### Purpose
- List examples of robots to execute specific game strategies
- Focus on robot capabilities, not much on mechanisms
- Trying to build a robot that does everything will probably lead to failure
- Think broadly, and not too deep -- we want diverse ideas!
- Things to think about:
    - What does the robot need to do in auto?  (programs? sensors? tasks?)
    - How does the robot interact with game pieces?
    - What attributes are needed (robust, speed, power, agility, etc)?

## The Robots

### Magic Carpet

**Description:**
- Just a magic carpet, the brave little toaster, the andymark chassis

**Pros:**
  - Moves
  - Could play defense

**Cons:**
   - Doesn’t score game pieces (maybe an algae)
   
### Coral Cycler

**Description:**
    - Stays on one side and cycles coral only
    
**Pros:**
   - Gets the Coral RP
   - Fast
    
**Cons:**
   - Parks, but does not climb
   - One Trick Pony
 
### Algae Cycler

**Description:**
  - Just cycles algae (to processor – maybe into net)
  - Can de-algaefy the reef
    
**Pros:**
  - Scores algae
  - Coopertition Bonus
   - Free up the reef for Coral
    
**Cons:**
   - One trick pony
   - No climb
   - Might run out of algae

### The Wall

**Description:**
   - Deploys wide and high to block human player shots especially
   - Might be able to score algae into processor
   
**Pros:**
   - Prevents 4-point from HP after 6-point processor score
   - Could potentially re-score missed Algae
    
**Cons:**
   - Limited flexibility
   - Might be top-heavy
   - Might run out of algae to defend against
   - Might not actually be able to get between human player and barge net
   - Might take a lot of time just to do nothing
   - Touching the net by accident would be a major foul

### RP Bot

 **Description:**
   - Can score 2 Algae into Processor for Coopertition, but barely
   - Can shore Coral onto the Reef, though not the best
   - Can deep climb
    
**Pros:**
   - Does just enough for Coral RP 
   - Doesn’t need to dealgaefy reef
    
**Cons:**
   - Needs to be able to do L4
   - Not great by itself – needs help to secure the win
   - Complexity of deep climbing
   - Each RP is just ⅓ of a win, not ½
   - RP is not a benefit in playoffs 

### KitBot

**Description:**
   - The Kit Bot
    
**Pros:**
   - Can score on L1
   - Lots of coral can fit on L1
   
**Cons:**
   - No swerve
   - Can’t score on other levels
   - Can’t manipulate algae (without modification)

### Hopper Bot (not Marie)
    
**Description:**
   - Receives coral from KitBot
    
**Pros:**
   - Let’s the KitBot do most of the cycling; score on Coral more quickly
   - Can score L2-L4 when paired with KitBot
    
**Cons:**
   - Capability wasted when not paired with non-KitBot

### Defense Bot
    
**Description:**
   - Goes to other side of the field to slow down opponent offense
   - Maybe could dealgaefy the opponent reef and bring algae across field
   - Strong & robust for defense
    
**Pros:**
   - Points are comparative - if they can’t score, they can’t win
   - Can give alliance more algae to score

**Cons:**
   - Cannot score itself

### Coral Front & Back
    
**Description:**
   - Can intake Coral from opposite site of scoring on reef
   - Can be fed Coral from Coral Station without needing to travel all the way to Coral Station
    
**Pros:**
   - Cuts down on cycle times by removing distance to travel
   - Doesn’t rule out also scoring algae
    
**Cons:**
   - Complexity and maintenance

### The California Powerhouse Bot (hi citrus)
    
**Description:**
   - Does everything
    
**Pros:**
   - No limitations
    
**Cons:**
   - You’ve gotta be one of those teams to pull it off

### The Annoying Bot
    
**Description:**
   - Wide
   - Gets in front of a Coral Station (or processor) and denies access
    
**Pros:**
   - Can shut down a Coral Station completely (or processor)
 
**Cons:**
   - There are two Coral Stations
   - Cannot score points itself
   - Needs to survive contact with deep cages

### The Shooter Bot
    
**Description:**
   - Shoots coral onto the reef
  
**Pros:**
   - Doesn’t need to move around reef to score on other branches
   - Points for EI
    
**Cons:**
   - Complexity / reliability of shooting from distance

### The Climbing Bot
    
**Description:**
   - Focused on ensuring the deep cage climb
   - Might push algae around a bit, but put most development effort into climb
    
**Pros:**
   - Always gets the Barge RP
    
**Cons:**
   - Does little otherwise to contribute to offense

### Do Everything Bot
    
**Description:**
   - Does a little bit of everything but doesn't do it well 
    
**Pros:**
   - Versatile
   - May help with RP
    
**Cons:**
   - Inefficient

<hr>

<div>
<div align="left">
<h2><span style="color:#bf5700">What our robot will do</span></h2>
</div>

### Our Robot Will
Purpose: Things our robot will do, not necessarily week 1, but eventually will do
- Be only as complex as absolutely necessary
- Have a low center of gravity / be stable
- Be robust – especially from potential Cage damage
- Have bumpers that can be quickly installed between matches
- Play in every match
- Be flexible enough to work with different alliance partners
- Automate tasks to provide simple controls to driver(s)
- Use LEDs effectively to communicate status to drive team
- Be able to remove Algae from the Reef
- Able to score Coral on all levels of the Reef
- Scores reliably and quickly on L2-L4 of the Reef
- Can score 15 Coral on L2-L4 of the Reef in a match
- Score 3 Coral in Auto
- Pick up Coral from the Coral Station in less than ½ second
- Obtain Coral while being defended
- Deep Cage climb

### Stretch goals
Purpose: Goals that we aren't as focused on, but if it falls in our lap or we've completed the will list, we will go for
- Ground intake of Algae
- Able to score at least two Algae in the Processor
- Maintain possession of Algae when removing from the Reef
- Possess both Coral and Algae simultaneously
- Score reliably on L1 of the Reef
- Can score 20 Coral on the Reef in a match (solo Coral RP)

### Non-goals
- Climb on the Shallow Cage
- Score Algae into the Barge net
- Intake Coral from the ground

