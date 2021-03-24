
### Tetris AI

A JavaScript implementation of Tetris with a AI that learned to play the game by itself using an evolutionary algorithm. You can access it here: https://sorting-visualization-vivian.netlify.app/

The AI uses following parameters to determine the best position to place the next piece. 
 * Height- The AI would want to minimize the height because this means you can place more pieces.
 * Holes- The AI would also want to minimize the number of holes because a hale makes the line harder to clear.
 * Cleared- The AI want to maximize the number of cleared lines.
 * Bumpiness- The AI want to minimize bumpiness because a flatter board makes it easier to clear lines.
 * Vacant- The AI want to minimize the number of vacant spots under where your piece is placed
because it makes it harder to clear the tiles below where your piece is placed.

### Screenshots
<img width="682" alt="tetris" src="https://user-images.githubusercontent.com/33815743/112341806-1c247100-8c98-11eb-8fa6-074e0f4f107e.png">


### Sources that helped me make this
* https://codemyroad.wordpress.com/2013/04/14/tetris-ai-the-near-perfect-player/
* https://towardsdatascience.com/introduction-to-genetic-algorithms-including-example-code-e396e98d8bf3
