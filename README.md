This notebook has been a simple example with working on football data.\ I started by summarizing the data and giving insights about the teams, offensively and defensively.\ Then I went to explore the data concerning the players.\ Later, I applied two ML and a DL algorithm to the data:

    The first is an XGBoost model with simple data (input data consists only of the match sides).
    The second model has some added features such as the amount of separate events for each team.
    The third model is a sequence model that takes in account the temporal variation of events inside the match.

The obtained accuracy is not-satisfactory (however the sequence model has a slightly higher accuracy), future work can include using NLP techniques with the event descriptions. Other applications can include whether a sequence of events can lead to goal or not, which I will try in the future.
