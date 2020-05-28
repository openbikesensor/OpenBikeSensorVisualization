# Recordings
This directory holds some example files to test the visualization.

Every file looks like that.  
It should contain one header line:  
*Date;Time;Latitude;Longitude;Course;Speed;Right;Left;Confirmed*  

And then many, many lines with content like this:  
23.05.2020;21:39:30;48.783449;9.158504;210.470;14.8160;255;255;0  
*Date* and *Time* should be self explaining. Time it UTC, though.  
*Latitude* and *Longitude* are the GPS values.  
*Course* is the orientation, i.e. the geographic direction  
*Speed* is the speed in km/h  
*Right* and *Left* are the distance measurements to the right and left in cm, 255 is the max value, it can't measure more than 255cm  
*Confirmed* is a boolean value, usually 0, but when the button on the handle bar is pressed, it turns to 1  
