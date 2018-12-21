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