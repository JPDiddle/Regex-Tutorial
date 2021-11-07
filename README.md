# Regex-Tutorial
# Email REGEX Tutorial

Regular expressions may seem quite difficult to understand when you're first being introduced to the idea. 
But fret not! I will be breaking down a regular expression that will match an email; this tutorial will break down the different components that make up the expression that will allow you to also use the definitions to help breakdown your own regular expressions.

## Summary
 `/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/`
This is the regex I will be breaking down for you all in this tutorial; this particular regex is used to match an email but you can still apply the knowledge you obtain during this tutorial to examine and breakdown other regular expressions.


## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Grouping Constructs](#grouping-constructs)
- [Bracket Expressions](#bracket-expressions)
- [Character Classes](#character-classes)
- [Character Escapes](#character-escapes)

## Regex Components

### Anchors
Anchors are the starting and ending points of regular expressions; they are presented as "^" or the dollar sign. An important note to take is ^ anchor signifies the start of a string that follows it and the dollar sign anchor signifies the end of the charachters that come before it.
^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/ 
As you can see in this regex you will see ^ in the begining and at the end of the code there is a dollar sign
### Quantifiers
Now quantifiers are components used in regular expressions that help set the limits of the formula. 
Different quantifiers will allow you to match certain patterns more than one time such as the "+" quantifier or on the other end curly brackets "{}" can help you set a certain limit such as with the length of a word or password.
/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/  

Back to our Regex formula you can see we are using both + and {} quantifiers, now lets break them down..
/^([a-z0-9_\.-]+)@([\da-z\.-]+)
The "+" quantifer allows the possible outcomes to match more than one time based on what is in the bracket expressions.
Using our formula ([a-z0-9_\.-]+); within the [] are elements that can be used such as creating a word using letters from A-Z and using numbers that go from 0-9 but with the "+" quantifier you are allowed to repeat these variables multiple times such as ...AAAABB12123.
([a-z\.]{2,6})$/
Now moving on to the {} quantifiers, as mentioned before they help you set limits in your formulas.
in our regex formula {2,6} this means the last partof our email ex(.com) is limited only to a length of 2-6 characters

### Grouping Constructs
Grouping constructs help you break up sections that need to meet different requirements; to use these you will need paranthesis ()
 /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/
As you can see in our regex formula there are a total of three grouping constructs being used. 
Remember this is a regex formula that is being used to match emails so it needs to be formatted a certain way.
(username)@(email).(com)
### Bracket Expressions
Bracket expressions are used in regular expressions to give limitation an example of this would be [a-e] which only letters a,b,c,d,e can be used but since theyre in square brackets NOT EVERY letter has to be used it just has to be in the allowed characters.
/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/
Three sets of square brackets used in our regex formula.
### Character Classes
Character classes can be used inside of the bracket expressions to add to the possibility of matching with a word, such as adding special characters to a username.
 /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/
 In our regex formula we have ".", and "\d" that are considered character classes. the "." was added into the square brackets to add the special character into one of the possible options.
 The "\d" is just another way of saying any number 0-9 can be used.

### Character Escapes
Character escapes "escape" strings to avoid them being interpretted literally
We only have one character escape in our regex formula
 /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/
 The "\" is the character escape that is now matching the period in "\."

## Author

I'm John or Jack Price, I am currently enrolled in UofA's Coding Bootcamp, and I hope this tutorial helped you! The following is a link to my Github profile:https: https://github.com/JPDiddle