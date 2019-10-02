# Ants-Game
<p>A game of Ants Vs. SomeBees consists of a series of turns. In each turn, new bees may enter the ant colony. Then, new ants are placed to defend their colony. Finally, all insects (ants, then bees) take individual actions. Bees either try to move toward the end of the tunnel or sting ants in their way. Ants perform a different action depending on their type, such as collecting more food, or throwing leaves at the bees. The game ends either when a bee reaches the ant queen (you lose), or the entire bee fleet has been vanquished (you win).</p>
<br>
<p>I implemented the back end of this game, writing classes(<a href="https://github.com/jiangdada1221/Ants-Game/blob/master/ants.py">ants.py</a>) for all the ants in the game</p>

<img src="http://m.qpic.cn/psb?/V13cnQO90zNVhL/te5*lJ6xlfAX07ZVA4c1S5JVOeFDksUrD*qPj7oud7c!/b/dL8AAAAAAAAA&bo=mgc4BAAAAAARB5E!&rf=viewer_4">

<h4>Ant's Description</h4>
<li>HarvesterAnt:adds one food in each turn</li>
<li>ThrowerAnt:attack bees in its location</li>
<li>ShortThrower:only attacks a Bee that is found after following at most 3 spaces</li>
<li>LongThrower:only attacks a Bee that is found after following at least 5 spaces</li>
<li>FireAnt:damages all the bees in the same place as itself when it dies</li>
<li>HungryAnt:select a random Bee from its place and eat it whole</li>
<li>NinjaAnt:damages all Bees that pass by, but can never be stung</li>
<li>WallrAnt:serves as a wall to withdraw attacks</li>
<li>TankAnt:protects an ant in its place and also deals 1 damage to all bees in its place each turn</li>
<li>QueenAnt:doubles the damage of all the ants behind her each time she performs an action</li>

<h4>How to play?</h4>
<p>Clone the repository and type in terminal: "python3 gui.py"</p>

