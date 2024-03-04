Reverse Polish Notation Calculator
Feet Inches Sixteenth Meter Millimeter
Adding machine like Paper tape stack display
parsFlat function for floating point error control(verify?). Eventually 
 goes to 0,1,NaN from rounding on very large or very small numbers.
EventListener to enable keyboard shortcuts.

to add -> press '3' press 'Enter' press '2' press '+'
'fis' mode would return  '5Ft'
'mm' mode would return  '5mm'
'units' mode would return '5.'

In fis or mm mode numbers without units get a decimal point, 
No decimal point first 2 digits in 'fis'mode are treated as feet, 3 and 4 digit 
 numbers are treated as inches and sixteenths- 308(3.5")=>3in8sx, 5 and more digits
 are treated as ftinsx- 10308(1'3.5")=>1ft3in8sx

double unit operators use the stack as the first operand and the display as the second operand.
single unit operators use the display as the operand.

y**x  press '3.' press 'Enter' press '2.' press 'y**x' returns '9.'
for 'fis' and 'mm' modes y**x takes '3.345 ft' and '2.' and returns 3.345ft**2
x**2 returns the answer to (3.345)^2ft**2

sin cos tan inv use degrees for input and return. In 'fis' and 
'mm' mode use decimal point.

To convert a number on the stack use 'ft'(or in,sx,etc)(f key,i key, etc) and
then 'Enter'. 

