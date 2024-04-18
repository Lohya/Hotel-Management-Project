                                                    HOTEL MANAGEMENT SYSTEM:



An application that was developed by the management system for a hotel with the following modules using structures, pointers to structure variables, passing structure pointers to function.
Designed the program using these factors:
1.	Get availability of the rooms in hotel.
2.	Features of room in the hotel.
3.	Collect the details of the customer.
4.	Based on the interest of the customer room should be allocated.
5.	Again, deallocate the room on the date the customer is leaving.
6.	Finalize the bill of the customer including restaurant bill.
As we know that, “necessity is the mother of invention”, so in today’s challenging world, every system is developed and launched by use of computer software and programming. As a customer and hotel are two related terms of business field, there should be proper way of management. The title of the project is related to the hotel i.e. “HOTEL MANAGEMENT SYSTEM”.  Hotel management deals with basic records of customers and staff, room details, restaurant details, report etc. of the hotel.




Data Flow Diagrams:

![Alt text](https://github.com/Lohya/Hotel-Management-Project/blob/main/Flow%201.png)



![Alt text](https://github.com/Lohya/Hotel-Management-Project/blob/main/Flow%202.png)


![Alt text](https://github.com/Lohya/Hotel-Management-Project/blob/main/Flow%203.png)


Algorithm:



step 1:- start

step 2:-  declare a structure customer 	name,  address, proof, phone number, id.no

step 3:- declare functions roombook containing pointers *p,*q,*r

step 4:- declare function custdetails

step 5:- declare function billing

step 6:- read no of rooms left T,T1,T2,choice

step 7:- print no. of rooms left of each type

step 8:- read choice
             pass choice into roombook function
             
step 9:- roombook function

step 10:-print the choice

step 11:-while(*p!=0)

              {
              
                  if(choice==1)
                  
                 {
                 
                   if(*q!=0)
                   
                    {
                    
                          print rooms available
                          
                          *q--;
                          
                          search=1;
                          
                          break;
                          
                     }
                     
                   else if(*q==0)
                   
                       print no room available
                       
                 }
                 
                 else if(choice==2)
                 
                 {
                 
                     if(*r!=0)
                     
                    {
                    
                        print rooms available
                        
                        *r--;
                        
                        search=2;
                        
                        break;
                        
                    }
                    
                    else
                    
                      {
                      
                              print room not availabe;
                              
                       }
                       
                    }
                    
                    else 
                    
                        print no room of such type;
                        
                 }
                 
                  if(*p==0)
                  
                       print no room available;
                       
                   if(search==1||search==2)
                   
                               *p--;
                               
                 }
                 
step 12:- read name of the customer 

step 13:- read address

step 14:- read phone number

step 15:- read proof and id number of the proof  of the customer

step 16:- read number of items taken

step 17:- read cost of each item

step 18:- calculate total cost of items taken

                 for(j=0;j<n;j++)
                 
                  {
                  
                       total=c[j];
                       
                   }
                   
step 19:-read number of days to be stayed

step 20:- if(choice==1)

                    roombill=1000*D;
                    
                else if(choice==2)
                
                    roombill=2500*D;
                    
step 21:- read tax percentage

step 22:- calculate restaurant bill

                     restbill=total+(total*taxp/100);
                     
step 23:- calculate total bill

                 tbill= resbill + roombill; 
                 
step 24: print total bill

