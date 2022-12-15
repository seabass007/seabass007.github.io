Hello World!

This is my home page! My name is Sebastian Gomez and I am a student at [Cal State Fullerton](http://www.fullerton.edu/) and my major is Computer Science.

## Computer Science Projects

My GitHub page is http://github.com/seabass007.

### CPSC 120
---
* LAB 2
 
   Lab 2 has to be one of my favorites not because of the code itself. It was the first time we were writing actual code and formatting. I remember the feeling of just formating the fahrenheit calculator for the first time and having it compile and run. I also remember during this code thinking to myself, "Huh this isn't going to be too bad." Boy was I wrong it would only get so much harder.

   ```html
    
    fahrenheit * 9.0/5.0 + 32.0; 
      std::cout <<fahrenheit << " degrees Fahrenheit is " <<  
      celsius << " degrees Celsius.\n";
   ```
   ---
* LAB 6
 
   Lab 6 was a really monumental lab for me because it taught me some things that I wasn't too clear on. Part one of that lab helped me understand nested loops. It was a loop that added dashes ans stars every loop. I didn't know that a nested loop behaved differently than a regular loop. My partner helped me understand that the outer loop loops loop once while the inner loops loop multiple times within that loop. That was very interesting to learn and helped me understand loops more.

   ```html
   for (int x = 0; x < kCounterMax; ++x) {
    for (int y = 0; y < kCounterMax; ++y) {
      if (y >= x) {
        continue;
      }
   ```
   ---
* LAB 9
 
   Lab 9 helped me understand how to replace a variable with a new data point. In this lab, we had to make an Olympic average score. My partner and I tried a while loop and it wasn't working. The TA came and helped us and said a for loop would be easier to do. He helped us and had us do a for loop where the score would equal the maximum if it was higher than the previous saved score

   ```html

   double minimum = 11.0;
  double maximum = -1.0;
  for (double score : scores) {
    if (score < minimum) {
      minimum = score;
    }
  }
  for (double score : scores) {
    if (score > maximum) {
      maximum = score;
    }
  }
  
```