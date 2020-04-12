# temperature_calculator
calculate different temperature scales 

Basic Requirements
Javascript

Create an express application using create-express-application.

Setup a database with one WEATHER table:

UID int

Output Scale varchar(30)

Output Temperature double

DateOfEntry DateTime

Calculations Page

Clicking 0 - 9 appends to the INPUT which is 0 by default

Clicking C clears the INPUT to 0 K

Clicking = calculates the input in Kelvin to Celsius and updates the OUTPUT

Clicking = initiates a POST request inserting the OUTPUT Temperature and the Output Scale to the CALCULATIONS table.

History Page

GET request that gets all records in WEATHER table

EDIT button makes the Output temperature editable

If clicked the EDIT button is replaced with a SAVE button

Clicking the SAVE button will initiate a PUT request updated the WEATHER table with the new Output Temperature value

Clicking the SAVE button will make the output temperature read-only again and bring back the EDIT button

DELETE button will initiate a DELETE request to delete that entry from the WEATHER table.

HTML

Calculate page

9 buttons numbered 1 - 9 arranged in a 3 x 3

1 button numbered 0

1 button labeled =

1 button labeled C

INPUT field that takes up the length of 3 buttons

OUTPUT field that takes up the length of 3 buttons

Rough Sketch:

I N P U T

7 8 9

4 5 6

1 2 3

0 C =

O U T P U T

History Page - GET request for all records in CALCULATIONS table

Display records in a readonly table, each record will have a

Date Of Entry

Output Temperature

EDIT button for each entry

DELETE button for each entry

CSS

Use to CSS animate the transition between the EDIT and SAVE button.
