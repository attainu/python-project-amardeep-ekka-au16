# Snakes And Ladders

The aim of this project is to play text-based snake and ladder game in the
terminal However, it is a fun thing to do for a beginner in order to learn how to
use multiple concepts in your program.

## Table Of Contents

```
❖ Snakes And Ladders
● Table Of Contents
● Technologies
● Requirements
● Setup
● What happens in game
● Contributing
● some code

```

## Technologies

```
● Python : 3.8.2
● Flake8(for linting)

```

## Requirements

```
● Use of Random function, sys function, time function
● Conditional Statements, Dictionaries, oops concept

```

## Setup

```
To run this project
● Clone the repo
● Install python
● Install flake8 library :
➢ Pip install flake8
➢ Go to root file
➢ Run python -m flake8 command and check for any errors
● Import all the library functions required

```

## What happens in Game

```
1- Display the welcome message
2- Collect the player's names
3- Until one of the player wins do the following
3.1- Roll the dice
3.2- Move the player forward for the value got on the dice roll.
3.3- If the player is on snake's head, move down to its tail
3.4- If the player is on ladder's bottom, take it to its top
3.5- else remain there and let the second player roll the dice

```

## Contributing

```
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

```

## some code

```
def get_dice_value(self):
    time.sleep(SLEEP_BETWEEN_ACTIONS)
    self.dice_value = random.randint(1, DICE_FACE)
    print("Its a " + str(self.dice_value))
    return self.dice_value
```

```
def check_win(self, player_name, position):
    time.sleep(SLEEP_BETWEEN_ACTIONS)
    if MAX_VAL == position:
        print("\n\n\nThats it.\n\n" + player_name + " won the game.")
        print("Congratulations " + player_name)
        print("\nThank you for playing the game.\n\n")
        sys.exit(1)
etc....,

```
