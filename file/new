#include <base.hpp>

int kernel_main()
{
	char *src =scr2; //(char *)0x000b8000L;
	
	int x=0;
	int y=0;
	int n=0;
        char *p1=c_hello();
        char *p2=c_hello();
        ostring s1; // define a os string
        ostring s2; // define a os string
        s1 *= 150;  // alocate 150 bytes
        s2 *= 150;  // alocate 150 bytes
        s1 &= p1;   //copy string
        s1 += p2;   //comcat string
        s2 &= toString(s1);  //copy string
	clear();
	locate(10,10);
	
	
		print(toString(s1));
		

	
return 0;	
}


