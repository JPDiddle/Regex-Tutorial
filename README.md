# Regex-Tutorial

## Run Down
Matching a URL!

 `/^(https?:\/\/)?([\da-z\.-]+)\.([a-z\.]{2,6})([\/\w \.-]*)*\/?$/`
 This is the regex I have chosen to do a tutorial on for this assignment!

 So to start a regex is a sequence of characters that defines a specific search pattern

 Lets begin to break down the components of this specific regex!

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Grouping Constructs](#grouping-constructs)
- [Bracket Expressions](#bracket-expressions)
- [Character Classes](#character-classes)
- [Character Escapes](#character-escapes)

## Regex Components

### Anchors
Anchors are what begin and end an expression, as you can see with ours, (`/^(https?:\/\/)?([\da-z\.-]+)\.([a-z\.]{2,6})([\/\w \.-]*)*\/?$/`), it is signified with the "^" at the start and an "$" at the end! But you can use either!
### Quantifiers
Quantifiers are what set the limit for our expression. It is shown many ways, such  as "{n}" this will match you pattern "n" number of times, or "?", this one means to match the pattern once or not at all! And as you can see with ours it does have one of those "?" in there!
### Grouping Constructs
 Grouping constructs are what help us break up our expression into different pieces using parathensis can be used to meet different needs, so with ours, (`/^(https?:\/\/)?([\da-z\.-]+)\.([a-z\.]{2,6})([\/\w \.-]*)*\/?$/`), you can see there are four pieces to our expression!
### Bracket Expressions
Bracket Expressions are used to give limits to certain aspects of the statement, this is shown like [1-7] which would mean only numbers 1,2,3,4,5,6,7 would be available. An example with ours would be [a-z] so all letters are available! 
### Character Classes
A character class helps define sets of characters! Who would have guessed! they can be shown as "." to "\n", these two match all but newline characters. Or "\d" this one matches arabic numeral digits!
So with ours, (`/^(https?:\/\/)?([\da-z\.-]+)\.([a-z\.]{2,6})([\/\w \.-]*)*\/?$/`), it is using the numeral diget class!
### Character Escapes
An escape is shown by a "\" this is used to escape segments before loading into new ones to prevent interuptions. So ours is escaping, (`/^(https?:\/\/)?([\da-z\.-]+)\.([a-z\.]{2,6})([\/\w \.-]*)*\/?$/`), right at the end of ([\da-z\.]) before continuing with the statement.
## Author
I'm John or Jack Price and this was an assignment in the coding bootcamp I am currently enrolled in with UofA, I hope this was helpful! Thank you! and heres a link to my Github profile if you'd like to see any other projects of mine! https://github.com/JPDiddle