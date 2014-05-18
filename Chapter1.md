#Toys

<table> 
<tr><td>
####Question
</td><td>
####Answer
</td></tr><tr><td>
................................................................................................................................................................................................................</td><td>
................................................................................................</tr>
<tr><td>
Is it true that this is a String? <br/>
&nbsp;&nbsp;&nbsp; `'string'`
</td><td>
Yes, <br/>
&nbsp;&nbsp;&nbsp; because `'string'` is a chain of zero or more <br />
&nbsp;&nbsp;&nbsp; characters beginning with the letter s and <br />
&nbsp;&nbsp;&nbsp; surrounded by single quotes.
</td></tr>


<table>
<tr><td></td><td></td></tr><tr><td>
................................................................................................................................................................................................................</td><td>
................................................................................................</tr>
<tr><td>
Is it true that this is a String? <br/>
&nbsp;&nbsp;&nbsp; `'chicken'`
</td><td>
Yes, <br/>
&nbsp;&nbsp;&nbsp; because `'chicken'` is a chain of zero or more <br />
&nbsp;&nbsp;&nbsp; characters beginning with a single letter.
</td></tr>

<table>
<tr><td></td><td></td></tr><tr><td>
................................................................................................................................................................................................................</td><td>
................................................................................................</tr>
<tr><td>
Is it true that this is a String? <br/>
&nbsp;&nbsp;&nbsp; `'1942'`
</td><td>
Yes, <br/>
&nbsp;&nbsp;&nbsp; because `'1942'` is a chain of digits, <br />
&nbsp;&nbsp;&nbsp; surrounded by single quotes.
</td></tr>

<table>
<tr><td></td><td></td></tr><tr><td>
................................................................................................................................................................................................................</td><td>
................................................................................................</tr>
<tr><td>
Is it true that this is a String? <br/>
&nbsp;&nbsp;&nbsp; `'v'`
</td><td>
Yes, <br/>
&nbsp;&nbsp;&nbsp; because `'v'` is a String of one character, <br />
&nbsp;&nbsp;&nbsp; which is a letter.
</td></tr>

<table>
<tr><td></td><td></td></tr><tr><td>
................................................................................................................................................................................................................</td><td>
................................................................................................</tr>
<tr><td>
Is it true that this is a String? <br/>
&nbsp;&nbsp;&nbsp; `'$xyz*'`
</td><td>
Yes, <br/>
&nbsp;&nbsp;&nbsp; because `'$xyz*'` is a String of characters, <br />
&nbsp;&nbsp;&nbsp; beginning and ending with a special character <br />
&nbsp;&nbsp;&nbsp; still in single quotes.
</td></tr>

<table>
<tr><td></td><td></td></tr><tr><td>
................................................................................................................................................................................................................</td><td>
................................................................................................</tr>
<tr><td>
Is it true that this is an Array? <br/>
&nbsp;&nbsp;&nbsp; `['s','t','r','i','n','g']`
</td><td>
Yes, <br/>
&nbsp;&nbsp;&nbsp; because `['s','t','r','i','n','g']` is a list of <br />
&nbsp;&nbsp;&nbsp; single-letter strings each in single quotes, <br />
&nbsp;&nbsp;&nbsp; separated by commas, and enclosed by brackets.
</td></tr>

<table>
<tr><td></td><td></td></tr><tr><td>
................................................................................................................................................................................................................</td><td>
................................................................................................</tr>
<tr><td>
Is it true that this is an Array? <br/>
&nbsp;&nbsp;&nbsp; `['string','chicken','or']`
</td><td>
Yes, <br/>
&nbsp;&nbsp;&nbsp; because it is a collection of strings <br />
&nbsp;&nbsp;&nbsp; in single quotes, separated by commas, <br />
&nbsp;&nbsp;&nbsp; and still enclosed by brackets.
</td></tr>

<table>
<tr><td></td><td></td></tr><tr><td>
................................................................................................................................................................................................................</td><td>
................................................................................................</tr>
<tr><td>
Is it true that this is an Array? <br/>
&nbsp;&nbsp;&nbsp; `['string','chicken'] 'or'`
</td><td>
No, <br/>
&nbsp;&nbsp;&nbsp; because these are actually two <br />
&nbsp;&nbsp;&nbsp; seperate expressions: one an Array, <br />
&nbsp;&nbsp;&nbsp; and the other a String.
</td></tr>

