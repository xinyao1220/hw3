# hw3

1. What code draws the blades of grass?
line(x, height-10, x+random(-10, 10), height-10-random(h));

2. What code makes the "lawnmower" come by? How often does it come by?
fill(255);
    rect(0, 0, width, height-15); This makes a white rectangle to cut the grass.
3. when random()>0.999 ,the lawnmover comes once.

4. What's the point of the h variable?
The height the blades.

5. What does the -10 do in the second and fourth arguments of the line function, height-10-random(h)? Why is it there?
In the secong argument Height-10, it draws the root of the blades. In the fourth argumnets, it makes one blade heigher than the root bales, which makes it looks like growing from the ground.

1. What's the point of an object?
It is used to tracking things and organizing the connections of variables.


2. What's an example of a range you might use for the map function?
Mouse x has a range between 0 and 600 and the backgroung color with the range with 0 and 255. When I want to take the value with range and map it with another range, map function can be used.

3. What line of code would give me a random year in the last century?
var x = random(1901,2000)

