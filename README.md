# Nov-28-2021-L14ExercisesProblems
only in .txt

------------------------------------1000 RANDOM/COUNT NUMBER 6---------------------------------------

  #include <iostream>
  #include <array>
  #include <algorithm>
  #include <time.h>
  using namespace std;

  int main()
  {
  srand(time(0));
  int randomArr[1000], x = 0, i;
  for (int i = 0; i < 1000; i++)
  {
  randomArr[i] = rand() % 100 + 1;
  cout << randomArr[i] << "  ";

  if (randomArr[i] == 6) {
  x++;
  }
  else {
  continue;
  }
  }
  cout << "\n\nTotal occurence of number 6: " << x;
  }

------------------------------------FIND LARGEST NUMBER------------------------------------------

  #include <iostream>
  #include <array>
  #include <algorithm>
  using namespace std;

  int main()
  {
  int numbers[11];
  int i, n;

  cout << "Enter 10 numbers " << endl;

  //  store input from user to array
  for (i = 1; i < 11; i++) {
  cout << "Enter number " << i << ": ";
  cin >> numbers[i];
  }

  cout << "The numbers are: ";

  //  print array elements
  for (n = 1; n < 11; n++) {
  cout << numbers[n] << "  ";
  }

  // print largest number
  for(i = 1; i < n; i++)
  {
  if(numbers[0] < numbers[i]) // compare if number in index is less than the numbers user input.
  numbers[0] = numbers[i]; // make number in index as number of user input.
  }
  cout << "\n\nLargest number = " << numbers[0];
  }
  
------------------------------------FIND SMALLEST NUMBER------------------------------------------

  #include <iostream>
  #include <array>
  #include <algorithm>
  
  using namespace std;

  int main()
  {
  int numbers[11];
  int i, n;

  cout << "Enter 10 numbers " << endl;

  //  store input from user to array
  for (i = 1; i < 11; i++) {
  cout << "Enter number " << i << ": ";
  cin >> numbers[i];
  }

  cout << "The numbers are: ";

  //  print array elements
  for (n = 1; n < 11; n++) {
  cout << numbers[n] << "  ";
  }

  // print largest number
  for(i = 1; i < n; i++)
  {
  if(numbers[0] < numbers[i]) // compare if number in index is less than the numbers user input.
  numbers[0] = numbers[i]; // make number in index as number of user input.
  }
  cout << "\n\nLargest number = " << numbers[0];
  }
