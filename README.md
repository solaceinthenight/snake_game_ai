# snake_game_ai

AI playing the classic Snake game and improving with reinforcement learning (Deep Q-Learning).


Followed tutorials from Python Engineer on YouTube

CREDIT:
- [GitHub](https://github.com/python-engineer/snake-ai-pytorch)
- [YouTube Playlist](https://youtube.com/playlist?list=PLqnslRFeH2UrDh7vUmJ60YrmWd64mTTKV)

## Remarks

### Observations
- 0 games: SnakeAI runs into walls and itself
- 25 games: No progress
- 50 games: No progress (High Score = 3)
- 80 games: SnakeAI starts finding fruit more consistently (High Score = 20)
- 89 games: Significant progress related to SnakeAI's searching algorithm (High Score = 51)
- 300 games: No significant progress (High Score = 64)

### Problems/Limitations
- After 100 games, SnakeAI fails to die to wall boundary; however, SnakeAI runs into itself
- After 300 games, SnakeAI has yet to improve: still runs into itself.


## Files
agent.py: AI playing Snake

arial.ttf: Arial font for PyGame

game.py: Classic Snake game (PyGame)

helper.py: Graph displaying score over number of games (MatPlotLib)

model.py: Traininig model for AI (PyTorch)
