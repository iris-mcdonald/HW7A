# HW7A
Create a web page called HW7A, with an embedded JavaScript
The script will have 2 functions, startProcess and GetVolume

GetVolume will accept 3 variables for calculating volume (Length, Width, Height)
It will define a variable called “Result” to hold the value of the calculated volume(Length * Width * Height)

startProcess will declare 3 variables (Length, Width, Height)
Set Length, width, and Height to any integer values.

Use a FOR loop inside startProcess to iterate i=1-10
For each iteration I {
	Length = i + 2;
               Width =  i + 3;
	Height = i + 4;
It will call GetVolume and pass it the required parameters

Inside the FOR loop, use IF-ELSE statements for the following:
If volume is 60-70 document.write(‘Small Volume: ’ + volume);
If volume is 71-80 document.write(‘Medium Volume: ’ + volume);
If volume is 81-90 document.write(‘Large Volume: ’ + volume);
If volume is 91-100 document.write(‘Extra Large Volume: ’ + volume);
}
