# Task
- collect data about the selected match
- analyze the match using given concepts, methods, and tools
- present the result in a report (dashboard, PDF file, website, TG-channel)

# Examples
[FIFA Training Centre match summary reports](https://www.fifatrainingcentre.com/en/game/tournaments/fcwc/2023/post-match-summary-reports.php)

# 1. Outcomes
### Ideas for report:
- scoring rates at the tournament
- predicted outcome for your match:
  * based on rating before the tournament
  * goal scoring (and conceding) rates for teams
  * pre-tournament betting odds
- hardness of a team's schedule
- simulation vs combinatorics of tournament schedule
- probability of a team winning the tournament

# 2. Running (Nazar)
### Ideas for report:
- estimate velocity, acceleration, curvature
- create heatmaps and trajectories
- ball speed as a proxy for match speed
- trajectory smoothing, simplification, classification
- filter for types of runs
- runs into penalty box, occupation
- check offsides
- create pitch control maps
- space control and creation through movement

# 3. Passing (Ivan)
### Ideas for report:
- reproduce FIFA passing statistics
- passing statistics for various types of passes
- distinguish players and teams by passing motifs
- create passing networks among players and/or zones
- replace grid zones by tactical zones
- identify line-breaking passes and players making them
- compare running characteristics of receivers
- passes that do not slow down the receiver
- passing motifs in time

# 4. Shooting (Oleh)
### Ideas for report:
- generate xG race charts
- what was the probability of the actual outcome
- generate shot maps
- determine alternative shot characteristics
- run different learning algorithms
- evaluate Wyscout xG, postShotXg
- compare different xG models (StatsBomb, Wyscout, yours, others)

# 5. Game Cycle
### Ideas for report:
- possession statistics from Wyscout and FIFA data
- develop your own model for match states
- determine transition probabilities
- determine expected threat (xT) from (variants of) utility potential function
- build ML model for action values
- rank players by action values
- validate action values with outcomes
- classify players and teams by action profiles
- classify matches by state transition profiles
