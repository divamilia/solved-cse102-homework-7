Download Link: https://assignmentchef.com/product/solved-cse102-homework-7
<br>
<strong>Part 0:</strong> The program reads a text file named ‘Video_Games.txt’. Every row of this text file includes several informations about a single game. You are asked to read every row as a string and decompose these informations which are separated by commas.

Here is the excel format of the txt file, so that you can get used to the data.

<ul>

 <li>The program should keep the names of the games in a one-dimensional string array.</li>

 <li>The program should keep the names of the genres &amp; platforms in two different one-dimensional strring arrays. Please be sure that the elements are not overlapping! I.e. there shouldn’t be more than one ‘simulation’ in the array just because there are more than one simulation games.</li>

 <li>The program should keep the data of every single game in a two-dimensional float array. This array should include 7 different data for every game, including genre&amp;platform. The genre/platform cell should point the index of the genre/platform array which stores the names of the related genre/platform.</li>

</ul>

For example;

If the genre of the game is ‘simulation’ and the index of the string ‘simulation’ in the <em>array of genres</em> is 5, then the cell which shows the genre of the game should be ‘5.0’ in the <em>float array</em>.

Be careful! Some of the games has no value for ‘global_sales’ data. They have a string ‘not_available’ instead of a float number. Store them in the float array wisely cause you will need that information later on!

<ul>

 <li>The float array shouldn’t include any information about the name of the games since they are stored in a string array with the same indexes.</li>

</ul>

<strong>Part 1:</strong> The program should support 8 different operations. Therefore, there should be a menu as below. The program should terminate if and only if the user enters ‘8’ as the input. The menu should appear <em>again and again</em> <strong>if an input is invalid</strong> or <strong>if the previously requested operation is done</strong>. If the menu appears because of an invalid input, there should be an error message too.

<strong>Part 2:</strong> 0<sup>th</sup> and the 1<sup>st</sup> operations are almost the same. If the user enter ‘0’ (or ‘1’) as input, then the program should list the genres (or the platforms) as strings.

<strong>Part 3</strong>:  2<sup>nd</sup> operation lists the games according to an information received from the user. Firstly, the program asks for a ‘year’, after that the program asks ‘until that year or since that year?’. Finally the program lists the names of the all games which released until/since that year. Don’t forget that the program should handle the invalid year or period values. I.e. if the oldest game was released in 1995 and the user wants to print the game which released until 1996, the program should show an error message and asks for new values since there is no game before 1996.

<strong>Part 4:</strong> The 3<sup>rd</sup> operation asks for a game name from the user. If the input matches with a name from the name array, then the program prints all information of that game. If the input doesn’t match with any element of the name array, then it should give an error message and ask for a new input. If the ‘global_sales’ information of that game was ‘not_available’ when the program read it, then the users should see it as ‘Not Available’.

<strong>Part 5:</strong>  4<sup>th</sup> operation basically calculates and prints the average of the user scores of all games.

<strong>Part 6: </strong> 5<sup>th</sup> operation asks a game name and prints either the game was more populer in NA or EU according to the sales. If the sales are equal, specify that. Again, if the game name is not in the database, the program should ask for another name.

<strong>Part 7:</strong>  6<sup>th</sup> and 7<sup>th</sup> operations are printing the frequences of every genre/platform. I.e. they prints the number of games for every genre/platform.

<ul>

 <li>You can assume that;

  <ul>

   <li>The longest game name has 100 characters</li>

   <li>The longest genre or platform name has 20 characters.</li>

   <li>The longest row of the text file has 200 characters</li>

  </ul></li>

</ul>

<ul>

 <li>You are not allowed to use any library other than;

  <ul>

   <li>&lt;stdio.h&gt;</li>

   <li>&lt;string.h&gt;</li>

   <li>&lt;stdlib.h&gt;</li>

  </ul></li>

 <li>You can use the ‘strtod’ function from &lt;stdlib.h&gt; library to parse a string to float.</li>

 <li>Some games are released on different platforms, which means some of the game names are the same. When you are search for a game with the name of it, pick the first one you find.</li>

 <li>You can write your own functions to make things easier.</li>

 <li>Don’t forget that the program shouldn’t terminate when an operation is done.</li>

</ul>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong> </strong>