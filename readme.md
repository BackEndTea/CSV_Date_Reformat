# CSV Date Format Changer

This script takes a csv file and changes the date format from dd/mm/yyyy to yyyy/mm/dd in the specified row. It then writes this to a new file that is named reformated - [orignialfile.csv] 

I made this quite some time ago to fix a database dump i had to use, which was from whatever database uses dd/mm/yyyy for its dates, which had then been converted to a csv.

It *Should* work whether or not the days and months have leading 0's. But in all honesty i wouldn't use this for really important files that don't have any sort of backup. Its verry possible that somewhere something could get messed up.

Usage:

    ./start [filename] [row number]

Example:

    ./start lel.csv 3

This works for the example file i added.
