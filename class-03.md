<em>From the Duckett HTML book:</em>
<ul>
<li>Chapter 3: “Lists” (pp.62-73)</li>
<li>Chapter 13: “Boxes” (pp.300-329)</li>
</ul>
<em>From the Duckett JS book:</em>
<ul>
<li>Chapter 4: “Decisions and Loops” from switch statements on (pp.162-182)</li>
</ul>

<h1>Chapter 3: "Lists" (HTML)</h1>

<h2>types of lists</h2>
<ul>
<li> ordered lists </li>
<li> unordered lists </li>
<li> <a href="http://www.htmlandcssbook.com/code-samples/chapter-03/definition-lists.html"</a>definition lists <em>see pg 67</em></li>
	<li> <a href = http://www.htmlandcssbook.com/code-samples/chapter-03/nested-lists.html:</a>nested lists <em>see pg 68</em></li>
</ul>

<h1>Chapter 4: "Decisions and Loops" from switch statements (Javascript)</h1>

<h2>Using Switch statements see pg (165)</h2>
<p>switch statement is to present the user with a different message depending on which level they are at. Pg 164 compares if statements vs switch statements Example code from textbook below:
</p>
"var msg;        // Message
var level = 2;  // Level

// Determine message based on level
switch (level) {
case 1:
    msg = 'Good luck on the first test';
    break;

case 2:
    msg = 'Second of three - keep going!';
    break;

case 3:
    msg = 'Final round, almost there!';
    break;

default:
    msg = 'Good luck!';
    break;
}

var el = document.getElementById('answer');
el.textContent = msg;"

<h2>Truthy and Falsy Values</h2>
<ul> Falsy values pg 167
	<li> var highScore = false; // traditional Boolean false </li>
	<li> var highScore = 0; // number zero</li>
	<li> var highScore = ''; // empty string </li>
	<li> var highScore = 10/'score'; // NaN </li>
	<li> var highScore; // no value assigned to it </li>
</ul>
<ul> Truthy values pg 167
	<li><li> var highScore = true; // traditional Boolean true </li>
	<li> var highScore = 1; // number other than zero</li>
	<li> var highScore = 'carrot'; // Strings with content </li>
	<li> var highScore = 10/5'score'; // Number calculations </li>
	<li> var highScore = 'true'; // true written as a string </li>
	<li> var highScore = '0'; // zero written as a string </li>
	<li> var highScore = 'false'; // false written as a string </li>
	
<p> checking equality and existence can be done using a single operand, see example below </p>

<p>using WHILE loops, example below from pg 176: </p>

"var i = 1;       // Set counter to 1
var msg = '';    // Message

// Store 5 times table in a variable
while (i < 10) {
  msg += i + ' x 5 = ' + (i * 5) + '<br />';
  i++;
}

document.getElementById('answer').innerHTML = msg;"

<p>using DO WHILE loops, example below from pg 177: </p>

"var i = 1;       // Set counter to 1
var msg = '';    // Message

// Store 5 times table in a variable
do {
  msg += i + ' x 5 = ' + (i * 5) + '<br />';
  i++;
} while (i < 1); 
// Note how this is already 1 and it still runs

document.getElementById('answer').innerHTML = msg;"


	
