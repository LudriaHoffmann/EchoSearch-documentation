# EchoSearch-documentation
EchoSearch is a client-side analysis tool that helps users observe and follow the presence of a specific player(s) of interest within an online server environment.

It operates entirely on the local client, analyzing publicly visible, in-session information that the client already receives during normal gameplay or interaction.

# Purpose
An Echo is a single observable instance of the subject, such as:
- Appearing in a player list
- Seeing a known display name active

# Identifying 
"A Quiet Window" is a time period where historical data shows a low probability of the user(s) being online.
These are calculated using:
- Observation density
- Time-of-day weighting
- Rolling averages
- Long-term vs short-term trends

# Visualization
EchoSearch generates local-only plots, such as:
- Hour-of-day activity graphs
- Day-of-week heatmaps
- Presence density timelines
- Highlighted low-activity zones

Visualizations are intended to be interpretive aids, not absolute predictors.

# Output
EchoSearch provides local-only insights, such as:
- Encounter timelines
- Reappearance indicators
- Confidence estimates for correlations
- Session-based summaries
