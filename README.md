These are some stats based on the equipment polls in Play Meter (available on archive.org) cross-referenced with the games listed on the Killer List of Video Games (https://www.arcade-museum.com/)

Based on photos of the arcade machine's controls available on KLOV, or elsewhere if KLOV didn't have suitable photos, I did my best to categorize the game's controls.

polls.csv identifies each game by an abbreviation and gives each game a rank for each issue of Play Meter I found.

legend.csv ties those abbreviations to specific games, and provides the full name of each game, the manufacturer as listed in Play Meter, and my notes for what style of control the American cabinet has, maybe notes about genre, and sometimes identifies when the Japanese version has different controls.

controlcodes.csv explains codes used in the ContSub column in legend.csv to describe the controls.

handGraphs.txt is R code that I've been using to graph the data contained in these CSV files.

In the Controls column in legend.csv was a simplified pass trying to categorize everything into left, right or symmetrical movement, where ContSub is more precise. (Distinguishing joystick movement from button or tackball movement.)

L = Left movement. Joystick or other movement controls are on the left. This includes games like Asteroids where the rotation is on the left and thrust is on the right, even though you can argue thrust is part of movement.

R = Right movement. Joystick or other movement controls are on the right. 

S = Symmetrical. Joystick with trigger, joystick with no buttons (Pac-Man), or joystick with mirrored buttons on either side (Sinistar)

NA = Not Applicable. Controls where it wouldn't have made sense to place movement on one side. Shooting games with gun controls or driving games with steering wheels, for example.

I tried to include the top ten from the equipment poll, even though Play Meter would sometimes list more than ten. Some issues that were missing could be partially filled in from following issues where they listed the prior rankings of games.
