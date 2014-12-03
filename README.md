DLDateFormatter
===========

A PHP flexible date formatter for passing in a date and/or time and returning a formatted date and/or time with options for calculating past/future dates/times

This simple function will accept a date as the first parameter in any standard US format (mm/dd/yy, mm/dd/yyyy, mm-dd-yy, mm-dd-yyyy, yyyy-mm-dd, yy-mm-dd), with optional time in standard US format (hh:ii:ss).

The second parameter is the desired format for the function to output the date/time. This parameter follows the format of the PHP date() function. Optional, and if none specified, returns in n/j/y format.

The third parameter accepts inputs in array format, and calculates the date/time back or forward based on the elements passed in through the array. The values accepted also follow the format of the PHP date() function, with any combination of these five accepted options: h, i, m, d, y. Optional.
