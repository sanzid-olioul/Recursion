### Regular Expressions

`Regular Expressions also called regex or regexex or REs` is a highly specialized language to find or match a pattern lke  ***email,phone-number,address etc*** in a string.
***Almost every programing language has embaded regex for finding pattern match for string and python also has.*** We can use regular expressins in python by importing `re` module.
Python re module is written in ***C***. As it is written in ***C***, Regular expression patterns are compiled into a series of bytecodes which are then executed by a matching engine
written in ***C***.

`. ^ $ * + ? { } [ ] \ | ( )` is the complete list of metacharacters used for creating patterns.

***`Alost Every Proramming Language Use same concept for creating patterns.`***

- `.` represents any character except newline
- `^` represents starts of the string
- `$` represents ends of the string
- `*` means zero or more.
- `+` means one or more
- `?` measns zero or one
- `{}` represents occurence time
- `[]` represents character set
- `\` represents inhibit the "specialness" of a character `. ^ $ * + ? { } [ ] \ | ( )` for match.
- `|` represents Alternation or `"or"` operator
- `()` means making a group

