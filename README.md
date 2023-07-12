# LENGHT-OF-STRING-WITHOUT-STRLEN-IN-C-

INPUT

      #include <stdio.h>
      main()
      {
    	char s[15];
	    int i=0,lenght=0;
	    printf("Enter the string:");
	    gets(s);
	    while(s[i]!='\0')
	    {
		  lenght++;
		  i++;
	    }
	    printf("Lenght of the string is %d\t",lenght);
      }

OUTPUT

      Enter the string:abcd efgh ijkl
      Lenght of the string is 14
