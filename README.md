# Greed Dice Game

A multiplayer dice game where players roll five dice to accumulate points. The first player to reach 3000 points triggers a final round where all other players get one last turn.

## Game Rules

- Players must score at least 300 points in a single turn to start tracking their score
- Once a player reaches 3000 points, all other players get one final turn
- Players can choose to re-roll non-scoring dice to potentially increase their turn score

### Scoring
- Three 1s = 1000 points
- Three of any other number = number × 100 points
- Single 1 = 100 points  
- Single 5 = 50 points
- All other dice score 0 points

## Running the Game

```bash
ruby start_game.rb
```

## Running Tests

```bash
gem install rspec
rspec game_spec.rb
```

## Files

- `dice_set.rb` - Handles dice rolling
- `score.rb` - Calculates scores from dice combinations
- `player.rb` - Manages player state and scoring
- `game.rb` - Main game logic and turn management
- `start_game.rb` - Entry point to start the game
- `game_spec.rb` - Test specifications


