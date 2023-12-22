### Finding Breakout Wide Receivers in Fantasy Football

<u>Project Aim</u>
Fantasy football has become one of the most popular products of the National Football League (NFL) over the past twenty years. Typical fantasy leagues feature 12 teams/managers with 16 rounds in the draft. Finding players with higher upside (who will score more than expected) in the draft's middle rounds is one of many possible ways to build a successful fantasy roster. This project adopts this approach and attempts to identify which wide receivers (position of player) for the 2023-2024 NFL season have the potential of outscoring their ADP. Such players will be called breakout wide receivers. For this project, breakout wide receiver will be defined as any wide receiver with an ADP in rounds 6-9 (12 team league; pick #: 60-108) who outscores their projected fantasy points per game by ‘X’ number of points. A simple linear regression model will be created to identify breakout wide receivers using data from the NFL's past ten years (2013-2022). Insights gained from that model will be then applied to the 2023 data to identify potential breakout wide receivers for the 2023-2024 fantasy football season.

To run project:

1. Clone this repository.
2. Create virtual environment to install dependencies for project.
3. Install the requirements found in `requirements.txt` using `pip install -r requirements.txt`.
4. Open the jupyter notebook /src/breakout_wr_fantasy_football_2023.ipynb
5. Run cells one at a time to follow along.
6. For further insight into the code and project results, open the pdf /results/bo_wr_2023.pdf

Explanation of getting the data, cleaning the data, running the analysis code, and producing visuals is explained through comments in breakout_wr_fantasy_football_2023.ipynb
Note that most of the commented out code in the notebook are to prevent saving over the previously saved csv and png files (data and data visualizations respectively).
