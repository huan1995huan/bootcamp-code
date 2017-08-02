# bootcamp-code

PImage photo;

void setup() {
  size(800, 800);
  photo = loadImage("5.jpg");
}

void draw() {
  
  image(photo, 0, 0, 400, 300);
}
