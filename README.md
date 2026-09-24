# fullstack-application
Overview: What does your project do?

My project is a React tic-tac-toe game, allowing for scorekeeping, going back in time, restarting games, draws, and resetting scores.

How to run it: What installation and start commands should we use?

You can run by cloning the repository, then installing the dependencies using npm install,a nd then starting with npm start. The program will run at http://localhost:3000.

Your contribution: What did you build or change?

I implemented a function that keeps tracks of wins and displays it on the scoreboard, which can be reset with a button. I also allowed for detection of a draw, which would also be displayed on the scoreboard. I made minor changes to the CSS file to add color to some of the game elements, such as when you hover over a button or one of the squares. 

What you learned: Briefly describe one challenge and how you approached it.

One challenge I faced was figuring out how to
keep track of the score across multiple games.
The original game only tracked the winner of the
current game, so I had to create additional
state to store the number of wins for each
player. I also had to make sure that resetting
the board did not reset the overall score. This
helped me better understand how React state
works and how different components can share and
update information.

References: Credit any tutorials, starters, or other resources you used.
This project was built from the official React tic-tac-toe tutorial (https://react.dev/learn/tutorial-tic-tac-toe).

