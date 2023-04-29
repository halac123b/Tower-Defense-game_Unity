# Tower-Defense-game_Unity
A simple Tower Defense game prototype where enemy can find path automatically through BFS.<br>

<p>Sequential enemy waves try to reach your home and steal your money, you should put your archer tower (cost money, too) to eliminate them. Enemy will become more difficult to kill over time.</p>
<p>Put tower on your enemy path will block them and make them have to find another path, make use of this function. But you can't block all feasible paths (at least one path still exist).</p>
<p>Press C to toggle coordinates of tiles on grid map.</p>
<br>
<p>Through this project, I learn about:</p>
<ul>
  <li>Create a grid board map, made from tiles with their own coordinate.</li>
  <li>Use collision particle effect as projectile.</li>
  <li>Use Object Pool to control enemy waves, without Instantiate in runtime, enhance performance.</li>
  <li>Use BFS algorithm to find optimal path, and make enemy follow that path, auto update new path when current path is blocked.</li>
  <li>Script Execution Order setting in Unity.</li>
</ul>

<img src="capture.gif">

<!-- Thanks to Udemy course of Gamedev.tv -->
