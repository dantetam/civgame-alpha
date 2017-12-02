## Civgame Archive

** I developed this world-building strategy game based off of Civilization 4 and 5 during my spare class time in high school. It features a procedurally generated terrain which forms the basis of an empire-centric world. The world features a full technology tree, AI opponents who fight and build up themselves, and the player's user interface. I was most proud of this because it revealed an intelligent, passionate work ethic within me. This still remains one of my largest projects,but not necessarily one of the most well-built. For a high school dev, this was ridiculously large and intricate, and rivaled the projectsof actual working software developers. I keep this up as an archive and a bit of my CS development history. **

A 4X civilization-style turn based strategy written in pure Java with Processing for rendering
<s>14,000+ lines as of 12/15/2014</s>
17,000+ lines as of 2/17/2015

This game is in deep alpha. Expect lots of bugs, crashes, and general inconvenience.

Instructions for those familiar with Eclipse

Make a new project from source, which is cloned down from github.

Instructions for those who aren't

1. Download Eclipse (https://eclipse.org/downloads/packages/eclipse-ide-java-developers/lunasr1a) and store it in a folder you can reach.

2. Run the eclipse purple ball application.

3. It will prompt you for a workspace folder; remember this location.

4. Go into git and clone the project down directly into the workspace (git clone https://github.com/dantetam/civgame.git).

5. Go to File > New > Java Project and it'll prompt you for a project name. Copy my project name exactly (it's the name of the cloned folder); it'll say "the wizard will configure the project automatically" or something like that. Create the project.

6. In the left side, the project will show up. Double click on it, then src > render > Game.java.

7. Run the project as an application by going to the Toolbar > Run > Run As > Java Application.

8. Have fun. There's a tutorial for the game.

Priorities:
Balance game to make it playable by average 4X player;
Update graphics (render terrain textures, polish UI);
Document and refactor code;
Exposure (???);