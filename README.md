# CP2-homework
//molnar rectangles//

createCanvas (400,600);
 
  noStroke();
background (0);
colorMode(HSB);


for (var x = 20; x < width-20; x += 20) {
  rect(x, 10+random(40), 18, height/4-40);
}
for (var x = 20; x < width-20; x += 20) {
  rect(x, height/3+random(40), 18, height/4-40);
}
for (var x = 20; x < width-20; x += 20) {
  rect(x, 400+random(40), 18, height/4-40);
}
