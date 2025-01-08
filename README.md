
# Soccer Player Performance Analysis

## FIFA Data Visualization README 
*By Shubh Goyal*  

## Introduction  
This project investigates the attributes that define a successful soccer player in various field positions. Using data from the FIFA 19 dataset, we analyze the skills required for different roles—such as forwards, midfielders, and defenders—within a classic 4-3-3 formation. The aim is to explore how skillsets differ across positions and determine which attributes correlate with success.

## Objective  
To identify key attributes that contribute to a soccer player's performance based on their position and to analyze the differences and correlations between these attributes.

## Dataset  
- **Source**: FIFA 19 dataset from [Kaggle](https://www.kaggle.com)  
- **Description**: The dataset includes player attributes such as speed, strength, shooting ability, and positional data.

## Methodology  
1. **Data Segmentation**:  
   The dataset was split into three subsets:  
   - **Forwards**: Left Wingers (LW), Right Wingers (RW), and Strikers (ST).  
   - **Midfielders**: Central (CM), Left (LM), and Right (RM).  
   - **Defenders**: Center Backs (CB), Left Backs (LB), and Right Backs (RB).  

2. **Selected Attributes**:  
   Seven essential attributes were analyzed for all positions:  
   - **Finishing**: Scoring ability from strong opportunities.  
   - **Shot Power**: Strength behind shots.  
   - **Interceptions**: Skill in disrupting opposing plays.  
   - **Sprint Speed**: Speed during runs.  
   - **Strength**: Physical robustness.  
   - **Dribbling**: Ball control and maneuverability.  
   - **Marking**: Ability to stay with assigned opposing players.  

3. **Analysis Tools**:  
   - Visualized data through **bar charts** and **correlation matrices**.  
   - Compared mean attribute ratings across player positions to identify trends.  

## Key Insights  
### 1. Positional Differences  
- **Forwards**: Excel in on-ball skills like **finishing**, **shot power**, and **dribbling**, essential for goal-scoring.  
- **Defenders**: Focus on off-ball skills such as **interceptions**, **strength**, and **marking**, which are crucial for regaining possession.  
- **Midfielders**: Serve as a balance between forwards and defenders, excelling in both offensive and defensive attributes.  

### 2. Attribute Correlations  
- Strong correlations were observed between certain skills, such as:  
  - **Finishing** and **Shot Power**, where increased shot power improves scoring ability.  
- Weak or no correlations were found between unrelated attributes, such as **Finishing** and **Interceptions**.  

## Conclusion  
This project highlights the differences in skill requirements across soccer positions:  
- **Attacking positions** benefit from technical skills such as **dribbling** and **finishing**.  
- **Defensive positions** rely on physical robustness and tactical skills like **marking** and **interceptions**.  

Additionally, the analysis revealed correlations between some attributes, showing how improving one skill can indirectly enhance another.  

### Future Work  
- Expand the study to analyze variations within midfield roles, such as Central Attacking Midfielder (CAM) or Central Defensive Midfielder (CDM).  
- Investigate how these attributes affect team performance and win rates.
