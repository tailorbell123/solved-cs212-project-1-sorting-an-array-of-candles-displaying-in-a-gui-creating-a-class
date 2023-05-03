Download Link: https://assignmentchef.com/product/solved-cs212-project-1-sorting-an-array-of-candles-displaying-in-a-gui-creating-a-class
<br>
<span class="kksr-muted">Rate this product</span>

Sorting an Array of Candles/ Displaying in a GUI/Creating a Class

Create a class called Candle to represent a candle. It should have four private instance variables: An int for the height, an int for the width, a float for the price and a boolean to determine if the candle is lit or not. The class should include a three-argument constructor (we will assume a constructed candle is not lit) and get and set methods for each instance variable. Override the method toString which should return the Candle information in the same format as the input file (See below).

Read the information about a candle from a file that will be given to you on Blackboard, parse out the three pieces of information for the Candle using a StringTokenizer, instantiate the Candle and store the Candle object in two different arrays (one of these arrays will be sorted in a later step). Once the file has been read and the arrays have been filled, sort one of the arrays by price using Selection Sort.

Display the contents of the arrays in a GUI that has a GridLayout with one row and two columns. The left column should display the candles in the order read from the file, and the right column should display the candles in sorted order.

The input file

Each line of the input file will contain information about a candle, with each piece of information separated by a comma. An example of the input file would be:

<pre>12,1,1.494,3,2.50</pre>

If the line of the file does not have exactly three tokens, do not put it in the arrays; print it to the console.

Submitting the Project.

You should have three files to submit for this project:

<pre>Project1.javaCandleGUI.javaCandle.java</pre>