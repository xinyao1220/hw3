# hw3

What code draws the blades of grass?
line(x, height-10, x+random(-10, 10), height-10-random(h));

What code makes the "lawnmower" come by? How often does it come by?
fill(255);
    rect(0, 0, width, height-15); This makes a white rectangle to cut the grass.
when random()>0.999 ,the lawnmover comes once.

What's the point of the h variable?
The height the blades.

What does the -10 do in the second and fourth arguments of the line function, height-10-random(h)? Why is it there?
In the secong argument Height-10, it draws the root of the blades. In the fourth argumnets, it makes one blade heigher than the root bales, which makes it looks like growing from the ground.
