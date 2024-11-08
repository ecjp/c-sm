#include<stdio.h>
main()
{void print1( );
	printf("-----\n");
	print1( );
	printf("-----\n");
}
void print1( )
{void print2( );
	printf("*****\n");
	print2( );
	printf("*****\n");
}
void print2( )
{printf("#####\n");}
