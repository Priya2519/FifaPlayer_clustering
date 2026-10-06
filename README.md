# FifaPlayer_Clustering

## Problem Statement

### Task 1
- Prepare a complete data analysis report on the given data.

### Task 2
- Explore football skills and cluster football players based on their attributes.

### Task 3
Explore the data and answer the following:

- Prepare a rank ordered list of top 10 countries with most players  
- Identify which countries are producing the most footballers  
- Plot the distribution of overall rating vs age  
- Find the age after which players stop improving  
- Identify which offensive role gets paid the most:
  - Striker  
  - Right Winger  
  - Left Winger  

---

## Dataset Info

FIFA 20 Football is one of the most popular football simulation games by EA Sports.

The dataset includes player data for Career Mode from FIFA 15 to FIFA 20 (players_20.csv).  
It allows comparisons of players across multiple versions.

### Possible Analysis

- Historical comparison between Messi and Ronaldo  
- Budget optimization for building a competitive team  
- Analysis of top % players (e.g., top 5%)  
- Attribute trends like:
  - Agility  
  - Ball Control  
  - Strength  

---

## Domain
*Sports*

---

## Attributes Used in the Project

- *Name*: Player name  
- *Age*: Player age  
- *Height*: Height in inches (converted to cm)  

- *Overall*: Player performance rating (1–99)  
- *Potential*: Maximum future rating (1–99)  

- *PreferredFoot*: Left (0) or Right (1)  
- *WeakFoot*: Skill rating (1–5)  

- *WorkRate*:
  - AttackWorkRate  
  - DefenseWorkRate  
  - Encoded as:
    - Low → 0  
    - Medium → 0.5  
    - High → 1  

- *Position*:
  - Striker (ST, RS, LS)  
  - Forward (CF, RF, LF)  
  - Winger (RW, LW)  

- *Skills*:

  - Crossing: Crossing ability  
  - Finishing: Goal scoring ability  
  - HeadingAccuracy: Heading precision  
  - ShortPassing: Short pass accuracy  
  - LongPassing: Long pass accuracy  
  - Dribbling: Ball control while moving

- *Physical & Speed*:

  - SprintSpeed: Running speed  
  - Acceleration: Speed buildup  
  - Strength: Physical strength  
  - Stamina: Energy endurance  
  - Jumping: Jump ability  

- *Technical Skills*:

  - BallControl 
  - FKAccuracy 
  - ShotPower
  - LongShots 
  - Volleys
  - Curve

- *Mental & Game Intelligence*:

  - Vision
  - Composure
  - Reactions 
  - Positioning

- *Defensive Skills*:

  - Interceptions
  - StandingTackle
  - SlidingTackle
  - Marking
