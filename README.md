# twitter014
#つぶやきProcessing float i,x,y,d,k,w=500;void setup(){size(500,500);}void draw(){fill(random(map(sin(radians(k)),0,1,0,99)));rect(0,0,w,w);for(i=0;i&lt;9;i++){x=random(w);y=random(w);d=x/4;stroke(255);line(x,y,x+d,y+d);}fill(0);noStroke();rect(240,0,20,w);rect(0,150,w,20);k++;}
