# CalendarData

I've been developing a paper-based daily planner designed for individuals with attention-deficit issues and I needed a list of days that would work cleanly with InDesign. The output therefrom, calendar.txt, is a big fat tab-separated value file with information about each day from 1/1/2011 through 12/31/2021 generated inside Excel 2010 on a Mac. 

## Non-Obvious Fields

* dd - 2-digit day of month
* yyyy - 4-digit year
* mm - 2-digit Month
* mmm - 3-letter month
* mmmm - Full month name
* ww - 2-digit week of the year
* weekstart - Date of Sunday of the current week 
* weekend - Date of Saturday of the current week
* nextstart - Date of Sunday of next week
* nextend - Date of Saturday of next week
* nextmonth - 2-digit value of next month
* nextyear - 4-digit value of next year
* Fields "1" through "35" contain the day/date relationship needed to show a month in 5 rows of 7 seven days, with 1 corresponding to Sunday of Week 1 and 35 corresponding to Saturday of Week 5 (complete and correct through the first week of January 2013)
* usenholiday - U.S. Federal Holidays are correct and complete through 2020 using the data and nomenclature specified by the [U.S. Office of Personnel Management](http://www.opm.gov/operating_status_schedules/fedhol/)
* doy - 1-3 digit day of year
* diy - 3-digit number of days in the current year
* usennote - Other holidays in the U.S., including:
	* Valentine's Day, St. Patrick's Day, Father's Day, Mother's Day, Flag Day and Halloween through 2021
	* Mardi Gras and Easter (Western Church) through 2020
	* Rosh Hashanah through 2013
	* Notable U.S. Election Dates (through 2012)
	* Super Bowls through XLVIII in 2014
	* Olympic Games and FIFA World Cup opening dates through 2018
	* 11/11/11 and 12/12/12

## To-Do List

* day/date relationships for 2013-2022
* additional holiday columns for other countries (such as ukenholiday and ukennote)
* religious holidays separated into columns by religion (westchr, eastchr, judaism, islam)

## Future Additions, When Known

* Holidays for Western Christianity for 2021 and 2022
* Olympics for 2020 and 2022
* World Cup for 2022
* Super Bowls from 2015 through 2022

## Potential Uses

* Merge Documents in Office
* Data source for a Web App
* Build your Own Day Planner

## Trivia

Federal holidays roam around the calendar to avoid occurring on the weekend so the birthdays of two historical figures are rarely commemorated on the actual anniversaries of their births.

* Martin Luther King, Jr. was born on 1/15/1929 and will be celebrated on the 15th in 2018.
* George Washington was born on 2/22/1732 and will be celebrated on the 22nd in 2017.

## License

Copyright (c) 2011 Disruptive Ventures, Inc.

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

## Source code can be downloaded or forked on GitHub

If you want to add or revise this data, send me a push request...

* [https://github.com/jerry/CalendarData](https://github.com/jerry/CalendarData)