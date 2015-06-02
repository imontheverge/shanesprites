for velocity of swipes


       //to make the swipe more responsive at lower speeds, and less at higher
 
       //(current velocity) = too dumb to find what you set it as) 

       //swipe left       

game.player.velocity.y += 5f - (current velocity * 0.5)

max y 10

max grav. -2

0 then acc. is 5

5 then acc. is 5 - (5 * 0.5) = 2.5

7.5 then acc is 5 -(7.5 * 0.5) = 1.25

8.75 then acc. is 5-(8.75 * 0.5) =  0.625

9.375 then acc. is 5-(9.375 * .05) = 0.3125

floor
camera
backgroud
clouds/forground