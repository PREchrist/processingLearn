My today's task on programing with processing is to make a program which consist to setup rectangles colorful. so the attached image below shows all the work.
so following codes allow me to edit this program:
```
size(500,500);
background(255,255);
```
So that to fix the boundaries of the small window which shows the work wrote on the sketch otherwise called canvas, we use the fonction "size"; inside this fonction we determine the length and the height. In this same way, there's the fonction"background"; this last one in prrograming in processing helps to give color of canvas; there isn't the fixe color and we are able to manipulate all colors as possible you just have to determine the numbers, the colorful of the short window is fix by using numbers from 0 till  infinity, also the combination of numbers such as: "(255,200), or (199)" whatever positive numbers give color. To take into account, never use one of these functions in capital letter or in uppercase in simple terms, otherwise the program won't work.
```
for( int i=0;i<450;i++){
fill(0);
rect(50*i,0,50,50);
}
```
Here's the code that we indicate in our console which will be execute in the canvas. So "for" is used to indicate the loop of program, its set we have "()" to insert how the process will be execute; <<i>> to indicate the numbers of the rectangle  and curly bracket "{}" to show the nonstraight. Also there is the ";" which is capital to run the program. if one of all those functions or points missing over programing, the shadow below the console will indicate too. "fill" is uesd to settle either the circle or rect color. the number of color is between the brackets and at the end the have ";" which is used to that to separate differents fonctions like when we used "," it means there is another expression or fonction after that one. finally, one fonction called "rect" is thi case which is uesd to create a program with rectangle. in the opposite of the circle, inside of the fonction "rect" we have four(4) point to indicate which are "X,Y" starting point which are changed after each new loop and the "width, height" overall the work don't change. they are  like two water drops that don't undergo changement.
