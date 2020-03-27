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

<h1>Chapter 4: "Decisions and Loops" from switch statements (HTML)</h1>

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

