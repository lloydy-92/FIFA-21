## 1) What is the relationship between rating and potential, and is there a siginifant difference between the two between younger and older players?
<img width="562" height="455" alt="image" src="https://github.com/user-attachments/assets/19e85a8e-047f-492e-a63d-378a93f2966f" />

Mann-Whitney U: P-value: 0.0000<br/>

Looking at Figure 1, it is clear to see that most players with high potential ratings are that of a younger age, with the majority of these players having relatively lower current ratings. On the contrary, older players follow an almost 1-to-1 relationship between their current rating and their potential. These results are to be expected, as a player younger in age has more of his career ahead of him, and a lower rated player has more room to grow and attain a higher rating, and so can become better as time goes on. Older players however have less room for improvement because they could have already hit their peak at a certain age when they were younger, and so do not have much more of their career left to further improve their abilities and therefore increase their rating. These conclusions are further backed up by the P-value of 0.0000 from the performed Mann-Whitney U test, indicating that the difference between current and potential rating is indeed significant between younger and older players.

## 2) What is the rating distribution and variance among positions?
<img width="1489" height="820" alt="image" src="https://github.com/user-attachments/assets/4c60ca50-3cf6-404f-a30b-d624e4fa10cd" />

<img width="1489" height="820" alt="image" src="https://github.com/user-attachments/assets/9d0cd121-ffdd-4a43-b67b-94385ddf3da5" /><br/>

**Table 1: Average Player rating by position**
| general_position | mean_rating | median_rating |
|------------------|-------------|---------------|
| Attacker | 67.774307 | 67.0 |
| Midfielder | 67.383129 | 67.0 |
| Defender | 67.125428 | 67.0 |
| Goalkeeper | 66.565817 | 66.0 |
| All-rounder | 67.189231 | 67.0 |<br/>

**Table 2: Average player ratings by position (top rated players only)**
| general_position | mean_rating | median_rating |
|------------------|-------------|---------------|
| Attacker | 83.060000 | 82.0 |
| Midfielder | 82.371795 | 82.0 |
| Defender | 82.400000 | 82.0 |
| Goalkeeper | 82.861111 | 82.0 |
| All-rounder | 81.974359 | 82.0 |

Looking at Figure 2 reveals that there is not a significant amount of variance between the distribution of player ratings for each position, with all plots being right-skewed peaking at around 67 in rating. Interestingly, goalkeepers appear to have a slightly higher proportion of their players at the very lower end, around 60 rated and below, which could indeed bring the overall average down. As it turns out, this is what happens, as shown by Table 1, where goalkeepers have the lowest mean rating, the only one to be below 67, and has a median of 66 rather than 66 like the other positions. The abundance of lower rated goalkeepers could be for a few reasons, such as fewer world-class goalkeepers being available globally, and the fact that many teams and squads only tend to use a single goalkeeper for a whole season, but with backup and youth keepers who rarely play if at all, which can significantly skew the average downwards.
Figure 3 however reveals that attackers have the highest proportion of their players rated at 80 and above compared to the other positions. Whilst other positions have some players within this region rated at 90 and then none beyond that, attackers have the most (proportionally) at 90 and some even higher still. This could in turn bring the average rating up for attackers, which is what is seen in both Tables 1 and 2, with attackers having the highest mean rating out of all the positions. The higher proportion of high-rated attackers could be due to the fact that an attacker's skills and talent is often the focus of scouting, media attention, and their performance metric, such as goals, assists, etc. This, paired with clubs tending to invest heavily in strong attacking talent, means that elite performances stand out more and are rated higher, making higher rated attackers more common.

## 3) What is the age distribution and variance among positions?
<img width="1489" height="820" alt="image" src="https://github.com/user-attachments/assets/190a78c2-d78f-4188-acfc-4e2dc7eb1d0d" /><br/>

**Table 3: Average player age by position**
| general_position | mean_rating | median_age |
|------------------|-------------|---------------|
| Attacker | 26.033285 | 26.0 |
| Midfielder | 25.835621 | 25.0 |
| Defender | 26.529986 | 826.0 |
| Goalkeeper | 27.725584 | 27.0 |
| All-rounder | 26.040000 | 26.0 |

Unlike with rating, Figure 4 shows that there is more significant variance in distribution of player ages between positions. For example, whilst all positions show an average/peak age of 25, this peak appears to occurs beforehand for midfielders and goalkeepers, the former of which being backed up by Table 3 where midfielders have the lowest mean and median ages of all the positions.
However, looking at Figure 4 once more reveals that goalkeepers have the highest proportion of players aged 30 and above, which is also supported by Table 3 where goalkeepers appear to have the highest mean and median age. This could be due to the unique physical and mental demands of a goalkeepers position on the pitch, where they in theory do not experience as much physical exertion as outfield players, leading to less injuries and long-term exhaustion over time, and so longer playing careers. Goalkeepers also tend to develop a better understanding of football, such as reading plays and effective positioning. For this reason, many clubs choose their main goalkeeper to be their captain, due to the time spent in such a position where they can develop lots of skills and experience that would fit such a role.
Figure 4 also shows that attackers and defenders do not have a certain one peak age for that role, but rather a broader spectrum between ages 20-30. In contrast, the focused peak point of midfielders and sharper drop off with age for all-rounders for example suggests that their effectiveness may peak at a more defined point in their careers — likely due to the high physical and tactical demands required in those roles.
