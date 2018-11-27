# csPortfolio

* WebPage [here](https://jtliggett.github.io/TestPage/JakeDogPage.html)
* Lightning [here](https://jtliggett.github.io/lightning2/)
* Lightning JS [here](https://jtliggett.github.io/lightning2/JSLightning/index.html)
* Dice [here](https://jtliggett.github.io/dice3)
* College Presentation [here](https://docs.google.com/presentation/d/e/2PACX-1vSKFChMDzyCOQGGyqc4GCK6H5u60xKVvyy7hOqBLWFDFsl7FOZPA_HYDRsApVUgh8Z1bW7cohidovDv/pub?start=false&loop=false&delayms=60000)
* Chemotaxis [here](https://jtliggett.github.io/chemotaxis4)
* Starfield [here](https://jtliggett.github.io/starfield5)


| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

Reflect on all your portfolio projects.  
       Overall, I'm very happy with my projects. They are the first coding projects I've made, and I think they're pretty good. However, I wish I could go back and make some of them have more feature when I ran out of time.

What is one or two things that are a source of pride in your programming development?  
       I'm really proud of my creativity on my projects. I typically choose not to be creative unless I absolutely have to, but all these projects were funny and entertaining. 
       
Identify them, write about why they are accomplishments, how you did it and what you learned.  Be sure to submit a code snippet along with your writing on the readMe file in your repo.
      Here is some of my dice code, which is my favorite project that I made:
      else if (boolToInt(nines == 2) + boolToInt(tens == 2) + boolToInt(jacks == 2) + boolToInt(queens == 2) + boolToInt(kings == 2) + boolToInt(aces == 2) == 2 )
    {
      textSize(30);
      fill(0);
      text("Two Pair", 50, 90);
    } 
    This was for a two pair combo where I had to create a new method booltoInt in order for the code to find the two pairs. I learned that sometimes you have to have methods within methods to make them run most efficiently. 
    
Identify the most significant hurdle you encountered last trimester. Write about what it was and how it was resolved.
       For a long time, I couldn't figure out how to get the stafield code working. There were little details I couldn't figure out how to fix. This was the first time I had to have many methods working together. I fixed it using a lot of trial and error and messing with code.
    Describe the incremental and iterative development process of your included code, focusing on two distinct points in the development process. Describe the difficulties and/ or opportunities you encountered and how they were resolved or incorporated. In your description clearly indicate whether the deveis, development described was collaborative or independent. At least one of these points must refer to independent program development.
    
This code below was for my lightning project. It took me a while to figure out how to add thunder to my code. I had to go into processing's files and add the sound maker. Then, I went online and found a thunder sound for my project. Afte this, implementing into my project took a while to make it work on github. Eventually, the thunder was added using help from Dr. R, but mostly on my own.
    
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
