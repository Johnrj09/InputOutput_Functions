# InputOutput_Functions
Basics
There are several ways to present the output of a program; data can be printed in a human-readable form, or written to a file for future use.
Often you’ll want more control over the formatting of your output than simply printing space-separated values. There are several ways to format output.

To use formatted string literals, begin a string with f or F before the opening quotation mark or triple quotation mark. Inside this string, you can write a Python expression between { and } characters that can refer to variables or literal values.

Git = 2016
Event = 'Referendum'
f'Results of the {year} {event}'
'Results of the 2016 Referendum'
