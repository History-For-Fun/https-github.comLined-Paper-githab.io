// for (start; how long; change)
background(255, 255, 255);
stroke(234, 0, 255);


for (var i = 0; i < 20  ; i++) {
var lineY = 20 + (i * 20);
line(0, lineY, 400, lineY);    
}
/*
var i = 0;
while (i < 41) {
    var lineY = 69 + (i * 9);
    line(13, lineY, 387, lineY);
    i++;
}
*/
fill(255, 0, 0);
textSize(20);


for(var j = 0; j < 20; j++) {
    var lineX = 20 + (j * 20);
    line(lineX, 0, lineX, 400);
}











