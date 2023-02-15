# How to solve any Pattern program
Pattern questions are typically not asked in the technical interview process for any SDE or SWE role in big or small tech companies. But solving these pattern questions and understanding the use of loops helps an individual to develop their pattern-recognising ability in a variety of questions. This also serves as a fundamental block in building your problem-solving ability if you are a beginner in coding.

*The pattern is “ a consistent, recurring characteristic that helps us identify a phenomenon and predict its future behaviour.”*
## Let's start by looking at an example problem:

![This is a alt text.](https://cdn.hashnode.com/res/hashnode/image/upload/v1673534789256/78bea4ac-528f-4c2e-82ba-1eee9610049f.jpeg?auto=compress,format&format=webp "This is a sample image.")


The first two things one should see while trying to solve a pattern problem are:

The number of rows.

The number of columns.

Then make loops to control the number of rows and columns, in this question the first loop should go from 1 to 5 to make five different rows. Nested inside it, we have to make a loop which will run the number of times as there are columns, here it is 1 for 1st row, 2 for 2nd ......5 for the 5th row.

The next thing we have to do is what needs to be printed for each row and column, as in this pattern the "*" needs to be printed and the number of stars is equal to the number of rows we are on. So the code for this pattern will be:

```
for(int i=1;i<=n;i++){ //loop for controlling rows 
for(int j=1;j<=i;j++){ //loop for controlling the columns 
System.out.print("* "); } System.out.println(""); // for changing line after each row 
}
```

As this one was a simple pattern so we did not have to do anything about what we had to print, but there will be problems where the real trick will be to find the relation between rows and columns to print the value/character needed.

## Here are some of the top patterns to practice and build your logical thinking at the start of your coding journey:

![This is a alt text.](https://cdn.hashnode.com/res/hashnode/image/upload/v1673535931390/5b9bbd7b-0bcc-46d5-9648-4e3b130732a9.png?auto=compress,format&format=webp "This is a sample image.")

![This is a alt text.](https://cdn.hashnode.com/res/hashnode/image/upload/v1673535982279/0131176b-94cf-450a-9c48-2d913f660b45.png?auto=compress,format&format=webp "This is a sample image.")

![This is a alt text.](https://cdn.hashnode.com/res/hashnode/image/upload/v1673536006512/54ae61d5-1008-45aa-b3c2-d403ebd93454.png?auto=compress,format&format=webp "This is a sample image.")

![This is a alt text.](https://cdn.hashnode.com/res/hashnode/image/upload/v1673536041302/3a9d0572-8b14-4fd1-95ce-f967ef88fac8.png?auto=compress,format&format=webp "This is a sample image.")

![This is a alt text.](https://cdn.hashnode.com/res/hashnode/image/upload/v1673536102514/4bf8b448-e323-4905-b6cc-ab222f2009ba.png?auto=compress,format&format=webp "This is a sample image.")

![This is a alt text.](https://cdn.hashnode.com/res/hashnode/image/upload/v1673536619390/f5e2530e-30e4-4255-899e-4b16e1169c8b.png?auto=compress,format&format=webp "This is a sample image.")

![This is a alt text.](https://cdn.hashnode.com/res/hashnode/image/upload/v1673536632868/51f83990-4b02-4144-ad8e-35841b183b2b.png?auto=compress,format&format=webp "This is a sample image.")

![This is a alt text.](https://cdn.hashnode.com/res/hashnode/image/upload/v1673536672681/a194c623-53b2-42e2-8dbe-4e3ccf86d4cc.png?auto=compress,format&format=webp "This is a sample image.")

*Please share this article if you liked it and if you have any feedback you can comment down, I would be glad to make the improvements.*
