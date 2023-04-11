# String Array Shortener
This is a C# program that shortens an input array of strings to an output array of strings with a length less than or equal to 3 characters. The program does not use collections, only arrays.

## Usage
The program takes an input array of strings and returns an output array of strings which length is less or equal to 3 symbols.

To use the program, call the ShortenStringArray method with the input array as a parameter:

*string[] inputArray = { "hello", "2", "world", ":-)" };*

*ShortenStringArray(inputArray);*

This will output the shortened string array:

*2, :-)*

## Implementation
The ShortenStringArray method takes an input array of strings, loops over each string in the array, and adds it to an output array if its length is less than or equal to 3 characters. The method uses the Array.Resize method to trim the output array to the correct size and removes any null values that were not filled in during the loop. Finally, the method prints the output array using string.Join to concatenate the elements with a comma and a space separator.

## License
This program is licensed under the MIT License. Feel free to use, modify, and distribute this program for any purpose.

## Technical changes to make 4 commits to comply with excersise 5
commit 2