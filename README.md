#include <stdio.h>

int main ()
{
	float c, fh;
	printf ("masukkan tempratur dalam celcius :", c, fh);
	scanf ("%f", &c);
	
	fh = (c * 9/5 + 32);
	
	printf ("jadi %.1f celcius adalah %.1f farhrenheit\n", fh);
	
	return 0;
}
