---
layout: post
title: "Flag Project - Final Submission"
date: 2018-12-21
---
 
## Flag of United kingdom/Union jack  by Ethan Rodgers

## Describe your program

I designed Union jack flag for the UK. The flag it self wasn't to complicated it was made up of multiple layers of rectangles, it was more of an annoying and teatious process. In my opion t believe i will get a apprentice level flag, this is due to the process of me making the flag and my lateness 


## Current output



* * *
![Flag](/images/final-flag.png)
* * *

## Describe your process.

one particular comment from my teacher made the process of the flag alot easier, he told me instead of making my background for the flag a white rectangle followed by blue triangles and crosses i should start with a blue rectangle making it so i only need to add the crosses. Not only that but one of my peers showed me how to rotate my shapes allowing me to program diaginal crossing rectanles, this made the process of a whole lot easier.


## Explain your code.

size = 300,  makes size worth 300 which allows it to be used in place of 300

height = size * 1, height takes the size function and multiples it by one, its unnessary but is apart of the flag ratio its also used in place of numbers making the process of trying to find the right number for a function simpler. function are slightly easier. 
width = size * 2, width which takes the size fuction and multiply it by two and it put into a function in place of numbers like the height function. function are slightly easier. 
smite = size / 6, smite takes size and divides it diving you 1/6 of 300 in this case, it works the same as height and width and in some cases replaes one in a function. function are slightly easier. 
stripe = size / 4 stripe tkaes size and divides it giving you 1/4 of whatever size is worth,  it works the same as height and width and in some cases replaes one in a function. function are slightly easier.

* * *
br = rectangle(width,height,"solid","navy") gives me a navy blue rectangle the backgroung of my shape and in the flag appears as 8 different triangles
wr = rectangle(700,stripe,"solid","white") gives me a white rectangle which i used to make the first layer of my flag which is the x cross 
rw = rectangle(stripe,700,"solid","white") gives me a white rectangle which i used to make the second layer of my flag which is the x cross 
yr = rectangle(less-height,300,"solid","red") i used this red rectangle to make each small rectangle on the sides of the white rectangle for the third to sixth layer
xr = rectangle(350,less-height,"solid","red")i used this red rectangle to make each small rectangle on the sides of the white rectangle for the third to sixth layer
Wr = rectangle(width,stripe,"solid","white") white rectangle used for the second cross on the seventh layer of the flag
Rw = rectangle(width,stripe,"solid","white")white rectangle used for the second cross on the eighth layer of the flag
rr = rectangle(380,less-height,"solid","red")i used this red rectangle to make each small rectangle on the sides of the white rectangle for the third to sixth layer
Rr = rectangle(less-height,400, "solid","red")i used this red rectangle to make each small rectangle on the sides of the white rectangle for the third to sixth layer
mr = rectangle(width,smite, "solid","red") white rectangle used for the third cross on the ninth layer of the flag 
rm = rectangle(width,smite, "solid","red") white rectangle used for the third cross on the last layer of the flag



* * *



## Program code

include image

size= 300

height = size * 1
width = size * 2
smite = size / 6
stripe = height / 4
stripe-height = height / 8
less-height = height  / 12





br = rectangle(width,height,"solid","navy")
wr = rectangle(700,stripe,"solid","white")
rw = rectangle(stripe,700,"solid","white")
yr = rectangle(less-height,300,"solid","red")
xr = rectangle(350,less-height,"solid","red")
Wr = rectangle(width,stripe,"solid","white")
Rw = rectangle(width,stripe,"solid","white")
rr = rectangle(380,less-height,"solid","red")
Rr = rectangle(less-height,400, "solid","red")
mr = rectangle(width,smite, "solid","red")
rm = rectangle(width,smite, "solid","red")
wb = place-image(rotate(25,wr),300,150,br)
wwb = place-image(rotate(65,rw),300,150,wb)
rwb = place-image(rotate(65,yr),130,85,wwb)
x-yr = place-image(rotate(25,xr),450,65,rwb)
xrr = place-image(rotate(155,rr),450,200,x-yr)
xyr = place-image(rotate(295,Rr),130,240,xrr)
wxr = place-image(wr,300,150,xyr)
wyr = place-image(rotate(90,Rw),300,150,wxr)
bflag = place-image(mr,300,150,wyr)
flag = place-image(rotate(90,rm),300,150,bflag)
