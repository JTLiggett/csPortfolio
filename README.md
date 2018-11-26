# csPortfolio

* WebPage [here](https://jtliggett.github.io/TestPage/JakeDogPage.html)
* Lightning [here](https://jtliggett.github.io/lightning2/)
* Lightning JS [here](https://jtliggett.github.io/lightning2/JSLightning/index.html)
* Dice [here](https://jtliggett.github.io/dice3)
* College Presentation [here](https://docs.google.com/presentation/d/e/2PACX-1vSKFChMDzyCOQGGyqc4GCK6H5u60xKVvyy7hOqBLWFDFsl7FOZPA_HYDRsApVUgh8Z1bW7cohidovDv/pub?start=false&loop=false&delayms=60000)
* Chemotaxis [here](https://jtliggett.github.io/chemotaxis4)
* Starfield [here](https://jtliggett.github.io/starfield5)

Reflect on all your portfolio projects.  
       Overall, I'm very happy with my projects. They are the first coding projects I've made, and I think they're pretty good. However, I wish I could go back and make some of them have more feature when I ran out of time.

What is one or two things that are a source of pride in your programming development?  
       I'm really proud of my creativity on my projects. I typically choose not to be creative unless I absolutely have to, but all these projects were funny and entertaining. 
       
Identify them, write about why they are accomplishments, how you did it and what you learned.  Be sure to submit a code snippet along with your writing on the readMe file in your repo.
      Here is some of my dice code, which is my favorite object


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