<table>
<tr><td></td><td></td></tr><tr><td>
................................................................................................................................................................................................................</td><td>
................................................................................................</tr>
<tr><td>
Is it true that this is an Array? <br/>
&nbsp;&nbsp;&nbsp; `[['string','chicken'], 'or']`
</td><td>
Yes, <br/>
&nbsp;&nbsp;&nbsp; because the inner Array and String <br />
&nbsp;&nbsp;&nbsp; are now enclosed by outer brackets,<br />
&nbsp;&nbsp;&nbsp; and separated by a comma.
</td></tr>

<table>
<tr><td></td><td></td></tr><tr><td>
................................................................................................................................................................................................................</td><td>
................................................................................................</tr>
<tr><td>
Is it true that this is an expression? <br/>
&nbsp;&nbsp;&nbsp; `'use chicken';`
</td><td>
Yes, <br/>
&nbsp;&nbsp;&nbsp; because all strings are valid expressions <br />
&nbsp;&nbsp;&nbsp; alone and followed by a semicolon.<br />
</td></tr>

<table>
<tr><td></td><td></td></tr><tr><td>
................................................................................................................................................................................................................</td><td>
................................................................................................</tr>
<tr><td>
Is it true that this is an expression? <br/>
&nbsp;&nbsp;&nbsp; `['eat', 'chicken'];`
</td><td>
Yes, <br/>
&nbsp;&nbsp;&nbsp; because it is an Array followed by a<br />
&nbsp;&nbsp;&nbsp; semicolon to mark the end the expression.<br />
</td></tr>

<table>
<tr><td></td><td></td></tr><tr><td>
................................................................................................................................................................................................................</td><td>
................................................................................................</tr>
<tr><td>
Is it true that this is an expression? <br/>
&nbsp;&nbsp;&nbsp; `[['eat', 'fried'], 'chicken'];`
</td><td>
Yes, <br/>
&nbsp;&nbsp;&nbsp; because it is an Array containing an Array<br />
&nbsp;&nbsp;&nbsp; with a semicolon to mark the end the expression.<br />
</td></tr>

<table>
<tr><td></td><td></td></tr><tr><td>
................................................................................................................................................................................................................</td><td>
................................................................................................</tr>
<tr><td>
Is it true that `question` contains an Array? <br/>
&nbsp;&nbsp;&nbsp; `var question = ['How', 'are', 'you', 'today', '?'];`
</td><td>
Yes, <br/>
&nbsp;&nbsp;&nbsp; because `question` is a variable holding<br />
&nbsp;&nbsp;&nbsp; an Array of Strings.<br />
</td></tr>

<table>
<tr><td></td><td></td></tr><tr><td>
................................................................................................................................................................................................................</td><td>
................................................................................................</tr>
<tr><td>
How many Strings are in the Array named `question`? <br/>
&nbsp;&nbsp;&nbsp; `var question = ['How', 'are', 'you', 'today', '?'];` <br />
and what are they?
</td><td>
Five: <br/>
&nbsp;&nbsp;&nbsp; `How`, `are`, `you`, `today`, and `?`.
</td></tr>

<table>
<tr><td></td><td></td></tr><tr><td>
................................................................................................................................................................................................................</td><td>
................................................................................................</tr>
<tr><td>
Is it true that this is an Array? <br/>
&nbsp;&nbsp;&nbsp; `[[['How'], 'are'], ['you', ['today', ['?']]]` <br />
</td><td>
Yes, <br/>
&nbsp;&nbsp;&nbsp; because it is a Array of Arrays containing <br />
&nbsp;&nbsp;&nbsp; Strings enclosed by brackets.<br />
</td></tr>

<table>
<tr><td></td><td></td></tr><tr><td>
................................................................................................................................................................................................................</td><td>
................................................................................................</tr>
<tr><td>
How many Arrays total are contained by this Array? <br/>
&nbsp;&nbsp;&nbsp; `[[['How'], 'are'], ['you', ['today', ['?']]]` <br />
</td><td>
Five, <br/>
&nbsp;&nbsp;&nbsp; `['How']` in `[[['How'], 'are']`, and `['?']`<br />
&nbsp;&nbsp;&nbsp; in `['today', ['?']]` in `['you', ['today', ['?']]]`
</td></tr>

<table>
<tr><td></td><td></td></tr><tr><td>
................................................................................................................................................................................................................</td><td>
................................................................................................</tr>
<tr><td>
Is it true that this is an Array? <br/>
&nbsp;&nbsp;&nbsp; `[]`
</td><td>
Yes,  <br/>
&nbsp;&nbsp;&nbsp; `[]` represents an empty Array. <br />
```javascript
var emptyArray = [];
```
</td></tr>
