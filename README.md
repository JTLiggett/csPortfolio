# csPortfolio

* WebPage [here](https://jtliggett.github.io/TestPage/JakeDogPage.html)
* Lightning [here](https://jtliggett.github.io/lightning2/)
* Lightning JS [here](https://jtliggett.github.io/lightning2/JSLightning/index.html)
* Dice [here](https://jtliggett.github.io/dice3/dice3.pde)

```Java
void mouseReleased() {
  Yend = (int) (Math.random()*700 ) +500;
  Y = (int) Math.random() * 600 + 100;
  X =(int) (Math.random()*1500) +50;
  while (Y < Yend) { 
    if ( X > 1550) {
      X2 = (int) (Math.random()*50) - 50;
    }
    if ( X < 80) {
      X2 = (int) (Math.random()*50);
    } else {
      X2 =(int) (Math.random()*100) - 50;
    } 
    strokeWeight(10); 
    line(X, Y, X+X2, Y+20); 
    stroke(255, 255, 0);
    Y += 20;
    X += X2;
    thunder.play();
  }
}
```
