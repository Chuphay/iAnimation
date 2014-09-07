Simple example to draw a line going diagonally down the screen:

```
from iAnimation import iAnimation
def y(x):
    return [x[0]+0.1,x[1]+0.1]

screen = iAnimation()
screen.next_position(y)
screen.animate(init = [2,1], clear_screen = False)
```


        
    

            
