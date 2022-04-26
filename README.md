let laranjas;

function setup() {
	createCanvas(windowWidth, windowHeight);
	background(0)

}

function draw() {

	background(0)


if(mouseY >= height/2) {
	noFill();
}

else{

	fill(12,108,57); //verde
}


if(mouseX <= width/2) {
	fill(19,52,146); //azul
}

if(mouseY < height/2 && mouseX <= width/2) {
	fill(221,56,56); //vermelho

}
	stroke(230);
	strokeWeight(2);
	
	circle(width / 2, height / 2, height / 4); // circulo sempre ao centro do encrã


}
