# Leap-year-
#I have written a program of leap year in Apex Language
Integer Year=2200;

if(Math.mod(Year,4)==0)
{
    if(Math.mod(Year,100)==0)
    {
        if(Math.mod(Year,400)==0)
        {
               system.debug('Leap Year'); 

        }
        else
        {
               system.debug('Not Leap Year'); 

        }
        
    }
    else
    {
           system.debug('Not Leap Year'); 

    }
}
else
{
   system.debug('Not Leap'); 
}

