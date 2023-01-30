# PowerBI-Dashboard

Percentange of presence, Work from Home and Sick Leave using PowerBI dashboard

About the dataset :

I have a dataset from the HR of a company which is the attendance sheet of all the employees. The file is in the form of 
xlsx format and contains 4 sheets. The three sheets are the data for April, May, and June, and another sheet 
is the attendance key which is useless to me. In all three sheets, the first column is the company name which is Atliq and 
there is a subcolumn namely Employee code and Name of the Employee. from the second onward column is the date of the month 
which shows that particular date the employee is working, or not.

The Attendance Key as per given sheet is as below:
ATTENDANCE KEY	
P	Present 
PL	Paid Leave 
SL	Sick Leave 
HPL	Half day PL 
HSL	Half day SL
WFH	Work from home 
FFL	Floting festival leave 
HFFL	Half Day Floting festival leave 
BL 	Birthday Leave 
LWP	Leave without pay
HLWP	Half day Leave without pay
BRL 	Bereavement Leave
HBRL 	Half Bereavement Leave
HWFH	Half Work From Home
WO	Weekly Off
HO	Holiday Off
ML	Menstrual Leave
HML	Half Day ML



Insights from the dashboard:

In this project, I first imported our data into PowerBI Dekstop from my system.
Then the one sheet of data is transformed into a powerBI query and perform some operations.
then we create a function for this sheet which will be used to call this function on the other sheets.
and then we will invoke this function to all other sheets which will give all the data in a single powerBI file.
We will create some measures to analyze for presence, WFH and SL percentage of all employees for selected months.



Presence Percentage:
1) The presence percentage for the may month is less than 90 %.
2) The presence percentage for April is approx 94 % which is higher than the May and June month.
3) The presence percentage is lower on Friday

WFH Percentage:
1) The WFH percentage is also highest in May month.
2) Most of the employee takes WFH on Friday.

Sick Leave Percentage:

1) Most employee takes sick leave on Monday.
2) Sick leave for May is higher compared to April and June month.


Conclusion:
Based on the above insights it can be concluded that there may be some reason in May month most people are taking sick leave and also prefer to work as WFH.
