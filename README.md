# maze-game
html/js app showing off maze creating and solving algorithms.


if you want to try the app without setting up a server, you can use the nomodule version by opening its index as a file in browser.

<details>
<summary><h2>Blazor Usage</h2></summary>
  <h4>Add Submodule</h4>
Navigate to the project's folder where you would like to use <i>maze-game-blazor</i> and open a terminal
<ul>
  <li><code>git submodule add https://github.com/mjliepke/maze-game-blazor.git</code></li>
  <li><code>git submodule init</code></li>
</ul>
    <h4>Usage</h4>
<p>Now, copy <strong>maze-game-razor/razor-maze/maze.js</strong> to your <strong>wwwroot/js</strong> folder</p>
<p>Finally, in your <i>_Host.razor</i> file in the <code>body</code> add the following line:</p>
<code><script src="js/maze.js"></script></code>
<p>Now, you are ready to refer to your <code>Maze.razor</code> component in your Blazor project</p>
</details>
