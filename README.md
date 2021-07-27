# American-Express-Questions

Scenario 1:  
Declare one 15 digit string card number, 
create an output which will print first 11 chars of that card number. 
Use stringutils class.

import stringutils

string card_number = "1231321321312";

void first_eleven(String card_number){
	String sliced_number = card_number.substring(0, 11);
	System.out.println(sliced_number);
}


Scenario 2: Write a program to display only the domain part of the email. 
emailadress ="james@yahoo.com", so output should be yahoo.com and convert the domain to upper case

emailaddress = "james@yahoo.com"

void get_domain(String email_address){
	System.out.println(email_address.substring(email_address.indexOf('@') + 1))).toUpperCase())
}

Scenario 3: Write a Java Program to remove all white spaces from a string with using regex, 

String str_val = "This     is my f irst program" 

void remove_white_space(String string_value){
	System.out.println(string_value.replaceall("\\s", ""));
}

Scenario 4: 
write syntax to create an empty table from an existing table. 
customer is the existing table and it is having cust id and salary and new table name customer_new

Create table customer_new as SELECT cust_id, salary FROM customer
