Rock Paper Scissors Trainer Kata
=================================
As a Rock Paper Scissors champion, I want to play against a clever bot in a fun
and intuitive UI so that I can work on my game.

Rules:
------
* Paper beats rock.
* Rock beats scissors.
* Scissors beat paper.
* I should be able to play with this on a mobile device.

Features:
---------
* I want a nice animation of our choices being pitted against each other and
  only one emerging as the victor.
    * The animation should be fast enough to let me keep playing the game, but
      pretty enough to make it visually appealing.  Something should bounce.
      Bouncy bouncy.
* I want a graph of my winning percentage over time that updates every game.
* I want updating graphs of the totals of the choices each player has made.
* I want to cheat sometimes.  Give me a way to see what the bot is thinking.

Suggestions:
------------
* Use Markov chains for prediction
* Allow the user to switch algorithms (or have the bot switch algorithms on the
  fly)
* Count winning (and losing) streaks; keep high scores for each
