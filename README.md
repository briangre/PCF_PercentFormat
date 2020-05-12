# PCF_PercentFormat
A PCF control that allows formatting of a decimal field as a percentage

This control will take either a decimal or float field type as input and convert the value to 
a formatted percentage display. There is an optional input parameter to either take the actual 
value and display with a '%':

     .65 == .65%

or you can set the useActual flag to false which will force a calculation to multiply the 
actual value by 100 for display and divide by 100 for storing the edited value:

     .65 == 65%

I tried to mimic the default model driven app behavior styling for the field, but it's 
possible I may have missed something. 
