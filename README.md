# Flying Logbook
A logbook for gliding and powered flying, implemented as OpenOffice / LibreOffice spreadsheet.

## Keep Track of Your Gliding and Powered Flying
The design of this pilot logbook spreadsheet follows the recommendations of the BGA and EASA for gliding and powered flying, respectively.
It serves as a backup in case you lose your paper logbooks, and it also does all the tedious calculations of total/annual/monthly flight time for you.
I have developed it primarily for soaring pilots, but pure power pilots might find it just as useful.

## Usage
The latest version of the spreadsheet has been developed and tested with LibreOffice Calc v7.0.
Earlier versions than v3.5.2. are not recommended due to serious bugs which cause errors in calculations and may even corrupt the file.

**Log sheets** are pretty self-explanatory.
Simply copy all entries from your paper logbook to the spreadsheet.
It pays off to be consistent though, e.g. do not type 'Std. Libelle' in one line and then 'Standard Libelle' in the next.
Gliding time is logged in hours and minutes, whereas powered flight time is specified in decimal hours.
There is often some confusion regarding "Crew Capacity".
The complex definitions by EASA, which have been defined mainly with commercial pilots in mind, do not make things easier.
The logbook uses four categories: 'P1', 'P2', 'PD', and 'PI'.
Personally, I use 'P1' for solo flying, 'P2' as pilot under tuition, 'PD' if I am safety pilot or qualified passenger, and 'PI' for instructing.
Additional information may be appended, e.g. 'P1-US' for pilot under supervision.

**Statistic pages** do all the maths.
Three values can be changed: the reference date, a glider registration, and a number of months for currency calculations.
These fields are highlighted in yellow.
By default, around 500 flights are processed.
If you need more, you must change the limits on the 'Misc' page.
The higher the limit, the longer it takes to update results.
For large databases, you may want to turn off automatic updating in Tools → Cell Contents → Auto Calculate.
You then have to press the 'F9' key to recalculate everything.

**Database queries** are an advanced functionality.
They can answer (almost arbitrarily) complex questions, which are not covered by the standard statistics pages.
Explanations on how to use the query tables can be found on the worksheet.
The number of processed flights is also controlled by the limits entered on the 'Misc' page, just as for the Statistics pages.

## FAQs
**I have entered a lot of flights, and the last ones do not show up in the statistics.**\
To keep calculation time short, the number of processed database entries is limited to 500.
If you have more entries than that, increase the limits on the 'Misc' worksheet.
The higher the limit, the longer it takes to update results.
For large databases, you may want to turn off automatic updating in *Tools → Cell Contents → Auto Calculate*.
You then have to press the 'F9' key to recalculate everything.

**The spreadsheet feels very sluggish.**\
See above.
For large databases and/or slow computers, you may want to turn off automatic updating in *Tools → Cell Contents → Auto Calculate*.
You then have to press the 'F9' key to recalculate everything.

**The document is protected - does that prevent me from making changes?**\
You can still change anything you want!
All worksheets are protected to prevent unintentional changes to formulas.
If you know what you are doing and want to make modifications, simply unprotect each sheet (*Tools → Protect Document → Sheet*).
Remember to turn on protection after you have finished.
Please understand that I am unable to provide any support for modified spreadsheets.

**I have made some changes and they totally messed up the calculations. What shall I do?**\
Download the spreadsheet again from this website and copy and paste your data from your old document.

## Feedback and Donations
I appreciate your feedback
Please let me know if you have found a bug, or -even better- if you have fixed one.
If you like the spreadsheet, buy me a beer sometime.

## Copyright
This software is released under the MIT License.
