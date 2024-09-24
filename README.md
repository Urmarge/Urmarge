void setup () {
  size(1000,700);  
vX= width / 3;
vY= height / 3;
}

void draw () {
  background(255);
  vX = mouseX;
  vY = mouseY;
  
fill(random(255), random(155), random(100));
noStroke();

rectMode(CENTRE);
rect(vX , vY, 100, 50);

fill(0);
ellipse(vX , vY, 100, 50 );

fill(0);
ellipse(vX - 30, vY + 25, 30, 30 );
ellipse(vX + 30, vY + 25, 30, 30);

fill(255);
rect(vX - 25, vY-10, 50, 20);
}
