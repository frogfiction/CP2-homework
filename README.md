# CP2-homework
//molnar rectangles//

createCanvas (400,600);
 
  noStroke();
background (0);
colorMode (HSB,100);
var hues = [0, 6, 12, 18, 24, 30, 42, 48, 54, 60, 66, 72, 78, 84, 90, 96];


for (var i = 0; i < width/25; i += 1) {
  fill(hues[i],100,100);
  rect(i*20+20, 10+random(40), 18, height/4-40);
}
for (var i = 0; i < width/25; i += 1) {
  fill(hues[i],100,50);
  rect(i*20+20, height/3+random(40), 18, height/4-40);
  
}
for (var i = 1; i < width/25; i += 1) {
  fill(random(100),50,100);
  rect(i*20+20, 400+random(40), 18, height/4-40);

}
