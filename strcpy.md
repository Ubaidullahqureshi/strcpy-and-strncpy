#include<iostream> 							// Header File 
#include<string.h>
using namespace std;
	int main(){
	
	char string1 [ 15 ] = "Ubaidullah1";				//String Initilaization .
	char string2 [ 15 ] = "Ubaidullah2";
		
	cout << " Before the copy : '\n";
	cout << "string1 : \t" << string1 << '\n';
	cout << "string2 : \t" << string2 << '\n';
	
	// Copy the whole string 
	strcpy ( string2 , string1 );   					// Copy string 1 into string 2   logic
		
	cout << " After the copy : '\n";
	cout << "string1 : \t" << string1 << '\n';
	cout << "string2 : \t" << string2 << '\n';
	
	// Copy three character of the string 1 into string 
	strncpy ( string2 , string1 , 3 );
	cout << "Strncpy ( string3 , string1 , 3) = " << string2;
		
		
	
	return 0;
		  
	}
