# nbaAnalysis
Calculating real expected score
General - based on the shots a team is able to create on offense how many points would you expect them to score. Imagining if this same game was played many times over what would be the average score.
Process:
Take play by play data, and based on whatever shot a team was able to create on a posession, calculate expected point per shot value associated with that shot.
Calculating point per shot:
Always take shooter, and where they shot from, as well as:
1)For jumpshots take distance to closest defender
2)For shots in the paint take nearest defender, but it probably matters who that defender is much more than it would for an outside jumpshot
What needs to be established:
Need enough data per player to show player point-per-shot correlates with spot of shot and distance to nearest defender. 
Check for correlation on if the specific defender has a significant enough impact on point-per-shot in different areas.(Ex. defender matters in paint, but not in mid-range)
Possible Issues:
Posessions with offensive rebounds
Should also find some correlation with fouls to account for a team that is either getting or not getting fouls called.

 
