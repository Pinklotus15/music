# music
var song2;
function preload() {
song2 = loadSound('Assests/sound/bensound-summer.mp3');
}
function setup() {
song2.play();
createCanvas(1250, 950);
background(0, 206, 255);
fill(0, 216, 0);
noStroke();
rect(0, 700, 1250, 200);
fill(255, 255, 0);
ellipse(1220, 50, 200, 200);
stroke(0, 0, 0);
strokeWeight(1);
theButton();
}; 
