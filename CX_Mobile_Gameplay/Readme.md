# **MOBILE GAME USER ANALYSIS REPORT**  
*(Funnel Analysis + Customer Segmentation Framework)*


## **Executive Summary**  
This report presents two integrated analyses on an anonymized mobile puzzle-builder game. The first is a **funnel analysis** that maps early user progression from first open to monetization, highlighting major drop-off points across onboarding, meta-layer tasks, and core gameplay. The second is a **customer segmentation model** that groups players based on engagement depth, motivational signals, and progression milestones.  
Together, these analyses provide a structured understanding of early-stage user behavior and identify opportunities to improve retention, task pacing, difficulty balance, and monetization readiness.


## **Background**  
Early user experience strongly influences long-term retention and revenue in mobile gaming. New players typically decide within minutes whether they will continue playing, making the onboarding flow, early tasks, and ad experience critical.

For this assessment, anonymized event data from a mobile puzzle-builder game was analyzed. The goal was to evaluate early player behavior, diagnose friction within the first gameplay sessions, and categorize players into behavioral segments that support targeted product and marketing strategy.  

All event counts and behavioral thresholds have been recreated or anonymized.


## **Objective**

### **1. Funnel Analysis Objectives**
- How do players progress through the first stages of gameplay?  
- Where do users drop off, and what causes disengagement?  
- How do early friction points influence retention and monetization?

### **2. Segmentation Objectives**
- What distinct behavioral groups exist among players?  
- How do engagement, motivation, and progression differ across these groups?  
- How can these segments inform targeted retention, content, and monetization strategies?


## **Key Focus Area**

### **Funnel Focus Areas**
- Onboarding clarity and pacing  
- Transition from guided tasks to independent gameplay  
- Motivation through early progression  
- Ad experience and its effect on session continuity  
- Movement toward early monetization triggers

### **Segmentation Focus Areas**
- Engagement depth (frequency, duration, activity rate)  
- Motivational indicators (achievement, creativity, social behavior, reward orientation)  
- Progression depth (levels completed, episodes completed, recovery behavior)  
- Behavioral clustering to guide targeted interventions


## **Data Structure**  
The analysis was completed using an anonymized, summarized dataset representative of typical mobile game analytics.

### **Primary Gameplay Events**
| Event Name | Description |
|------------|-------------|
| `first_open` | First launch after installation |
| `progress` | Tutorial onboarding sequence begins |
| `builder_task` | Early meta-layer tasks requiring earned keys |
| `puzzle_level` | Core puzzle gameplay loop |
| `level_up` | Successful completion of a puzzle level |
| `episode_complete` | Completion of a major milestone |
| `ad_impression` | Viewing an interstitial or rewarded ad |
| `purchase_event` | Monetization event or purchase trigger |

### **Segmentation Data Fields**
- Session frequency  
- Average session duration  
- Puzzle and task play rate  
- Achievement indicators (win rate × retry rate)  
- Creative or social actions  
- Reward-oriented behavior (bonuses, ad rewards)  
- Level milestones and completion patterns  
- Failure-recovery indicators  


## **Insights Deep Dive**

# **A. Funnel Analysis Insights**

### **1. Strong Onboarding Entry but Weak Transition**
Nearly all players who launched the game entered the onboarding flow.  
However, a significant drop occurred immediately after onboarding, driven by:
- Fast tutorial pacing  
- Limited visual/audio guidance  
- Poor clarity on next steps  

This suggests the onboarding experience may overwhelm first-time users.

### **2. High Abandonment in the Builder Layer**
The transition to early builder tasks showed the steepest drop-off.  
Players struggled with:
- Long multi-step tasks  
- Slow early rewards  
- Limited autonomy in choosing tasks  

This created friction and reduced motivation for continued play.


### **3. Lower-Than-Expected Core Gameplay Engagement**
Only a smaller subset reached the puzzle layer, the core loop of the game.  
Key disruptors included:
- Forced long ads after failed attempts  
- Limited retry options  
- Difficulty spikes too early  
- Slow reward pathways  

This prevented players from experiencing the game’s most enjoyable loop.


### **4. Very Low Monetization Readiness**
Only a small fraction reached monetization triggers:
- Rewarded ad engagement  
- Repeated ad events  
- Purchase attempts  

This confirms that players disengaged early, before the game's revenue systems could activate.


# **B. Customer Segmentation Insights**

### **1. Engagement Depth Score (EDS)**  
Measures how actively players participate.  
Includes:
- Session frequency  
- Average session duration  
- Level play rate  

Segments ranged from **Dormant Users** to **Core Champions**.


### **2. Motivation Affinity Index (MAI)**  
Explains *why* players engage.  
Includes:
- Achievement behavior  
- Creative actions  
- Social interactions  
- Reward-oriented behavior  

Segments ranged from **Routine Users** to **Focused Achievers**.


### **3. Progression Score (PS)**  
Measures *how far* players advance.  
Includes:
- Levels completed  
- Episodes completed  
- Failure-recovery behavior  

Segments ranged from **Early-Stage Players** to **Late-Stage Veterans**.


### **Combined 3×3 Segmentation Grid**  
Nine segments were formed based on High/Medium/Low tiers of EDS, MAI, and PS:

- **High Motivation & High Engagement:** Core Champions, Focused Achievers  
- **Mid Motivation & Mid Engagement:** Balanced Regulars, Veteran Decorators  
- **Low Motivation & Low Engagement:** Dormant Users, Routine Users  
- **Mixed Profiles:** Potential Core Starters, Casual Returnees, Habitual Veterans  

Each segment provides targeted opportunities for onboarding, re-engagement, content updates, and monetization strategy.


## **Recommendations**

### **Funnel-Improvement Recommendations**
- Improve onboarding clarity with slower pacing and better guidance.  
- Shorten early tasks and introduce choice to reduce fatigue.  
- Redesign ad experience to reduce repetition and interruption.  
- Rebalance difficulty and rewards to sustain early motivation.

### **Segmentation-Based Recommendations**
- **Core Champions:** Add mastery paths, advanced content, and loyalty rewards.  
- **Mid-Tier Segments:** Use time-limited events, fresh tasks, and varied challenges.  
- **Churn-Risk Segments:** Provide early boosts, simplified tasks, and low-friction gameplay.  
- **Motivation-Driven Players:** Introduce achievement badges, creative features, and social incentives.

These combined actions strengthen the game’s ability to retain, delight, and monetize players across behavioral types.


## **Analysis Resources**
*(All materials fully anonymized prior to use)*  
- Analysis report [link](Mobile_Gameplay_Analysis.pdf) 
- Funnel chart based on cumulative retention (%) [link](Early_Player_Journey_Funnel.xlsx)  
- User journey friction notes [link](First_Time_User_Journey_Notes.pdf) 
- Presentation deck summarizing findings [link](Presentation_Deck_Mobile_Gameplay.pdf) 
