function setup() {
 createCanvas(600, 600);
 background("black");
}
function draw() {
 stroke("purple");
 fill("pink");

 if(mouseIspassed){
 rect(mouseX, mouseY, 20, 35);
 }
 }
