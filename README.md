# programming-2
Public class Divisible
{
Public static void main (String [] args)
               {
                                int count = 0;
   for (int i=2; i< 100000; i = i + 1)
                                {
	if (i%9 == 0)   // checking if the number is evenly divisible or not
	{
	Count = count + 1;
}
if ( i%13 == 0)
{
	Count = count + 1;
}
if (i%27 == 0)
{
	Count = count + 1;
}
if (i%81 == 0)
{
	Count = count + 1;
}
	else
	{
                System.out.println (“Try next number!!!”);
              }
                               }
                 System.out.println (“Number of counts =” + count); //Result displayed on the screen.
            }
}

