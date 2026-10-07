# CODE-10-07-26
// C++ SYNTAX
#inclue<iostream> // give access to std::cout, std::cin
int main(){
  std::cout<<"hello,world!"<<std::endl;
  return 0;
}

// Variables, types, and I/0
#inclue <iostream>
#include <string>

using namespace std,

int main(){
// Declaring the variables of different types--
 int age = 20;
 double price = 30.60;
 float weight = 80.5f;
 char grade = 'b';
 bool isStudent = true;
 string name ="Bench";

  // Getting input using cout---
cout<<"Name: "<< name<<endl;
cout<<"Age: "<< age<<endl;
cout<<"Price: "<< price<<endl;
cout<<"Grade: "<< grade<<endl;
cout<<"Is Student? "<< isStudent<<endl;

//k Getting input using cin---
string userCity;
cout<<"\nEnter your city: ";
cin>> userCity; // read one word (stop at whitespace)
cout<<"\nYou live in; "<userCity<<endl;

//----Reading a full line(including spaces)
cin.ignore();// clears leftover newline character from previous cin 
string fullSentence;
cout<<"Enter a sentence about yourself: ";
getline(cin, fullSentence); // reads the emtire line
cout<<"You said: "<<fullSentence<<endl;
return 0;

}

//  Control Flow(if/else, switch,loops)
#include <iostream>
using namespace std;

int main()
 // if/else if/else condition
 int score;
 cout<<"Enter your exam score: ":
 cin>>score;

 if(score>=90){
   cout<<"Grade: A"<<endl;
 }else if(score>=80){
   cout<<"Grade: B"<<endlL;
 }else if (score>=70){
   cout<<"Grade: C"<<endl;
 }else(
   }
 }

intv day;
cout<<"\nEnter a day number (1-7):";
cin>>day;

switch (day)
 case 1: cout<<"Monday"<<endl; break;
 case 2: cout<<"Tuesday"<<endl; break;
 case 3: cout<<"Wednesday"<<endl; break;
 case 4: cout<<"Thursday"<<endl; break;
 case 5: cout<<"Friday"<<endl; break;
 case 6: cout<<"Saturday"<<endl; break;
 case 7: cout<<"Sunday"<<endl; break;
 default : cout<<"Invalid day"<<endl; break;
}

// for loop
cout<<"\nCounting 1 to 5 with a for loop: "<<endl;
for (int i =i; i<=5; i++){
  cout<,i<<"";
}
cout<<endl;

// while loop
cout<<"\nCounting down from 5 with a while loop:"<<endl:
int n =5;
while(n>0){
  cout<< n <<" ";
  n--;
   }
   cout<<endl;

// do while loop
cout<<"\nDo while example: "endl;
int x = 0;
do{
  cout<<"x = "<< x <<endl;
  x++;
}while (x < 3);

// Break and comtinue
cout<<"\nSkipping 3 usimg continue, stopping at 7
using break : "endl;
for(int i =1; i<=10; i++) {
  if(i  == 3) continue;//skip this iteration
  if(i == 7) break; // exit the loop entirel
  cout<< i << " ";
}
cout << endl; 

return 0;
}
 
 
 











