# Sept-27-2021-L7ExercisesProblems
only in .txt

//--------------------------MARK MY WORDS (COMPOUND CONDITION)--------------------------------

#include <iostream>
  
#include <string>

using namespace std;

void runProgramAgain();  //function to rerun program again if user wants to

int main(){
  
 int grade;
  
 char again; 
 
 do{ // to make program run again
 
 cout << "Enter a grade number to view the grade boundaries: ";
  
 cin >> grade;
 
if (grade >= 70 )
  
cout << "that is an A grade";
  
else if ( grade >= 60 && grade <= 69)
                                    
cout << "that is a B grade";
        
else if ( grade >= 50 && grade <= 59)
                                    
cout <<"That is a C grade";
        
else if ( grade >= 40 && grade <= 49)
                                    
cout <<"That is a D grade";
        
else if ( grade < 40)
  
cout <<"that is an F grade";
  
cout << endl;
  
cout << endl;
  
cout << "Would you like to run the program again? (y/n):";
  
cin >> again;
  
}while(again=='y');
  
cout << "Press any key to continue." << endl;
  
cin.ignore(1);
  
}

//--------------------------STARTING A BAND (NESTED-IF)--------------------------------
  
// Example program

#include <iostream>
  
#include <string>

using namespace std;
  
int main()
  
{
  
bool musicalFriend = true;
  
string friendPlaysGuitar = "guitar";
  
string friendPlaysDrum = "drums";
  
string strInput;
  
char input;
 
  
cout <<"Do you have a musical friend? y/n? ";
  
cin >> input;
  
if (input == 'n'){  //no condition made cuz its down below
  
}
  
else{
  
cout <<"Which instrument does your friend play? A guitar or drums? ";
  
cin >> strInput;
  
}
  
if (input == 'y' && musicalFriend == true){
  
if (strInput == friendPlaysGuitar || strInput == friendPlaysDrum){  //will identify if the user input matches the string in the variable.
  
cout << "Great we can start a band!";
  
}else{
  
cout << "Im only asking if the friend can play a guitar or drum. I guess i'll consider it. The friend will play the " << strInput << endl;   //will only apply if user
  
input doesnt match string
  
}
  
}else{
  
cout << "We cant form a band. Sadge. ";
  
}
}
     

//--------------------------KILLING TIME (NESTED-IF)--------------------------------
// Example program

#include <iostream>
  
#include <string>

using namespace std;
  
int main()
{
  
int money = 5; 
  
int minsNeededForFriendToCome = 15;
  
cout << "It is 12 AM in the midnight. You are in Dubai Mall waiting for a friend. You suddenly recieved a text message from your friend." << endl;
  
cout <<"\n\n";
  
cout << "The message said that";
  
if (minsNeededForFriendToCome > 14) {
  
if (money >= 5) {
  
cout << " your friend is arriving in 15 minutes or maybe even more than that so might as well buy a coffee." << endl;
  
} else {
  
cout << " your friend is arriving in 15 minutes or so, and I dont have enough money to buy a coffee." << endl;
  
cout <<"\n\n";
  
cout << " So Im gonna go for a walk around the mall." << endl;
  
}
  
} else {
  
cout << " your friend will arrive in less than 15 minutes. Might as well sit in the food court and wait." << endl;
  
}
}

//--------------------------EARTHQUAKE DESCRIPTOR (NESTED-IF)--------------------------------
// Example program
  
#include <iostream>
  
#include <string>

using namespace std;
  
int main() {
    
double input; 
  
cout << "WARNING!!! AN EARTHQUAKE HAS BEEN DETECTED IN YOUR AREA. PLEASE ENTER THE MAGNITUDE TO CALCULATE THE DESCRIPTOR OF THE EARTHQUAKE: ";
  
cin >> input;
  
if (input >= 10){
  
cout << "Magnitude " << input << ":" << " DESCRIPT AS METEORIC";
}
  
else{
  
    if (input >= 8.0 && input < 10.0){
                                      
cout << "Magnitude " << input << ":" << " DESCRIPT AS GREAT";
                                        
}
                                        
else{
                                        
    if (input >= 7.0 && input < 8.0){
                                     
        cout << "Magnitude " << input << ":" << " DESCRIPT AS MAJOR";
                                                
}
                                                
else{
                                                
    if (input >= 6.0 && input < 7.0){
                                     
        cout << "Magnitude " << input << ":" << " DESCRIPT AS STRONG";
}
                                                
else{
                                                
    if (input >= 5.0 && input < 6.0){
                                     
        cout << "Magnitude " << input << ":" << " DESCRIPT AS MODERATE";
                                                
}
                                                 
else{
                                                
    if (input >= 4.0 && input < 5.0){
                                     
        cout << "Magnitude " << input << ":" << " DESCRIPT AS LIGHT";
                                               
}
                                                
else{
                                                
    if (input >= 3.0 && input < 4.0){
                                     
        cout << "Magnitude " << input << ":" << " DESCRIPT AS MINOR";
                                                
}
                                                
else{
                                                
    if (input >= 2.0 && input < 3.0){
                                     
        cout << "Magnitude " << input << ":" << " DESCRIPT AS VERY MINOR";
                                                
}
                                                
else{
                                                
    cout << "Magnitude " << input << ":" << " DESCRIPT AS MICRO";
                                            
}}}}}}}}}
