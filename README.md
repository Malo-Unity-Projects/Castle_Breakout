# Castle_Breakout

Castle Breakout is a a 3D roguelike coop multiplayer topdown game I made to learn to make a multiplayer Unity game.
I used Playfab to manage the friends system, and Photon Unity Network for the multiplayer.

Once logged in, players can see their list of friends, and add new ones. They can chat with them, and invite them in their team.
When a team is formed, the team leader can start the game. Alternately, the game can be played alone.

The goal of the game is for players to reach the exit of the castle, while avoiding the enemies within it.
There is currently only 1 spawn, but the game randomly selects a spawn within the list of existing ones, so on the long term, more rooms will be added to the game.
One each zone, there can be multiple points at which players can change zone by pressing 'E'. If in a team, players cannot change zone until all players are at the point.
